# Multi-Person-Face-Recognition
## Overview
This project implements a robust multi-person face recognition system using Dlib, face_recognition, and other advanced technologies. The system is designed to detect and recognize faces in real-time, leveraging GPU acceleration and Docker for efficient deployment.
The project is to create a trained ML model that can perform multi-person identification in the live video feed on NVIDIA A100 DGX Server.

We have used popular DLib and face_recognition libraries as the basis of the project 
- https://github.com/ageitgey/face_recognition

## Creating Docker Image
- Clone the repository
- Change the directory to the cloned repository
- Run the following command to create the docker image
    1. On DGX Server
        - `docker build -t Multi-Person-Face-Recognition:latest .`
    2. On Local Machine
        - `docker build -t Multi-Person-Face-Recognition:latest -f Dockerfile.local .`

## Running the Docker Image

### Technologies Used
- Dlib
- face_recognition
- imutils
- numpy
- pandas
- scipy
- matplotlib
- seaborn
- Flask
- Gmail API
- CUDA
- Docker
- OpenCV
- PyTorch
- NVIDIA A100 DGX

## Key Features
- **Facial Detection and Recognition**: Implemented Dlib and face_recognition for precise facial detection and recognition.
- **Custom Database**: Designed a custom database for storing facial embeddings, ensuring efficient data management.
- **Optimization**: Utilized NVIDIA A100 DGX Server and CUDA for accelerated processing, enhancing system performance.
- **Real-time Recognition**: Integrated with live video feeds for real-time face recognition with high accuracy.
- **Pose Robustness**: Capable of recognizing faces in various poses, without requiring subjects to stand straight.

## Deployment
The system is deployed on NVIDIA A100 DGX Server for continuous high-performance computing with live video input. Docker is used for scalable and efficient deployment across different environments.

## Achievements
Developed a real-time multi-person face recognition system that achieves high accuracy across various conditions and poses.

## Attendance System
Implemented Gmail API for generating CSV file attendance reports, ensuring streamlined communication and efficient data management.

## Usage
- Connect your video feed to the system.
- Access the system's web interface for real-time face recognition and attendance tracking.


