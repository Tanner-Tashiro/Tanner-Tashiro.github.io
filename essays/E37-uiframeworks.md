---
layout: essay
type: essay
title: "The Power of UI Frameworks"
date: 2026-02-25
published: true
labels:
  - Bootstrap 5
  - Framework
  - UI
---

When I first started learning UI development, I thought that writing HTML seemed straightforward. It seemed simpler than Java and just overall easier to understand. However, I noticed how large your code can get if you want very specific things to be certain ways. There are so many things that you can do with HTML that can be a bit overwhelming to a new learner: padding, text, color, etc. 

## What and Why use UI Framework
At first glance, UI frameworks can feel complicated. They introduce new classes, conventions, and sometimes, a verbose way of doing things that raw HTML could accomplish. However, frameworks can:

* Consistency: Pre-designed components that ensure page looks polished
* Responsive Design: Modern websites must adapt to screens of all sizes. Bootstrap’s grid system allows for automatic adjustment to different view sizes.
* Time Efficiency: Using a framework reduces the time spent debugging layout issues or inconsistencies. For a professional environment, this can mean faster development and fewer errors.

## My Experience with Bootstrap 5
Initially, it was frustrating to learn the class conventions and grid system. There are so many things that would take long to memorize, so having to find what I wanted to do in the documentation was a bit tedious. But once I got the hang of it, I realized the payoff. I could create a responsive, consistent page in a fraction of the time it would have taken with only raw HTML. 

### Navigations with Navbars
One of the WODs tasked me to make several varying navbars so I could get the hang of designing. Navbars, or navigation bars, are one of the clearest examples of why UI frameworks like Bootstrap 5 are so valuable. A website’s navigation is more than just a set of links, it guides users through the site and shapes their experience. Building a responsive and visually consistent navbar allows for users to easily navigate the website and engage with content. Bootstrap 5 simplifies this with prebuilt classes that handle responsive behavior, spacing, color theming, etc. attributes automatically. In my WODs, using a Bootstrap navbar allowed me to quickly implement a fully responsive menu without spending hours debugging layout issues, enabling me to focus on content and overall design consistency. 

Here is an example of practicing Bootstrap 5 Frameworks:
```
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container">
    <a class="navbar-brand" href="#">
      <img src="https://courses.ics.hawaii.edu/ics314s26/morea/ui-frameworks/experience-bootstrap-navbars-aloha-beer-logo.png" width="110" alt="Aloha Beer Logo">
      </a>

      <div class="nav justify-content-center mx-auto">
        <a class="nav-link" href="#">Locations & Menus</a>
        <a class="nav-link" href="#">Events</a>
        <a class="nav-link" href="#">Brewery</a>
        <a class="nav-link" href="#" style="color:#EDC601;">Shop</a>
      </div>

      <div class="nav justify-content-end">
        <a class="nav-link" href="#">Account</a>
        <a class="nav-link" href="#"><i class="bi bi-search"></i></a>
        <a class="nav-link" href="#"><i class="bi bi-cart3"></i></a>
      </div>
    </div>
</nav>
```
## Conclusion
UI frameworks like Bootstrap 5 are more than just shortcuts for styling; they are powerful tools that help developers create professional, consistent, and responsive websites efficiently. While the learning curve can feel steep at first, the benefits in maintainability, scalability, and time saving make the effort worthwhile. Frameworks provide ready made components that handle many different scenarios, allowing developers to focus on design and functionality. My experience with Bootstrap 5 has shown that once you understand the rules, you can build web pages that are both visually appealing and user-friendly in a less time than it would take with raw HTML alone. 


