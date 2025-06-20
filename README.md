# Awesome-Visual-Tracking
This repository aims to collect awesome visual tracking works, including algorithms and benchmarks. The goal is to provide a platform (like an informal review) for researchers to conveniently follow recently published as well as previous literature in the tracking community. Please note that, this repository focuses on the so-called `single object tracking`, including both 2D and 3D tracking tasks, and other tracking tasks such as multi-object tracking and point tracking is beyong the goal of this repository.

## Regarding this repository

* #### Why build this repository?
  
Visual tracking is a rapidly evolving field with a significant number of research papers proposed each year. To understand the most recent trends in visual tracking, we build this repository to collect the latest works (which are accepted or published; arXiv papers are not included now, but may be added later) so that researchers in this area can easily follow cutting-edge ideas and innovations in this community. 

* #### What will be included in this repository?

We will focus on the bounding-box-based visual tracking, including `single modality visual tracking` (i.e., generic (RGB) tracking and LiDAR-based tracking) and `multi-modality visual tracking` (i.e., vision-language tracking, RGB-X tracking with X being depth/event/thermal etc). Papers focusing on algorithm, benchmarks, and survey will be collected.

* #### Where will you collect the tracking papers?

With numerous papers published on visual tracking each year, it is (almost) impossible to collect all the papers in this field. We will collect papers from major computer vision (e.g., CVPR/ICCV/ECCV) and machine learning (e.g., NeurIPS/ICLR/ICML) conferences or journals (e.g., IEEE T-PAMI and IJCV) because they usually represent the latest innovations in the tracking community. But please be noted that, papers outside the aforementioned avenues might also be considered.

