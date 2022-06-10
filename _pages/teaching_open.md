---
layout: archive
title: "Open Student Projects"
permalink: /open_projects/
author_profile: true
---

{% include base_path %}

## How To Apply

Please read this section carefully. I might not answer you if you do not follow the instructions and I am very busy at the moment (or just reply with a link here).

In order to apply write an email to zorah.laehner@uni-siegen.de with at least the following information:
- a **short** introduction of yourself including your study program, semester and programming languages you have experience with
- your transcript of records (this is the list of your courses and grades you can get from Unisono)
- which project you are the most interested in (from the list below, or your own project but only 3D related topics)
- some kind of acknowledgment that you are aware that I only give out projects related to 3D data and will not ask for a pure image based project (except it is in the list below)

Optional but appreciated:
- your CV
- a description of experience you have with handling 3D data
- names of people in the computer vision chair you have worked with before
- any questions/constraints you have that you want to clear before doing the programming task

I will then send you a small programming task related to 3D geometry processing (no prior knowledge required) which you have a week to solve. Afterwards we have a meeting where we will discuss your solution, I will ask some questions about Bachelor level math or data structure topics to make sure you have the needed background knowledge, and I give you a more detailed overview over the project(s).

## Available Projects

Currently available spots: 1

(there are more topics here than available spots but I can only supervise a certain amount of students at the same time, please do not write emails if it says 0 spots available)

All projects related to deep learning need to be implemented in PyTorch.

### Fast Marching on a 3D Product Manifold

*Summary:* Replace the Dijkstra shortest path implementation in the paper below with fast marching.

*Suitable for:* Bachelor Thesis, Studienarbeit

*Most related paper:* [Efficient Globally Optimal 2D-to-3D Deformable Shape Matching, Lähner et al, 2016](https://zorah.github.io/publication/2016-cvpr-efficient-globally-optimal-2d-to-3d-deformable-shape-matching)

*Requirements:* C++, Matlab (brief is fine, the Matlab part does not need to be changed)



### Survey of Autoencoder Architectures

*Summary:* Survey, implement and compare existing autoencoder architectures for point clouds, voxel grids and triangle meshes.

*Suitable for:* Bachelor Thesis, Master Thesis, Studienarbeit

*Requirements:* Python, passed our Deep Learning lecture (exception for Bachelor students)


### Non-Rigid Puzzles

*Summary:* Merging and correspondence calculation between multiple non-rigidly deformed shapes of the same object instance (e.g. humans in the same pose, see example paper).

*Suitable for:* Master Thesis

*Most related paper:* [Spectral Unions of Partial Deformable 3D Shapes, Moschella et al, 2021](https://arxiv.org/abs/2104.00514)

*Requirements:* Python, passed any lecture related to machine learning offered in Siegen
