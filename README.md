# Bilibili-TSC-Dataset
bilibili-tsc-dataset
## Paper Title
Video Content Classification Using Time-Sync Comments and Titles
## Explain
Time-Sync Conment(TSC)
This dataset is collected from the https://www.bilibili.com/. It contains video information CSV files and TXT files. 
### video information csv
To make sure the data is representative, the data of the top 100 videos on the website was weekly crawled. the information of 15,032 videos and 12,080,313 TSCs are collected. This dataset covers 8 video areas, including Animation, Kichiku, Knowledge, Life, Fashion, Dance, Music and Game. The information of the videos includes title, URL, video hits, number of TSCs, creator ID and ranking scores, and the videos are available from URLs.
### tsc txt
The TSCs are stored as TXT file withs the first column time and the second column comments.The file name is 'av number_bv number' corresponding to the video.The video can be accessed at https://www.bilibili.com/video/ + 'bv number'
