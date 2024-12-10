## TITLE
Mariam Sanusi, Fall 2024

##Abstract
Inclusion Direct is a project designed to foster inclusivity and representation in technology by developing a mentorship platform tailored for underrepresented groups, specifically women of color in tech. This platform bridges the gap between mentors and mentees through a mobile application that combines centralized resources, personalized guidance, and professional networking opportunities within a safe and supportive environment. By addressing systemic exclusion, social isolation, and the lack of mentorship in the tech industry, Inclusion Direct aims to empower marginalized individuals so they thrive professionally and personally. This paper discusses the vision, design strategies, and potential challenges of implementing Inclusion Direct.

##Introduction
Currently, open-source projects have grown to be a crucial force for fostering collaboration, inclusivity, and innovation. Open-source initiatives are responsible for bringing people together to share knowledge, build towards solutions, and address pressing social challenges. However, as technology continues to evolve, the disparities in access and representation within the industry have become more evident, especially for women of color. Underrepresentation not only limits opportunities for individuals but also stifles the diverse perspectives that drive meaningful progress. Inclusion Direct was created to close this gap using the principles of open-source collaboration to create a platform that will empower and uplift those who have been historically marginalized in tech. In addition, the platform will leverage the openness and adaptability of technology to create an inclusive and supportive space. The creation of Inclusion Direct is rooted in the understanding that mentorship and community are necessary for breaking down barriers and building a more equitable future.
##Vision Statement
Inclusion Direct envisions a future where the field of technology is accessible, inclusive, and empowering for all, specifically for underrepresented groups. This platform seeks to break down systemic barriers, inspire confidence, and enable marginalized individuals to thrive in the tech industry through connections made through the platform. The primary goals of Inclusion Direct include creating an inclusive mentorship network, facilitating meaningful long-term connections, and offering activities that encourage growth and engagement.
##Target Audience
The primary audience for Inclusion Direct consists of women of color who are aged over 14 and are looking to be active in the tech industry yet are having difficulty making connections and finding ways of entry. The platform offers the audience direct access to mentors who understand their unique experiences, helping to build confidence and foster career growth. This platform will be accessible through mobile applications and online channels, effectively ensuring availability to users wherever they are. Developers are another crucial audience for this project. Open-source contributors, UI/UX designers, and software engineers who are passionate about social impact will find opportunities to collaborate on improving the platform. With their contributions, the tools and features that drive Inclusion Direct can be formed. By focusing on this audience, Inclusion Direct will not only support those who need mentorship but also create a collaborative ecosystem where developers and users collectively contribute to a shared goal of building an inclusive and equitable tech community.
##Open Sourcing and Contributors
A key aspect of this project is the usage of Open Source for its development. Open source refers to a software development model where the source code is made freely available for everyone to view, use, modify, and distribute. With this type of approach, a collaborative environment is fostered, and global communities of developers can contribute to the evolution of the project.

As Comino states in “From Planning to Mature: On the Success of Open Source Projects”, the bigger the community, the higher the probability that, within the community, a developer has the skills to fix a bug or improve the software code. This is one of the benefits that come with the usage of open source because not only does the platform improve, but the developer gains the chance to form a connection with the other people who have worked on the project before they did, along with the people who are using the project.

Inclusion Direct adapts several principles of Open Source, three of them being transparency, collaboration, and accessibility. Throughout the development process, the project’s codebase, documentation, and development roadmap will consistently be accessible to the public, which ensures visibility into all parts of Inclusion Direct’s development and decision-making. In terms of collaboration, there is the input of developers, designers, and users, all of which are able to connect to each other. Finally, as this platform is designed to empower underrepresented groups and ensure equitable access to resources, there is consistent accessibility.

This project will use an open-source model to enhance transparency with the easily accessible codebase. The aim is to create a technically sophisticated platform that attracts killed contributors who are intellectually motivated. “Developers’ efforts mainly focus on 'behind the scenes system applications' or utilities providing basic functionalities,"  (Comino et al., 2007), which aligns with our project's technical focus.

Additionally, using a transparent codebase will allow stakeholders to track the evolution of the project by ensuring it meets the evolving needs of the community. This transparency also helps build trust and demonstrate accountability. 

As a result, Inclusion Direct will be hosted on GitHub, which is a widely used platform that supports collaboration through version control, issue tracking, and community-driven feature requests. The infrastructure also allows the project to maintain a well-documented and modular codebase which aligns with Crowston et al. (2007) who emphasized that source code of high quality is a key indicator of software success. With GitHub, contributors can submit pull requests to propose changes which will be visible for all to peer review and allow only the high-quality and vetted code to be added to the project. The Discussions feature also fosters engagement for this project by enabling open conversations about the project, its direction, and challenges.


