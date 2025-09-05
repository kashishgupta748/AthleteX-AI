# AthleteX-AI
Democratizing sports talent discovery in India with AI-powered video analysis, cheat detection, and performance benchmarking.

👥 Team: Code Warrior


Team Members: Kashish Gupta,Aniket Pandey, Amit Sharma, Alok Gupta, Hement, Shardha



🔍 Problem Overview
Identifying and assessing athletic talent in India is a major challenge due to:
❌ Lack of standardized testing facilities in rural & remote areas
🏟 Limited opportunities for aspiring athletes to showcase their talent
🕒 Manual evaluation being slow, biased, and resource-heavy
⚠ Difficulty in detecting fraudulent submissions during assessments



✅ Proposed Solution
AthleteX AI is a mobile-first platform that enables athletes to showcase their talent anytime, anywhere.
📱 Athletes record videos of standard fitness tests (vertical jump, shuttle run, sit-ups, endurance run, etc.)
🧠 AI/ML models verify movements, calculate performance metrics & detect cheating
🔄 Data securely uploaded to SAI servers for official evaluation
📊 Athletes receive instant performance benchmarking and digital progress tracking


🚀 Key Features
🎥 Video-based Assessment: Record & upload fitness tests directly via mobile
🧠 On-device AI Analysis: Jump height, sit-up count, shuttle run timing, endurance run distance
🛡 AI Cheat Detection: Detects tampered videos, incorrect posture, or camera manipulation
📊 Performance Benchmarking: Instant comparison with age/gender-specific standards
🕹 Gamified Experience: Leaderboards, badges & progress tracking to motivate athletes
📶 Offline Support: Video analysis works offline, syncs when internet available
📂 SAI Dashboard: Officials view verified performance reports & athlete profiles


🧩 Backend
🐍 Flask / FastAPI for AI inference endpoints
📂 Secure API for athlete video uploads & report storage
🧠 AI Models for movement detection, rep counting & cheat detection
☁ Deployment on AWS / GCP for scalability


💻 Frontend
📱 React Native / Flutter for cross-platform mobile app
🎨 TailwindCSS for responsive, clean UI
🌐 Web Dashboard (React.js) for SAI officials


🧠 Machine Learning Modules
📷 Pose Estimation (MediaPipe / OpenPose) → Detects athlete body movements
🧩 Action Recognition Models (CNN + LSTM) → Counts reps, measures form
🛡 Anomaly Detection → Cheat prevention (cuts, overlays, wrong reps)
⏱ Computer Vision Timing → Tracks shuttle runs & endurance time


💰 Future Aspects
🏟 National-Level Rollout: Integration with SAI’s official scouting program
🏫 School/College Integration: Early athlete identification at grassroots level
📱 Native iOS & Android apps with multilingual support
🤝 Partnerships with NGOs, academies, and federations
🧠 AI Skill Profiling: Predicts potential in different sports based on test results


📈 Scalability Roadmap
📱 MVP: App for video capture & AI-based performance evaluation
🌍 Expand: Multilingual support + offline-first architecture
🧪 Scale: Government & institutional onboarding
🏆 Future: AI-driven scouting + wearable integration


🌍 Expected Impact
🌱 Democratization: Rural athletes get equal access to talent assessment
🕒 Efficiency: Saves time & cost of physical scouting
🏅 Transparency: AI ensures unbiased, scientific evaluation
🚀 Mass Participation: Engage millions of aspiring athletes


🧪 Implementation Roadmap
📷 Build AI pipeline (pose estimation, rep counting, jump height detection)
🧠 Integrate cheat detection & anomaly analysis
💻 Develop athlete mobile app (video capture + results)
🌐 Build SAI dashboard for officials
☁ Deploy with secure APIs
🧰 How to Run the Project


📦 Backend Setup

pip install flask flask-cors opencv-python mediapipe ultralytics python-dotenv

python app.py

Backend runs on: http://localhost:5000/

💻 Frontend Setup
cd frontend
npm install
npm run dev

Frontend runs on: http://localhost:5173/

📬 Contact
For collaboration or queries:
📧 Kashish Gupta – kashishgupta892004@gmail.com
📧 Kashish Gupta – kashish.gupta@example.com
👉 This repo is under active development by Team [Your Team Name] for Smart India Hackathon 2025.
