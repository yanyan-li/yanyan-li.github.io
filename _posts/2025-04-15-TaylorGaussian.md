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
Capturing the temporal evolution of Gaussian properties such as position, rotation, and scale is a challenging task due to the vast number of time-varying parameters and the limited photometric data available, which generally results in convergence issues, making it difficult to find an optimal solution. While feeding all inputs into an end-to-end neural network can effectively model complex temporal dynamics, this approach lacks explicit supervision and struggles to generate high-quality transformation fields. On the other hand, using time-conditioned polynomial functions to model Gaussian trajectories and orientations provides a more explicit and interpretable solution, but requires significant handcrafted effort and lacks generalizability across diverse scenes. To overcome these limitations, this paper introduces a novel approach based on a learnable infinite Taylor Formula to model the temporal evolution of Gaussians. This method offers both the flexibility of an implicit network-based approach and the interpretability of explicit polynomial functions, allowing for more robust and generalizable modeling of Gaussian dynamics across various dynamic scenes.Extensive experiments on dynamic novel view rendering task are conducted on public datasets, demonstrating that the proposed method achieves state-of-the-art performance in this domain. 
</div>