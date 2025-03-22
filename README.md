# AI-Powered Criminal Detection System

## Overview

This AI-driven system enhances criminal detection by analyzing both CCTV footage and real-time video feeds. It integrates advanced GAN-based sketch-to-image conversion, face detection, and face recognition to identify suspects with high accuracy. The system enables law enforcement and security agencies to recognize individuals using AI-enhanced facial analysis, reducing manual effort in video surveillance.

## Features

1. CCTV Footage Analyzer – Detects and identifies faces from pre-recorded security footage.
2. Real-Time Monitoring System – Performs live face recognition for instant suspect identification.
3. Sketch-to-Image Feature – Converts rough sketches into realistic colorized images for enhanced facial matching.
4. Database Storage – Stores extracted face feature vectors, names, and locations for quick retrieval and matching.

## Tech Stack

### Frontend

1. React.js – UI development
2. Vite.js – Fast build tool for React
3. TypeScript – Ensures type safety

### Backend

1. FastAPI – High-performance API for handling image processing and recognition requests
2. Python – Core language for AI and backend processing
3. GAN Models – AI-based image generation for sketch-to-photo conversion
4. InsightFace (IR-SE50) – Face detection and feature extraction
5. FAISS – Fast similarity search for efficient face matching

## Installation & Setup

### Clone the Repository

```
git clone https://github.com/Mit-Gandhi/HackOverflow-AI_Mavericks.git  
cd AI-Criminal-Detection
```

### Backend Setup

#### Install required dependencies:

```
pip install -r backend/requirements.txt
```

#### Run the FastAPI server:
```
cd backend
uvicorn backend.main:app --reload
```

#### Frontend Setup:
```
cd frontend  
npm install  
npm run dev  
```
