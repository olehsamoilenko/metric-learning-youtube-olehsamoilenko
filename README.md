# Computer Vision Course Assignment: Metric Learning with YouTube Commons Dataset

## Overview

Welcome to the Metric Learning assignment for the Computer Vision course! In this assignment, you will be working on building a similarity search feature using videos from the YouTube Commons dataset. The goal is to create a system that can search for videos based on both images and text queries.

### Getting Started

1. **Download the YouTube Commons dataset:**
   - Download the dataset from the provided link: [YouTube Commons Dataset](https://huggingface.co/datasets/PleIAs/YouTube-Commons).

2. **Clone this repository to your local machine:**
     ```bash
     git clone https://github.com/mshamrai-teaching/metric-learning-youtube-*your-name*
     ```
3. **Navigate to the project directory:**
      ```bash
       cd metric-learning-youtube-*your-name*
      ```

### Guidelines

* Dataset:
  * Utilize the YouTube Commons dataset for this assignment.
  * Ensure that you preprocess the videos appropriately for your model.

* Model:
  * You are free to choose or design a model suitable for both video and text processing.
  * Transfer learning can be beneficial; consider using pre-trained models for feature extraction.
  * **You don't have to train your own model!**

* Similarity Search:
  * Implement a similarity search mechanism that can retrieve videos based on both image and text queries.
  * Explore techniques such as feature extraction, vectorization, and similarity metrics to achieve this.

* Tools and Libraries:
  *  Investigate the following libraries for content-based video retrieval using high-dimensional features: FAISS, Elasticsearch, ChromaDB.

### Hints

* Video Processing:
  * Consider using techniques like frame sampling, keyframe extraction, or video summarization to represent videos efficiently.
 
* Image Quering:
  * Consider using Unicom, DINOv2 etc. for feature extraction from images. 

* Text Quering:
  * Consider using CLIP for multimodal understanding and semantic similarity between images and text.

* Similarity Metrics:
  * Experiment with different similarity metrics such as cosine similarity, Euclidean distance, or Jaccard similarity for comparing video and text features.

### Submission

To submit your solution, commit your files to the `main` branch of the repository.

Ensure your final submission includes:
* Source code (main.py or similar) implementing the video and text search functionality.
* A brief report (report.md or similar) describing your model architecture, preprocessing techniques, integration of tools and libraries, and evaluation results.

### Evaluation

Your solution will be evaluated based on the accuracy and efficiency of the similarity search feature, as well as the clarity of your code and documentation.

Best of luck with your assignment! If you encounter any difficulties or have questions, don't hesitate to ask for assistance.
