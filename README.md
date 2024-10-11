# Image Captioning for Accessibility using ViT and GPT-2

This project merges NLP and computer vision to create a system aiding visually impaired individuals with multilingual, color-focused image captions. Employing ViT and GPT-2 models on over 330,000 images from MS COCO and Flickr30k, it significantly enhances image accessibility. The resultant paper is recognized in academic and professional spheres for its innovative, inclusive approach to AI.

## Overview
This project merges Natural Language Processing (NLP) and Computer Vision to assist visually impaired individuals by generating accessible, multilingual, color-based image captions. It uses over 330,000 images from the MS COCO and Flickr30k datasets, and the generated captions are designed to be descriptive with a specific focus on color information.

## Key Features
- **Multilingual Support**: Generate captions in multiple languages.
- **Color-Focused Descriptions**: Captions emphasize color details, making the system useful for individuals with color blindness.
- **State-of-the-art Models**: Leverages Vision Transformer (ViT) for image understanding and GPT-2 for text generation.
- **Extensive Dataset**: Trained on large-scale datasets (MS COCO and Flickr30k) with over 330,000 images.
- **Pre-trained Models**: Pre-trained ViT and GPT-2 models are used for faster and more accurate caption generation.

## Dataset
- **MS COCO**: Common Objects in Context, used for object detection, segmentation, and captioning.
- **Flickr30k**: A dataset with 30,000 images and accompanying captions.

The dataset provides a wide variety of images and captions that are essential for generating accessible and detailed descriptions.

## Model Architecture
- **Encoder**: Vision Transformer (ViT) extracts visual features from the images.
- **Decoder**: GPT-2 generates text captions based on the visual features.
- **Training**: The model is fine-tuned to generate color-focused captions based on MS COCO and Flickr30k datasets.

## Results
The model has shown promising results in generating color-focused captions, which significantly enhance the accessibility of images for visually impaired users. The captions not only describe the objects but also emphasize their color attributes.

