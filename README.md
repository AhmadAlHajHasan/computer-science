<div align="center" style="text-align: center">
<img src="http://i.imgur.com/kYYCXtC.png" alt="Open Source Society logo"/>
<h3>Open Source Society University</h3>
<p>
  Path to a free self-taught education in Computer Science!
</p>
<p>
  <a href="https://github.com/sindresorhus/awesome">
    <img alt="Awesome" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg"
  ></a>
  <a href="https://github.com/ossu/computer-science">
    <img alt="Open Source Society University - Computer Science" src="https://img.shields.io/badge/OSSU-computer--science-blue.svg"
  ></a>
</p>
</div>

# Contents

- [Summary](#summary)
- [Community](#community)
- [Curriculum](#curriculum)
- [Code of conduct](#code-of-conduct)
- [Team](#team)

# Summary

The OSSU curriculum is a **complete education in computer science** using online materials.
It's not merely for career training or professional development.
It's for those who want a proper, *well-rounded* grounding in concepts fundamental to all computing disciplines,
and for those who have the discipline, will, and (most importantly!) good habits to obtain this education largely on their own,
but with support from a worldwide community of fellow learners.

It is designed according to the degree requirements of undergraduate computer science majors, minus general education (non-CS) requirements,
as it is assumed most of the people following this curriculum are already educated outside the field of CS.
The courses themselves are among the very best in the world, often coming from Harvard, Princeton, MIT, etc.,
but specifically chosen to meet the following criteria.

**Courses must**:
- Be open for enrollment
- Run regularly (ideally in self-paced format, otherwise running multiple times per year)
- Be of generally high quality in teaching materials and pedagogical principles
- Match the curricular standards of the [CS 2013](CURRICULAR_GUIDELINES.md): Curriculum Guidelines for Undergraduate Degree Programs in Computer Science

When no course meets the above criteria, the coursework is supplemented with a book.
When there are courses or books that don't fit into the curriculum but are otherwise of high quality,
they belong in [extras/courses](extras/courses.md) or [extras/readings](extras/readings.md).

**Organization**. The curriculum is designed as follows:
- *Intro CS*: for students to try out CS and see if it's right for them
- *Core CS*: corresponds roughly to the first three years of a computer science curriculum, taking classes that all majors would be required to take
- *Advanced CS*: corresponds roughly to the final year of a computer science curriculum, taking electives according to the student's interests
- *Final Project*: a project for students to validate, consolidate, and display their knowledge, to be evaluated by their peers worldwide

**Duration**. It is possible to finish within about 2 years if you plan carefully and devote roughly 20 hours/week to your studies. Learners can use [this spreadsheet
](https://docs.google.com/spreadsheets/d/1bkUU90y4rKYQHwY5AR2iX6iiPTrPEsYs75GkCAkrgm4/copy) to estimate their end date. Make a copy and input your start date and expected hours per week in the `Timeline` sheet. As you work through courses you can enter your actual course completion dates in the `Curriculum Data` sheet and get updated completion estimates.
  
> **Warning:** While the spreadsheet is a useful tool to estimate the time you need to complete this curriculum, it may not be up-to-date with the curriculum. Use the spreadsheet just to estimate the time you need. Use the [OSSU CS website](https://cs.ossu.dev) or [the repo](https://github.com/ossu/computer-science) to see what courses to do.

**Cost**. All or nearly all course material is available for free. However, some courses may charge money for assignments/tests/projects to be graded.
Note that both [Coursera](https://www.coursera.support/s/article/209819033-Apply-for-Financial-Aid-or-a-Scholarship?language=en_US) and [edX](https://courses.edx.org/financial-assistance/) offer financial aid.

Decide how much or how little to spend based on your own time and budget;
just remember that you can't purchase success!

**Process**. Students can work through the curriculum alone or in groups, in order or out of order.
- We recommend doing all courses in Core CS, only skipping a course when you are certain that you've already learned the material previously.
- For simplicity, we recommend working through courses (especially Core CS) in order from top to bottom. Some students choose to study multiple courses at a time in order to vary the material they are working on is a day/week. A popular option is to take the math courses in parallel with the introductory courses. Course prerequisites are listed to help you determine if you are prepared for a given course.
- Courses in Advanced CS are electives. Choose one subject (e.g. Advanced programming) you want to become an expert in and take all the courses under that heading. You can also create your own custom subject; the Discord community may provide feedback on your planned subject.

**Content policy**. If you plan on showing off some of your coursework publicly, you must share only files that you are allowed to.
*Respect the code of conduct* that you signed in the beginning of each course!

**[How to contribute](CONTRIBUTING.md)**

**[Getting help](HELP.md)** (Details about our FAQ and chatroom)

# Community

- We have a Discord server! [![Discord](https://img.shields.io/discord/744385009028431943.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/wuytwK5s9h) This should be your first stop to talk with other OSSU students. Why don't you introduce yourself right now? [Join the OSSU Discord](https://discord.gg/wuytwK5s9h)
- You can also interact through GitHub issues. If there is a problem with a course, or a change needs to be made to the curriculum, this is the place to start the conversation. Read more [here](CONTRIBUTING.md).
- Add **Open Source Society University** to your [Linkedin](https://www.linkedin.com/school/11272443/) profile!

> **Warning:** There are a few third-party/deprecated/outdated material that you might find when searching for OSSU. We recommend you to ignore them, and only use the [OSSU CS website](https://cs.ossu.dev) or [OSSU CS Github Repo](https://github.com/ossu/computer-science). Some known outdated materials are:
>  - An unmaintained and deprecated firebase app. Read more in the [FAQ](./FAQ.md#why-is-the-firebase-ossu-app-different-or-broken).
>  - An unmaintained and deprecated trello board
>  - Third-party notion templates

# Curriculum

**Curriculum version**: `8.0.0` (see [CHANGELOG](CHANGELOG.md))

- [Prerequisites](#prerequisites)
- [Intro CS](#intro-cs)
- [Core CS](#core-cs)
  - [Core programming](#core-programming)
  - [Core math](#core-math)
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
  - [Advanced math](#advanced-math)
- [Final project](#final-project)

---

## Prerequisites

- [Core CS](#core-cs) assumes the student has already taken [high school math](https://github.com/ossu/computer-science/blob/master/FAQ.md#how-can-i-review-the-math-prerequisites), including algebra, geometry, and pre-calculus.
- [Advanced CS](#advanced-cs) assumes the student has already taken the entirety of Core CS
and is knowledgeable enough now to decide which electives to take.
- Note that [Advanced systems](#advanced-systems) assumes the student has taken a basic physics course (e.g. AP Physics in high school).

## Intro CS

This course will introduce you to the world of computer science and programming. This course gives you a flavor of the material to come. If you finish the course wanting more, Computer Science is likely for you!

**Topics covered**:
`computation`
`imperative programming`
`basic data structures and algorithms`
`and more`

Courses | Duration | Effort | Prerequisites | Status
:-- | :--: | :--: | :--: | :--:
[Introduction to Computer Science and Programming using Python](coursepages/intro-cs/README.md) | 14 weeks | 6-10 hours/week | [high school algebra](https://www.khanacademy.org/math/algebra-home) | ✅

## Core CS

All coursework under Core CS is **required**, unless otherwise indicated.

### Core programming
**Topics covered**:
`functional programming`
`design for testing`
`program requirements`
`common design patterns`
`unit testing`
`object-oriented design`
`static typing`
`dynamic typing`
`ML-family languages (via Standard ML)`
`Lisp-family languages (via Racket)`
`Ruby`
`and more`

Courses | Duration | Effort | Prerequisites | Status
:-- | :--: | :--: | :--: | :--:
[Systematic Program Design](coursepages/spd/README.md) | 13 weeks | 8-10 hours/week | none | ⬅️
[Class-based Program Design](https://course.ccs.neu.edu/cs2510sp22/index.html) | 13 weeks | 5-10 hours/week | Systematic Program Design, High School Math | -
[Programming Languages, Part A](https://www.coursera.org/learn/programming-languages) | 5 weeks | 4-8 hours/week | Systematic Program Design ([Hear instructor](https://www.coursera.org/lecture/programming-languages/recommended-background-k1yuh)) | -
[Programming Languages, Part B](https://www.coursera.org/learn/programming-languages-part-b) | 3 weeks | 4-8 hours/week | Programming Languages, Part A | -
[Programming Languages, Part C](https://www.coursera.org/learn/programming-languages-part-c) | 3 weeks | 4-8 hours/week | Programming Languages, Part B | -
[Object-Oriented Design](https://course.ccs.neu.edu/cs3500f19/) | 13 weeks | 5-10 hours/week | Class Based Program Design | -
[Software Architecture](https://www.coursera.org/learn/software-architecture) | 4 weeks | 2-5 hours/week | Object Oriented Design | -

### CS Tools
Understanding theory is important, but you will also be expected to create programs. There are a number of tools that are widely used to make that process easier. Learn them now to ease your future work writing programs.

**Topics covered**:
`terminals and shell scripting`
`vim`
`command line environments`
`version control`
`and more`

Courses | Duration | Effort | Prerequisites | Status
:-- | :--: | :--: | :--: | :--:
[The Missing Semester of Your CS Education](https://missing.csail.mit.edu/) | 2 weeks | 12 hours/week | - | -

### Core systems

**Topics covered**:
`procedural programming`
`manual memory management`
`boolean algebra`
`gate logic`
`memory`
`computer architecture`
`assembly`
`machine language`
`virtual machines`
`high-level languages`
`compilers`
`operating systems`
`network protocols`
`and more`

Courses | Duration | Effort | Additional Text / Assignments| Prerequisites | Status
:-- | :--: | :--: | :--: | :--: | :--:
[Build a Modern Computer from First Principles: From Nand to Tetris](https://www.coursera.org/learn/build-a-computer) ([alternative](https://www.nand2tetris.org/)) |  6 weeks | 7-13 hours/week | - | C-like programming language | ⬅️
[Build a Modern Computer from First Principles: Nand to Tetris Part II ](https://www.coursera.org/learn/nand2tetris2) | 6 weeks | 12-18 hours/week | - | one of [these programming languages](https://user-images.githubusercontent.com/2046800/35426340-f6ce6358-026a-11e8-8bbb-4e95ac36b1d7.png), From Nand to Tetris Part I | -
[Operating Systems: Three Easy Pieces](coursepages/ostep/README.md) | 10-12 weeks | 6-10 hours/week | - | Nand to Tetris Part II | -
[Computer Networking: a Top-Down Approach](http://gaia.cs.umass.edu/kurose_ross/online_lectures.htm)| 8 weeks | 4–12 hours/week | [Wireshark Labs](http://gaia.cs.umass.edu/kurose_ross/wireshark.php) | algebra, probability, basic CS | -

### Core theory

**Topics covered**:
`divide and conquer`
`sorting and searching`
`randomized algorithms`
`graph search`
`shortest paths`
`data structures`
`greedy algorithms`
`minimum spanning trees`
`dynamic programming`
`NP-completeness`
`and more`

Courses | Duration | Effort | Prerequisites | Status
:-- | :--: | :--: | :--: | :--:
[Divide and Conquer, Sorting and Searching, and Randomized Algorithms](https://www.coursera.org/learn/algorithms-divide-conquer) | 4 weeks | 4-8 hours/week | any programming language, Mathematics for Computer Science | -
[Graph Search, Shortest Paths, and Data Structures](https://www.coursera.org/learn/algorithms-graphs-data-structures) | 4 weeks | 4-8 hours/week | Divide and Conquer, Sorting and Searching, and Randomized Algorithms | -
[Greedy Algorithms, Minimum Spanning Trees, and Dynamic Programming](https://www.coursera.org/learn/algorithms-greedy) | 4 weeks | 4-8 hours/week | Graph Search, Shortest Paths, and Data Structures | -
[Shortest Paths Revisited, NP-Complete Problems and What To Do About Them](https://www.coursera.org/learn/algorithms-npcomplete) | 4 weeks | 4-8 hours/week | Greedy Algorithms, Minimum Spanning Trees, and Dynamic Programming | -
[Databases: Modeling and Theory](https://www.edx.org/course/modeling-and-theory)| 2 weeks | 10 hours/week | core programming | -
[Databases: Relational Databases and SQL](https://www.edx.org/course/databases-5-sql)| 2 weeks | 10 hours/week | core programming | -
[Databases: Semistructured Data](https://www.edx.org/course/semistructured-data)| 2 weeks | 10 hours/week | core programming | -
[Compilers](https://www.edx.org/course/compilers) | 9 weeks | 6-8 hours/week | none | -

### Core applications

**Topics covered**:
`Agile methodology`
`REST`
`software specifications`
`refactoring`
`relational databases`
`transaction processing`
`data modeling`
`neural networks`
`supervised learning`
`unsupervised learning`
`OpenGL`
`ray tracing`
`and more`

Courses | Duration | Effort | Prerequisites | Status
:-- | :--: | :--: | :--: | :--:
[Software Engineering: Introduction](https://www.edx.org/learn/software-engineering/university-of-british-columbia-software-engineering-introduction) ([alternative](https://github.com/ubccpsc/310/blob/main/resources/README.md)) | 6 weeks | 8-10 hours/week | Core Programming, and a [sizable project](FAQ.md#why-require-experience-with-a-sizable-project-before-the-Software-Engineering-courses) | -
[Software Debugging](https://www.youtube.com/playlist?list=PLAwxTw4SYaPkxK63TiT88oEe-AIBhr96A)| 8 weeks | 6 hours/week | Python, object-oriented programming | -
[Software Testing](https://www.youtube.com/playlist?list=PLAwxTw4SYaPkWVHeC_8aSIbSxE_NXI76g) | 4 weeks | 6 hours/week | Python, programming experience | -
[Fullstack Open](https://fullstackopen.com/en/) | 12 weeks | 15 hours/week | programming| -
[Functional Programming in Scala (Specialization)](https://www.coursera.org/specializations/scala) | 29 weeks | 4-5 hours/week | One year programming experience | -
[Cloud Computing (Specialization)](https://www.coursera.org/specializations/cloud-computing) | 30 weeks | 2-6 hours/week | C++ programming | -
[Internet of Things (Specialization)](https://www.coursera.org/specializations/internet-of-things) | 30 weeks | 1-5 hours/week | strong programming | -
[Modern Robotics (Specialization)](https://www.coursera.org/specializations/modernrobotics) | 26 weeks | 2-5 hours/week | freshman-level physics, linear algebra, calculus, [linear ordinary differential equations](https://www.khanacademy.org/math/differential-equations) | -

## Recommended

### Core security
**Topics covered**
`Confidentiality, Integrity, Availability`
`Secure Design`
`Defensive Programming`
`Threats and Attacks`
`Network Security`
`Cryptography`
`and more`

Courses | Duration | Effort | Prerequisites | Status
:-- | :--: | :--: | :--: | :--:
[Cybersecurity Fundamentals](https://www.edx.org/course/cybersecurity-fundamentals) | 8 weeks | 10-12 hours/week | - | -
[Principles of Secure Coding](https://www.coursera.org/learn/secure-coding-principles)| 4 weeks | 4 hours/week | - | -
[Identifying Security Vulnerabilities](https://www.coursera.org/learn/identifying-security-vulnerabilities) | 4 weeks | 4 hours/week | - | -

Choose **one** of the following:

Courses | Duration | Effort | Prerequisites | Status
:-- | :--: | :--: | :--: | :--:
[Identifying Security Vulnerabilities in C/C++Programming](https://www.coursera.org/learn/identifying-security-vulnerabilities-c-programming) | 4 weeks | 5 hours/week | - | -
[Exploiting and Securing Vulnerabilities in Java Applications](https://www.coursera.org/learn/exploiting-securing-vulnerabilities-java-applications) | 4 weeks | 5 hours/week | - | -

**Advanced** Information Security:

Courses | Duration | Effort | Prerequisites | Status
:-- | :--: | :--: | :--: | :--:
[Web Security Fundamentals](https://www.edx.org/course/web-security-fundamentals) | 5 weeks | 4-6 hours/week | understanding basic web technologies | -
[Security Governance & Compliance](https://www.coursera.org/learn/security-governance-compliance) | 3 weeks | 3 hours/week | - | -
[Digital Forensics Concepts](https://www.coursera.org/learn/digital-forensics-concepts) | 3 weeks | 2-3 hours/week | Core Security | -
[Secure Software Development: Requirements, Design, and Reuse](https://www.edx.org/course/secure-software-development-requirements-design-and-reuse) | 7 weeks | 1-2 hours/week | Core Programming and Core Security | -
[Secure Software Development: Implementation](https://www.edx.org/course/secure-software-development-implementation) | 7 weeks | 1-2 hours/week | Secure Software Development: Requirements, Design, and Reuse | -
[Secure Software Development: Verification and More Specialized Topics](https://www.edx.org/course/secure-software-development-verification-and-more-specialized-topics) | 7 weeks | 1-2 hours/week | Secure Software Development: Implementation | -

## Optional

### Core ethics

**Topics covered**:
`Social Context`
`Analytical Tools`
`Professional Ethics`
`Intellectual Property`
`Privacy and Civil Liberties`
`and more`

Courses | Duration | Effort | Prerequisites | Status
:-- | :--: | :--: | :--: | :--:
[Ethics, Technology and Engineering](https://www.coursera.org/learn/ethics-technology-engineering)| 9 weeks | 2 hours/week | none | -
[Introduction to  Intellectual Property](https://www.coursera.org/learn/introduction-intellectual-property)| 4 weeks | 2 hours/week | none | -
[Data Privacy Fundamentals](https://www.coursera.org/learn/northeastern-data-privacy)| 3 weeks | 3 hours/week | none | -

## Congratulations

After completing the requirements of the curriculum above,
you will have completed the equivalent of a full bachelor's degree in Computer Science.
Congratulations!

What is next for you? The possibilities are boundless and overlapping:

- Pay attention to emerging technologies in the world of software development:
  + Explore the **actor model** through [Elixir](https://elixir-lang.org/), a new functional programming language for the web based on the battle-tested Erlang Virtual Machine!
  + Explore **borrowing and lifetimes** through [Rust](https://www.rust-lang.org/), a systems language which achieves memory- and thread-safety without a garbage collector!

## How to show your progress

[Fork](https://www.freecodecamp.org/news/how-to-fork-a-github-repository/) the [GitHub repo](https://github.com/ossu/computer-science) into your own GitHub account and put ✅ next to the stuff you've completed as you complete it. This can serve as your [kanban board](https://en.wikipedia.org/wiki/Kanban_board) and will be faster to implement than any other solution (giving you time to spend on the courses).
