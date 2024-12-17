Real-Time Vehicle Detection System Using YOLO for Unauthorized Vehicles
Lina Chen, Fall 2024, Personal Website Link

Introduction
Project Goals
[Comment_3]: <> (This project focuses on three major goals:

Accurate Detection: Identify unauthorized vehicles using diverse datasets of American license plates.
Real-Time Processing: Ensure low-latency processing of live camera feeds.
Scalability: Provide a solution that can scale seamlessly across different locations and environmental conditions.)

Figure 1. Real-time vehicle detection pipeline. Store image as an issue or in the local directory.
Development Workflow
[Comment_5]: <> (The project follows a structured development process:

Week 1: Initial Setup and Data Collection

Set up Google Colab with GPU and install YOLO dependencies.
Download and explore datasets:
Cars Video Object Tracking
Vehicle Detection Image Dataset
Vehicle Detection Sample and Output Videos
Week 2: Data Preparation and Initial Training

Annotate and clean the data if needed.
Train YOLOv5 on a small subset to validate the setup.
Week 3: Model Training and Optimization

Train the model using the full dataset and fine-tune hyperparameters.
Perform error analysis to improve performance.
Week 4: Testing and Integration

Test the model with unseen data and integrate it into a real-time video pipeline.
Develop a Flask-based web interface to display detection results.
Week 5: Final Adjustments and Documentation

Optimize for latency and accuracy.
Document the process and prepare a final report with feedback from Kaleem and Hari.)
Key Features
[Comment_6]: <> (The real-time vehicle detection system includes:

Real-Time Detection: Processes live video feeds with minimal delay.
User-Friendly Web Interface: Built using Flask to display results in real time.
Scalable Architecture: Can adapt to different locations and environmental conditions.
Adaptability: Supports model retraining to account for evolving vehicle types and conditions.)
Conclusion
References
[Comment_8]: <> (Developers, T. (2022). TensorFlow. Zenodo.
Faridoon, A., & Imran, M. (2021). Big Data Storage Tools Using NoSQL Databases. Computing & Informatics.
Lenarduzzi, V., et al. (2021). Technical Debt Prioritization. Journal of Systems and Software.
Kaggle Datasets:

Cars Video Object Tracking: https://www.kaggle.com/datasets/trainingdatapro/cars-video-object-tracking
Vehicle Detection Image Dataset: https://www.kaggle.com/datasets/pkdarabi/vehicle-detection-image-dataset
Vehicle Detection Sample and Output Videos: https://www.kaggle.com/datasets/vivek603/vehicle-detection-sample-and-output-videos)

