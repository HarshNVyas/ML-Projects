# Deep Learning with Low Code Libraries

## 1) Fastai for:
  - vision object detection task: Animal Detector
  - vision segmentation task: Dashcam Video Image Segmentation
  - tabular task: Classifier for Iris Flower Species Data
  - recommendation task: Movie Recommendation System

    Sneak Peak into the results (segmentation task):
    ![image](https://github.com/Samarth-Sharma-G/Deep-Learning-CMPE-258/assets/107587243/64ea13eb-49aa-4d82-84c9-5368c71b533d)

Link to <a href='https://colab.research.google.com/drive/1zP6vLXyX6IyO2MQk85sdUTvu5gSfK_eF?usp=sharing'> FastAI Colab </a>

## 2) Hugging Face Transformers API:
  - Text classification: Sentiment Analysis
  - Named entity recognition: ner for a random sentence
  - Question answering: Open Domain QA
  - Text summarization: Summarization 
  - Translation: Chinese to English
  - Zero-shot classification: segmenting the input into user defined labels
  - Computer vision: Detecting a Cat
  - Audio: Sentiment analysis based on Audio
  - Table QA: QA for a custom built table

Link to <a href='https://colab.research.google.com/drive/1o0HoKGoUrzRBLog9KfsVrdqKg60nRGpf?usp=sharing'> HuggingFaceAPI Colab </a>

## 3) Keras-NLP for:
   
   Used bert_tiny_en_uncased through out for easier comparision of performance on our Sentiment dataset:
   
  - Inference with a pre-trained classifier: - bert_tiny_en_uncased_sst2 - 81.2% (really good without any training/finetuning)
  - Fine-tuning a pre-trained backbone - bert_tiny_en_uncased - 87% (after being finetuned for 6 epochs, some good progress)
  - Fine-tuning with user-controlled preprocessing - Used bert_large_en_uncased for preprocessing and then finetuned bert_tiny_en_uncased - 88.5% (Preprocessing matters a lot to take that last leap.)
  - Fine-tuning custom model - 73.5% (this is actually a decent performance given the custom model had 5% training parameters in comparision to bert_tiny_en_uncased, and about the same training time.)

Link to <a href='https://colab.research.google.com/drive/1B6BE8QzOVx2p8yk1hXT3Rdn3jojz7DgR?usp=sharing'> KerasNLP Colab </a>


## 4) User Keras-CV for various vision tasks

  - Inference with a pre-trained classifier: Detecting a Lion
  - Fine-tuning a pre-trained backbone: Fintuned efficientnetv2_b0_imagenet to classify cells into Malaria infected or not.
  - Training an image classifier from scratch: Trained a classifier for the Fashion Mnist Data
  - Draw inference from pre-trained and then train custom object detection model (using YOLO)

  Sneak Peak into the results:

  ![image](https://github.com/Samarth-Sharma-G/Deep-Learning-CMPE-258/assets/107587243/a3807b46-60e2-4611-822e-058417560e3f)

  Link to <a href='https://colab.research.google.com/drive/1-qvDDbKqptL1Uo-R60KjxuZFh9CmDNyW?usp=sharing'> Object Detection using YOLO Colab </a>
  
  Link to <a href='https://colab.research.google.com/drive/1w5H2opOU-1TzV6R9PnZU2n6yDQn67bHp?usp=sharing'> KerasCV Colab </a>
  
  




