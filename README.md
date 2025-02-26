[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=18368184&assignment_repo_type=AssignmentRepo)
# SE_Day1
Software Engineering Day1 Assignment

#Part 1: Introduction to Software Engineering

A)Explain what software engineering is and discuss its importance in the technology industry.
1.Software engineering is the systematic approach to designing, developing, testing, deploying, and maintaining software applications. It involves applying engineering principles and methods to ensure the quality,realibility, effeciency, maintainability and overall functionality of software products.
2.The importance of software engineering in technology industry
a.Improves productivity and collaboration, software engineers can work in teams effectively ensuring faster development cycle and better software quality.
b.Ensures high-quality software, software engineering follows structured process to build software that is efficient, secure, and reliable. It reduces errors and ensures that software meets user needs.
c.Enhances scalability and performance, well engineered software can handle larger user loads and adapt to future business needs ,preventing downtime.
d.Increase  security and reduce risks, with the rise of cyber threats, software engineering focuses on secure coding practices to pretect sensitive data and prevent security breaches.

B)Identify and describe at least three key milestones in the evolution of software engineering.
1. The birth of software engineering - a period when software development faced major issues like cost overruns, project failures, and poor software quality. The impact emphasized the need for structured development methodologies and led to the creation of software development life cycle  models.
2. The emergence of object oriented programming - this introduced a new way of designing software by organizing code into objects, which represent real-world entities. Key principles of OOP are encapsulation, abstraction, inheritance and polymorphissm. The impact on software engineering improved code reusability and modularility, also made software easier to maintain and scale.
3. Introduction of structured programming - this approach promoted breaking programs into smaller, modular components using control structures like loops and conditionals instead of goto statements. The impact improved code readability, maintainability and debugging.

C)List and briefly explain the phases of the Software Development Life Cycle.
1. Planning - In this phase the goal, scope, and feasibility of the project are defined. Identify problem statement and business needs, estimate cost resources and timeline.
2. Requirement Analysis - Gather, analyze, and document functional and non-functional requirements. Conducting meetings with stakeholders, end-users, and business analysts. Creating a software requirement specification document.
3. Design - Create a blueprint of the software architecture, UI/UX, and database. Choosing algorithms, frameworks, and database models.
4. Implementation - Writting and implementation of the actual source code based on the design specifications. Developers follow the SRS and design documents to write code.
5. Testing - Identifying and fixing of bugs, errors, and vulnerabilities before deployment. Ensures scalability and data protection ,test individual components for errors.
6. Deployment - Release the tested software into the production environment and monitoring for performance issues and user feedback.
7. Maintenance - Ensure the software remains functional, secure, and up-to-date. Bug fixes and patches for newly discovered issues, security updates to prevent cyber threats and the software remains reliable and continuosly improved. 

D)Compare and contrast the Waterfall and Agile methodologies. Provide examples of scenarios where each would be appropriate.
1. Waterfall Methodology
a. The Waterfall methodology is a linear and sequential software development model where each phase must be completed before moving on to the next. It follows a structured approach and is best suited for projects with clearly defined requirements and minimal expected changes.
b. - Sequential Process: Follows a step-by-step approach from planning to maintenance.
 -Fixed Requirements: All project requirements are gathered and documented at the start.
 -Emphasis on Documentation: Heavy use of Software Requirement Specifications (SRS), design documents, test plans, etc.
 -Late Testing Phase: Testing is performed only after development is completed.
 -Rigid Structure: Difficult to accommodate changes once development begins.
c. for istance, banking and financial system they require High stability and reliability.

3. Agile Methodology
a. Agile is an iterative and incremental approach to software development that emphasizes flexibility, collaboration, and customer feedback also welcomes changing requirements and continuous improvement throughout the project lifecycle.
b. -Iterative Development: Software is built and improved through multiple short cycles (sprints).
  -Customer-Centric: Continuous involvement of stakeholders and end-users.
  -Adaptability: Changes can be made at any stage based on feedback.
 -Frequent Releases: Deliver small, working versions of the software regularly.
 -Collaboration: Developers, testers, and business teams work together closely.
c. For istance,  mobile App and web development they need Frequent updates based on user feedback.

