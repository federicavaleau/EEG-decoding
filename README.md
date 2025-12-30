# Decoding Visual Stimuli Responses from EEG Data Using Deep Learning Techniques


This repository contains code developed for my Bachelor’s thesis at Sapienza University on decoding EEG responses to visual stimuli using deep learning models.

The goal of the project is to classify EEG signals recorded from subjects observing images belonging to 40 different visual categories, treating the problem as a supervised classification task. Experiments include both 40-class classification and binary classification between visual stimuli of objects and animals.

---

## Project Overview

The notebook explores different strategies for representing and learning from EEG signals, comparing:

- **Temporal representations**, including wavelet-based transformations  
- **Regional feature extraction**, focusing on localized EEG channels  
- **Holistic representations** of EEG signals  

The deep learning architectures that are evaluated to extract discriminative neural features are:
- Convolutional Neural Networks (CNNs)
- Recurrent Neural Networks (LSTMs and Bidirectional LSTMs)
- Residual-style architectures

---

## Dataset

The dataset used in this project can be downloaded at the following link:  
https://tinyurl.com/eeg-visual-classification

Please cite the original dataset creators if you use this data:

- S. Palazzo, C. Spampinato, I. Kavasidis, D. Giordano, J. Schmidt, M. Shah,  
  *Decoding Brain Representations by Multimodal Learning of Neural Activity and Visual Features*,  
  IEEE Transactions on Pattern Analysis and Machine Intelligence, 2020.  
  doi: 10.1109/TPAMI.2020.2995909

- C. Spampinato, S. Palazzo, I. Kavasidis, D. Giordano, N. Souly, M. Shah,  
  *Deep Learning Human Mind for Automated Visual Classification*,  
  CVPR 2017.

