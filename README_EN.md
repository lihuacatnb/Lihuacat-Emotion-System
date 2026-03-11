# Lihuacat Emotion Assessment System

---

📖 **This is the English version of the README.** Click here to view the [中文版本](./README.md) 

---

## 1.📖 Project Overview
The Lihuacat Emotion Assessment System is a full-stack mental health platform designed to provide convenient emotional monitoring services through multimodal data (text, facial expressions, and questionnaires).The system utilizes a decoupled architecture and integrates machine learning models along with Large Language Models (Gemma) to create a complete loop from data collection and sentiment analysis to visual feedback.The project consists of two main components:
- User Assessment System: A WeChat Mini-program for end-users providing facial recognition, text analysis, and psychological assessments.
- Admin Management Portal: A web-based dashboard for administrators to monitor data, manage AI model training, and handle user feedback.

## 2.🏗 Technical Architecture
The system adopts a polyglot micro-services approach to leverage the strengths of different tech stacks:
### (1) Core Technologies
- Machine Learning (Supervised Learning Algorithms)
- Natural Language Processing (NLP)
- Facial expression recognition

### (2) Assessment System (Frontend & Mobile)
- Backend: Python + Flask Framework.
- Frontend: Uni-App (deployed as a WeChat Mini-program).

### (3) Management System (Admin)
- Backend: Java + Spring Boot Framework.
- Frontend: jQuery + Bootstrap.

### (4) Database & AI
- Database: MySQL 8.0.

### (5) LLM Support
- Gemma LLM (Used for text translation).

## 3.✨ Key Features
### (1) Multimodal Assessment
Detects emotional states through browser history keywords, social media posts (WeChat Moments), real-time facial photos, and professional psychological scales.

### (2) Data Visualization
Automatically generates emotional heatmaps and stress probability distribution charts for intuitive user feedback.

### (3) AI Training Center
Allows users to participate in data labeling, facilitating supervised learning to continuously improve model accuracy.

### (4) Feedback loop
User feedback is directly integrated with the backend management system, enabling immediate responses.

## 4.📁 Project Structure
Core table structure：
- lifephilosophy / mental_health: Store knowledge base content。
- ailearn3: Store user-contributed training datasets。
- presstable: Record user feedback and related image resources。

## 5.🚀 Getting Started
- Python 3.9+
- JDK 11
- MySQL 8.0
- HBuilderX (for Uni-App compilation)

## 6.🎓 Developers
- Lihuacat AI
- Special thanks to Professor __Liu Shuyan__, Yanjing Institute of Technology

## 7.📦 Project Display
The following are screenshots showcasing some of the features：  
### （1）User Assessment System
<img src="others/7-1.png" width="350">
<br>
<img src="others/7-2.png" width="350">

### （2）Admin Management Portal
<img src="others/7-4.png" width="850">
<br>
<img src="others/7-5.png" width="850">
<br>
<img src="others/7-6.png" width="850">
<br>

---

<p align="center">⭐️ If you find this helpful, feel free to give it a Star to show your support! ⭐️</p>


