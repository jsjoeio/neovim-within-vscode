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

<!-- The goal of this talk is to show you how to use Neovim in an unconventional way. -->

---

# About Me

<v-clicks>

<img src="https://avatars.githubusercontent.com/u/3806031?v=4" class="h-35 mb-2 rounded-full mx-auto" />

[@jsjoeio](https://twitter.com/jsjoeio)

<br />


- Joe Previte
- Open Source TypeScript Engineer at [Coder](https://coder.com)
- girl dad(1y), dogs, indie hacking, Star Wars

</v-clicks>

<style>
  h1 {
    text-align: center
  }
  p {
    text-align: center;
    margin-top: 1px;
    margin-bottom: 1.6rem;
  }
</style>

  <!-- A little bit about me. I'm Joe Previte. I work as an Open Source TypeScript Engineer at a startup called Coder which helps teams move their development environments to the cloud (aka remote dev environments). Lastly, a couple more personal things. -->

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

# universal 

# keyboard shortcuts


<!-- Vim on the other hand is like “universal keyboard shortcuts”. It actually has a purpose outside VS Code. It can even be used in most web-based platforms like Replit and CodeSandbox. That fact alone sold it for me. I could keep my workflows but supercharge my skills. I drank the Vim kool aid and loved it so much I created a course to help others pick up the skills faster than I could.
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

<div class="flex flex-row">
<div class="flex flex-col justify-center items-center mr-8">
<img src="https://pbs.twimg.com/profile_images/1510770649559547908/zd9t45gH_400x400.jpg" class="h-35 mb-2 rounded-full mx-auto" />
<span class="text-center mt-2">ThePrimeagen</span>
</div>

<div class="flex flex-col justify-center items-center mr-8">
<img src="https://pbs.twimg.com/profile_images/1518677058301349888/iZmoplTq_400x400.jpg" class="h-35 mb-2 rounded-full mx-auto" />
<span class="mt-2">teej dv</span>
</div>
</div>

<v-clicks>

<p class="pt-16 font-bold text-center">Neovim</p>

</v-clicks>

<!-- Somehow, I end up following these on Twitter: ThePrimeagen and Teej. And there’s one thing they both keep mentioning over and over: Neovim. -->


---
layout:center
---

![teej tweet about livestream with him](/tweet-.png)

<!-- I finally caved and asked TJ where I can learn more. Being the nice guy he is, he offers to introduce me to Neovim on a live stream. -->

---

![joe and teej livestreaming neovim](/livestream.png)

<!-- We do the livestream and it’s awesome! It’s fun, there is so much you can configure and it genuinely seems like it could be faster than my VS Code experience. I also think back to my idols and how I’m still missing out on something they’ve found. After weeks after the livestream, I’m reflecting on the livestream I had with TJ and thinking, “Neovim would be cool…but I don’t know if it could match my current workflow.”
-->

---

<v-clicks>

1. An internet connection
2. A browser

</v-clicks>


<!-- My workflow only had two requirements:
1. An internet connection
2. A browser

Everything else is irrelevant. This is the workflow I’ve adopted because it lets me access my dev environment from any device, anywhere. I could spill coffee on my laptop, pick up my phone and be coding 5mins later. And I love having that ability.
 -->

---

![dms between joe and teej](/dms.png)

<!--
Still, I romanticize using Neovim as my main IDE. Multiple times I tweet and DM TJ asking if he knows of a web-based terminal because then I could migrate my flows over. It’s this last time that we were tweeting about it where he says something that makes it click.
 -->

---
layout: center
---

![tweet about ssh](/ssh.png)

<!-- He says, “all you need is an SSH client.” -->

---

<v-clicks>

![code-server with terminal in workbench](/code-server-neovim.png)

</v-clicks>

<!-- 
I let that sink in and then I realized, “Oh my gosh. The answer has been in front of me this whole time.”

“code-server is my SSH Client. It’s literally a giant terminal that I can access via the web.”

That means I can keep all my tools without having to find an SSH client or terminal application for every device I have. I can do it all through the browser! And that’s what I’ve been doing for the last couple of weeks.
 -->

---
layout: center
---
# Demo of Workflow

<!--
Now that you know what it took to get me here today, I want to show you this flow right now.

-->

---
layout: center
---

# Thank you!

<br />

Say hi on Twitter: [@jsjoeio](https://twitter.com/jsjoeio)

<br />

[Learn more about Neovim in Coder](https://github.com/coder/coder/discussions/5191)

<style>
  h1 {
    text-align: center
  }
  p {
    text-align: center;
    margin-top: 1px;
    margin-bottom: 1.6rem;
  }
</style>

<!--
Thank you so much for your attention today! Hope you enjoyed learning about how
to use Neovim in a different way that makes your dev environment more portable.

If you want to connect, I'm on Twitter @jsjoeio

Thanks again!
 -->
