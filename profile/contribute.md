# Contribution Role

You can contribute to our content if you are part of our team or not, but is more easy to work with us if you are part of our team. Anybody can fork our repository. Members can be: Instructors, Developers or Students. Having one of these roles you can have direct access. When you have direct access you can work in development branches and commit to main branch or work directly in the main branch.

**Guests**

As a guest you can visit our homepage and start learning how to code. You do not have to register or login. We host two courses: Software Engineering and Programming Languages. You can learn principles of programming from zero to hero in shorter time than school. Our courses are focussed on basic knowledge. For advanced programming you can follow documentation. There is no schedule, you can start learning any time and pause or continue in your own free time. We do not track your progress.

**Community**

You can join our community on Discord, Google, Reddit. After you join, you can claim a new role on chat room. We do not have any registry or database and we do not collect e-mail addresses nor phone numbers. After you get a role you will receive an invitation for GitHub in your e-mail. You can accept this invitation to become member in our team and get access to projects.

**Invitations**

* [Sage-Code Discord](https://discord.gg/fAEHfw8T)
* [Sage-Code Group](https://groups.google.com/g/sagecode)
* [Sage-Code Reddit](https://www.reddit.com/r/sagecode/)

## Students

As a student, you can have access to extra resources, not available for guests. This include secret links and voice rooms where we share presentations and schedule work sessions. Students can make PR requests for any of our projects. We grant direct access to specific training projects so you don't need to fork some of the projects.

## Developers

To become a developer on Sage-Code you must be active on Discord. Post some info about your goals and skills on our #team channel and read the rules. An instructor will send you DM for an interview and will assign you the role. Developers have direct access to all our projects and can work in developer branches.

## Instructors

Sage-Code instructors are professional developers with experience that we can trust. Instructors are moderators and code maintainers. As an instructor you can accept PR from students and you can merge code into main branch. To become an instructor you need to pass several exams and prove your skills. Instructors are our partners and have access to private Sage-Code projects.

# Work environment

You can fork any of our repositories. We do not accept PR requests from random visitors that we don't know. You must connect with an Instructor or Developer who can merge PR requests. We advice you to avoid extra work. As a guest you can clone our repositories instead of forking. Later if you get a role you will be able to work in branches and commit. We will merge the branches into main or you can do it yourself.

## Structure

```
~/sagecode
    |
    |
    +-->&images
    |
    +-->eve
    |
    +-->bee
    |
    +-->www
    |    +-->images
    |    ...
    +-->tor
    |...
    (root files)
```

Our website is distributed in many repositories. The main repository is the /www repository. This contains www/images folder and one folder for every language that we teach.  Before you can start your contribution you must fork or clone /www into a working folder named: ~/sage or ~/sagecode. This repository contains index.html, software engineering course and programming course. Folder www/image contains common images, reused for many languages. Some of these images can be used by other projects.

## Projects

Usually a developer work on a single project. You can clone our projects in the same working folder. For example ~/sage/eve/. After you clone a project, the style and some of the pictures are not accesible so the page will not look good in local browser. Therefore you need to run from ~/sage/www the file export.sh using commands: 

```
%/> cd ~/sage/www
~/sage/www/bash export.sh
```

This script will make a soft link to /www/images folder and will copy the root files in the ~/sage work folder. With this, you can now view the entire website including the projects correctly. I keep the projects outside of the /www repository but I publish them together on the website so the website. That is not your concern as a contributor. Is my job to publish and refresh the website.

## Your Rolet

You can claim a role on Discord. Having a developer role on Discord is the first condition to work on our projects. Second you need a role on GitHub. If you are not invited to our organization you can't contribute to our projects directly, but you can clone the project anyhow. What you can't do is modify the project and push changes. For this you need a fork, then create a clone of the fork and push changes in your own repository. If you do so, you can make later a PR. A mentor can review your code and accept the changes. So you can contribute even if you are not a Sage-Code member after all.

## Get started

You can ask questions on Sage-Code general [discussions](https://github.com/orgs/sage-code/discussions) board. Every repository has also a discussion board and a read.me file that contains info about that particular project. Follow this info and update new info when you have it.

**Follow up:**

1. Visit: [Sage-Code Laboratory](https://sagecode.net)
2. Clone: [Images repo](https://github.com/sage-code/images)
3. Clone: [Root repo](https://github.com/sage-code/root)

After these steps you are ready to contribute. Publish ~/sagecode/root using ./publish.sh command. Then you can open the website locally offline. Clone your favorite programming languages or projects. This is a great resource to learn and contribute without internet connection. Start editing then verify locally and commit later. Please commit every day at least once if you modify anything. From time to time, update your clone especially before starting to edit to avoid possible future conflicts.

Learn and prosper 🖖🏼

----
Copyright (c) Sage-Code 2023


