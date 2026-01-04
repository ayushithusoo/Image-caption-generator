# Image Caption Generator

This project focuses on generating meaningful captions for images using deep learning techniques by combining computer vision and natural language processing.

## Overview
The model takes an image as input and generates a descriptive caption that explains the visual content in natural language.

## Approach
- Extracted image features using a pre-trained CNN (VGG16)  
- Processed and tokenized text captions  
- Used an LSTM-based model to generate captions sequentially  
- Trained and evaluated the model on the Flickr8k dataset  

## Tech Stack
- Programming Language: Python  
- Libraries & Frameworks: TensorFlow, Keras, NumPy, Pandas, Matplotlib  
- Techniques: CNN, LSTM, Image Processing, NLP  

## Dataset
Flickr8k dataset containing images paired with human-written captions.

## Outcome
The model was able to generate context-aware captions that reasonably describe the contents of images.

## Future Improvements
- Use larger datasets such as Flickr30k or MS COCO  
- Improve caption quality with attention mechanisms  
- Explore transformer-based image captioning models  
