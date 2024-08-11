# CHATTER-BOT-ChatGpt-


🎉 Chatterbox is a cutting-edge chat application designed to provide an intelligent and seamless user experience by leveraging the power of the ChatGPT API. This application is crafted to cater to modern communication needs, offering both security and convenience. Below are the key features and integration highlights:

🌐 ChatGPT-Powered Conversations
Chatterbox uses the ChatGPT API to deliver real-time, intelligent responses that make conversations more engaging and insightful. Whether you're chatting for fun, seeking advice, or looking for answers, Chatterbox provides an interactive and dynamic experience.

🔒 Secure Login & Signup with Email OTP
Security is at the core of Chatterbox. The app implements a two-step verification process during login and signup:

User Registration & Login: Users can easily sign up or log in with their email.
Email OTP Integration: Upon signup or login, users receive a One-Time Password (OTP) via email, ensuring that only verified users can access the platform. This adds an extra layer of security by preventing unauthorized access.
🗃️ SQLite Database Integration
All user data, including credentials, chat history, and profile information, is securely stored in a SQLite database (db.sqlite3):

Lightweight & Efficient: SQLite is perfect for Chatterbox as it provides a reliable and fast data storage solution without requiring complex setup.
Data Integrity: The use of SQLite ensures that user data is stored with high integrity, allowing for seamless retrieval and updates as needed.
✨ Integration Highlights
Email OTP Authentication: Chatterbox integrates an email service to send OTPs directly to users, ensuring secure authentication.
SQLite Database Management: The app uses db.sqlite3 to handle all backend data operations, keeping everything streamlined and easy to manage.
ChatGPT API Integration: By embedding the ChatGPT API, Chatterbox brings AI-driven conversation capabilities to the forefront, making the app more than just a simple chat tool.
🚀 Why Chatterbox?
Chatterbox is not just another chat app. It combines AI-powered interactions with robust security measures, ensuring a safe and enjoyable user experience. The integration of email OTP for secure login and signup, along with the use of SQLite for efficient data management, makes it a versatile and powerful tool for modern communication.



Chatterbox Setup Guide
Follow these steps to set up Chatterbox on your local machine:

1. Install Python
Download and install Python from the official website:

Download Python
2. Create and Activate a Virtual Environment
For macOS/Linux:

Open your terminal and navigate to the project directory.
Create a virtual environment:
 terminal or cmd prompt
 
python3 -m venv env
Activate the virtual environment:
 terminal or cmd prompt
 
source env/bin/activate
For Windows:

Open Command Prompt or PowerShell and navigate to the project directory.
Create a virtual environment:
cmd
 
python -m venv env
Activate the virtual environment:
cmd
 
.\env\Scripts\activate
3. Install Required Packages
Ensure you are in the project directory and install the required packages by running:

 terminal or cmd prompt
 
pip install -r requirements.txt
4. Update Configuration Files
You need to update some configuration settings. Open the requirements.txt file and replace the placeholder lines with the following:

ChatGPT API Key: Replace the placeholder line with the ChatGPT API key. You can obtain it from OpenAI's API documentation. Find the specific line in requirements.txt and update it with the API key reference from todo-1.jpg.

Email ID for OTP: Replace the placeholder email address used for sending OTP messages with your actual email address. Refer to todo-2.jpg for the required format.

App Password: Use the app password generated from your Google Account. For instructions on how to get an app password, visit Google's support page. Update the placeholder line in requirements.txt with this app password, as seen in todo-2.jpg.

5. Start the Application
Ensure your virtual environment is activated.
Run the following command to start the application:
 terminal or cmd prompt
 
python manage.py runserver
You’re all set! Open your browser and navigate to http://127.0.0.1:8000 to start using Chatterbox.
