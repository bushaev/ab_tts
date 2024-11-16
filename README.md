# TTS Model Comparison Tool

A web application for comparing and evaluating different Text-to-Speech (TTS) models through A/B testing. Users can listen to audio samples generated by different models and provide their preferences. In the end, the application provides statistics on the models' performance.

This website was build fully by AI - Claude 3.5 Sonnet with my guidance.  (Most of this README too)

![TTS Model Comparison Tool Screenshot](public/screenshot.png)

![TTS Model Comparison Tool Stats Dialog](public/charts_screenshot.png)

## Features

- Interactive comparison of multiple TTS models
- Audio playback with custom controls
- User session management
- Statistics tracking for model preferences
- Responsive Material UI design
- Results visualization

## Tech Stack

### Frontend!
- Material UI (MUI) for components and styling
- Vite for build tooling
- Axios for API requests

### Backend
- Node.js with Express
- TypeScript
- File-based storage for user comparisons
- CORS support

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Audio files for comparison (not included in repository)

### Installation

1. Clone the repository
2. Install dependencies: `npm install`
3. Run the development server: `npm run dev:all` (Runs both frontend and backend)