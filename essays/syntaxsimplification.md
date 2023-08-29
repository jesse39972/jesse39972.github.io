---
layout: essay
type: essay
title: "Syntax Simplification"
# All dates must be YYYY-MM-DD format!
date: 2023-08-29
published: true
labels:
  - JavaScript
---


Primitive data types serve as one of the most fundamental building blocks of any programming language. As such, any programmer should get familiar with initializing them. Here are a few examples. To initialize a string in Java, you would type `String name = new String (“data”);` with name being the name and data being the word. Things get weird in C where a string is treated as an array of characters, and you initialize one like `char name = [size]` with size being the length of the word. Looking at both ways, things can look a little busy. In Java, you have to type String twice, use the new keyword, and use (""). In C, you type out char with array brackets. JavaScript offers a better alternative for declaring these important fundamental pieces.   

To initialize a Primitive data type in JavaScript, you use one of three words: let, const, or var. You learn early on that using var is bad practice because it makes the data type global, which means that it can be accessed from anywhere in the program. As your program grows, this can cause issues with the specific data being held by each type. You really only use two words: let and const. In JavaScript, the same string from earlier will be written as `let name = "data";`. You can replace let with const if the value won't change. Seems convenient so far; there are much less words to type. Now, let's say you need an int as well. You would initialize it as 
`const num = 23;` with num being the name and 23 being the number. The data being stored serves as the only real difference between the two. While the names are different for this example, they do not need to be; you could store an int in the same variable being used to currently hold a string, if you have no need for that string anymore of course.     

At first, I found this all very confusing. If I wanted to work on a string, I would sit there trying to remember the correct JavaScript syntax for a string, only to realize there is no special way. You simply declare a var and use quotes for the data. After getting used to it, I realized that is the syntax! Without the need to call a string a `String`, and less words on the line, the name you choose for your variables stand out more. I felt that choosing a good name for each variable became important to help me remember what was being stored in what. With let, const, and potentially the name being the same, one might say that the syntax for a string in JavaScript is simply "". "" proves much easier to both read and type than that long winded declaration found in the first paragraph.    

Though I remain a complete JavaScript beginner, the more I use the language the more I can see this syntax simplification philosophy being put into practice. Objects, loops, and many other mechanics are much easier to both use and understand when compared to other programming languages. All these simplifications lend themself well to cleaner, shorter code that is much easier to read and work with. The real joys of programming come from thinking through complex problems, not struggling with syntax. The easier the syntax of a language is to both read and write, the more of your brain can be devoted to solving said problems. In this aspect, JavaScript performs very well. 
