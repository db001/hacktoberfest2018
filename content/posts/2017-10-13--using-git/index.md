---
title: Using Git 
cover: photo-1451324119451-db0ac857463c.jpg
category: "hacktoberfest"
author: wwcodepdx
---

![unsplash.com](./photo-1451324119451-db0ac857463c.jpg)

### What is Git?

Before I can answer that question, I need to answer another: **What is Version Control?**

I'll rely on the people at [Atlassian](https://www.atlassian.com) to answer that:


*"Version control systems are a category of software tools that help a software team manage changes to source code over time. Version control software keeps track of every modification to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members."*

So, **what is git?**  Git is the most widely used modern version control system today.  That's it.  

Rather than talk about what it can do, the best way is to start using it.  So let's dive in...

It's very easy to get overwhelmed when first trying git, some of the commands aren't intuitive and it can be difficult to learn. However keep trying and using it regularly, even just to back up your own code, and it will get easier.

There are several ways to interact with git on your computer.  I'll be using the terminal (or command line).  Any commands that I type will be shown as:

`example code`

Firstly you need a free [Github](www.github.com) account.  Github is simply somewhere to keep that central code store, in what are call **repositiories** (or **repo** for short).  Others are available such as [Bitbucket](https://bitbucket.org/) and [SourceForge](https://sourceforge.net/).

Once you're signed up, create a new repository, give it a name, tick the box that says *Initialize this repository with a README* and create your first repo.  It only has your README file at the moment.

To download the repo to your computer, also known as cloning, click the green *Clone or download* button.  This will give you link to copy by clicking the little clipboard icon next it - I'll use *https://github.com/user/example.git*.  Then open your terminal and type

`git clone https://github.com/user/example.git`