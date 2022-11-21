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
Ryan florence story
 -->

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
