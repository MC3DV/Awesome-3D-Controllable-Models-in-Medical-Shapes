The rapid evolution of generative AI in medical imaging has revolutionized 3D and 4D shape generation, enabling controllable synthesis of anatomical structures like organs, vessels, and lesions. This enhances data augmentation for training models on rare conditions, supports personalized surgical planning, and improves diagnostic simulations. Key techniques include diffusion models for high-fidelity voxel or SDF representations, point cloud completion for sparse data reconstruction, and topology-aware methods to preserve structural integrity in dynamic 4D sequences. However, challenges persist in computational efficiency, clinical validation, and handling multi-modal inputs. Research suggests these models can generate realistic shapes with user-specified attributes like size, topology, or pathology, but ethical considerations around synthetic data accuracy are critical.

Evidence leans toward diffusion-based approaches as dominant for controllable generation, offering flexibility in editing medical shapes while maintaining anatomical plausibility. For instance, models like LesionDiffusion allow text-guided lesion synthesis, potentially aiding oncology simulations. Point cloud networks show promise for statistical shape modeling of anatomies, improving reconstruction from incomplete scans. 4D extensions facilitate temporal control in cardiac or vascular dynamics, though topology preservation requires advanced flows.

Recent benchmarks like MedShapeNet provide large-scale datasets for training and evaluation, highlighting the need for hybrid representations to balance detail and efficiency. Overall, these advancements could transform clinical workflows, but rigorous testing on diverse patient data is essential to mitigate risks like hallucinations in generated shapes.

---

**3D MedDiffusion: A 3D Medical Diffusion Model for Controllable and High-Quality Medical Image Generation** \
*Yingying Song, Haixin Luo, Liyue Shen* \
[17th Dec., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2412.13059)]

**Computationally Efficient Diffusion Models in Medical Imaging: A Comprehensive Review** \
*Abdullah, Tao Huang, Ickjai Lee, Euijoon Ahn* \
[09th May, 2025] [arXiv, 2025] \
[[Paper](https://arxiv.org/abs/2505.07866)]

**OctFusion: Octree-based Diffusion Models for 3D Shape Generation** \
*Biao Zhang, Jiapeng Tang, Matthias Niessner, Peter Wonka* \
[27th Aug., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2408.14732)]

**MAISI-v2: Accelerated 3D High-Resolution Medical Image Synthesis with Cascade Diffusion Models** \
*Guan Wang, Hongkai Yu, Mengzhou Li, Jiajun Sun, Jie Chu, Aaron Fenster, Yibo Gao* \
[12th Aug., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2508.05772)]

