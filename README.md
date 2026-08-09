# 🎓 EduMind AI

> An AI-powered personalized education platform designed to help students learn smarter, practice effectively, and track their progress.

## 🚀 Live Demo

🌐 **Try EduMind AI:**  
https://aieducation-63zjkipwabolnnwvge8emu.streamlit.app/

---

## 📖 Overview

**EduMind AI** is an AI-powered education platform that provides personalized learning tools in one place.

The platform connects:

- 🧠 Quiz Generator
- 🗂️ Flashcards
- 📝 Assignment Generator
- 📚 Chat with Lecture PDFs
- 📊 Student Progress Dashboard
- 🎯 Personalized Learning

The application stores learner activity in a local SQLite database. Quiz scores, flashcard reviews, PDF questions, and assignments dynamically update the student's dashboard and personalized learning recommendations.

---

## ✨ Features

### 🧠 AI Quiz Generator
Generate quizzes based on the selected learning content and evaluate student performance.

### 🗂️ Flashcards
Create and review flashcards to reinforce important concepts and track learning activity.

### 📝 Assignment Generator
Generate educational assignments to help students practice and improve their understanding.

### 📚 Chat with Lecture PDFs
Upload lecture PDFs and interact with their content through an AI-powered question-answering system.

### 📊 Student Progress Dashboard
Track quiz scores, completed activities, learning performance, and progress over time.

### 🎯 Personalized Learning
Analyze strong and weak topics and generate personalized study recommendations.

### 💾 Activity Tracking
Learner activity is stored locally using SQLite and used to update the dashboard and recommendations dynamically.


---

## ⚙️ Setup

### 1. Install dependencies

```bash
pip install -r requirements.txt
```
### 2.  Run the application
```bash
python -m streamlit run app.py
