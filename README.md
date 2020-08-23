# WIP

This document is going to get updated over time, not often, but as I learn more I can share more. A lot of this is from information I've gathered over the years and my attempt at giving you some resources on where to start. Especially if you're unsure where to look because programming is broken up into different areas which can be confusing especially if you're looking at web development stuff when you're trying to get into game development.

# Common Tools

Programming Tools are essential for writing code. You'll need a syntax editor or an IDE which is a syntax editor that helps you auto complete common tasks and helps you identify issues before they happen. When starting out you'll most likely always learn to use a syntax text editor.

**Common Editors**

- [Visual Studio Code](https://code.visualstudio.com/) (very popular)
- [Notepad++](https://notepad-plus-plus.org/) (Some colleges require it for teaching)

I'm going to leave IDE's out of this section for now because IDE's are most of the time language dependent. For example PHPStorm is a (paid) IDE that is a staple in the web development industry currently.

**Source Code Management & Repository Management Sites**

- https://git-scm.com/
- https://github.com
- https://bitbucket.org
- https://gitlab.com

One thing you'll probably need to learn eventually is how to use git. It's not the easiest thing to jump in right away, but definitely once you start managing your head around programming [look into git](https://www.freecodecamp.org/news/an-introduction-to-git-for-absolute-beginners-86fa1d32ff71/).

# Resources

**Help Forums**

- [Reddit](https://www.reddit.com/r/learnprogramming/) - judgement free community
- [Stackoverflow](https://stackoverflow.com/) - like a wiki of common programming questions across all languages and issues that people ask. A bit more strict, so be careful with asking questions & always search first.

**Online Free/Paid Course sites**

- https://www.freecodecamp.org/ - free?
- [Khan Academy](https://www.khanacademy.org/computing/computer-programming) - free
- [edX](https://www.edx.org) - free from MIT
- [Udemy](https://udemy.com) - paid

**Freelance Job Sites**

- https://upwork.com
- https://www.freelancer.com
- https://guru.com
- https://forums.digitalpoint.com/#buy-sell-or-trade.32 BST - old school, grey area, lot of overseas work. 

# Web Development 

## Introduction

When it comes to web development there's 4 different types of things you can learn, but not necessarily need to learn. Such as markup language (HTML), styling sheet language (CSS), scripting language (Javascript aka JS) and then general purpose languages (such as PHP, Ruby on Rails (RoR), Python, Javascript [using NodeJS+Libraries such as React], etc...) which process & handles data from and to the web browser that you can't visually see.

(And while I did list a specific amount of general purpose languages, you are not limited to just those languages to make websites as there's also stuff like csharp [C#] using Asp.NET. There's tons of different languages that over the years you may gravitate towards because it meets your programming style of writing, but when it comes to popularity then PHP, JS, Python, ASP.NET and even RoR are considered dominating the web space. Now if you've ever created a wordpress blog then you've seen PHP in the wild without even realizing it)

Becoming a web developer, you can be split into two categories. A frontend developer (consisting of HTML/JS/CSS) or a backend developer (PHP, Node(JS), Python, ASP, Ruby(On Rails), etc...) or both which is called a full stack developer who can develop for both the client side (browser/frontend) or server side (backend). I started out as a frontend web developer where I started learning how to use javascript. How javascript interacts with the HTML (DOM) and being able to remove/add/modify and animate different parts of a web page. In order for me to fully understand how HTML and JS interacted I had to learn how to put a web page together which is the visual part of a website that you see when you visit facebook.com or any webpage for that matter. If you're old enough you may have been introduced to HTML & CSS from myspace way back when you could customize your page with html & css.

As time went on I wanted to understand how data from the webpage was being processed to the server's database (storage) and I learned about the backend and what happens when a form gets submitted. Which teaches you about how form data is sent with most page requests. For instance a redirect after hitting the login button on facebook takes that data from that page request and processes it against the server database to check if you're using the correct password. You don't necessarily see that from the browser because it's all processing as the page loads via one of the backend languages that site decided to use (such as PHP, etc..), but when you complete or fail a login the frontend web page will visually change to indicate if you successfully logged in or not just to give you a real world example of how to visualize what may be happening. 

Not all websites need a backend, but all backends have a frontend lol. Meaning, you can have basic web pages that do absolutely nothing but show information with just HTML/CSS and a bit of javascript. But if you want a web page to have user interaction or handle data 9 times out of 10 there will be some form of backend code being used to do that.

I was kind of debating on how to write this and further sections, but I think giving you a surface introduction to web development in this case then telling you how to start, where to go and how to learn is the best approach for sending you in the right direction because I'm not a teacher, but I'm good at explaining how to get into something.

## How I started

I started doing web development by learning frontend development first which consists of:

- Learning what HTML is and how to structure an html page
- Learn what CSS is and how CSS can transform your HTML into beautiful web pages. You won't make beautiful web pages starting out, but being able to change the color/alignment/etc... using CSS allows you to understand the properties of your HTML.
- Learning how to manipulate the HTML using javascript such as changing the text inside an html tag from one word to another word. Deleting an html tag from the page when you press a button.

After learning the basics I gave myself a simple project to create. For you it could be anything, for me I went a simple route and made an "About Me" page that had information aobut me and you could even have an image somewhere. Then with javascript you can show/hide a section to show more. The idea of creating starter projects for yourself is to help you improve your craft so you can learn the basics and remember the basics. You don't necessarily want to push yourself too far without understanding the simple stuff which to some people is the boring part. Everyone wants to jump into crazy animations and image carousels. While all that stuff is fun, you have to start small and gradually move up at your own pace.

As time went on I wanted a little more from my web pages, I wanted to understand how people created those guest books where people could randomly leave messages on your page. Now this is where backend development kicks in which is a steeper curve than frontend. Because first you have to find a language you like of the popular languages. For me PHP was the first language I chose because of the resources I could find on it. But if you want you can look into Ruby On Rails, Python, CSharp using ASP.NET or Node(JS). The last two are a bit more complex than the others in my opinion, but it really depends on how fast you catch on.

So I had to:

- Learn what PHP was and how to get started
- Learn about variables, variable types, type inference, operators, functions, control flow/structures, classes (OOP, object oriented programming), essentially the overall basics of php
- Learn how to make it interact with my web pages
- Learn how to submit a form and display the contents of that form on a web page (if we really think about it a lot of web pages are about delivering content to the browser and submission form handling [eg.: login, saving, etc...])
- Learn about databases and how php interacts with databases

When learning a backend server language for web development there's a lot that goes into that process such understanding how to setup PHP on your computer, or a webserver. 

Just like with the frontend, I started little by little and learned about the PHP basics; the language itself. How it works, how to execute code, how to setup PHP on my computer. Then I started diving into more smaller things like what is a class and what is object oriented programming. Then I started to come up with small challenges and build little web applications like submitting text on a form and displaying it. Simple, but you have to start somewhere. Or calculating two values and displaying the result from the user.

## Where to start

Now where to start is very subjective and with there being millions of free resources online it's kind of hard to tell someone where to look. My only suggestion is if you start with google be sure to check multiple sources on things you learn in case tutorials are outdated or just not what you're supposed to do. Since programming is a thing everyone wants to do, bloggers tend to flood the internet with misinformation specifically to mess up SEO so they can flip a blog for profit leaving people that actually want to learn confused or misguided.

- [Mozilla (firefix developers) created an absolute beginners guide to HTML/JS/CSS](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web)
- [PHP For Absolute Beginners](https://www.youtube.com/watch?v=yXzWfZ4N4xU) - PHP is a bit tricky, I think video tutorials might be easier when learning PHP for the first time, but eveyrone isn't a visual learner so I'd recommend starting with a book I bought years ago
- [CodeAcademy](https://www.codecademy.com/learn/learn-php) - my introduction to PHP is very much different than things are today, they have a fairly okay/introduction to PHP.

## Resources

This section is more about showing you a few common things to search & places on where to find the needed resources or answers to things you need to know about. Also, I'll explain how you can simplify your programming question to garner better results in search engines.

**Common search terms to research for web development**

- What is frontend web development (replace frontend with backend for backend results)
- How to get started with (HTML/Javascript/CSS/ETC)

**Tools/Software**

- https://3v4l.org/ - allows you to test PHP in the browser without saving anything on your pc (good for learning the very basics)
- https://codepen.io/ - allows you to test/run JS/HTML & CSS in the browser w/out saving anything on your pc (good for learning the very basics)
- [Visual Studio Code](https://code.visualstudio.com/) - free
- [Sublime Text](https://www.sublimetext.com/) - semi-free
- [PHPStorm](https://www.jetbrains.com/phpstorm/) - paid
- [WebStorm](https://www.jetbrains.com/webstorm/) - paid

**Other**

- https://phptherightway.com/ once you get familiar with PHP, take a look at this for modern takes on PHP (things have changed a lot over the years)



# Game Development

TBD 

## Where to start

TBD

## Resources

TBD

# App Development

TBD 

## Where to start

TBD

## Resources

TBD

# Software Development

TBD 

## Where to start

TBD

## Resources

TBD