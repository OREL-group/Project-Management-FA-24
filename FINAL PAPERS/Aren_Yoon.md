## College Resource Hub Database Design
Aren Yoon, IS 340, Fall 2024

### Summary
The College Resource Hub Database Design project is a database-driven approach that helps college students to locate resources needed easily and efficiently for academic and career success. This will benefit a wide range of students, including first-generation students and those with limited access to information, by offering integrated campus resources with customized functionality.

### Introduction
College students have used a variety of channels for exploring academic and career opportunities, including internships, mentorships, research, and events. This procedure is extremely time-consuming and inefficient. Additionally, scattered information poses even greater obstacles for first-generation students and other marginalized groups. In response, this project solves these challenges by offering a centralized database with tailored resource recommendations and intuitive navigation features, thereby increasing accessibility and simplifying resource management for students.

### Purpose
- To make it easier for students to explore academic and professional opportunities.  
- To fulfill individual needs and objectives using a customized database.
- To consolidate all campus resources onto a single platform, closing information gaps. 
- To ensure the system's continued expansion and adaptation, choose an intuitive and scalable database design.

### Vision
- **Centralized Resource Integration**: Combines internships, mentorships, research, events, and support programs into a single database.
- **Personalized Recommendations**: Offers tailored resource recommendations based on user profiles.
- **Logical Navigation**: Categorizes resources by topic, department, type, and level of need to allow quick and easy exploration.
- **Deadline Management**: Provides reminders for resource deadlines and integrates event schedules to prevent missed opportunities.
- **Evaluation System**: Collects student feedback to continuously improve the database and resource quality.
- **Data Visualization**: Allows users to visually track resource usage and set relevant goals for future opportunities.

### Database Design
The system uses a relational database structure with the following components:
- **User Table**: Stores user ID, name, department, year, interests, and goals for personalized recommendations.
- **Resource Table**: Manages resource ID, title, category, description, provider, deadline, and URL for centralized resource data.
- **Feedback Table**: Tracks user feedback, including resource ratings and comments, for continuous improvement.
- **Schedule Table**: Stores user-specific event dates and notification preferences for deadline management.
The database is designed for scalability, allowing easy addition of new resource types and evolving user needs.

### Open-Source Solution
The project follows open-source principles to ensure collaboration and transparency:
- **Openness**: Codebase and database structure are publicly available on GitHub.
- **Technology Stack**: MySQL/PostgreSQL (database), Node.js with Express (backend), React.js (frontend).
- **Collaboration**: Developers, designers, and contributors can improve the system by providing feedback and features.
- Transparency: All documentation and development progress are accessible, ensuring trust and accountability.

### Target Users
- **College students**: Primary users seeking to explore and utilize campus resources.
- **First-generation students**: Those requiring additional support to find personalized resources.
- **Professionals and mentors**: Contributors offering mentorship and networking opportunities.
- **Administrators**: Users managing resources and incorporating feedback for system improvement

### Strategy
- Develop an intuitive, user-centered design to ensure easy navigation.
- Continuously collect and analyze user feedback to refine features.
- Create a scalable database structure that supports future resource additions.
- Foster open-source collaboration to encourage innovation and growth.

### Development Stages
1. **Research and Planning**: Conduct user research, gather requirements, and define the project scope.
2. **Database Design**: Design the database structure and input initial test data.
3. **Prototype Development**: Develop UI/UX prototypes and collect feedback.
4. **Implementation**: Build and integrate the backend, frontend, and database.
5. **Testing and Refinement**: Conduct functionality tests, fix errors, and pilot the system with early users.
6. **Final Deployment**: Optimize the system, launch it, and provide continuous updates and maintenance.

### Conclusion
This project delivers a database-driven platform that improves access to academic and career resources for college students, particularly underserved groups. Its personalized features, intuitive design, and open-source foundation ensure scalability, transparency, and continuous improvement. By addressing information gaps, the platform creates a more equitable environment where all students can confidently pursue their goals.

### References
- Nagle, T., & Sammon, D. (2020). The role of open source in modern software development. Journal of Open Innovation: Technology, Market, and Complexity, 6(3), 85.
- Yan, Z., Wang, W., & Ye, J. (2022). A user-centered design approach for database-driven platforms: Case study and implementation. Journal of Systems and Software, 190, 111320.

