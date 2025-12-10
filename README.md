BiLish Website Project - README

Project Overview

This project contains the official website for BiLish - Private English
Course, including: - Landing page - Login & Register system (Firebase
Authentication) - Responsive design using Bootstrap and custom CSS -
Carousel banners, services section, catalog, team, testimonials, events,
and contact form

Folder Structure

    BiLish/
    │
    ├── assets/
    │   ├── css/
    │   ├── js/
    │   ├── images/
    │   └── webfonts/
    │
    ├── vendor/
    │   ├── bootstrap/
    │   └── jquery/
    │
    ├── login/
    │   ├── firebase-auth.js
    │   ├── script.js
    │   ├── style.css
    │   └── index.html (login & register)
    │
    └── index.html (Landing page)

------ Login System ------

The login and register system is located inside:

    BiLish/login/

and contains: - index.html - style.css - script.js - firebase-auth.js

Firebase Authentication

The login & register functions use: - createUserWithEmailAndPassword -
signInWithEmailAndPassword

Configured through:

    firebase-auth.js

------ Deployment ------

The project is deployable on Vercel since it is fully client-side.

Requirements

No backend server required. Only: - HTML - CSS - JavaScript - Firebase
Authentication

Usage

1.  Open index.html to access the landing page.
2.  Click Register Now! to enter login/register page.
3.  User accounts are created through Firebase.
4.  Successful login redirects back to the main website.

------ Author Notes ------

1. Favicon added
2. Contact details and social links available
3. Ready for presentation to client
4. You can access the project by visiting this link: bi-lish-project.vercel.app
