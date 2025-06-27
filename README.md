# 📰 News Sentiment Analysis with Firebase and PySpark

This project collects news articles from NewsAPI, detects their language, and prepares them for sentiment analysis using PySpark. Results are stored in Firebase Firestore, simulating a cloud-connected data pipeline.

---

## 🎯 Project Objectives

- Fetch news articles using the NewsAPI
- Detect language of each article using `langdetect`
- Store article titles and sentiment scores in **Firebase Firestore**
- Load and prepare the dataset using **PySpark**

---

## 🛠️ Tools & Technologies

- `langdetect` – for language detection
- `firebase-admin` – to connect with Firebase
- `pyspark` – to process and display big data
- `requests` – to access NewsAPI
- `datetime`, `getpass` – for automation

