![NXFury Information Security](https://i.imgur.com/kYYCXtC.png)

<h3 align="center">NXFury Information Security</h3>
<p align="center">
  Path to a free self-taught education in Information Security!
</p>
<p align="center">
  <a href="https://github.com/TheNXFury/NXFuryInfoSec">
	<img alt="NXFury- Information Security" src="https://img.shields.io/badge/NXFURY-Information%20Security-blue.svg">
  </a>
  <a href="https://opensource.org/licenses/MIT">
  	<img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-red.svg">
  </a>
</p>

# Contents

- [Summary](#summary)
- [Community](#community)
- [Curriculum](#curriculum)
- [Code of conduct](#code-of-conduct)
- [Team](#team)

# Summary

The NXFury curriculum is a **complete education in information security** using online materials.
It's not merely for career training or professional development.
It's for those who want a proper, *well-rounded* grounding in concepts fundamental to all information security disciplines,
and for those who have the discipline, will, and (most importantly!) good habits to obtain this education largely on their own,
but with support from a worldwide community of fellow learners.

It is designed based on the Open Source Society's Computer Science curriculum,
and it is assumed most of the people following this curriculum are already vaguely familiar with the world of computing.
The courses themselves are hand selected for the highest quality, but specifically chosen to meet the following criteria.

**Courses must**:
- Be open for enrollment
- Run regularly (ideally in self-paced format, otherwise running multiple times per year)
- Be of generally high quality in teaching materials and pedagogical principles

When no course meets the above criteria, the coursework is supplemented with a book.
When a student wishes to pursue industry, level certifications, the curriculum shall
include opportunities to substitute training for those in place of pre-existing course materials.
When there are courses or books that don't fit into the curriculum but are otherwise of high quality,
they belong in [extras/courses](extras/courses.md) or [extras/readings](extras/readings.md).

**Organization**. The curriculum is designed as follows:
- *Intro CS*: for students to try out CS and see if it's right for them
- *Core CS*: corresponds roughly to the first three years of a computer science curriculum, taking classes that all majors would be required to take
- *Advanced CS*: corresponds roughly to the final year of a computer science curriculum, taking electives according to the student's interests
- *Final Project*: a project for students to validate, consolidate, and display their knowledge, to be evaluated by their peers worldwide

**Duration**. It is possible to finish within about 2 years if you plan carefully and devote roughly 20 hours/week to your studies. Learners can use [this spread
](https://docs.google.com/spreadsheets/d/1bkUU90y4rKYQHwY5AR2iX6iiPTrPEsYs75GkCAkrgm4/copy) to estimate their end date. Make a copy and input your start date and expected hours per week in the `Timeline` sheet. As you work through courses you can enter your actual course completion dates in the `Curriculum Data` sheet and get updated completion estimates.

**Cost**. All or nearly all course material is available for free. However, some courses may charge money for assignments/tests/projects to be graded.
Note that both [Coursera](https://www.coursera.support/s/article/209819033-Apply-for-Financial-Aid-or-a-Scholarship?language=en_US) and [edX](https://courses.edx.org/financial-assistance/) offer financial aid.

Decide how much or how little to spend based on your own time and budget;
just remember that you can't purchase success!

**Process**. Students can work through the curriculum alone or in groups, in order or out of order.
- We recommend doing all courses in Core CS, only skipping a course when you are certain that you've already learned the material previously.
- For simplicity, we recommend working through courses (especially Core CS) in order from top to bottom, as they have already been [topologically sorted](https://en.wikipedia.org/wiki/Topological_sorting) by their prerequisites.
- Courses in Advanced CS are electives. Choose one subject (e.g. Advanced programming) you want to become an expert in and take all the courses under that heading. You can also create your own custom subject, but we recommend getting validation from the community on the subject you choose.

**Content policy**. If you plan on showing off some of your coursework publicly, you must share only files that you are allowed to.
*Do NOT disrespect the code of conduct* that you signed in the beginning of each course!

**[How to contribute](CONTRIBUTING.md)**

**[Getting help](HELP.md)** (Details about our FAQ and chatroom)

# Community

- We have a discord server! [![Discord](https://img.shields.io/discord/744385009028431943.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://example.com) This should be your first stop to talk with other NXFury students. Why don't you introduce yourself right now? [Join the NXFury Discord](https://example.com)
- You can also interact through GitHub issues. If there is a problem with a course, or a change needs to be made to the curriculum, this is the place to start the conversation. Read more [here](CONTRIBUTING.md).

# Curriculum

**Curriculum version**: `0.0.1` (see [CHANGELOG](CHANGELOG.md))

- [Prerequisites](#prerequisites)
- [Intro Programming](#intro-programming)
  - [Introduction to Programming](#introduction-to-programming)
  - [Introduction to Computer Science](#introduction-to-computer-science)
- [Core CS](#core-cs)
  - [Core programming](#core-programming)
  - [CS Tools](#cs-tools)
  - [Core systems](#core-systems)
  - [Core theory](#core-theory)
  - [Core security](#core-security)
  - [Core applications](#core-applications)
  - [Core ethics](#core-ethics)
- [Advanced CS](#advanced-cs)
  - [Advanced programming](#advanced-programming)
  - [Advanced systems](#advanced-systems)
  - [Advanced theory](#advanced-theory)
  - [Advanced information security](#advanced-information-security)
- [Final project](#final-project)

---

## Prerequisites

- [Core CS](#core-cs) assumes the student has already taken [high school math](https://github.com/ossu/computer-science/blob/master/FAQ.md#how-can-i-review-the-math-prerequisites), including algebra, geometry, and pre-calculus.
- [Advanced CS](#advanced-cs) assumes the student has already taken the entirety of Core CS
and is knowledgeable enough now to decide which electives to take.
- Note that [Advanced systems](#advanced-systems) assumes the student has taken a basic physics course (e.g. AP Physics in high school).

## Intro Programming

### Introduction to Programming

If you've never written a for-loop, or don't know what a string is in programming, start here. This course is self-paced, allowing you to adjust the number of hours you spend per week to meet your needs.

**Topics covered**:
`simple programs`
`simple data structures`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Python for Everybody](https://www.py4e.com/lessons) | 10 weeks | 10 hours/week | none

### Introduction to Computer Science

This course will introduce you to the world of programming. Students who have been introduced to programming, either from the courses above or through study elsewhere, should take this course for a flavor of the material to come. If you finish the course wanting more, Information Security is likely for you!

**Topics covered**:
`computation`
`imperative programming`
`basic data structures and algorithms`
`and more`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Introduction to Computer Science and Programming using Python](https://www.edx.org/course/introduction-to-computer-science-and-programming-7) ([alt](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/)) | 9 weeks | 15 hours/week | [high school algebra](https://www.khanacademy.org/math/algebra-home)
[The Missing Semester of Your CS Education](https://missing.csail.mit.edu/) | 2 weeks | 12 hours/week | - 

## Core Curriculum

All coursework under Core Curriculum is **required**, unless otherwise indicated.

### Basics
**Topics covered**:
`functional programming`
`unit testing`
`object-oriented design`
`static typing`
`dynamic typing`
`manual memory management`
`boolean algebra`
`gate logic`
`memory`
`computer architecture`
`and more`

The How to Code courses are based on the textbook [How to Design Programs](https://htdp.org/2003-09-26/). The First Edition is available for free online and includes problem sets and solutions. Students are encouraged to do these assignments.

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[How to Code - Simple Data](https://www.edx.org/course/how-to-code-simple-data) | 7 weeks | 8-10 hours/week | none 
[How to Code - Complex Data](https://www.edx.org/course/how-to-code-complex-data) | 6 weeks | 8-10 hours/week
[Object-Oriented Design](https://www.coursera.org/learn/object-oriented-design) | 4 weeks | 4 hours/week | [Basic Java](https://www.youtube.com/watch?v=GoXwIVyNvX0)
[Design Patterns](https://www.coursera.org/learn/design-patterns) | 4 weeks | 4 hours/week | Object-Oriented Design
[Software Architecture](https://www.coursera.org/learn/software-architecture) | 4 weeks | 2-5 hours/week | Design Patterns
[Build a Modern Computer from First Principles: From Nand to Tetris](https://www.coursera.org/learn/build-a-computer) ([alt](https://www.nand2tetris.org/)) | 6 weeks | 7-13 hours/week | - | C-like programming language
[Build a Modern Computer from First Principles: Nand to Tetris Part II ](https://www.coursera.org/learn/nand2tetris2) | 6 weeks | 12-18 hours/week | - | one of [these programming languages](https://user-images.githubusercontent.com/2046800/35426340-f6ce6358-026a-11e8-8bbb-4e95ac36b1d7.png), From Nand to Tetris Part I
[C For Everyone: Programming Fundamentals ](https://www.coursera.org/learn/c-for-everyone) | 3-4 weeks | 12-15 hours/week | -
[C For Everyone: Structured Programming ](https://www.coursera.org/learn/c-structured-programming) | 2 weeks | 5 hours/week | -
[Operating Systems: Three Easy Pieces](coursepages/ostep/OSTEP.md) | 10-12 weeks | 6-10 hours/week | - | C programming
[Computer Networking](https://www.udacity.com/course/computer-networking--ud436) | 12 weeks | 5-8 hours/week | -

### Core ethics

**Topics covered**:
`Privacy and Civil Liberties`
`and more`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Data Privacy Fundamentals](https://www.coursera.org/learn/northeastern-data-privacy)| 3 weeks | 3 hours/week | none

### Databases 

**Topics covered**:
`REST`
`refactoring`
`relational databases`
`transaction processing`
`and more`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Databases: Modeling and Theory](https://www.edx.org/course/modeling-and-theory)| 2 weeks | 10 hours/week | core programming
[Databases: Relational Databases and SQL](https://www.edx.org/course/databases-5-sql)| 2 weeks | 10 hours/week | core programming
[Databases: Semistructured Data](https://www.edx.org/course/semistructured-data)| 2 weeks | 10 hours/week | core programming


### Core security
**Topics covered**
`Confidentiality, Integrity, Availability`
`Secure Design`
`Defensive Programming`
`Threats and Attacks`
`Network Security`
`Cryptography`
`and more`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Cybersecurity Fundamentals](https://www.edx.org/course/cybersecurity-fundamentals) | 8 weeks | 10-12 hours/week | - 
[Principles of Secure Coding](https://www.coursera.org/learn/secure-coding-principles)| 4 weeks | 4 hours/week | - 
[Identifying Security Vulnerabilities](https://www.coursera.org/learn/identifying-security-vulnerabilities) | 4 weeks | 4 hours/week | -


Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Identifying Security Vulnerabilities in C/C++Programming](https://www.coursera.org/learn/identifying-security-vulnerabilities-c-programming) | 4 weeks | 5 hours/week | -
[Exploiting and Securing Vulnerabilities in Java Applications](https://www.coursera.org/learn/exploiting-securing-vulnerabilities-java-applications) | 4 weeks | 5 hours/week | -
[Cryptography I](https://www.coursera.org/learn/crypto) | 7 weeks | 2.5 hours/week | -



## Advanced Information Security

After completing **every required course** in Core CS, students should choose a subset of courses from Advanced CS based on interest.
Not every course from a subcategory needs to be taken.
But students should take *every* course that is relevant to the field they intend to go into.

### Advanced programming

**Topics covered**:
`debugging theory and practice`
`goal-oriented programming`
`parallel computing`
`object-oriented analysis and design`
`UML`
`large-scale software architecture and design`
`and more`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Architecture 1001: x86-64 Assembly ](https://p.ost2.fyi/courses/course-v1:OpenSecurityTraining2+Arch1001_x86-64_Asm+2021_v1/about) | 8 weeks | 10-15 hours/week | C programming
[Parallel Programming](https://www.coursera.org/learn/scala-parallel-programming)| 4 weeks | 6-8 hours/week | Scala programming
[Compilers](https://www.edx.org/course/compilers) | 9 weeks | 6-8 hours/week | none
[Software Debugging](https://www.udacity.com/course/software-debugging--cs259)| 8 weeks | 6 hours/week | Python, object-oriented programming
[Software Testing](https://www.udacity.com/course/software-testing--cs258) | 4 weeks | 6 hours/week | Python, programming experience

(*) book by Blackburn, Bos, Striegnitz (compiled from [source](https://github.com/LearnPrologNow/lpn), redistributed under [CC license](https://creativecommons.org/licenses/by-sa/4.0/))

### Advanced Information Security

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Web Security Fundamentals](https://www.edx.org/course/web-security-fundamentals) | 5 weeks | 4-6 hours/week | understanding basic web technologies
[Security Governance & Compliance](https://www.coursera.org/learn/security-governance-compliance) | 3 weeks | 3 hours/week | -
[Digital Forensics Concepts](https://www.coursera.org/learn/digital-forensics-concepts) | 3 weeks | 2-3 hours/week | Core Security
[Secure Software Development: Requirements, Design, and Reuse](https://www.edx.org/course/secure-software-development-requirements-design-and-reuse) | 7 weeks | 1-2 hours/week | Core Programming and Core Security
[Secure Software Development: Implementation](https://www.edx.org/course/secure-software-development-implementation) | 7 weeks | 1-2 hours/week | Secure Software Development: Requirements, Design, and Reuse
[Secure Software Development: Verification and More Specialized Topics](https://www.edx.org/course/secure-software-development-verification-and-more-specialized-topics) | 7 weeks | 1-2 hours/week | Secure Software Development: Implementation

## Final project

OSS University is project-focused.
The assignments and exams for each course are to prepare you to use your knowledge to solve real-world problems.

After you've gotten through all of Core CS and the parts of Advanced CS relevant to you, you should think about a problem that you can solve using the knowledge you've acquired.
Not only does real project work look great on a resume, but the project will also validate and consolidate your knowledge.
You can create something entirely new, or you can find an existing project that needs help via websites like
[CodeTriage](https://www.codetriage.com/)
or
[First Timers Only](https://www.firsttimersonly.com/).

### Evaluation

Upon completing your final project:
- Submit your project's information to [PROJECTS](PROJECTS.md) via a pull request.
- Put the NXFury Information Security badge in the README of your repository!
[![NXFury - Information Security](https://img.shields.io/badge/NXFURY-Information%20Security-blue.svg)](https://github.com/TheNXFury/NXFuryInfoSec)

  - Markdown: `[![Open Source Society University - Computer Science](https://img.shields.io/badge/OSSU-computer--science-blue.svg)](https://github.com/TheNXFury/NXFuryInfoSec)`
  - HTML: `<a href="https://github.com/TheNXFury/NXFuryInfoSec"><img alt="NXFury- Information Security" src="https://img.shields.io/badge/NXFURY-Information%20Security-blue.svg"></a>`
- Use our [community](#community) channels to announce it to your fellow students.

Solicit feedback from your NXFury peers.
You will not be "graded" in the traditional sense — everyone has their own measurements for what they consider a success.
The purpose of the evaluation is to act as your first announcement to the world that you are an information security specialist
and to get experience listening to feedback — both positive and negative.

The final project evaluation has a second purpose: to evaluate whether NXFury,
through its community and curriculum, is successful in its mission to guide independent learners in obtaining a world-class information security education.

### Cooperative work

You can create this project alone or with other students!
**We love cooperative work**!
Use our [channels](#community) to communicate with other fellows to combine and create new projects!

### Which programming languages should I use?

My friend, here is the best part of liberty!
You can use **any** language that you want to complete the final project.

The important thing is to **internalize** the core concepts and to be able to use them with whatever tool (programming language) that you wish.

## Congratulations

After completing the requirements of the curriculum above, you will have completed the equivalent of a full bachelor's degree in Computer Science. Congratulations!

What is next for you? The possibilities are boundless and overlapping:

- Look for a job in information security!
- Check out the [readings](extras/readings.md) for classic books you can read that will sharpen your skills and expand your knowledge.
- Join a local hacker meetup (e.g. via [meetup.com](https://www.meetup.com/)).
- Engage in bug bounties to make software more secure (e.g. via [HackerOne](https://www.hackerone.com/)).

![keep learning](https://i.imgur.com/REQK0VU.jpg)

# Code of conduct
[OSSU's code of conduct](https://github.com/ossu/code-of-conduct).

## How to show your progress

1. Create an account in [Trello](https://trello.com/).
1. Copy [this](https://trello.com/b/IScNSzsI/ossu-compsci) board to your personal account.
See how to copy a board [here](https://help.trello.com/article/802-copying-cards-lists-or-boards).

Now that you have a copy of our official board, you just need to pass the cards to the `Doing` column or `Done` column as you progress in your study.

We also have **labels** to help you have more control through the process.
The meaning of each of these labels is:

- `Main Curriculum`: cards with that label represent courses that are listed in our curriculum.
- `Extra Resources`: cards with that label represent courses that were added by the student.
- `Doing`: cards with that label represent courses the student is currently doing.
- `Done`: cards with that label represent courses finished by the student.
Those cards should also have the link for at least one project/article built with the knowledge acquired in such a course.
- `Section`: cards with that label represent the section that we have in our curriculum.
Those cards with the `Section` label are only to help the organization of the Done column.
You should put the *Course's cards* below its respective *Section's card*.

The intention of this board is to provide our students a way to track their progress, and also the ability to show their progress through a public page for friends, family, employers, etc.
You can change the status of your board to be *public* or *private*.

# Credits

The original template for this course generously provided by the [Open Source Society University](https://github.com/ossu/computer-science). Security-related courses provided by OpenSecurityTraining.
