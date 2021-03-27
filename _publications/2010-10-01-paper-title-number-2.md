---
title: "Plane Segmentation Based on the Optimal-vector-field in LiDAR Point Clouds"
collection: publications
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: 'Description'
date: 2020-05-18
venue: 'IEEE Transactions on Pattern Analysis and Machine Intelligence'
paperurl: 'https://ieeexplore.ieee.org/document/9095372'
citation: 'Xu, S., R. Wang, H. Wang and R. Yang (2020). &quot;Plane Segmentation Based on the Optimal-vector-field in LiDAR Point Clouds.&quot; <i>IEEE Transactions on Pattern Analysis and Machine Intelligence</i>. doi: 10.1109/TPAMI.2020.2994935.'
---
One key challenge in the point cloud segmentation is the detection and split of overlapping regions between different planes. The existing methods depend on the similarity and the dissimilarity in neighbor regions without a global constraint, which brings the ‘over- ’ and ‘under- ‘ segmentation in the results. Hence, this paper presents a pipeline of the accurate plane segmentation for point clouds to address the shortcoming in the local optimization. There are two phases included in the proposed segmentation process. One is a local phase to calculate connectivity scores between different planes based on local variations of surface normals. In this phase, a new optimal-vector-field is formulated to detect the plane intersections. The optimal-vector-field is large in magnitude at plane intersections and vanishing at other regions. The other one is a global phase to smooth local segmentation cues to mimic leading eigenvector computation in the graph-cut. Evaluation of two datasets shows that the achieved precision and recall is 94.50% and 90.81% on the collected mobile LiDAR data and obtains an average accuracy of 75.4% on an open benchmark, which outperforms the state-of-the-art methods in terms of completeness and correctness.

[Download paper here](http://lostagex.github.io/files/TPAMI2020.pdf)


