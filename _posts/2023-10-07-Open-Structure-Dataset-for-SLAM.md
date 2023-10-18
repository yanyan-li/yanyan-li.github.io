---
layout: post
title: "Open-Structure: a Structural Benchmark Dataset for SLAM Algorithms"
author:
- Y. Li
- Z. Guo
- Z. Yang
- Y. Sun
- L. Zhao
- F. Tombari
---


<div style="float:left;margin:0 10px 10px 0" class="col-md-4" markdown="1">
  <!-- ![Alt Text](../img/folder/blah.jpg) -->
  <img width="300px" class="center-block" src="../../../images/dataset_post/live_demo.gif">
  </div>
 *This paper introduces a new benchmark dataset, Open-Structure, for evaluating visual odometry and SLAM methods, which directly equips point and line measurements, correspondences, structural associations, and co-visibility factor graphs instead of providing raw images. Based on the proposed benchmark dataset, these 2D or 3D data can be directly input to different stages of SLAM pipelines to avoid the impact of the data preprocessing modules in ablation experiments.*


<p align="center">
     <a href="https://arxiv.org/pdf/2310.10931.pdf"><img src="https://img.shields.io/badge/OpenStructure-Paper-yellow.svg"></a>
  <a href="https://github.com/yanyan-li/Open-Structure/tree/main/dataset"><img src="https://img.shields.io/badge/OpenStructure-Dataset-green.svg"></a>
    <a href="https://github.com/yanyan-li/Open-Structure/tree/main/baseline"><img src="https://img.shields.io/badge/OpenStructure-Baseline-blue.svg"></a>
</p>

### 1. List of sequences

| *office0:* [img](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/office0/img.zip) \|  [observation](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/office0/observation.zip) \| [initial factor graph](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/office0/baseline.zip) | *livingroom0:*  [img](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/livingroom0/img.zip) \| [observation](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/livingroom0/observation.zip) \| [initial factor graph](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/livingroom0/baseline.zip) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![of0](../../../images/dataset_post/of0.png)                 | ![lrkt0](../../../images/dataset_post/lrkt0.png)             |
| *office1:*  [img](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/office1/img.zip) \|[observation](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/office1/observation.zip) \| [initial factor graph](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/office1/baseline.zip) | *livingroom1:*  [img](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/livingroom1/img.zip) \| [observation](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/livingroom1/observation.zip) \| [initial factor graph](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/livingroom1/baseline.zip) |
| ![of1](../../../images/dataset_post/of1.png)                 | ![lrkt1](../../../images/dataset_post/lrkt1.png)             |
| *office2:*  [img](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/office2/img.zip) \| [observation](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/office2/observation.zip) \| [initial factor graph](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/office2/baseline.zip) | *livingroom2:*  [img](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/livingroom2/img.zip) \| [observation](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/livingroom2/observation.zip) \| [initial factor graph](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/livingroom2/baseline.zip) |
| ![of2](../../../images/dataset_post/of2.png)                 | ![lrkt2](../../../images/dataset_post/lrkt2.png)             |
| *office3:*  [img](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/office3/img.zip) \| [observation](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/office3/observation.zip) \| [initial factor graph](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/office3/baseline.zip) | *livingroom3:*  [img](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/livingroom3/img.zip) \| [observation](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/livingroom3/observation.zip) \| [initial factor graph](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/livingroom3/baseline.zip) |
| ![of3](../../../images/dataset_post/of3.png)                 | ![lrkt3](../../../images/dataset_post/lrkt3.png)             |



