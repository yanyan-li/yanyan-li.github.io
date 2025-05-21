---
layout: post
title: "Structure-SLAM: Low-drift Monocular SLAM in Indoor Environments"
author:
- Y Li
- N Brasch
- Y Wang
- N Navab
- F Tombari
---
<div style="float:left;margin:0 10px 10px 0" class="col-md-4" markdown="1">
  <!-- ![Alt Text](../img/folder/blah.jpg) -->
  <img width="300px" class="center-block" src="../../../images/structureslam.gif">
  </div>
 <li> <b>Yanyan Li</b>, Nikolas Brasch, Yida Wang, Nassir Navab, Federico Tombari. <span style="color:#B31B1B;font-weight:bold;">@ IEEE RAL/IROS 2020</span> </li>
<li>
<span class="link"><a target=_blank href="https://arxiv.org/pdf/2008.01963">[Paper]</a></span>
<span class="link"><a target=_blank href="https://github.com/yanyan-li/PlanarSLAM">[Code]</a></span>
</li>
<div style="clear: both;"></div>


<h3>Abstract:</h3>
<div>
  
The low-drift monocular SLAM method, Structure-SLAM, is proposed targeting indoor scenarios, where monocular SLAM often fails due to the lack of textured surfaces. Our approach decouples rotation and translation estimation of the tracking process to reduce the long-term drift in indoor environments. In order to take full advantage of the available geometric information in the scene, surface normals are predicted by a convolutional neural network from each input RGB image in real-time.