By lowering barriers to entry and fostering collaboration, GitHub will position Inclusion Direct for growth and long-term sustainability.
Project Plan
This workflow map outlines the lifecycle of Inclusion Direct, detailing each phase of its development and maintenance to ensure a robust and scalable mentorship platform. 

The first phase is Tool Selection and Design which occurs from months one to two. This phase focuses on identifying and selecting technologies tailored to the project’s requirements. Tools such as React Native (for cross-platform mobile app development), Node.js (for backend services), and PostgreSQL (for database management) were chosen for their scalability and community support. Open-source libraries will be used to enhance functionality while reducing costs.

The second phase is the Development and Documentation Setup phase which occurs from months three to four. Here, the coding standards are established to ensure consistent, maintainable code. Tools like GitHub for version control and Swagger for API documentation were selected to promote clear communication and collaboration. Comprehensive documentation enables developers to contribute efficiently and ensures smooth transitions during team changes.

The third phase in the map is Code Reviews and Testing Infrastructure which occurs in month five. This phase involves setting up code review processes using GitHub Actions for automated checks and manual peer reviews to maintain quality. 

The fourth phase is Monitoring Dependencies and Performance which occurs in month six. Performance baselines are established here using New Relic. New Relic is a web-based software platform that helps monitor, debug, and improve applications, infrastructure, and other components. For this project, New Relic will be used to track the platform’s responsiveness, scalability, and dependency health. 

The fifth phase is responsible for Scaling Preparation which occurs from months seven to eight. To prepare for growth, the codebase is refined for scalability. Optimizations include database indexing and load balancing using AWS Elastic Load Balancer to handle increased traffic. Elastic Load Balancing (ELB) automatically distributes incoming application traffic across multiple targets and virtual appliances.

The sixth phase is the Dependency Update Sprint which occurs in month nine. This phase focuses on updating all key dependencies to their latest stable versions, ensuring compatibility and security. Automation tools like Dependabot streamline this process. Dependabot is a GitHub feature that helps developers manage dependencies and security concerns by automatically updating dependencies and identifying security vulnerabilities.

The seventh phase is about Migration Strategy Development which takes place in month ten. In this phase, a future-proof migration plan is created to allow seamless transitions to updated software or alternative frameworks without disrupting users.

The eighth phase is responsible for the Review and Performance Testing of the platform. This occurs in month eleven. Thorough testing evaluates whether the platform can support anticipated growth. Stress tests using Apache JMeter simulate heavy usage to identify bottlenecks. This project uses Apache JMeter because it's used to test the performance and scalability of applications by simulating heavy loads of traffic.

The ninth phase fixates on Ongoing Debt Assessment and Future Maintenance and occurs from the twelfth month well into the future. In this phase, regular assessments will track technical debt, ensuring the platform remains maintainable. Debt is prioritized and managed using tools like SonarQube which is an open-source platform that analyzes code quality to detect bugs and security issues. Future maintenance will have monthly code reviews, quarterly refactoring, and yearly migration updates. This ensures the platform evolves alongside user needs and technological advancements.

By combining cutting-edge tools and best practices, this workflow ensures the development of a high-quality, adaptable, and inclusive platform.
Project Implementation
The final platform will be an open-source platform made to empower underrepresented groups such as women of color in tech. It will feature a seamless interface for mentees to find mentors, participate in community discussions, and access curated resources. The backend will facilitate secure and efficient data management, while the frontend will provide an intuitive user 


[Comment_1]: <> (begin your text here)


[Comment_2]: <> (An example of a reference in paper text, cite in Reference list -- see Comment 8)

#### Subheading
[Comment_3]: <> (begin your text here)

| ![](https://user-images.githubusercontent.com/38323286/233691025-55deb1db-3e35-4589-8c55-4f859f8e41cd.jpg) | 
| :--: |
| <b>Figure 1.</b> Caption test. [Store image as an issue](https://github.com/OREL-group/Project-Management/issues/279) or in the local directory. |   

[Comment_4]: <> (Insert Figure with caption here)

#### Subheading     

[Comment_5]: <> (begin your text here)

__Paragraph heading__         

[Comment_6]: <> (begin your text two spaces after the last underscore in the previous line)


### Conclusion      

[Comment_7]: <> (begin your text here)


### References     

[Comment_8]: <> (begin your reference list here. Cite as author, year in main text. Reference link should correpond with link in Comment 2  Use any format you wish -- MLA, APA, etc.)

Cite as the form (Lastname, 2023) in the body of your text. List reference citation in this section. 
