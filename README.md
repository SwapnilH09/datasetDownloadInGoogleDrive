# datasetDownloadInGoogleDrive

## By pass the limitations of RAM for your machine learning projects
Most the ML projects require large RAM which is not mostly available to everyone. Like, in my case, I am working with Microsoft Malware Detection dataset whose train-set size is 200 GiB in total. It is impossible for anyone to have a RAM of this size at their disposal. So, we turn to cloud services. 
I decided to use my google drive as my active RAM for my project. The only bottleneck in this procedure is that you will need that amount of storage in your google drive. In my case, our college provides us with google account which has enough storage for my purpose. 

## Download publically available datasets using kaggle apis directly into google drive.
This IPython notebook contains script to download kaggle datasets using apis and saving(unzip the dataset in your drive) the dataset into google drive. Further, it also includes script to fetch files, folders from google drive into colab notebook. 

## use storage space in your google drive as your working RAM for machine learning projects
This can be done very easily, just by providing the path to the file/directory, after providing with a working connection to google drive from your colab notebook.

### requirements
1. kaggle credentials
2. memory in google drive (space equivalent to dataset after unzipping)
3. Python 3.0+
4. general python libraries

