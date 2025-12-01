# Manoa Guesser
Link to the GitHub organization can be found [here](https://github.com/manoa-guesser)

## Table of contents

* [Overview](#overview)
* [Deployment](#deployment)
* [User Guide](#user-guide)
<!-- * [Community Feedback](#community-feedback) -->
<!-- * [Developer Guide](#developer-guide) -->
<!-- * [Continuous Integration](#continuous-integration) -->
<!-- * [Walkthrough videos](#walkthrough-videos) -->
<!-- * [Example enhancements](#example-enhancements)  -->
* [Team](#team)


## Overview

**Manoa Guesser** is a gamified exploration web app designed to help students at the University of Hawaiʻi at Mānoa familiarize themselves with campus locations. Every year, UH Mānoa welcomes a new influx of students, many of whom struggle to navigate the large and diverse campus. This project aims to make the process of discovering study spots, landmarks, and hidden corners of campus both fun and engaging.

**The goal:**  
To create a campus-based guessing game that encourages exploration, connection, and familiarity with the UH Mānoa environment through friendly competition and participation.

**The system will eventually provide:**
- A guessing game where users identify locations from random photos taken around UH Mānoa.
- A points-based scoring system rewarding accuracy.
- User-submitted campus photos for community-driven content.
- Administrative moderation tools for managing photo submissions.

### Key Features
- **Interactive Gameplay:** Guess the campus location based on a provided image.
- **Leaderboards:** Track high scores and encourage competition.
- **Photo Submission:** Users can submit their own images for review.
- **Admin Dashboard:** Moderation tools to approve or reject submitted photos.

---

## Deployment

The project was deployed using Vercel and can be found at this [link](https://manoa-guesser.vercel.app/)

# M1 Board
[Link](https://github.com/orgs/manoa-guesser/projects/2)

# M2 Board
[Link](https://github.com/orgs/manoa-guesser/projects/4)

# M3 Board
[Link](https://github.com/orgs/manoa-guesser/projects/8)

---


## User Guide
This User Guide walks through all currently implemented functionality in Manoa Guesser. Each section includes a description of what users can accomplish on each page, along with example screenshots demonstrating the interface and workflow.

### Landing Page

The landing page introduces the app and provides navigation to sign in, sign up, or explore basic information about the project.

- Users can view the project purpose.
- Users can navigate to authentication pages to begin playing.

<img src='public/M2-Landing-Page.png'>

### Sign In Page

The Sign In page allows existing users to log into their accounts using their registered email and password.

- Users enter credentials to access gameplay, the leaderboard, and submission features.
- Authentication is handled securely using NextAuth.

<img src="public/M2-Sign-In.png">

### Sign Up Page

The Sign Up page enables new users to create an account.

- Users provide an email, password, and other required fields.
- Once registered, they can immediately log in and begin playing.

<img src="public/M2-Sign-up.png">

### Home Page

The Home Page serves as the central hub of the system.

Users can:
- Start a new game.
- View the leaderboard.
- Submit new campus photos.
- Navigate to other parts of the system.

**Screenshot:**  
<img src="public/M2-Homepage.png">

### Game Page

The Game Page is where gameplay occurs.

Current functionality includes:
- Displaying a campus image for the user to identify.
- Allowing the user to guess a location using the interactive map.
- Showing game results (score, accuracy) once a guess is submitted.

<img src="public/M2-Game-Page.png">

### Leaderboard Page

The Leaderboard page displays user scores in descending order.

Users can:
- View top-performing players.
- See their own best scores.
- Compare performance with others.

Scores automatically update based on gameplay results.

<img src="public/M2-Leaderboard.png">

### Submission Page

The Submission Page allows logged-in users to upload their own campus photos to expand the game content.

Users can:
- Upload an image file.
- Provide a location name and a hint.
- Submit the entry for administrative approval.

Once reviewed, approved images may appear in the gameplay rotation. (WIP)

<img src="public/M2-Submission.png">


### Admin Dashboard 

If the Admin Dashboard is enabled for your role:
- Admins can view all pending photo submissions.
- Admins can approve or reject images.
- Approved images become available for gameplay.

<img src='public/M2-Admin-1.png'>
<img src='public/M2-Admin-2.png'>

<img src='public/M2-Admin-Edit.png'>
---



<!-- 
## Community Feedback

Future stages of the project will include gathering feedback from UH Mānoa students and faculty to improve gameplay balance, usability, and engagement.

---

## Developer Guide

Manoa Guesser is being developed using **Next.js**, **TypeScript**, and **Prisma** for the backend, with a **PostgreSQL** database to store user accounts, photos, and scores.  
The system architecture will support:
- User authentication and role-based access control.
- Integration with campus maps for accurate geolocation scoring.
- A clean, responsive UI that aligns with UH Mānoa’s design identity.

--- -->

## Team

- [Lawrence Zheng](https://lawrencezheng5.github.io/)
- [Jia Jun Li](https://jiajunli526.github.io/)
- [Joshua Chow](https://zhouweijosh.github.io/)
- [Colbren Fujimoto](https://colbren.github.io/)

[Team Contract](https://docs.google.com/document/d/1WQjzh6r09rr-exfMHNruvm9btdQKU5Tv-qu1LLYoXVQ/edit?usp=sharing)
---