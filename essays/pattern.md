---
layout: essay
type: essay
title: "Are Design Patterns Necessary"
# All dates must be YYYY-MM-DD format!
date: 2024-12-05
published: true
labels:
  - Design Pattern
---

<img width="600px" class="rounded float-start pe-4" src="../img/pattern/design-patterns.jpg">


# How I Came to Appreciate Design Patterns
When I first started writing code, my approach was pretty naive. I’d open Visual Studio Code, write a bit of logic, and watch it run. If my program produced the right result, I’d consider it a win and move on. I wasn’t overly concerned with structure or long-term maintainability. I just wanted to solve the immediate problem, and it felt liberating. No complex guidelines, no heavy frameworks, just me, the code, and a quick sense of accomplishment. But as my projects grew, so did the complexity. Suddenly, making a small change in one corner of the codebase would create a domino effect of strange bugs somewhere else. I found myself wrestling with a tangle of functions and variables, and the carefree coding style I loved began to feel like a liability.

# My First Encounter: Model-View-Controller (MVC) Framework
Before taking the software development class at my university, I never even knew about the existence of design patterns but while working on the final projects for that class, I had the opportunity to familarize myself with one of the concept which is the Model-View-Controller framework. For that project, we seperated our NextJS applications into three distinct parts: the "Model" which manages data through Prisma in this projects, the "View" which handles the user interface rendering, and the "Controller" which acts as the intermediary, receiving user input and directing the Model to update data while also updating the View to reflect those changes.