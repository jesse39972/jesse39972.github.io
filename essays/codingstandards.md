---
layout: essay
type: essay
title: "Software Engineers Hate Him! Easiest Way to Write Better Code Instantly!"
# All dates must be YYYY-MM-DD format!
date: 2023-09-20
published: true
labels:
  - Coding Standards
  - IntelliJ
  - Tips
---
# Standards?

Everyone writes code in a different way. From indent placement to variable names, a single function can look vastly different depending on who wrote it. This is all fine while working alone, but such differences in readability can have adverse effects when working in a group/team setting, the default setting of the workplace. That’s where coding standards come in. Coding standards dictate where to place those indents, what to name those variables, and generally how to format that function so the code from each person looks uniform, making it easier to read. As an example, imagine reading a book where the author writes all their sentences from right to left. Of course the actual content wouldn’t change, but you’d probably spend so much time trying to adjust to such an eccentric style that you wouldn’t even be able to think about the actual subject matter. Such is the case with code. When reading and trying to understand a coworker’s or group member’s code, you should spend more time actually working out what it does then trying to figure out where everything is. That’s what coding standards help facilitate. 


# Shortcuts

Of course, checking a whole hundred, thousand, maybe even ten-thousand lines of code errors, then fixing all those errors, sounds absolutely ridiculous. That’s why coding standards should always be automated by some program. Recently, I’ve used ESLint on IntelliJ, as I’ve been working in JavaScript. Once I configured them together, ESLint will automatically check my code as I write it and notify me about any errors. Then, I have multiple options for going in and fixing said errors. I have the keyboard shortcut F2, which immediately jumps my cursor to the next error. While my cursor is on an error, I can use alt+shift+enter to open up a dropdown menu of potential fixes. I simply select one, press enter, and the error is fixed. However, my absolute favorite way to fix errors consists of typing the command “npm run lint-fix” into the intelliJ terminal. This goes in and fixes all the errors in the entire file automatically. A massive time-saver for any coding project. 


# Having standards is a good thing

While they can seem pointless and a little tedious, learning to work with coding standards pays dividends down the line. Writing more easily readable code is never a bad thing, and leveraging your tools in the correct way can eliminate any tedium from combing through a file for errors. No bad can come from incorporating standards into your code sooner rather than later. 
