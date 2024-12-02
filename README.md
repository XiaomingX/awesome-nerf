# Neural Radiance Fields (NeRF) 精选资源

这里为大家整理了一些与神经辐射场（NeRF）相关的重要论文和资源，希望能帮助对NeRF研究感兴趣的同仁们。

[高斯分割]( https://github.com/XiaomingX/awesome-3D-gaussian-splatting )

## 主要论文

| 年份 | 会议/期刊 | 代码 | 标题 | 其他信息 |
| :-: | :-: | :-: | :-: | :-: |
| 2020 | ECCV | [TensorFlow](https://github.com/bmild/nerf) [PyTorch](https://github.com/yenchenlin/nerf-pytorch) | [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://dl.acm.org/doi/pdf/10.1145/3503250) | [项目主页](https://www.matthewtancik.com/nerf) |

## 综述类论文

| 年份 | 会议/期刊 | 标题 | 链接 |
| :-: | :-: | :-: | :-: |
| 2022 | Computer Graphics Forum | Advances in Neural Rendering | [链接](https://arxiv.org/pdf/2111.05849.pdf) |
| 2022 | - | NeRF: Neural Radiance Field in 3D Vision, A Comprehensive Review | [链接](https://arxiv.org/pdf/2210.00379.pdf) |
| 2022 | Computer Graphics Forum | Neural Fields in Visual Computing and Beyond | [链接](https://arxiv.org/pdf/2111.11426.pdf) |

## NeRF任务分类

### 数据增强

| 年份 | 会议/期刊 | 代码 | 标题 | 其他信息 |
| :-: | :-: | :-: | :-: | :-: |
| 2022 | ECCV | [PyTorch](https://github.com/gyhandy/Neural-Sim-NeRF) | [Neural-Sim: Learning to Generate Training Data with NeRF](https://arxiv.org/pdf/2207.11368.pdf) | - |
| 2022 | CVPR | [PyTorch](https://github.com/VITA-Group/Aug-NeRF) | [Aug-NeRF: Training Stronger Neural Radiance Fields with Triple-Level Physically-Grounded Augmentations](https://openaccess.thecvf.com/content/CVPR2022/papers/Chen_Aug-NeRF_Training_Stronger_Neural_Radiance_Fields_With_Triple-Level_Physically-Grounded_Augmentations_CVPR_2022_paper.pdf) | - |

### 小样本学习

| 年份 | 会议/期刊 | 代码 | 标题 | 其他信息 |
| :-: | :-: | :-: | :-: | :-: |
| 2022 | NeurIPS | [TensorFlow](https://github.com/d2nerf/d2nerf) | [D^2NeRF: Self-Supervised Decoupling of Dynamic and Static Objects from a Monocular Video](https://arxiv.org/pdf/2205.15838.pdf) | [项目主页](https://d2nerf.github.io/) |
| 2022 | ECCV | - | [GeoAug: Data Augmentation for Few-Shot NeRF with Geometry Constrains](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136770326.pdf) | - |
| 2021 | ICCV | [PyTorch](https://github.com/ajayjain/DietNeRF) | [Putting NeRF on a Diet: Semantically Consistent Few-Shot View Synthesis](https://openaccess.thecvf.com/content/ICCV2021/papers/Jain_Putting_NeRF_on_a_Diet_Semantically_Consistent_Few-Shot_View_Synthesis_ICCV_2021_paper.pdf) | [项目主页](https://www.ajayj.com/dietnerf) |

### 渲染性能优化

| 年份 | 会议/期刊 | 代码 | 标题 | 其他信息 |
| :-: | :-: | :-: | :-: | :-: |
| 2022 | arXiv | [JAX](https://github.com/google-research/jax3d/tree/main/jax3d/projects/mobilenerf) | [MobileNeRF: Efficient Neural Field Rendering on Mobile Architectures](https://arxiv.org/pdf/2208.00277.pdf) | [项目主页](https://mobile-nerf.github.io/) |
| 2022 | ECCV | [PyTorch](https://github.com/apchenstu/TensoRF) | [TensoRF: Tensorial Radiance Fields](https://arxiv.org/pdf/2203.09517.pdf) | [项目主页](https://apchenstu.github.io/TensoRF/) |

## 数据集

| 年份 | 数据集名称 | 相关论文 | 任务 | 实例数量 | 备注 |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 2022 | [PeRFception](https://postech-cvlab.github.io/PeRFception/) | [PeRFception: Perception using Radiance Fields](https://openreview.net/pdf?id=MzaPEKHv-0J) | 2D/3D分类与分割 | 19k | - |
| 2021 | [NeuS-DATA](https://drive.google.com/drive/folders/1Nlzejs4mfPuJYORLbDEUDWlc9IZIbU0C) | [NeuS: Learning Neural Implicit Surfaces](https://arxiv.org/pdf/2106.10689.pdf) | 表面重建 | - | - |

## 相关演讲

| 年份 | 主题 | 演讲者/发布者 | 语言 |
| :-: | :-: | :-: | :-: |
| 2022 | [TensoRF: Tensorial Radiance Fields](https://www.youtube.com/watch?v=ujOMgaKV3lA) | Zexiang Xu | EN |
| 2022 | [Learning Dynamic Facial Radiance Fields for Few-Shot Talking Head Synthesis](https://www.youtube.com/watch?v=F6fkVNk9bBw) | Shens | EN |
| 2020 | [NeRF: Neural Radiance Fields](https://www.youtube.com/watch?v=JuH79E8rdKc) | Matthew Tancik | EN |
