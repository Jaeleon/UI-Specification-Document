# **User Interface Specification Document For the User Management Panel**

1. ## **Introduction** 

    1. ## Purpose of This Specification Document

    In this document explanation and requirements for user interface will be covered. Also, the limitations of the project and the tools that are required will be covered in this document.

    2. ## Scope of This Specification Document

    This document will explain all details related to this user interface project and it will help both developers and users to understand what kind of product they will encounter at the end. 

    3. ## Overview

    The aim of this user interface is to access databases that contain all pieces of informations about users that are registered in system. This user interface will be used to control user profiles. With the help of this user interface managers easily see registered users. Also, they can register, delete users and update their information easily. 

2. ## **General Description**

This user interface offers accessing a user management panel screen for managing users. It contains a registration form where managers can register new users. In this part, they can enter information like username, mail, and roles to save them in the system. In the left part there will be a list of users according to the filters that the user chooses. They can filter or order by username, email, id and they can choose to hide disabled users. 

3. ## **Functional Requirements**

This user interface requires to meet users' needs. It must have a good and well-organized design for users to read all items without confusion. 
- First of all, in this project, there must be a database to connect. In this database, there must be tables for pieces of information that will be used for each user. So, we need queries to create tables, and website codes like PHP codes to connect this database to the website.
- This user interface needs forms and functional buttons that can be used to make operations on the system. We will need buttons like save user, new user, and filter to choose the operation that the user will make. 
- A server is needed to run database smoothly. 
- User interface needs a box that contains informations of registered users. In this table, managers must see user informations and change them. 

4. ## **Interface Requirements**

The project needs connections between different kinds of codes and users. We must specify how codes will connect to each other. Also, we must ensure that users can easily communicate with our system. For these reasons, we need a few things.
- Web programming languages such as HTML or CSS to build interfaces to communicate with users.
- A programming language like Python or PHP to connect database to our forms and buttons on the website. 
- The website must work on HTTP or HTTPS. So, we need web certificates.

5. ## **Performance Requirements**

User interface must be well designed and we must calculate the functions and actions carefully. This project must have no issues with performance so that every user can use it easily on every platform. In order to do this we must consider some ideas.
- We must avoid using unnecessary coding to prevent loss of memory. 
- We must ensure that our user interface works well on every web browser and on mobile browsers as well.
- User interface must take informations and save them in database quickly to avoid any synchronization problems.
- The project must be optimized well to prevent the usage of lots of memory or CPU on users' devices.
- In heavy load, the project must respond to every action to prevent a crash in the system. 

6. ## **Non-Functional Requirements**

Our user interface must be reliable, compatible, safe, and secure. In order to relieve user's concerns we must complete some parts to make sure that we meet some requirements.
- Accessing this user interface must be impossible without permission, so that unauthorized people can't access our user interface. 
- We must use some cookies and protocols in our codes to make our system more secure.
- Our system must be very fast, every button must operate its functions in under 1 second. 
- This user interface must contain compatible codes, so that it can run on every device and browser. 
- In this user interface we must offer lots of storage, therefore it can carry much information with lots of users. 
- The user interface can be designed in more than one language to reach more users.

7. ## **Risks**
Like every project, this project can lead us to some risks. We must absolutely work to avoid these risks. In order to prevent problems we must think, learn and work about them to list and see these problems.
- Our system has a risk of being accessed by unauthorized people. If they can access our system without permission they can easily edit and change the system.
- This project can crash under heavy load if we don't give enough storage and memory to the system. 
- In the user interface if there is a low productivity issue users can't have their functions done. 
- Servers and databases may cost us much if we don't choose them carefully.

8. ## **Glossary**

- Database: A set of systems that contains tables, columns, and rows to hold information.
- Server: A computer program or hardware that provides connection to another computer or users.
- CPU (Central Processing Unit): CPU is a type of processor that execute lots of operations such as algorithms, I/O, and logic operations. It is known as the brain of a computer.
- Memory: Memory in computers or systems holds data and makes access to this data quickly. 
- Crash: It is a term that is used for when a computer or system stopped functioning properly. 
- HTTP(Hypertext Transfer Protocol): HTTP or HTTPS is the primary protocol that is used to send information between a browser and a website. The letter S in HTTPS means secure and this protocol encrypts information in a safe way to protect users.

9. ## **References**

- R. Chris. 2021. User Interface Design: 4 Key Elements for Every Project. Aloa. Retrieved from [Article Link](https://aloa.co/blog/user-interface-design-4-key-elements-to-consider-for-every-project)
- A. Darejeh, S. Dalbir. November 2013. A review on user interface design principles to increase software usability for users with less computer literacy. Journal of Computer Science. Retrieved from [Article Link](https://www.researchgate.net/publication/277589616_A_review_on_user_interface_design_principles_to_increase_software_usability_for_users_with_less_computer_literacy)
- J. Nielsen. January 2003. Usability 101: introduction to usability. JOUR. Retrieved from [Article Link](https://www.researchgate.net/publication/285838148_Usability_101_introduction_to_usability)
- https://www.geeksforgeeks.org/software-engineering-user-interface-design/