# 3D Human Body Reconstruction Paper List
- [Fundamentals](#fundamentals)
- [Naked Human](#naked-human)
- [Clothing Condition on SMPLs](#clothing-condition-on-smpls)
- [Non-Parametric Clothed Human](#non-parametric-clothed-human)
  - [Voxels](#voxels)
  - [Implicit Fields](#implicit-fields)
  - [Animatable](#animatable)
  - [Nerfs](#nerfs)
- [Other Related Paper Lists](#other-related-paper-lists)

## Fundamentals
1. [Marching Cubes: A high resolution 3d surface construction algorithm](http://fab.cba.mit.edu/classes/S62.12/docs/Lorensen_marching_cubes.pdf). SigGraph, 1987.

1. [Learning Implicit Fields for Generative Shape Modeling](https://arxiv.org/abs/1812.02822). CVPR, 2019. [[Page]](https://www.sfu.ca/~zhiqinc/imgan/Readme.html) [[Code]](https://github.com/czq142857/implicit-decoder)

1. [DeepSDF: Learning Continuous Signed Distance Functions for Shape Representation](https://arxiv.org/abs/1901.05103). CVPR, 2019. [[Code]](https://github.com/facebookresearch/DeepSDF)

1. [Occupancy Networks: Learning 3D Reconstruction in Function Space](https://arxiv.org/abs/1812.03828). CVPR, 2019. [[Page]](https://avg.is.mpg.de/publications/occupancy-networks) [[Code]](https://github.com/autonomousvision/occupancy_networks)

1. [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://arxiv.org/abs/2003.08934). ECCV, 2020. [[Page]](https://www.matthewtancik.com/nerf) [[Code]](https://github.com/bmild/nerf)


## Naked Human
1. [SMPL: A Skinned Multi-Person Linear Model](http://files.is.tue.mpg.de/black/papers/SMPL2015.pdf). SIGGRAPH Asia, 2015. [[Page]](https://smpl.is.tue.mpg.de) [[Code]](https://github.com/vchoutas/smplx)

1. [End-to-end Recovery of Human Shape and Pose](https://arxiv.org/pdf/1712.06584.pdf). CVPR, 2018. [[Page]](https://akanazawa.github.io/hmr) [[Code]](https://github.com/akanazawa/hmr)

1. [Learning to Reconstruct 3D Human Pose and Shape via Model-fitting in the Loop](https://arxiv.org/pdf/1909.12828.pdf). ICCV, 2019. [[Page]](https://www.seas.upenn.edu/~nkolot/projects/spin) [[Code]](https://github.com/nkolot/SPIN)

1. [Expressive Body Capture: 3D Hands, Face, and Body from a Single Image](https://ps.is.tuebingen.mpg.de/uploads_file/attachment/attachment/497/SMPL-X.pdf). CVPR, 2019. [[Page]](https://smpl-x.is.tue.mpg.de) [[Code]](https://github.com/vchoutas/smplify-x)

1. [Monocular Expressive Body Regression through Body-Driven Attention](https://ps.is.tuebingen.mpg.de/uploads_file/attachment/attachment/620/0983.pdf). ECCV, 2020. [[Page]](https://expose.is.tue.mpg.de) [[Code]](https://github.com/vchoutas/expose)

1. [GHUM & GHUML: Generative 3D Human Shape and Articulated Pose Models](https://arxiv.org/pdf/2008.08535). CVPR (Oral), 2020.  [[Code]](https://github.com/google-research/google-research/tree/master/ghum)

1. [STAR: Sparse Trained Articulated Human Body Regressor](https://arxiv.org/pdf/2008.08535). ECCV, 2020. [[Page]](http://star.is.tue.mpg.de) [[Code]](https://github.com/ahmedosman/STAR)

1. [SUPR: A Sparse Unified Part-Based Human Representation](https://arxiv.org/abs/2210.13861). ECCV, 2022. [[Page]](https://supr.is.tue.mpg.de/) [[Code]](https://github.com/ahmedosman/SUPR)

## Clothing Condition on SMPLs
1. [Learning to Reconstruct People in Clothing from a Single RGB Camera](https://arxiv.org/abs/1903.05885). CVPR, 2019.

1. [Detailed Human Avatars from Monocular Video](https://arxiv.org/abs/1808.01338). 3DV, 2018.

1. [Video Based Reconstruction of 3D People Models](https://arxiv.org/abs/1803.04758). CVPR, 2018.

1. [Tex2Shape: Detailed Full Human Body Geometry From a Single Image](https://arxiv.org/abs/1904.08645). ICCV, 2019.

1. [360-Degree Textures of People in Clothing from a Single Image](https://arxiv.org/abs/1908.07117). 3DV, 2019.

1. [ClothCap: Seamless 4D Clothing Capture and Retargeting](https://ps.is.mpg.de/uploads_file/attachment/attachment/374/clothcap.pdf). TOG, 2017.

1. [MonoClothCap: Towards Temporally Coherent Clothing Capture from Monocular RGB Video](https://arxiv.org/abs/2009.10711). 3DV, 2020.

1. [Detailed Human Shape Estimation from a Single Image by Hierarchical Mesh Deformation](https://arxiv.org/abs/1904.10506). CVPR, 2019.

## Non-Parametric Clothed Human
### Voxels
1. [BodyNet: Volumetric Inference of 3D Human Body Shapes](https://arxiv.org/abs/1804.04875v3). ECCV, 2018. [[Page]](https://www.di.ens.fr/willow/research/bodynet/) [[Code]](https://github.com/gulvarol/bodynet)

1. [LEAP: Learning Articulated Occupancy of People](https://arxiv.org/abs/2104.06849). CVPR, 2021. [[Page]](https://neuralbodies.github.io/LEAP) [[Code]](https://github.com/neuralbodies/leap)

### Depth Maps
1. [Moulding Humans: Non-parametric 3D Human Shape Estimation from Single Images](https://arxiv.org/abs/1908.00439). ICCV, 2019.

1. [FACSIMILE: Fast and Accurate Scans From an Image in Less Than a Second](https://arxiv.org/abs/1909.00883). ICCV, 2019.

1. [A Neural Network for Detailed Human Depth Estimation from a Single Image](https://arxiv.org/abs/1910.01275). ICCV, 2019. [[Code]](https://github.com/sfu-gruvi-3dv/deep_human)

### Implicit Fields
1. **[PIFu: Pixel-Aligned Implicit Function for High-Resolution Clothed Human Digitization](https://arxiv.org/pdf/1905.05172.pdf). ICCV, 2019. [[Page]](https://shunsukesaito.github.io/PIFu) [[Code]](https://github.com/shunsukesaito/PIFu)**

1. [PIFuHD: Multi-Level Pixel-Aligned Implicit Function for High-Resolution 3D Human Digitization](https://arxiv.org/pdf/2004.00452.pdf). CVPR (Oral), 2020. [[Page]](https://shunsukesaito.github.io/PIFuHD) [[Code]](https://github.com/facebookresearch/pifuhd)

1. [Implicit Functions in Feature Space for 3D Shape Reconstruction and Completion](https://arxiv.org/abs/2003.01456). CVPR, 2020. [[Page]](http://virtualhumans.mpi-inf.mpg.de/ifnets) [[Code]](https://github.com/jchibane/if-net)

1. [LatentHuman: Shape-and-Pose Disentangled Latent Representation for Human Bodies](https://arxiv.org/abs/2111.15113). 3DV, 2021. [[Page]](https://latenthuman.github.io/) [[Code]](https://github.com/latenthuman/latenthuman)

1. [StylePeople: A Generative Model of Fullbody Human Avatars](https://arxiv.org/abs/2104.08363). CVPR, 2021. [[Page]](http://saic-violet.github.io/style-people) [[Code]](https://github.com/saic-vul/style-people)

### Animatable
1. [ICON: Implicit Clothed humans Obtained from Normals](https://arxiv.org/abs/2112.09127). CVPR, 2022. [[Page]](https://icon.is.tue.mpg.de/) [[Code]](https://github.com/YuliangXiu/ICON)

1. [Neural Deformation Graphs for Globally-consistent Non-rigid Reconstruction](https://arxiv.org/abs/2012.01451). CVPR, 2021.

1. [S3: Neural Shape, Skeleton, and Skinning Fields for 3D Human Modeling](https://arxiv.org/abs/2101.06571). CVPR, 2021.

### Nerfs
1. [Neural Body: Implicit Neural Representations with Structured Latent Codes for Novel View Synthesis of Dynamic Humans](https://arxiv.org/abs/2012.15838). CVPR, 2021. [[Page]](https://zju3dv.github.io/neuralbody) [[Code]](https://github.com/zju3dv/neuralbody)

1. [H-NeRF: Neural Radiance Fields for Rendering and Temporal Reconstruction of Humans in Motion](https://arxiv.org/abs/2110.13746). NIPS, 2021.

1. [Animatable Neural Radiance Fields for Modeling Dynamic Human Bodies](https://arxiv.org/abs/2105.02872). ICCV, 2021. [[Page]](https://zju3dv.github.io/animatable_nerf) [[Code]](https://github.com/zju3dv/animatable_nerf)

1. [Neural Human Performer: Learning Generalizable Radiance Fields for Human Performance Rendering](https://arxiv.org/abs/2109.07448). ArXiv, 2021. [[Page]](https://youngjoongunc.github.io/nhp) 

1. [Neural Actor: Neural Free-view Synthesis of Human Actors with Pose Control](https://arxiv.org/abs/2106.02019). ArXiv, 2021.  

1. [A-NeRF: Articulated Neural Radiance Fields for Learning Human Shape, Appearance, and Pose](https://arxiv.org/abs/2102.06199). NIPS, 2021.

1. [HumanNeRF: Free-viewpoint Rendering of Moving People from Monocular Video](https://arxiv.org/abs/2201.04127). CVPR, 2022.

1. [DoubleField: Bridging the Neural Surface and Radiance Fields for High-fidelity Human Reconstruction and Rendering](https://arxiv.org/abs/2106.03798). CVPR, 2022. [[Page]](http://www.liuyebin.com/dbfield/dbfield.html) 

### Heads
1. [AD-NeRF: Audio Driven Neural Radiance Fields for Talking Head Synthesis](https://arxiv.org/abs/2103.11078). ICCV, 2021.

1. [Learning Compositional Radiance Fields of Dynamic Human Heads](https://arxiv.org/abs/2012.09955). CVPR, 2021.

1. [HeadNeRF: A Real-time NeRF-based Parametric Head Model](https://arxiv.org/abs/2112.05637). CVPR, 2022.

1. [FLAME-in-NeRF: Neural control of Radiance Fields for Free View Face Animation](https://arxiv.org/abs/2108.04913). FG, 2023.

### Editable
1. [UV Volumes for Real-time Rendering of Editable Free-view Human Performance](https://arxiv.org/abs/2203.14402). ArXiv, 2022. [[Page]](https://fanegg.github.io/UV-Volumes/) [[Code]](https://github.com/fanegg/UV-Volumes)

## Other Related Paper Lists
1. [3DFaceBody/awesome-3dbody-papers](https://github.com/3DFaceBody/awesome-3dbody-papers)

1. [rlczddl/awesome-3d-human-reconstruction](https://github.com/rlczddl/awesome-3d-human-reconstruction)

1. [weihaox/awesome-clothed-human](https://github.com/weihaox/awesome-clothed-human)
