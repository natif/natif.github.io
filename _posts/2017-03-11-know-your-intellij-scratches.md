---
layout: post
title:  "Know Your IntelliJ – Scratches"
date:   2017-03-11 06:00:00 +0200
author: "Kamil Kubacki"
tags: ide java
---

With this post I start a series of Know Your IntelliJ blog posts related
to the IntelliJ’s IDEA best features (according to me).
I use IntelliJ IDEA on a daily basis and it is my IDE of choice.
Throughout a couple of last years, I got some experience with IntelliJ
and it looks like we get on well with each other. I realized that
some of you may benefit from this experience.
Keep track of this blog posts series on my blog.
The Know Your IntelliJ series starts with IntelliJ’s scratches.

## What are scratches?
In the past, I often jumped into a situation where I needed to create
a note or save a JSON request/response for further use. In those cases,
I would have used editors like Sublime 3 or Notepad++. Both of them
were suitable for me to keep temporary notes. However, switching
from IntelliJ to different editor, just to make a note, is really unproductive.
Fortunately, IntelliJ’s creators came up with a solution for that kind of problems.
They introduced scratch files and scratch buffers, which main
purpose is to behave as temporary files. Thanks to that,
it is a lot easier to keep your notes in the same same place in which you keep your code.
What I value the most in usage of IntelliJ’s scratches, is that they save me from context switching.
Let me get through both scratch files and scratch buffers in more detailed way.

## Scratch files
Scratch files are language and extension specified temporary files.
Scratch files are the ones I use the most. The variety of scratch
files’ extensions is big, e.g. JSON, SQL, XML, just to name a few.
I see no better option of using scratch files than keeping sample
requests/responses to services that you currently work on. Additionally,
those temporary files can be used as code formatters.

Imagine a situation when you read from your applications
logs a sample output of JSON service.
It is really hard to read it without proper formatting.
To solve that, a scratch file can be easily and fast
created with JSON extension type and then IntelliJ’s code formatting option can be used.

For scratches presentation purpose, I decided to record short videos
presenting the usage of scratch files and buffers.
I hope it makes more sense than writing all the steps down in blog post.
The video below presents the usage of scratch files which includes:
* creating/modifying scratch files,
* listing scratch files types,
* formatting scratch files,
* listing all available scratch files.

<video width="450" controls>
    <source src="/files/scratches/ScratchFiles.mp4" type="video/mp4">
</video>


## Scratch buffers
Scratch buffers are just simple .txt files (the extension is not visible).
They are not language specific files, so one of the best option to use
them is for keeping simple notes.

Personally, I use scratch buffers
for daily TODO lists. In the past, I used notebook for daily TODO lists.
However, using scratch buffers improved the comfort of my work,
because I simply check my IDE which of the tasks are left to complete.
No need to get my sight off the IDE.

The video below presents the usage of scratch buffers which includes:
* creating/modifying scratch buffers,
* listing all available scratch buffers and scratch files.

<video width="450" controls>
    <source src="/files/scratches/ScratchBuffer.mp4" type="video/mp4">
</video>

More information related to scratch files/buffers can be found
at IntelliJ IDEA help page.

<b>Please check my detailed answer at
[Stackoverflow](https://stackoverflow.com/questions/41117918/how-to-format-pasted-json-in-intellij-android-studio/41148344#41148344).</b>

Knowing features of your IDE is a must for high work
performance and developer’s comfort. The more of them you know,
the better your work results are. In my case, scratches have reduced
the time of tool switching and unnecessary focus lose.
Let me know how it works for you!
