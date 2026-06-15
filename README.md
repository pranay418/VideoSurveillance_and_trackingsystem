# Video Surveillance and Tracking System using Facial Recognition

## Overview

This project is an AI-powered Video Surveillance and Tracking System that uses Facial Recognition, Object Detection, and Real-Time Monitoring to enhance security and surveillance operations.

The system can connect to multiple CCTV cameras and automatically identify, track, and monitor individuals across different locations within a premises. It maintains records of detected persons and provides real-time alerts whenever a recognized or suspicious individual is detected.

## Features

### Facial Recognition
- Detects and recognizes registered individuals using facial recognition.
- Identifies people entering and exiting monitored areas.
- Maintains attendance and access records automatically.

### Real-Time Tracking
- Tracks a person's movement across connected CCTV cameras.
- Displays the latest detected location of an individual.
- Supports continuous monitoring within a surveillance network.

### Smart Detection System
- Detects human presence in camera feeds.
- Identifies unknown or unregistered individuals.
- Records detection timestamps and camera locations.

### Alert Generation
- Generates real-time alerts when:
  - A blacklisted person is detected.
  - An unknown individual enters a restricted area.
  - Suspicious activity is identified.
- Displays notifications to security personnel.

### Detection Logs and Records
- Maintains a searchable database of detections.
- Stores:
  - Person Name
  - Detection Time
  - Camera Location
  - Recognition Confidence
  - Alert Status

### Surveillance Dashboard
- Live CCTV monitoring interface.
- Detection history and tracking records.
- Alert management system.
- Person search functionality.

## Applications

- Corporate Offices
- Educational Institutions
- Airports and Railway Stations
- Shopping Malls
- Government Buildings
- Smart City Surveillance
- Industrial Security Systems

## Advanced Use Cases

When integrated with authorized law enforcement or security databases, the system can assist in:

- Identifying wanted individuals.
- Detecting unauthorized access attempts.
- Enhancing public safety monitoring.
- Supporting security investigations.

## Technology Stack

- Python
- OpenCV
- Face Recognition
- SQLite Database
- CCTV Camera Integration
- Tkinter/PyQt GUI
- Machine Learning & Computer Vision

## Project Structure

```text
├── images/
├── data.db
├── main.py
├── gui.py
├── Track.py
├── simple_facerec.py
├── data_handling.py
└── README.md

Workflow
CCTV Camera Feed
        ↓
Face Detection
        ↓
Face Recognition
        ↓
Person Identification
        ↓
Tracking & Location Update
        ↓
Alert Generation
        ↓
Database Logging
        ↓
Dashboard Display
Future Enhancements
Multi-camera tracking
Cloud database integration
Mobile application support
Email/SMS alert notifications
AI-based suspicious activity detection
Real-time analytics dashboard
Heatmap visualization of movement patterns
Disclaimer

This project is intended for educational, research, and authorized security applications only. Any deployment involving personal data or facial recognition must comply with applicable privacy, data protection, and surveillance laws and regulations.
