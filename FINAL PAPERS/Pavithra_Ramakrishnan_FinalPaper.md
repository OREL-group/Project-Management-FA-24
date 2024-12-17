## Real-Time Vehicle Detection System Using YOLO for Unauthorized Vehicles  
Pavithra Ramakrishnan, Fall 2024, [link to personal website](https://www.linkedin.com/in/pavithramakrishnan/).  

---

### Introduction  

The rise in security concerns across critical infrastructures such as gated communities, airports, and government buildings necessitates advanced monitoring solutions. Existing systems often fail to provide efficient, real-time identification of unauthorized vehicles due to limitations in accuracy and processing speed. This project addresses these challenges by developing a state-of-the-art vehicle detection system that leverages the YOLO object detection framework. The system identifies unauthorized vehicles entering sensitive locations through live camera feeds, offering a scalable, adaptable, and user-friendly solution. By utilizing real-time processing and advanced machine learning algorithms, this project improves access control efficiency and overall security.

---

#### Vision Statement  

This project aims to deliver a real-time vehicle detection platform capable of accurately identifying unauthorized vehicles with minimal delay. The system integrates advanced machine learning techniques—YOLO—and efficient algorithms to process video feeds, providing actionable insights for security professionals. The solution prioritizes scalability and adaptability, ensuring seamless deployment across diverse environments and conditions. Ultimately, the project enhances security protocols while maintaining operational efficiency and reducing manual intervention.

| ![Workflow](https://github.com/user-attachments/assets/615d4a47-192c-4fbc-8df1-cc53be64828c) |  
| :--: |  
| **Figure 1.** Workflow Diagram. [Store image as an issue](https://github.com/OREL-group/Project-Management/issues/279) or in the local directory. |  

---

#### Project Goals  

This system must accurately detect and identify unauthorized vehicles by leveraging diverse datasets of American license plates to ensure high precision. Real-time processing capabilities are crucial to minimize latency in live video feeds, enabling timely responses to security threats. The system should be highly scalable to accommodate varying locations, hardware configurations, and environmental conditions. Finally, a user-friendly web interface for displaying real-time detection results is essential to enhance usability for security teams, providing them with a clear and accessible overview of the system's output.

---

#### Technology Stack  

The technology stack was selected based on its reliability, scalability, and suitability for real-time applications:  
- **YOLO**: Provides state-of-the-art object detection capabilities, making it ideal for identifying license plates quickly and accurately.  
- **OpenCV**: Facilitates efficient video processing and seamless integration with the YOLO model.  
- **Flask**: Enables the creation of a lightweight and user-friendly web interface for displaying real-time detection results.  
- **Google Colab**: Offers a powerful environment with GPU support, enabling rapid and efficient model training and experimentation.  

---

### Dataset Sources  

The project uses three diverse datasets to train and validate the model:  
1. **Cars Video Object Tracking**  
2. **Vehicle Detection Image Dataset**  
3. **Vehicle Detection Sample and Output Videos**  

These datasets provide varied perspectives, vehicle types, and environmental conditions to ensure the robustness of the model.

---

### Development Workflow  

The project development follows a structured plan:  

**1. Initial Setup and Data Collection**  
- Set up Google Colab with GPU.  
- Install YOLO and necessary dependencies.  
- Download and explore datasets, including initial visualization and structure analysis.  

**2. Data Preparation and Initial Training**  
- Annotate and clean data where needed using LabelImg.  
- Configure YOLO training scripts.  
- Train the model on a subset of data to verify setup and resolve initial issues.  

**3. Model Training and Optimization**  
- Train the model with the full dataset and fine-tune hyperparameters (e.g., learning rate, epochs).  
- Evaluate the model on validation data and perform error analysis.  
- Implement data augmentation techniques to improve performance.  

**4. Testing and Integration**  
- Test the model on unseen data and real-time camera feeds.  
- Integrate the model into a real-time detection pipeline using OpenCV.  
- Develop a basic Flask-based web interface to display results.  

**5. Final Adjustments and Documentation**  
- Optimize latency and ensure the accuracy of the detection pipeline.  
- Document processes, including data preprocessing, model training, and integration.  
- Conduct a final review.  

---

#### Key Features  

The system prioritizes real-time performance by processing live camera feeds with minimal delay and displaying results instantaneously. It is designed for scalability, enabling deployment across various environments, locations, and hardware configurations. A user-friendly Flask-based dashboard provides security teams with a clear visualization of vehicle detection results. Furthermore, the model's adaptability is ensured through the ability to retrain it with new data, allowing it to accommodate evolving conditions and variations in vehicles, maintaining high accuracy over time.

---

#### Addressing Technical Debt  

Technical debt in this project primarily arises from tool dependencies and scalability requirements. Frequent updates to tools like YOLO and OpenCV may introduce breaking changes, necessitating regular code reviews and a modular architecture to minimize disruption. The current web interface, built with Flask, may require replacement with a more scalable framework like FastAPI to handle increased traffic. Furthermore, transitioning to cloud solutions for real-time processing will incur data processing costs that require careful financial planning. Mitigating long-term technical debt involves maintaining clear documentation, automating workflows with CI/CD processes, and adopting a microservices architecture for improved flexibility and maintainability.

---

#### Target Audience  

- **Security Professionals**: Responsible for monitoring access to sensitive areas.  
- **Institutions with High-Security Needs**: Airports, government buildings, gated communities, and corporate facilities.  

---

#### Community Engagement  

To sustain and improve the project, the following strategies will be used:  
- **Outreach**: Collaborate with security technology providers and attend security conferences.  
- **Open-Source Contributions**: Engage with the open-source community to attract skilled developers and enhance features.  
- **Feedback Loop**: Partner with security firms to test the system, gather feedback, and refine the pipeline.  

---

### Conclusion  

This project delivers a real-time, scalable vehicle detection solution tailored for security applications. By leveraging advanced YOLO models, OpenCV, and a lightweight web interface, the system efficiently identifies unauthorized vehicles, reducing security risks and operational overhead. The open-source approach ensures continuous improvement and adaptability, making it a practical and future-proof solution for access control and monitoring.

---

### References  

Developers, T. (2022). *TensorFlow*. Zenodo.  
Faridoon, A., & Imran, M. (2021). *Big Data Storage Tools Using NoSQL Databases*. Computing & Informatics.  
Lenarduzzi, V., et al. (2021). *Technical Debt Prioritization*. Journal of Systems and Software.  
