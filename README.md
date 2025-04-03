# Sentiment Analysis Web Application

## 📌 Overview
Sentiment Analysis is the process of computationally identifying and categorizing opinions expressed in tweets to determine whether the sentiment is **positive (1), negative (0), or neutral (2)**. This project leverages the power of **MERN stack** and **Machine Learning (ML)** to build a robust sentiment analysis system with **incremental learning** capabilities, ensuring that the model remains updated over time.

## 🌟 Key Features
- **Real-time Sentiment Prediction:** Enter a tweet or text and receive an instant sentiment classification.
- **Incremental Learning:** The model updates dynamically with new user inputs, improving accuracy over time.
- **Secure & Scalable:** Built on **MERN Stack**, ensuring a secure and scalable application.
- **FastAPI-powered ML Backend:** Efficiently processes sentiment analysis requests with low latency.
- **MongoDB Integration:** Stores user inputs and model predictions for future learning.
- **Hosted on AWS:** Ensures high availability, speed, and scalability.
- **User Verification System:** Prevents spam and ensures authentic data contributions.

## 🚀 Technology Stack
### 🔹 Frontend:
- React.js (for dynamic UI and seamless user interaction)

### 🔹 Backend:
- Node.js with Express.js (for handling API requests securely)
- FastAPI (for efficient ML model inference)
- MongoDB (for storing user data and model updates)

### 🔹 Machine Learning:
- **Sentence Transformer + SGDClassifier** (for sentiment classification)
- **Incremental Learning** (for continuously improving model accuracy)
- **NLP Preprocessing** (removes noise and enhances model efficiency)

## 🔧 How It Works
1. **User submits a tweet/text.**
2. **Model processes the text** and predicts whether the sentiment is positive, negative, or neutral.
3. **Prediction is displayed** on the UI.
4. **User feedback is stored** and verified for authenticity.
5. **Verified data is used** for incremental learning, keeping the model up to date.

## 🛠 Deployment & Hosting
- **Backend & Frontend:** Hosted and deployed on **AWS Ubuntu** with FastAPI and for a smooth and responsive experience.
- **Database:** Managed using **MongoDB Atlas**, ensuring scalability and security.

## 📂 Project Structure

📦 Sentiment-Analyzer
 ┣ 📂 client (React Frontend)
 ┣ 📂 server (Express.js Backend)
 ┣ 📂 ml-model (FastAPI + ML)
 ┣ 📜 README.md (Project Documentation)


## 📌 Future Enhancements
- Expand to multi-lingual sentiment analysis.
- Implement deep learning models for enhanced accuracy.
- Integrate a recommendation system based on sentiment trends.

## 🎯 Conclusion
This project is a powerful blend of **MERN Stack**, **Machine Learning**, and **Cloud Deployment**, ensuring real-time, accurate, and continuously improving sentiment analysis. With **incremental learning and secure API integration**, this tool provides an **authentic, fast, and scalable** sentiment prediction system.

🚀 **Let's analyze sentiments and make data-driven decisions!** 🎯
