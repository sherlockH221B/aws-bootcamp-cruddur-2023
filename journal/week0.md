# Week 0 — Billing and Architecture
Date 07-08-2024 + Video 01 to 10

01 Setting up with the github account along with gitpod.
02 Setting up the codespace into github
03 Setting up the free tier AWS Account and adding Multifactor authentication.
04 Create new repository this is my new repo for this 100 Hours AWS Cloud Bootcamp.
05 Create account on Lucid Charts.
06 Create account on HoneyComb.io https://ui.honeycomb.io/
07 Create account on RollBar https://app.rollbar.com/

++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

Video on the 11 is all about the created documentation folder and added the doc file. 

Andrew Brown introduces a free 14-week AWS Cloud project boot camp, discussing its structure, sponsors, and resources. Participants will build a cloud workload, focusing on CI/CD pipelines, decentralised authentication, and database management. The session emphasises the importance of understanding project requirements, risks, and constraints, while encouraging interaction and knowledge transfer among participants.
You may be interested in these questions:
What is the focus of the AWS Cloud project boot camp? 
How can participants manage their AWS spending during the boot camp? 
What are the key components of the CRUD application being built? 

Highlights


Intro of project
The AWS Cloud project bootcamp is a 14-week program designed to build cloud workloads while providing hands-on experience. Participants will engage in various projects, enhancing their cloud skills progressively.
Guest instructors introduce themselves and their backgrounds, highlighting their expertise in AWS and cloud services, providing valuable insights to participants.

(Lecture 1st from Manager perspective and CTO Investor)
The concept of user personas is discussed as a project management tool, helping participants to better understand their audience and stakeholder perspectives.


The startup called Crudder is developing an ephemeral microblogging platform aimed at users who prefer temporary online presence. The focus is on community engagement while protecting user privacy. The platform aims to attract users by offering a unique, community-focused experience, distinguishing itself from traditional social media like Twitter and Snapchat. 
The discussion focuses on transitioning from monolithic applications to microservices for improved scalability and resilience. This shift allows for better component reuse and complexity management in software development
Microservices enable decoupling of application components, allowing for independent scaling and maintenance. This architecture promotes flexibility and makes it easier to manage changes. 

AWS provides a robust platform for implementing microservices, offering various serverless options like Lambda. This facilitates the integration of different services as modular components.



The Iron Triangle of project management highlights the trade-off between budget, timeline, and scope. Understanding this can help teams prioritise effectively while managing project expectations.



Learning to think critically about project management is crucial for success. Emphasising trade-offs, such as those outlined in the Iron Triangle, helps teams navigate complexities effectively.


Architecture diagrams serve as vital communication tools. They help clarify project complexities to stakeholders and validate technical components with team members.

Summery(Recap)
Understanding the Iron Triangle concept is essential for project management. It highlights the balance between cost, speed, and quality, forcing teams to prioritise effectively.Effective communication and team collaboration are key skills for solution architects. Employers value candidates who can navigate technical and interpersonal challenges successfully.




(Session 2nd Start DEMO)
The session focuses on building a web application similar to Twitter, emphasizing the importance of explaining technical concepts in an accessible manner for different audiences. This involves using a project repository, automated environments, and emphasising software architecture principles.


Participants are instructed to copy a GitHub repository template and follow prerequisites for setting up the development environment. This ensures everyone is on the same page for the project.



The discussion shifts to the importance of soft skills in technical roles, highlighting how effective communication and understanding customer needs can lead to better project outcomes.



The application being developed will include features like user sign-ups, message replies, and a unique card expiration system, enhancing user interaction and experience.

What is Good Architecture?
Measurable requirements are essential in project planning, ensuring they are verifiable, monitorable, traceable and feasible. Proper measurement allows teams to assess requirements effectively and manage expectations.
Eg.
A good requirement should meet standards like ISO, providing a binary option for evaluation. This ensures clarity and easier verification of project goals.


Understanding risks, assumptions, and constraints is crucial for effective project management. These elements can significantly affect the feasibility and success of the project's requirements.


Conceptual, logical, and physical designs form a framework for translating business needs into technical specifications. This layered approach helps in organizing project development stages effectively.


Asking fundamental questions and engaging in conceptual exercises is crucial for developing a clear understanding of project requirements and constraints. This approach helps prevent oversights and sets the foundation for deeper discussions.


Engaging in creative exercises, like drawing diagrams on napkins, can facilitate understanding and encourage participation in brainstorming sessions. Such activities can foster innovative thinking among team members.


The concept of 'being the packet' involves visualizing the user experience to better understand system requirements. This method encourages team collaboration by highlighting different perspectives on project challenges.


Documenting all processes and decisions is essential for maintaining clarity and accountability within a project. This practice ensures that even those with minimal technical knowledge can grasp the project's scope and requirements.


Miscommunication often arises in group settings due to different perspectives among participants. To bridge these gaps, encouraging questions, even perceived as 'dumb,' fosters clarity and understanding.


Various frameworks exist to simplify complex projects, such as TOGAF and the 4C model. Choosing a familiar framework can enhance communication and streamline processes.


Understanding key performance indicators (KPIs) is crucial for evaluating system performance and optimizing costs. Companies must also consider sustainability goals to reduce their carbon footprint effectively.
The importance of selecting the right architecture is highlighted, weighing options between EC2 instances and serverless solutions. This choice influences cost and performance significantly.


Engaging with finance teams is essential for cost optimization 	
Sustainability practices are increasingly vital for organizations. Companies lacking sustainability goals may overlook important architectural considerations that can mitigate their environmental impact.

Lucide Chart 
Understanding the physical layer in cloud services involves recognizing specific resources like IP addresses and Amazon resource names. 

This detailed knowledge is crucial for effective management of cloud infrastructure.The physical layer includes granular details such as the names of S3 buckets and load balancers, which are essential for resource identification. This level of detail helps in troubleshooting and configuration.
Lucidchart is introduced as a valuable tool for creating conceptual diagrams, enabling clear communication of design ideas. It offers a free tier, making it accessible for users.




The discussion emphasises a user-centric approach to design, focusing on high-level functionality rather than specific technologies. This perspective helps align technical designs with business goals.


Understanding the architecture of a software system involves defining user identities and managing stateful data effectively. This ensures efficient data handling and real-time messaging capabilities within the application.


Identifying user identity is essential for creating unique profiles, which impacts how data is stored and managed within the system. This can influence user experience significantly.


The choice of database technology affects the system's scalability and performance, especially when handling stateful data and ephemeral messages. Different data storage solutions may be required.
Real-time components, such as messaging systems, need to be integrated into the architecture to support immediate user interactions. This is crucial for enhancing user engagement.


The discussion revolves around the implementation of decentralized services and the potential use of APIs for user interaction. Security aspects, particularly against DDoS attacks, are also emphasized in the design framework.


The team considers whether the search service should be classified as decentralized, focusing on its management and functional components. Clear definitions are essential for effective communication.


There are concerns about API accessibility directly by users, with executives preferring to limit exposure for security reasons. Rate limiting and security setup are discussed as crucial considerations.


The importance of intellectual property is highlighted, especially regarding unique services like timeline curation. Investors would be interested in understanding what distinguishes the product.










