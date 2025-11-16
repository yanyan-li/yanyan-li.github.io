---
layout: post
title: "RiemanLine: Riemannian Manifold Representation of 3D Lines for Factor Graph Optimization"
# categories: junk
author:
- Yanyan Li 
- Ze Yang
- Keisuke Tateno
- Federico Tombari
- Liang Zhao
- Gim Hee Lee
meta: "Springfield"
---
<div style="float:left;margin:0 10px 10px 0" class="col-md-4" markdown="1">
  <!-- ![Alt Text](../img/folder/blah.jpg) -->
  <img width="300px" class="center-block" src="../../../images/ReimanLine.gif">
  </div>
<li> <b>Yanyan Li</b>, Ze Yang, Keisuke Tateno, Federico Tombari, Liang Zhao, Gim Hee Lee. <span style="color:#B31B1B;font-weight:bold;">@ AAAI 2026</span> </li>
<li>
<span class="link"><a target=_blank href="https://arxiv.org/pdf/2508.04335">[Paper]</a></span>
<span class="link"><a target=_blank href="https://github.com/yanyan-li/RiemanLine">[Code]</a></span>
</li>
<div style="clear: both;"></div>

<h3>Abstract:</h3>
<div>
Minimal parametrization of 3D lines plays a critical role in camera localization and structural mapping. Existing representations in robotics and computer vision predominantly handle independent lines, overlooking structural regularities such as sets of parallel lines that are pervasive in man-made environments. This paper introduces RiemanLine, a unified minimal representation for 3D lines formulated on Riemannian manifolds that jointly accommodates both individual lines and parallel-line groups. Our key idea is to decouple each line landmark into global and local components: a shared vanishing direction optimized on the unit sphere, and scaled normal vectors constrained on orthogonal subspaces, enabling compact encoding of structural regularities. Extensive experiments on ICL-NUIM, TartanAir, and synthetic benchmarks demonstrate that our method achieves significantly more accurate pose estimation and line reconstruction, while reducing parameter dimensionality and improving convergence stability.
</div>