# Speech Emotion Recognition (SER) Project

## Overview
This project focuses on **Speech Emotion Recognition (SER)** by leveraging machine learning and deep learning techniques. It is structured to preprocess audio data, extract relevant features, and analyze performance using various algorithms. The goal is to accurately classify emotions based on speech signals.

---

## Data Preprocessing
### Key Steps:
1. **Audio Processing**:
   - Preprocessing audio files forms the foundation of this project, contributing to 70% of the work.
2. **Feature Extraction**:
   - Extracts meaningful features such as:
     - **MFCC**: Captures timbral texture.
     - **Chroma**: Represents pitch content.
     - **MEL Spectrogram**: Encodes frequency content.
     - **Contrast**: Highlights spectral peaks and valleys.
     - **Tonnetz**: Captures tonal features.

### Workflow:
- Audio files are traversed, and features are extracted.
- Input-output mappings are prepared for machine learning models.
- The dataset is split into **training (80%)** and **testing (20%)**.

---

## Model Training and Analysis
### 1. Traditional Machine Learning Models
- Tested algorithms include **Decision Trees**, **SVM**, and **Random Forest**.
- Observations: These models struggled to achieve satisfactory performance, motivating a shift to deep learning approaches.

### 2. Deep Learning Models
- **Multi-Layer Perceptron (MLP)**:
  - Initially implemented but prone to **overfitting**, especially with limited data.
- **Convolutional Neural Networks (CNN)**:
  - Proved to be a **game-changer** with superior performance.
  - Several architectures were analyzed to optimize results.
  - Models were trained for **500 epochs** with identical configurations to evaluate consistency.

---

## Visualization
- Visual representations of audio signals and features help in better understanding the data.
- Spectrograms and waveforms are utilized for exploratory data analysis.

---

## Key Insights
- Deep learning models, particularly **CNNs**, outperform traditional machine learning methods in most cases.
- **Overfitting** is a common challenge due to the data-hungry nature of deep learning models.
- CNN architectures demonstrate varying levels of performance despite identical configurations, emphasizing the importance of careful model design and hyperparameter tuning.

---

## Conclusion
This project highlights the effectiveness of **deep learning techniques**, especially **CNNs**, in Speech Emotion Recognition. The preprocessing of audio data and extraction of meaningful features are critical to achieving high accuracy. The results underline the need for extensive data and careful architecture design to mitigate overfitting and improve generalization.

