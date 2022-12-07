# NeRF-Survey: Collection of Neural Radiance Field (NeRF) papers


The papers are organized in terms of category, then in terms of the date of ArXiv/preprint first draft. The official publication dates can be found in the bibtex files. 

If you find this survey/list useful in writing your manuscript(s), please consider citing our paper. 

@article{gao2022nerf,<br>
  title={Nerf: Neural radiance field in 3d vision, a comprehensive review},<br>
  author={Gao, Kyle and Gao, Yina and He, Hongjie and Lu, Denning and Xu, Linlin and Li, Jonathan},<br>
  journal={arXiv preprint arXiv:2210.00379},<br>
  year={2022}<br>
}<br>


## Survey papers:

Neural Volume Rendering: NeRF And Beyond, Dellaert and Yen-Chen, (Dec 17 2020) | [pdf](https://arxiv.org/abs/2101.05204) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/dellaert2020neural) | [github](https://github.com/yenchenlin/awesome-NeRF)

Advances in Neural Rendering, Tewari et al., (Nov 10 2021) | [pdf](https://arxiv.org/abs/2111.05849) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/tewari2022advances)

NeRF: Neural Radiance Field in 3D Vision, A Comprehensive Review, Gao et al., (Oct 1 2022) | [pdf](https://arxiv.org/abs/2210.00379) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/gao2022nerf)

## Journal/Conference papers:

[NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://www.matthewtancik.com/nerf), Mildenhall et al., (May 19 2020) | [pdf](https://arxiv.org/abs/2003.08934) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/mildenhall2021nerf) | [github](https://github.com/bmild/nerf)

### Fundamentals:

[Mip-nerf: A multiscale representation for anti-aliasing neural radiance fields](https://jonbarron.info/mipnerf/), Barron et al., (May 24 2021) | [pdf](https://arxiv.org/abs/2103.13415) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/barron2021mip) | [github](https://github.com/google/mipnerf)

[Ref-NeRF: Structured View-Dependent Appearance for Neural Radiance Fields](https://dorverbin.github.io/refnerf/), Verbin et al., (Dec 7 2021) | [pdf](https://arxiv.org/abs/2112.03907) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/verbin2022ref) | [github](https://github.com/google-research/multinerf)

### Unbound Scene:
NeRF++: Analyzing and Improving Neural Radiance Fields, Zhang et al., (Oct 15 2020) | [pdf](https://arxiv.org/abs/2010.07492) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/zhang2020nerf%2B%2B) | [github](https://github.com/Kai-46/nerfplusplus) |

[Mip-NeRF 360: Unbounded Anti-Aliased Neural Radiance Fields](https://jonbarron.info/mipnerf360/), Barron et al., (Nov 23 2021) | [pdf](https://arxiv.org/abs/2111.12077) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/barron2022mip) | [github](https://github.com/google-research/multinerf)


### Speed:

#### -Baked (Faster Inference):

FastNeRF: High-Fidelity Neural Rendering at 200FPS, Garbin et al. (18 Mar 2021) | [pdf](https://arxiv.org/abs/2103.10380) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/garbin2021fastnerf)

[PlenOctrees For Real-time Rendering of Neural Radiance Fields](https://alexyu.net/plenoctrees/), Yu et al, (Mar 25 2021) | [pdf](https://arxiv.org/abs/2103.14024) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/yu2021plenoctrees) | [github](https://github.com/sxyu/plenoctree)

[Baking Neural Radiance Fields for Real-Time View Synthesis](https://phog.github.io/snerg/), Hedman et al., (Mar 26 2021) | [pdf](https://arxiv.org/abs/2103.14645) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/hedman2021baking) | [github](https://github.com/google-research/google-research/tree/master/snerg)

KiloNeRF: Speeding up Neural Radiance Fields with Thousands of Tiny MLPs, Reiser et al., (Aug 2 2021) | [pdf](https://arxiv.org/abs/2103.13744) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/reiser2021kilonerf) | [github](https://github.com/creiser/kilonerf)

#### -Non-baked (Faster Inference and Typically Faster Training):

[Neural Sparse Voxel Fields](https://lingjie0206.github.io/papers/NSVF/), Liu et al., (Jul 22 2020) | [pdf](https://arxiv.org/abs/2007.11571) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/liu2020neural) | [github](https://github.com/facebookresearch/NSVF)

[AutoInt: Automatic integration for fast neural volume rendering](https://davidlindell.com/publications/autoint), Lindell et al., (Dec 3 2020) | [pdf](https://arxiv.org/abs/2012.01714) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/lindell2021autoint) | [github](https://github.com/computational-imaging/automatic-integration)

[Instant Neural Graphics Primitives with a Multiresolution Hash Encoding](https://nvlabs.github.io/instant-ngp/), Muller et al., (Jan 16 2022) | [pdf](https://arxiv.org/abs/2201.05989) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/muller2022instant) | [github](https://github.com/NVlabs/instant-ngp)


### Few-shot/Sparse View (Typically Faster Training):
[PixelNeRF Neural Radiance Fields from One or Few Images](https://alexyu.net/pixelnerf/), Yu et al., (Dec 3 2020) | [pdf](https://arxiv.org/abs/2012.02190) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/yu2021pixelnerf) | [github](https://github.com/sxyu/pixel-nerf)

[MVSNeRF: Fast Generalizable Radiance Field Reconstruction from Multi-View Stereo](https://apchenstu.github.io/mvsnerf/), Chen et al., (Mar 29 2021) | [pdf](https://arxiv.org/abs/2103.15595) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/chen2021mvsnerf) | [github](https://github.com/apchenstu/mvsnerf)

Putting NeRF on a Diet: Semantically Consistent Few-Shot View Synthesis, Jain et al., (April 1 2021) | [pdf](https://arxiv.org/abs/2104.00677) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/jain2021putting) | [github](https://github.com/ajayjain/DietNeRF)

[Depth-supervised NeRF: Fewer Views and Faster Training for Free](https://www.cs.cmu.edu/~dsnerf/), Deng et al., (Jul 6 2021) | [pdf](https://arxiv.org/abs/2107.02791) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/deng2022depth) | [github](https://github.com/dunbar12138/DSNeRF)

[Neural Rays for Occlusion-aware Image-based Rendering](https://liuyuan-pal.github.io/NeuRay/), Liu et al., (Jul 28 2021) | [pdf](https://arxiv.org/abs/2107.13421) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/liu2022neural) | [github](https://github.com/liuyuan-pal/NeuRay)



### Latent-Conditional 

### Latent-Generative
[GIRAFFE Representing Scenes as Compositional Generative Neural Feature Fields](https://m-niemeyer.github.io/project-pages/giraffe/index.html), Niemeyer and Geiger, (Nov 24, 2020) | [pdf](https://arxiv.org/abs/2011.12100) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/niemeyer2021giraffe) | [github](https://github.com/autonomousvision/giraffe)

[Generative Radiance Fields for 3D-Aware Image Synthesis](https://autonomousvision.github.io/graf/), Schwarz et al., (Jul 5 2020) | [pdf](https://arxiv.org/abs/2007.02442) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/schwarz2020graf) | [github](https://github.com/autonomousvision/graf)

[pi-GAN: Periodic Implicit Generative Adversarial Networks for 3D-Aware Image Synthesis](https://marcoamonteiro.github.io/pi-GAN-website/), Chan et al., (Dec 2 2020) | [pdf](https://arxiv.org/abs/2012.00926) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/chan2021pi) | [github](https://github.com/marcoamonteiro/pi-GAN)

GNeRF: GAN-based Neural Radiance Field without Posed Camera, Meng et al., (Mar 29 2021) | [pdf](https://arxiv.org/abs/2103.15606) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/meng2021gnerf) | [github](https://github.com/quan-meng/gnerf)

[Pix2NeRF: Unsupervised Conditional p-GAN for Single Image to Neural Radiance Fields Translation](https://vas.mpi-inf.mpg.de/pix2nerf/), Cai et al., (Feb 26, 2022) | [pdf](https://arxiv.org/abs/2202.13162) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/cai2022pix2nerf) | [github](https://github.com/primecai/Pix2NeRF)



### Pose Estimation

### Scene Composition

#### -Labelling

#### -Editing



### Urban
[NeRF in the Wild: Neural Radiance Fields for Unconstrained Photo Collections](https://nerf-w.github.io/), Martin-Brualla et al., (Aug 5 2020) | [pdf](https://arxiv.org/abs/2008.02268) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/martin2021nerf) | [github-non official](https://github.com/kwea123/nerf_pl)

[Ha-NeRF: Hallucinated Neural Radiance Fields in the Wild](https://rover-xingyu.github.io/Ha-NeRF/), Chen et al., (Nov 30 2021) | [pdf](https://arxiv.org/abs/2111.15246) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/new/main/Citations/chen2022hallucinated) | [github](https://github.com/rover-xingyu/Ha-NeRF)

### Human Body/Face

### Surface/Voxel/Depth Reconstruction

NerfingMVS: Guided Optimization of Neural Radiance Fields for Indoor Multi-view Stereo, Wei et al., (Sep 2 2021) | [pdf](https://arxiv.org/abs/2109.01129) | [bibtex](https://github.com/kyle-gao/NeRF-Survey/blob/main/Citations/wei2021nerfingmvs) | [github](https://github.com/weiyithu/NerfingMVS)

### Scene Editing/Labelling

### Denoising/Deblurring/Super-resolution

