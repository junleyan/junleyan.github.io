---
layout: project
type: project
image: img/aloha-queue/aloha-queue-square.png
title: "AlohaQueue"
date: 2023
published: true
labels:
  - Python
  - GitHub
summary: "A python library that I made to streamline the process of checking appointment availability on AlohaQ."
---

<img class="img-fluid" src="../img/aloha-queue/aloha-queue-rectangle.png">

AlohaQueue is a user-friendly Python library designed to streamline the process of checking appointment availability on AlohaQ for people who do not want to wait another whole month for their appointment and deal with the terrible UX of the AlohaQ web applications. 

## Installation
``` sh
pip install aloha-queue
```   

## Examples
Here is a code snippet utilizing the library to check for appointment availability at Kapalama Driver Licensing Center
```py
from alohaqueue import QueueChecker

# QueueChecker(location, target month, target day, target year)
checker = QueueChecker("KAPA", 12, 12, 2023)

# returns all available appointment dates before 12/12/2023
available_dates = checker.get_available_dates()
# returns all available appointment time on 06/06/2023
available_time = checker.get_available_time("2023-06-06")
```