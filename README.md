# This whole repo is against Google Colab policy and you shouldn't be using it.
> **Why are hardware resources such as T4 GPUs not available to me?**
The best available hardware is prioritized for users who use Colaboratory interactively rather than for long-running computations. Users who use Colaboratory for long-running computations may be temporarily restricted in the type of hardware made available to them, and/or the duration that the hardware can be used for. We encourage users with high computational needs to use Colaboratory’s UI with a local runtime.
Please note that using Colaboratory for cryptocurrency mining is disallowed entirely, and may result in being banned from using Colab altogether.

<sub>Source: https://research.google.com/colaboratory/faq.html</sub>

# Torrent To Google Drive Downloader and Google Drive to S3 Uploader using Google Colab
Simple notebook to stream torrent files to Google Drive and then upload to S3 bucket using Google Colab.

<a href="https://colab.research.google.com/github/imasimali/torrent-gdrive-s3-colab/blob/main/torrent-gdrive-s3-colab.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>


### Tutorial
Click the badge which says 'Open in Colab' and follow directions there.

### What is the purpose of it?
1. Because of Google Servers' speed, I downloaded 12GB of a file and the average speed was 60MBPS.
2. Because it is in the cloud, by that I mean I can access it anywhere on my phone, tablet, etc without copying files around
3. Instead of manually downloading the files from google drive and uploading them to s3. You can use the cloud to automate the task.

### Frequently Asked Questions
1. **How to get more disk space**:

    > Go to Runtime -> Change Runtime and give GPU as the Hardware Accelerator.  
You will get around 384GB to download any torrent you want.

2. **Downloading missing files without re-downloading whole torrent**: If somehow some files are missing try to re-download torrent. Fastresume will check files.

3. **What else we can do with S3?**: You can also download files to google drive or change the bucket's ACL using the documentation provided on [AWS_Boto3](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html)


Special Thanks to [FKLC](https://github.com/FKLC) for providing Torrent to Google Drive Notebook.