E)Describe the roles and responsibilities of a Software Developer, a Quality Assurance Engineer, and a Project Manager in a software engineering team.
1.Software developer is responsible for designing, coding, testing, and maintaining software applications. They transform business requirements into functional software using programming languages and frameworks.
They understand project needs and translate them into software solutions.
2.quality assurance engineer ensures that the software meets quality standards by identifying defects, preventing issues, and maintaining high performance and security.
They are responsible for developing a test strategies, cases, and automation scripts.  Ensure the system can handle expected workloads. Verify that the software meets business needs.
3.Project Manager oversees the planning, execution, and completion of a software project. They ensure timely delivery, resource allocation, risk management, and communication with stakeholders.
Responsible for defining project goals, timelines, and deliverables. Task allocation and resource management. Ensure the project is completed within the allocated budget and deadline.

F)Discuss the importance of Integrated Development Environments (IDEs) and Version Control Systems (VCS) in the software development process. Give examples of each.
1. Integrated Development Environment (IDE) is a software application that provides all-in-one tools for writing, debugging, and testing code.
The importance is that it is efficience and productivity IDEs auto-complete code, provide syntax highlighting, and offer real-time debugging, reducing development time.
For example,  Visual Studio Code (VS Code) – A lightweight, extensible IDE for multiple languages like Python, JavaScript. A Java developer working on a Spring Boot application uses IntelliJ IDEA for efficient code navigation, debugging, and integration with Maven to manage dependencies.
2. Version Control System (VCS) is a tool that tracks changes to source code over time. It allows multiple developers to work on a project simultaneously, maintain different versions of the code, and revert to previous versions if necessary.
The importance is that it enables collaboration and teamwork, multiple developers can work on the same project without overwriting each other's code.
For example ,Git , the most widely used VCS, with tools like GitHub, GitLab, and Bitbucket for cloud-based collaboration. A team of frontend developers working on a React.js application use GitHub to manage code versions.


G)What are some common challenges faced by software engineers? Provide strategies to overcome these challenges.
1. Challenge : The tech industry evolves quickly, with new programming languages, frameworks, and tools emerging frequently. 
   Solution : Continuous Learning ,follow online course. Join developer communities, engage in platforms like Stack Overflow and Github. Follow industry trends: Read blogs , listen to tech podcasts, and attend webinars. Build small projects to experiment with new technologies
2. Challange : Debugging can be time-consuming, especially when dealing with complex systems or unfamiliar codebases.
   Solution : Break Down the Problem, isolate sections of code to identify where the issue originates. Explain the problem to someone to gain clarity. Look at logs and search for similar issues in developer forums.  Write Unit Tests, utomated tests help catch issues early before they escalate.

H)Explain the different types of testing (unit, integration, system, and acceptance) and their importance in software quality assurance.
1. Unit testing focuses on testing individual components/units of the software in isolation to verify their correctness. A unit can be a function, method, or class.
   The importance is that it catches bugs early in the development process. Helps ensure each unit works as expected before integration. Makes debugging easier, as issues are found in smaller, isolated parts of the code. Encourages modular development, leading to maintainable and reusable code.
2. Integration testing verifies that multiple components or modules work together correctly. It ensures that data flows properly between modules and detects issues related to APIs, databases, or third-party services.
   The importance is that it detects interface issues between modules. Ensures data integrity between different systems. Identifies dependency conflicts between integrated components.
3. System testing evaluates the entire application as a whole to verify that it meets functional and non-functional requirements.
   The importance is that it ensures the entire system functions correctly in a real-world environment. Validates both functional (features) and non-functional (performance, security) aspects. Identifies unexpected system behavior due to module interactions.
4. Acceptance testing determines whether the software meets business requirements and is ready for release. It is often performed by end-users or clients.
   The importance is that it ensures that the software meets business needs and user expectations. Reduces the risk of deployment failures. Helps get final approval from stakeholders before release.

#Part 2: Introduction to AI and Prompt Engineering


A)Define prompt engineering and discuss its importance in interacting with AI models.


B)Provide an example of a vague prompt and then improve it by making it clear, specific, and concise. Explain why the improved prompt is more effective.
