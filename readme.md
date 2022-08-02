# a guide to learning how to build the web.

this is a very opinionated guide for people who want to learn how to make things on the web &mdash; whether those things are websites, games, applications, or anything else that requires programming and design. with that being said, it's not definitive and definitely could stand some improvement and criticism.

---

## contents

### inital setup

1.  [introduction (what this guide is for, what you can do after reading it, etc)](#introduction)
1.  [tools you will need](#tooling)
1.  [optional software and hardware](#optional)

### just starting out

1.  [how to learn your tools](#learning-your-tools)
1.  [actually writing code](#writing-some-code)

### making things

1.  [making your first projects](#first-projects)
1.  getting creative
1.  coming up with useful ideas

### going forward

1.  working in the field
1.  constant improvement

---

## part one: inital setup.

#### introduction

this guide is not a comprehensive list, nor is it a full course in web development. it's simply a starting point &mdash; it will point you to a list of resources that you should take advantage of. this will supplement your independent learning, hopefully allowing you to learn new techniques and technologies more quickly.

also, this guide is aimed primarily at windows users, because that's what I am.

#### tooling

##### 1. text editors

choosing a text editor is a matter of personal preference, but here are some that have been really good to me.

-   [**atom (my current editor).**](https://atom.io/) I picked this editor up many years ago and chose it because of its high extensibility. this means the editor itself is fully modifiable with user-created extensions. this editor can easily be turned into whatever you want it to be, from simple things like the font / color scheme to underlying functionality.

![atom editor's interface](./img/atom.png)

-   [**brackets.**](https://brackets.io/) this is the text editor I used for several years before I switched to atom. it's really simple, but it has a nice interface and a wide selection of user created extensions at your fingertips.

![brackets editor's interface](./img/brackets.png)

-   [**sakura**](https://sakura-editor.github.io/index.en.html) barebones as it is, I love sakura. I use it as my editor for doing git stuff (rebasing, writing commit messages, etc) but probably would not use it as my primary editor - it has pretty low extensibility and can be tricky to get into due to a lot of the reading material being written in japanese.

![sakura editor's interface](./img/sakura.png)

see also: [notepad++](https://notepad-plus-plus.org/downloads/), [sublime text](https://www.sublimetext.com/).

##### 2. terminal

a terminal (when combined with a shell) will allow you a higher level of control over your computer compared to the average windows user. one of these is required to use certain software, such as [command-line interfaces](https://en.wikipedia.org/wiki/Command-line_interface). you're going to need a terminal to use software like [npm](https://www.npmjs.com/), [node](https://nodejs.org/), and [git](https://git-scm.com/), just to name a few.

-   [**windows terminal.**](https://www.microsoft.com/store/apps/9n0dx20hk701) this is the one I currently use. it's developed by microsoft for windows, so it actually works very very smoothly.

![bash running on windows terminal](./img/bash-windows-terminal.png)

-   [**cmder.**](https://github.com/cmderdev/cmder/releases) I used to use this one before windows terminal came out and even a little bit afterward. it's pretty good, it's just not pretty-looking enough for my purposes.

![bash running on cmder](./img/bash-cmder.png)

##### 2. shell

a shell is essentially a program that you'll run within a terminal. the shell is the program that's actually interpreting and processiong your commands. one of the most common ones is bash, and that's what I use. I've also listed fish because I think it's a nice piece of software.

-   [**bash (cygwin).**](https://www.cygwin.com/packages/summary/bash.html) this is what I use.

-   [**bash (git bash).**](https://gitforwindows.org/) this one is the same as cygwin bash, but I found it to be more difficult to install new software packages with.

-   [**fish.**](https://fishshell.com/) this one looks fun and comes with some nice autosuggestion features.

##### 3. version control

a version control system is a piece of software designed to track changes in a codebase. this will allow you to write code incrementally &mdash; meaning that if you break something, you can go back to a previous "checkpoint". it also is a huge benefit when you're working with multiple people on a team, because it helps you to see who did what within the code.

-   [**git.**](https://git-scm.com/) git is an extremely powerful version control system and the de facto item of its type.

#### optional

-   **multiple monitors.** this might help you out quite a lot. seeing the software you're working on while being able to look at the code you're writing at the same time is a great benefit. I started out using only one monitor, but at the time of writing I use 4 to work &mdash; one for a text editor, one for a terminal, one for discord, and one for a web browser.

-   **task management software.** I'm an extremely disorganized person, so I use [aeriform tape](https://aeriform.itch.io/tape) to help me manage my day-to-day tasks.

---

## part two: just starting out.

### learning your tools

#### 1. learning the shell

one of the first things you should do with your shell and terminal after setting up is to learn how to navigate around your computer. learn how the filesystem is arranged. figure out how to move between folders, create / delete new folders and files, and how to edit them &mdash; all from the command line. after this step, you should be able to set up a new project from scratch using only shell commands.

resources:

1.  e