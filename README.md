# Image Captioning: Teaching Computers to Describe Pictures

An end-to-end deep learning system that automatically generates 
natural language captions for images.

## Overview
This project tackles the multimodal challenge of combining 
computer vision and natural language processing to describe 
image content. It serves as a comparative study of model 
components across loss functions and optimization strategies.

## Architecture
- **Encoder**: VGG16 (pre-trained on ImageNet) via transfer 
  learning for visual feature extraction
- **Decoder**: LSTM-based RNN for sequential caption generation
- **Attention**: Semantic attention mechanism to focus on 
  relevant image regions

## Key Features
- Comparative analysis of 3 loss functions × 2 optimizers
- Evaluated on 2 benchmark datasets (Flickr8k / MS-COCO)
- Full preprocessing pipeline: tokenization, vocabulary 
  building, sequence padding
- BLEU score evaluation

## Tech Stack
Python · Keras/TensorFlow · NumPy · NLTK · Matplotlib

## Results
| Configuration | BLEU-1 | BLEU-4 |
|---|---|---|
| Best Model | XX | XX |
| Baseline | XX | XX |

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook Automatic_Image_Captioning.ipynb
```

## References
- Karpathy & Li, CVPR 2015
- Vinyals et al., 2015 (Show and Tell)
- Xu et al., 2015 (Show, Attend and Tell)
