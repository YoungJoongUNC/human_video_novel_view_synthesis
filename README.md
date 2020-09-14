# Multi-View Human Action (MVHA) Dataset
## Official repository for <br/> "Rotationally-Temporally Consistent Novel View Synthesis of Human Performance Video" (ECCV 2020 Spotlight) and <br/> "Rotationally-Consistent Novel View Synthesis for Humans" (ACM MM 2020) <br/>[[Paper (ECCV)](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123490375.pdf)]
<br/>

[Youngjoong Kwon](https://youngjoongkwon.com/), [Dahun Kim](https://mcahny.github.io/).

## Dataset

a.Before downloading the dataset, first use the following command:

```
pip install gdown
conda install zip unzip
```

b.

If you want to download 256x256 dataset, use the following command:

```
gdown https://drive.google.com/uc?id=1FmxdgfQmjsGySNyWLZ_WaCN9pQB0Gc7o
```

After the download, you will see a zip file, e.g. xxx.zip
unzip the zip file using the following command:

```
unzip xxx.zip
```

After the unzip process, you will see the rgb image folder and mask image folder(foreground/background --> foreground is denoted as 1 and background as 0)

c.

If you want to download 512x512 dataset, use the following command:

```
gdown https://drive.google.com/uc?id=1V4UbHXAAmdKM9v63DvP-_kmp1NlV7skw
```

After the download, you will see the zip file, ex) xxx.zip
unzip the zip file using the following command:

```
unzip xxx.zip
```

Every image is 4 channel which is: RGB+mask (foreground/background --> foreground is denoted as 1 and background as 0)


## Citation

If you use this dataset in your research, please cite following papers.

Rotationally-Temporally Consistent Novel View Synthesis of Human Performance Video (ECCV 2020)
Rotationally-Consistent Novel View Synthesis for Humans (ACM MM 2020)


## Contact

If you have any questions regarding the repo, please contact Youngjoong Kwon (youngjoong@cs.unc.edu) or create an issue.

