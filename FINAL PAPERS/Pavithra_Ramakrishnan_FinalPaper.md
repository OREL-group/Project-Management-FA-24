## Real-Time Vehicle Detection System Using YOLO for Unauthorized Vehicles  
Pavithra Ramakrishnan, Fall 2024, [link to personal website](https://www.linkedin.com/in/pavithramakrishnan/).  
Google collab final project file: https://github.com/OREL-group/Project-Management/blob/main/finalproject_images/License_Plate_Recognition.ipynb

---

### Introduction  

The rise in security concerns across critical infrastructures such as gated communities, airports, and government buildings necessitates advanced monitoring solutions. Existing systems often fail to provide efficient, real-time identification of unauthorized vehicles due to limitations in accuracy and processing speed. This project addresses these challenges by developing a state-of-the-art vehicle detection system that leverages the YOLO object detection framework. The system identifies unauthorized vehicles entering sensitive locations through live camera feeds, offering a scalable, adaptable, and user-friendly solution. By utilizing real-time processing and advanced machine learning algorithms, this project improves access control efficiency and overall security.

---

#### Vision Statement  

This project aims to deliver a real-time vehicle detection platform capable of accurately identifying unauthorized vehicles with minimal delay. The system integrates advanced machine learning techniques—YOLO—and efficient algorithms to process video feeds, providing actionable insights for security professionals. The solution prioritizes scalability and adaptability, ensuring seamless deployment across diverse environments and conditions. Ultimately, the project enhances security protocols while maintaining operational efficiency and reducing manual intervention.


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

| ![Workflow](https://github.com/user-attachments/assets/615d4a47-192c-4fbc-8df1-cc53be64828c) |  
| :--: |  
| **Figure 1.** Workflow Diagram. |  

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

#### Status

| ![Status](https://github.com/user-attachments/assets/9b7a00e0-adac-46ae-adad-43c0758beec1) |  
| :--: |  
| **Figure 1.** This output is a structured dataset or table capturing results from a vehicle and license plate detection/tracking pipeline. It logs relevant detection and tracking information frame by frame, exported from my detection system for further analysis. |  

| ![Successful Detection](https://github.com/user-attachments/assets/d03e7788-27b0-4a6d-8198-b290568ebcdf) |  
| :--: |  
| **Figure 2.** This output is a log of object detection results from a YOLO-based model processing video frames for real-time vehicle and license plate detection. |  

| ![Tracking Vehicles](https://github.com/user-attachments/assets/a77ab508-1b9f-4136-9b2e-142b0fed515e) |  
| :--: |  
| **Figure 3.** This output log contains the results of an object detection and tracking pipeline applied to video frames. It logs the detection and tracking results for cars and their associated license plates over multiple frames. |  


---

#### Addressing Technical Debt  

Technical debt in this project primarily arises from tool dependencies and scalability requirements. Frequent updates to tools like YOLO and OpenCV may introduce breaking changes, necessitating regular code reviews and a modular architecture to minimize disruption. Lenarduzzi et al. (2021) emphasize that prioritizing technical debt requires balancing maintenance costs, productivity impact, and business value to avoid significant long-term consequences.

Research by Faridoon and Imran (2021) highlights how NoSQL databases excel at managing large-scale, heterogeneous data efficiently, providing fault tolerance, scalability, and replication capabilities crucial for handling dynamic data growth in real-time systems. Such insights emphasize the importance of adopting modular, scalable storage solutions to mitigate long-term technical debt while ensuring high system performance.

Mitigating long-term technical debt involves maintaining clear documentation, automating workflows with CI/CD processes, and adopting a microservices architecture for improved flexibility and maintainability. Journyx (2023) highlights that while project management cannot be fully automated due to its complex decision-making requirements, integrating automation tools significantly enhances productivity by handling routine tasks. Applying this principle, automated pipelines for model retraining, error detection, and integration with the Flask-based web interface will ensure the system remains scalable and adaptable to evolving requirements.

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

The project also reflects an interest in exploring natural language processing (NLP) and gaining hands-on experience with practical applications of technology. While primarily focused on object detection, this project provides opportunities to integrate NLP techniques in areas such as automated reporting, alert generation, or log analysis. The system is built to handle different locations, hardware setups, and environmental conditions, making it adaptable for a wide range of applications like airports, office buildings, and gated communities. By taking an open-source approach, the system can continue to improve over time with contributions from others, ensuring it stays up-to-date and flexible as technology evolves. Overall, this project aims to create a practical and efficient solution for enhancing safety, improving operational efficiency, and exploring advanced technologies like NLP to address the growing need for smarter security systems.

---

### References  
 
Journyx. (2023, May 3). Can project management be automated? Journyx. https://journyx.com/resources/blog/can-project-management-be-automated/
Faridoon, A., & Imran, M. (2021). Big data storage tools using NoSQL databases and their applications in various domains: A systematic review. Computing and Informatics, 40(3), 489-521. https://doi.org/10.31577/cai_2021_3_489
Lenarduzzi, V., Besker, T., Taibi, D., & Martini, A., & Arcelli Fontana, F. (2021). A systematic literature review on Technical Debt prioritization: Strategies, processes, factors, and tools. Journal of Systems and Software, 171, 110827. https://doi.org/10.1016/j.jss.2020.110827
