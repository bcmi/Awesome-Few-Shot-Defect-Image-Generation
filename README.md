# Awesome Few-Shot Defect Image Generation  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of resources including papers, datasets, and relevant links pertaining to few-shot defect image generation.Few-shot defect image generation aims to synthesize diverse and realistic defect images using only a limited number of annotated anomaly samples. It primarily focuses on augmenting data for industrial scenarios to improve downstream tasks such as anomaly detection, localization, and segmentation, despite severe data scarcity.

## Contributing

Contributions are welcome.  If you wish to contribute, feel free to send a pull request. If you have suggestions for new sections to be included, please raise an issue and discuss before sending a pull request.

## Table of Contents
+ [Surveys](#Surveys)
+ [Papers](#Papers)
+ [Datasets](#Datasets)
+ [Other Resources](#Other-resources)

## Surveys
+ Yunkang Cao, Xiaohao Xu, Jiangning Zhang, Yuqi Cheng, Xiaonan Huang, Guansong Pang, Weiming Shen: "*A Survey on Visual Anomaly Detection: Challenge, Approach, and Prospect.*" arXiv (2024) [[pdf]](https://arxiv.org/pdf/2401.16402)
+ Yang Liu, Jing Liu, Chengfang Li, Rui Xi, Wenchao Li, Liang Cao, Jin Wang, Laurence T. Yang, Junsong Yuan, Wei Zhou: "*Anomaly Detection and Generation with Diffusion Models: A Survey.*" arXiv (2025) [[pdf]](https://arxiv.org/pdf/2506.09368)

## Papers

### Non-generative methods
+ Dongyun Lin, Yanpeng Cao, Wenbing Zhu, Yiqun Li: "*Few-Shot Defect Segmentation Leveraging Abundant Normal Training Samples Through Normal Background Regularization and Crop-and-Paste Operation.*" ICME (2021) [[pdf]](https://arxiv.org/pdf/2007.09438)
+ Vitjan Zavrtanik, Matej Kristan, Danijel Skočaj: "*DRAEM -- A discriminatively trained reconstruction embedding for surface anomaly detection.*" ICCV (2021) [[pdf]](https://arxiv.org/pdf/2108.07610) [[code]](https://github.com/VitjanZ/DRAEM)
+ Chun-Liang Li, Kihyuk Sohn, Jinsung Yoon, Tomas Pfister: "*CutPaste: Self-Supervised Learning for Anomaly Detection and Localization.*" CVPR (2021) [[pdf]](https://arxiv.org/pdf/2104.04015) [[code]](https://github.com/LilitYolyan/CutPaste)
+ Hui Zhang, Zuxuan Wu, Zheng Wang, Zhineng Chen, Yu-Gang Jiang: "*Prototypical Residual Networks for Anomaly Detection and Localization.*" CVPR (2023) [[pdf]](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Prototypical_Residual_Networks_for_Anomaly_Detection_and_Localization_CVPR_2023_paper.pdf) [[code]](https://github.com/xcyao00/PRNet)

### Generative methods

#### GAN-based methods
+ Shuanlong Niu, Bin Li, Xinggang Wang, HuiLin: "*Defect Image Sample Generation With GAN for Improving Defect Recognition.*" IEEE TASE (2020) [[pdf]](https://ieeexplore.ieee.org/abstract/document/9000806)
+ Gongjie Zhang, Kaiwen Cui, Tzu-Yi Hung, Shijian Lu: "*Defect-GAN: High-Fidelity Defect Synthesis for Automated Defect Inspection.*" WACV (2021) [[pdf]](https://openaccess.thecvf.com/content/WACV2021/papers/Zhang_Defect-GAN_High-Fidelity_Defect_Synthesis_for_Automated_Defect_Inspection_WACV_2021_paper.pdf)
+ Yuxuan Duan, Yan Hong, Li Niu, Liqing Zhang: "*Few-Shot Defect Image Generation via Defect-Aware Feature Manipulation.*" AAAI (2023) [[pdf]](https://arxiv.org/pdf/2303.02389) [[code]](https://github.com/Ldhlwh/DFMGAN)

#### Diffusion-based methods

##### SD-based methods
+ Musawar Ali, Nicola Fioraio, Samuele Salti, Luigi Di Stefano: "AnomalyControl: Few-Shot Anomaly Generation by ControlNet Inpainting.*" IEEE Access (2024) [[pdf]](https://ieeexplore.ieee.org/document/10806704)
+ Qianzi Yu, Kai Zhu, Yang Cao, Feijie Xia, Yu Kang: "*TF²: Few-Shot Text-Free Training-Free Defect Image Generation for Industrial Anomaly Inspection.*" IEEE TCSVT (2024) [[pdf]](https://ieeexplore.ieee.org/document/10587314)
+ Adnan Md Tayeb, Hope Leticia Nakayiza , Heejae Shin, Seungmin Lee, Chaesoo Lee, YeongHun Lee, Dong-Seong Kim, Jae-Min Lee: "*DefectGen: Few-Shot Defect Image Generation
 Using Stable Diffusion for Steel Surface Analysis.*" IEEE ICTC (2024) [[pdf]](https://ieeexplore.ieee.org/abstract/document/10827273)
+ Guan Gui, Bin-Bin Gao, Jun Liu, Chengjie Wang, Yunsheng Wu: "*Few-Shot Anomaly-Driven Generation for Anomaly Classification and Segmentation.*" ECCV (2024) [[pdf]](https://arxiv.org/pdf/2505.09263) [[code]](https://github.com/gaobb/AnoGen)
+ Qingfeng Shi, Jing Wei, Fei Shen, Zhengtao Zhang: "*Few-shot Defect Image Generation based on Consistency Modeling.*" ECCV (2024) [[pdf]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/09803.pdf) [[code]](https://github.com/FFDD-diffusion/DefectDiffu)
+ Shuai Yang, Zhifei Chen, Pengguang Chen, Xi Fang, Yixun Liang, Shu Liu, Yingcong Chen: "*Defect Spectrum: A Granular Look of Large-Scale Defect Datasets with Rich Semantics.*" ECCV (2024) [[pdf]](https://arxiv.org/pdf/2310.17316) [[code]](https://github.com/EnVision-Research/Defect_Spectrum)
+ Teng Hu, Jiangning Zhang, Ran Yi, Yuzhen Du, Xu Chen, Liang Liu, Yabiao Wang, Chengjie Wang: "*AnomalyDiffusion: Few-Shot Anomaly Image Generation with Diffusion Model.*" AAAI (2024) [[pdf]](https://arxiv.org/pdf/2312.05767) [[code]](https://github.com/sjtuplayer/anomalydiffusion)
+ Ximiao Zhang, Min Xu, Xiuzhuang Zhou: "*RealNet: A Feature Selection Network with Realistic Synthetic Anomaly for Anomaly Detection.*" CVPR (2024) [[pdf]](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhang_RealNet_A_Feature_Selection_Network_with_Realistic_Synthetic_Anomaly_for_CVPR_2024_paper.pdf) [[code]](https://github.com/cnulab/RealNet)
+ Zhewei Dai, Shilei Zeng, Haotian Liu, Xurui Li, Feng Xue, Yu Zhou: "*SeaS: Few-shot Industrial Anomaly Image Generation with Separation and Sharing Fine-tuning.*" ICCV (2025) [[pdf]](https://arxiv.org/pdf/2410.14987) [[code]](https://github.com/HUST-SLOW/SeaS)
+ Ying Jin, Jinlong Peng, Qingdong He, Teng Hu, Jiafu Wu, Hao Chen, Haoxuan Wang, Wenbing Zhu, Mingmin Chi, Jun Liu, Yabiao Wang: "*Dual-Interrelated Diffusion Model for Few-Shot Anomaly Image Generation.*" CVPR (2025) [[pdf]](https://openaccess.thecvf.com/content/CVPR2025/papers/Jin_Dual-Interrelated_Diffusion_Model_for_Few-Shot_Anomaly_Image_Generation_CVPR_2025_paper.pdf) [[code]](https://github.com/yinyjin/DualAnoDiff)
+ Han Sun, Yunkang Cao, Hao Dong, Olga Fink: "*Unseen Visual Anomaly Generation.*" CVPR (2025) [[pdf]](https://openaccess.thecvf.com/content/CVPR2025/papers/Sun_Unseen_Visual_Anomaly_Generation_CVPR_2025_paper.pdf) [[code]](https://github.com/EPFL-IMOS/AnomalyAny)

##### FLUX-based methods
#### Other-based methods
+ Hannah M. Schlüter, Jeremy Tan, Benjamin Hou, Bernhard Kainz: "*Natural Synthetic Anomalies for Self-Supervised Anomaly Detection and Localization.*" ECCV (2022) [[pdf]](https://arxiv.org/pdf/2109.15222) [[code]](https://github.com/hmsch/natural-synthetic-anomalies)

## Datasets
+ MVTec AD:  5354 high-resolution RGB images across 15 categories — 10 object classes (e.g., bottle, cable, metal nut) and 5 texture classes (e.g., carpet, leather, tile). Each category includes a variety of anomaly types such as scratches, dents, contaminations, or missing parts, totaling 73 distinct defect types. [[link]](https://www.mvtec.com/company/research/datasets/mvtec-ad/)
+ VisA:  12 subsets with 10,821 images (9,621 normal, 1,200 anomalous) covering diverse objects. Anomalies involve surface defects like scratches and dents, and structural defects such as misplacement or missing parts. [[link]](https://github.com/amazon-science/spot-diff)
+ MVTec 3D-AD:  over 4,000 high-resolution 3D scans across 10 object categories for unsupervised 3D anomaly detection and localization, with defect-free training data, defective test samples, and precise ground-truth annotations. [[link]](https://www.mvtec.com/company/research/datasets/mvtec-3d-ad)
+ Kaputt:  a large-scale and realistic dataset for visual defect detection, containing 238K images, 29K defective samples, and 48K unique items with detailed annotations. It features diverse appearances, poses, and real-world noise, offering a challenging benchmark that exposes the limitations of current defect detection methods. [[link]](https://www.kaputt-dataset.com/)
## Other-resources
