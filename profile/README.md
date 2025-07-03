# Learning Management System (LMS) - Graduation Project

<div align="center">
  <img src="images/Cairo_University_Crest.png" alt="Image 1" width="156" height="200"/>
  <img src="images/sci-cu.png" alt="Image 2" width="200" height="200"/>
</div>

![Static Badge](https://img.shields.io/badge/CU-SCI-blue) ![GitHub License](https://img.shields.io/github/license/gp-lms-sci-cu-24/.github) [![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)](https://www.notion.so/Graduation-Project-cf2b59c49c5447829e59cc5e111964ac?pvs=4)

![HTML](https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white) ![Css](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![js](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E) ![ts](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)![react](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![react](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white) ![react](https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white)

![java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) ![spring](https://img.shields.io/badge/Microsoft_Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white) ![spring](https://img.shields.io/badge/json%20web%20tokens-323330?style=for-the-badge&logo=json-web-tokens&logoColor=pink) ![spring](https://img.shields.io/badge/redis-%23DD0031.svg?&style=for-the-badge&logo=redis&logoColor=white) ![spring](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=Spring-Security&logoColor=white)
![spring](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white) ![spring](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=Jenkins&logoColor=white)

![spring](https://img.shields.io/badge/Google%20Analytics-E37400?style=for-the-badge&logo=google%20analytics&logoColor=white) ![spring](https://img.shields.io/badge/Trello-0052CC?style=for-the-badge&logo=trello&logoColor=white)

Welcome to our Learning Management System (LMS) project! This system is designed to streamline and enhance the learning experience for both students and educators. This project is specifically developed as the graduation project for students in the Mathematics department at the Faculty of Science, Cairo University.

## 🚀 Features:

- **User-Friendly Interface:** Intuitive design for easy navigation.
- **Course Management:** Create, organize, and manage courses effortlessly.
- **User Roles:** Define roles for students, instructors, and administrators.
- **Assignment Submission:** Students can submit assignments online.
- **Grading System:** Efficient grading tools for instructors.
- **Real-time Communication:** Instant messaging for seamless student-teacher interaction.

## 🧰 Tech Stack:

- Java
- Spring boot
- Postgres
- HTML, CSS, JavaScript
- React
- Vite

## 🛠️ Tools:

- Docker
- Kubarnates
- Jenkins
- Nginx

## 🏗️ System Architecture

<p align="center">
  <img src="images/diagram-arch.png" alt="System Architecture Diagram" width="100%"/>
</p>

Our LMS (UPLern) is designed as a **monolithic architecture** with modular responsibilities and scalability in mind. Below is a breakdown of the system's core components:

- **Delta (Frontend)**: Built with **React** and **Vite**, it provides a responsive, user-friendly interface for students, instructors, and administrators.
- **Firewall Layer**: Handles access control and security filtering before requests reach core services.
- **Nginx**: Acts as a **reverse proxy**, managing traffic, load balancing across backend instances, and serving static files via CDN.
- **Lambda (Backend Services)**: Multiple instances of a **Java Spring Boot** backend handle core business logic such as user authentication, role-based access, registration, grading, announcements, and internal communication.
- **PostgreSQL**: Relational database storing users, courses, classes, schedules, messages, and performance data.
- **Redis**: Caching layer for sessions, frequent queries, and real-time event handling.
- **Jenny (AI Chatbot)**: Built with **Botpress**, Jenny helps students with FAQs, navigation, and learning support.
- **NFC Attendance Service**: A micro-service handling **NFC-based check-ins** to automate class attendance.

The architecture supports real-time communication using **WebSocket** and **Server-Sent Events (SSE)**, with a focus on speed, modularity, and reliability.

## 📽️ Project Presentation

> [Click here to watch the project presentation](https://www.canva.com/design/DAGJnM21mcQ/VHZul6l3XjXjzWaSDHOpQg)

## 📚 Full Documentation

> [Read the full system documentation](../docs/Uplearn_Gp_Document.pdf)

## 🌐 Landing Page

> [visit our landing page](https://uplearn-a6c00.web.app/)

## 🔗 Useful Links:

- [DOCS](../docs/Uplearn_Gp_Document.pdf)
- [Documentation Wiki](https://github.com/gp-lms-sci-cu-24/wiki)
- [Slack Channel](https://join.slack.com/t/graduationprojectlms/shared_invite/zt-2ddps1l2p-v2ST3WOaOOvOmfIriL5VaA) - Join our Slack community for real-time discussions.
- [Trello Board](https://trello.com/invite/graduationprojectlms/ATTI60f36808f858128dd0c880228aff1288D5A037B9) - Track project progress and tasks on our Trello board.
- [Notion Workspace](https://www.notion.so/Graduation-Project-cf2b59c49c5447829e59cc5e111964ac?pvs=4) - Collaborate and access project-related documents on Notion.
  We welcome contributions! Feel free to fork the project, make improvements, and create pull requests. If you encounter any issues or have suggestions, please open an [issue](https://github.com/gp-lms-sci-cu-24/issues). Happy learning!

## Collaborators:

| Code    | Name             | GitHub Account                                           | Email                       |
| ------- | ---------------- | -------------------------------------------------------- | --------------------------- |
| 2027453 | Mahmoud Atef     | [@Mahmoudbakar2002](https://github.com/Mahmoudbakar2002) | mahmoudatef.coder@gmail.com |
| 2027115 | Mohamed Atef     | [@hngara](https://github.com/hngara)                     | mohamedshata9898@gmail.com  |
| 2027069 | Abdallah Mohamed | [@Abdallah85](https://github.com/Abdallah85)             | abdallah.moh.153@gmail.com  |
| 2027220 | Hazem Mohamed    | [@hazemmuuhammed](https://github.com/hazemmuuhammed)     | hazemmuuhammed@gmail.com    |
| 1928275 | Ahmed Hany       | [@HNOONa-0](https://github.com/HNOONa-0)                 | hanyahmed11811@gmail.com    |
| 2027471 | Omar Kenawi      | [@omarKenawi](https://github.com/omarKenawi)             | omar.sseeddeekk@gmail.com   |
| 1927194 | Muhammed Walied  | [@Muhammed-Walied](https://github.com/Muhammed-Walied)   | mohamedwalied248@gmail.com  |
