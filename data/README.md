# 📦 Dataset for This Project

This project uses the following dataset, which is hosted on Google Drive due to size limitations on GitHub.

## 🔗 Download Link

[📥 Download dataset (Google Drive)](https://drive.google.com/uc?id=YOUR_FILE_ID)

> Note: You must manually unzip the dataset after downloading.

## 📂 Contents

The dataset contains:

- `train.csv`: training examples
- `test.csv`: test set
- `images/`: folder with images (if applicable)

## 💡 Tips

You can also download it using `gdown`:

bash
pip install gdown

gdown https://drive.google.com/uc?id=YOUR_FILE_ID
unzip ProjectA_dataset.zip





## #####################

And for each dataset used in project, we need provide these additional details:

## Dataset Name
Twitch

## Description
This is a dataset of users consuming streaming content on Twitch. We retrieved all streamers, and all users connected in their respective chats, every 10 minutes during 43 days.

## Basic statistics
    100k	full
    Users:	100k	15.5M
    Streamers (items):	162.6k	465k
    Interactions:	3M	124M
    Time steps:	6148	6148
## Metadata
Start and stop times are provided as integers and represent periods of 10 minutes. Stream ID could be used to retrieve a single broadcast segment from a streamer (not used in our work).
    User ID (anonymized)
    Stream ID
    Streamer username
    Time start
    Time stop
## Example
    1,34347669376,grimnax,5415,5419
    1,34391109664,jtgtv,5869,5870
    1,34395247264,towshun,5898,5899
    1,34405646144,mithrain,6024,6025
    2,33848559952,chfhdtpgus1,206,207
    2,33881429664,sal_gu,519,524
    2,33921292016,chfhdtpgus1,922,924
  
## Download link
See our data folder containing all Twitch files. The file full_a.csv.gz contains the full dataset while 100k.csv is a subset of 100k users for benchmark purposes. The code is available in our Github repository.

## Citation
Please cite the following if you use the data:

Recommendation on Live-Streaming Platforms: Dynamic Availability and Repeat Consumption
Jérémie Rappaz, Julian McAuley and Karl Aberer
RecSys, 2021