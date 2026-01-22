---
layout: essay
type: essay
title: "My Journey so Far in Typescript"
date: 2026-01-22
published: true
labels:
  - E10
  - Typescript
---

## What do I think about Typescript so far?
My experience with TypeScript so far has been enjoyable. I have some personal experience with coding in Java using the Eclipse IDE, C++, and C. Compared to those languages, I see TypeScript as an extension of Java OOP concepts (classes, inheritance, etc.), but I find TypeScript easier to read and write. After taking the FreeCodeCamp ES6 course, I became familiar with JavaScript functionality such as arrow functions, destructuring, promises, and more, which made learning TypeScript smoother.

### WODs 
In the first couple of weeks I have had a lot of practice doing the WODs which allowed me to learn the syntax of the language. This hands-on, repetitive practice is challenging, but it helps me to understand how to efficiently and effectively code. While the timed nature of WODs can be a bit stressful, completing them in this manner helps build my proficiency in coding under pressure. 

Here is an example of practicing TypeScript functions and type saftey:
```
function isUnique(target: string): boolean {
  const chars = target.split("");

  for (let i = 0; i < chars.length; i++) {
    for (let j = i + 1; j < chars.length; j++) {
      if (chars[i] === chars[j]) {
        return false;
      }
    }
  }

  return true;
}
  
console.log(isUnique('abcde'));
console.log(isUnique('abcdea'));
```


## What do I think about Typescript from a software engineering perspective?
I think that Typescript, through the lens of software engineering, can be very effective an beneficial. Typescript uses static typing which can be useful in catching errors and making the code more readable. Additionally, Typescript's structure (interfaces, generics, modules) can make it effective in projects with multiple developers due to its modularic nature. Overall, from a software engineering perspective, TypeScript is a good programming language because it encourages clean and maintainable code, which is essential in software engineering.
