# LG-Net
This repository provides a partial open-source implementation of LG-Net, a local–global learning framework for large-scale indoor point cloud semantic segmentation.

LG-Net is designed to jointly model local geometric discrimination and global semantic relations, enabling robust segmentation in complex indoor environments with cluttered layouts and visually similar categories.
# Overview

Large-scale indoor point clouds present unique challenges due to irregular sampling, severe occlusions, and strong semantic ambiguity (e.g., walls vs. boards, pillars vs. corners).
LG-Net addresses these challenges through a task-driven local–global feature learning strategy, consisting of:
1） feature aggregation with geometry-aware attention
2）Global semantic relation modeling via lightweight contextual priors
3）Feature refinement to suppress global redundancy and enhance local discriminability
The proposed framework performs end-to-end point-wise prediction without voxelization or projection.
