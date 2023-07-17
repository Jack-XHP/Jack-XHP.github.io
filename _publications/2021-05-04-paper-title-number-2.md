---
title: "Computer vision for liquid samples in hospitals and medical labs using hierarchical image segmentation and relations prediction"
collection: publications
permalink: /publication/2021-05-04-paper-title-number-2
excerpt: ''
date: 2021-05-04
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2105.01456'
citation: 'Eppel, Sagi, Haoping Xu, and Alan Aspuru-Guzik. “Computer Vision for Liquid Samples in Hospitals and Medical Labs Using Hierarchical Image Segmentation and Relations Prediction.” arXiv, May 4, 2021.'
---
This work explores the use of computer vision for image segmentation and classification of medical fluid samples in transparent containers (for example, tubes, syringes, infusion bags). Handling fluids such as infusion fluids, blood, and urine samples is a significant part of the work carried out in medical labs and hospitals. The ability to accurately identify and segment the liquids and the vessels that contain them from images can help in automating such processes. Modern computer vision typically involves training deep neural nets on large datasets of annotated images. This work presents a new dataset containing 1,300 annotated images of medical samples involving vessels containing liquids and solid material. The images are annotated with the type of liquid (e.g., blood, urine), the phase of the material (e.g., liquid, solid, foam, suspension), the type of vessel (e.g., syringe, tube, cup, infusion bottle/bag), and the properties of the vessel (transparent, opaque). In addition, vessel parts such as corks, labels, spikes, and valves are annotated. Relations and hierarchies between vessels and materials are also annotated, such as which vessel contains which material or which vessels are linked or contain each other. Three neural networks are trained on the dataset: One network learns to detect vessels, a second net detects the materials and parts inside each vessel, and a third net identifies relationships and connectivity between vessels.