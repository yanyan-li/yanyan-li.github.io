---
layout: post
title: "GeoGaussian: Geometry-aware Gaussian Splatting for Scene Rendering"
author:
- Y. Li
- C. Lyu
- Y. Di
- G. Zhai
- G. Lee
- F. Tombari
---
<div style="float:left;margin:0 10px 10px 0" class="col-md-4" markdown="1">
  <!-- ![Alt Text](../img/folder/blah.jpg) -->
  <img width="300px" class="center-block" src="../../../images/o2-ours.gif">
</div>
<li> <b>Yanyan Li</b>, Chenyu Lyu, Yan Di, Guangyao Zhai, Gim Hee Lee, Federico Tombari. <span style="color:#B31B1B;font-weight:bold;">@ ECCV 2024</span> </li>
<li>
<span class="link"><a target=_blank href="https://arxiv.org/pdf/2403.11324">[Paper]</a></span>
<span class="link"><a target=_blank href="https://yanyan-li.github.io/project/gs/geogaussian.html">[Project Page]</a></span>
<span class="link"><a target=_blank href="https://github.com/yanyan-li/GeoGaussian">[Code]</a></span>
</li>
<div style="clear: both;"></div>

<h3>Abstract:</h3>
<div>
During the Gaussian Splatting optimization process, the scene's geometry can gradually deteriorate if its structure is not deliberately preserved, especially in non-textured regions such as walls, ceilings, and furniture surfaces. This degradation significantly affects the rendering quality of novel views that deviate significantly from the viewpoints in the training data.

To mitigate this issue, we propose a novel approach called GeoGaussian. Based on the smoothly connected areas observed from point clouds, this method introduces a novel pipeline to initialize thin Gaussians aligned with the surfaces, where the characteristic can be transferred to new generations through a carefully designed densification strategy. Finally, the pipeline ensures that the scene's geometry and texture are maintained through constrained optimization processes with explicit geometry constraints. Benefiting from the proposed architecture, the generative ability of 3D Gaussians is enhanced, especially in structured regions. Our proposed pipeline achieves state-of-the-art performance in novel view synthesis and geometric reconstruction, as evaluated qualitatively and quantitatively on public datasets. 
</div>
