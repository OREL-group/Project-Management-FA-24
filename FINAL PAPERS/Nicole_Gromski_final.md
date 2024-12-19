## FitMe!- Personalized Fitness Application
Nicole Gromski
Fall 2024
[LinkedIn](https://www.linkedin.com/in/nicole-gromski/) 


### Abstract   

In this paper, I will be detailing the process of creating an open-source application in the context of an application that promotes the wellbeing of those with hectic schedules. This personalized fitness application focuses on utilizing technology to incorporate healthy lifestyle choices into schedules in a calendar-like format. The primary goal is to hone in on college students as they have sporadic schedules and may require guidance in prioritizing their health. The premise of the application is allowing users to input their schedule and their desired data in order to create a fitness plan made for them. Priorities of this project are transparency to stakeholders and documentation as it is an open-source project. This will be done through the use of Github where the source code will be easily available. In order to support this application, the project management methodology, Agile, will be a key player for developers to effectively communicate their processes and encourage a collaborative environment. Through these project management principles and more, I will be able to discuss the creation plan for this user-friendly application. 


### Introduction

As a college student, specifically my sophomore year, I found it difficult to manage my overwhelming and inconsistent schedule. Though my Freshman year was overwhelming and new, I had more support provided to adjust to my new lifestyle including dining halls, nearby gyms, and subjectively easier coursework. Sophomore provided another challenge. I was completely reliant on myself for grocery shopping and preparing meals, the gym was across campus, and courses started to get more difficult and my schedule started to fill up more. I found it challenging to maintain a healthy lifestyle of working out and cooking balanced meals in between all of my classes, homework, and extracurricular activities. Because of this, I physically felt my body being weaker which left me unfocused. According to BYU’s Life Sciences department, “Exercise induces good blood flow to deliver all the nutrients required to carry out the brain's job, while it also increases production molecules important to brain function, including memory (McGregor, 2022).” Being a full-time college student requires a lot of brain power that needs to function properly in order to excel academically and even socially. As I worked my way to a healthier lifestyle, I struggled to find an easy and reliable resource to help me get started. I did not have a routine to follow that would allow me to get on track or one that I did find felt overbearing and would not fit in my hectic schedule. Through all this, I wished there was a way to be guided into a workout routine with healthy meal ideas that I could force myself to adhere to by blocking off a part of my schedule.

Applications I looked into typically worked as a fitness tracker instead of an aid or worked as an aid without the diet. For example, the widely used application MyFitnessPal allows for users to track their weight goals, exercise, and water intake along with calories and nutrition. While another commonly used application called Nike Training Club created by Nike footwear company, offers workout programs and training plans for all levels created by the company. Though these apps have successful ratings and useful ideas, it did not have the purpose that I wanted which led me to Fit Me!

###Purpose

Fit Me! serves as a way for those with hectic schedules to value their health and promote a healthy lifestyle. It allows for personalization to cater towards a wide range of individuals to create an inclusive user-specific diet and exercise plan for all levels. Its main goal is to make life easier by providing a smooth user-friendly interface experience to allow you to continue to make sure to take care of your body. It also encourages educational growth as it guides users through diet and exercise plans that are right for them, allowing for beginner-friendly usage. 

###Target Audience

The audience I am targeting with this product is college students, ages 18 to 24. College students have courses throughout the week that do not allow for a standardized schedule. Courses are not the only part of their schedule to account for as they balance multiple extracurriculars, homework and exams, social interactions, and more. Because of this, their schedules are left all over the place with, many of times, scarce amounts of free time. They become reliant on calendars in order to account for all of their tasks that need to be done. 

Benefits specific to this target audience:

Flexibility: the application adapts to the inputted schedule to work around hectic schedules 

Budgeting: a feature is included to adjust recipes based on budgeting which can be beneficial to those with a specific budget and is good for young professional or students that do not have full-time jobs yet

Mental stimulation: studies have shown that improved diet and exercise can assist with mental focus which can be crucial for full-time students

Education: research is done to ensure approved exercise and meal plans are utilized through the application which can educate users that are unfamiliar with proper nutrition plans or knowing how to target specific muscles when exercising 

###Technology 

I want to prioritize efficiency, collaboration, and scalability when developing an open-source fitness application with a project management mindset. React, HTML, and CSS create a foundation for a user-friendly front-end design which ensures a practical, interactive interface for users to utilize when creating their personalized fitness plans. The backend would be Python as it would support the algorithmic database design and make the planned features, such as personalized meal plans and exercise schedules, dynamic. These technologies together were chosen as they are widely used when creating applications and ensure functionality and aesthetic appeal. This provides users with a consistent and engaging experience. 

For effective data management, MySQL serves as the database solution, supporting scalable storage of user data which is beneficial with data such as preferences and schedules. The development process is streamlined through the use of GitHub for version control. This helps developers collaborate on code updates, track changes, and ensure a clean workflow. Additionally, documentation is managed with Atlassian tools like Confluence. This provides a centralized platform for project tracking and developer notes that would support the open-source vision of the project.

The technologies I plan to use, such as React, HTML, and CSS, may present some potential for technical debt since they can be complex to understand. However, React’s popularity helps mitigate it due to its large community and growth of resources for learning and debugging. When using open-source data, there is also the potential for technical debt if the data is not properly integrated or doesn’t align with the application model, so choosing reliable, accurate, and relevant data is crucial. By using a commonly utilized tech stack, I can leverage existing documentation and create additional resources tailored to Fit Me! to keep the development process efficient.

###Features

Personalized Input- the application would include a page where users would input their schedule in a calendar format, their fitness goals and diet plans, and their personal preferences

Calendar Integration- the application would incorporate the outputted data into a calendar format that could easily be inputted into another calendar if preferred

Budget adjustability- a filter menu would allow for adjustability for price in terms of diet plans 

Dietary restrictions- as a part of the personal preferences page and dietary planner, a user is able to add their dietary restrictions such as allergies to filter out any diets that would not work for them 

User-friendly interface - developers will map out the interface using technology such as canva or LucidChart to ensure a user-centric interface and later accept feedback throughout the developmental stages to ensure optimal design

###Database Design

The database serves as a critical feature of the application especially as it relies on an algorithm. It enables efficient storage, retrieval, and management of user data. From a project management standpoint, selecting a scalable and secure database, such as MySQL, is essential to handle increasing user demands as the application grows. The database must support dynamic and algorithmic personalization. This is important when storing critical information like user preferences, schedules, and progress metrics. To make sure that there is collaboration among contributors, the database schema and design should be well-documented and version-controlled through platforms like GitHub. This allows for developers to understand, adapt, and expand the system without potentially causing errors or inconsistencies.

The database would be designed to manage all of the personalized user data inputted into the application on the beginning page. The user would need to create an account in order for the database to align the data with its specified user. The data would be segmented into attributes within the user entity such as age, weight, height, and more. Other entities could include diets and exercise plans (GeekforGeeks, na). 

Another important process included within this application is database integration as it helps maintain the application’s usability and future scalability. It is crucial to have regular updates to the database structure which can be guided by user feedback This makes sure that the system remains relevant, secure, and efficient. From a project management perspective, prioritizing database security, backup protocols, and performance monitoring guarantees reliability and user trust. 


### Developmental Phases 

This chart illustrates my proposed workflow in regards to this project. It is segmented into three different responsibility groups: the owner, frontend developers, and database developers. 

![workflow](https://github.com/OREL-group/Project-Management/blob/30c40f87d87970f1a9e728eb4f012fa372897b13/finalproject_images/Screenshot%202024-10-23%20235806.png)]

Phase 1: Planning - The process involves selecting tools, addressing user needs, conducting outreach research, designing the UI, and establishing agile methodology with effective team communication.

Phase 2: Implementation - The process includes creating components and pages, selecting or creating a database, and integrating a calendar feature.

Phase 3:Testing/Feedback - The process involves testing the application, releasing a beta version for feedback, and making adjustments accordingly.

Phase 4: Launch - The process includes running the application, documenting it, monitoring and updating the application and database, and executing marketing efforts. Post launch process would include maintaining communication with stakeholders and incorporating feedback into application updates. 


###Collaborative Methodology 

I plan to align the team workflow using Agile Methodology. Agile methodology provides a structured approach while still promoting flexibility. By organizing the development process into sprints, the team can focus on delivering incremental improvements and make sure that the product is focused on the user. This can help prioritize features as they are split up into digestible tasks. Daily standups promote consistent communication among team members and allow them to discuss progress, challenges, and upcoming tasks efficiently. This can be done through a unified communication source and at the beginning of the work day to provide direction for the upcoming day. It additionally helps resolve blockers to keep the process efficient. 

Teams can help prioritize tasks based on user need and project goals through backlog processing. This breaks down complex features into manageable tickets using tools like Jira. This allows for clear tracking of progress and seamless ticket integration for developers and contributors. Stakeholders can gain trust in the project through visibility into the project's roadmap. Unified communication applications like Slack or MS Teams can additionally enhance coordination. These platforms allow for a space where real-time updates, discussions, and potential feedback can be discussed. 


###Open Source 

Open source is an application whose design is publicly available and encourages collaboration, innovation, and inclusivity (Opensource, na). Open-source principles allow contributors worldwide to participate in building and improving the application. This offers diverse perspectives and expertise which can help the growth of the application. Developers can collaborate on the project via GitHub by submitting pull requests, identifying bugs, and enhancing functionality. This can accelerate innovation and ensure the product evolves based on real-world feedback. By providing access to the source code, the project encourages transparency to stakeholders as well as contributors. Through this, trust can be built and a wider range of people can benefit. 

By integrating open source principles, it can enhance scalability and sustainability. Technologies like React, Python, and MySQL, which are widely used, benefit from numerous libraries and community support. In turn, this can reduce development time and resources which can be cost efficient. Additionally, open-source contributions help maintain and improve the codebase and keep up with technological advancements. The use of Atlassian tools for documentation ensures that contributors have clear guidelines, creating a simplified and streamlined onboarding process for new developers. This collaborative and sustainable model ensures the fitness application remains dynamic, reliable, and accessible to a broad audience.


###Future Plans

As the personalized fitness application gains support and users, the idea of scaling its infrastructure to allow for growth will be a top priority. More servers may be needed as increased traffic can slow the application’s performance. Another solution is to use cloud computing technologies for storage users and data are increased. An example of this can be using a platform such as AWS which allows for quick access to storage, reduces storage spend, and secure and protects data ().  Through this technology the application could grow increasingly and even fosters the growing ability to incorporate features such as AI. AI can be used as a potential helpful chatbot to further increase user-experience and make the application easier to use. This growth also creates the need for updating the original database to a more expansive and dynamic solution which would be capable of handling large datasets. These adjustments will support additional features that could be implemented after the launch of the application such as manual personalization. Manual personalization allows users to change their fitness plans or schedule to more specific preferences beyond the application algorithm. This reduces the chances of users getting plans that they do not enjoy or adding in personal workouts that they do enjoy. 

The application will focus on refining the user experience by encouraging collaboration and feedback. Regular surveys, user testing, and open forums will help identify desired features and promote the evolution of the app to be even more beneficial to users. Another potential plan for the future is to expand the target audience which includes options for different age groups or fitness levels. This can increase future outreach and increase accessibility. Additionally, creating a feature where users can interact with one another through group challenges or shared fitness goals could be implemented. This feature could encourage user engagement and foster a sense of belonging along with expanding outreach. The application can scale effectively by aligning these strategies with user needs to promote growth within an open environment.


###Conclusion

In conclusion, the development of FitMe!, an open-source personalized fitness application, relies on a collaborative approach that integrates user feedback and effective project management practices. By using Agile, prioritizing community engagement, and focusing on a dynamic database, the project can evolve in response to user needs and growth. Ultimately, this project aims to create a user-friendly, adaptable platform and can be revolutionary in the fitness space. This not only promotes individual health and fitness, but also encourages community-driven innovation and improvement.


###Citations 

Cloud storage services on AWS. (n.d.-b). https://aws.amazon.com/products/storage/ 
Desktop, N. (2024, November 12). What is the REACT framework & why is it so popular?. Classes Near Me Blog. https://www.nobledesktop.com/classes-near-me/blog/what-is-react#:~:text=React%20is%20currently%20the%20most,use%20in%20the%20past%20year. 
GeeksforGeeks. (2024, September 24). Database design in DBMS. https://www.geeksforgeeks.org/database-design-in-dbms/
McGregor, G. (2022, January 28). How exercise affects the brain. Life Sciences. https://lifesciences.byu.edu/how-exercise-affects-your-brain 
Opensource.com. (n.d.). What is open source? https://opensource.com/resources/what-open-source 
