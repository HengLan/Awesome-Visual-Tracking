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

There are already some excellent repositories related to visual tracking. This repository is slightly different in topics by including various single-object tracking settings and in organizations in which papers are collected based on topics with clear accesses to paper and code. Papers sharing the code and the dataset are marked with a 🌟 (a periodic check for code/dataset release will be performed).

* #### How will this repository be maintained and update?

We aim to update this repository whenever we know papers accepted/published from the avenues where we collect papers. Most likely, we will update it after the decision of a certain conference is released or when we see a paper published in the related journals.

## Log
- ECCV'24, ICML'24, CVPR'24, NeurIPS'23, ICCV'23, CVPR'2023 papers have been added.
- TODO: NeurIPS'22, ECCV'22, CVPR'22 papers to be added.

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

* [**ECCV'2024**] ***"Tracking Meets LoRA: Faster Training, Larger Model, Stronger Performance***", Liting Lin, Heng Fan, Zhipeng Zhang, Yaowei Wang, Yong Xu, and Haibin Ling. [[`paper`]](https://arxiv.org/abs/2403.05231) [[`Code`🌟]](https://github.com/LitingLin/LoRAT)

* [**ICML'2024**] ***"Learning Adaptive and View-Invariant Vision Transformer for Real-Time UAV Tracking***", Yongxin Li, Mengyuan Liu, You Wu, Xucheng Wang, Xiangyang Yang, and Shuiwang Li. [[`paper`]](https://proceedings.mlr.press/v235/li24ax.html) [[`Code`🌟]](https://github.com/wuyou3474/AVTrack)

* [**CVPR'2024**] ***"RTracker: Recoverable Tracking via PN Tree Structured Memory***", Yuqing Huang, Xin Li, Zikun Zhou, Yaowei Wang, Zhenyu He, and Ming-Hsuan Yang. [[`paper`]](https://arxiv.org/abs/2403.19242)

* [**CVPR'2024**] ***"Autoregressive Queries for Adaptive Tracking with Spatio-TemporalTransformers***", Jinxia Xie, Bineng Zhong, Zhiyi Mo, Shengping Zhang, Liangtao Shi, Shuxiang Song, and Rongrong Ji. [[`paper`]](https://arxiv.org/abs/2403.19242) [[`Code`🌟]](https://github.com/GXNU-ZhongLab/AQATrack)

* [**CVPR'2024**] ***"HIPTrack: Visual Tracking with Historical Prompts***", Wenrui Cai, Qingjie Liu, and Yunhong Wang. [[`paper`]](https://arxiv.org/abs/2311.02072) [[`Code`🌟]](https://github.com/WenRuiCai/HIPTrack)

* [**CVPR'2024**] ***"DiffusionTrack: Point Set Diffusion Model for Visual Object Tracking***", Fei Xie, Zhongdao Wang, and Chao Ma. [[`paper`]](https://openaccess.thecvf.com/content/CVPR2024/papers/Xie_DiffusionTrack_Point_Set_Diffusion_Model_for_Visual_Object_Tracking_CVPR_2024_paper.pdf) [[`Code`🌟]](https://github.com/VISION-SJTU/DiffusionTrack)

* [**CVPR'2024**] ***"ARTrackV2: Prompting Autoregressive Tracker Where to Look and How to Describe***", Yifan Bai, Zeyang Zhao, Yihong Gong, and Xing Wei. [[`paper`]](https://arxiv.org/abs/2312.17133) [[`Code`🌟]](https://github.com/MIV-XJTU/ARTrack)

* [**NeurIPS'2023**] ***"MixFormerV2: Efficient Fully Transformer Tracking***", Yutao Cui, Tianhui Song, Gangshan Wu, and Limin Wang. [[`paper`]](https://arxiv.org/abs/2305.15896) [[`Code`🌟]](https://github.com/MCG-NJU/MixFormerV2)

* [**NeurIPS'2023**] ***"ZoomTrack: Target-aware Non-uniform Resizing for Efficient Visual Tracking***", Yutong Kou, Jin Gao, Bing Li, Gang Wang, Weiming Hu, Yizheng Wang, and Liang Li. [[`paper`]](https://arxiv.org/abs/2310.10071) [[`Code`🌟]](https://github.com/Kou-99/ZoomTrack)

* [**NeurIPS'2023**] ***"Reading Relevant Feature from Global Representation Memory for Visual Object Tracking***", Xinyu Zhou, Pinxue Guo, Lingyi Hong, Jinglun Li, Wei Zhang, Weifeng Ge, and Wenqiang Zhang. [[`paper`]](https://proceedings.neurips.cc/paper_files/paper/2023/file/2349293cb1bf2ce36d5c566f660f957e-Paper-Conference.pdf)

* [**NeurIPS'2023**] ***"BadTrack: A Poison-Only Backdoor Attack on Visual Object Tracking***", Bin Huang, Jiaqian Yu, Yiwei Chen, Siyang Pan, Qiang Wang, and Zhi Wang. [[`paper`]](https://proceedings.neurips.cc/paper_files/paper/2023/file/828bb8f42d4ab15322b9315151959c61-Paper-Conference.pdf)

* [**NeurIPS'2023**] ***"EgoTracks: A Long-term Egocentric Visual Object Tracking Dataset***", Hao Tang, Kevin J Liang, Kristen Grauman, Matt Feiszli, and Weiyao Wang. [[`paper`]](https://proceedings.neurips.cc/paper_files/paper/2023/file/ef01d91aa87e7701aa9c8dc66a2d5bdb-Paper-Datasets_and_Benchmarks.pdf) [[`Dataset`🌟]](https://github.com/EGO4D/episodic-memory/tree/main/EgoTracks)

* [**ICCV'2023**] ***"PVT++: A Simple End-to-End Latency-Aware Visual Tracking Framework***", Bowen Li, Ziyuan Huang, Junjie Ye, Yiming Li, Sebastian Scherer, Hang Zhao, and Changhong Fu. [[`paper`]](https://arxiv.org/abs/2211.11629) [[`Code`🌟]](https://github.com/Jaraxxus-Me/PVT_pp)

* [**ICCV'2023**] ***"Foreground-Background Distribution Modeling Transformer for Visual Object Tracking***", Dawei Yang, Jianfeng He, Yinchao Ma, Qianjin Yu, and Tianzhu Zhang. [[`paper`]](https://openaccess.thecvf.com/content/ICCV2023/papers/Yang_Foreground-Background_Distribution_Modeling_Transformer_for_Visual_Object_Tracking_ICCV_2023_paper.pdf)

* [**ICCV'2023**] ***"Robust Object Modeling for Visual Tracking***", Yidong Cai, Jie Liu, Jie Tang, and Gangshan Wu. [[`paper`]](https://arxiv.org/abs/2308.05140) [[`Code`🌟]](https://github.com/dawnyc/ROMTrack)

* [**ICCV'2023**] ***"Adaptive and Background-Aware Vision Transformer for Real-Time UAV Tracking***", Shuiwang Li, Yangxiang Yang, Dan Zeng, and Xucheng Wang. [[`paper`]](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Adaptive_and_Background-Aware_Vision_Transformer_for_Real-Time_UAV_Tracking_ICCV_2023_paper.pdf)

* [**ICCV'2023**] ***"Exploring Lightweight Hierarchical Vision Transformers for Efficient Visual Tracking***", Ben Kang, Xin Chen, Dong Wang, Houwen Peng, and Huchuan Lu. [[`paper`]](https://arxiv.org/abs/2308.06904)

* [**CVPR'2023**] ***"Generalized Relation Modeling for Transformer Tracking***", Shenyuan Gao, Chunluan Zhou, and Jun Zhang. [[`paper`]](https://arxiv.org/abs/2303.16580) [[`Code`🌟]](https://github.com/Little-Podi/GRM)

* [**CVPR'2023**] ***"SeqTrack: Sequence to Sequence Learning for Visual Object Tracking***", Xin Chen, Ben Kang, Jiawen Zhu, Dong Wang, Houwen Peng, and Huchuan Lu. [[`paper`]](https://openaccess.thecvf.com/content/CVPR2023/papers/Chen_SeqTrack_Sequence_to_Sequence_Learning_for_Visual_Object_Tracking_CVPR_2023_paper.pdf) [[`Code`🌟]](https://github.com/chenxin-dlut/SeqTrackv2)

* [**CVPR'2023**] ***"Autoregressive Visual Tracking***", Xing Wei, Yifan Bai, Yongchao Zheng, Dahu Shi, and Yihong Gong. [[`paper`]](https://openaccess.thecvf.com/content/CVPR2023/papers/Wei_Autoregressive_Visual_Tracking_CVPR_2023_paper.pdf) [[`Code`🌟]](https://github.com/MIV-XJTU/ARTrack)

* [**CVPR'2023**] ***"DropMAE: Masked Autoencoders with Spatial-Attention Dropout for Tracking Tasks***", Qiangqiang Wu, Tianyu Yang, Ziquan Liu, Baoyuan Wu, Ying Shan, and Antoni B. Chan. [[`paper`]](https://arxiv.org/abs/2304.00571) [[`Code`🌟]](https://github.com/jimmy-dq/DropMAE)









#### `RGB-X Tracking (X as another vision modality)`

* [**CVPR'2024**] ***"OneTracker: Unifying Visual Object Tracking with Foundation Models and Efficient Tuning***", Lingyi Hong, Shilin Yan, Renrui Zhang, Wanyun Li, Xinyu Zhou, Pinxue Guo, Kaixun Jiang, Yiting Chen, Jinglun Li, Zhaoyu Chen, and Wenqiang Zhang. [[`paper`]](https://arxiv.org/abs/2403.09634)

* [**CVPR'2024**] ***"Single-Model and Any-Modality for Video Object Tracking***", Jinxia Xie, Bineng Zhong, Zhiyi Mo, Shengping Zhang, Liangtao Shi, Shuxiang Song, and Rongrong Ji. [[`paper`]](https://arxiv.org/abs/2311.15851)

* [**CVPR'2024**] ***"SDSTrack: Self-Distillation Symmetric Adapter Learning for Multi-Modal Visual Object Tracking***", Xiaojun Hou, Jiazheng Xing, Yijie Qian, Yaowei Guo, Shuo Xin, Junhao Chen, Kai Tang, Mengmeng Wang, Zhengkai Jiang, Liang Liu, and Yong Liu. [[`paper`]](https://arxiv.org/abs/2403.16002) [[`Code`🌟]](https://github.com/hoqolo/SDSTrack)

* [**CVPR'2024**] ***"Event Stream-based Visual Object Tracking: A High-Resolution Benchmark Dataset and A Novel Baseline***", Xiao Wang, Shiao Wang, Chuanming Tang, Lin Zhu, Bo Jiang, Yonghong Tian, and Jin Tang, Mengmeng Wang, Zhengkai Jiang, Liang Liu, and Yong Liu. [[`paper`]](https://arxiv.org/abs/2309.14611) [[`Code and Dataset`🌟]](https://github.com/Event-AHU/EventVOT_Benchmark)

* [**CVPR'2023**] ***"Efficient RGB-T Tracking via Cross-Modality Distillation***", Tianlu Zhang, Hongyuan Guo, Qiang Jiao, Qiang Zhang, and Jungong Han. [[`paper`]](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Efficient_RGB-T_Tracking_via_Cross-Modality_Distillation_CVPR_2023_paper.pdf)

* [**CVPR'2023**] ***"Visual Prompt Multi-Modal Tracking***", Jiawen Zhu, Simiao Lai, Xin Chen, Dong Wang, and Huchuan Lu. [[`paper`]](https://arxiv.org/abs/2303.10826) [[`Code`🌟]](https://github.com/jiawen-zhu/ViPT)

* [**CVPR'2023**] ***"Representation Learning for Visual Object Tracking by Masked Appearance Transfer***", Haojie Zhao, Dong Wang, and Huchuan Lu. [[`paper`]](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhao_Representation_Learning_for_Visual_Object_Tracking_by_Masked_Appearance_Transfer_CVPR_2023_paper.pdf) [[`Code`🌟]](https://github.com/difhnp/MAT?tab=readme-ov-file)

* [**CVPR'2023**] ***"Bridging Search Region Interaction with Template for RGB-T Tracking***", Tianrui Hui, Zizheng Xun, Fengguang Peng, Junshi Huang, Xiaoming Wei, Xiaolin Wei, Jiao Dai, Jizhong Han, and Si Liu. [[`paper`]](https://openaccess.thecvf.com/content/CVPR2023/papers/Hui_Bridging_Search_Region_Interaction_With_Template_for_RGB-T_Tracking_CVPR_2023_paper.pdf) [[`Code`🌟]](https://github.com/RyanHTR/TBSI)

* [**CVPR'2023**] ***"Resource-Efficient RGBD Aerial Tracking***", Jinyu Yang, Shang Gao, Zhe Li, Feng Zheng, and Aleš Leonardis. [[`paper`]](https://openaccess.thecvf.com/content/CVPR2023/papers/Yang_Resource-Efficient_RGBD_Aerial_Tracking_CVPR_2023_paper.pdf)

* [**CVPR'2023**] ***"Frame-Event Alignment and Fusion Network for High Frame Rate Tracking***", Jiqing Zhang, Yuanchen Wang, Wenxi Liu, Meng Li, Jinpeng Bai, Baocai Yin, and Xin Yang. [[`paper`]](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Frame-Event_Alignment_and_Fusion_Network_for_High_Frame_Rate_Tracking_CVPR_2023_paper.pdf) [[`Code`🌟]](https://github.com/Jee-King/AFNet)






#### `Vision-Language Tracking`

* [**ECCV'2024**] ***"SemTrack: A Large-scale Dataset for Semantic Tracking in the Wild***", Dezhao Huang, Evan Ling, Weiling Chen, Keng Teck Ma, Minhoe Hur, and Jun Liu. 
  [paper] [[`Dataset`🌟]](https://github.com/sutdcv/SemTrack?tab=readme-ov-file)

* [**IEEE T-PAMI'2024**] ***"Divert More Attention to Vision-Language Object Tracking***", Mingzhe Guo, Zhipeng Zhang, Liping Jing, Haibin Ling, and Heng Fan. 
  [[`paper`]](https://arxiv.org/abs/2307.10046) [[`Code`🌟]](https://github.com/JudasDie/SOTS)

* [**CVPR'2024**] ***"Context-Aware Integration of Language and Visual References for Natural Language Tracking***", Yanyan Shao, Shuting He, Qi Ye, Yuchao Feng, Wenhan Luo, and Jiming Chen. 
  [[`paper`]](https://arxiv.org/abs/2403.19975)

* [**NeurIPS'2023**] ***"A Multi-modal Global Instance Tracking Benchmark (MGIT): Better Locating Target in Complex Spatio-temporal and Causal Relationship***", Shiyu Hu, Dailing Zhang, Meiqi Wu, Xiaokun Feng, Xuchen Li, Xin Zhao, and Kaiqi Huang. [[`paper`]](https://openreview.net/forum?id=xo6zDI8gvB&referrer=%5Bthe%20profile%20of%20Kaiqi%20Huang%5D(%2Fprofile%3Fid%3D~Kaiqi_Huang1)) [[`Dataset`🌟]](http://videocube.aitestunion.com/)

* [**ICCV'2023**] ***"Tracking by Natural Language Specification with Long Short-term Context Decoupling***", Ding Ma and Xiangqian Wu. [[`paper`]](https://openaccess.thecvf.com/content/ICCV2023/papers/Ma_Tracking_by_Natural_Language_Specification_with_Long_Short-term_Context_Decoupling_ICCV_2023_paper.pdf)

* [**ICCV'2023**] ***"CiteTracker: Correlating Image and Text for Visual Tracking***", Xin Li, Yuqing Huang, Zhenyu He, Yaowei Wang, Huchuan Lu, and Ming-Hsuan Yang. [[`paper`]](https://arxiv.org/abs/2308.11322) [[`Code`🌟]](https://github.com/NorahGreen/CiteTracker)

* [**CVPR'2023**] ***"Joint Visual Grounding and Tracking with Natural Language Specification***", Li Zhou, Zikun Zhou, Kaige Mao, and Zhenyu He. [[`paper`]](https://arxiv.org/abs/2303.12027) [[`Code`🌟]](https://github.com/lizhou-cs/JointNLT)







#### `Lidar-based 3D Object Tracking`
* [**ECCV'2024**] ***"3D Single-object Tracking in Point Clouds with High Temporal Variation***", Qiao Wu, Kun Sun, Pei An, Mathieu Salzmann, Yanning Zhang, and Jiaqi Yang.
  [[`paper`]](https://arxiv.org/pdf/2408.02049)
  
* [**ECCV'2024**] ***"Boosting 3D Single Object Tracking with 2D Matching Distillation and 3D Pre-training***", Qiangqiang Wu, Yan Xia, Jia Wang, and Antoni B Chan.
  [paper]

* [**ICCV'2023**] ***"MBPTrack: Improving 3D Point Cloud Tracking with Memory Networks and Box Priors***", Tian-Xing Xu, Yuan-Chen Guo, Yu-Kun Lai, and Song-Hai Zhang. [[`paper`]](https://arxiv.org/abs/2303.05071)

* [**ICCV'2023**] ***"Synchronize Feature Extracting and Matching: A Single Branch Framework for 3D Object Tracking***", Teli Ma, Mengmeng Wang, Jimin Xiao, Huifeng Wu, and Yong Liu. [[`paper`]](https://arxiv.org/abs/2308.12549)

* [**CVPR'2023**] ***"CXTrack: Improving 3D Point Cloud Tracking with Contextual Information***", Tian-Xing Xu, Yuan-Chen Guo, Yu-Kun Lai, and Song-Hai Zhang. [[`paper`]](https://arxiv.org/abs/2211.08542) [[`Code`🌟]](https://github.com/slothfulxtx/cxtrack3d)


## Acknowledgements
