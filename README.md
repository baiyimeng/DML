# DML
[![arXiv](https://img.shields.io/badge/arXiv-2306.17426-red.svg)](https://arxiv.org/abs/2306.17426)

This is the pytorch implementation of our paper at CIKM 2023:
> [Leveraging Watch-time Feedback for Short-Video Recommendations: A Causal Labeling Framework](https://arxiv.org/abs/2306.17426)
> 
> Yang Zhang, Yimeng Bai, Jianxin Chang, Xiaoxue Zang, Song Lu, Jing Lu, Fuli Feng, Yanan Niu, Yang Song.

## Usage

⚠️ **Due to company policies, the code associated with this paper is not publicly available**.

However, the core component of DML—the WPR label (also known more broadly as **Watch Time Distribution**, or **WTD**)—can be viewed as an extension of D2Q, enhanced with adaptive binning. For reference, we encourage readers to consult the following D2Q implementations:

- [Official D2Q Implementation](https://github.com/MorganSQ/Ks-D2Q)  
- [Alternative D2Q Implementation](https://github.com/hyz20/D2Co/blob/main/src/preprocessing/cal_baseline_label.py)



## Citation
```
@inproceedings{10.1145/3583780.3615483,
author = {Zhang, Yang and Bai, Yimeng and Chang, Jianxin and Zang, Xiaoxue and Lu, Song and Lu, Jing and Feng, Fuli and Niu, Yanan and Song, Yang},
title = {Leveraging Watch-time Feedback for Short-Video Recommendations: A Causal Labeling Framework},
year = {2023},
isbn = {9798400701245},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3583780.3615483},
doi = {10.1145/3583780.3615483},
booktitle = {Proceedings of the 32nd ACM International Conference on Information and Knowledge Management},
pages = {4952–4959},
numpages = {8},
keywords = {recommender system, debiasing, causal recommendation},
location = {Birmingham, United Kingdom},
series = {CIKM '23}
}
```
