# EmojifyMe - Hand Gesture Detection Using OpenCV and MediaPipe

## Final Project: Fall 2024

**Section: NZA** <br>
**Group Number: 4** <br>
**Authors:** <br>
1. Arashdeep Singh (**Student ID:** 165871229, **GitHub Profile:** https://github.com/ArashTechDev) 
2. Ankit Thapar (**Student ID:** 125698217, **GitHub Profile:** https://github.com/jotkhehra)
3. Mustafa Toygar Baykal (**Student ID:** 112398227, **GitHub Profile:** https://github.com/mtogi)
4. Sayeda Insha Fatima Zaidi (**Student ID:** 128002227, **GitHub Profile:** https://github.com/fzinsha)

**Project Start Date:** 20th November 2024 <br>
**Project End Date:** 3rd December 2024 <br>

**Project Supervised By:** Professor Savita Seharawat <br>
**Course:** Computer Vision (CVI620) <br>
**Section:** NZA <br>
**Department:** School of Software Design and Data Science <br>
**Institute:** Seneca Polytechnic (Toronto, Canada) <br>

## Overview

**EmojifyMe** is a real-time hand gesture detection project that utilizes OpenCV and MediaPipe to recognize hand gestures via your webcam. The program identifies specific hand gestures and displays corresponding gesture names, creating an interactive and engaging user experience.

## Purpose

### 1. Creating a Fun, Interactive, Real-Time Communication Tool:
**EmojifyMe** transforms hand gestures into emojis in real time, making interactions lively, engaging, and fun. This feature enhances communication, especially in scenarios like video calls, where gestures can be instantly converted into emojis to add a new layer of expressiveness. It bridges traditional communication with a modern, visual approach, catering to a wide audience looking for creative and engaging ways to interact.

### 2. Enhancing Accessibility:
By converting gestures to emojis, this program offers a seamless communication bridge for individuals who rely on American Sign Language (ASL) or other gesture-based systems. It fosters inclusivity by enabling effective communication between ASL users and non-ASL users, breaking down communication barriers and making conversations more accessible.

### 3. Empowering Visually Impaired Users with Assistive Technology:
**EmojifyMe** can integrate with screen readers and other assistive tools to make gesture-based communication more accessible for visually impaired individuals. By translating gestures into emojis accompanied by descriptive audio cues, the program creates an intuitive and interactive way to communicate that complements existing assistive technologies. This feature is a step towards more inclusive and adaptive solutions for people with visual impairments.

### 4. Making Education Fun and Engaging:
The program serves as an educational tool, enhancing learning experiences for children and students. By associating gestures with emojis, it encourages playful interaction while teaching sign language, gestures, or emotional expression. This innovative approach can boost engagement, retention, and enjoyment in educational settings.

## Technologies Used

### Python: 
**Python** is the primary programming language used to build EmojifyMe. Its simplicity, ease of integration with libraries, and rich ecosystem make it perfect for developing computer vision and machine learning applications. The **math** library in Python is used to calculate the angles between the fingers, helping determine whether a finger is extended or curled. This mathematical analysis is key for accurate gesture recognition, such as distinguishing between an open hanD, a fist or detecting if a finger is extended.

### OpenCV:
**OpenCV** is used for image processing and real-time video frame capture. It helps track hand gestures by detecting key points on the hand and analyzing the movement in the video stream. OpenCV allows for effective manipulation of the image data to extract relevant features needed for gesture recognition.

### Google MediaPipe:
**MediaPipe** is used for real-time hand tracking and gesture recognition. It provides **pre-trained models** that enable Emojify Me to track key points of the hand in 3D space. These points are then used to determine hand gestures such as pointing, fist, or open hand, which are then converted into corresponding emojis.

## Demonstration
<img width="800" alt="1" src="https://github.com/user-attachments/assets/70c6937c-1912-46e4-b4e8-604eacf9a769">
<br/>
<br/>
<img width="800" alt="2" src="https://github.com/user-attachments/assets/13e55ef5-31fd-46c8-ac47-8d266c16c7a0">
<br/>
<br/>

<img width="800" alt="3" src="https://github.com/user-attachments/assets/4b80290d-8e8d-4205-82b2-15e02d33de76">

### Works for both hands

<img width="800" alt="Screenshot 2024-12-03 at 10 11 47 PM" src="https://github.com/user-attachments/assets/ea37b2dd-6535-4387-aeed-bbb5740a489a">
<img width="800" alt="Screenshot 2024-12-03 at 10 10 59 PM" src="https://github.com/user-attachments/assets/5e065c5e-a039-4ffa-8c7d-4a893695b828">



## Setup and Usage



