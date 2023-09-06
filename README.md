# web-scraping

## Scraping Process

First scrap all brand links, then in every brand link scrap all page links, then in every page link scrap every phone link, then in every phone link scrap every phone features.

## Data Cleaning and Preprocessing

All scrapped data is in string format so need to extract numeric values, datetime values and boolean values, then fill nan values etc.

## About Dataset

This dataset contains phone features including price of popular brands. Every phone in this dataset continues to be manufactured. Does not include discontinued phones.

- <ins>phone_name</ins>: name of the phone
- <ins>brand</ins>: brand of the phone
- <ins>os</ins>: operating system of the phone
- <ins>inches</ins> size of the phone screen as inches
- <ins>resolution</ins>: resolution of the phone screen
- <ins>battery</ins>: battery capacity of the phone
- <ins>battery_type</ins>: battery type of the phone
- <ins>ram(GB)</ins>: ram of the phone as GB
- <ins>announcement_date</ins>: the date of the announcement of the phone
- <ins>weight(g)</ins>: weight of the phone as gram
- <ins>storage(GB)</ins>: storage capacity of the phone as GB
- <ins>video_720p</ins>: does phone camera has 720p feature
- <ins>video_1080p</ins>: does phone camera has 1080p feature
- <ins>video_4K</ins>: does phone camera has 4K feature
- <ins>video_8K</ins>: does phone camera has 8K feature
- <ins>video_30fps</ins>: does phone camera has 30fps feature
- <ins>video_60fps</ins>: does phone camera has 60fps feature
- <ins>video_120fps</ins>: does phone camera has 120fps feature
- <ins>video_240fps</ins>: does phone camera has 240fps feature
- <ins>video_480fps</ins>: does phone camera has 480fps feature
- <ins>video_960fps</ins>: does phone camera has 960fps feature
- <ins>price(USD)</ins>(USD): price of the phone as USD

### NOTE: The purpose of this dataset is training and practice. It can never be used for commercial purposes.
