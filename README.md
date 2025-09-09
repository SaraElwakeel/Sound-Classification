# Sound Detection with YAMNet 🎶🔊

## 📌 Overview
This project uses **YAMNet**, a deep learning model from TensorFlow, to classify audio signals into sound categories. YAMNet is trained on the **AudioSet** dataset and can detect hundreds of everyday sounds, such as speech, music, alarms, and environmental noises.

The notebook demonstrates:
- Loading and preprocessing audio data  
- Running inference with YAMNet  
- Visualizing model predictions  
- Extracting embeddings for downstream tasks  

---

## 🚀 Features
- **Audio classification** into 521 AudioSet classes  
- **Pretrained TensorFlow Lite model** for efficiency  
- **Embeddings extraction** for transfer learning or custom ML tasks  
- **Visualization** of prediction probabilities  

---

## 📂 Project Structure

---

## ⚙️ Requirements
Make sure you have the following installed:

- Python 3.8+
- TensorFlow >= 2.5
- NumPy
- Matplotlib
- Librosa (for audio processing)
- Jupyter Notebook (to run the notebook)

Install dependencies:
```bash
pip install tensorflow numpy matplotlib librosa