| *nostr_textrue_far*:  [img](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/nostructure_texture_far/img.zip) \| [observation](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/nostructure_texture_far/observation.zip) \| [initial factor graph](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/nostructure_texture_far/baseline.zip) | *box1:*  [img](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/box1/img.zip) \| [observation](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/box1/observation.zip) \| [initial factor graph](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/box1/baseline.zip) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![nostructure_texture_far](../../../images/dataset_post/nostructure_texture_far.png) | ![box1](../../../images/dataset_post/box1.png)               |
| *nostr_texture_near_loop:*  [img](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/nostr_texture_near_loop/img.zip) \| [observation](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/nostr_texture_near_loop/observation.zip) \| [initial factor graph](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/nostr_texture_near_loop/baseline.zip) | *box2*:  [img](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/box2/img.zip) \| [observation](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/box2/observation.zip) \| [initial factor graph](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/box2/baseline.zip) |
| ![nostructure_texture_near_withloop](../../../images/dataset_post/nostructure_texture_near_withloop.png) | ![box2](../../../images/dataset_post/box2.png)               |
| *str_notexture_far*:  [img](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/str_notexture_far/img.zip) \| [observation](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/str_notexture_far/observation.zip) \| [initial factor graph](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/str_notexture_far/baseline.zip) | *corridor1*:  [img](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/corridor1/img.zip) \| [observation](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/corridor1/observation.zip) \| [initial factor graph](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/corridor1/baseline.zip) |
| ![structure_notexture_far](../../../images/dataset_post/structure_notexture_far.png) | ![corridor1](../../../images/dataset_post/corridor1.png)     |
| *str_notexture_near*:  [img](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/str_notexture_near/img.zip) \| [observation](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/str_notexture_near/observation.zip) \|[initial factor graph](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/str_notexture_near/baseline.zip) | *corridor2*:  [img](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/corridor2/img.zip) \| [observation](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/corridor2/observation.zip) \| [initial factor graph](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/corridor2/baseline.zip) |
| ![structure_notexture_near](../../../images/dataset_post/structure_notexture_near.png) | ![corridor2](../../../images/dataset_post/corridor2.png)     |
| *str_texture_near*:  [img](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/str_texture_near/img.zip) \| [observation](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/str_texture_near/observation.zip) \| [initial factor graph](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/str_texture_near/baseline.zip) | *sphere1*:  [img](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/sphere1/img.zip) \| [observation](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/sphere1/observation.zip) \| [initial factor graph](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/sphere1/baseline.zip) |
| ![structure_texture_far](../../../images/dataset_post/structure_texture_far.png) | ![sphere1](../../../images/dataset_post/sphere1.png)         |
| *str_texture_far*:  [img](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/str_texture_far/img.zip) \| [observation](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/str_texture_far/observation.zip) \| [initial factor graph](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/str_texture_far/baseline.zip) | *sphere2*:  [img](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/sphere2/img.zip) \| [observation](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/sphere2/observation.zip) \| [initial factor graph](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/sphere2/baseline.zip) |
| ![structure_texture_near](../../../images/dataset_post/structure_texture_near.png) | ![sphere2](../../../images/dataset_post/sphere2.png)         |



| *hospital*: [img](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/hospital/img.zip)  [observation](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/hospital/observation.zip)  [initial factor graph](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/hospital/baseline.zip) | *japanesealley*: [img](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/japanesealley/img.zip)  [observation](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/japanesealley/observation.zip)  [initial factor graph](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/japanesealley/baseline.zip) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![hospital](../../../images/dataset_post/hospital.png)       | ![japanesealley](../../../images/dataset_post/japanesealley.png) |
| *carwelding*: [img](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/carwelding/img.zip)  [observation](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/carwelding/observation.zip)  [initial factor graph](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/carwelding/baseline.zip) | *office*: [img](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/office/img.zip)  [observation](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/office/observation.zip)  [initial factor graph](https://github.com/yanyan-li/Open-Structure/blob/main/dataset/office/baseline.zip) |
| ![carwelding](../../../images/dataset_post/carwelding.png)   | ![office](../../../images/dataset_post/office.png)           |

### 2.Baseline of Open-Structure

![baseline_arch](../../../images/dataset_img/baseline_arch.png)

### 3. BibTeX

```
@inproceedings{liopenstructure,
  author = {Li, Yanyan and Guo, Zhao and Yang, Ze and Sun Yanbiao and Liang, Zhao and Tombari, Federico},
  title = {Open-Structure: a Structural Benchmark Dataset for SLAM Algorithms},
  year = {2023},
  booktitle = {arXiv}
 }
```



