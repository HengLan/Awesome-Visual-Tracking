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

There are already some excellent repositories related to visual tracking. This repository is slightly different in topics by including various single-object tracking settings and in organizations in which papers are collected based on topics with clear accesses to paper and code. For those papers sharing the code and the dataset, a thumbs up 👍 is shown (a periodic check for code/dataset release will be performed).

* #### How will this repository be maintained and update?

We aim to update this repository whenever we know papers accepted/published from the avenues where we collect papers. Most likely, we will update it after the decision of a certain conference is released or when we see a paper published in the related journals.

## Log
- ECCV'2024, ICML'2024, and CVPR'2024 papers have been added.
- TODO: NeurIPS'2023, ICCV'2023, and CVPR'2023 papers to be added.

## Content
- [Generic Tracking](#generic-tracking-or-rgb-only-tracking)
  
- [RGB-X Tracking](#rgb-x-tracking-x-as-another-vision-modality)
  
- [Vision-Language Tracking](#vision-language-tracking)
  
- [Lidar-based 3D Object Tracking](#lidar-based-3d-object-tracking)

Note: all papers are listed in the chronological order.


#### `Generic Tracking (or RGB-only Tracking)`
  
* [**ECCV'2024**] ***"Enhancing Tracking Robustness with Auxiliary Adversarial Defense Networks"***, Zhewei Wu, Ruilong Yu, Qihe Liu, Shuying Cheng, Shilin Qiu, and Shijie Zhou. [[`paper`]](https://arxiv.org/abs/2402.17976)

* [**ECCV'2024**] ***"Diff-Tracker: Text-to-Image Diffusion Models are Unsupervised Trackers***", Zhengbo Zhang, Li Xu, Duo Peng, Hossein Rahmani, and Jun Liu. [[`paper`]](https://arxiv.org/pdf/2407.08394)

* [**ECCV'2024**] ***"Exploring the Feature Extraction and Relation Modeling For Light-Weight Transformer Tracking***", Jikai Zheng, Mingjiang Liang, Shaoli Huang, and Jifeng Ning. [paper]

* [**ECCV'2024**] ***"Tracking Meets LoRA: Faster Training, Larger Model, Stronger Performance***", Liting Lin, Heng Fan, Zhipeng Zhang, Yaowei Wang, Yong Xu, and Haibin Ling. [[`paper`]](https://arxiv.org/abs/2403.05231) [[`Code`👍]](https://github.com/LitingLin/LoRAT)

* [**ICML'2024**] ***"Learning Adaptive and View-Invariant Vision Transformer for Real-Time UAV Tracking***", Yongxin Li, Mengyuan Liu, You Wu, Xucheng Wang, Xiangyang Yang, and Shuiwang Li. [[`paper`]](https://proceedings.mlr.press/v235/li24ax.html) [[`Code`👍]](https://github.com/wuyou3474/AVTrack)

* [**CVPR'2024**] ***"RTracker: Recoverable Tracking via PN Tree Structured Memory***", Yuqing Huang, Xin Li, Zikun Zhou, Yaowei Wang, Zhenyu He, and Ming-Hsuan Yang. [[`paper`]](https://arxiv.org/abs/2403.19242)

* [**CVPR'2024**] ***"Autoregressive Queries for Adaptive Tracking with Spatio-TemporalTransformers***", Jinxia Xie, Bineng Zhong, Zhiyi Mo, Shengping Zhang, Liangtao Shi, Shuxiang Song, and Rongrong Ji. [[`paper`]](https://arxiv.org/abs/2403.19242) [[`Code`👍]](https://github.com/GXNU-ZhongLab/AQATrack)

* [**CVPR'2024**] ***"HIPTrack: Visual Tracking with Historical Prompts***", Wenrui Cai, Qingjie Liu, and Yunhong Wang. [[`paper`]](https://arxiv.org/abs/2311.02072) [[`Code`👍]](https://github.com/WenRuiCai/HIPTrack)

* [**CVPR'2024**] ***"DiffusionTrack: Point Set Diffusion Model for Visual Object Tracking***", Fei Xie, Zhongdao Wang, and Chao Ma. [[`paper`]](https://openaccess.thecvf.com/content/CVPR2024/papers/Xie_DiffusionTrack_Point_Set_Diffusion_Model_for_Visual_Object_Tracking_CVPR_2024_paper.pdf) [[`Code`👍]](https://github.com/VISION-SJTU/DiffusionTrack)

* [**CVPR'2024**] ***"ARTrackV2: Prompting Autoregressive Tracker Where to Look and How to Describe***", Yifan Bai, Zeyang Zhao, Yihong Gong, and Xing Wei. [[`paper`]](https://arxiv.org/abs/2312.17133) [[`Code`👍]](https://github.com/MIV-XJTU/ARTrack)

* [**NeurIPS'2023**] ***"MixFormerV2: Efficient Fully Transformer Tracking***", Yutao Cui, Tianhui Song, Gangshan Wu, and Limin Wang. [[`paper`]](https://arxiv.org/abs/2305.15896) [[`Code`👍]](https://github.com/MCG-NJU/MixFormerV2)

* [**NeurIPS'2023**] ***"ZoomTrack: Target-aware Non-uniform Resizing for Efficient Visual Tracking***", Yutong Kou, Jin Gao, Bing Li, Gang Wang, Weiming Hu, Yizheng Wang, and Liang Li. [[`paper`]](https://arxiv.org/abs/2310.10071) [[`Code`👍]](https://github.com/Kou-99/ZoomTrack)

* [**NeurIPS'2023**] ***"Reading Relevant Feature from Global Representation Memory for Visual Object Tracking***", Xinyu Zhou, Pinxue Guo, Lingyi Hong, Jinglun Li, Wei Zhang, Weifeng Ge, and Wenqiang Zhang. [[`paper`]](https://proceedings.neurips.cc/paper_files/paper/2023/file/2349293cb1bf2ce36d5c566f660f957e-Paper-Conference.pdf)

* [**NeurIPS'2023**] ***"BadTrack: A Poison-Only Backdoor Attack on Visual Object Tracking***", Bin Huang, Jiaqian Yu, Yiwei Chen, Siyang Pan, Qiang Wang, and Zhi Wang. [[`paper`]](https://proceedings.neurips.cc/paper_files/paper/2023/file/828bb8f42d4ab15322b9315151959c61-Paper-Conference.pdf)

* [**NeurIPS'2023**] ***"EgoTracks: A Long-term Egocentric Visual Object Tracking Dataset***", Hao Tang, Kevin J Liang, Kristen Grauman, Matt Feiszli, and Weiyao Wang. [[`paper`]](https://proceedings.neurips.cc/paper_files/paper/2023/file/ef01d91aa87e7701aa9c8dc66a2d5bdb-Paper-Datasets_and_Benchmarks.pdf) [[`Dataset`👍]](https://github.com/EGO4D/episodic-memory/tree/main/EgoTracks)








#### `RGB-X Tracking (X as another vision modality)`

* [**CVPR'2024**] ***"OneTracker: Unifying Visual Object Tracking with Foundation Models and Efficient Tuning***", Lingyi Hong, Shilin Yan, Renrui Zhang, Wanyun Li, Xinyu Zhou, Pinxue Guo, Kaixun Jiang, Yiting Chen, Jinglun Li, Zhaoyu Chen, and Wenqiang Zhang. [[`paper`]](https://arxiv.org/abs/2403.09634)

* [**CVPR'2024**] ***"Single-Model and Any-Modality for Video Object Tracking***", Jinxia Xie, Bineng Zhong, Zhiyi Mo, Shengping Zhang, Liangtao Shi, Shuxiang Song, and Rongrong Ji. [[`paper`]](https://arxiv.org/abs/2311.15851)

* [**CVPR'2024**] ***"SDSTrack: Self-Distillation Symmetric Adapter Learning for Multi-Modal Visual Object Tracking***", Xiaojun Hou, Jiazheng Xing, Yijie Qian, Yaowei Guo, Shuo Xin, Junhao Chen, Kai Tang, Mengmeng Wang, Zhengkai Jiang, Liang Liu, and Yong Liu. [[`paper`]](https://arxiv.org/abs/2403.16002) [[`Code`👍]](https://github.com/hoqolo/SDSTrack)

* [**CVPR'2024**] ***"Event Stream-based Visual Object Tracking: A High-Resolution Benchmark Dataset and A Novel Baseline***", Xiao Wang, Shiao Wang, Chuanming Tang, Lin Zhu, Bo Jiang, Yonghong Tian, and Jin Tang, Mengmeng Wang, Zhengkai Jiang, Liang Liu, and Yong Liu. [[`paper`]](https://arxiv.org/abs/2309.14611) [[`Code and Dataset`👍]](https://github.com/Event-AHU/EventVOT_Benchmark)






#### `Vision-Language Tracking`

* [**ECCV'2024**] ***"SemTrack: A Large-scale Dataset for Semantic Tracking in the Wild***", Dezhao Huang, Evan Ling, Weiling Chen, Keng Teck Ma, Minhoe Hur, and Jun Liu. 
  [paper] [[`Dataset`👍]](https://github.com/sutdcv/SemTrack?tab=readme-ov-file)

* [**IEEE T-PAMI'2024**] ***"Divert More Attention to Vision-Language Object Tracking***", Mingzhe Guo, Zhipeng Zhang, Liping Jing, Haibin Ling, and Heng Fan. 
  [[`paper`]](https://arxiv.org/abs/2307.10046) [[`Code`👍]](https://github.com/JudasDie/SOTS)

* [**CVPR'2024**] ***"Context-Aware Integration of Language and Visual References for Natural Language Tracking***", Yanyan Shao, Shuting He, Qi Ye, Yuchao Feng, Wenhan Luo, and Jiming Chen. 
  [[`paper`]](https://arxiv.org/abs/2403.19975)

* [**NeurIPS'2023**] ***"A Multi-modal Global Instance Tracking Benchmark (MGIT): Better Locating Target in Complex Spatio-temporal and Causal Relationship***", Shiyu Hu, Dailing Zhang, Meiqi Wu, Xiaokun Feng, Xuchen Li, Xin Zhao, and Kaiqi Huang. [[`paper`]](https://openreview.net/forum?id=xo6zDI8gvB&referrer=%5Bthe%20profile%20of%20Kaiqi%20Huang%5D(%2Fprofile%3Fid%3D~Kaiqi_Huang1)) [[`Dataset`👍]](http://videocube.aitestunion.com/)





#### `Lidar-based 3D Object Tracking`
* [**ECCV'2024**] ***"3D Single-object Tracking in Point Clouds with High Temporal Variation***", Qiao Wu, Kun Sun, Pei An, Mathieu Salzmann, Yanning Zhang, and Jiaqi Yang.
  [[`paper`]](https://arxiv.org/pdf/2408.02049)
  
* [**ECCV'2024**] ***"Boosting 3D Single Object Tracking with 2D Matching Distillation and 3D Pre-training***", Qiangqiang Wu, Yan Xia, Jia Wang, and Antoni B Chan.
  [paper]


## Acknowledgements
