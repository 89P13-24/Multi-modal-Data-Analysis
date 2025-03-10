# Multi-modal Data Analysis  

This repository contains multiple Jupyter notebooks designed for **scalable data collection** and **multi-modal analysis** across different data types.  

---

## 🚀 Scalable Data Collection  

### 📷 Image Dataset (`Image_Dataset.ipynb`)  
- This notebook contains an automated script to **download 50 images** for **20 different categories**.  
- These categories are specified within the notebook.  
- It also demonstrates a **use case of the generated data**, assessing the **feature representation capability of a model**.
- The dataset generated is named as **Images_20** and is stored in **Images_20.zip**.

### 📝 Text Dataset (`Text_Dataset.ipynb`)  
- Implements a **web crawler** to extract **relevant text** for different categories.  
- Explores how different models **capture semantics in text**.  
- Performs **clustering** to analyze **sector-wise similarities based on textual data**.
- The dataset generated is named as **Textual-20**.

### 🎙 Audio Dataset (`Audio_Dataset.ipynb`)  
- This notebook contains an **automated script to record and store audio streams** (duration: **30–90 seconds**).  
- Uses **Automated Speech Recognition (ASR)** to transcribe the audio files.  
- Showcases how **Large Language Models (LLMs)** interpret transcriptions.
- The dataset generated is named as **Global_Recordings-30**.
- Transcripts are stored in **Transcripts**.

### 🌦 Weather Dataset (`Weather_Dataset.ipynb`)  
- Uses the **Open-Meteo API** to fetch **historical weather data**.  
- Demonstrates various **time-series visualization techniques**.
- The dataset generated is named as **Weather_Dataset**.  

### 🇮🇳 Analyzing_India_with_Data.ipynb
- This notebook focuses on Air Quality analysis in India.
- The data is extracted from a government website and used for in-depth analysis
- The data is stored in **Air_Quality.csv**.
- Interactive plots are generated which can be viewed easily on any browser are stored in **Interactive-plots-for-air-quality**.
---

## 🎵 Analyzing Flags & Anthems  

### 🌍 Data Collection  
- Uses **BeautifulSoup** to scrape data from **[nationalanthems.info](https://nationalanthems.info/)**.
- The Images of selected flaga are stores in **Flag-images**.
- Corresponding national anthems in English translations are stored in **Anthem-Translations** whereas anthem-audio files are stored in **Anthems-mp3**

### 🏳️ Visual Analysis  
- Analyzes **flag aspect ratios** and **color distributions**.  
- Examines possible **correlations between flags** of different nations.  

### 🔤 Textual Analysis  
- Extracts **text embeddings** using **pretrained models**.  
- Performs **clustering** to find semantic relationships among anthems.  

### 🎼 Audio Analysis  
- Extracts **audio features** from anthems.  
- Investigates **correlations in musical structure** across different national anthems.

### 🔄 Multi-modal Correlation  
- **Matches audio (anthems) with their written versions** to explore **multi-modal correlations**.  
- Analysis is made on various aspects and the results are stored in **Anthem-and-Flag-Analysis**.  
---

## 📜 How to Run  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/89P13-24/Multi-modal-Data-Analysis.git
   cd Multi-modal-Data-Analysis
