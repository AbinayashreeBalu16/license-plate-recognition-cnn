# License Plate Recognition in Traffic System

A low-cost license plate recognition system built on a Raspberry Pi, designed to read number plates from noisy CCTV-style images where costly AI-based solutions are not practical.

## Problem
Existing license plate recognition systems often fail in poor visibility such as rain, fog, night-time and motion blur. High-end AI-based solutions need powerful hardware and are expensive for small institutions, offices and industries.

## Objective
- Improve license plate visibility in noisy images
- Enable simple automated reading under challenging conditions
- Keep the system affordable and easy to deploy

## How It Works
1. A Pi Camera captures the vehicle image and sends it to the Raspberry Pi.
2. The rectangular plate area is detected using contour and shape detection.
3. Only the number plate region is cropped from the full image.
4. The image is converted to grayscale, noise is removed and edges are enhanced (TensorFlow Lite).
5. The recognised number is stored in a database or used to trigger actions.

## Hardware
- Raspberry Pi 3B+
- Raspberry Pi Camera
- 32 GB memory card

## Software
- Python (Thonny IDE)
- Raspberry Pi OS
- TensorFlow Lite

## Documentation
See `project-presentation` in this repository for the full presentation: problem, literature survey, block diagram, working and output.

## Future Work
- Lightweight OCR for automated number reading
- Real-time processing of live video feeds
- SMS or email alerts for unauthorized vehicles

## Project Info
Final-year team project (3 members), B.E. Electronics and Communication Engineering, Dr. N.G.P. Institute of Technology, Coimbatore (2026).
