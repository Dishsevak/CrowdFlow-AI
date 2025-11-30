


CrowdFlow – AI-Powered Real-Time Crowd Density Monitoring System 👥📊

CrowdFlow is an AI-driven crowd monitoring system that detects, analyzes, and visualizes real-time crowd density using a live camera feed or uploaded video.
It helps users understand how crowded a place is by classifying the area into Low, Moderate, or High crowd levels — useful for events, public places, college festivals, malls, exhibitions, and smart-city projects.





🚀 Features
📸 Real-Time Crowd Detection
Uses computer vision to count people and estimate density.

🧠 AI Classification (Low / Medium / High)
Automatically categorizes crowd levels using a trained model.

🎛️ Interactive User Dashboard
Clean UI to display live status with colors & animations.

🌐 Map-Based or Section-Based Visualization
Users can select a zone/area to check crowd condition.

📎 Upload Video Option
If no webcam, upload a clip to analyze crowd.

⚡ Fast & Lightweight Frontend (React + Vite)
Smooth performance with modern design.




🛠️ Tech Stack
Component	Technology
Frontend	React.js, Vite, TailwindCSS
Backend (optional)	Flask / Node.js
AI Model	OpenCV, TensorFlow / YOLO
Tools	VS Code, GitHub




📂 Project Structure
CrowdFlow/
│── public/
│── src/
│   ├── components/
│   ├── pages/
│   ├── utils/
│   ├── assets/
│── index.html
│── package.json
│── vite.config.js
│── README.md



▶️ How to Run the Project
1. Install dependencies
npm install

2. Start development server
npm run dev


Project will start at:
👉 http://localhost:5173




🧪 How Crowd Detection Works

Video frame is captured

People detection model processes the frame

Head/Body bounding boxes are counted

Density = total individuals in frame

Category assigned:

0–5 → Low

6–15 → Medium

16+ → High



🎯 Use Cases

Event management & monitoring

Campus / college crowd control

Shopping malls

Stadiums & concerts

Smart city crowd analytics

Safety surveillance

Queue monitoring

Public-space management




🖼️ Screenshots

<img width="281" height="280" alt="Screenshot (626)" src="https://github.com/user-attachments/assets/2894556c-efbd-4c10-afe7-ea8036898781" />
<img width="281" height="280" alt="Screenshot (626)" src="https://github.com/user-attachments/assets/b9f88077-9dc3-4464-b041-09ab85204082" />
<img width="281" height="280" alt="Screenshot (627)" src="https://github.com/user-attachments/assets/33093068-dd34-42b8-98f2-22cbc02da160" />
<img width="281" height="280" alt="Screenshot (629)" src="https://github.com/user-attachments/assets/6ebea72a-eca2-4849-8b78-c5cb0c83697d" />




🏆 Project Motivation

CrowdFlow was developed to help create safer and smarter public environments by giving real-time visibility of crowd density.
The aim is to support:

safety monitoring

better decision making

efficient crowd management

👨‍💻 Developer
Dishant Sevak

B.Tech CSE (Cybersecurity)
AI • Cybersecurity • Ethical Hacking • Computer Vision Projects









