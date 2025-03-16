# Quick start
Wang, Zhiwen, et al. "One network to solve them all: A sequential multi-task joint learning network framework for MR imaging pipeline." Machine Learning for Medical Image Reconstruction: 4th International Workshop, MLMIR 2021, Held in Conjunction with MICCAI 2021, Strasbourg, France, October 1, 2021, Proceedings 4. Springer International Publishing, 2021.

Running the shell scripts below would plot the Figure2b in our paper.
```bash
bash demo.sh
```

All data and models can be downloaded in [Google-drive](https://drive.google.com/file/d/1fdxsNnbEURpetsH9seP4RRv9nML2y2i1/view?usp=sharing).

It is a `zip file` (~843M) which contain a `demo testing data` and `parameter files of compared models`. 

Then place the `demo testing data` in:

```
├── datasets
│   ├── brain
│   │   ├── OASI1_MRB
│   │   ├── testing-h5py
│   │   │   ├── demo
│   │   │   │   └── oasis1_disc1_OAS1_0042_MR1.h5
│   ├── cardiac
│   └── prostate
```

place the `parameter files` in:
```
├── model_zoo
│   ├── pretrained_seg
│   │   └── OASI1_MRB_3seg.pth
│   └── tab1
│       └── OASI1_MRB
│           ├── asl_ablation_seqmdrecnet_bg_step3_1_local__0.05_2D.pth
│           ├── csl_seqmri_unet__0.05_2D.pth
│           ├── csmri1__0.05.pth
│           ├── csmri2__5.pth
│           └── csmtl__0.05.pth
```
