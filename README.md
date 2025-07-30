# Enhancing Victim Detection in Disaster Scenarios: A YOLOv8 and YOLOv9 Performance Study
---
ABSTRACT

Following natural and man-made catastrophes like earthquakes, floods, fires, and structural collapses, the immediate and accurate identification of victims is essential for effective rescue strategies. Manual search or primitive sensor-based methods are usually the traditional ways of detecting victims, but these can be inefficient, cumbersome, and even risky for the rescue team. In order to transcend these constraints, this project investigates the use of state of the art computer vision methods based on deep learning models namely YOLOv8 and YOLOv9 for real-time victim identification.

YOLO (You Only Look Once) is a modern object detection system recognized for its efficiency in combining speed and accuracy. This study involves training and evaluating both YOLOv8 and YOLOv9 on datasets designed to reflect real-life disaster conditions, such as complex backgrounds, obstructions, dim lighting, and partially visible objects. The models are assessed using key performance indicators like precision, recall, mean average precision (mAP), and inference time. Findings suggest that YOLOv9 achieves higher detection accuracy and handles difficult environments more effectively. Nonetheless, YOLOv8 demonstrates faster processing, making it better suited for deployment on resource-limited or edge devices.

The results of this research show how deep learning algorithms can become a critical component in improving victim detection, assisting rescue efforts with quicker decision-making and eliminating human effort and exposure. Incorporating such AI tools in disaster response systems has the potential to transform rescue outcomes and save more people
---
Architecture diagram
        The Victim Detection in Disaster system operates through a structured and sequential process to identify victims using deep learning models. Initially, users must register on the platform by providing necessary credentials. Once registered, they log into the system to access its core functionalities. The process continues as the user uploads images taken from disaster-affected areas. These images are then directed to a prediction module equipped with two object detection models: YOLOv8 and YOLOv9. YOLOv8 processes the image first, identifying victims and generating an output with bounding boxes. Concurrently, the image is also analyzed by YOLOv9, which performs a similar detection and produces its result. On the backend, the system uses a pre-collected and annotated dataset to train both models, ensuring their accuracy and efficiency before deployment. After training, the models are stored for future use in real-time detection. Once both models have analyzed the uploaded image, their outputs are generated and stored in a central database. This enables performance comparison and selection of the more accurate model. The stored detection results can also be used by rescue teams for prioritizing interventions and making informed decisions. The entire architecture ensures quick processing, reliable detection, and a scalable approach to managing disaster response effectively. The figure 2.2.1 below depicts architecture diagram.
---

## 📌 Features

- Real-time victim detection using YOLOv8 and YOLOv9
- Django-based web application with secure login and image upload
- Comparison of model performance (accuracy, inference time, etc.)
- Visualization of detections with bounding boxes and confidence scores
- Evaluation using metrics like precision, recall, mAP, F1-Score
- User-friendly interface for rescue teams

---

## 🧠 Technologies Used

- **Language:** Python 3.9+
- **Frameworks:** Django, PyTorch, OpenCV
- **Models:** YOLOv8, YOLOv9 (Ultralytics)
- **Frontend:** HTML/CSS (Django templates)
- **Database:** SQLite / MySQL (optional)

---
