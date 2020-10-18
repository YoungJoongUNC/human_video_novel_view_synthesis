# Multi-View Human Action (MVHA) Dataset
## Official repository of "Rotationally-Temporally Consistent Novel View Synthesis of Human Performance Video" (ECCV 2020 Spotlight) <br/> [[Paper (ECCV)](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123490375.pdf)]
<br/>

[Youngjoong Kwon](https://youngjoongkwon.com/), [Stefano Petrangeli](https://research.adobe.com/person/stefano-petrangeli/), [Dahun Kim](https://mcahny.github.io/), [Haoliang Wang](https://research.adobe.com/person/haoliang-wang/), [Eunbyung Park](https://www.cs.unc.edu/~eunbyung/), [Viswanathan Swaminathan](https://research.adobe.com/person/vishy-swaminathan/), [Henry Fuchs](http://henryfuchs.web.unc.edu/).




## Dataset Overview

<img src="./images/supple_dataset_overview (1).png" width="800"> <br/>

We provide multi-view human action (MVHA) dataset consists of RGB and binary mask (foreground/background) which are rendered from multiple views. For now, we provide images that are generated from 18 views along the azimuth with 20-degree interval.

## Download Instructions

a. Before downloading the dataset, first use the following command:

```
pip install gdown
conda install zip unzip
```

b. If you want to download 256x256 dataset, use the following command:

```
gdown https://drive.google.com/uc?id=1FmxdgfQmjsGySNyWLZ_WaCN9pQB0Gc7o
```

After the download, you will see a zip file, e.g. xxx.zip
unzip the zip file using the following command:

```
unzip xxx.zip
```

After the unzip process, you will see the rgb image folder and mask image folder(foreground/background --> foreground is denoted as 1 and background as 0)

c. If you want to download 512x512 dataset, use the following command:

```
gdown https://drive.google.com/uc?id=1V4UbHXAAmdKM9v63DvP-_kmp1NlV7skw
```

After the download, you will see the zip file, ex) xxx.zip
unzip the zip file using the following command:

```
unzip xxx.zip
```

Every image is 4 channel which is: RGB+mask (foreground/background -> foreground is denoted as 1 and background as 0)


## Citation

If you use this dataset in your research, please cite following two papers.

Rotationally-Temporally Consistent Novel View Synthesis of Human Performance Video (ECCV 2020) <br/>
```bibtex
@inproceedings{kwon2020rotationally,
  title={Rotationally-Temporally Consistent Novel View Synthesis of Human Performance Video},
  author={Kwon, YoungJoong and Petrangeli, Stefano and Kim, Dahun and Wang, Haoliang and Park, Eunbyung and Swaminathan, Viswanathan and Fuchs, Henry},
  booktitle={Proceedings of the European Conference on Computer Vision (ECCV)},
  year={2020}
}
```
<br/>
Rotationally-Consistent Novel View Synthesis for Humans (ACM MM 2020) <br/>

```bibtex
@inproceedings{kwon2020rotationally,
  title={Rotationally-Consistent Novel View Synthesis for Humans},
  author={Kwon, Youngjoong and Petrangeli, Stefano and Kim, Dahun and Wang, Haoliang and Fuchs, Henry and Swaminathan, Viswanathan},
  booktitle={Proceedings of the 28th ACM International Conference on Multimedia},
  pages={2308--2316},
  year={2020}
}
```


## License
The Multi-View Human Action (MVHA) dataset is released under the CC-BY-NC license (https://creativecommons.org/licenses/by-nc/4.0/)


## Contact

If you have any questions regarding the repo, please contact Youngjoong Kwon (youngjoong@cs.unc.edu) or create an issue.

