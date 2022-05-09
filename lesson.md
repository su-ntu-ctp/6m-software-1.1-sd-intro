## Brief

### How to use the lesson sample code

There are two folders prepared for the lesson. 
- [Instructor's folder](./lesson-sample-code/instructor-demo-code)
- [Learners' folder](./lesson-sample-code/learners-practice-code)

Instructor to use the code provided for demonstration during the I DO segment. Learners will use the java file provided in the respective folder for practice during the WE DO segment.

### Any other announcements to instructors or learners

## Self studies check-in

1. What is programming languages for? Why do we have to use them?
2. What is the difference between compiler, transpiler and interpreter?
3. What is a software development environment? (bridging to lesson)

---

## Part 1 - Bash for Win & Explore Bash Commands

Demonstrate to students what bash commands can do by referring to this [cheatsheet](https://www.educative.io/blog/bash-shell-command-cheat-sheet). Attempt the following Shell Commands in 5 mins as part of demo:

```sh
mkdir test-folder # create new folder
pwd # print working directory (current directory)
cd test-folder # change directory to 'test-folder'
pwd # print current directory and observe the difference
touch a.txt # create a new file
touch b.txt # create a new file
ls # list all files in current directory
```

Now, let Windows Learners install their Bash Shell for Windows and MacOS Learners to play around with the cheat sheet.

---

## Part 2 - Install NVM & Latest Node LTS

- Install NVM in the respective Operating Systems.
- Install node and npm using the `nvm` command.

Example:
```sh
nvm ls-remote # list all versions
nvm install v16.15.0 # install latest LTS
nvm alias default # ensure v16.15.0 is printed
```

---

## Part 3 - VS Code

- Install VS Code
- Install Extensions
    - Live Share (pair programming - good for seeking help from instructors)
        - Instructor create a read-only link and share with students.
        - Be sure to show students there are read-only and write permissible links.
    - Live Server (to host html)
        - This is being used in module 1 only (2 weeks).
        - In the explorer navigation on the left
            1. expand `src` folder
            1. right-click `index.html`
            1. choose "Open with live server"
            1. you should see a page on browser 
    - Prettier code formatter
        - Use [index.js](./src/index.js) as example by opening the file.
        - Right-click the code and choose "Format Document with"
        - Select Prettier

---
## Part 4 - Installing & Basic GIT Commands

Refer to a step by step walk through for installation and basic use [here](./assets/git-guide.pdf).

> Note: All learners should write their git commands in bash shell through the VS Code Terminal. This is to ensure consistency in the lesson.

---

## Part 5 - Chrome Developer's Tool

Walk learners through the `elements` and `console` tab.

<img src="./assets/dev-tools.png" />