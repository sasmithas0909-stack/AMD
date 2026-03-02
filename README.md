ReviewScope AI – Smart Product Review Analyzer

An AI-powered web application that analyzes product reviews from e-commerce links and provides a data-driven buy recommendation using sentiment analysis and fake review detection.

📌 Project Overview

ReviewScope AI helps users make smarter purchasing decisions by:

🔍 Analyzing product reviews

😊 Detecting positive / neutral / negative sentiment

⚠ Identifying fake review probability

📊 Generating a final buy score (0–100)

🟢 Providing clear recommendation (Buy / Think Twice / Not Recommended)

🎯 Key Features
✅ Sentiment Analysis

Classifies reviews into:

Positive

Neutral

Negative

🚨 Fake Review Detection

Detects suspicious reviews using linguistic patterns and probability scoring.

📈 Buy Score Engine

Final score calculated using:

Final Score = 
(Positive %) 
- (Negative %) 
- (Fake % × 0.5)

Normalized to 0–100 scale.

📊 Visual Analytics

Sentiment Breakdown Chart

Confidence Meter

Fake Review Percentage

Pros & Cons Summary

🕒 Session History

Stores last 5 analyzed products

Persistent using LocalStorage

🖥️ Tech Stack
Frontend

HTML5

Tailwind CSS

JavaScript (Vanilla JS)

Chart.js

Storage

LocalStorage (Session History)

🏗️ Project Structure
ReviewScope-AI/
│
├── index.html
├── README.md
└── assets/
🔄 Working Flow

User pastes Amazon/Flipkart product link

System analyzes review dataset

Sentiment percentages calculated

Fake review probability computed

Final buy score generated

Recommendation displayed

Data stored in session history

🟢 Recommendation Logic
Score Range	Recommendation
70 – 100	Highly Recommended
40 – 69	Average – Think Twice
0 – 39	Not Recommended
📸 UI Highlights

Modern glass UI design

Animated score meter

Responsive layout

Interactive charts

Real-time UI updates

🚀 Future Enhancements

🔗 Real-time web scraping integration

🤖 NLP model integration (BERT)

🧠 AI-generated review summary

📄 Export report as PDF

🌐 Backend integration with FastAPI

📱 Mobile responsive optimization

🎓 Academic / Hackathon Use

This project is ideal for:

AI & NLP projects

Hackathon submissions

Final year engineering projects

Portfolio enhancement
