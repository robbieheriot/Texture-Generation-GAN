# Texture-Generation-GAN
# Master's Dissertation: Texture Generation with GAN using Google Colab, Python, and TensorFlow

## Overview

This repository contains the code for a Generative Adversarial Network (GAN) implemented in Python using TensorFlow on Google Colab. The GAN is designed to generate brand new image textures for 3D models. Users can upload their existing image textures, and the GAN will create new textures based on the input data.
A link to file can be found [here](https://colab.research.google.com/gist/robbieheriot/1c1a0a1589a6f2e96ecb2d9f52488242/gantextures.ipynb) 

## Getting Started

### Prerequisites

- Google Colab account
- Python
- TensorFlow
- 32 existing image textures (512x512) placed in the `content/textures` directory.

### Running the GAN

1. Open the provided Google Colab notebook.

2. Upload your existing image textures to the `content/textures` directory in the Colab environment.

3. Run the notebook. The training process may take a few hours.

4. Observe the results after around 25,000 epochs. The generated textures should be available for download or viewing.

5. Normal maps can then be created in Photoshop. 

### Example 1 Rock Texture

![Preview-01-01](https://github.com/robbieheriot/Texture-Generation-GAN/assets/118136425/9a961f2f-9a28-4295-bf94-ed2125d99a98)

### Example 2 Wood Texture

![Preview-02-01](https://github.com/robbieheriot/Texture-Generation-GAN/assets/118136425/4aba8d67-e23a-45c3-bb64-741d9593a699)


