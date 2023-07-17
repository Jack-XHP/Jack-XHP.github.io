---
title: "Seeing Glass: Joint Point Cloud and Depth Completion for Transparent Objects"
collection: publications
permalink: /publication/2021-09-30-paper-title-number-4
excerpt: ''
date: 2021-09-30
venue: 'Conference on Robot Learning (CoRL) 2021'
paperurl: 'https://arxiv.org/abs/2110.00087'
citation: 'Xu, Haoping, Yi Ru Wang, Sagi Eppel, Alàn Aspuru-Guzik, Florian Shkurti, and Animesh Garg. “Seeing Glass: Joint Point Cloud and Depth Completion for Transparent Objects.” in proceedings of Conference on Robot Learning (CoRL) 2021'
---
The basis of many object manipulation algorithms is RGB-D input. Yet, commodity RGB-D sensors can only provide distorted depth maps for a wide range of transparent objects due light refraction and absorption. To tackle the perception challenges posed by transparent objects, we propose TranspareNet, a joint point cloud and depth completion method, with the ability to complete the depth of transparent objects in cluttered and complex scenes, even with partially filled fluid contents within the vessels. To address the shortcomings of existing transparent object data collection schemes in literature, we also propose an automated dataset creation workflow that consists of robot-controlled image collection and vision-based automatic annotation. Through this automated workflow, we created Toronto Transparent Objects Depth Dataset (TODD), which consists of nearly 15000 RGB-D images. Our experimental evaluation demonstrates that TranspareNet outperforms existing state-of-the-art depth completion methods on multiple datasets, including ClearGrasp, and that it also handles cluttered scenes when trained on TODD. 