Please note that, tracking is a really large community. It is hard to collect trackers starting from the very begining. Considering that Transformer-based architectures now show dominant performnace, we collect trackers published after 2021 (including 2021) when the Transformer-based tracker were proposed for the first time. For more classific trackers, the readers are encouraded to look at other repositories such as [this](https://github.com/DavidZhangdw/Visual-Tracking-Development), [this](https://github.com/wangdongdut/Long-term-Visual-Tracking), [this](https://github.com/wangdongdut/Online-Visual-Tracking-SOTA), [this](https://github.com/foolwood/benchmark_results), and [this](https://github.com/Little-Podi/Transformer_Tracking).

We will try our best to update this repository to include new trackers in time.

* #### How is your repository different from others?

There are already some excellent repositories related to visual tracking. This repository is slightly different in topics by including various single-object tracking settings and in organizations in which papers are collected based on topics with clear accesses to paper and code. Papers sharing the code and the dataset are marked with a 🌟 (a periodic check for code/dataset release will be performed).

* #### How will this repository be maintained and update?

We aim to update this repository whenever we know papers accepted/published from the avenues where we collect papers. Most likely, we will update it after the decision of a certain conference is released or when we see a paper published in the related journals.

## Content
- [Generic Tracking](#generic-tracking-or-rgb-only-tracking)
  
- [RGB-X Tracking](#rgb-x-tracking-x-as-another-vision-modality)
  
- [Vision-Language Tracking](#vision-language-tracking)
  
- [Lidar-based 3D Object Tracking](#lidar-based-3d-object-tracking)

Note: all papers are listed in the chronological order.


#### `Generic Tracking (or RGB-only Tracking)`

* [**ICML'2025**] ***"Efficient Motion Prompt Learning for Robust Visual Tracking"***, Jie Zhao, Xin Chen, Yongsheng Yuan, Michael Felsberg, Dong Wang, and Huchuan Lu. [[`paper`]](https://arxiv.org/abs/2505.16321) [[`Code`🌟]](https://github.com/zj5559/Motion-Prompt-Tracking)

* [**CVPR'2025**] ***"Similarity-Guided Layer-Adaptive Vision Transformer for UAV Tracking"***, Chaocan Xue, Bineng Zhong, Qihua Liang, Yaozong Zheng, Ning Li, Yuanliang Xue, and Shuxiang Song.

* [**CVPR'2025**] ***"Autoregressive Sequential Pretraining for Visual Tracking"***, Shiyi Liang, Yifan Bai, Yihong Gong, and Xing Wei.
  
* [**CVPR'2025**] ***"SPMTrack: Spatio-Temporal Parameter-Efficient Fine-Tuning with Mixture of Experts for Scalable Visual Tracking"***, Wenrui Cai, Qingjie Liu, and Yunhong Wang.
  
* [**CVPR'2025**] ***"Learning Occlusion-Robust Vision Transformers for Real-Time UAV Tracking"***, You Wu, Xucheng Wang, Xiangyang Yang, Mengyuan Liu, Dan Zeng, Hengzhou Ye, and Shuiwang Li.

* [**CVPR'2025**] ***"A Distractor-Aware Memory for Visual Object Tracking with SAM2"***, Jovana Videnovic, Alan Lukezic, and Matej Kristan. [[`paper`]](https://arxiv.org/abs/2411.17576) [[`Code`🌟]](https://github.com/jovanavidenovic/DAM4SAM)

* [**NeurIPS'2024**] ***"DeTrack: In-model Latent Denoising Learning for Visual Object Tracking"***, Xinyu Zhou, Jinglun Li, Lingyi Hong, Kaixun Jiang, Pinxue Guo, Weifeng Ge, and Wenqiang Zhang.

* [**NeurIPS'2024**] ***"VastTrack: Vast Category Visual Object Tracking"***, Liang Peng, Junyuan Gao, Xinran Liu, Weihong Li, Shaohua Dong, Zhipeng Zhang, Heng Fan, and Libo Zhang. [[`paper`]](https://arxiv.org/abs/2403.03493) [[`Dataset`🌟]](https://github.com/HengLan/VastTrack)

* [**NeurIPS'2024**] ***"Beyond Accuracy: Tracking more like Human through Visual Search***", Dailing Zhang, Shiyu Hu, Xiaokun Feng, Xuchen Li, Meiqi Wu, Jing Zhang, and Kaiqi Huang. 

* [**NeurIPS'2024**] ***"WebUOT-1M: Advancing Deep Underwater Object Tracking with A Million-Scale Benchmark"***, Chunhui Zhang, Li Liu, Guanjie Huang, Hao Wen, Xi Zhou, and Yanfeng Wang. [[`paper`]](https://arxiv.org/abs/2405.19818) [[`Dataset`🌟]](https://github.com/983632847/Awesome-Multimodal-Object-Tracking)

* [**ECCV'2024**] ***"Enhancing Tracking Robustness with Auxiliary Adversarial Defense Networks"***, Zhewei Wu, Ruilong Yu, Qihe Liu, Shuying Cheng, Shilin Qiu, and Shijie Zhou. [[`paper`]](https://arxiv.org/abs/2402.17976)

* [**ECCV'2024**] ***"Diff-Tracker: Text-to-Image Diffusion Models are Unsupervised Trackers***", Zhengbo Zhang, Li Xu, Duo Peng, Hossein Rahmani, and Jun Liu. [[`paper`]](https://arxiv.org/pdf/2407.08394)

* [**ECCV'2024**] ***"Exploring the Feature Extraction and Relation Modeling For Light-Weight Transformer Tracking***", Jikai Zheng, Mingjiang Liang, Shaoli Huang, and Jifeng Ning. [[`paper`]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04168.pdf)

* [**ECCV'2024**] ***"Tracking Meets LoRA: Faster Training, Larger Model, Stronger Performance***", Liting Lin, Heng Fan, Zhipeng Zhang, Yaowei Wang, Yong Xu, and Haibin Ling. [[`paper`]](https://arxiv.org/abs/2403.05231) [[`Code`🌟]](https://github.com/LitingLin/LoRAT)

* [**ICML'2024**] ***"Learning Adaptive and View-Invariant Vision Transformer for Real-Time UAV Tracking***", Yongxin Li, Mengyuan Liu, You Wu, Xucheng Wang, Xiangyang Yang, and Shuiwang Li. [[`paper`]](https://proceedings.mlr.press/v235/li24ax.html) [[`Code`🌟]](https://github.com/wuyou3474/AVTrack)

* [**CVPR'2024**] ***"RTracker: Recoverable Tracking via PN Tree Structured Memory***", Yuqing Huang, Xin Li, Zikun Zhou, Yaowei Wang, Zhenyu He, and Ming-Hsuan Yang. [[`paper`]](https://arxiv.org/abs/2403.19242)

* [**CVPR'2024**] ***"Autoregressive Queries for Adaptive Tracking with Spatio-TemporalTransformers***", Jinxia Xie, Bineng Zhong, Zhiyi Mo, Shengping Zhang, Liangtao Shi, Shuxiang Song, and Rongrong Ji. [[`paper`]](https://arxiv.org/abs/2403.19242) [[`Code`🌟]](https://github.com/GXNU-ZhongLab/AQATrack)

* [**CVPR'2024**] ***"HIPTrack: Visual Tracking with Historical Prompts***", Wenrui Cai, Qingjie Liu, and Yunhong Wang. [[`paper`]](https://arxiv.org/abs/2311.02072) [[`Code`🌟]](https://github.com/WenRuiCai/HIPTrack)

* [**CVPR'2024**] ***"DiffusionTrack: Point Set Diffusion Model for Visual Object Tracking***", Fei Xie, Zhongdao Wang, and Chao Ma. [[`paper`]](https://openaccess.thecvf.com/content/CVPR2024/papers/Xie_DiffusionTrack_Point_Set_Diffusion_Model_for_Visual_Object_Tracking_CVPR_2024_paper.pdf) [[`Code`🌟]](https://github.com/VISION-SJTU/DiffusionTrack)

* [**CVPR'2024**] ***"ARTrackV2: Prompting Autoregressive Tracker Where to Look and How to Describe***", Yifan Bai, Zeyang Zhao, Yihong Gong, and Xing Wei. [[`paper`]](https://arxiv.org/abs/2312.17133) [[`Code`🌟]](https://github.com/MIV-XJTU/ARTrack)

* [**ICLR'2024**] ***"LRR: Language-Driven Resamplable Continuous Representation against Adversarial Tracking Attacks***", Jianlang Chen, Xuhong Ren, Qing Guo, Felix Juefei-Xu, Di Lin, Wei Feng, Lei Ma, and Jianjun Zhao. [[`paper`]](https://arxiv.org/abs/2404.06247)

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

* [**CVPR'2023**] ***"Representation Learning for Visual Object Tracking by Masked Appearance Transfer***", Haojie Zhao, Dong Wang, and Huchuan Lu. [[`paper`]](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhao_Representation_Learning_for_Visual_Object_Tracking_by_Masked_Appearance_Transfer_CVPR_2023_paper.pdf) [[`Code`🌟]](https://github.com/difhnp/MAT?tab=readme-ov-file)

* [**CVPR'2023**] ***"VideoTrack: Learning to Track Objects via Video Transformer***", Fei Xie, Lei Chu, Jiahao Li, Yan Lu, and Chao Ma. [[`paper`]](https://openaccess.thecvf.com/content/CVPR2023/papers/Xie_VideoTrack_Learning_To_Track_Objects_via_Video_Transformer_CVPR_2023_paper.pdf)

* [**CVPR'2023**] ***"OmniTracker: Unifying Object Tracking by Tracking-with-Detection***", Junke Wang, Dongdong Chen, Zuxuan Wu, Chong Luo, Xiyang Dai, Lu Yuan, and Yu-Gang Jiang. [[`paper`]](https://arxiv.org/abs/2303.12079)

* [**CVPR'2023**] ***"Universal Instance Perception as Object Discovery and Retrieval***", Bin Yan, Yi Jiang, Jiannan Wu, Dong Wang, Ping Luo, Zehuan Yuan, and Huchuan Lu. [[`paper`]](https://arxiv.org/abs/2303.06674) [[`Code`🌟]](https://github.com/MasterBin-IIAU/UNINEXT)

* [**NeurIPS'2022**] ***"SwinTrack: A Simple and Strong Baseline for Transformer Tracking***", Liting Lin, Heng Fan, Zhipeng Zhang, Yong Xu, and Haibin Ling. [[`paper`]](https://arxiv.org/abs/2112.00995) [[`Code`🌟]](https://github.com/LitingLin/SwinTrack)

* [**ECCV'2022**] ***"Joint Feature Learning and Relation Modeling for Tracking: A One-Stream Framework***", Botao Ye, Hong Chang, Bingpeng Ma, Shiguang Shan, and Xilin Chen. [[`paper`]](https://arxiv.org/abs/2203.11991) [[`Code`🌟]](https://github.com/botaoye/OSTrack)

* [**ECCV'2022**] ***"Towards Grand Unification of Object Tracking***", Bin Yan, Yi Jiang, Peize Sun, Dong Wang, Zehuan Yuan, Ping Luo, and Huchuan Lu. [[`paper`]](https://arxiv.org/abs/2207.07078) [[`Code`🌟]](https://github.com/MasterBin-IIAU/Unicorn)

* [**ECCV'2022**] ***"AiATrack: Attention in Attention for Transformer Visual Tracking***", Shenyuan Gao, Chunluan Zhou, Chao Ma, Xinggang Wang, and Junsong Yuan. [[`paper`]](https://arxiv.org/abs/2207.09603) [[`Code`🌟]](https://github.com/Little-Podi/AiATrack)

* [**ECCV'2022**] ***"Backbone Is All Your Need: A Simplified Architecture for Visual Object Tracking***", Boyu Chen, Peixia Li, Lei Bai, Lei Qiao, Qiuhong Shen, Bo Li, Weihao Gan, Wei Wu, and Wanli Ouyang. [[`paper`]](https://arxiv.org/abs/2203.05328) [[`Code`🌟]](https://github.com/LPXTT/SimTrack)

* [**ECCV'2022**] ***"Hierarchical Feature Embedding for Visual Tracking***", Zhixiong Pi, Weitao Wan, Chong Sun, Changxin Gao, Nong Sang, and Chen Li. [[`paper`]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820418.pdf)

* [**ECCV'2022**] ***"Towards Sequence-Level Training for Visual Tracking***", Minji Kim, Seungkwan Lee, Jungseul Ok, Bohyung Han, and Minsu Cho. [[`paper`]](https://arxiv.org/abs/2208.05810) [[`Code`🌟]](https://github.com/byminji/SLTtrack)

* [**ECCV'2022**] ***"Robust Visual Tracking by Segmentation***", Matthieu Paul, Martin Danelljan, Christoph Mayer, and Luc Van Gool. [[`paper`]](https://arxiv.org/abs/2203.11191) [[`Code`🌟]](https://github.com/visionml/pytracking)

* [**ECCV'2022**] ***"FEAR: Fast, Efficient, Accurate and Robust Visual Tracker***", Vasyl Borsuk, Roman Vei, Orest Kupyn, Tetiana Martyniuk, Igor Krashenyi, and Jiři Matas. [[`paper`]](https://arxiv.org/abs/2112.07957) [[`Code`🌟]](https://github.com/PinataFarms/FEARTracker)

* [**CVPR'2022**] ***"Transforming Model Prediction for Tracking***", Christoph Mayer, Martin Danelljan, Goutam Bhat, Matthieu Paul, Danda Pani Paudel, Fisher Yu, and Luc Van Gool. [[`paper`]](https://arxiv.org/abs/2203.11192) [[`Code`🌟]](https://github.com/visionml/pytracking)

* [**CVPR'2022**] ***"Unsupervised Learning of Accurate Siamese Tracking***", Qiuhong Shen, Lei Qiao, Jinyang Guo, Peixia Li, Xin Li, Bo Li, Weitao Feng, Weihao Gan, Wei Wu, and Wanli Ouyang. [[`paper`]](https://arxiv.org/abs/2204.01475)

* [**CVPR'2022**] ***"Unified Transformer Tracker for Object Tracking***", Fan Ma, Mike Zheng Shou, Linchao Zhu, Haoqi Fan, Yilei Xu, Yi Yang, and Zhicheng Yan. [[`paper`]](https://arxiv.org/pdf/2203.15175) [[`Code`🌟]](https://github.com/Flowerfan/Trackron)

* [**CVPR'2022**] ***"Unsupervised Domain Adaptation for Nighttime Aerial Tracking***", Junjie Ye, Changhong Fu, Guangze Zheng, Danda Pani Paudel, and Guang Chen. [[`paper`]](https://arxiv.org/abs/2203.10541) [[`Code`🌟]](https://github.com/vision4robotics/UDAT)

* [**CVPR'2022**] ***"TCTrack: Temporal Contexts for Aerial Tracking***", Ziang Cao, Ziyuan Huang, Liang Pan, Shiwei Zhang, Ziwei Liu, and Changhong Fu. [[`paper`]](https://arxiv.org/abs/2203.01885) [[`Code`🌟]](https://github.com/vision4robotics/TCTrack)

* [**CVPR'2022**] ***"Correlation-Aware Deep Tracking***", Fei Xie, Chunyu Wang, Guangting Wang, Yue Cao, Wankou Yang, and Wenjun Zeng. [[`paper`]](https://arxiv.org/abs/2203.01666)

* [**CVPR'2022**] ***"Transformer Tracking With Cyclic Shifting Window Attention***", Zikai Song, Junqing Yu, Yi-Ping Phoebe Chen, and Wei Yang. [[`paper`]](https://arxiv.org/abs/2205.03806) [[`Code`🌟]](https://github.com/SkyeSong38/CSWinTT)

* [**CVPR'2022**] ***"Global Tracking via Ensemble of Local Trackers***", Zikun Zhou, Jianqiu Chen, Wenjie Pei, Kaige Mao, Hongpeng Wang, and Zhenyu He. [[`paper`]](https://arxiv.org/abs/2203.16092)

* [**CVPR'2022**] ***"MixFormer: End-to-End Tracking With Iterative Mixed Attention***", Yutao Cui, Cheng Jiang, Limin Wang, and Gangshan Wu. [[`paper`]](https://arxiv.org/abs/2203.11082) [[`Code`🌟]](https://github.com/MCG-NJU/MixFormer)

* [**CVPR'2022**] ***"Ranking-Based Siamese Visual Tracking***", Feng Tang and Qiang Ling. [[`paper`]](https://arxiv.org/abs/2205.11761) [[`Code`🌟]](https://github.com/sansanfree/RBO)

* [**NeurIPS'2021**] ***"Do Different Tracking Tasks Require Different Appearance Models?***", Zhongdao Wang, Hengshuang Zhao, Ya-Li Li, Shengjin Wang, Philip Torr, and Luca Bertinetto. [[`paper`]](https://proceedings.neurips.cc/paper_files/paper/2021/file/06997f04a7db92466a2baa6ebc8b872d-Paper.pdf) [[`Code`🌟]](https://zhongdao.github.io/UniTrack/)

* [**ICCV'2021**] ***"Learning Spatio-Temporal Transformer for Visual Tracking***", Bin Yan, Houwen Peng, Jianlong Fu, Dong Wang, and Huchuan Lu. [[`paper`]](https://arxiv.org/abs/2103.17154) [[`Code`🌟]](https://github.com/researchmm/Stark)

* [**ICCV'2021**] ***"Learn to Match: Automatic Matching Network Design for Visual Tracking***", Zhipeng Zhang, Yihao Liu, Xiao Wang, Bing Li, and Weiming Hu. [[`paper`]](https://arxiv.org/abs/2108.00803) [[`Code`🌟]](https://github.com/JudasDie/SOTS)

* [**ICCV'2021**] ***"High-Performance Discriminative Tracking with Transformers***", Bin Yu, Ming Tang, Linyu Zheng, Guibo Zhu, Jinqiao Wang, Hao Feng, Xuetao Feng, and Hanqing Lu. [[`paper`]](https://openaccess.thecvf.com/content/ICCV2021/papers/Yu_High-Performance_Discriminative_Tracking_With_Transformers_ICCV_2021_paper.pdf)

* [**ICCV'2021**] ***"HiFT: Hierarchical Feature Transformer for Aerial Tracking***", Ziang Cao, Changhong Fu, Junjie Ye, Bowen Li, and Yiming Li. [[`paper`]](https://arxiv.org/abs/2108.00803) [[`Code`🌟]](https://github.com/vision4robotics/HiFT)

* [**ICCV'2021**] ***"Learning Target Candidate Association to Keep Track of What Not to Track***", Christoph Mayer, Martin Danelljan, Danda Pani Paudel, and Luc Van Gool. [[`paper`]](https://arxiv.org/abs/2103.16556) [[`Code`🌟]](https://github.com/visionml/pytracking)

* [**ICCV'2021**] ***"Saliency-Associated Object Tracking***", Zikun Zhou, Wenjie Pei, Xin Li, Hongpeng Wang, Feng Zheng, and Zhenyu He. [[`paper`]](https://arxiv.org/abs/2108.03637) [[`Code`🌟]](https://github.com/ZikunZhou/SAOT)

* [**ICCV'2021**] ***"Learning to Track Objects from Unlabeled Videos***", Jilai Zheng, Chao Ma, Houwen Peng, and Xiaokang Yang. [[`paper`]](https://arxiv.org/abs/2108.12711) [[`Code`🌟]](https://github.com/VISION-SJTU/USOT)

* [**ICCV'2021**] ***"Transparent Object Tracking Benchmark***", Heng Fan, Halady Akhilesha Miththanthaya, Harshit, Siranjiv Ramana Rajan, Xiaoqiong Liu, Zhilin Zou, Yuewei Lin, and Haibin Ling. [[`paper`]](https://arxiv.org/abs/2011.10875) [[`Code and Dataset`🌟]](https://hengfan2010.github.io/projects/TOTB/)

* [**ICCV'2021**] ***"Video Annotation for Visual Tracking via Selection and Refinement***", Kenan Dai, Jie Zhao, Lijun Wang, Dong Wang, Jianhua Li, Huchuan Lu, Xuesheng Qian, and Xiaoyun Yang. [[`paper`]](https://arxiv.org/abs/2108.03821)

* [**ICCV'2021**] ***"Learning to Adversarially Blur Visual Object Tracking***", Qing Guo, Ziyi Cheng, Felix Juefei-Xu, Lei Ma, Xiaofei Xie, Yang Liu, and Jianjun Zhao. [[`paper`]](https://arxiv.org/abs/2107.12085) [[`Code`🌟]](https://github.com/tsingqguo/ABA)




#### `RGB-X Tracking (X as another vision modality)`

* [**ICML'2025**] ***"CSTrack: Enhancing RGB-X Tracking via Compact Spatiotemporal Features"***, Xiaokun Feng, Dailing Zhang, Shiyu Hu, Xuchen Li, Meiqi Wu, Jing Zhang, Xiaotang Chen, and Kaiqi Huang. [[`paper`]](https://arxiv.org/abs/2505.19434) [[`Code`🌟]](https://github.com/XiaokunFeng/CSTrack)

* [**CVPR'2025**] ***"Exploring Historical Information for RGBE Visual Tracking with Mamba***", Jiqing Zhang, Yang Wang, Huilin Ge, Qianchen Xia, Baocai Yin, and Xin Yang.

* [**CVPR'2025**] ***"MUST: The First Dataset and Unified Framework for Multispectral UAV Single Object Tracking***", Haolin Qin, Tingfa Xu, Tianhao Li, Zhenxiang Chen, Tao Feng, and Jianan Li.

* [**CVPR'2025**] ***"PURA: Parameter Update-Recovery Test-Time Adaption for RGB-T Tracking***", Zekai Shao, Yufan Hu, Bin Fan, and Hongmin Liu.
  
* [**NeurIPS'2024**] ***"Revisiting motion information for RGB-Event tracking with MOT philosophy***", Tianlu Zhang, Kurt Debattista, Qiang Zhang, Guiguang Ding, and Jungong Han.

* [**CVPR'2024**] ***"OneTracker: Unifying Visual Object Tracking with Foundation Models and Efficient Tuning***", Lingyi Hong, Shilin Yan, Renrui Zhang, Wanyun Li, Xinyu Zhou, Pinxue Guo, Kaixun Jiang, Yiting Chen, Jinglun Li, Zhaoyu Chen, and Wenqiang Zhang. [[`paper`]](https://arxiv.org/abs/2403.09634)

* [**CVPR'2024**] ***"Single-Model and Any-Modality for Video Object Tracking***", Jinxia Xie, Bineng Zhong, Zhiyi Mo, Shengping Zhang, Liangtao Shi, Shuxiang Song, and Rongrong Ji. [[`paper`]](https://arxiv.org/abs/2311.15851)

* [**CVPR'2024**] ***"SDSTrack: Self-Distillation Symmetric Adapter Learning for Multi-Modal Visual Object Tracking***", Xiaojun Hou, Jiazheng Xing, Yijie Qian, Yaowei Guo, Shuo Xin, Junhao Chen, Kai Tang, Mengmeng Wang, Zhengkai Jiang, Liang Liu, and Yong Liu. [[`paper`]](https://arxiv.org/abs/2403.16002) [[`Code`🌟]](https://github.com/hoqolo/SDSTrack)

* [**CVPR'2024**] ***"Event Stream-based Visual Object Tracking: A High-Resolution Benchmark Dataset and A Novel Baseline***", Xiao Wang, Shiao Wang, Chuanming Tang, Lin Zhu, Bo Jiang, Yonghong Tian, and Jin Tang, Mengmeng Wang, Zhengkai Jiang, Liang Liu, and Yong Liu. [[`paper`]](https://arxiv.org/abs/2309.14611) [[`Code and Dataset`🌟]](https://github.com/Event-AHU/EventVOT_Benchmark)

* [**CVPR'2023**] ***"Efficient RGB-T Tracking via Cross-Modality Distillation***", Tianlu Zhang, Hongyuan Guo, Qiang Jiao, Qiang Zhang, and Jungong Han. [[`paper`]](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Efficient_RGB-T_Tracking_via_Cross-Modality_Distillation_CVPR_2023_paper.pdf)

* [**CVPR'2023**] ***"Visual Prompt Multi-Modal Tracking***", Jiawen Zhu, Simiao Lai, Xin Chen, Dong Wang, and Huchuan Lu. [[`paper`]](https://arxiv.org/abs/2303.10826) [[`Code`🌟]](https://github.com/jiawen-zhu/ViPT)

* [**CVPR'2023**] ***"Bridging Search Region Interaction with Template for RGB-T Tracking***", Tianrui Hui, Zizheng Xun, Fengguang Peng, Junshi Huang, Xiaoming Wei, Xiaolin Wei, Jiao Dai, Jizhong Han, and Si Liu. [[`paper`]](https://openaccess.thecvf.com/content/CVPR2023/papers/Hui_Bridging_Search_Region_Interaction_With_Template_for_RGB-T_Tracking_CVPR_2023_paper.pdf) [[`Code`🌟]](https://github.com/RyanHTR/TBSI)

* [**CVPR'2023**] ***"Resource-Efficient RGBD Aerial Tracking***", Jinyu Yang, Shang Gao, Zhe Li, Feng Zheng, and Aleš Leonardis. [[`paper`]](https://openaccess.thecvf.com/content/CVPR2023/papers/Yang_Resource-Efficient_RGBD_Aerial_Tracking_CVPR_2023_paper.pdf)

* [**CVPR'2023**] ***"Frame-Event Alignment and Fusion Network for High Frame Rate Tracking***", Jiqing Zhang, Yuanchen Wang, Wenxi Liu, Meng Li, Jinpeng Bai, Baocai Yin, and Xin Yang. [[`paper`]](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Frame-Event_Alignment_and_Fusion_Network_for_High_Frame_Rate_Tracking_CVPR_2023_paper.pdf) [[`Code`🌟]](https://github.com/Jee-King/AFNet)

* [**NeurIPS'2022**] ***"Learning Graph-embedded Key-event Back-tracing for Object Tracking in Event Clouds***", Mingzhe Guo, Zhipeng Zhang, Heng Fan, and Liping Jing. [[`paper`]](https://openreview.net/forum?id=hTxYJAKY85)

* [**ECCV'2022**] ***"Towards Generic 3D Tracking in RGBD Videos: Benchmark and Baseline***", Jinyu Yang, Zhongqun Zhang, Zhe Li, Hyung Jin Chang, Aleš Leonardis, and Feng Zheng. [[`paper`]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820108.pdf)

* [**CVPR'2022**] ***"Spiking Transformers for Event-Based Single Object Tracking***", Jiqing Zhang, Bo Dong, Haiwei Zhang, Jianchuan Ding, Felix Heide, Baocai Yin, Xin Yang. [[`paper`]](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Spiking_Transformers_for_Event-Based_Single_Object_Tracking_CVPR_2022_paper.pdf) [[`Code`🌟]](https://github.com/Jee-King/CVPR2022_STNet)

* [**CVPR'2022**] ***"Visible-Thermal UAV Tracking: A Large-Scale Benchmark and New Baseline***", Pengyu Zhang, Jie Zhao, Dong Wang, Huchuan Lu, and Xiang Ruan. [[`paper`]](https://arxiv.org/abs/2204.04120) [[`Dataset`🌟]](https://zhang-pengyu.github.io/DUT-VTUAV/)

* [**ICCV'2021**] ***"Object Tracking by Jointly Exploiting Frame and Event Domain***", Jiqing Zhang, Xin Yang, Yingkai Fu, Xiaopeng Wei, Baocai Yin, and Bo Dong. [[`paper`]](https://arxiv.org/abs/2109.09052)

* [**ICCV'2022**] ***"DepthTrack : Unveiling the Power of RGBD Tracking***", Song Yan, Jinyu Yang, Jani Käpylä, Feng Zheng, Aleš Leonardis, and Joni-Kristian Kämäräinen. [[`paper`]](https://arxiv.org/abs/2108.13962) [[`Code and Dataset`🌟]](https://github.com/xiaozai/DeT)

* [**CVPR'2021**] ***"Learning to Filter: Siamese Relation Network for Robust Tracking***", Siyuan Cheng, Bineng Zhong, Guorong Li, Xin Liu, Zhenjun Tang, Xianxian Li, and Jing Wan. [[`paper`]](https://arxiv.org/abs/2104.00829)

* [**CVPR'2021**] ***"STMTrack: Template-free Visual Tracking with Space-time Memory Networks***", Zhihong Fu, Qingjie Liu, Zehua Fu, and Yunhong Wang. [[`paper`]](https://arxiv.org/abs/2104.00324) [[`Code`🌟]](https://github.com/fzh0917/STMTrack)

* [**CVPR'2021**] ***"Transformer Tracking***", Xin Chen, Bin Yan, Jiawen Zhu, Dong Wang, Xiaoyun Yang, and Huchuan Lu. [[`paper`]](https://arxiv.org/abs/2103.15436) [[`Code`🌟]](https://github.com/chenxin-dlut/TransT)

* [**CVPR'2021**] ***"LightTrack: Finding Lightweight Neural Networks for Object Tracking via One-Shot Architecture Search***", Bin Yan, Houwen Peng, Kan Wu, Dong Wang, Jianlong Fu, and Huchuan Lu. [[`paper`]](https://arxiv.org/abs/2104.14545) [[`Code`🌟]](https://github.com/researchmm/LightTrack)

* [**CVPR'2021**] ***"Alpha-Refine: Boosting Tracking Performance by Precise Bounding Box Estimation***", Bin Yan, Xinyu Zhang, Dong Wang, Huchuan Lu, and Xiaoyun Yang. [[`paper`]](https://arxiv.org/abs/2012.06815) [[`Code`🌟]](https://github.com/MasterBin-IIAU/AlphaRefine)

* [**CVPR'2021**] ***"Graph Attention Tracking***", Dongyan Guo, Yanyan Shao, Ying Cui, Zhenhua Wang, Liyan Zhang, and Chunhua Shen. [[`paper`]](https://arxiv.org/abs/2011.11204) [[`Code`🌟]](https://github.com/ohhhyeahhh/SiamGAT)

* [**CVPR'2021**] ***"Transformer Meets Tracker: Exploiting Temporal Context for Robust Visual Tracking***", Ning Wang, Wengang Zhou, Jie Wang, and Houqaing Li. [[`paper`]](https://arxiv.org/abs/2103.11681) [[`Code`🌟]](https://github.com/594422814/TransformerTrack)

* [**CVPR'2021**] ***"Distractor-Aware Fast Tracking via Dynamic Convolutions and MOT Philosophy***", Zikai Zhang, Bineng Zhong, Shengping Zhang, Zhenjun Tang, Xin Liu, and Zhaoxiang Zhang. [[`paper`]](https://arxiv.org/abs/2104.12041) [[`Code`🌟]](https://github.com/hqucv/dmtrack)

* [**CVPR'2021**] ***"CapsuleRRT: Relationships-Aware Regression Tracking via Capsules***", Ding Ma and Xiangqian Wu. [[`paper`]](https://openaccess.thecvf.com/content/CVPR2021/papers/Ma_CapsuleRRT_Relationships-Aware_Regression_Tracking_via_Capsules_CVPR_2021_paper.pdf)

* [**CVPR'2021**] ***"CapsuleRRT: Relationships-Aware Regression Tracking via Capsules***", Qiangqiang Wu, Jia Wan, and Antoni B. Chan. [[`paper`]](https://openaccess.thecvf.com/content/CVPR2021/papers/Wu_Progressive_Unsupervised_Learning_for_Visual_Object_Tracking_CVPR_2021_paper.pdf)

* [**CVPR'2021**] ***"IoU Attack: Towards Temporally Coherent Black-Box Adversarial Attack for Visual Object Tracking***", Shuai Jia, Yibing Song, Chao Ma, and Xiaokang Yang. [[`paper`]](https://arxiv.org/abs/2103.14938) [[`Code`🌟]](https://github.com/VISION-SJTU/IoUattack)

* [**CVPR'2021**] ***"Rotation Equivariant Siamese Networks for Tracking***", Deepak K. Gupta, Devanshu Arya, Efstratios Gavves. [[`paper`]](https://arxiv.org/abs/2012.13078)






#### `Vision-Language Tracking`

* [**CVPR'2025**] ***"DreamTrack: Dreaming the Future for Multimodal Visual Object Tracking***", Mingzhe Guo, Weiping Tan, Wenyu Ran, Liping Jing, and Zhipeng Zhang.

* [**CVPR'2025**] ***"MambaVLT: Time-Evolving Multimodal State Space Model for Vision-Language Tracking***", Xinqi Liu, Li Zhou, Zikun Zhou, Jianqiu Chen, and Zhenyu He.

* [**CVPR'2025**] ***"JTD-UAV: MLLM-Enhanced Joint Tracking and Description Framework for Anti-UAV Systems***", Yifan Wang, Jian Zhao, Zhaoxin Fan, Xin Zhang, Xuecheng Wu, Yudian Zhang, Lei Jin, Xinyue Li, Gang Wang, Mengxi Jia, Ping Hu, Zheng Zhu, and Xuelong Li.
  
* [**CVPR'2025**] ***"Dynamic Updates for Language Adaptation in Visual-Language Tracking***", Xiaohai Li, Bineng Zhong, Qihua Liang, Zhiyi Mo, Jian Nong, and Shuxiang Song.

* [**NeurIPS'2024**] ***"MemVLT: Vision-Language Tracking with Adaptive Memory-based Prompts***", Xiaokun Feng, Xuchen Li, Shiyu Hu, Dailing Zhang, Meiqi Wu, Jing Zhang, Xiaotang Chen, and Kaiqi Huang.

* [**NeurIPS'2024**] ***"ChatTracker: Enhancing Visual Tracking Performance via Chatting with Multimodal Large Language Model***", Yiming Sun, Fan Yu, Shaoxiang Chen, Yu Zhang, Junwei Huang, Yang Li, Chenhui Li, and Changbo Wang. 

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

* [**NeurIPS'2022**] ***"Divert More Attention to Vision-Language Tracking***", Mingzhe Guo, Zhipeng Zhang, Heng Fan, and Liping Jing. [[`paper`]](https://arxiv.org/abs/2207.01076) [[`Code`🌟]](https://github.com/JudasDie/SOTS)

* [**CVPR'2021**] ***"Towards More Flexible and Accurate Object Tracking With Natural Language: Algorithms and Benchmark***", Xiao Wang, Xiujun Shu, Zhipeng Zhang, Bo Jiang, Yaowei Wang, Yonghong Tian, and Feng Wu. [[`paper`]](https://arxiv.org/abs/2103.16746) [[`Dataset`🌟]](https://github.com/wangxiao5791509/TNL2K_evaluation_toolkit)

* [**CVPR'2021**] ***"Siamese Natural Language Tracker: Tracking by Natural Language Descriptions with Siamese Trackers***", Qi Feng, Vitaly Ablavsky, Qinxun Bai, and Stan Sclaroff. [[`paper`]](https://arxiv.org/abs/1912.02048) [[`Dataset`🌟]](https://github.com/fredfung007/snlt)





#### `Lidar-based 3D Object Tracking`
* [**ECCV'2024**] ***"3D Single-object Tracking in Point Clouds with High Temporal Variation***", Qiao Wu, Kun Sun, Pei An, Mathieu Salzmann, Yanning Zhang, and Jiaqi Yang.
  [[`paper`]](https://arxiv.org/pdf/2408.02049)
  
* [**ECCV'2024**] ***"Boosting 3D Single Object Tracking with 2D Matching Distillation and 3D Pre-training***", Qiangqiang Wu, Yan Xia, Jia Wang, and Antoni B Chan.
  [[`paper`]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/01900.pdf)

* [**ICLR'2024**] ***"Towards Category Unification of 3D Single Object Tracking on Point Clouds***", Jiahao Nie, Zhiwei He, Xudong Lv, Xueyi Zhou, Dong-Kyu Chae, and Fei Xie. [[`paper`]](https://arxiv.org/abs/2401.11204)

* [**ICCV'2023**] ***"MBPTrack: Improving 3D Point Cloud Tracking with Memory Networks and Box Priors***", Tian-Xing Xu, Yuan-Chen Guo, Yu-Kun Lai, and Song-Hai Zhang. [[`paper`]](https://arxiv.org/abs/2303.05071)

* [**ICCV'2023**] ***"Synchronize Feature Extracting and Matching: A Single Branch Framework for 3D Object Tracking***", Teli Ma, Mengmeng Wang, Jimin Xiao, Huifeng Wu, and Yong Liu. [[`paper`]](https://arxiv.org/abs/2308.12549)

* [**CVPR'2023**] ***"CXTrack: Improving 3D Point Cloud Tracking with Contextual Information***", Tian-Xing Xu, Yuan-Chen Guo, Yu-Kun Lai, and Song-Hai Zhang. [[`paper`]](https://arxiv.org/abs/2211.08542) [[`Code`🌟]](https://github.com/slothfulxtx/cxtrack3d)

* [**ECCV'2022**] ***"3D Siamese Transformer Network for Single Object Tracking on Point Clouds***", Le Hui, Lingpeng Wang, Linghua Tang, Kaihao Lan, Jin Xie, and Jian Yang. [[`paper`]](https://arxiv.org/abs/2207.11995) [[`Code`🌟]](https://github.com/fpthink/STNet)

* [**ECCV'2022**] ***"CMT: Context-Matching-Guided Transformer for 3D Tracking in Point Clouds***", Zhiyang Guo, Yunyao Mao, Wengang Zhou, Min Wang, and Houqiang Li. [[`paper`]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820091.pdf)

* [**CVPR'2022**] ***"PTTR: Relational 3D Point Cloud Object Tracking With Transformer***", Changqing Zhou, Zhipeng Luo, Yueru Luo, Tianrui Liu, Liang Pan, Zhongang Cai, Haiyu Zhao, and Shijian Lu. [[`paper`]](https://arxiv.org/abs/2112.02857) [[`Code`🌟]](https://github.com/Jasonkks/PTTR)

* [**CVPR'2022**] ***"Beyond 3D Siamese Tracking: A Motion-Centric Paradigm for 3D Single Object Tracking in Point Clouds***", Chaoda Zheng, Xu Yan, Haiming Zhang, Baoyuan Wang, Shenghui Cheng, Shuguang Cui, and Zhen Li. [[`paper`]](https://arxiv.org/abs/2203.01730) [[`Code`🌟]](https://github.com/Ghostish/Open3DSOT)

* [**NeurIPS'2021**] ***"3D Siamese Voxel-to-BEV Tracker for Sparse Point Clouds***", Le Hui, Lingpeng Wang, Mingmei Cheng, Jin Xie, and Jian Yang. [[`paper`]](https://arxiv.org/abs/2111.04426)

* [**ICCV'2021**] ***"MLVSNet: Multi-level Voting Siamese Network for 3D Visual Tracking***", Zhoutao Wang, Qian Xie, Yu-Kun Lai, Jing Wu, Kun Long, and Jun Wang. [[`paper`]](https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_MLVSNet_Multi-Level_Voting_Siamese_Network_for_3D_Visual_Tracking_ICCV_2021_paper.pdf)

* [**ICCV'2021**] ***"Box-Aware Feature Enhancement for Single Object Tracking on Point Clouds***", Chaoda Zheng, Xu Yan, Jiantao Gao, Weibing Zhao, Wei Zhang, Zhen Li, and Shuguang Cui. [[`paper`]](https://arxiv.org/abs/2108.04728) [[`Code`🌟]](https://github.com/Ghostish/Open3DSOT)


## Acknowledgements

We draw some inspirations from the following excellent repositories (thanks!):

* [Visual Tracking Development](https://github.com/DavidZhangdw/Visual-Tracking-Development)

* [Long-term Visual Tracking](https://github.com/wangdongdut/Long-term-Visual-Tracking)

* [Online Visual Tracking-SOTA](https://github.com/wangdongdut/Online-Visual-Tracking-SOTA)

* [Visual Tracking Paper List](https://github.com/foolwood/benchmark_results)

* [Transformer Tracking](https://github.com/Little-Podi/Transformer_Tracking)

