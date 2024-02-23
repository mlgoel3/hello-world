
# *Google Soultion Challenge*
## SECURE VIEW AI

## *AI that senses anomalies and disasters in Cctv cameras and raise alarm leading too quick and swift action*


### Table of Contents
1. [Introduction](#introduction)
2. [Tech Stack](#tech-stack)
3. [Functioning of model](#functioning-of-model)
4. [Features](#features)
5. [Quick Start](#quick-start)
6. [Snippets](#snippets)
7. [Links](#links)
8. [More](#more)

## Introduction
- In response to the growing need for proactive security measures, our projectfocuses on developing an advanced  AI model for anomaly detection in CCTV videos
- Leveraging cutting-edge technologies such as CNNs and LSTMs, we aim to swiftly identify critical events like fighting, shoplifting, abuse, and more .We have used the UCf crime dataset to train the model Our mission is to revolutionize security operations by providing a robust tool for preemptive threat detection, ultimately fostering safer communities worldwide.
-  website ka kuch 

## Tech Stack
- **Language**: Python, JavaScript
- **Input Data**: UCF crime dataset (kaggle)
- **Model techniques**: LSTM, Recurrent convolutional nueral network

- 
- **Web Framework**: FastAPI,Next.js,TailwindCSS
- **DataBase**: MongoDB, Mongoose
- **Authentication**: NextAuth



## Functioning of model
**Data Information**
   - we have utilised the UCF crime database for anamoly detection 
   
**Data Pre-processing:**
  - As a crucial step in our workflow, preprocessing the video involves extracting individual frames and standardizing their dimensions for uniformity. By ensuring consistency in both height and length, we lay the foundation for accurate analysis and classification of video content.

  - Once standardized, the frames undergo classification labeling, where each frame is assigned a specific category based on its content. This classification step serves as a preliminary assessment, enabling us to organize and categorize the video frames according to the presence or absence of anomaly events.

  - By meticulously preprocessing the video data and labeling the frames, we establish a structured framework for subsequent analysis and model training. This systematic approach not only streamlines the data preparation process but also sets the stage for robust anomaly detection in CCTV videos
**Text Embeddings:**


**Model Structure:**
  - The LRCN model begins with a convolutional network, which extracts spatial features from individual frames of the video. These features are then fed into the recurrent neural network component, where the LSTM units capture temporal dependencies across successive frames. This integration enables our model to effectively analyze both spatial and temporal aspects of the video data, thereby enhancing its ability to detect complex anomaly events.

  - By leveraging the LRCN architecture, we create a sophisticated deep learning model that is capable of capturing intricate patterns and dynamics present in CCTV video streams. This approach not only enhances the accuracy of anomaly detection but also ensures robustness in handling real-world scenarios with varying complexities and durations.



## Features

###   Aisa kuch website ka (Modern Design with Glassmorphism Trend Style)
A modern and visually appealing design, incorporating the glassmorphism trend style for a sleek and contemporary appearance.

### Precise Anomaly Localization
The AI precisely pinpoints the exact frame within the video where an anomaly occurs, enabling quick identification and response.

### Community Engagement Platform:
 Our platform facilitates community involvement by providing a space for individuals to share insights, report suspicious activities, and collectively contribute to enhancing surveillance efforts.

### Future Integration with Society's CCTV Infrastructure
 We envision integrating our AI model with the existing CCTV infrastructure in society, thereby augmenting overall security measures and enhancing anomaly detection capabilities across various locations.

### Anomaly Categorization:
The AI system categorizes detected anomalies into distinct severity levels and contextual categories. This helps prioritize response actions and allocate resources effectively, ensuring that urgent threats are addressed promptly while minimizing disruptions for less critical deviations.

