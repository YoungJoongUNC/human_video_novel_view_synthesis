# Multi-View Human Action (MVHA) Dataset
## Official repository of "Rotationally-Temporally Consistent Novel View Synthesis of Human Performance Video" (ECCV 2020 Spotlight) <br/>[[Paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123490375.pdf)]
<br/>

[Youngjoong Kwon](https://youngjoongkwon.com/), [Dahun Kim](https://mcahny.github.io/).

1.Before downloading the dataset, first use the following command:

pip install gdown
conda install zip unzip

2.
- If you want to download 256x256 dataset, use the following command:

gdown https://drive.google.com/uc?id=1FmxdgfQmjsGySNyWLZ_WaCN9pQB0Gc7o

-after the download, you will see the zip file, ex) xxx.zip
unzip the zip file using the following command:

unzip xxx.zip

-after the unzip, you will see the rgb image folder and mask image folder(foreground/background --> foreground is denoted as 1 and background as 0)

3.
- If you want to download 512x512 dataset, use the following command:

gdown https://drive.google.com/uc?id=1V4UbHXAAmdKM9v63DvP-_kmp1NlV7skw

-after the download, you will see the zip file, ex) xxx.zip
unzip the zip file using the following command:

unzip xxx.zip

-every image is 4 channel which is: RGB+mask (foreground/background --> foreground is denoted as 1 and background as 0)
