---
layout: essay
type: essay
title: "Using Design Patterns"
date: 2026-04-30
published: true
labels:
  - Design Patterns
  - Bootstrap 5
  - UI
  - Web Development
---

When I first started learning UI development, writing HTML felt like assembling furniture without instructions. You have all the pieces: divs, classes, styles, but no clear sense of how they should connect together. 
At first, it seemed simple compared to languages like Java, but as my pages grew more complex, I realized that without structure, even simple designs can become messy, repetitive code.

That’s when I ran into the idea of design patterns.

Design patterns, at their core, are reusable solutions to common problems in software design. They are not code you copy and paste, but rather ways of organizing code so that it is maintainable, scalable, and understandable. 
In a way, they are like architectural blueprints. Instead of reinventing how to build a door every time, you follow a pattern that works, and adapting it slightly depending on your goal.

In UI development, frameworks like Bootstrap 5 embody these patterns. At first glance, Bootstrap just looks like a collection of predefined classes. But underneath, it is a system of design decisions that solve 
recurring problems: how to structure layouts, how to maintain consistency, and how to ensure responsiveness across devices.

## What and Why use UI Framework

Initially, Bootstrap felt overwhelming. There were so many class names and layout rules that it seemed easier to just write raw HTML. However, I began to notice that the framework had this consistent pattern of design:

* **Consistency**: Instead of manually styling every element, Bootstrap provides standardized components that make my code easier to understand.
* **Responsive Design**: Its grid system acts as a layout pattern that adapts content across screen sizes.
* **Time Efficiency**: By relying on established patterns, I spent less time debugging and more time building.

What I once saw as “extra complexity” was actually structure—structure that prevented chaos in larger projects.

## My Experience with Design Patterns in my Final Project

My final project, a Manoa Study Space application, made design patterns feel much more real. The goal of the app was simple: allow users to add their own study spots around UH Mānoa through a form, and then display those locations as organized cards on the page. But behind that simplicity was a lot of structure that relied on patterns.One of the most obvious patterns I used was a reusable component pattern through study space cards. Every time a user submitted a new location, the application didn’t create a completely new layout—it reused the same card structure. Each card followed a consistent format (title, description, location details), which made the interface predictable and easy to read. 
Instead of solving the display problem repeatedly, I solved it once and reused that solution.

Another important pattern appeared in how user input was handled. The add form acted as a clear input-processing-output flow: users provide data, the system processes it, and then the result is displayed dynamically as a new card. Even though the implementation was simple, the structure made the application easier to expand and debug. I also relied heavily on Bootstrap’s grid system to organize the study space cards. This created a consistent layout pattern where cards automatically adjusted based on screen size. This reinforced the idea that good design patterns don’t just solve one problem—they scale across different scenarios.

Finally, consistency played a major role. By using the same styling conventions, spacing, and alignment throughout the app, the entire project felt unified. This reflects a broader design principle: when patterns are applied consistently, the user experience becomes smoother and the code becomes easier to maintain.

## Conclusion
Working on this project helped me realize that design patterns are not just abstract concepts discussed in interviews. They are practical tools that guide how applications are built. In my case, patterns like reusable components (study space cards), structured input handling (the add form), and responsive layouts (Bootstrap grid) allowed me to turn a simple idea into a clean, scalable application.

