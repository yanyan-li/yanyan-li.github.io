---
layout: post
title: "ManhattanSLAM: Robust Planar Tracking and Mapping Leveraging Mixture of Manhattan Frames"
# categories: junk
author:
- Yunus R
- Li Y
- Tombari F
meta: "Springfield"
---

<div style="float:left;margin:0 10px 10px 0" class="col-md-4" markdown="1">
  <!-- ![Alt Text](../img/folder/blah.jpg) -->
  <img width="300px" class="center-block" src="../../../images/ManhattanSLAM.png">
  </div>
In this paper, a robust RGB-D SLAM system is proposed to utilize the structural information in indoor scenes, allowing for accurate tracking and efficient dense mapping on a CPU. Prior works have used the Manhattan World (MW) assumption to estimate low-drift camera pose, in turn limiting the applications of such systems. This paper, in contrast, proposes a novel approach delivering robust tracking in MW and non-MW environments. We check orthogonal relations between planes to directly detect Manhattan Frames, modeling the scene as a Mixture of Manhattan Frames. 
