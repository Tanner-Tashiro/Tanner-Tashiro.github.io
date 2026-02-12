---
layout: essay
type: essay
title: "Living Up to the Coding Standards"
date: 2026-02-11
published: true
labels:
  - Coding Standards
  - ESLint
  - VSCode
---

## What is Coding Standards?
When most hear of the phrase "coding standards", me being one of those people, they likely imagine small stylistic rules that code need to abide to such as tabs vs spaces or closing curly braces belonging on its own line. Coding standards felt cosmetic; important for neatness, maybe, but not for actual software quality. But after working with ESLint integrated into VSCode, I've started to see coding standards differently. It is not just about aesthetics, its about clairty. 

### Key Components of Coding Standards
* Naming Conventions: Rules for naming variables, functions, and classes
* Documentation: Best practice for explaining code purpose
* Code Format: Indentation, line length, etc.
* Specific Language Rules

## Using ESLint with VSCode
At the beginning, my screen was filled with red squiggly lines. Unused variables. Improperly formatted arrow functions. Inconsistent spacing. It felt tedious to fix everything, especially when the program technically “worked” already. However, after a few days I noticed that I was getting a lot less of red squiggly lines, I began catching mistakes before ESLint pointed them out. For instance, I would stop leaving unused variables and would begin to properly format arrow functions correctly without really thinking about it.

That said, the experience was not entirely smooth. Setting up the development environment felt unnecessarily complicated. Downloading configuration files, dragging them into the right directories, renaming them correctly. It was easy to forget a step. Sometimes I worried that one small mistake in the setup would cause problems later, and I wouldn’t even know where the issue came from. This part felt tedious and fragile. While coding standards improve development in the long run, the process can be intimidating for beginners.

## "It's Just Style"
It is easy to dismiss coding standards as trivial because many of the rules are technically optional. The program often runs even if some of the coding standards are ignored. But software qualitiy is not just about whether it runs, it is about readability and maintainability. Lets say you are working in a team as a software engineer and you are really good at coding, if no one can understand your code then it sort of becomes irrelevant. Coding is a team effort and everyone on the team needs to understand what each other is doing to do the work more efficiently. After one week with ESLint and VSCode, my view on coding standards has changed. What used to seem trivial to me now feels like it is a foundation to building good coding habits. 
