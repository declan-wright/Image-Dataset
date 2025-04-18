# Image Dataset README

## Dataset Description

This repository contains a dataset of AI-generated and real photographs used for research on differentiating between AI-generated and authentic images.

The dataset consists of 60 images:
- 30 AI-generated images (A1.jpg - A30.jpg)
- 30 real photographs (B1.jpg - B30.jpg)

All images have been scaled to a consistent resolution of 1024 × 768 pixels (approximately 0.8 megapixels) to control resolution as a potential confounding variable. This is also consistent with how most people interact with images online or through social media, where compression and lower resolution images are common.

## Image Categories

The dataset is divided into 6 visual categories, with 5 AI-generated and 5 real images in each category:

**Type** | **Number of AI images** | **Number of real images**
---------|------------------------|------------------------
Nature/Landscape | 5 | 5
Multi-person | 5 | 5
Single-person | 5 | 5
Celebrity/political figure | 5 | 5
Architectural/urban landscape | 5 | 5
Object | 5 | 5

A diverse range of image types are included in the study, preventing bias towards any one category, which could potentially skew the results. Differentiated image types also assess the ability to detect AI-generated images across different visual domains.

## Real Image Selection Criteria

For real images, only photographs with robust EXIF data and a publication date prior to 2021 (the year advanced image generators became mainstream) were selected. This reduces the probability of an AI-generated image being inadvertently included in the dataset of real photographs.
