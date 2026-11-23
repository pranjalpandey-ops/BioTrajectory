# BioTrajectory

BioTrajectory is an AI-powered healthcare intelligence and continuous biomarker tracking platform. It integrates vital health monitoring, trajectory forecasting, telemedicine consultations, emergency response QR profiles, and clinical administration into a unified full-stack application.

## Key Features

- **Biomarker Suite & Health Trajectory**: Continuous tracking of vitals, blood pressure, heart rate, blood glucose, and urinalysis with predictive health trajectories.
- **AI Health Assistant**: Natural language medical inquiry powered by Groq (`qwen/qwen3.8-27b`) with clinical safety boundaries and triage assistance.
- **Doctor Consultation Portal**: Real-time telemedicine with Google Meet synchronization, patient triage queues, and digital prescriptions.
- **Emergency QR System**: Dynamic tokenized emergency profiles for first responders and clinical staff.
- **Family Health Hub**: Coordinated health monitoring for dependents and family members.
- **Population Health & Admin**: Comprehensive disease library, doctor verification pipeline, and epidemiological analytics.

## Tech Stack

- **Frontend**: React 19, Vite, Tailwind CSS v4, Three.js, Recharts, Framer Motion, Daily.co / WebRTC.
- **Backend**: FastAPI, Pydantic v2, Groq LLM, PyPDF, HTTPX.
- **Database & Auth**: Firebase Authentication, Cloud Firestore, Cloud Storage.

## Quick Start

### 1. Install Dependencies
```bash
npm install
npm --prefix frontend install
cd backend && pip install -r requirements.txt
```

### 2. Run Applications
```bash
# Start frontend
npm run dev:frontend

# Start backend
npm run dev:backend
```
