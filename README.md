# CNN-Audio-Recognition
This project is a Python-based deep learning system for recognizing and interpreting audio using a Convolutional Neural Network (CNN).   The model converts raw audio signals into spectrograms and classifies them into textual or categorical outputs.

## ⚙️ Project Workflow

### 1. Dataset Preparation
- Load audio files from the `dataset/` directory.  
- Split the data into:
  - **Training set:** 70%  
  - **Validation set:** 15%  
  - **Test set:** 15%

### 2. Preprocessing
- Apply preprocessing to make the data suitable for CNN input:
  1. **Squeeze** the audio array to remove extra dimensions.  
  2. **Convert** each audio file into a **spectrogram** representation.

### 3. Model Architecture
A **Convolutional Neural Network (CNN)** is implemented using **TensorFlow**, consisting of:
- **Input Layer** — receives spectrogram features.  
- **Hidden Layers** — several convolutional and pooling layers to extract features.  
- **Output Layer** — fully connected layer for final classification.

### 4. Model Training
- Train the CNN model using the training and validation sets.  
- Track **accuracy** and **loss** metrics during training.

### 5. Prediction and Evaluation
- Test the model using the unseen test dataset.  
- Display predicted results 
- Evaluate the model’s performance using **accuracy** and **validation metrics**.

---

## 🧩 Technologies Used

| Category | Tools |
|-----------|--------|
| Language | Python |
| Libraries | TensorFlow / Keras |
| Numerical Computing | NumPy |
| Visualization | Matplotlib |

---

## 📊 Expected Outputs
 
- Training and validation accuracy curves  
- Prediction outputs with confidence scores  
- Overall evaluation metrics  

---

## 🚀 Future Improvements

- Implement real-time audio classification  
- Add support for emotion or speaker recognition  
- Optimize preprocessing pipeline for larger datasets  
- Deploy as a web or mobile application  

