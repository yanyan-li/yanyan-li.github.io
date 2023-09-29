---
layout: post
title: "Structure-SLAM: Low-drift Monocular SLAM in Indoor Environments"
---
The low-drift monocular SLAM method, Structure-SLAM, is proposed targeting indoor scenarios, where monocular SLAM often fails due to the lack of textured surfaces. Our approach decouples rotation and translation estimation of the tracking process to reduce the long-term drift in indoor environments. In order to take full advantage of the available geometric information in the scene, surface normals are predicted by a convolutional neural network from each input RGB image in real-time.