# NeRF-Survey: Collection of Neural Radiance Field (NeRF) papers


The papers are organized in terms of category, then in terms of the date of ArXiv/preprint first draft. The official publication dates can be found in the bibtex files. 

If you find this survey/list useful in writing your manuscript(s), please consider citing our paper. 

@article{gao2022nerf,<br>
  title={Nerf: Neural radiance field in 3d vision, a comprehensive review},<br>
  author={Gao, Kyle and Gao, Yina and He, Hongjie and Lu, Denning and Xu, Linlin and Li, Jonathan},<br>
  journal={arXiv preprint arXiv:2210.00379},<br>
  year={2022}<br>
}<br>


To submit a pr for additional entries: 
1) create a bibtex file in NeRF-Survey/Citations/
2) Insert your entry, ordered by frist draft date, in the README.ME with:

[paper title](link to project page), AUTHORS, (First Draft Date) | \[pdf\](link to pdf) | \[bibtex\](link to NeRF-Survey/Citations/\<MyEntry\>) | \[github\](link to code repo)

## Survey papers:

Neural Volume Rendering: NeRF And Beyond, Dellaert and Yen-Chen, (Dec 17 2020) | [pdf](https://arxiv.org/abs/2101.05204) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/dellaert2020neural) | [github](https://github.com/yenchenlin/awesome-NeRF)

Advances in Neural Rendering, Tewari et al., (Nov 10 2021) | [pdf](https://arxiv.org/abs/2111.05849) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/tewari2022advances)

NeRF: Neural Radiance Field in 3D Vision, A Comprehensive Review, Gao et al., (Oct 1 2022) | [pdf](https://arxiv.org/abs/2210.00379) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/gao2022nerf)

## Journal/Conference papers:

[NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://www.matthewtancik.com/nerf), Mildenhall et al., (May 19 2020) | [pdf](https://arxiv.org/abs/2003.08934) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/mildenhall2021nerf) | [github](https://github.com/bmild/nerf)

### Fundamentals

[Mip-nerf: A multiscale representation for anti-aliasing neural radiance fields](https://jonbarron.info/mipnerf/), Barron et al., (May 24 2021) | [pdf](https://arxiv.org/abs/2103.13415) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/barron2021mip) | [github](https://github.com/google/mipnerf)

[Ref-NeRF: Structured View-Dependent Appearance for Neural Radiance Fields](https://dorverbin.github.io/refnerf/), Verbin et al., (Dec 7 2021) | [pdf](https://arxiv.org/abs/2112.03907) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/verbin2022ref) | [github](https://github.com/google-research/multinerf)

[NeRF in the Dark: High Dynamic Range View Synthesis from Noisy Raw Images](https://bmild.github.io/rawnerf/) | Mildenhal et al.,(Nov 26 2021) | [pdf](https://arxiv.org/abs/2111.13679) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/mildenhall2022nerf) | [github](https://github.com/google-research/multinerf)

### Unbound Scene
NeRF++: Analyzing and Improving Neural Radiance Fields, Zhang et al., (Oct 15 2020) | [pdf](https://arxiv.org/abs/2010.07492) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/zhang2020nerf%2B%2B) | [github](https://github.com/Kai-46/nerfplusplus) |

[Mip-NeRF 360: Unbounded Anti-Aliased Neural Radiance Fields](https://jonbarron.info/mipnerf360/), Barron et al., (Nov 23 2021) | [pdf](https://arxiv.org/abs/2111.12077) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/barron2022mip) | [github](https://github.com/google-research/multinerf)


### Speed

#### -Baked (Faster Inference)

FastNeRF: High-Fidelity Neural Rendering at 200FPS, Garbin et al. (18 Mar 2021) | [pdf](https://arxiv.org/abs/2103.10380) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/garbin2021fastnerf)

[PlenOctrees For Real-time Rendering of Neural Radiance Fields](https://alexyu.net/plenoctrees/), Yu et al, (Mar 25 2021) | [pdf](https://arxiv.org/abs/2103.14024) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/yu2021plenoctrees) | [github](https://github.com/sxyu/plenoctree)

[Baking Neural Radiance Fields for Real-Time View Synthesis](https://phog.github.io/snerg/), Hedman et al., (Mar 26 2021) | [pdf](https://arxiv.org/abs/2103.14645) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/hedman2021baking) | [github](https://github.com/google-research/google-research/tree/master/snerg)

KiloNeRF: Speeding up Neural Radiance Fields with Thousands of Tiny MLPs, Reiser et al., (Aug 2 2021) | [pdf](https://arxiv.org/abs/2103.13744) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/reiser2021kilonerf) | [github](https://github.com/creiser/kilonerf)

#### -Non-baked (Faster Inference and Typically Faster Training)

[Neural Sparse Voxel Fields](https://lingjie0206.github.io/papers/NSVF/), Liu et al., (Jul 22 2020) | [pdf](https://arxiv.org/abs/2007.11571) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/liu2020neural) | [github](https://github.com/facebookresearch/NSVF)

[AutoInt: Automatic integration for fast neural volume rendering](https://davidlindell.com/publications/autoint), Lindell et al., (Dec 3 2020) | [pdf](https://arxiv.org/abs/2012.01714) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/lindell2021autoint) | [github](https://github.com/computational-imaging/automatic-integration)

[Instant Neural Graphics Primitives with a Multiresolution Hash Encoding](https://nvlabs.github.io/instant-ngp/), Muller et al., (Jan 16 2022) | [pdf](https://arxiv.org/abs/2201.05989) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/muller2022instant) | [github](https://github.com/NVlabs/instant-ngp)

#### -MLP-less/Direct radiance fields

[Direct Voxel Grid Optimization: Super-fast Convergence for Radiance Fields Reconstruction](https://sunset1995.github.io/dvgo/), Sun et al., (Nov 22 2021) | [pdf](https://arxiv.org/abs/2111.11215) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/sun2022improved) | [github](https://github.com/sunset1995/DirectVoxGO)

[Plenoxels: Radiance Fields without Neural Networks](https://alexyu.net/plenoxels/), Yu et al., (Dec 9 2021) | [pdf](https://arxiv.org/abs/2112.05131) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/yu2021plenoxels) | [github](https://github.com/sxyu/svox2)

[TensoRF: Tensorial Radiance Fields](https://apchenstu.github.io/TensoRF/), Chen et al., (Mar 17 2022) | [pdf](https://arxiv.org/abs/2203.09517) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/Chen2022ECCV) | [github](https://github.com/apchenstu/TensoRF)


### Few-shot/Sparse View (Typically Faster Training)
[GRF: Learning a General Radiance Field for 3D Representation and Rendering](), Trevithick and Yang, (Oct 9 2020) | [pdf](https://arxiv.org/abs/2010.04595) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/trevithick2021grf) | [github](https://github.com/alextrevithick/GRF)

[PixelNeRF Neural Radiance Fields from One or Few Images](https://alexyu.net/pixelnerf/), Yu et al., (Dec 3 2020) | [pdf](https://arxiv.org/abs/2012.02190) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/yu2021pixelnerf) | [github](https://github.com/sxyu/pixel-nerf)

[MVSNeRF: Fast Generalizable Radiance Field Reconstruction from Multi-View Stereo](https://apchenstu.github.io/mvsnerf/), Chen et al., (Mar 29 2021) | [pdf](https://arxiv.org/abs/2103.15595) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/chen2021mvsnerf) | [github](https://github.com/apchenstu/mvsnerf)

Putting NeRF on a Diet: Semantically Consistent Few-Shot View Synthesis, Jain et al., (April 1 2021) | [pdf](https://arxiv.org/abs/2104.00677) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/jain2021putting) | [github](https://github.com/ajayjain/DietNeRF)

[Depth-supervised NeRF: Fewer Views and Faster Training for Free](https://www.cs.cmu.edu/~dsnerf/), Deng et al., (Jul 6 2021) | [pdf](https://arxiv.org/abs/2107.02791) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/deng2022depth) | [github](https://github.com/dunbar12138/DSNeRF)

[Neural Rays for Occlusion-aware Image-based Rendering](https://liuyuan-pal.github.io/NeuRay/), Liu et al., (Jul 28 2021) | [pdf](https://arxiv.org/abs/2107.13421) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/liu2022neural) | [github](https://github.com/liuyuan-pal/NeuRay)



### Latent-Conditional 
[Starting from NeRF-W, most urban/outdoors methods use latent codes to condition for lighting/appearance.](#urbanoutdoors) Many deformation models ([faces](#Face) and [bodies](#humanarticulated-body)) use latent codes to code for pose/deformation. Many [scene editing](#Edit) models use latent codes to condition for object pose/deformation.  

### Latent-Generative
[GIRAFFE Representing Scenes as Compositional Generative Neural Feature Fields](https://m-niemeyer.github.io/project-pages/giraffe/index.html), Niemeyer and Geiger, (Nov 24, 2020) | [pdf](https://arxiv.org/abs/2011.12100) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/niemeyer2021giraffe) | [github](https://github.com/autonomousvision/giraffe)

[Generative Radiance Fields for 3D-Aware Image Synthesis](https://autonomousvision.github.io/graf/), Schwarz et al., (Jul 5 2020) | [pdf](https://arxiv.org/abs/2007.02442) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/schwarz2020graf) | [github](https://github.com/autonomousvision/graf)

[pi-GAN: Periodic Implicit Generative Adversarial Networks for 3D-Aware Image Synthesis](https://marcoamonteiro.github.io/pi-GAN-website/), Chan et al., (Dec 2 2020) | [pdf](https://arxiv.org/abs/2012.00926) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/chan2021pi) | [github](https://github.com/marcoamonteiro/pi-GAN)

GNeRF: GAN-based Neural Radiance Field without Posed Camera, Meng et al., (Mar 29 2021) | [pdf](https://arxiv.org/abs/2103.15606) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/meng2021gnerf) | [github](https://github.com/quan-meng/gnerf)

[Pix2NeRF: Unsupervised Conditional p-GAN for Single Image to Neural Radiance Fields Translation](https://vas.mpi-inf.mpg.de/pix2nerf/), Cai et al., (Feb 26, 2022) | [pdf](https://arxiv.org/abs/2202.13162) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/cai2022pix2nerf) | [github](https://github.com/primecai/Pix2NeRF)



### Pose Estimation
[INeRF: Inverting Neural Radiance Fields for Pose Estimation](http://yenchenlin.me/inerf/), Yen-Chen et al, (Dec 10 2020) | [pdf](https://arxiv.org/abs/2012.05877) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/yen2021inerf) | [github](https://github.com/yenchenlin/iNeRF-public)

[NeRF--: Neural Radiance Fields Without Known Camera Parameters](https://nerfmm.active.vision/), Wang et al., (Feb 14 2021) | [pdf](https://arxiv.org/abs/2102.07064) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/wang2021nerf) | [github](https://github.com/ActiveVisionLab/nerfmm)

[Self-Calibrating Neural Radiance Fields](https://postech-cvlab.github.io/SCNeRF/), Jeong et al., (Aug 31 2021) | [pdf](https://arxiv.org/abs/2108.13826) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/jeong2021self) | [github] (https://github.com/POSTECH-CVLab/SCNeRF)

[BARF: Bundle-Adjusting Neural Radiance Fields](https://chenhsuanlin.bitbucket.io/bundle-adjusting-NeRF/), Lin et al., (Apr 13 2021) | [pdf](https://arxiv.org/abs/2104.06405) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/jeong2021self) | [github](https://github.com/chenhsuanlin/bundle-adjusting-NeRF)

#### -SLAM

[iMAP Implicit Mapping and Positioning in Real-Time](https://edgarsucar.github.io/iMAP/), Sucar et al., (Mar 23 2021) | [pdf](https://arxiv.org/abs/2103.12352) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/sucar2021imap)


[NICE-SLAM: Neural Implicit Scalable Encoding for SLAM](https://pengsongyou.github.io/nice-slam), Zhu et al., (Dec 22 2021) | [pdf](https://arxiv.org/abs/2112.12130) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/zhu2022nice) | [github](https://github.com/cvg/nice-slam)
### Scene Composition

#### -Labelling
[In-Place Scene Labelling and Understanding with Implicit Scene Representation](https://shuaifengzhi.com/Semantic-NeRF/), Zhi et al., (Mar 29 2021) | [pdf](https://arxiv.org/abs/2103.15875) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/zhi2021place) | [github](https://github.com/Harry-Zhi/semantic_nerf/)

[FiG-NeRF: Figure Ground Neural Radiance Fields for 3D Object Category Modelling](https://fig-nerf.github.io/), Xie et al., (Apr 17 2021) | [pdf](https://arxiv.org/abs/2104.08418) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/xie2021fig) 

[NeSF: Neural Semantic Fields for Generalizable Semantic Segmentation of 3D Scenes](https://nesf3d.github.io/), Vora et al., (Nov 25 2021) | [pdf](https://arxiv.org/abs/2111.13260) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/vora2021nesf) | [github](https://github.com/google-research/jax3d/tree/main/jax3d/projects/nesf)

[Panoptic Neural Fields: A Semantic Object-Aware Neural Scene Representation](https://deepai.org/publication/panoptic-neural-fields-a-semantic-object-aware-neural-scene-representation), Kundu et al., (May 9 2022) | [pdf](https://arxiv.org/abs/2205.04334) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/kundu2022panoptic)

#### -[Editing](#Edit)

[Editing Conditional Radiance Fields](http://editnerf.csail.mit.edu/), Liu et al., (May 13 2021) | [pdf](https://arxiv.org/abs/2105.06466) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/wang2022clip) | [github](https://github.com/stevliu/editnerf)

[CodeNeRF : Disentangled Neural Radiance Fields for Object Categories](https://sites.google.com/view/wbjang/home/codenerf), Jang and Agapito, (Sep 3 2021) | [pdf](https://arxiv.org/abs/2109.01750) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/jang2021codenerf) | [github](https://github.com/wbjang/code-nerf)

[Learning Object-Compositional Neural Radiance Field for Editable Scene Rendering](https://zju3dv.github.io/object_nerf/), Yang et al., (Sep 4 2021) | [pdf](https://arxiv.org/abs/2109.01847) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/yang2021learning) | [github](https://github.com/zju3dv/object_nerf)

[CoNeRF: Controllable Neural Radiance Fields](https://conerf.github.io/), Kania et al., (Dec 3 2021) | [pdf](https://arxiv.org/abs/2112.01983) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/kania2022conerf) | [github](https://github.com/kacperkan/conerf)

[CLIP-NeRF: Text-and-Image Driven Manipulation of Neural Radiance Fields](https://cassiepython.github.io/clipnerf/), Wang et al., (Dec 9 2021) | [pdf](https://arxiv.org/abs/2112.05139) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/wang2022clip) | [github](https://github.com/cassiePython/CLIPNeRF)


### [Urban/Outdoors](#Urban)
[NeRF in the Wild: Neural Radiance Fields for Unconstrained Photo Collections](https://nerf-w.github.io/), Martin-Brualla et al., (Aug 5 2020) | [pdf](https://arxiv.org/abs/2008.02268) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/martin2021nerf) | [github-non official](https://github.com/kwea123/nerf_pl)

[Urban Radiance Fields](https://urban-radiance-fields.github.io/), Rematas et al., (Nov 29 2021) | [pdf](https://arxiv.org/abs/2111.14643) | bibtex (https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/rematas2022urban) 


[Ha-NeRF: Hallucinated Neural Radiance Fields in the Wild](https://rover-xingyu.github.io/Ha-NeRF/), Chen et al., (Nov 30 2021) | [pdf](https://arxiv.org/abs/2111.15246) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/chen2022hallucinated) | [github](https://github.com/rover-xingyu/Ha-NeRF)

[Block-NeRF: Scalable Large Scene Neural View Synthesis](https://waymo.com/research/block-nerf/), Tancik et al., (Feb 10 2022) | [pdf](https://arxiv.org/abs/2202.05263) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/tancik2022block)


### Aerial 
Shadow Neural Radiance Fields for Multi-view Satellite Photogrammetry, Derksen and Izzo, (Apr 20 2021) | [pdf](https://arxiv.org/abs/2104.09877) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/derksen2021shadow) |[github](https://github.com/esa/snerf)

[BungeeNeRF: Progressive Neural Radiance Field for Extreme Multi-scale Scene Rendering](https://city-super.github.io/citynerf/), Xiangli et al., (Dec 10 2021) | [pdf](https://arxiv.org/abs/2112.05504) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/xiangli2022bungeenerf) | [github](https://github.com/city-super/BungeeNeRF)

[Mega-NeRF: Scalable Construction of Large-Scale NeRFs for Virtual Fly-Throughs](https://meganerf.cmusatyalab.org/), Turki et al., (Dec 20 2021) | [pdf](https://arxiv.org/abs/2112.10703) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/turki2022mega) | [github](https://github.com/cmusatyalab/mega-nerf)

[Sat-NeRF: Learning Multi-View Satellite Photogrammetry With Transient Objects and Shadow Modeling Using RPC Cameras](https://centreborelli.github.io/satnerf/), Mari et al., (Mar 16 2022) | [pdf](https://arxiv.org/abs/2203.08896) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/mari2022sat) | [github](https://github.com/centreborelli/satnerf)

### [Human/Articulated Body](#Body)
[Neural Body: Implicit Neural Representations with Structured Latent Codes for Novel View Synthesis of Dynamic Humans](https://zju3dv.github.io/neuralbody/), Peng et al., (Dec 31 2020) | [pdf](https://arxiv.org/abs/2012.15838) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/peng2021neural) | [github](https://github.com/zju3dv/neuralbody)

[A-NeRF: Articulated Neural Radiance Fields for Learning Human Shape, Appearance, and Pose](https://lemonatsu.github.io/anerf/), Su et al., (Feb 11 2021) | [pdf](https://arxiv.org/abs/2102.06199) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/su2021nerf) | [github](https://github.com/LemonATsu/A-NeRF)

[HumanNeRF: Efficiently Generated Human Radiance Field from Sparse Inputs](https://zhaofuq.github.io/humannerf/), Zhao et al., (Dec 6 2021) | [pdf](https://arxiv.org/abs/2112.02789) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/zhao2022humannerf) | [github](https://github.com/zhaofuq/HumanNeRF)

[HumanNeRF: Free-viewpoint Rendering of Moving People from Monocular Video](https://grail.cs.washington.edu/projects/humannerf/), Weng et al., (Jan 11 2022) | [pdf](https://arxiv.org/abs/2201.04127) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/weng2022humannerf) | [github](https://github.com/chungyiweng/humannerf)

[Structured Local Radiance Fields for Human Avatar Modeling](https://liuyebin.com/slrf/slrf.html), Zheng et al., (Mar 28 2022) | [pdf](https://arxiv.org/abs/2203.14478) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/zheng2022structured) 


### [Face](#Face)
[Nerfies: Deformable Neural Radiance Fields](https://nerfies.github.io/), Park et al., (Nov 25 2020) | [pdf](https://arxiv.org/abs/2011.12948) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/park2021nerfies) | [github](https://github.com/google/nerfies)

[A Higher-Dimensional Representation for Topologically Varying Neural Radiance Fields](https://hypernerf.github.io/), Park et al., (Jun 24 2021) | [pdf](https://arxiv.org/abs/2106.13228) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/park2021hypernerf) | [github](https://github.com/google/hypernerf)

[HeadNeRF: A Real-time NeRF-based Parametric Head Model](https://hy1995.top/HeadNeRF-Project/), Hong et al., (Dec 10 2021) | [pdf](https://arxiv.org/abs/2112.05637) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/hong2022headnerf) | [github](https://github.com/CrisHY1995/headnerf)

### 3D(Surface/voxel/depth) Reconstruction
[Neural RGB-D Surface Reconstruction](https://dazinovic.github.io/neural-rgbd-surface-reconstruction/), Azinovic et al., (Apr 9 2021) | [pdf](https://arxiv.org/abs/2104.04532) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/azinovic2022neural) | [github](https://github.com/dazinovic/neural-rgbd-surface-reconstruction)

[UNISURF: Unifying Neural Implicit Surfaces and Radiance Fields for Multi-View Reconstruction](https://moechsle.github.io/unisurf/), Oechsle et al., (Apr 20 2021) | [pdf](https://arxiv.org/abs/2104.10078) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/oechsle2021unisurf) | [github](https://github.com/autonomousvision/unisurf)

[NeuS: Learning Neural Implicit Surfaces by Volume Rendering for Multi-view Reconstruction](https://lingjie0206.github.io/papers/NeuS/), Wang et al., (Jun 20 2021) | [pdf](https://arxiv.org/abs/2106.10689) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/wang2021neus) | [github](https://github.com/Totoro97/NeuS)

NerfingMVS: Guided Optimization of Neural Radiance Fields for Indoor Multi-view Stereo, Wei et al., (Sep 2 2021) | [pdf](https://arxiv.org/abs/2109.01129) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/wei2021nerfingmvs) | [github](https://github.com/weiyithu/NerfingMVS)


### Denoising/Deblurring/Super-resolution

[Deblur-NeRF: Neural Radiance Fields from Blurry Images](https://limacv.github.io/deblurnerf/), Ma et al., (Nov 29 2021) | [pdf](https://arxiv.org/abs/2111.14292) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/ma2022deblur) | [github](https://github.com/limacv/Deblur-NeRF)

[NeRF-SR: High-Quality Neural Radiance Fields using Super-Sampling](https://cwchenwang.github.io/NeRF-SR/), Wang et al., (Dec 3 2021) | [pdf](https://arxiv.org/abs/2112.01759) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/wang2022nerf) | [github](https://github.com/cwchenwang/NeRF-SR)

[NAN: Noise-Aware NeRFs for Burst-Denoising](https://noise-aware-nerf.github.io/), Pearl et al., (Apr 10 2022) | [pdf](https://arxiv.org/abs/2204.04668) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/pearl2022nan) | [github](https://github.com/NaamaPearl/nan)
