# Project Description
This project uses MediaPipe and OpenCV to perform hand tracking. It captures video from a camera, detects hands in the video frames, and tracks the positions of the hand landmarks.

## Setup Instructions
 * Clone the repository:  
```bash
git clone <repository-url>
cd handtracking
```
 * Create a virtual environment:
```bash
Create a virtual environment:  
python -m venv venv
source venv/bin/activate 
```
 * Install the required packages:
```bash
pip install -r requirements.txt
```
 * Run the script:
```bash
python app.py
```

## Project Structure
app.py: Main script to run the application.
src: Contains the handDetector class for hand tracking. utils/: Utility scripts.
requirements.txt: List of dependencies.
README.md: Project description, setup instructions, and usage details.
