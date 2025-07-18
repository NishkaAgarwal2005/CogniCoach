# CogniCoach

AI Learning Companion
An intelligent tutoring system powered by Google's Gemini AI that provides personalized learning experiences in Mathematics, Physics, and Chemistry.

Features
Intelligent Tutoring: Get personalized help from AI tutors specialized in Math, Physics, and Chemistry
Multi-language Support: Learn in your preferred language with support for English, Spanish, French, German, Chinese, Hindi, Arabic, and Russian
Voice Responses: Listen to AI explanations with text-to-speech support
Image Understanding: Upload images of problems or diagrams for the AI to analyze
Practice Questions: Generate and solve practice questions with instant feedback
Progress Tracking: Monitor your learning progress with detailed analytics and visualizations
Achievement System: Earn badges as you progress in your learning journey
Personalized Recommendations: Get topic recommendations based on your performance
Usage
Registration/Login:

Create a new account with a unique student ID
Log in with your student ID
Select Subject and Topic:

Choose from Math, Physics, or Chemistry
Select a specific topic within the subject
Get topic recommendations based on your performance
Ask Questions:

Type your question in the chat
Upload images of problems or diagrams
Get detailed explanations with optional voice output
Practice:

Generate practice questions at your preferred difficulty level
Submit answers for evaluation
Get instant feedback and explanations
Track Progress:

View performance analytics
Track earned badges
Identify areas for improvement
Project Structure
app.py: Main Streamlit application
ai_service.py: AI tutoring service using Gemini
student_manager.py: Student data management
config.py: Application configuration
requirements.txt: Project dependencies
Dependencies
Python 3.8+
Streamlit
Google Generative AI
Pillow
pytesseract
langdetect
gTTS
pandas
matplotlib
seaborn
python-dotenv
