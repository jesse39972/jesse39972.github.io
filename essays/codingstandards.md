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

Everyone writes code in their own way. From indent placement to variable names, the same function can look vastly different depending on who wrote it. This may not affect people working on their own, but such differences in readability can have adverse effects when working in a group or team setting, the setting where software engineering typically takes place. That’s where coding standards come in. Coding standards dictate where to place those indents, what to name those variables, and how to format those functions so each person's code looks uniform and readable. Since all group members will be continually working with and iterating on each other's code while building software, readable code takes a much higher priority than usual. As an example, imagine reading a book where the author writes all their sentences from right to left. Of course the actual content wouldn’t change, and that author may even be a solid writer, but you’d probably spend so much brainpower trying to actually read the words that you wouldn’t even be able to think about the deeper themes present in the story. Such is the case with code. Someone could come up with an absolutely elegant solution to a problem, but if they never press enter and their entire program looks like one big block of text with semicolons and parentheses everywhere, you can't even appreciate the solution, let alone understand it. When building software, it's important to spend your valuable brainpower actually thinking about the problems you set out to tacke and how to optimize the solutions for them, rather than trying to decipher a mess of text. That’s what coding standards help facilitate. 


# Standard Shortcuts?

Of course, checking a whole hundred, thousand, maybe even ten-thousand lines of code for errors, then fixing all those errors, sounds absolutely ridiculous. That’s why enforcing coding standards should always be automated in some way. Recently, I’ve used ESLint, the standard code analysis tool for JavaScript, while working in IntelliJ. After some tinkering with some settings, ESLint will automatically check my code as I write it and notify me about any errors. Then, IntelliJ offers several useful keyboard shortcuts for deaing with said errors. I have the keyboard shortcut F2, which immediately jumps my cursor to an error. While my cursor is on the error, I can use F2 again to jump to the next one, if it exists. Once on an error, Alt+Enter opens up a dropdown menu of potential fixes. I simply select one using arrow keys, press enter, and the error is fixed. That being said, the holy grail of shortcuts can be accessed from the terminal. While in the IntelliJ terminal, typing the command “npm run lint-fix” fixes all the errors in the entire file for you automatically. I can't imagine coding without it. 


# Standards.

While they can seem pointless and a little tedious, learning to work with coding standards pays dividends down the line. Writing more easily readable code is never a bad thing, and leveraging your tools in the correct way can eliminate any tedium involved in combing through a file for errors. Only good can come from incorporating standards into your code sooner rather than later. 
