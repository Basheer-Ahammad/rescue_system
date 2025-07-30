# Enhancing Victim Detection in Disaster Scenarios: A YOLOv8 and YOLOv9 Performance Study

## ABSTRACT
Following natural and man-made catastrophes like earthquakes, floods, fires, and structural collapses, the immediate and accurate identification of victims is essential for effective rescue strategies. Manual search or primitive sensor-based methods are usually the traditional ways of detecting victims, but these can be inefficient, cumbersome, and even risky for the rescue team. In order to transcend these constraints, this project investigates the use of state of the art computer vision methods based on deep learning models namely YOLOv8 and YOLOv9 for real-time victim identification.

YOLO (You Only Look Once) is a modern object detection system recognized for its efficiency in combining speed and accuracy. This study involves training and evaluating both YOLOv8 and YOLOv9 on datasets designed to reflect real-life disaster conditions, such as complex backgrounds, obstructions, dim lighting, and partially visible objects. The models are assessed using key performance indicators like precision, recall, mean average precision (mAP), and inference time. Findings suggest that YOLOv9 achieves higher detection accuracy and handles difficult environments more effectively. Nonetheless, YOLOv8 demonstrates faster processing, making it better suited for deployment on resource-limited or edge devices.

The results of this research show how deep learning algorithms can become a critical component in improving victim detection, assisting rescue efforts with quicker decision-making and eliminating human effort and exposure. Incorporating such AI tools in disaster response systems has the potential to transform rescue outcomes and save more people
## INTRODUCTION
Disaster scenarios like earthquakes, floods, landslides, and collapsing buildings can cause extensive damage with a high degree of victims being trapped, wounded, or even incapable of raising an alarm. Rapid identification of victims is vital in order to perform successful rescue operations and save lives. Classical practices like manual search or simple sensors are usually time-consuming, unsafe, and narrow-spectrum.

This. "Enhancing Victim Detection in Disaster Scenarios: A YOLOv8 and YOLOv9 Performance Study" aims to address this challenge with state-of-the-art deep learning methods. It leverages the YOLO (You Only Look Once) object detection approach, namely its most recent implementations, YOLOv8 and YOLOv9, to identify people (victims) from images and videos taken by drones, cameras, or monitoring devices installed in disaster areas.

The objective of the project is to contrast and evaluate the detection performance of YOLOv8 and YOLOv9 in terms of accuracy, speed, and stability in adverse environments like:
•	Low light or smoky environments
•	Obstructed views due to obstacles
•	Partial visibility of humans (hands, face, or limbs)
•	Busy and noisy backgrounds

Through training these models on real-time disaster data, the system can be utilized by rescue teams to identify possible victims automatically and rapidly. The eventual output will assist in prioritizing areas for searching, minimize human workload, and accelerate response time — all of which contribute to saving more lives in emergencies.
## Features

- Real-time victim detection using YOLOv8 and YOLOv9
- Django-based web application with secure login and image upload
- Comparison of model performance (accuracy, inference time, etc.)
- Visualization of detections with bounding boxes and confidence scores
- Evaluation using metrics like precision, recall, mAP, F1-Score
- User-friendly interface for rescue teams

## Technologies Used

- Language   : Python 3.9+
- Frameworks : Django, PyTorch, OpenCV
- Models     : YOLOv8, YOLOv9 (Ultralytics)
- Frontend   : HTML/CSS (Django templates)
- Database   : SQLite / MySQL (optional)

## project input & output

