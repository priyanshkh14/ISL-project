
# Indian Sign Language to Speech Translation (Multiple Languages)

Real-time Indian Sign Language recognition system for 80+ words, alphabets (A-Z), and digits (0-9) using temporal deep learning models.

##  Key Features
-  Processes video input (webcam/upload)
-  Detects 21 hand landmarks per frame using MediaPipe
-  Dual model architecture: **Bidirectional LSTM-GRU** and **Transformer**
-  93.4% accuracy on custom ISL dataset
-  Real-time prediction (<50ms/frame)

##  Tech Stack
- **Core**: Python 3.9, TensorFlow 2.10
- **Vision**: MediaPipe Holistic, OpenCV
- **Models**: Bidirectional LSTM-GRU (603K params), Transformer
- **UI**: Streamlit web interface

##  Dataset
- 80+ ISL words (60 videos/word)
- 24 frames/video → 1440 frames/word
- 1662 features/frame (hand + pose + face landmarks)

##  Installation
```bash
git clone https://github.com/priyanshkh14/ISL-project.git
cd ISL-project
pip install -r requirements.txt
```
---
[Report Issue](https://github.com/priyanshkh14/ISL-project/issues) | 
[Contribute](https://github.com/priyanshkh14/ISL-project/pulls) 
