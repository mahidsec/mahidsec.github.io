---
title: "Reverse Engineering: From byte to bit | 0x01"
description: Will know what is Reverse Engineering, where to use it, why we use it?
image: 
  path: https://i.ibb.co.com/9TtqQ3s/0x01.png
  alt: "0x01 Thumbnail" 
categories: [Reverse Rngineering 101, English]
tags: ["Reversing", "0x01", "English"]
---
# Greetings
ٱلسَّلَامُ عَلَيْكُمْ yes! There was anothe post on this topic but there were some mistakes in that post so that I had to write it again. As always along the blog you'll hear my lame logics. And yes we are talking about software reverse engineering!
বাংলায় পড়তে [এখানে](https://google.com) ক্লিক করুন।

![Let's begin the show](https://i.ibb.co.com/Bjz8c09/Let-The-fest-begin.png){: .shadow .light }
![Let's begin the show](https://i.ibb.co.com/KmqNZ1p/Let-The-fest-begin-dark.png){: .shadow .dark }

## Introduction to Software Reverse Engineering
In simple term examine something either by tearing it or knowing it by it's outer surface is known as [`Reverse Engineering`](https://en.wikipedia.org/wiki/Reverse_engineering)। 


## Basic Computer Class & Fundamental Concepts
We all know that a computer can't do things on its own even AI needs to be programmed to do something on its own. Programming is hard and for this reason, we get paid to use some of the software on the internet

![poor cat](https://i.ibb.co.com/8gXSDHp/853686e5-627c-4207-97f6-961c362a8bb7.jpg){: .shadow }
_USSSSSSSSS_

Computer works with **1** and **0** which is known as **binary**. We humans simply can't program with binary. So, we build some `systems` to instruct a computer what it should do, Which is known as `Programming Language`. There are so many of them. For example, **`Assembly`** which is so close to system that we can communicate directly with a computer's hardware, **C** is known as the "mother of all programming languages" as well as C++, C#, python, rust, go and the list goes on and so on. We write some instructions for the computer in our chosen programming language. Then we use something called a **[Compiler](https://en.wikipedia.org/wiki/Compiler)**. But some modern language also supports **[Interpreter](https://en.wikipedia.org/wiki/Interpreter_(computing))**.

## Behind the scenes.
when we compile our program to run on a machine it actually compiles our codes to binary. Here is a simple diagram that shows how it's done.
![graph.png](https://i.ibb.co.com/KN4g5BJ/Your-paragraph-text-1.png){: .shadow }
_Diagram Image ©️mahidsec_



## Use cases of reverse engineering
We do not use Reverse Engineering to bad things at all, we also use it to do good.

: ### 1. Malware Analysis
to know about Malicious Software.Like [Marcus Hutchins](https://en.wikipedia.org/wiki/Marcus_Hutchins) used to distroy [WannaCry](https://en.wikipedia.org/wiki/WannaCry_ransomware_attack) ransomware.

: ### 2. Software Vulnerability Discovery
Discovering vulnerability across softwares

: ### 3. Patch Development
Some times a Softwear might be [closed source](https://simple.wikipedia.org/wiki/) and in order to fix that we have todo it, like [here](https://nee.lv/2021/02/28/How-I-cut-GTA-Online-loading-times-by-70/) someone droped GTA V loading time up to 70%.

: ### 4. License Recovery
Removing License legally to restore lost or stolen license, like [here](https://www.youtube.com/watch?v=o5IySpAkThg).

: ### 5. Crack Prevention and Software Protection
Devoloper it self use this method to know either there sosftwere is easily crackable or not and do they need to do [Obfuscation](https://en.wikipedia.org/wiki/Obfuscation_(software)).

: ### 6. Understanding Competitor Software
To understand Competitor Software, How theymaden etc.

: ### 7. Educational Purposes
To teach people how softwear work internally. 

: ### 8. Game Modding
বিভিন্ন গেইমের মোড তৈরি করতে Reverse Engineering করা হয়।


## Ethics & Safety
Using paid softwear freely is not good and we also advice not to do it, There are hackers who binds melicious malware to hack you!

![Hacker Cat](https://i.ibb.co.com/7pt5GtP/feb57781-40dd-4131-a112-b6432073f27a.jpg){: .shadow }
_HCKRRRRRRRRRR_

## What's Next?
We'll start our first Reverse Engineering from the next lession
[**`Part 2`**](../reverse-engineering-en-0x02/)