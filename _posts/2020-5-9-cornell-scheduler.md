---
title: Cornell Scheduler
categories:
- General
- Academic
feature_image: "/assets/scheduler.png"
---

Cornell Scheduler is a tool for Cornell students to build their class schedules. The Scheduler takes user-inputted schedule preferences and then generates and ranks schedules for the user.

<!-- more -->

For my final project for my Functional Programming course, I wrote a Cornell class scheduling tool using OCaml. The 1800-line program builds permutations of all possible schedule configurations based on user-inputted semester and class ID’s. Then, the system deletes all conflicting and duplicate schedules and uses an algorithm to rank them based on user-inputted preferences. The user then has the luxury of viewing the schedules in a polished visualizer displayed to the terminal window.



{% include button.html text="Link" link="https://github.com/JunhoKimLee/scheduler" icon="github" %}