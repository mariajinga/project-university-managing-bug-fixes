# Web App for Managing Bug Fixes | Aplicație Web pentru Gestionarea Bug-urilor

*******************************************************
https://youtu.be/QSkBtqw8lSQ
*******************************************************
 
## Overview | Prezentare Generală

The project involves the development of a **web application** dedicated to the management and resolution of bugs within a software application. The main purpose of the application is to facilitate communication between members of a development team to identify, monitor, and resolve bugs efficiently. 

Proiectul constă în dezvoltarea unei **aplicații web** dedicate gestionării și rezolvării bug-urilor în cadrul unei aplicații software. Scopul principal al aplicației este facilitarea comunicării între membrii unei echipe de dezvoltare pentru identificarea, monitorizarea și rezolvarea bug-urilor într-un mod eficient.

## Key Features | Funcționalități Esențiale

- **Single Page Application (SPA)** architecture accessible from various devices: desktop, mobile, and tablets.
- **User Authentication**: Students can log in with an email-based account.
- **Project Monitoring**: Ability to register software projects for bug tracking.
- **Bug Management**: Log bugs with information like severity, priority, description, and associated commit link.
- **Role-Based Permissions**: Manage access rights for project members to add and modify projects or update bug statuses, while testers can add new bugs.

- **Aplicație tip Single Page Application (SPA)** accesibilă de pe diverse dispozitive: desktop, dispozitive mobile și tablete.
- **Autentificare utilizator**: Studenții se pot conecta cu un cont bazat pe adresă de email.
- **Monitorizare proiecte**: Posibilitatea de a înregistra proiecte software pentru monitorizarea bug-urilor.
- **Gestionarea bug-urilor**: Înregistrarea bug-urilor cu informații precum severitatea, prioritatea, descrierea și legătura către commit-ul asociat.
- **Permisiuni bazate pe roluri**: Gestionarea drepturilor de acces pentru membrii proiectului pentru a adăuga și modifica proiecte sau a actualiza statusul bug-urilor, în timp ce testerii pot adăuga noi bug-uri.

## Project Structure | Structura Proiectului

The project focuses on understanding and developing the interaction between the **front-end** and **back-end** within a web application, specifically for bug management and resolution.

Proiectul se concentrează pe dezvoltarea și înțelegerea interacțiunii dintre **front-end** și **back-end** în cadrul unei aplicații web, axându-se pe gestionarea și rezolvarea bug-urilor dintr-o aplicație.

### Front-End

The structure of the project is organized into three main components:

- **HTML, CSS, JavaScript**: The project is organized into separate components with individual files for each. This modular development allows for efficient code management.
- **Client-Server Architecture**: Emphasizes the importance of the front-end in providing a pleasant and functional user experience.

Structura proiectului este organizată în trei componente principale:

- **HTML, CSS, JavaScript**: Proiectul este organizat în componente separate, cu fișiere individuale pentru fiecare. Această dezvoltare modulară permite o gestionare eficientă a codului.
- **Arhitectură Client-Server**: Evidențiază importanța front-end-ului în furnizarea unei experiențe de utilizare plăcute și funcționale.

### Back-End

The back-end is responsible for managing bug fixes and handling operations related to collections, bugs, and users. Key components include:

- **Controllers**:
  - `bugs.js`: Handles operations for bug collection, with a focus on the `create` and `update` functions for data manipulation.
  - `users.js`: Manages user-related operations, with emphasis on the `create` and `update` functions for user data management.
- **Models**:
  - `bugs.js` and `users.js`: Define the data structures and relationships in the database.
- **Routes**:
  - API routes are defined in `bugs.js` and `users.js`, improving request handling and error management.
- **Services**:
  - CRUD operations are performed using `bugs.js` and `users.js` modules, where data consistency bugs are identified and fixed.
- **Main**:
  - Configures the Express server, manages middleware, and handles database connections to ensure overall stability.

Back-end-ul este responsabil pentru gestionarea bug-urilor și manipularea operațiunilor legate de colecții, bug-uri și utilizatori. Componentele cheie includ:

- **Controllers**:
  - `bugs.js`: Gestionează operațiunile pentru colecția de bug-uri, concentrându-se pe funcțiile `create` și `update` pentru manipularea datelor.
  - `users.js`: Gestionează operațiunile legate de utilizatori, cu accent pe funcțiile `create` și `update` pentru gestionarea datelor despre utilizatori.
- **Models**:
  - `bugs.js` și `users.js`: Definesc structurile datelor și relațiile în baza de date.
- **Routes**:
  - Rutele API-urilor sunt definite în `bugs.js` și `users.js`, îmbunătățind manipularea cererilor și gestionarea erorilor.
- **Services**:
  - Operațiile CRUD sunt realizate folosind modulele `bugs.js` și `users.js`, unde se identifică și remediază bug-uri care pot afecta consistența datelor.
- **Main**:
  - Configurează serverul Express, gestionează middleware-urile și conexiunile la baza de date pentru a asigura stabilitatea generală.

## Conclusion | Concluzie

By addressing and fixing bugs in each section, the goal is to improve the overall quality and stability of the application. The project emphasizes the importance of effective communication and collaboration within development teams to manage software bugs efficiently.

Prin abordarea și rezolvarea bug-urilor în fiecare secțiune, se urmărește îmbunătățirea calității și stabilității generale a aplicației. Proiectul subliniază importanța comunicării și colaborării eficiente în cadrul echipelor de dezvoltare pentru gestionarea eficientă a bug-urilor software.

---
