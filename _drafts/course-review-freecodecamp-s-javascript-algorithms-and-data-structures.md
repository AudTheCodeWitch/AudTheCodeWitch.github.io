---
layout: post
date: 2020-07-20 09:34:03 -0600
title: 'Course Review: FreeCodeCamp''s JavaScript Algorithms and Data Structures'

---
Last week, I completed freeCodeCamp's JavaScript Algorithms and Data Structures course.

![Audrea's JS Algorithms and Data Structures Certificate](/uploads/fcc-js-algorithms-cert.jpg)

## The Curriculum

Let's break this course down. It is divided into 9 modules, plus a section of 5 projects at the end. Like the Responsive Web Design course ([read my review](https://www.codewitch.dev/course_review_freecodecamps_responsive_web_design "Course Review: FCC's Responsive Web Design")), each lesson has a quick readme with a coding exercise. To advance to the next lesson, your code must pass a set of predefined tests.

### Module 1: Basic JavaScript

Don't let the 110 lessons intimidate you. This section starts with the very basics, such as how to add comments to your code, and builds from there. Being already familiar with the majority of the concepts in this module, the lessons progressed quite quickly. If you are already familiar with JavaScript, this section may not be necessary; however, I found it to be a helpful review, particularly when looking at iteration.

### Module 2: ES6

This 31-lesson module explores ES6, the "most recent standardized version" of JavaScript, which came out in 2015. This section breaks down arrow functions, classes, modules, and more. 

I enjoyed practicing object destructuring, like in the example below:

```JavaScript
// Create a module object with 'name' and 'lessons' keys.
const module = { name: 'ES6', lessons: 31 };
    
// Use object destructuring to create variables using the object keys.
// The variable equals the key's value.
const { name, lessons } = module;
  // This is the same as:
  // const name = module.name;
  // const lessons = module.lessons
    
console.log(name);
  // 'ES6'
    
console.log(lessons);
  // 31
```

This section also explained how to import and export your code for reuse. I appreciated the four lessons covering JavaScript Promises, as well.

### Module 3: Regular Expressions

I was a bit terrified to begin this 33-lesson module. Regex has always mystified me, and I thought this section would be no exception. 

Perhaps not surprisingly, FreeCodeCamp did a great job explaining how to use `.match()` and `.test()`, as well as all sorts of Regex, to manipulate your JavaScript code. 

While I wouldn't say Regex is _easy_ for me, this course, coupled with [Regex101](https://regex101.com/ "Regex 101"), certainly made it _easier_. I now recognize when and how to use Regex, and I no longer balk at it.

### Module 4: Debugging

For me, this was the least helpful module in the course. The 12-lesson section on debugging did not do much more than explain how to use `console.log()` to check for common code errors. 

### Module 5: Basic Data Structures

This module is short and sweet, at only 4 lessons. It explains how to create a media query and make images and other elements responsive, but I feel like this was the weakest section of the course.

In the future, I would love to see freeCodeCamp expand this section to discuss mobile-first vs desktop-first design approaches. A few lessons discussing important media query break-points would also be awesome. To supplement the section as it currently stands, I recommend reviewing the [Media Queries](https://www.w3schools.com/css/css_rwd_mediaqueries.asp) section of w3schools' Responsive Web Design module.

### Module 6: Basic Algorithm Scripting

The final two modules cover some more advanced aspects of CSS. This 17-lesson section explains how to use `flexbox` to position elements within a container. While freeCodeCamp covers `flexbox` pretty well, I still find it to be a little confusing, especially for beginners. If you struggle with this section, I suggest reading [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) by CSS-Tricks. Their explanations and illustrations, coupled with freeCodeCamp's exercises, really solidified this concept for me.

### Module 7: Object Oriented Programming

The final module is 22 lessons long, and covers `grid`, another tool for creating complex web layouts. Having used `grid` in previous projects (not to mention countless Neopets pages), I found this module to be a solid review. Learners create basic grids using `grid-template-rows` and `grid-template-columns`. After learning to adjust these grids, users then learn to align items within the grid as well as use the ever-helpful `grid-template-areas`.

### Module 8: Functional Programming

wfwalfjwelfjwewefjweoifjweaofjw

### Module 9: Intermediate Algorithm Scripting

## The Projects

To complete this course, learners must create 5 separate pages, each with unique user stories to guide the design. FreeCodeCamp provides a CodePen.io example for each project, but they also give a huge amount of creative freedom.

I make no claims to being a designer. However, after quickly getting the tests to pass, I usually spent a few more hours playing with the CSS, tweaking things here and there, and trying new techniques learned throughout this course.

I chose to complete these projects using my own editor (RubyMine) instead of CodePen. I also created a GitHub repository for each project to track my code changes. Additionally, I used these projects as an opportunity to practice deploying sites to Heroku.

Here are my submissions for the 5 projects. Click the links to see them in action. Note that any forms don't actually submit anywhere.

## Final Thoughts

Overall, I think freeCodeCamp has created an excellent course. Did it take me 300 hours to complete? Definitely not. Would it take that long for an absolute beginner? Possibly. Either way, the Responsive Web Design course is a solid review for experienced devs, and a great introductory course for code newbies.

If you have ANY interest in code or web design, I highly recommend starting with [freeCodeCamp](https://www.freecodecamp.org/learn/).