---
title: "Conformer Search Using SE3-Transformers and Imitation Learning"
collection: publications
permalink: /publication/2022-11-21-paper-title-number-5
excerpt: ''
date: 2022-11-21
venue: 'NeurIPS 2022 Workshop AI4Mat'
paperurl: 'https://openreview.net/forum?id=b832-LQhwYP'
citation: 'Thiede, Luca, Santiago Miret, Krzysztof Sadowski, Haoping Xu, Mariano Phielipp, and Alan Aspuru-Guzik. “Conformer Search Using SE3-Transformers and Imitation Learning" in NeurIPS 2022 Workshop AI4Mat '
---
We introduce a novel approach to conformer search, the discovery of three-dimensional structures for two-dimensional molecular formulas. We focus on organic molecules using deep imitation learning and equivariant graph neural networks, with the prospect of using reinforcement learning algorithms for fine tuning. To that end, we present our interactive environment that describes the molecule in a ridig-rotor approximation and leverage a behavioral cloning torsion policy to autoregressively determine the dihedral angles of the molecule ultimately yielding a three-dimensional molecular structure. For our policy architecture, we leverage an SE(3) equivariant neural network, which enables us to exploit inherent molecular symmetries and to respect the topology of the angle distribution using a Mixture of Projected Normals action distribution. Our preliminary results for a policy trained on a behavioral cloning objective using the QM9 dataset for expert trajectories shows that the policy can accurately predict torsion angles for various molecules. We believe this to be a promising starting point for future work pertaining to performing conformer search using deep reinforcement learning.