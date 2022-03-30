# FS6D 
This is the official source code for the CVPR 2022 work, **FS6D: Few-Shot 6D Pose Estimation of Novel Objects**.

[Project Page](fs6d.github.io) | [Arxiv](https://arxiv.org/abs/2203.14628) | [ShapeNet6D](https://hkustconnect-my.sharepoint.com/:f:/g/personal/yhebk_connect_ust_hk/Ek9OaY-nmD1GqOZdqV05AbIBZqrPpGMqAZSqoqNHBps23Q?e=VF2Ozk)

## Introduction & Citation
<div align=center><img width="55%" src="figs/intro.png"/></div>
We study the new open-set few-shot 6D object poses estimation problem: estimating the 6D pose of an unknown object by a few support views without CAD models and extra training. We propose a large-scale synthesis dataset for network pretraining. We also discuss possible solution to the problem and introduce a dense prototypes matching framework. The benchmark for the problem is established to facilitate future research as well.


Please cite FS6D if you use this repository or the ShapeNet6D dataset in your publications:

```
@InProceedings{he2022fs6d,
  author    = {Yisheng, He and Yao, Wang and Haoqiang, Fan and Qifeng, Chen and Jian, Sun},
  title     = {FS6D: Few-Shot 6D Pose Estimation of Novel Objects},
  booktitle = {IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  month     = {June},
  year      = {2022},
}
```

## Installation

## Datasets
- **ShapeNet6D:** Download the ShapeNet6D dataset from [OneDrive](https://hkustconnect-my.sharepoint.com/:f:/g/personal/yhebk_connect_ust_hk/Ek9OaY-nmD1GqOZdqV05AbIBZqrPpGMqAZSqoqNHBps23Q?e=VF2Ozk).
- **LineMOD:** Download the LineMOD dataset from [BOP Benchmark](https://bop.felk.cvut.cz/datasets/).
- **YCB-Video:** Download the YCB-Video Dataset from [BOP Benchmark](https://bop.felk.cvut.cz/datasets/).

## Training and evaluating

### Training on the ShapeNet6D Dataset

### Finetuning on the LineMOD Dataset
### Finetuning on the YCB-Video Dataset

### Evaluating on the YCB-Video Dataset

## License
Licensed under the [MIT License](./LICENSE).

