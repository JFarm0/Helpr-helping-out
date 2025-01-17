<!-- # Project Outline -->
<!-- For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/modules/assignments/project-outline)

## Submission Instructions
 -->
# Helpr
This was my capstone project for LiftOff with LaunchCode that ran from July to September 2021. This was built with three other LaunchCode LC101 graduates. The working title of the project was "helping out" which is what it will appear as in your IDE.

### Overview
This project was designed to be an online portal in which non-profit organizations and interested volunteer candidates could search for one another based on shared interests. This two-way list feature would require users to register as an organization or an individual, create a profile with interests via a tagging system. As a registered user, organizations will update or delete their account as needed.

An overarching admin level would have power to add, edit and delete volunteers, organizations and tags as needed.

In the creation of this application, we had stretch features that we could have seen incorporated to the final product. These could have included: tracking volunteer hours, volunteer experience and opportunity feed, Google geolocation integration and more.

### Features
User account creation and authentication: Volunteers and organizations will both be allowed to create accounts, with differing access rights and permissions.

Tagging system with list functionality: Organizations will be able to link various tags to their organization detailing what “causes” they are involved in. Users will be able to peruse through the organizations via the same tag system.

Automatic database CRUD: All users will be automatically be added to persistent, application-created tables and associate tags with their accounts at will.

### Technologies Used
IntelliJ

Spring Boot

Java

Hibernate (JPA)

Thymeleaf

Bootstrap

MySQL

GitHub Version Control

### Executing the program
After copying the "helping out" project code into your IDE, open up your database service. We used IntelliJ and MySQL Workbench respectively. Once both programs are running, check to make sure that application.properties is pointing to the correct database. This database schema would need to be created in your database service. Finally, bootRun the project and point your browser to localhost:8080.

<!-- ### What I'll Have to Learn
At this juncture, we have several possible areas of increased learning. Creating various levels of user access and permissions is something that we have not been exposed to yet. Having the two main user groups with two-way searching is also a new area of possible development. Authentication options have not been determined yet, but there will be much to learn in that area.
### Project Tracker
Link to your Trello board here
https://trello.com/b/39iI2e7c/group-b-capstone-project -->
