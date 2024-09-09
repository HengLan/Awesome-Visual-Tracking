# Awesome-Visual-Tracking
This repository aims to collect awesome visual tracking works, including algorithms and benchmarks. The goal is to provide a platform (like an informal review) for researchers to conveniently follow recently published as well as previous literature in the tracking community. Please note that, this repository focuses on the so-called `single object tracking`, including both 2D and 3D tracking tasks, and other tracking tasks such as multi-object tracking and point tracking is beyong the goal of this repository.


## Regarding this repository

* #### Why build this repository?
  
Visual tracking is a rapidly evolving field with a significant number of research papers proposed each year. To understand the most recent trends in visual tracking, we build this repository to collect the latest works (which are accepted or published; arXiv papers are not included now, but may be added later) so that researchers in this area can easily follow cutting-edge ideas and innovations in this community. 

* #### What will be included in this repository?

We will focus on the bounding-box-based visual tracking, including `single modality visual tracking` (i.e., generic (RGB) tracking and LiDAR-based tracking) and `multi-modality visual tracking` (i.e., vision-language tracking, RGB-X tracking with X being depth/event/thermal etc). Papers focusing on algorithm, benchmarks, and survey will be collected.

* #### Where will you collect the tracking papers?

With numerous papers published on visual tracking each year, it is (almost) impossible to collect all the papers in this field. We will collect papers from major computer vision (e.g., CVPR/ICCV/ECCV) and machine learning (e.g., NeurIPS/ICLR/ICML) conferences or journals (e.g., IEEE T-PAMI and IJCV) because they usually represent the latest innovations in the tracking community. But please be noted that, papers outside the aforementioned avenues might also be considered.

Considering deep trackers started to show dominant results on benchmarks starting from 2015, we include trackers from 2015 to now.

* #### How is your repository different from others?

There are already some excellent repositories related to visual tracking. This repository is slightly different in topics by including various single-object tracking settings and in organizations in which papers are collected based on topics with clear accesses to paper and code. For those papers sharing the code and the dataset, a thumbs up 👍 is shown.

* #### How will this repository be maintained and update?

We aim to update this repository whenever we know papers accepted/published from the avenues where we collect papers. Most likely, we will update it after the decision of a certain conference is released or when we see a paper published in the related journals.

## Content
- [Generic Tracking](#generic-tracking-or-rgb-only-tracking)
  
- [RGB-X Tracking](#rgb-x-tracking-x-as-another-vision-modality)
  
- [Vision-Language Tracking](#vision-language-tracking)
  
- [Lidar-based 3D Object Tracking](#lidar-based-3d-object-tracking)

Note: all papers are listed in the chronological order.

#### `Generic Tracking (or RGB-only Tracking)`
  
* [**ECCV'2024**] ***"Enhancing Tracking Robustness with Auxiliary Adversarial Defense Networks"***, Zhewei Wu, Ruilong Yu, Qihe Liu, Shuying Cheng, Shilin Qiu, and Shijie Zhou.<br>
  [[`paper`]](https://arxiv.org/abs/2402.17976)

* [**ECCV'2024**] Diff-Tracker: Text-to-Image Diffusion Models are Unsupervised Trackers, Zhengbo Zhang, Li Xu, Duo Peng, Hossein Rahmani, and Jun Liu. <br>
  [[`paper`]](https://arxiv.org/pdf/2407.08394)

* [**ECCV'2024**] Exploring the Feature Extraction and Relation Modeling For Light-Weight Transformer Tracking, Jikai Zheng, Mingjiang Liang, Shaoli Huang, and Jifeng Ning.<br>
  [paper]

* [**ECCV'2024**] Tracking Meets LoRA: Faster Training, Larger Model, Stronger Performance, Liting Lin, Heng Fan, Zhipeng Zhang, Yaowei Wang, Yong Xu, and Haibin Ling. <br>
  [[`paper`]](https://arxiv.org/abs/2403.05231) [[`Code`👍]](https://github.com/LitingLin/LoRAT)<br>

#### `RGB-X Tracking (X as another vision modality)`

#### `Vision-Language Tracking`
* [**ECCV'2024**] SemTrack: A Large-scale Dataset for Semantic Tracking in the Wild, Dezhao Huang, Evan Ling, Weiling Chen, Keng Teck Ma, Minhoe Hur, and Jun Liu. [paper] [[`Dataset`👍]](https://github.com/sutdcv/SemTrack?tab=readme-ov-file)

#### `Lidar-based 3D Object Tracking`
* [**ECCV'2024**] 3D Single-object Tracking in Point Clouds with High Temporal Variation, Qiao Wu, Kun Sun, Pei An, Mathieu Salzmann, Yanning Zhang, and Jiaqi Yang. [[`paper`]](https://arxiv.org/pdf/2408.02049)

* [**ECCV'2024**] Boosting 3D Single Object Tracking with 2D Matching Distillation and 3D Pre-training, Qiangqiang Wu, Yan Xia, Jia Wang, and Antoni B Chan. [paper]


## Acknowledgements
