# CorNet: Unsupervised Deep Homography Estimation on Agricultural Aerial Imagery

This repository contains the implementation of the CorNet project, which is based on the research published in the Springer paper titled "CorNet: Unsupervised Deep Homography Estimation on Agricultural Aerial Imagery".

Overview

CorNet is a deep learning-based approach to estimate homography between aerial imagery frames without the need for supervision. This method is highly effective in generalizing homography estimation across different terrains, including agricultural fields, forests, buildings, and water bodies. Compared to ASIFT, CorNet provides comparable accuracy while achieving up to ten times faster processing speeds.

Features
- Unsupervised Learning: CorNet does not require labeled data for training.
- High Generalization: Performs well across diverse environments.
- Efficiency: Achieves homography estimation at a fraction of the time required by traditional methods like ASIFT.

Installation
To clone and set up this project locally, follow these steps:
https://github.com/dek8v5/CorNet.git
cd CorNet
pip install -r requirements.txt

Usage
Training
To train CorNet on a custom dataset:

Inference
To perform homography estimation on new aerial images:

Results
Below is a comparison of CorNet with ASIFT:

Citation
If you find this repository useful in your research, please consider citing:
