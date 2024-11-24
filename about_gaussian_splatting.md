---
layout: page
title: Gaussian Splatting
permalink: /about_gaussian_splatting/
---

### GeoGaussian: Geometry-aware Gaussian Splatting for Scene Rendering
*During the Gaussian Splatting optimization process, the scene's geometry can gradually deteriorate if its structure is not deliberately preserved, especially in non-textured regions such as walls, ceilings, and furniture surfaces. This degradation significantly affects the rendering quality of novel views that deviate significantly from the viewpoints in the training data. 
To mitigate this issue, we propose a novel approach called GeoGaussian. Based on the smoothly connected areas observed from point clouds, this method introduces a novel pipeline to initialize thin Gaussians aligned with the surfaces, where the characteristic can be transferred to new generations through a carefully designed densification strategy. Finally, the pipeline ensures that the scene's geometry and texture are maintained through constrained optimization processes with explicit geometry constraints.*

<a href="../project/gs/geogaussian.html"> Website</a>


### SmileSplat: Generalizable Gaussian Splats for Unconstrained Sparse Images
*Sparse Multi-view Images can be Learned to predict explicit radiance fields via Generalizable Gaussian Splatting approaches, which 
can achieve wider application prospects in real-life when ground-truth camera parameters are not required as inputs.
In this paper, a novel generalizable Gaussian Splatting method, SmileSplat, is proposed to reconstruct pixel-aligned Gaussian surfels for diverse scenarios only requiring unconstrained sparse multi-view images.
First, Gaussian surfels are predicted based on the multi-head Gaussian regression decoder, which can are represented with less degree-of-freedom but have better multi-view consistency. Furthermore, the normal vectors of Gaussian surfel are enhanced based on high-quality of normal priors. 
Second, the Gaussians and camera parameters (both extrinsic and intrinsic) are optimized to obtain high-quality Gaussian radiance fields for novel view synthesis tasks based on the proposed Bundle-Adjusting Gaussian Splatting module.*

<a href="../project/gs/smilesplat.html"> Website</a>
