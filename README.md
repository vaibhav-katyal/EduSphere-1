# Edu-Sphere

Edu-Sphere is a *virtual study platform* where students can create *public or private study groups, share resources, take quizzes, collaborate in real-time, and participate in **live coding sessions*** with a built-in compiler. The platform integrates *AI-powered study assistance* and video conferencing to enhance engagement.

## 🚀 Features

- *Public & Private Study Groups* – Join or create study groups based on subjects.
- *Real-Time Chat & Video Sessions* – Integrated with WebRTC & Socket.io.
- *Live Code Compiler* – Supports multiple languages using Judge0 API.
- *Resource Library* – Upload & share study materials (PDFs, links, notes, etc.).
- *AI Study Assistant* – Flask-based chatbot for answering study-related queries.
- *Secure Authentication* – User authentication via JWT.

## 🛠 Tech Stack

*Frontend:* React (Vite) | TailwindCSS  
*Backend:* Node.js (Express) | Flask (AI features)  
*Database:* MongoDB  
*Real-Time:* Socket.io & WebRTC  
*Compiler API:* Judge0 API  
*Authentication:* JWT  

# Project Setup Instructions

## Prerequisites
Make sure you have the following installed on your system:
- [Node.js](https://nodejs.org/)
- [Python](https://www.python.org/)

## Getting Started

### Step 1: Clone the Repository
Open your terminal and run the following command to clone the project:
```sh
git clone <repository-url>
```
Replace `<repository-url>` with the actual repository link.

### Step 2: Start the Server
Navigate to the project folder and start the server by running:
```sh
cd <project-folder>
node server.js
```
This will start the server. Since the database is not yet deployed, this step is necessary for accessing the Group Page.

## Group Page Access
- The Group Page (Video Call & Chat) will work only when `server.js` is running.
- Video Call & Chat features are already deployed on the backend, so no additional server setup is required for them.

## Using AI Summarizer in the Library
To use the AI Summarizer feature, follow these steps:
1. Open the terminal and navigate to the appropriate directory.
2. Run the following command:
   ```sh
   python app.py
   ```
3. This will connect the summarization service to the HTML interface, enabling AI summarization.

---
### Notes:
- Ensure that required dependencies for both Node.js and Python are installed before running the commands.
- If you encounter any issues, check for missing dependencies and install them using `npm install` for Node.js and `pip install -r requirements.txt` for Python.

Enjoy using the project! 🚀


