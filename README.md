# Monet Style Transfer with CycleGAN  
“Kaggle: I’m Something of a Painter Myself”

<img width="256" height="256" alt="image" src="https://github.com/user-attachments/assets/f96a535d-1aaf-43ca-80bf-48259e86f4a1" />


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1xKEd9hky3mNOHAsurxV9MhSYIlMu8Wqn?usp=sharing)

## Overview

This project uses a **CycleGAN** to translate real-world landscape photos into images in the style of **Claude Monet**.  
It was developed for Kaggle’s *“I’m Something of a Painter Myself”* competition, where the goal is to generate Monet-style images that can fool a classifier.

The notebook trains a CycleGAN from scratch, generates Monet-style images from input photos, and prepares a submission file for Kaggle.  
My best submission so far achieves a **public leaderboard score of ~69.54**.

## Project Features

- Data loading and preprocessing for Monet and photo images  
- CycleGAN architecture (generator + discriminator with residual blocks)  
- Adversarial, cycle-consistency, and identity losses  
- Training loop with checkpoints and sample visualizations  
- Inference pipeline to generate Monet-style images from test photos  
- Kaggle submission `.zip` file creation

## Getting Started

You can run everything in your browser using Google Colab:

1. Click the **“Open in Colab”** badge at the top of this README.  
2. Make sure you are logged into your Google account.  
3. In Colab, go to **Runtime → Change runtime type** and select **GPU**.  
4. Run the cells in order from top to bottom.


