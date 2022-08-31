---
layout: ../../layouts/project.astro
title: Frontend frameworks comparison from beginner's perspective
client: Self
publishDate: 2022-09-02 00:00:00
img: https://images.unsplash.com/photo-1547234935-80c7145ec969?fit=crop&w=1400&h=700&q=75
description: |
  I built the same simple project using 6 different frontend frameworks and 4 different languages to decide on my own which one I prefer
tags:
  - frontend
  - dev
  - dotnet
  - rust
  - javascript
  - react
  - angular
  - svelte
  - yew
  - miso
  - blazor
---

First hard thing to overcome when self learning web development is, at least for me, diversity and quantity of tools you can use. It would be nice to just google "which frontend framework is best" and get clear and unequivocal results, but the only thing you can learn by searching for anwser for such question is basically "you have to try on your own to decide". So I've decided to try.

I have currently some experience in writing programs in four languages: Rust, JavaScript, Haskell and C#. And as I explored frontend landscape I discovered that each of these languages have tools for frontend development, which isn't so obvious, because frontend is inextricably associated with JavaScript. But, utilising different solutions frontend frameworks can be built in any language. Blazor (C# framework) and Yew (Rust framework) are using WebAssembly, standard which aim to "define a portable, size- and load-time-efficient binary format to serve as a compilation target which can be compiled to execute at native speed by taking advantage of common hardware capabilities available on a wide range of platforms, including mobile and IoT", which for me doesn't mean much, but basically, as I understand it, it enables browsers to run code (after compilation to specified format) written in any language. As it comes to Haskell, I decided to use Miso, which isn't using WebAssembly but just compiles to JavaScript, so it is like wrapper for JavaScript. JavaScript is of course different beast, because, as native web browser language, it has been language of choice for writing frontend framework. And number of JavaScript frameworks is enormous. Effectively comparing all of these is impossible so the best you can do is pick popular one or the one that is perceived as good one by community (I get idea of what is popular and liked mainly from StackOverflow survey and StateOfJs survey). Based on these criterions I decided to try React, Angular and Svelte (of which React and Angular I have already used).

Next step was to design some single page app which will be simple, but not too simple, because I wanted to really see which framework will help me the best with solving more complex tasks in the future. Inspired by React official tutorial I decided to create tic-tac-toe game with basic functionalities like showing which player's turn it is, undoing moves, showing each players' score and restarting game. 