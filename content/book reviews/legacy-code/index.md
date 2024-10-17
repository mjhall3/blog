+++
title = "Book Review: The Legacy Code Programmer's Toolbox"
date = 2023-01-31
draft = true
categories = ["Book Review"]
tags = ["book review", "legacy code", "software development"]
banner = "img/legacy-code.png"
author = "Michael Hall"
+++

[//]: # (![legacy-code.png]&#40;legacy-code.png&#41;)

{{< figure src="legacy-code.png" title="Legacy Code" width="200" >}}

📚 Book Review:  The Legacy Code Programmer's Toolbox by Jonathan Boccara

Rating: 5/5

I had this book sitting on my desk for a few years, recommended by a coworker.  Life got busy.  I decided to pick it back up and finish it!  Here’s some of the insight I’ve learned from it.

The author begins by defining legacy code as code that is hard to understand, uncomfortable to change, and causes concern.  Attitude plays a significant role in how we approach legacy code. There’s the natural mindset, often negative, versus the effective mindset, which is more constructive. We can choose to understand legacy code as a solution to past problems accumulated over time and recognize it as a reason we have jobs.

A few pieces of advice the author shares:

* If you don’t like a piece of code, reflect on why.
* Read good code to learn new problem-solving techniques.

He also outlines three techniques for gaining an overview of unfamiliar code:

1. Choosing a stronghold: Start from a code section you understand.
2. Analyzing inputs and outputs: Focus on how the program receives and returns data.
3. Well-chosen stacks: Set breakpoints to inspect the call stack during execution.

Knowledge is key. Legacy code is challenging primarily due to a lack of understanding. Writing valuable documentation can help spread knowledge within the team, so it’s crucial to keep it aligned with the code. Presentations, pair programming, and external meetups are great ways to share insights.

The author discusses strategies for finding a bug, echoing some methods familiar to our engineering team.  The quickest way to find the source of a bug:

* Step 1: Reproduce the issue.
* Step 2: Start with small differences, then move to larger ones.
* Step 3: Formulate and validate a hypothesis.

Lastly, the importance of strategic refactoring is emphasized—knowing what to fix to maximize value while minimizing costs is vital.

If you’re seeking to grow as a developer, I recommend this insightful read!