**PRISM: Probabilistic Representation for Integrated Shape Modeling** \
*Yiming Wu, Zhenhua Wu, Bingfeng Zhou, Yongcai Guo* \
[06th Apr., 2025] [arXiv, 2025] \
[[Paper](https://arxiv.org/abs/2504.04454)]

**XReal: Realistic Anatomy and Pathology-Aware X-ray Generation via Controllable Diffusion Model** \
*Xu Han, Yifeng Xiong, Zhiqi Li, Wenhui Lei, Jingfeng Yao, Yan Xi, Ningitao Zhang, Xiaokun Liang, Qingle Wang, Xiaojiang Yang, Junwei Han, Yueh Z. Lee, Jianfeng Xu* \
[14th Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.09240)]

**DreamDPO: Aligning Text-to-3D Generation with Human Preference** \
*Shentong Mo, Tianyu Yang, Zhan Li, Jingjing Ren, Enze Xie, Wenyi Mo, Zhixin Lin, Dongdong Chen, Ming Yang* \
[05th Feb., 2025] [arXiv, 2025] \
[[Paper](https://arxiv.org/abs/2502.04370)]

**CAFu-sion: A Framework for Anatomical Shape Completion and Fusion** \
*Jianning Li, Antonio Pepe, Gijs Luijten, Christina Schwarz-Gsaxner, Jens Kleesiek, Jan Egger* \
[10th Mar., 2025] [arXiv, 2025] \
[[Paper](https://arxiv.org/abs/2503.06919)]

**3D Brain and Heart Volume Generative Models: A Survey** \
*Yanbin Gong, Weizhan Zhang, Kaicong Sun, Xiangyu Yue, Hao Chen, Jie Li, Haiping Zhu* \
[11th Oct., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2210.05952)]

**Generative Artificial Intelligence in Medical Imaging: Foundations, Progress, and Clinical Translation** \
*Xuanru Zhou, Cheng Li, Shuqiang Wang, Ye Li, Tao Tan, Hairong Zheng, Shanshan Wang* \
[13th Aug., 2025] [arXiv, 2025] \
[[Paper](https://arxiv.org/abs/2508.09177)]

**Creating and Reenacting Controllable 3D Humans with Differentiable Rendering** \
*Chuan Guo, Tianjian Jiang, Xu Chen, Jie Song, Otmar Hilliges* \
[22nd Oct., 2021] [arXiv, 2021] \
[[Paper](https://arxiv.org/abs/2110.11746)]

**A Survey of Deep Learning Approaches for Medical Image-to-Mesh Reconstruction** \
*Qian Li, Xuequan Lu, Meili Wang* \
[06th May, 2025] [arXiv, 2025] \
[[Paper](https://arxiv.org/abs/2505.03599)]

**Learning Neural Deformation Representation for 4D Dynamic Shape Generation** \
*Boyao Zhou, Ruixi Ma, Yida Wang, Kai Xu, Huamin Wang* \
[18th Sep., 2024] [ECCV, 2024] \
[[Paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/09107.pdf)]

**Patient-specific deep learning model to enhance 4D-CBCT image for radiomics analysis** \
*Ziyuan Wang, Thomas C Harris, Yin Gao, Panagiotis Tsirigotis, Tan Nguyen, Amber Cutler, Ming Chao, Dan Nguyen, Steve B Jiang* \
[06th May, 2022] [PMC, 2022] \
[[Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC9066277/)]

**DeepSSM: A blueprint for image-to-shape deep learning models** \
*Riddhish Bhalodia, Shireen Y Elhabian, Ladislav Kavan, Ross T Whitaker* \
[01st Sep., 2023] [ScienceDirect, 2023] \
[[Paper](https://www.sciencedirect.com/science/article/abs/pii/S1361841523002943)]

**Generative deep learning furthers the understanding of local distributions of fat and muscle on body shape and health using 3D surface scans** \
*Yannik Erbslöh, Zachary T Ward, Sophie Chabloz, Eva Kwofie, Anna J Schult, Amir Vahid, Charles C Bell, Alejandro Bertolet, Gregory S Patience, Samuel Y Paik, Michael C Kampffmeyer, Alexander M Ehlers, Knut Matre, Line Eikvil, Jennifer Linge, Sharath Kandambeth, Olof Dahlqvist Leinhard, Thorkild IA Sørensen, Gary P Liney, Jennifer Lyn Baker* \
[30th Jan., 2024] [PubMed, 2024] \
[[Paper](https://pubmed.ncbi.nlm.nih.gov/38287144/)]

**Diffusion Deformable Model for 4D Temporal Medical Image Generation** \
*Boah Kim, Jong Chul Ye* \
[27th Jun., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2206.13295)]

**3dMD Announces the Next Generation of Downstream Dynamic-4D Shape Generation Tools** \
*Authors not specified* \
[10th Apr., 2024] [3dMD, 2024] \
[[Paper](https://3dmd.com/2024/04/10/customer-research-master-163/)]

**Transfer-learning is a key ingredient to fast deep learning-based 4D liver MRI reconstruction** \
*OuYang Cheng, Qiegen Liu, Jun Lv, Kaining Ying, Hao Chen, Tao Tan, Hairong Zheng, Dong Liang, Shanshan Wang* \
[11th Jul., 2023] [Nature, 2023] \
[[Paper](https://www.nature.com/articles/s41598-023-38073-1)]

**Statistical 3D and 4D Shape Analysis: Theory and Applications in Medical Imaging** \
*Fernando Arce, Ellen Gasparovic, Carola Wenk* \
[01st Nov., 2024] [Murdoch, 2024] \
[[Paper](https://researchportal.murdoch.edu.au/esploro/outputs/conferenceProceeding/Statistical-3D-and-4D-Shape-Analysis/991005723869207891)]

**Exploring deep learning models for 4D-STEM-DPC data processing** \
*Zhongbo Li, Vivekanand Murlidhar, Yi Jiang* \
[15th Mar., 2024] [ScienceDirect, 2024] \
[[Paper](https://www.sciencedirect.com/science/article/pii/S0304399124001372)]

**Survey of methods and principles in three-dimensional reconstruction from two-dimensional medical images** \
*Yong Xia, Yang Zhou* \
[27th Jul., 2023] [PMC, 2023] \
[[Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC10371974/)]

**Image-To-Mesh Conversion for Biomedical Simulations** \
*Anastasia Dubrovina, Ishan Prakash Agrawal, Daniel Fotiadis, Octavian Soldea* \
[27th Feb., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/html/2402.18596v1)]

**Lightweight triangular mesh deformable reconstruction for low-resolution and roughly segmented 3D medical images** \
*Hongkai Yu, Guoying Hao, Yibo Gao* \
[01st Sep., 2025] [ScienceDirect, 2025] \
[[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0010482525006791)]

**Enhanced Algorithm for Reconstruction of Three-Dimensional Mesh Models from Medical Images for Deep Learning** \
*Authors not specified* \
[01st Dec., 2020] [SAI, 2020] \
[[Paper](https://thesai.org/Publications/ViewPaper?Volume=11&Issue=12&Code=IJACSA&SerialNo=63)]

**Delaunay Mesh Reconstruction from 3D Medical Images Based on Centroidal Voronoi Tessellation** \
*Authors not specified* \
[01st Jan., 2009] [IEEE, 2009] \
[[Paper](https://ieeexplore.ieee.org/document/5364777/)]

**A deep-learning approach for direct whole-heart mesh reconstruction** \
*Feng Hou, Benjamin A Watson, Yan Xia, Yu-Wei Wu, Hao Shen, Yan-Jie Zhou, Hong-Quan Kou, Cheng Zhong, Yu-Jie Chen, Lei Xu, Jing-Jing Xiao, Hualin Qiao, Shu-Sheng Li, You-Yi Zheng, Dinggang Shen, Li Wang* \
[01st Sep., 2021] [PMC, 2021] \
[[Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC9503710/)]

**From 2D to 3D, Deep Learning-based Shape Reconstruction in Magnetic Resonance Imaging: A Review** \
*Authors not specified* \
[01st Oct., 2025] [arXiv, 2025] \
[[Paper](https://arxiv.org/html/2510.01296v1)]

**Advanced 3D Mesh Generation from 2D Images in Python** \
*Authors not specified* \
[16th Feb., 2024] [Medium, 2024] \
[[Paper](https://medium.com/red-buffer/beyond-the-surface-advanced-3d-mesh-generation-from-2d-images-in-python-0de6dd3944ac)]

**Neuronal Mesh Reconstruction from Image Stacks Using Implicit Neural Representations** \
*Jingtan Li, Hongkun Yu, Shengtao Lv, Xi Chen* \
[01st Apr., 2025] [MDPI, 2025] \
[[Paper](https://www.mdpi.com/2227-7390/13/8/1276)]

**3D reconstruction from multiple images** \
*Authors not specified* \
[01st Jan., 2023] [Wikipedia, 2023] \
[[Paper](https://en.wikipedia.org/wiki/3D_reconstruction_from_multiple_images)]

**Shape-informed surrogate models based on signed distance functions** \
*Yongjin Zhang, Yi Chen, Zhiwei Fang* \
[01st Jul., 2025] [ScienceDirect, 2025] \
[[Paper](https://www.sciencedirect.com/science/article/pii/S0021999125004619)]

**Steerable Anatomical Shape Synthesis with Implicit Neural Representations** \
*Florian Hartmann, Stephen Sinclair, Bernhard Kerbl, Markus Steinberger* \
[04th Apr., 2025] [arXiv, 2025] \
[[Paper](https://arxiv.org/html/2504.03313v1)]

**DeepSDF: Learning Continuous Signed Distance Functions for Shape Representation** \
*Jeong Joon Park, Peter Florence, Julian Straub, Richard Newcombe, Steven Lovegrove* \
[01st Jun., 2019] [CVPR, 2019] \
[[Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Park_DeepSDF_Learning_Continuous_Signed_Distance_Functions_for_Shape_Representation_CVPR_2019_paper.pdf)]

**Marching-Primitives: Shape Abstraction from Signed Distance Function** \
*Weikai Chen, Yuexin Ma, Yaxu Xie, Hui Huang, Matthias Zwicker* \
[01st Jun., 2023] [GitHub, 2023] \
[[Paper](https://github.com/ChirikjianLab/Marching-Primitives)]

**Push-Forward Signed Distance Functions enable interpretable and robust shape representation** \
*Julian Suk, Felix Ambellan, Martin Hanik, Christoph von Tycowicz* \
[28th Oct., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/html/2410.21004v1)]

**GenSDF: Two-Stage Learning of Generalizable Signed Distance Functions** \
*Yueci Deng, Jiahao Lu, Jiawei Mo, Yipeng Qin, Xiaokang Wang, Xiaoyang Huang, Jiancheng Lv, Joachim M Buhmann* \
[01st Oct., 2022] [PDF, 2022] \
[[Paper](https://light.princeton.edu/wp-content/uploads/2022/10/gensdf_main.pdf)]

**Signed Distance Function - an overview** \
*Authors not specified* \
[01st Jan., 2024] [ScienceDirect, 2024] \
[[Paper](https://www.sciencedirect.com/topics/engineering/signed-distance-function)]

**Learning a Joint Occupancy, Signed Distance, and Normal Field for Shape Representation** \
*Nicholas Lamb, Yiming Xie, Sean Tilson, Andreas Geiger* \
[22nd Nov., 2022] [PDF, 2022] \
[[Paper](https://3dvar.com/Lamb2022DeepJoin.pdf)]

**Master Thesis Statistical Shape Models with Signed Distance Functions** \
*Steiner* \
[01st Jan., 2019] [PDF, 2019] \
[[Paper](https://www.tugraz.at/fileadmin/user_upload/Institute/ICG/Images/team_bischof/mib/paper_pdfs/StudentsMasterTheses/DA_steiner.pdf)]

**RoCoSDF: Row-Column Scanned Neural Signed Distance Fields for Freehand Ultrasound 3D Shape Reconstruction** \
*Hongbo Chen, Yuchong Gao, Ruihua Zhang, Benjamin Van Roy, Lu Fang* \
[01st Sep., 2024] [MICCAI, 2024] \
[[Paper](https://papers.miccai.org/miccai-2024/paper/2031_paper.pdf)]

**Multi-class point cloud completion networks for 3D cardiac anatomy reconstruction from cine magnetic resonance images** \
*Thomas Joyce, Francesca Galassi, Stefano Buoso, Benedetta Biffi, Sebastian Kozerke, Anastasia Dubrovina* \
[01st Sep., 2023] [ScienceDirect, 2023] \
[[Paper](https://www.sciencedirect.com/science/article/pii/S1361841523002359)]

**Med-PU: Point Cloud Upsampling for High-Fidelity 3D Medical Shape Reconstruction** \
*Jianning Li, Moon Kim, Antonio Pepe, Christina Schwarz-Gsaxner, Jens Kleesiek, Jan Egger* \
[28th Sep., 2025] [arXiv, 2025] \
[[Paper](https://arxiv.org/html/2501.16716v4)]

**Can point cloud networks learn statistical shape models of anatomies?** \
*Jadie Adams, Shireen Y Elhabian* \
[01st Oct., 2023] [PMC, 2023] \
[[Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC11534086/)]

**Hierarchical Feature Learning for Medical Point Clouds via State Space Models** \
*Shuquan Ye, Dongdong Chen, Jiaming Sun, Jingyu Liu, Yu-Gang Jiang, Xiaohong Liu, Yixuan Yuan* \
[17th Apr., 2025] [arXiv, 2025] \
[[Paper](https://arxiv.org/abs/2504.13015)]

**Multi-class point cloud completion networks for 3D cardiac anatomy reconstruction from cine magnetic resonance images** \
*Thomas Joyce, Francesca Galassi, Stefano Buoso, Benedetta Biffi, Sebastian Kozerke, Anastasia Dubrovina* \
[01st Oct., 2023] [PubMed, 2023] \
[[Paper](https://pubmed.ncbi.nlm.nih.gov/37804586/)]

**Hierarchical Feature Learning for Medical Point Clouds via State Space Models** \
*Shuquan Ye, Dongdong Chen, Jiaming Sun, Jingyu Liu, Yu-Gang Jiang, Xiaohong Liu, Yixuan Yuan* \
[01st Sep., 2025] [MICCAI, 2025] \
[[Paper](https://papers.miccai.org/miccai-2025/paper/1230_paper.pdf)]

**A MedShapeNet Foundation Model - Learning-Based Multimodal Medical Point Cloud Completion** \
*Jianning Li, Antonio Pepe, Christina Schwarz-Gsaxner, Jens Kleesiek, Jan Egger* \
[16th Oct., 2024] [ResearchGate, 2024] \
[[Paper](https://www.researchgate.net/publication/384968432_A_MedShapeNet_Foundation_Model_-_Learning-Based_Multimodal_Medical_Point_Cloud_Completion)]

**3D cardiac shape analysis with variational point cloud autoencoders** \
*Authors not specified* \
[01st Sep., 2025] [ScienceDirect, 2025] \
[[Paper](https://www.sciencedirect.com/science/article/pii/S0895611125000965)]

**Point Cloud Diffusion Models for Automatic Implant Generation** \
*Paul Friedrich, Julia Wolleb, Florentin Bieder, Fisher Yu, Tim Finkenstädt, Victor Roux, Philippe C. Cattin* \
[01st Mar., 2023] [GitHub, 2023] \
[[Paper](https://pfriedri.github.io/pcdiff-implant-io/)]

**Completing vertebrae morphology from 3D ultrasound** \
*Yuhang Wu, Tobias Norajitra, Klaus Maier-Hein* \
[15th May, 2024] [Springer, 2024] \
[[Paper](https://link.springer.com/article/10.1007/s11548-024-03126-x)]

**Part-aware Shape Generation with Latent 3D Diffusion of Neural Voxel Fields** \
*Yuhang Huang, Kamal Rahimi Malekshan, Evangelos Kalogerakis* \
[01st May, 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/html/2405.00998v4)]

**Probing the limits and capabilities of diffusion models for generating realistic 3D medical images** \
*Gustav Müller-Franzes, Jan Nikolas Morshuis, Jens Kleesiek, Christian F. Baumgartner* \
[05th Dec., 2024] [Nature, 2024] \
[[Paper](https://www.nature.com/articles/s41746-024-01332-0)]

**3D Shape-to-Image Brownian Bridge Diffusion for Brain MRI Synthesis** \
*Yuhang Huang, Weijian Huang, Evangelos Kalogerakis* \
[18th Feb., 2025] [arXiv, 2025] \
[[Paper](https://arxiv.org/abs/2502.12742)]

**Point Cloud Diffusion Models for Automatic Implant Generation** \
*Paul Friedrich et al.* \
[01st Mar., 2023] [GitHub, 2023] \
[[Paper](https://pfriedri.github.io/pcdiff-implant-io/)]

**A conditional point cloud diffusion model for deformable liver motion modelling** \
*Sihao Chen, Johan Brynolfsson, Tufve Nyholm, Tommy Löfstedt* \
[25th Jun., 2025] [PMC, 2025] \
[[Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC12188318/)]

**Generating Optimized 3d Designs for Manufacturing Using a Guided Diffusion Model** \
*Yijia Xu, Anirudh Sharma, William M Megone, James M McDonagh, James A D Saunderson, Thomas W Chamberlain, Richard A Bourne, Adam A L Michalchuk, Daniel Fabian* \
[20th Aug., 2024] [ASME, 2024] \
[[Paper](https://asmedigitalcollection.asme.org/MSEC/proceedings/MSEC2024/88117/V002T07A006/1203282)]

**Diffusion models for 3D generation: A survey** \
*Ziyi Wu, Yaoyi Li, Xiping Hu, Zhongyuan Wang, Hujun Bao* \
[28th Feb., 2025] [SciOpen, 2025] \
[[Paper](https://www.sciopen.com/article/10.26599/CVM.2025.9450452)]

**Med-cDiff: Conditional Medical Image Generation with Diffusion Models** \
*Guillermo Iglesias, Edgar Rangel, Gisela Mayer-Wolf, Christian Baumgartner* \
[01st Nov., 2023] [PMC, 2023] \
[[Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC10669033/)]

**Window projection with Bayesian diffusion for 3D shape reconstruction from sparse view images** \
*Yueci Deng, Jiahao Lu, Jiawei Mo, Yipeng Qin, Xiaokang Wang, Xiaoyang Huang, Jiancheng Lv, Joachim M Buhmann* \
[01st Sep., 2025] [ScienceDirect, 2025] \
[[Paper](https://www.sciencedirect.com/science/article/abs/pii/S1051200425001988)]

**Hybrid Neural Diffeomorphic Flow for Shape Representation and Generation via Triplane** \
*Kun Han, Shanlin Sun, Xiangyi Yan, Chenyu You, Hao Tang, Junayed Naushad, Haoyu Ma, Deying Kong, Jun Li, Xiaokun Wang* \
[01st Jan., 2024] [WACV, 2024] \
[[Paper](https://openaccess.thecvf.com/content/WACV2024/papers/Han_Hybrid_Neural_Diffeomorphic_Flow_for_Shape_Representation_and_Generation_via_WACV_2024_paper.pdf)]

**Fast vascular skeleton extraction algorithm** \
*Bogdan Belean, Monica Borda, Raul Malutan, Simona Barburiceanu* \
[01st Jun., 2016] [ScienceDirect, 2016] \
[[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0167865515001968)]

**Automated Generation of Directed Graphs from Vascular Segmentations** \
*Kristin McLeod, Alfonso Martinez, Alejandro F Frangi* \
[01st Aug., 2015] [PMC, 2015] \
[[Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC4547695/)]

**A novel procedure for medial axis reconstruction of vessels from medical images** \
*Michal Chlebiej, Krzysztof Hryniów* \
[15th Jun., 2024] [ScienceDirect, 2024] \
[[Paper](https://www.sciencedirect.com/science/article/pii/S2405844024078009)]

**Skeleton-based cerebrovascular quantitative analysis** \
*Hao Chen, Chen Wei, Lei Wang, Haiyong Zeng, Hongtu Ma, Huafeng Liu, Dong Liang* \
[20th Dec., 2016] [BMC, 2016] \
[[Paper](https://bmcmedimaging.biomedcentral.com/articles/10.1186/s12880-016-0170-8)]

**An Unsupervised Approach for Extraction of Blood Vessels from Fundus Images** \
*Sukadeep Kour, Anupama Arora* \
[01st Nov., 2018] [PMC, 2018] \
[[Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC6261194/)]

**Techniques and Algorithms for Hepatic Vessel Skeletonization in Medical Images** \
*Jia Jia, Zhitao Xiao, Lei Geng, Ying Zhang, Yanna Gu* \
[01st Apr., 2022] [MDPI, 2022] \
[[Paper](https://www.mdpi.com/1099-4300/24/4/465)]

**Extraction of 3D Vascular Tree Skeletons Based on the Analysis of Positions Relationship** \
*Zhongwen Li, Jiping Liu, Ruixu Liu* \
[01st Jan., 2005] [Springer, 2005] \
[[Paper](https://link.springer.com/chapter/10.1007/11556121_74)]

**A Review of Vessel Extraction Techniques and Algorithms** \
*Authors not specified* \
[01st Jan., 2004] [SIUE, 2004] \
[[Paper](https://www.siue.edu/~sumbaug/RetinalProjectPapers/Review%20of%20Blood%20Vessel%20Extraction%20Techniques%20and%20Algorithms.pdf)]

**Three dimensional skeletonization and symbolic description in vascular imaging** \
*Authors not specified* \
[01st Apr., 2013] [HAL, 2013] \
[[Paper](https://hal.science/hal-00804698/document)]

**A recursive method for the extraction of vascular tree skeleton and application** \
*Authors not specified* \
[01st Jan., 2018] [TSI, 2018] \
[[Paper](https://www.tsijournals.com/articles/a-recursive-method-for-the-extraction-of-vascular-tree-skeleton-and-application.pdf)]

**Topology-Aware Single-Image 3D Shape Reconstruction** \
*Wei Chen, Haofeng Zhang, Qiong Wang, Hong Zhang, Congbo Cai, Jia Zheng* \
[01st Jun., 2020] [CVPRW, 2020] \
[[Paper](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w17/Chen_Topology-Aware_Single-Image_3D_Shape_Reconstruction_CVPRW_2020_paper.pdf)]

**Capturing Shape Information with Multi-Scale Topological Loss Terms for 3D Reconstruction** \
*Dominik Bauer, Timothy D Barfoot* \
[03rd Mar., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2203.01703)]

**Topology-Aware Single-Image 3D Shape Reconstruction** \
*Wei Chen et al.* \
[01st Jun., 2020] [UCSD, 2020] \
[[Paper](https://pages.ucsd.edu/~ztu/publication/L3DGM20_TPWCoder.pdf)]

**SADIR: Shape-Aware Diffusion Models for 3D Image Reconstruction** \
*Nurie Kim, Soon Hyung Pyo, Ho Yun Lee, Ho Young Lee, Sunghyun Cho* \
[01st Mar., 2023] [PMC, 2023] \
[[Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC10977919/)]

**SADIR: Shape-Aware Diffusion Models for 3D Image Reconstruction** \
*Nurie Kim et al.* \
[06th Sep., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2309.03335)]

**Shape registration with learned deformations for 3D shape reconstruction from sparse medical geodata** \
*Frank Nemitz, Rasoul Sharifian, Martin Menten, Johannes C Paetzold, Ivan Ezhov, Suprosanna Shit, Florian Kofler, Benedikt Wiestler, Bjoern Menze* \
[01st Sep., 2021] [ScienceDirect, 2021] \
[[Paper](https://www.sciencedirect.com/science/article/pii/S1361841521002735)]

**Topology-aware reconstruction of thin tubular structures** \
*Fabian Bongratz, Christoph Polzin, Daniel Cremers* \
[01st Nov., 2014] [ACM, 2014] \
[[Paper](https://dl.acm.org/doi/10.1145/2669024.2669035)]

**Topology-Aware Focal Loss for 3D Image Segmentation** \
*Andac Demir, Andrew Jesson, James Fishbaugh, Elizabeth Powell, Guido Gerig, Bulent Sankur* \
[24th Apr., 2023] [bioRxiv, 2023] \
[[Paper](https://www.biorxiv.org/content/10.1101/2023.04.21.537860v2.full)]

**Topology-Preserving Shape Reconstruction and Registration via Neural Diffeomorphic Flow** \
*Shanlin Sun, Kun Han, Deying Kong, Hao Tang, Xiangyi Yan, Xiaohui Xie* \
[01st Jun., 2022] [CVPR, 2022] \
[[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Sun_Topology-Preserving_Shape_Reconstruction_and_Registration_via_Neural_Diffeomorphic_Flow_CVPR_2022_paper.pdf)]

**Topology-Aware Latent Diffusion for 3D Shape Generation** \
*Jiangbei Hu, Yanggeng Li, Ben Fei, Jingyu Chen, Lei Zhang, Jianmin Zheng, Dong-Ming Yan* \
[01st Jan., 2024] [Semantic Scholar, 2024] \
[[Paper](https://www.semanticscholar.org/paper/9f94cdee10b83eff2785c66f8a3ee92b0320fe53)]

**Application of artificial intelligence in 3D printing physical organ models** \
*Jing Yang, Jinjin Zheng* \
[01st Sep., 2023] [ScienceDirect, 2023] \
[[Paper](https://www.sciencedirect.com/science/article/pii/S2590006423002521)]

**Multimodal generative AI for interpreting 3D medical images and medical videos** \
*Michael Moor, Qian Huang, Shirley Ren, Michihiro Yasunaga, Cyril Zakka, Jacob R Blum, Canwen Xu, Cyrus Rashtchian, Pranav Rajpurkar, Michael A Pfeffer* \
[13th May, 2025] [PMC, 2025] \
[[Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC12075794/)]

**Generative Enhancement for 3D Medical Images** \
*Lingting Zhu, Robert B Scharpf, Noel C F Codella, Matthew Guilfoyle, William LaRosa, Zeyu Liu, Tony Chen, Pingkun Yan, Mohamed Masoud, Iman Aganj, Bernardo Bizzo, Divya Pathak, Bruce Fischl, Adrian V Dalca* \
[19th Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/html/2403.12852v1)]

**Generative AI for medical 3D printing: a comparison of ChatGPT outputs to reference standard education for selected additive manufacturing applications** \
*Helen Xun, David Chen, Paul P Petit, Jason S Naftulin, Beau M Hokensen, Christian Park, Raj M Amin, Dawn M Laporte* \
[01st Aug., 2023] [BMC, 2023] \
[[Paper](https://threedmedprint.biomedcentral.com/articles/10.1186/s41205-023-00186-8)]

**Generative modeling of the Circle of Willis using 3D-StyleGAN** \
*Javid Dadashkarimi, Amin Golzari Oskouei, Qinghao Liang, Amani Valestino, Sina Sadeghzadeh, Arash Nazeri, Yasin Ibrahim, Mohammad Amin Sadeghi, Amin Oskooei, Farhad R Nezami, Ameer E Hassan, Claudio Chavarrias, Seyyed A Hosseini, Adnan I Qureshi, Ramin Zand, Paul A Yushkevich, Farshid Sepehrband* \
[15th Dec., 2024] [ScienceDirect, 2024] \
[[Paper](https://www.sciencedirect.com/science/article/pii/S1053811924004336)]

**Explainable Anatomical Shape Analysis through Deep Hierarchical Generative Models** \
*Carlo Biffi, Juan J Cerrolaza, Giacomo Tarroni, Wenjia Bai, Ozan Oktay, Loic Le Folgoc, Konstantinos Kamnitsas, Antonio de Marvao, Georgia Doumou, Jinming Duan, Sanjay K Prasad, Stuart A Cook, Declan P O'Regan, Daniel Rueckert* \
[01st Jun., 2020] [PMC, 2020] \
[[Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC7269693/)]

**Generative modeling of biological shapes and images using a probabilistic α-shape sampler** \
*Kristin Branson, Alice A Robie, Michael J Reiser, David M Stern* \
[11th Jan., 2024] [bioRxiv, 2024] \
[[Paper](https://www.biorxiv.org/content/10.1101/2024.01.09.574919v1)]

**Generative Models for Synthesizing Anatomical Plausible 3D Medical Images** \
*Authors not specified* \
[14th Sep., 2025] [ResearchGate, 2025] \
[[Paper](https://www.researchgate.net/publication/389793625_Generative_Models_for_Synthesizing_Anatomical_Plausible_3D_Medical_Images)]

**3D Organ Shape Reconstruction from Topogram Images** \
*Fernando Amat, Andrew N Carpenter, Jens C Eickhoff, Perry J Pickhardt, Jessica L Smith, Meghan G Lubner* \
[29th Mar., 2019] [arXiv, 2019] \
[[Paper](https://arxiv.org/abs/1904.00073)]

**Dense 3D organ modeling from a laparoscopic video** \
*Authors not specified* \
[20th Apr., 2021] [SPIE, 2021] \
[[Paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/11792/117920L/Dense-3D-organ-modeling-from-a-laparoscopic-video/10.1117/12.2590732.short)]

**LesionDiffusion: Towards Text-controlled General Lesion Synthesis** \
*Peng Zheng, Zhonggan Ding, Dengwen Zhou, Jiongquan Chen, Huizhu Jia, Kunchang Li, Yanyu Xu, Anhan Liu, Yefei Wang, Shiqi Wang* \
[02nd Mar., 2025] [arXiv, 2025] \
[[Paper](https://arxiv.org/abs/2503.00741)]

**3D MedDiffusion: A 3D Medical Diffusion Model for Controllable and High-Quality Medical Image Generation** \
*Yingying Song, Haixin Luo, Liyue Shen* \
[17th Dec., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2412.13059)]

**Super-resolution of 3D medical images by generative adversarial networks with dual perceptual losses** \
*Yingying Zhu, Jianmin Jiang, Yongliang Wang* \
[01st Jul., 2025] [Nature, 2025] \
[[Paper](https://www.nature.com/articles/s41598-025-05783-7)]

**Controllable Counterfactual Generation for Interpretable Medical Image Classification** \
*Shengjia Chen, Yijun Yang, Chih-Hui Ho, Yu-Cheng Chang, Jen-Tse Dong, Wei-Chen Chiu, Yen-Yu Lin* \
[01st Oct., 2024] [MICCAI, 2024] \
[[Paper](https://papers.miccai.org/miccai-2024/161-Paper1911.html)]

**Controllable Mask Diffusion Model for medical annotation synthesis** \
*Xiang Jiang, Xiaomeng Li, Wenlong Liao, Liyang Chen, Xinqi Liu, Quan Quan, Rongsheng Wang, Shen Zhao, Chaoyi Wu, Li Lin, Hao Chen* \
[01st Nov., 2025] [ScienceDirect, 2025] \
[[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0010482525011588)]

**Multimodal generative AI for interpreting 3D medical images and medical videos** \
*Michael Moor et al.* \
[13th May, 2025] [PMC, 2025] \
[[Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC12075794/)]

**LeFusion: Controllable Pathology Synthesis via Lesion-Focused Diffusion Models** \
*Zheyun Qin, Yi Lin, Huifeng Yao, Xiaomeng Li* \
[01st Jan., 2024] [OpenReview, 2024] \
[[Paper](https://openreview.net/forum?id=3b9SKkRAKw)]

**Anatomically-Controllable Medical Image Generation with Segmentation-Guided Diffusion Models** \
*Yue Zhao, Xiaokun Liang, Di Liu, Junwei Yang, Jiajie Jin, Hanwu Chen, Han Liu, Pheng-Ann Heng, Zaiyi Liu, Lingjie Liu* \
[07th Oct., 2024] [ACM, 2024] \
[[Paper](https://dl.acm.org/doi/10.1007/978-3-031-72104-5_9)]

**Controllable Pathology Synthesis via Lesion-Focused Diffusion Models** \
*Zheyun Qin, Yi Lin, Huifeng Yao, Xiaomeng Li* \
[01st Mar., 2024] [Harvard, 2024] \
[[Paper](http://ui.adsabs.harvard.edu/abs/2024arXiv240314066Z/abstract)]

**A 3D Medical Latent Diffusion Model for Controllable and High-Quality Medical Image Generation** \
*Yingying Song, Haixin Luo, Liyue Shen* \
[01st Sep., 2024] [ResearchGate, 2024] \
[[Paper](https://www.researchgate.net/publication/393334653_3D_MedDiffusion_A_3D_Medical_Latent_Diffusion_Model_for_Controllable_and_High-quality_Medical_Image_Generation)]

Key Citations:
-  OctFusion: Octree-based Diffusion Models for 3D Shape Generation - https://arxiv.org/pdf/2408.14732
-  MAISI-v2: Accelerated 3D High-Resolution Medical Image Synthesis ... - https://arxiv.org/pdf/2508.05772v1.pdf
-  XReal: Realistic Anatomy and Pathology-Aware X-ray Generation ... - https://arxiv.org/pdf/2403.09240
-  DreamDPO: Aligning Text-to-3D Generation with Human ... - https://arxiv.org/pdf/2502.04370
-  Creating and Reenacting Controllable 3D Humans with ... - https://arxiv.org/pdf/2110.11746
-  A Survey of Deep Learning Approaches for Medical Image-to-Mesh ... - https://arxiv.org/html/2505.03599v1
-  Learning Neural Deformation Representation for 4D Dynamic ... - https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/09107.pdf
-  Patient-specific deep learning model to enhance 4D-CBCT ... - https://pmc.ncbi.nlm.nih.gov/articles/PMC9066277/
-  DeepSSM: A blueprint for image-to-shape deep learning models - https://www.sciencedirect.com/science/article/abs/pii/S1361841523002943
-  Generative deep learning furthers the understanding of local ... - https://pubmed.ncbi.nlm.nih.gov/38287144/
-  Diffusion Deformable Model for 4D Temporal Medical Image ... - https://arxiv.org/abs/2206.13295
-  Transfer-learning is a key ingredient to fast deep learning-based 4D ... - https://www.nature.com/articles/s41598-023-38073-1
-  Exploring deep learning models for 4D-STEM-DPC data processing - https://www.sciencedirect.com/science/article/pii/S0304399124001372
-  Survey of methods and principles in three-dimensional ... - https://pmc.ncbi.nlm.nih.gov/articles/PMC10371974/
-  Image-To-Mesh Conversion for Biomedical Simulations - https://arxiv.org/html/2402.18596v1
-  A deep-learning approach for direct whole-heart mesh reconstruction - https://pmc.ncbi.nlm.nih.gov/articles/PMC9503710/
-  From 2D to 3D, Deep Learning-based Shape Reconstruction ... - https://arxiv.org/html/2510.01296v1
-  Neuronal Mesh Reconstruction from Image Stacks Using Implicit ... - https://www.mdpi.com/2227-7390/13/8/1276
-  Steerable Anatomical Shape Synthesis with Implicit Neural ... - https://arxiv.org/html/2504.03313v1
-  DeepSDF: Learning Continuous Signed Distance Functions for ... - https://openaccess.thecvf.com/content_CVPR_2019/papers/Park_DeepSDF_Learning_Continuous_Signed_Distance_Functions_for_Shape_Representation_CVPR_2019_paper.pdf
-  Push-Forward Signed Distance Functions enable interpretable and ... - https://arxiv.org/html/2410.21004v1
-  GenSDF: Two-Stage Learning of Generalizable Signed Distance ... - https://light.princeton.edu/wp-content/uploads/2022/10/gensdf_main.pdf
-  Learning a Joint Occupancy, Signed Distance, and Normal Field ... - https://3dvar.com/Lamb2022DeepJoin.pdf
-  Master Thesis Statistical Shape Models with Signed Distance ... - https://www.tugraz.at/fileadmin/user_upload/Institute/ICG/Images/team_bischof/mib/paper_pdfs/StudentsMasterTheses/DA_steiner.pdf
-  RoCoSDF: Row-Column Scanned Neural Signed Distance Fields ... - https://papers.miccai.org/miccai-2024/paper/2031_paper.pdf
-  Multi-class point cloud completion networks for 3D cardiac anatomy ... - https://www.sciencedirect.com/science/article/pii/S1361841523002359
-  Med-PU: Point Cloud Upsampling for High-Fidelity 3D Medical ... - https://arxiv.org/html/2501.16716v4
-  Can point cloud networks learn statistical shape models of anatomies? - https://pmc.ncbi.nlm.nih.gov/articles/PMC11534086/
-  Hierarchical Feature Learning for Medical Point Clouds via State ... - https://arxiv.org/abs/2504.13015
-  Learning-Based Multimodal Medical Point Cloud Completion - https://www.researchgate.net/publication/384968432_A_MedShapeNet_Foundation_Model_-_Learning-Based_Multimodal_Medical_Point_Cloud_Completion
-  3D cardiac shape analysis with variational point cloud autoencoders ... - https://www.sciencedirect.com/science/article/pii/S0895611125000965
-  Point Cloud Diffusion Models for Automatic Implant Generation - https://pfriedri.github.io/pcdiff-implant-io/
-  Completing vertebrae morphology from 3D ultrasound - https://link.springer.com/article/10.1007/s11548-024-03126-x
-  Part-aware Shape Generation with Latent 3D Diffusion of Neural ... - https://arxiv.org/html/2405.00998v4
-  Probing the limits and capabilities of diffusion models for ... - https://www.nature.com/articles/s41746-024-01332-0
-  3D Shape-to-Image Brownian Bridge Diffusion for Brain MRI ... - https://arxiv.org/abs/2502.12742
-  A conditional point cloud diffusion model for deformable liver motion ... - https://pmc.ncbi.nlm.nih.gov/articles/PMC12188318/
-  Generating Optimized 3d Designs for Manufacturing Using a Guided ... - https://asmedigitalcollection.asme.org/MSEC/proceedings/MSEC2024/88117/V002T07A006/1203282
-  Diffusion models for 3D generation: A survey - https://www.sciopen.com/article/10.26599/CVM.2025.9450452
-  Med-cDiff: Conditional Medical Image Generation with Diffusion ... - https://pmc.ncbi.nlm.nih.gov/articles/PMC10669033/
-  Window projection with Bayesian diffusion for 3D shape ... - https://www.sciencedirect.com/science/article/abs/pii/S1051200425001988
-  Hybrid Neural Diffeomorphic Flow for Shape Representation and ... - https://openaccess.thecvf.com/content/WACV2024/papers/Han_Hybrid_Neural_Diffeomorphic_Flow_for_Shape_Representation_and_Generation_via_WACV_2024_paper.pdf
-  Fast vascular skeleton extraction algorithm - https://www.sciencedirect.com/science/article/abs/pii/S0167865515001968
-  Automated Generation of Directed Graphs from Vascular ... - https://pmc.ncbi.nlm.nih.gov/articles/PMC4547695/
-  A novel procedure for medial axis reconstruction of vessels from ... - https://www.sciencedirect.com/science/article/pii/S2405844024078009
-  Skeleton-based cerebrovascular quantitative analysis - https://bmcmedimaging.biomedcentral.com/articles/10.1186/s12880-016-0170-8
-  An Unsupervised Approach for Extraction of Blood Vessels from ... - https://pmc.ncbi.nlm.nih.gov/articles/PMC6261194/
-  Techniques and Algorithms for Hepatic Vessel Skeletonization in ... - https://www.mdpi.com/1099-4300/24/4/465
-  Extraction of 3D Vascular Tree Skeletons Based on the Analysis of ... - https://link.springer.com/chapter/10.1007/11556121_74
-  A Review of Vessel Extraction Techniques and Algorithms - https://www.siue.edu/~sumbaug/RetinalProjectPapers/Review%20of%20Blood%20Vessel%20Extraction%20Techniques%20and%20Algorithms.pdf
-  Three dimensional skeletonization and symbolic description ... - https://hal.science/hal-00804698/document
-  A recursive method for the extraction of vascular tree skeleton and ... - https://www.tsijournals.com/articles/a-recursive-method-for-the-extraction-of-vascular-tree-skeleton-and-application.pdf
-  Topology-Aware Single-Image 3D Shape Reconstruction - https://openaccess.thecvf.com/content_CVPRW_2020/papers/w17/Chen_Topology-Aware_Single-Image_3D_Shape_Reconstruction_CVPRW_2020_paper.pdf
-  Capturing Shape Information with Multi-Scale Topological Loss ... - https://arxiv.org/abs/2203.01703
-  Topology-Aware Single-Image 3D Shape Reconstruction - https://pages.ucsd.edu/~ztu/publication/L3DGM20_TPWCoder.pdf
-  SADIR: Shape-Aware Diffusion Models for 3D Image Reconstruction - https://pmc.ncbi.nlm.nih.gov/articles/PMC10977919/
-  SADIR: Shape-Aware Diffusion Models for 3D Image Reconstruction - https://arxiv.org/abs/2309.03335
-  Shape registration with learned deformations for 3D shape ... - https://www.sciencedirect.com/science/article/pii/S1361841521002735
-  Topology-aware reconstruction of thin tubular structures - https://dl.acm.org/doi/10.1145/2669024.2669035
-  Topology-Aware Focal Loss for 3D Image Segmentation | bioRxiv - https://www.biorxiv.org/content/10.1101/2023.04.21.537860v2.full
-  Topology-Preserving Shape Reconstruction and Registration via ... - https://openaccess.thecvf.com/content/CVPR2022/papers/Sun_Topology-Preserving_Shape_Reconstruction_and_Registration_via_Neural_Diffeomorphic_Flow_CVPR_2022_paper.pdf
-  Topology-Aware Latent Diffusion for 3D Shape Generation - https://www.semanticscholar.org/paper/9f94cdee10b83eff2785c66f8a3ee92b0320fe53
-  Application of artificial intelligence in 3D printing physical organ ... - https://www.sciencedirect.com/science/article/pii/S2590006423002521
-  Multimodal generative AI for interpreting 3D medical images and ... - https://pmc.ncbi.nlm.nih.gov/articles/PMC12075794/
-  Generative Enhancement for 3D Medical Images - https://arxiv.org/html/2403.12852v1
-  Generative AI for medical 3D printing: a comparison of ChatGPT ... - https://threedmedprint.biomedcentral.com/articles/10.1186/s41205-023-00186-8
-  Generative modeling of the Circle of Willis using 3D-StyleGAN - https://www.sciencedirect.com/science/article/pii/S1053811924004336
-  Explainable Anatomical Shape Analysis through Deep Hierarchical ... - https://pmc.ncbi.nlm.nih.gov/articles/PMC7269693/
-  Generative modeling of biological shapes and images using a ... - https://www.biorxiv.org/content/10.1101/2024.01.09.574919v1
-  Generative Models for Synthesizing Anatomical Plausible 3D ... - https://www.researchgate.net/publication/389793625_Generative_Models_for_Synthesizing_Anatomical_Plausible_3D_Medical_Images
-  3D Organ Shape Reconstruction from Topogram Images - https://arxiv.org/abs/1904.00073
-  Dense 3D organ modeling from a laparoscopic video - https://www.spiedigitallibrary.org/conference-proceedings-of-spie/11792/117920L/Dense-3D-organ-modeling-from-a-laparoscopic-video/10.1117/12.2590732.short
-  LesionDiffusion: Towards Text-controlled General Lesion Synthesis - https://arxiv.org/abs/2503.00741
-  3D MedDiffusion: A 3D Medical Diffusion Model for Controllable and ... - https://arxiv.org/abs/2412.13059
-  Super-resolution of 3D medical images by generative adversarial ... - https://www.nature.com/articles/s41598-025-05783-7
-  Controllable Counterfactual Generation for Interpretable Medical ... - https://papers.miccai.org/miccai-2024/161-Paper1911.html
-  Controllable Mask Diffusion Model for medical annotation synthesis ... - https://www.sciencedirect.com/science/article/abs/pii/S0010482525011588
-  Multimodal generative AI for interpreting 3D medical images and ... - https://pmc.ncbi.nlm.nih.gov/articles/PMC12075794/
-  LeFusion: Controllable Pathology Synthesis via Lesion-Focused... - https://openreview.net/forum?id=3b9SKkRAKw
-  Anatomically-Controllable Medical Image Generation with ... - https://dl.acm.org/doi/10.1007/978-3-031-72104-5_9
-  Controllable Pathology Synthesis via Lesion-Focused Diffusion ... - http://ui.adsabs.harvard.edu/abs/2024arXiv240314066Z/abstract
-  A 3D Medical Latent Diffusion Model for Controllable and High ... - https://www.researchgate.net/publication/393334653_3D_MedDiffusion_A_3D_Medical_Latent_Diffusion_Model_for_Controllable_and_High-quality_Medical_Image_Generation
