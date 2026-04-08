# TRINETRA - AI Traffic Violation Detection System

## Introduction
TRINETRA is an AI-powered traffic monitoring solution that uses artificial intelligence and computer vision to automatically detect traffic violations and improve overall road safety.

## Objectives
- Automate traffic monitoring
- Reduce human error
- Provide real-time violation detection
- Generate insights for authorities

## Features
- Real-time traffic monitoring dashboard
- Helmet detection for two-wheelers
- Seatbelt detection for drivers
- Red light violation detection
- Over-speed detection
- Wrong side driving detection
- Triple riding detection
- Mobile usage detection while driving
- Lane discipline monitoring
- Illegal parking detection
- Number plate detection and validation
- AI-based analytics and insights
- Evidence generation with timestamp
- Live alerts and notifications

## System Architecture
Video Input → YOLO Detection → Tracking → Rule-based Violation Detection → Backend API → Database → Frontend Dashboard

## Technologies Used
- **Frontend:** React.js, Tailwind CSS
- **Backend:** FastAPI (Python)
- **AI/ML:** YOLO, OpenCV
- **Database:** SQLite/PostgreSQL

## Project Structure
- `frontend/` → user interface
- `backend/` → API services
- `ai/` → detection logic

## Conclusion
TRINETRA is a scalable and practical solution for smart city traffic management, enabling safer roads through automated and intelligent violation detection.
