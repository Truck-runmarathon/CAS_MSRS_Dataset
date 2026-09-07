# CAS_MSRS_Dataset
Multi-UAV Collaborative Remote Sensing Reconstruction Dataset



## Dataset 

**Baidu Netdisk download link:**  
**Dataset:** MRSRdataset
**Link:** [Baidu Cloud / Baidu Netdisk (https://pan.baidu.com/s/1X4XIZI9xWV5DNgByIfw2IA?pwd=4xt8) ](https://pan.baidu.com/s/1X4XIZI9xWV5DNgByIfw2IA?pwd=4xt8) 
**Access Code:** `4xt8`

# MRSRdataset Data Directory Structure

Below is an example of the expected directory structure for the `MRSRdataset`:

```text
MRSRdataset/

├── village
├──── cam.yaml                 # Camera parameters or configuration file
├──── image1/                  # Image sequence or camera view 1
│   ├──── 00000*.png           # Image frame
│   └──── ...
├──── image2/                  # Image sequence or camera view 2
│   ├──── 00000*.png           # Image frame
│   └──── ...
└── image3/                  # Image sequence or camera view 3
│   ├──── 00000*.png           # Image frame
    └──── ...
└── image4/                  # Image sequence or camera view 3
│   ├──── 00000*.png           # Image frame
    └──── ...

├── park
├──── cam.yaml                 # Camera parameters or configuration file
├──── image1/                  # Image sequence or camera view 1
│   ├──── 00000*.png           # Image frame
│   └──── ...
├──── image2/                  # Image sequence or camera view 2
│   ├──── 00000*.png           # Image frame
│   └──── ...


├── factory
├──── cam.yaml                 # Camera parameters or configuration file
├──── image1/                  # Image sequence or camera view 1
│   ├──── 00000*.png           # Image frame
│   └──── ...
├──── image2/                  # Image sequence or camera view 2
│   ├──── 00000*.png           # Image frame
│   └──── ...
└── image3/                  # Image sequence or camera view 3
│   ├──── 00000*.png           # Image frame
    └──── ...
├── temple
├──── cam.yaml                 # Camera parameters or configuration file
├──── image1/                  # Image sequence or camera view 1
│   ├──── 00000*.png           # Image frame
│   └──── ...
├──── image2/                  # Image sequence or camera view 2
│   ├──── 00000*.png           # Image frame
│   └──── ...
└── image3/                  # Image sequence or camera view 3
│   ├──── 00000*.png           # Image frame
    └──── ...
└── image4/                  # Image sequence or camera view 3
│   ├──── 00000*.png           # Image frame
    └──── ...

```

# demo

![deom](Factory.gif)

# Cite

If you find this dataset useful for your research, please consider citing the paper

```
@article{DU2026105387,
title = {MSRS-SLAM: A real-time multi-UAV dense mapping system for efficient low-altitude remote sensing},
journal = {International Journal of Applied Earth Observation and Geoinformation},
volume = {151},
pages = {105387},
year = {2026},
issn = {1569-8432},
doi = {https://doi.org/10.1016/j.jag.2026.105387},
url = {https://www.sciencedirect.com/science/article/pii/S1569843226003031},
author = {Bing Du and Xiaohan Liao and Huanyin Yue and Yuyu Zhang and Huping Ye and Jianli Liu},
keywords = {Reconstruction, VSLAM, UAV remote sensing, Point cloud, Real-time mapping}}
```

