---
# try also 'default' to start simple
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: "text-center"
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
fonts:
  # basically the text
  sans: "Robot"
  # use with `font-serif` css class from windicss
  serif: "Robot Slab"
  # for code blocks, inline code, etc.
  mono: "Fira Code"
---

# Why I Use Neovim

# From Within VS Code

<!-- Hey everyone, my name is Joe Previte and today I'm going to be talking to you about why I use Neovim from within VS Code.  -->

---
layout: center
---

## "but why???"

<!-- The goal of this talk  is to open your eyes to a new way of seeing the relationship between Neovim and VSCode.  -->

---

# About Me

<v-clicks>

- Joe Previte
- Open Source TypeScript Engineer at [Coder](https://coder.com)

</v-clicks>

  <!-- A little bit about me. I work as an Open Source TypeScript Engineer at a startup called Coder which helps teams move their development environments to the cloud (aka remote dev environments). -->

---

[![screenshot of code-server](/code-server.png)](https://github.com/coder/code-server)

<!-- There my main responsibility is maintaining an open source project called code-server which is VS Code in the browser. -->

---

# Courses

<div class="container">

[![vim course screenshot](/vim-course.jpg)](https://vimforvscode.com)

[![typescript course screenshot](/ts-course.jpg)](https://typescriptcourse.com)

</div>

<!-- Outside of that I have two courses - one that’s a free email course on TypeScript and the other is a paid course which teaches you the basics of Vim to use within VS Code. -->

<style>
  .container {
    display: flex;
    flex-direction: row;
  }
  img {
    width: 500px;
  }
</style>

---
layout: center
---

"You're too slow"

<!-- I want to start today’s talk with a quick story about how I became interested in keyboard productivity, the gateway to Vim. -->
---

<v-clicks>

![coworking space](/cohoots.png)

</v-clicks>

<!--
Picture this: I'm at my first dev job as a self-taught engineer. It’s my first week in the office after working with my boss remotely for one month.
 -->

---

![coworking space with arrow](/cohoots-arrow.png)

<!--
Part of our “culture” is doing these things called Feedback Fridays where we sit down right here and give each other feedback, if we have any.

As usual, he starts it off with, “so…do you have any feedback for me?” I’m a nice guy. It’s also my first dev job so I don’t want to screw anything up and I say, “i like pair-programming with you! I feel like I’m always learning new things about WordPress.”

He smiles and says thanks! He also enjoys pairing with me.

 -->

---
layout: center
---

<v-clicks>

![man sweating profusely](/sweating.gif)

</v-clicks>

<!-- He pauses, waiting for me to ask him the same question so I say, “so…do you have any feedback for me?” My heart’s beating fast. I’ve still got the first-week nerves. -->

---

<v-clicks>

"You're too slow at the keyboard."

<br />

"You use your mouse too much."

<br />

"I want to see you invest in learning keyboard shortcuts."

</v-clicks>


<!-- He smiles and says, “I do. You’re too slow at the keyboard. You use your mouse too much. I want to see you invest in learning keyboard shortcuts.”  -->

---
layout: center
---

<v-clicks>

![sublime for dummies book](/dummies.jpeg)

</v-clicks>

<!-- Inside, I was crumbling. “Dang… never even thought to deliberately invest time into learning keyboard shortcuts.” So I spent the entire weekend learning Sublime keyboard shortcuts just so he wouldn’t say the same thing next Feedback Friday. And over time, I started to realize the power of keyboard speed. -->

---

## "Used by the Greats"

<!--
This next story I want to share is called "used by the greats".

 -->

---
layout:center
---

<v-clicks>

![ryan florence speaking on stage](/ryan-phoenix.webp)

</v-clicks>

<!-- Fast forward a couple years later. I'm sitting in the front row at the Phoenix React.js Meetup listening to Ryan Florence talk about React hooks. Hooks are this completely new paradigm but that’s not what’s got my attention. No, it’s Ryan and his fingers.

He is literally flying through his editor and my brain literally can’t comprehend it. “How is it humanly possible to move that fast without touching your trackpad?” I ask myself.
 -->

---
layout: center
---

<v-clicks>

# Vim

</v-clicks>

<!-- Then I realized there could only be one answer: Vim.

It was then I had an epiphany. These giants in the web space had one thing in common: they all used Vim! 
 -->

---
layout: center
---

![VS Code logo](/vscode-logo.png)

# "I love you"

<!-- I was already on the VS Code train by then and had my workflows down to a T like pair-programming with VS Live Share, had my theme and my settings so I wasn’t prepared to switch editors. -->

<style>
  img {
    width: 200px;
  }
</style>

---
layout: center
---

![sublime vscode extension](/sublime.jpg)

<!-- Heck, I was still using the Sublime keyboard shortcuts – in VS Code! -->

---

<v-clicks>

![vim vscode extension](/vim-vscode.png)

</v-clicks>

<!-- I asked myself, could I get the powers of Vim in VS Code without taking the full plunge? After some research, I discovered a solution - the Vim keybindings extension.  -->

---
layout: center
---

<div class="container">

<v-clicks>

![VS Code logo](/vscode-logo.png)

![sublime logo](/sublime-logo.png)

</v-clicks>

</div>

<!-- When debating whether or not to switch, one reason stood out: you know those Sublime keyboard shortcuts I invested so heavily in? Well turns out they’re only useful in two places: Sublime and VS Code. -->

<style>
  .container {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: space-between;
  }
  img {
    width: 200px;
    margin-right: 48px;
  }
</style>

---
layout: center
---

# unviersal 

# keyboard shortcut 

# language

<!-- Vim on the other hand is like a “universal keyboard shortcut language”. It actually has a purpose outside VS Code. It can even be used in most web-based platforms like Replit and CodeSandbox. That fact alone sold it for me. I could keep my workflows but supercharge my skills. I drank the Vim kool aid and loved it so much I created a course to help others pick up the skills faster than I could.
 -->

<style>
  h1 {
    text-align: center;
    font-size: 5rem;
  }
</style>

---
layout: center
---

# 2022

"same same but different"

<!-- Continuing with the timeline, now it’s 2022. I’m still using VS Code as my IDE but there’s a twist. -->

---

[![screenshot of code-server](/code-server.png)](https://github.com/coder/code-server)

<!-- I’m 100% sold on the “localhost is dead” movement and I’ve moved to a remote development environment. Most of the things I don’t code locally and I access my IDE through a browser. This is the way. -->

---
layout: center
---

![Mando saying this is the way](/way.gif)

---
layout: center
---


![lurker](/lurking.gif)

<!-- However, Vim still lurks in the shadows. -->
---
layout: center
---

tj and prime
<!-- Somehow, I end up following these two degens on Twitter: ThePrimeagen and Teej. And there’s one thing they both keep mentioning over and over: Neovim. --> -->
---

## "Professor TJ"

<!--
TJ story
 -->

---

# Demo of Workflow

<!--
Here's what we're going to do.
1. Find an open source repo
2. Find an issue that's been solved
3. Use it as a way to learn how to navigate the codebase

After this, do live searching on GitHub.
Clone and go through steps.

-->

---

# Thank you!

<img src="https://avatars.githubusercontent.com/u/3806031?v=4" class="h-35 mb-2 rounded-full mx-auto" />

[@jsjoeio](https://twitter.com/jsjoeio)

<br />

girl dad &lt; 1 year, dogs, indie hacking, Star Wars

<style>
  p {
    margin-top: 1px;
    margin-bottom: 1.6rem;
  }
</style>

<!--
Thank you so much for your attention today!

If you want to connect, I'm on Twitter @jsjoeio

Or if you want to come say hi after the talks, here's a list of good topic starters/things i'm into

Thanks again!
 -->
