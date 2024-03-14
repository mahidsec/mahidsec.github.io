---
title: Intro to Reverse Engineering
date: 2024-03-12 15:29 +0600
author: mahidsec
image: assets/img/post _images/confused_cat.jpg
categories: [Reverse-Engineering, Reversing 101]
tags: [Reverse Engineering]
layout: post
---

## Greeting
Assalamu Alaikum, I'm Writting this on First Ramadan So Ramadan Karim.

Who am I? Well, know more about me [here](/about/). For now

![dumbledore-albus-percival-wulfric-brian-dumbledore.gif](https://i.postimg.cc/rsmQPXp3/dumbledore-albus-percival-wulfric-brian-dumbledore.gif){: width='500'}

## What is Reverse Engineering?
Definitions from **Oxford** Languages say "the reproduction of another manufacturer's product following detailed examination of its construction or composition." Now what does all of that mean? in simple terms when we extract detailed information from the software like how it was built and when to do what etc etc. is called **Reverse Engineering**.

## Basic Computer Class
We all know that a computer can't do things on its own even AI needs to be programmed to do something on its own. Programming is hard and for this reason, we get paid to use some of the software on the internet
![meme.jpg](https://i.postimg.cc/rsmzXNpS/harry-potter-hogwarts-express.gif){: width='500'}

## How does this work?
Computer works with **1** and **0** which is known as **binary**. We humans simply can't program with binary. So, we build some `systems` to instruct a computer what it should do, Which is known as `Programming Language`. There are so many of them. For example, **`Assembly`** which can communicate directly with a computer's hardware, **C** is known as the "mother of all programming languages" as well as C++, C#, python, rust, go and the list goes on and so on. We write some instructions for the computer in our chosen programming language. Then we use something called a **[Compiler](https://en.wikipedia.org/wiki/Compiler)**. But some modern language also supports **[Interpreter](https://en.wikipedia.org/wiki/Interpreter_(computing))**.

### What is this gibberish?
We can't read complex binary and computers can't read our simplest programs.
![leviosa-not-leviosar.gif](https://i.postimg.cc/PJy95kr0/its-leviosa-not-leviosar.gif){: width='500'}

We need a middleman who can understand both. **[Compiler](https://en.wikipedia.org/wiki/Compiler)** and **[Interpreter](https://en.wikipedia.org/wiki/Interpreter_(computing))** are the middlemen who can translate our codes into **machine code**. By the term **`machine code`**, we refer to **[Assembly Language](https://en.wikipedia.org/wiki/Assembly_language)**.

## Behind the scenes.
when we compile our program to run on a machine it actually compiles our codes to machine codes.
![graph.png](https://i.postimg.cc/1XyWnQS0/Your-paragraph-text.png){: width='500'}

## Everything is open-source if you know Assembly.
If everything is compiled into machine code, we can reverse-engineer the program and eventually get the whole program source code. Although this code is not the original code but it does the same thing. In the next blog, we'll learn more about the process of **reverse engineering**.


For now, Allah Hafiz