# Overview
This project was developed as part of the Advanced Programming course during the second year of our B.Sc. studies at Bar-Ilan University (BIU). The project was a team assignment, where we were required to design and implement a fullstack video-sharing platform, inspired by YouTube.
<br/>
The solution includes:
- A React-based web app
- An Android native app
- A Node.js-based backend with Express
- A C++ TCP server for recommendations
- A MongoDB database
  
# Collaborators
- [Erez Chamilevsky](https://github.com/ErezChamilevsky) - erez284@gmail.com
- [Izhak Ben David](https://github.com/Izhakbd) - izhak573@gmail.com 

## 💻 Frontend

### Web Application
- Built using **React.js**
- Styled with **CSS/Bootstrap**
- Client-side routing using `react-router`
- Implements components for:
  - **Sign Up** & **Login**
  - **Video Feed (Homepage)**
  - **Video Player Page**
  - **Upload/Edit Video**
  - **Comment Section**

### Android Application
- Developed using **Java** in **Android Studio**
- Mimics the structure and functionality of the web version
- UI/UX optimized for mobile (e.g., drawer menu, responsive design)


## Backend

### HTTPS Server
- **Node.js + Express**
- Implements a **RESTful API** that powers the frontend and mobile app
- Handles:
  - User authentication via **JWT**
  - Video CRUD operations
  - Comments management
  - Serving media files and user profiles

### TCP Server (Recommendations)
- Developed in **C++**
- Listens on a separate port to generate video recommendations
- Algorithm based on user history and behavior patterns

## Database
- **MongoDB** used for storing:
  - Users (with encrypted passwords)
  - Videos metadata
  - Comments
  - Likes, views, etc.
- Authentication and access control implemented

# Repositories
As part of the course structure, we worked with **Git and GitHub**, maintaining:
- Multiple branches:
  - One per project phase (e.g., `part-1`, `part-2`, `part-3`, `main`)
  - Merging via **Pull Requests** with code reviews by teammates
- All feature development was done via **feature branches**, reviewed before merging to `main`
<p>Check out the different components of the project:</p>

<ul>
  <li>
    <a href="https://github.com/ErezChamilevsky/ProjectAndroidVersion/tree/part3Main" target="_blank">
      Android Application (Java)
    </a>
  </li>
  <li>
    <a href="https://github.com/ErezChamilevsky/Project-Part1" target="_blank">
      Web Application (React)
    </a>
  </li>
  <li>
    <a href="https://github.com/Izhakbd/CPP-TCP-Server/tree/main" target="_blank">
      TCP Server (C++)
    </a>
  </li>
  <li>
    <a href="https://github.com/ErezChamilevsky/youtubeProjectServer" target="_blank">
      HTTPS Server (Node.js)
    </a>
  </li>
</ul>

> In addition, we also managed our project using **JIRA**, planned sprints, and tracked task ownership and 



https://github.com/user-attachments/assets/086483c8-4ee0-4733-a129-d06c3349b58f


https://github.com/user-attachments/assets/0d9016c9-4730-4a2e-85c6-e16c8eacd600


https://github.com/user-attachments/assets/d8484157-8fcf-42a3-9fb2-7183a4058617

## Final Notes

This project simulated the full software development lifecycle:
- Requirements analysis
- UI/UX design
- Agile teamwork with sprints
- Git-based collaboration with pull requests and reviews
- Cross-platform development (Web + Android)
- Integration of modern technologies across frontend and backend

We're proud of this system and the collaboration that brought it to life.
