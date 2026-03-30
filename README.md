# 🚗 Vehicle and Pedestrian Detection System

## 📌 Overview

This project is about a system that can detect vehicles and pedestrians in video streams. It uses a computer vision system to do this in time using OpenCV. The system can detect vehicles and pedestrians because it uses Haar Cascade classifiers to identify objects one frame at a time. It then draws boxes around these objects, which helps with tracking in a video that is playing continuously.

---

## 🎯 Features

- The system can detect vehicles using Haar Cascade.

- It can detect pedestrians in time.

- The system works with videos to detect objects.

- It is fast. Does not need a special graphics card.

- You can see the objects in the video with boxes around them as it happens.

---

## 🧠 Working Principle

The system works with the video input in these steps:

1. **Video Capture**

It reads frames from a video file using OpenCV. It does this all the time.

2. **Preprocessing**

Each frame is changed to grayscale, which makes the detection happen faster.

3. **Object Detection**

The system detects. Pedestrians using Haar Cascade classifiers.

It uses a file called `cars.xml` to detect vehicles.

It uses a file called `body.xml` to detect pedestrians.

4. **Bounding Box Drawing**

The system draws boxes around vehicles.

The system draws boxes around pedestrians.

5. **Display Output**

The system shows the video with the boxes, around the objects in time and it keeps doing this until you stop it.

---

## ⚙️ Project Structure

├── video.py # This is the script that does the detection

├── cars.xml # This is the Haar cascade file that detects vehicles

├── body.xml # This is the Haar cascade file that detects pedestrians

├── cars_2.mp4 # This is a sample video that you can use to test the system
