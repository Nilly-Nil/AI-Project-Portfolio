# Personal Assistant — Commercial Prototype

## Overview
A production-grade multimodal AI personal assistant built for a commercial client and delivered as a functional prototype intended for retail deployment.

The system enables real-time voice interaction with a persistent avatar by integrating live speech recognition, conversational reasoning, and synchronized audiovisual response into a single coordinated pipeline.

## Problem Addressed
Most consumer AI assistants fail under real-world constraints due to fragmented handling of:
- Audio latency
- Conversational state
- Avatar playback
- User gesture gating
- Cross-platform device behavior

This project was designed to solve those problems holistically.

## Key Contributions
- End-to-end system architecture and orchestration
- Real-time microphone capture and streaming STT pipeline
- Conversational state management and scene control
- Avatar playback synchronization (speech, pauses, gestures)
- Client-side interaction handling and audio unlock logic
- Windows executable packaging and deployment
- Diagnostic logging and cross-platform audio debugging

## Architecture Summary
- Local Windows client application
- Streaming microphone capture
- WebSocket-based speech-to-text
- Backend conversation and state engine
- WebRTC avatar rendering and playback
- Event-driven coordination between audio, avatar, and conversation layers

(Architecture diagram and full brief available upon request.)

## Technologies
- Python (asyncio, WebSockets)
- Deepgram (streaming STT)
- D-ID (avatar streaming)
- ElevenLabs (TTS)
- WebRTC
- Low-level audio handling (sounddevice)
- Windows packaging and deployment

## Status
Completed prototype delivered to client.  
Currently undergoing final testing prior to retail release.

## Access
Source code and demonstrations available upon request.