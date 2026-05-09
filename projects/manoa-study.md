---
layout: project
type: project
image: img/manoa-study.png
title: "ICS 314 - Manoa Study Spaces Project"
date: 2025
published: true
labels:
  - Bootstrap 5
  - Nextjs
  - UI Development
  - HTML
  - React
summary: "An introductory Unity project focused on learning core game development concepts through building a small games."
---

## Building a Collaborative Campus Study Space Platform

UH Manoa students are constantly searching for good places to study. Some want quiet spaces for individual work, while others look for collaborative environments where they can meet classmates and prepare for exams together. Despite the number of study locations available on campus, students often rely on word of mouth, group chats, or trial and error to find spaces that match their needs.

To address this problem, my team developed a web application that allows students to discover and share study spaces around campus while also creating and joining study groups. The goal of the project was to make studying more social, organized, and accessible for students.

## Project Overview

The application functions as a community-driven platform where users can:

* Add new study locations around campus
* View study spaces submitted by other students
* Create study groups for specific courses or exams
* Join existing study groups
* Leave reviews to comment on other's spaces

We designed the platform to encourage collaboration between students while also helping newcomers discover useful campus resources they may not otherwise know about. One of the most important aspects of the project was creating a intuitive user experience. Since students would likely use the application quickly between classes or during busy study sessions, we focused on making navigation simple and efficient.

## My Contributions

During this project, I contributed to both the frontend development and the overall design of the application. I worked on implementing features that allowed users to submit and view study spaces, as well as improving the layout and usability of the interface.

Some of my specific contributions included:

* Developing user interface components such as the navbar, space cards, and the landing page.
* Creating the listings of both the study spaces and study groups
* Creating the forms for submitting study spaces and study groups
* Connecting frontend pages with backend data
* Debugging issues related to displaying and updating information

I also collaborated with my teammates using GitHub for any issues that may show up in main. Working in a shared repository environment helped us organize development tasks, review each other’s work, and avoid conflicts when multiple people were contributing simultaneously.

### Landing Page
The landing page is presented to users when they visit the top-level URL of the site.

<img src="/img/landing-page.png" width="700">

### Listing Page
Displays all created study spaces from the Add Space form.

<img src="/img/listing-page.png" width="700">

### Add Space Form
This form allows users to add a study space with information such as the name, image, quiet level, capacity, and amenities.

<img src="/img/add-space.png" width="700">

### Study Group Page
Displays all available study groups and includes filters to sort groups based on availability.

<img src="/img/study-group-page.png" width="700">

## Challenges and Lessons Learned

One of the biggest challenges during development was coordinating work across multiple contributors. In team projects, even small changes can unintentionally affect another person’s code when communication is limited. Our workflow often involved each team member working independently on separate tasks, while one person handled merging changes into the main branch. This frequently led to merge conflicts and integration issues. Looking back, many of these problems could have been reduced through more consistent communication, better coordination between team members, and regularly updating our branches from the main branch before making new changes.

Another challenge involved project delays caused by technical difficulties and incomplete tasks. Early in development, several team members struggled with configuring the database connection and deploying the application through Vercel. These issues slowed progress significantly and made collaboration more complicated. For example, the “add spaces” feature, which was one of the core functionalities needed to establish the foundation of the application, was not fully completed until the beginning of Milestone 2. I also noticed that some team members were not really completing the tasks they were assigned by their deadlines and this severly limited what we were able to accomplish for this project. This experience highlighted the importance of establishing a stable development environment early and ensuring that all team members are comfortable with the project setup before major development begins.

Through this experience, I gained a stronger understanding of:

* Collaborative software development
* GitHub workflow and version control
* Frontend and backend integration
* User-centered interface design
* Debugging and iterative testing

More importantly, the project showed me how software engineering extends beyond simply writing code. Successful applications require communication, planning, adaptability, and attention to the user experience.

## Reflection

This project was valuable because it focused on solving a real problem students face every semester. Rather than building a purely theoretical application, we created something practical that could improve how students connect and study together on campus.

The experience also strengthened my confidence working in a development team. I learned how to contribute effectively in a collaborative environment, respond to feedback, and improve software through multiple iterations.

If I continue developing this application in the future, I would like to add features such as:

* Real-time study group notifications
* Interactive campus maps
* Scheduling and calendar integration
* Filters for the amenities

Overall, this project helped me grow both technically and professionally, and is one of the most meaningful software engineering experiences I have completed so far.
