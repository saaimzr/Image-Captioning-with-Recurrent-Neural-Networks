# Image Captioning with Recurrent Neural Networks (RNNs) and Long Short-Term Memory (LSTM)

This **Image Captioning Project** was completed as part of Assignment 5-1 from the *EECS 498-007 Deep Learning for Computer Vision* course offered by the University of Michigan. Although I am a University of Toronto Computer Engineering student, I independently chose to follow this course online through its publicly available content on YouTube to deepen my knowledge in deep learning applications for computer vision.

## Project Overview

This project explores image captioning by building a machine learning model capable of generating descriptive captions for images using RNN and LSTM architectures. By leveraging spatial attention mechanisms, the model effectively learns to focus on specific image regions, resulting in accurate, context-aware captions. This project showcases skills in neural network architecture, natural language processing, and computer vision.

## Key Features

- **Vanilla RNN and LSTM Models**: Implemented foundational RNN and LSTM architectures to generate image captions based on preprocessed image data, laying the groundwork for sequence modeling in image captioning.
  
- **Attention Mechanism**: Integrated spatial attention, allowing the model to prioritize significant areas within an image during caption generation. The model’s attention mechanism is inspired by cutting-edge research, including *Show, Attend, and Tell* for neural image captioning with visual attention.

- **COCO Captions Dataset**: Utilized the 2014 COCO Captions dataset, which provides images annotated with multiple captions, to effectively train and validate the model’s performance.

## Technology Stack

- **Deep Learning**: PyTorch
- **Machine Learning Models**: RNN, LSTM, Attention-based LSTM
- **Data Handling and Processing**: Python, Google Colab
- **Dataset**: COCO Captions 2014

## How It Works

1. **Data Preprocessing**: The COCO Captions dataset is preprocessed by resizing images and tokenizing captions, which are then represented as integer sequences for efficient training.

2. **Model Training**: The notebook guides the training process, starting with a basic RNN model, enhancing it with an LSTM layer for improved memory retention, and finally integrating spatial attention for refined caption generation.

3. **Attention-Based Caption Generation**: Using the attention mechanism, the model dynamically adjusts focus across image regions during caption generation, producing captions that accurately reflect key elements in each image.

4. **Model Evaluation**: After training, the model's performance is evaluated, with visualizations of its attention over various image regions to provide insights into its decision-making process.

This project demonstrates initiative in independent learning as well as technical expertise in RNNs, LSTMs, and advanced attention mechanisms, bridging computer vision and natural language processing in a real-world application.
