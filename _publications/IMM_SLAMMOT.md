---
title: "IMM-SLAMMOT : Tightly-Coupled SLAM and IMM-based Multi-Object Tracking"
collection: publications
permalink: /publication/IMM_SLAMMOT
excerpt: ' '
date: 2023-12-22
venue: 'IEEE Transactions on Intelligent Vehicles'
paperurl: 'https://ieeexplore.ieee.org/document/10372112'
citation: 
---

# Abstract

In the context of autonomous driving systems, SLAM and dynamic object tracking represent pivotal challenges. Autonomous driving scenarios frequently demand the simultaneous acquisition of ego-pose and comprehensive motion information from the surrounding environment to enhance decision-making and scene comprehension.Given the inherent interdependence between these two challenges, a viable approach is to integrate SLAM and object tracking into an interconnected system referred to as SLAMMOT. However, many conventional SLAMMOT solutions rely on a single motion model for object tracking, which may inadequately capture complicated dynamics of real-world motions. In practice, object motion patterns can change from time to time, not conforming neatly to a single model. To handle existing challenges, this paper proposes the IMM-SLAMMOT, a tightly-coupled LiDAR-based SLAMMOT system that utilizes instance semantic segmentation and IMM modelling for dynamic object tracking. Ego-pose and dynamic object states are jointly optimized in an innovative graph optimization framework intimately integrated with the IMM algorithm. Comparative analysis against our baseline, which employs a single motion model for object tracking, demonstrates that the IMM-SLAMMOT outperforms at motion-pattern-transition moments and consistently achieves competitive results in SLAM and multi-object tracking tasks throughout the entire trajectory.



[Download paper here](https://simon-ying.github.io/files/IMM-SLAMMOT__Tightly-Coupled_SLAM_and_IMM-based_Multi-Object_Tracking.pdf)



# BibTex

```
@article{ying2023imm,
 title		={IMM-SLAMMOT: Tightly-Coupled SLAM and IMM-based Multi-Object Tracking},
 author		={Ying, Zhuoye and Li, Hao},
 journal	={IEEE Transactions on Intelligent Vehicles},
 year		={2023},
 publisher	={IEEE}
}
```

