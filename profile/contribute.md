# Contribution Role

You can contribute to our content if you are part of our team or not, but is more easy to work with us if you are part of our team. Anybody can fork our repository. Memvers cab be: Instructors, Developers or Students. Having one of these roles you can have direct access. Wehn you have direct access you can work in developement branches and commit to main branch or work directly in the main branch.

**Gusts**

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
    +-->root
    |
    +-->images
    |
    +-->seng
    |
    | ...
    (other projects)
```
Our website is distributed in many repositories. The main repository is the /root repository. When you start your contribution you must fork or clone at least two: *root* and *images* repositories into the working folder: ~/sagecode or directly in your home folder ~/. You must copy all files from ~/sagecode/root into the working folder that is ~/ or ~/sagecode/. This is for testing and ofline browsing. Use script ~/sagecode/root/publush.sh to copy the files into parent folder.

## Project

Usually a developer work on a single tutorial. Therefore you can clone the specific tutorial in the working folder. For example ~/sagecode/java is containing the Java tutorial. If you have installed immages properly, you can open ~/java/index.html in local browser without installing any special software. We use relative links to find the immages and the style files that should be located in ~/sagecode/ (work folder) and  ~/sagecode/images/.

## Publshing 

After you make any modification in ~/sagecode/root folder, you need to run ./publish.sh to copy over the new files in the work folder ~/sagecode/ so you can see locally the new version. After you verify to look good in the browser you can commit the root repository. In the future we will have automation scripts that will publush your modification to our website. At this time we do manual work to publish all modifications to the website.

## Get started

You can ask questions on Sage-Code general [discutions](https://github.com/orgs/sage-code/discussions) board. Every repository has also a discution board and a read.me file that contains info about that particular project. Follow this info and update new info when you have it.

**Follow up:**

1. Visit: [Sage-Code Laboratory](https://sagecode.net)
2. Clone: [Images repo](https://github.com/sage-code/images)
3. Clone: [Root repo](https://github.com/sage-code/root)

After these steps you are ready to contribute. Publish ~/sagecode/root using ./publish.sh command. Then you can open the website locally ofline. Clone your favorite programming languages or projects. This is a great resource to learn and contribute without internet connection. Start editing then verify locally and commit later. Please commit every day at least once if you modify anything. From time to time, update your clone especially before starting to edit to avoid possible future conflicts.

Learn and prosper 🖖🏼

----
Copiright (c) Sage-Code 2022


