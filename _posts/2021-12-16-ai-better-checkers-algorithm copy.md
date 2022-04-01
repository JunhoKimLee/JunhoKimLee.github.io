---
title: AI Better Checkers Algorithm
categories:
- General
- Academic
feature_image: "/assets/checkers.png"
---

An AI minimax algorithm that incorporates custom-built heuristics to make it smarter with less computational time.

<!-- more -->

For my AI Practicum as part of my Computer Science curriculum at Cornell University, I built an AI checkers program that distinguishes itself from other algorithms based on the fact that it utilizes custom heuristics to be better at the game without sacrificing computational time. The key aspect of this program was its board evaluation function- the function the minimax algorithm used to evaluate how favorable any given board state was for a given player. By using machine learning to tune the weights of a variety of factors (e.g. # of kings, # of moves available, # of vulnerable pieces, etc), we built a program that could reliably beat a "standard minimax algorithm" that had a higher search depth.


{% include button.html text="Link" link="https://github.com/JunhoKimLee/AI_practicum" icon="github" %}