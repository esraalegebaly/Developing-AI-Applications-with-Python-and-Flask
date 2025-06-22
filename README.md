# Developing-AI-Applications-with-Python-and-Flask
Emotion Detection Web Application
Final Project Submission

Project Overview
This project involves building an emotion detection application using IBM Watson NLP and deploying it as a Flask web app. The system analyzes user-provided text and returns emotion scores (anger, disgust, fear, joy, sadness) along with the dominant emotion.

Key Features
✅ Emotion analysis using Watson NLP
✅ Flask-based web deployment
✅ Error handling (blank input, invalid requests)
✅ Unit testing & static code analysis (10/10 pylint score)
✅ Packaged as a Python module

Tasks Completed
Task	Description	Points
1	Cloned repository & verified structure	1
2	Built emotion detection function	2
3	Formatted JSON output	2
4	Packaged the application	2
5	Implemented & passed unit tests	2
6	Deployed via Flask	2
7	Added error handling (HTTP 400)	3
8	Static code analysis (10/10)	2
Total Points: 16

How to Run the Project
Prerequisites
Python 3.7+

Flask (pip install flask)

IBM Watson NLP Library

Steps
Clone the Repository

bash
git clone <repository_url>
cd emotion-detection-app
Install Dependencies

bash
pip install -r requirements.txt
Run the Flask App

bash
python server.py
Access the app at: http://localhost:5000

Test the API
Send a POST request (e.g., using curl or Postman):

bash
curl -X POST -H "Content-Type: application/json" -d '{"text":"I am happy today!"}' http://localhost:5000/emotion
Screenshots for Peer Review
📌 Task 1: Repository structure
📌 Task 2: Code + successful import
📌 Task 3: Formatted JSON output
📌 Task 4: Packaging (__init__.py, folder structure)
📌 Task 5: Unit tests (code + passing results)
📌 Task 6: Flask deployment (browser/terminal)
📌 Task 7: Error handling (blank input test)
📌 Task 8: Pylint 10/10 score

Grading Criteria Met
✔ All functions implemented
✔ Correct output format
✔ Proper error handling (HTTP 400)
✔ Unit tests pass
✔ Static code analysis perfect score

Submission Notes
All screenshots are attached as per the task list.

The application is fully functional.

Feedback is welcome!

