# Image Captioning with Vision Transformer and GPT-2

This project demonstrates how to generate descriptive captions for images using a pre-trained **VisionEncoderDecoderModel**. It combines **Vision Transformer (ViT)** for feature extraction and **GPT-2** for text generation, enabling automatic captioning for input images.

## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)

## Features:
- **Image Preprocessing**: Converts input images to RGB and processes them using the Vision Transformer (ViT) feature extractor.
- **Caption Generation**: Leverages GPT-2 to generate accurate captions from the extracted image features.
- **Customizable Parameters**: Easily adjust the caption generation parameters such as `max_length` (maximum caption length) and `num_beams` (for beam search optimization).

## Requirements:
- Python 3.x
- `transformers` library
- `torch` library
- `Pillow` (PIL) library

## Installation:
 - Clone the repository:
      git clone https://github.com/your-username/vit-gpt2-image-captioning.git
      cd vit-gpt2-image-captioning
 - Install the required dependencies:
      pip install -r requirements.txt  

## Features:
- **Image Preprocessing**: Converts input images to RGB and processes them using the Vision Transformer (ViT) feature extractor.
- **Caption Generation**: Leverages GPT-2 to generate accurate captions from the extracted image features.
- **Customizable Parameters**: Easily adjust the caption generation parameters such as `max_length` (maximum caption length) and `num_beams` (for beam search optimization).

## Usage:
- You can use this script to generate captions for one or more images. The predict_step function processes the input images and generates captions.


