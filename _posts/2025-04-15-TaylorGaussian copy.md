---
layout: post
title: "Learnable Infinite Taylor Gaussian for Dynamic View Rendering"
# categories: junk
author:
- Y Di 
- C Zhang
- C Wang
- R Zhang
- G Zhai
- Y Li
- B Fu
- X Ji 
- S Gao
meta: "Springfield"
---
<div style="float:left;margin:0 10px 10px 0" class="col-md-4" markdown="1">
  <!-- ![Alt Text](../img/folder/blah.jpg) -->
  <img width="300px" class="center-block" src="../../../images/cut_roasted_beef-ours.gif">
  </div>
<li> Bingbing Hu*, <b>Yanyan Li*</b>, Rui Xie, Bo Xu, Haoye Dong, Junfeng Yao, Gim Hee Lee. <span style="color:#B31B1B;font-weight:bold;">@ CVPR 2025</span> </li>
<li>
<span class="link"><a target=_blank href="https://arxiv.org/pdf/2412.04282">[Paper]</a></span>
<span class="link"><a target=_blank href="https://ellisonking.github.io/TaylorGaussian/">[Project Page]</a></span>
<span class="link"><a target=_blank href="https://github.com/EllisonKing/taylor_gaussian">[Code]</a></span>
</li>
<div style="clear: both;"></div>

<h3>Abstract:</h3>
<div>
In this paper, we present ShapeMaker, a unified selfsupervised learning framework for joint shape canonicalization, segmentation, retrieval and deformation. Given
a partially-observed object in an arbitrary pose, we first canonicalize the object by extracting point-wise affineinvariant features, disentangling inherent structure of the object with its pose and size. These learned features are then leveraged to predict semantically consistent part segmentation and corresponding part centers. Next, our lightweight retrieval module aggregates the features within each part as its retrieval token and compare all the tokens with source shapes from a pre-established database to identify the most geometrically similar shape. Finally, we deform the retrieved shape in the deformation module to tightly fit the input object by harnessing part center guided neural cage deformation. 
</div>