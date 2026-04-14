# Vora Voice

Vora Voice is a browser-based voice assistant that uses real-time speech recognition and Google’s Gemini API to generate intelligent responses. It is a fully frontend application designed for fast, continuous voice interaction without requiring any backend server.

### Overview

Vora Voice listens to user speech through the Web Speech API, converts it into text, sends the text to the Gemini API, and displays a structured AI-generated response. The application runs entirely in the browser and is designed for simplicity, speed, and ease of use.

### Features
Real-time speech recognition using the Web Speech API
AI responses powered by Google Gemini API
Continuous listening with automatic restart
Visual state indicators for listening, thinking, and error modes
Automatic retry handling for API rate limits and server errors
Structured and readable AI responses
Microphone permission handling
Fully frontend-based with no backend dependency
### How It Works
The browser listens to the user’s voice using speech recognition
Speech is converted into text in real time
The text is sent to the Gemini API for processing
The AI returns a formatted response
The response is displayed in the interface
The system automatically resumes listening after completion
#### Requirements
Modern browser (Google Chrome recommended)
Microphone access enabled
Stable internet connection
HTTPS or localhost environment for speech recognition support
Browser Compatibility
Google Chrome: Fully supported
Microsoft Edge: Fully supported
Firefox: Limited support
Safari: Not recommended
### Limitations
Requires internet connection to function
Speech recognition depends on browser support
API key is exposed in frontend (not suitable for production)
Performance depends on Gemini API response time
Security Notice

This project uses a frontend API key setup for simplicity and demonstration purposes. For production use, API requests should be handled through a secure backend, and sensitive keys should never be exposed in client-side code.

## Project Structure

The project consists of a single frontend file along with optional assets for UI enhancements such as images or previews.

Future Improvements
Add conversation history
Add dark mode support
Improve mobile responsiveness
Add backend proxy for secure API handling
Add multilingual speech support
Add wake word activation
