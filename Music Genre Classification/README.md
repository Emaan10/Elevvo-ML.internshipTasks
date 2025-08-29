# Music Genre Classification (GTZAN Dataset)

This project classifies music into **10 genres** (e.g., rock, jazz, classical) using the **GTZAN Dataset**.  
It applies both **classical ML (Random Forest)** and **Deep Learning (CNNs)** on **MFCC features** extracted from audio.

---

## Features

-  **Dataset Download**: Automatically fetches the GTZAN dataset via **KaggleHub**  
-  **Feature Extraction**: Extracts **MFCCs (Mel-Frequency Cepstral Coefficients)** for audio representation  
-  **Baseline Model**: Random Forest Classifier on flattened MFCCs  
-  **Deep Learning Model**: CNN for improved performance on spectrogram-like MFCCs  
-  **Visualizations**:  
  - RandomForest Confusion Matrix  
  - CNN Training History (Accuracy curves)  
  - Example MFCC and Spectrogram plots  

---

## Dataset

- **Dataset:** GTZAN Genre Collection  
- **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification)  
- **Classes:** 10 music genres  
  - `blues, classical, country, disco, hiphop, jazz, metal, pop, reggae, rock`  
- **Format:** 30s `.wav` clips  

---



