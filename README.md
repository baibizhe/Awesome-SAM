# Awesome-SAM [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
This repo collects the research resources based on SAM(Segment Anything Model) proposed by Meta AI. If you would like to contribute, please open an issue.
Some paper haven't been updated to google scholar database. I search it daily from arxiv. 

(Upate on June 19 .Some premiliary  work on  testing SAM on different dataset without any improvement on SAM has been moved to  premiliary  test section )


## SAM 
- [Segment Anything](https://arxiv.org/abs/2304.02643) [[code](https://segment-anything.com/) , [demo](https://segment-anything.com/) , [Fine-tune blog](https://encord.com/blog/learn-how-to-fine-tune-the-segment-anything-model-sam/)]



## Applications

### Object detection

- [When SAM Meets Camouflaged Object Detection](https://arxiv.org/abs/2304.04709) [[code](https://github.com/luckybird1994/SAMCOD)]
- [H2RBox-v2: Boosting HBox-supervised Oriented
Object Detection via Symmetric Learning](https://arxiv.org/pdf/2304.04403.pdf) [[code](https://github.com/Li-Qingyun/sam-mmrotate)]


### Semantic segmentation  related

- [ SAMM (Segment Any Medical Model): A 3D Slicer Integration to SAM](https://arxiv.org/abs/2304.04738) [[code](https://github.com/bingogome/samm)]
- [DSEC-MOS: Segment Any Moving Object with Moving Ego Vehicle](https://arxiv.org/pdf/2305.00126.pdf) [[code](https://github.com/ZZY-Zhou/DSEC-MOS)] (404 at May 2nd)

- [GazeSAM: What You See is What You Segment](https://arxiv.org/pdf/2304.13844.pdf) [[code](https://github.com/ukaukaaaa/GazeSAM)]
- [SkinSAM: Empowering Skin Cancer Segmentation with Segment Anything Model](https://arxiv.org/pdf/2304.13973.pdf) 
- [Application of Segment Anything Model for Civil Infrastructure Defect Assessment](https://arxiv.org/pdf/2304.12600.pdf) 

- [Personalize Segment Anything Model with One Shot](https://arxiv.org/pdf/2305.03048.pdf) [[code](https://github.com/ZrrSkywalker/Personalize-SAM)]

- [Knowledge distillation with Segment Anything (SAM) model for Planetary Geological Mapping](https://arxiv.org/pdf/2305.07586.pdf) 
- [Segment Any Anomaly without Training via Hybrid Prompt Regularization](https://arxiv.org/pdf/2305.10724.pdf) [[code](https://github.com/caoyunkang/Segment-Any-Anomaly)]
- [UVOSAM: A Mask-free Paradigm for Unsupervised Video Object Segmentation via Segment Anything Model](https://arxiv.org/pdf/2305.12659.pdf) 


- [Matting Anything](https://arxiv.org/pdf/2306.05399.pdf) [[code](https://github.com/SHI-Labs/Matting-Anything)]
- [SAM3D: Segment Anything in 3D Scenes](https://arxiv.org/pdf/2306.03908.pdf) [[code](https://github.com/Pointcept/SegmentAnything3D)]
- [SAM3D: Zero-Shot 3D Object Detection via Segment Anything Model](https://arxiv.org/pdf/2306.02245.pdf) [[code](https://github.com/DYZhang09/SAM3D)]


### Image style transfer
- [ Any-to-Any Style Transfer: Making Picasso and Da Vinci Collaborate ](https://arxiv.org/abs/2304.09728) [[code](https://github.com/Huage001/Transfer-Any-Style)]
- [ Inpaint Anything: Segment Anything Meets Image Inpainting ](https://arxiv.org/abs/2304.06790) [[code](https://github.com/geekyutao/Inpaint-Anything)]

### Fine tunning SAM 
- [Medical SAM Adapter: Adapting Segment Anything Model for Medical Image Segmentation](https://arxiv.org/pdf/2304.12620.pdf) [[code](https://github.com/WuJunde/Medical-SAM-Adapter)]
- [Segment Anything in Medical Images](https://arxiv.org/pdf/2304.12306.pdf) [[code](https://github.com/bowang-lab/MedSAM)]
- [Learnable Ophthalmology SAM](https://arxiv.org/pdf/2304.13425.pdf) [[code](https://github.com/Qsingle/LearnablePromptSAM)]
- [Customized Segment Anything Model for Medical Image Segmentation](https://arxiv.org/pdf/2304.13785.pdf) [[code](https://github.com/hitachinsk/SAMed)]
- [PromptUNet: Toward Interactive Medical Image Segmentation](https://arxiv.org/pdf/2305.10300.pdf) [[code](https://github.com/WuJunde/PromptUNet)]
- [Segment Anything in High Quality](https://arxiv.org/pdf/2306.01567.pdf) [[code](https://github.com/SysCV/SAM-HQ)]
- [AutoSAM: Adapting SAM to Medical Images by Overloading the Prompt Encoder](https://arxiv.org/pdf/2306.06370.pdf)
- [SAM Meets Robotic Surgery: An Empirical Study on Generalization, Robustness and Adaptation](https://arxiv.org/pdf/2308.07156.pdf)  [[code](https://github.com/ternaus/robot-surgery-segmentation)](Point based segmentation)
- [Winning Solution for the CVPR2023 Visual Anomaly and Novelty Detection Challenge: Multimodal Prompting for Data-centric Anomaly Detection
](https://arxiv.org/abs/2306.09067v1) [[code](https://github.com/caoyunkang/Segment-Any-Anomaly)]
- [Polyp-SAM++: Can A Text Guided SAM Perform Better for Polyp Segmentation?](https://arxiv.org/pdf/2308.06623.pdf) [[code](https://github.com/RisabBiswas/Polyp-SAM++)] (SAM+GroundedDINO)
- [AdaptiveSAM: Towards Efficient Tuning of SAM for Surgical Scene Segmentation](https://arxiv.org/pdf/2308.03726.pdf) [[code](https://github.com/JayParanjape/biastuning)]
- [All-in-SAM: from Weak Annotation to Pixel-wise Nuclei Segmentation with Prompt-based Finetuning](https://arxiv.org/pdf/2307.00290.pdf) [[code]()]



### Weakly-Supervised Semantic Segmentation
- [An Alternative to WSSS? An Empirical Study of the Segment Anything Model (SAM) on Weakly-Supervised Semantic Segmentation Problems](https://arxiv.org/pdf/2305.01586.pdf) 
- [Segment Anything is A Good Pseudo-label Generator for Weakly Supervised Semantic Segmentation](https://arxiv.org/pdf/2305.01275.pdf) 
- [Segment Anything Model (SAM) Enhanced Pseudo Labels for Weakly Supervised Semantic Segmentation](https://arxiv.org/pdf/2305.05803.pdf) [[code](https://github.com/cskyl/SAM_WSSS)]


### 3D-related
- [Anything-3D: Towards Single-view Anything Reconstruction in the Wild](https://arxiv.org/abs/2304.10261) [[code](https://github.com/Anything-of-anything/Anything-3D)]
- [Segment Any Point Cloud Sequences](https://arxiv.org/abs/2306.09347) [[code](https://github.com/youquanl/Segment-Any-Point-Cloud)]

### Tracking
- [Track Anything: Segment Anything Meets Videos](https://arxiv.org/pdf/2304.11968.pdf) [[code](https://github.com/gaomingqi/Track-Anything)]
- [Segment and Track Anything](https://arxiv.org/pdf/2305.06558.pdf) [[code](https://github.com/z-x-yang/Segment-and-Track-Anything)]



### Others
- [CAN SAM COUNT ANYTHING? AN EMPIRICAL STUDY ON SAM COUNTING](https://arxiv.org/pdf/2304.10817.pdf) [[code](https://github.com/Vision-Intelligence-and-Robots-Group/count-anything)]
- [ATTACK-SAM: TOWARDS EVALUATING ADVERSARIAL ROBUSTNESS OF SEGMENT ANYTHING MODEL](https://arxiv.org/pdf/2305.00866.pdf) [[code](https://github.com/chenshuang-zhang/attack-sam)]
- [An Empirical Study on the Robustness of the Segment Anything Model (SAM)](https://arxiv.org/pdf/2305.06422.pdf) 
- [Can SAM Boost Video Super-Resolution? ](https://arxiv.org/pdf/2305.06524.pdf) 
- [AV-SAM: Segment Anything Model Meets Audio-Visual Localization and Segmentation](https://arxiv.org/pdf/2305.01836.pdf) 
- [A Comprehensive Survey on Segment Anything Model for Vision and Beyond](https://arxiv.org/pdf/2305.08196.pdf) 
- [Restore Anything Pipeline: Segment Anything Meets Image Restoration](https://arxiv.org/pdf/2305.13093.pdf) [[code](https://github.com/eth-siplab/RAP)]
- [Explain Any Concept: Segment Anything Meets Concept-Based Explanation](https://arxiv.org/pdf/2305.10289.pdf) 
- [On the Robustness of Segment Anything](https://arxiv.org/pdf/2305.16220.pdf) [[code]()]

- []() [[code]()]

##  Premiliary  Test on SAM 
- [Segment Anything Model for Medical Images?](https://arxiv.org/abs/2304.14660)
- [An Investigation of SAM on Different Real-world Applications](https://arxiv.org/pdf/2304.05750.pdf) 
- [Segment Anything in Non-Euclidean Domains:Challenges and Opportunities](https://arxiv.org/pdf/2304.11595.pdf) 
- [ Assess Zero-shot Segmentation on Whole Slide Imaging](https://arxiv.org/abs/2304.04155) 
- [ SAM vs BET: A Comparative Study for Brain Extraction and Segmentation of Magnetic Resonance Images using Deep Learning](https://arxiv.org/abs/2304.04738)
-  [SAM Struggles in Concealed Scenes](https://arxiv.org/abs/2304.06022) 
- [Accuracy of Segment-Anything Model (SAM) in medical image segmentation tasks](https://arxiv.org/abs/2304.09324) 
- [Can SAM Segment Polyps?](https://arxiv.org/abs/2304.07583) [[code](https://github.com/taozh2017/SAMPolyp)]
- [Learning to "Segment Anything" in Thermal Infrared Images through Knowledge Distillation with a Large Scale Dataset SATIR](https://arxiv.org/abs/2304.07969) [[code](https://github.com/chenjzBUAA/SATIR)]
- [When SAM Meets Medical Images: An Investigation of Segment Anything Model (SAM) on Multi-phase Liver Tumor Segmentation](https://arxiv.org/abs/2304.08506)
- [Segment anything, from space?](https://arxiv.org/pdf/2304.13000.pdf) 
- [Generalist Vision Foundation Models for Medical Imaging: A Case Study of Segment Anything Model on Zero-Shot Medical Segmentation](https://arxiv.org/pdf/2304.12637.pdf) 
- [Application of Segment Anything Model for CivilInfrastructure Defect Assessment](https://arxiv.org/pdf/2304.12600.pdf) 
- [Segment Anything Model for Medical Image Analysis: an Experimental Study](https://arxiv.org/pdf/2304.10517.pdf) 
- [segment anything model (SAM) meets glass: mirror and transparent objects cannot be easily detected.](https://arxiv.org/pdf/2305.00278.pdf)
- [Exploring the Zero-Shot Capabilities of the Segment Anything Model (SAM) in 2D Medical Imaging: A Comprehensive Evaluation and Practical Guideline](https://arxiv.org/pdf/2305.00109.pdf)
-  [Scaling-up Remote Sensing Segmentation Dataset with Segment Anything Model](https://arxiv.org/pdf/2305.02034.pdf) [[code](https://github.com/ViTAE-Transformer/SAMRS)]
- [SAM on Medical Images: A Comprehensive Study on Three Prompt Modes](https://arxiv.org/pdf/2305.00035.pdf)
-  [How Segment Anything Model (SAM) Boost Medical Image Segmentation?](https://arxiv.org/pdf/2305.03678.pdf) [[code](https://github.com/YichiZhang98/SAM4MIS)]
- [Computer-Vision Benchmark Segment-AnythingModel (SAM) in Medical Images: Accuracy in 12 Datasets](https://arxiv.org/pdf/2304.09324.pdf)
-  [When SAM Meets Shadow Detection](https://arxiv.org/pdf/2305.11513.pdf) [[code](https://github.com/LeipingJie/SAMShadow)]
- [BreastSAM: A Study of Segment Anything Model for Breast Tumor Detection in Ultrasound Images](https://arxiv.org/pdf/2305.12447.pdf) [[code]()]
- [Detect Any Shadow: Segment Anything for Video Shadow Detection](https://arxiv.org/pdf/2305.16698.pdf) [[code](https://github.com/harrytea/Detect-AnyShadow)]
- [SAM Meets Robotic Surgery: An Empirical Study in Robustness Perspective](https://arxiv.org/pdf/2304.14674.pdf) 
## Acknowledgment
Inspired by [Awesome-CLIP](https://github.com/yzhuoning/Awesome-CLIP).  
