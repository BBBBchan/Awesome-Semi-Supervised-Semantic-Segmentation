# Awesome-Semi-Supervised-Semantic-Segmentation 

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/BBBBchan/Awesome-Semi-Supervised-Semantic-Segmentation/graphs/commit-activity)

This is a summary of recent semi-supervised semantic segmentation methods. Plese feel free to contact me (sbysbysby123@gmail.com) if I miss some papers. Issues and PRs are also welcomed! 


*NOTE:*  The methods of semi-supervised medical segmentation methods are not included, you can find them [here](https://github.com/HiLab-git/SSL4MIS). As for general semi-supervised learning, you can refer to [this repo](https://github.com/yassouali/awesome-semi-supervised-learning).

## 2022
| Title| Abbreviation| Published | &emsp;&emsp;Dataset&emsp;&emsp;| CODE | PDF             |
| :---------| :------------------------------:| :----------------------: | :-------------------------------------------------------------------------:| :--------------------: |  :--------------- |  
|Transformer-CNN Cohort: Semi-supervised Semantic Segmentation by the Best of Both Students | TCC|Arxiv 2022|PASCAL VOC 2012, Cityscapes|-|[Paper](https://arxiv.org/pdf/2209.02178.pdf)
|Revisiting Weak-to-Strong Consistency in Semi-Supervised Semantic Segmentation|UniMatch|Arxiv 2022|PASCAL VOC 2012, Cityscapes, MS COCO|[Code](https://github.com/LiheYoung/UniMatch)![Github stars](https://img.shields.io/github/stars/LiheYoung/UniMatch)| [Paper](https://arxiv.org/pdf/2208.09910.pdf)|
|Multi-View Correlation Consistency for Semi-Supervised Semantic Segmentation|MVCC|Arxiv 2022|PASCAL VOC 2012, Cityscapes|-|[Paper](https://arxiv.org/pdf/2208.08437.pdf)|
|Semi-supervised Semantic Segmentation with Prototype-based Consistency Regularization|-|NeurIPS 2022|PASCAL VOC 2012, Cityscapes|[Code](https://github.com/HeimingX/semi_seg_proto)![Github stars](https://img.shields.io/github/stars/HeimingX/semi_seg_proto)|[Paper](https://arxiv.org/pdf/2210.04388.pdf)|
|Learning from Future: A Novel Self-Training Framework for Semantic Segmentation|FST| NeurIPS 2022|PASCAL VOC 2012| [Code](https://github.com/usr922/FST)![Github stars](https://img.shields.io/github/stars/usr922/FST)|[Paper](https://arxiv.org/pdf/2209.06993.pdf)|
|Semi-supervised 3D shape segmentation with multilevel consistency and part substitution|-|CVM 2022|PartNet,  ShapeNetPart, ScanNet|[Code](https://github.com/isunchy/semi_supervised_3d_segmentation)![Github stars](https://img.shields.io/github/stars/isunchy/semi_supervised_3d_segmentation)|[Paper](https://arxiv.org/pdf/2204.08824.pdf)|
|Semi-Supervised Semantic Segmentation with Cross Teacher Training|CTT|Neurocomputing 2022|PASCAL VOC 2012, Cityscapes|-|[Paper](https://arxiv.org/pdf/2209.01327.pdf)|
|Region-level Contrastive and Consistency Learning for Semi-Supervised Semantic Segmentation|RC2L|IJCAI 2022|PASCAL VOC 2012, Cityscapes|-|[Paper](https://arxiv.org/pdf/2204.13314.pdf)|
|One Weird Trick to Improve Your Semi-Weakly Supervised Semantic Segmentation Model|-|IJCAI 2022|PASCAL VOC 2012|-|[Paper](https://arxiv.org/pdf/2205.01233.pdf)|
|Multi-Granularity Distillation Scheme Towards Lightweight Semi-Supervised Semantic Segmentation|MGD |ECCV 2022|PASCAL VOC 2012, Cityscapes|-|[Paper](https://arxiv.org/pdf/2208.10169.pdf)|
|Learning Self-Supervised Low-Rank Network for Single-Stage Weakly and Semi-Supervised Semantic Segmentation|SLRNet|IJCV 2022| Pascal VOC 2012, L2ID, MS COCO |[Code](https://github.com/DesertsP/SLRNet)![Github stars](https://img.shields.io/github/stars/DesertsP/SLRNet)|[Paper](https://arxiv.org/pdf/2203.10278.pdf)|
|Semi-Supervised Semantic Segmentation Using Unreliable Pseudo-Labels |U2PL  |CVPR 2022 |PASCAL VOC 2012  | [Code](https://github.com/Haochen-Wang409/U2PL)![Github stars](https://img.shields.io/github/stars/Haochen-Wang409/U2PL)| [Paper](https://arxiv.org/pdf/2203.03884.pdf)|
|Semi-supervised Semantic Segmentation with Error Localization Network | ELN |CVPR 2022| PASCAL VOC 2012, Cityscapes| [Code](https://github.com/kinux98/SSL_ELN)![Github stars](https://img.shields.io/github/stars/kinux98/SSL_ELN)|[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Kwon_Semi-Supervised_Semantic_Segmentation_With_Error_Localization_Network_CVPR_2022_paper.pdf)|
|UCC: Uncertainty guided Cross-head Co-training for Semi-Supervised Semantic Segmentation| UCC|CVPR 2022|PASCAL VOC 2012, Cityscapes|-|[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Fan_UCC_Uncertainty_Guided_Cross-Head_Co-Training_for_Semi-Supervised_Semantic_Segmentation_CVPR_2022_paper.pdf)|
|Perturbed and Strict Mean Teachers for Semi-supervised Semantic Segmentation|PS-MT | CVPR 2022|PASCAL VOC 2012, Cityscapes|[Code](https://github.com/yyliu01/ps-mt)![Github stars](https://img.shields.io/github/stars/yyliu01/ps-mt)|[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Perturbed_and_Strict_Mean_Teachers_for_Semi-Supervised_Semantic_Segmentation_CVPR_2022_paper.pdf)|
|Unbiased Subclass Regularization for Semi-Supervised Semantic Segmentation|USRN|CVPR 2022|PASCAL VOC 2012, Cityscapes|[Code](https://github.com/Dayan-Guan/USRN)![Github stars](https://img.shields.io/github/stars/Dayan-Guan/USRN)|[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Guan_Unbiased_Subclass_Regularization_for_Semi-Supervised_Semantic_Segmentation_CVPR_2022_paper.pdf)|
|ST++: Make Self-training Work Better for Semi-supervised Semantic Segmentation|ST/ST++| CVPR 2022|PASCAL VOC 2012, Cityscapes|[Code](https://github.com/LiheYoung/ST-PlusPlus)![Github stars](https://img.shields.io/github/stars/LiheYoung/ST-PlusPlus)|[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Yang_ST_Make_Self-Training_Work_Better_for_Semi-Supervised_Semantic_Segmentation_CVPR_2022_paper.pdf)|
|Semi-Supervised Video Semantic Segmentation with Inter-Frame Feature Reconstruction| IRF | CVPR 2022| Cityscapes, CamVid| [Code](https://github.com/jfzhuang/IFR)![Github stars](https://img.shields.io/github/stars/jfzhuang/IFR)|[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhuang_Semi-Supervised_Video_Semantic_Segmentation_With_Inter-Frame_Feature_Reconstruction_CVPR_2022_paper.pdf)|
|Noisy Boundaries: Lemon or Lemonade for Semi-supervised Instance Segmentation?|-|CVPR 2022| Cityscapes, MS COCO,BDD100K|[Code](https://github.com/zhenyuw16/noisyboundaries)![Github stars](https://img.shields.io/github/stars/zhenyuw16/noisyboundaries)|[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Noisy_Boundaries_Lemon_or_Lemonade_for_Semi-Supervised_Instance_Segmentation_CVPR_2022_paper.pdf)|
|TWIST: Two-Way Inter-label Self-Training for Semi-supervised 3D Instance Segmentation|TWIST |CVPR 2022|ScanNet v2,  S3DIS| - |[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Chu_TWIST_Two-Way_Inter-Label_Self-Training_for_Semi-Supervised_3D_Instance_Segmentation_CVPR_2022_paper.pdf)
|Adversarial Dual-Student with Differentiable Spatial Warping for Semi-Supervised Semantic Segmentation|DGW|TCSVT 2022| PASCAL VOC 2012, Cityscapes|[Code](https://github.com/cao-cong/ADS-SemiSeg)![Github stars](https://img.shields.io/github/stars/cao-cong/ADS-SemiSeg)|[Paper](https://arxiv.org/pdf/2203.02792.pdf)|
|Semi-supervision semantic segmentation with uncertainty-guided self cross supervision|USCS|Arxiv 2022|PASCAL VOC 2012|-|[Paper](https://arxiv.org/pdf/2203.05118.pdf)|
|GuidedMix-Net: Semi-supervised Semantic Segmentation by Using Labeled Images as Reference| GuidedMix-Net|AAAI 2022|PASCAL VOC 2012, Cityscapes|-|[Paper](https://arxiv.org/pdf/2112.14015)|
|Active Learning for Improved Semi-Supervised Semantic Segmentation in Satellite Images|-|WACV 2022|UCM, deepglobe|[Code](https://github.com/immuno121/ALS4GAN)![Github stars](https://img.shields.io/github/stars/immuno121/ALS4GAN)|[Paper](https://arxiv.org/pdf/2110.07782.pdf)|
|The GIST and RIST of Iterative Self-Training for Semi-Supervised Segmentation|GIST RIST|CRV 2022|PASCAL VOC 2012, Cityscapes|-|[Paper](https://arxiv.org/pdf/2103.17105.pdf)|

## 2021

| Title| Abbreviation| Published | &emsp;&emsp;Dataset&emsp;&emsp;| CODE | PDF             |
| :---------| :------------------------------:| :----------------------: | :-------------------------------------------------------------------------:| :--------------------: |  :--------------- |  
|n-CPS: Generalising Cross Pseudo Supervision to n Networks for Semi-Supervised Semantic Segmentation|n-CPS|Arxiv 2021|PASCAL VOC 2012, Cityscapes|-|[Paper](https://arxiv.org/pdf/2112.07528.pdf)|
|Revisiting consistency for semi-supervised semantic segmentation|-|Arxiv 2021|Cityscapes|-|[Paper](https://arxiv.org/pdf/2106.07075.pdf)|
|Robust Mutual Learning for Semi-supervised Semantic Segmentation|-|Arxiv 2021|PASCAL VOC 2012, Cityscapes|-|[Paper](https://arxiv.org/pdf/2106.00609.pdf)|
|Mask-based Data Augmentation for Semi-supervised Semantic Segmentation| ComplexMix |Arxiv 2021|Cityscapes|-|[Paper](https://arxiv.org/pdf/2101.10156.pdf)|
|Semi-Supervised Semantic Segmentation via Adaptive Equalization Learning|AEL|NeurIPS 2021|PASCAL VOC 2012, Cityscapes|[Code](https://github.com/hzhupku/SemiSeg-AEL)![Github stars](https://img.shields.io/github/stars/immuno121/ALS4GAN)|[Paper](https://arxiv.org/pdf/2110.05474.pdf)|
|Colour augmentation for improved semi-supervised semantic segmentation|-|Arxiv 2021|PASCAL VOC 2012, Cityscapes|-|[Paper](https://arxiv.org/pdf/2110.04487.pdf)|
| C3-SemiSeg: Contrastive Semi-supervised Segmentation via Cross-set Learning and Dynamic Class-balancing|C3-SemiSeg|ICCV 2021|Cityscapes, BDD100K|[Code](https://github.com/SIAAAAAA/C3-SemiSeg)![Github stars](https://img.shields.io/github/stars/SIAAAAAA/C3-SemiSeg)|[Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhou_C3-SemiSeg_Contrastive_Semi-Supervised_Segmentation_via_Cross-Set_Learning_and_Dynamic_Class-Balancing_ICCV_2021_paper.pdf)|
|A Simple Baseline for Semi-supervised Semantic Segmentation with Strong Data Augmentation|-|ICCV 2021|PASCAL VOC 2012, Cityscapes|[Code](https://github.com/jianlong-yuan/SimpleBaseline)![Github stars](https://img.shields.io/github/stars/jianlong-yuan/SimpleBaseline)|[Paper](https://arxiv.org/pdf/2104.07256.pdf)|
|Semi-Supervised Semantic Segmentation with Pixel-Level Contrastive Learning from a Class-wise Memory Bank|-|ICCV 2021|PASCAL VOC 2012, Cityscapes|[Code](https://github.com/Shathe/SemiSeg-Contrastive)![Github stars](https://img.shields.io/github/stars/Shathe/SemiSeg-Contrastive)|[Paper](https://arxiv.org/pdf/2104.13415.pdf)|
|Pixel Contrastive-Consistent Semi-Supervised Semantic Segmentation|P2Seg|ICCV 2021|PASCAL VOC 2012, Cityscapes, MS COCO|-|[Paper](https://arxiv.org/pdf/2108.09025.pdf)|
|Re-distributing Biased Pseudo Labels for Semi-supervised Semantic Segmentation: A Baseline Investigation|DARS|ICCV 2021|PASCAL VOC 2012, Cityscapes|[Code](https://github.com/CVMI-Lab/DARS)![Github stars](https://img.shields.io/github/stars/CVMI-Lab/DARS)|[Paper](https://arxiv.org/pdf/2107.11279.pdf)|
|Semi-supervised Semantic Segmentation with Directional Context-aware Consistency|-|CVPR 2021|PASCAL VOC 2012, Cityscapes|[Code](https://github.com/dvlab-research/Context-Aware-Consistency)![Github stars](https://img.shields.io/github/stars/dvlab-research/Context-Aware-Consistency)|[Paper](https://arxiv.org/pdf/2106.14133.pdf)|
|Semi-Supervised Semantic Segmentation with Cross Pseudo Supervision|CPS|CVPR 2021|PASCAL VOC 2012, Cityscapes|[Code](https://github.com/charlesCXK/TorchSemiSeg)![Github stars](https://img.shields.io/github/stars/charlesCXK/TorchSemiSeg)|[Paper](https://arxiv.org/pdf/2106.01226.pdf)|
|Anti-Adversarially Manipulated Attributions for Weakly and Semi-Supervised Semantic Segmentation|-|CVPR 2021|PASCAL VOC 2012|[Code](https://github.com/jbeomlee93/AdvCAM)![Github stars](https://img.shields.io/github/stars/jbeomlee93/AdvCAM)|[Paper](https://arxiv.org/pdf/2103.08896.pdf)|
|Semi-supervised Domain Adaptation based on Dual-level Domain Mixing for Semantic Segmentation|-|CVPR 2021|Cityscapes, GTA5, SYNTHIA|-|[Paper](https://arxiv.org/pdf/2103.04705.pdf)|
|Learning from Pixel-Level Label Noise: A New Perspective for Semi-Supervised Semantic Segmentation|-|TIP 2021|PASCAL VOC 2012, PASCAL-Context, Cityscapes|-|[Paper](https://arxiv.org/pdf/2103.14242)|
|A Three-Stage Self-Training Framework for Semi-Supervised Semantic Segmentation|-|TIP 2021|PASCAL VOC 2012, Cityscapes|-|[Paper](https://arxiv.org/pdf/2012.00827.pdf)|



