# Neon-Trace-Mind
A futuristic AI-powered digital blackboard that uses real-time hand tracking and Gemini AI. Draw in the air using your webcam and interact with an intelligent sidebar for creative insights.


**Neon-Trace-Mind** is a futuristic, gesture-controlled digital blackboard. By combining computer vision with generative AI, it allows users to "paint in the air" and interact with an intelligent AI assistant in a sleek, neon-themed environment.

## 🚀 Features
- **Air Drawing:** Use your index finger to draw directly on your screen via webcam.
- **Real-time Tracking:** High-speed hand landmark detection with zero lag.
- **Glassmorphism UI:** A modern, translucent sidebar for AI interactions.
- **Gemini AI Integration:** An intelligent "Mind" that can analyze your drawings and answer questions.
- **Responsive Design:** Built with Tailwind CSS for a professional look on any screen.

## 🧠 Technology Stack
### Frontend
- **Framework:** [React.js](https://reactjs.org/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Bundler:** [Vite](https://vitejs.dev/)

### Backend & Database
- **Backend:** Serverless Architecture via [Supabase Edge Functions](https://supabase.com/edge-functions).
- **Database:** [PostgreSQL (Supabase)](https://supabase.com/) for session and data persistence.

### AI Models
- **Computer Vision:** [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html) — Tracks 21 hand landmarks in real-time.
- **LLM:** [Google Gemini 1.5 Flash](https://aistudio.google.com/) — Powers the intelligent chat and vision analysis.

## 🛠️ Installation & Setup
To run this project locally:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/nandanavijesh/neon-trace-mind.git](https://github.com/nandanavijesh/neon-trace-mind.git)
   cd neon-trace-mind


Install dependencies:
npm install

Set up environment variables:
Create a .env file in the root directory and add your Gemini API Key:
VITE_GEMINI_API_KEY=your_key_here

Run the application:
npm run dev

Demo
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/a72c2ec0-06ce-43c7-9cf0-2045b80aeeef" />
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/67b2c680-be63-4b7d-bb51-798c968d8e53" />


