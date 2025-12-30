# SENTINEL
A SMART CROWD MONITORING AND DANGER ALERT SYSTEM
SENTINEL is an AI-powered smart crowd monitoring and security alert system designed to enhance public safety in crowded environments such as railway stations, temples, campuses, bus terminals, and public events.
The system uses computer vision and deep learning to automatically detect people, analyze crowd density, identify abnormal activities such as fights or falls, and generate real-time alerts with voice notifications.

PROBLEM STATEMENT : Manual monitoring of crowded public places is inefficient and unreliable. The absence
                    of real-time crowd analysis can lead to overcrowding, panic, and accidents. An
                    automated system is needed to monitor people density and provide early warnings to
                    ensure public safety.
PROBLEM DESCRIPTION :Crowded public places such as temples, colleges, bus stands, and large
                     events are difficult to monitor manually. Security personnel cannot
                     continuously track the number of people or identify dangerous situations
                     in real time. This lack of effective monitoring often results in
                     overcrowding, panic, accidents, and stampedes. An automated system is
                     required to analyze video feeds, monitor people density, and provide
                     early alerts to prevent such incidents and improve public safety.

Proposed Solution : SENTINEL uses a pretrained YOLOv8 deep learning model to detect people in images and videos. The system analyzes spatial movement, posture, and interaction patterns to:
                    Count the number of people
                    Detect overcrowding
                    Identify violent activity (fight/clash)
                    Detect fall incidents
                    Trigger visual and voice-based alerts
The application is deployed using Gradio, allowing users to upload images or videos and view the analysis in real time.

Key Features : 
-->👥 Real-time Crowd Counting
-->🚨 Overcrowding Detection
-->⚠️ Fight / Violent Activity Detection
-->🆘 Fall Detection
-->🔊 Voice Alerts for Critical Events
-->📸 Image Monitoring
-->🎥 Video Monitoring
-->🌐 Live Web Deployment

Technologies Used : 
  Programming Language: Python
  Deep Learning Model: YOLOv8 (Ultralytics)
  Computer Vision: OpenCV
  Web Interface: Gradio
  Voice Alerts: gTTS (Google Text-to-Speech)
  Deployment Platform: Google Colab + Gradio Live Link

Dataset Information : 
  The system leverages pretrained YOLO models trained on large-scale real-world datasets such as:
  COCO Dataset (for person detection)
  Public crowd and activity datasets (indirectly via pretrained weights)
No synthetic data was used.

How to Run the Project :
  Open the project notebook in Google Colab
  Install required dependencies
  Run all cells
  A Gradio live link will be generated
  Upload an image or video to analyze crowd behavior.
  The final version of the ML model : https://2614ac19edbecb77fe.gradio.live/ } --> Direct link 
