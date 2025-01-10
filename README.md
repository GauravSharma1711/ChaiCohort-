<h1>Git & GitHub Guide for Chai Cohort Members 🚀<h1/>
<h2>Introduction<h2/>

Welcome to the one-stop solution for learning Git & GitHub! This guide is specially designed for members of the Chai Cohort in a beginner-friendly manner. Here, you’ll not only learn Git & GitHub from basics to advanced but also see real-life examples to make your understanding easier. Let’s dive in! 😊

<h2>Problem Statement<h2/>
Imagine this:

Your company, Chai Cohort, is hosting a mini-hackathon with exciting gifts for the winners! 🎉 You’re eager to participate but there's a catch – it’s a full-stack web development hackathon, and you only know HTML, CSS, JavaScript, and basic React.

To solve this, you leverage the alumni network and form a team with a beginner backend developer, Gaurav. Everything seems great, except…

💔 The Problem: You and Gaurav live in different cities. How will you both collaborate on the same codebase?

Gaurav comes to the rescue:
<Br>
"We can use a centralized codebase to share and update our code."

The solution? Git & GitHub.

<h2>What is Git?<h2/>

Git is a version control system (VCS) that tracks changes in your code and helps you collaborate with others. It’s like a time machine for your code.

With Git, you can:

Save Snapshots: Capture the state of your code at different points (called commits).

Undo Mistakes: Revert to an earlier version if something breaks.

Collaborate: Work with multiple developers on the same project without conflicts.

Think of Git as software running on your computer to manage your project files.


<h2>What is GitHub?</h2h2>

GitHub is an online platform that hosts your Git repositories. It’s like Google Drive but specifically for code.

With GitHub, you can:

Backup Code: Save your code in the cloud for safekeeping.

Collaborate: Work with others on the same project.

Track Changes: View the history of edits and contributions.

Learn and Share: Discover open-source projects or share your own

<hr>

<h2>Installation and Setup:<h2/>
  
1. Install Git

Download Git: https://git-scm.com/downloads
![git-scm com_downloads](https://github.com/user-attachments/assets/2be67d7f-a029-472a-b693-ef638cb82863)

After installation, open a terminal and type:

```bash
git --version

```
This checks if Git is installed correctly.



<h2>Creating Github Account<h2/>
(https://github.com/)
<img width="938" alt="image" src="https://github.com/user-attachments/assets/aecd723b-9c13-4431-8b6f-36b88187f461" />


  
<br>
Click on Signup and create your Github account (It is similar to creating instagram account)


<br>
<img width="932" alt="image" src="https://github.com/user-attachments/assets/3a0a7315-21f6-47a7-bfb6-85dd36099b4f" />


# Key Differences Between Git and GitHub

| Feature        | Git                                          | GitHub                                       |
|----------------|---------------------------------------------|---------------------------------------------|
| Definition     | A distributed version control system.       | A cloud-based platform for Git repositories.|
| Purpose        | Tracks changes in the code locally.         | Facilitates collaboration and sharing online.|
| Installation   | Installed on your local machine.            | Accessible via a web browser or desktop app.|
| Usage          | Version control and history management.     | Hosting repositories and team collaboration.|
| Examples       | `git init`, `git commit`, `git push`.       | Pull requests, issue tracking, CI/CD.       |


<hr>

<h2>Configure Git<h2/>

Link your Git to GitHub by setting your email and name:

```
git config --global user.email "your-email@example.com"

git config --global user.name "Your Name"

git config --list
```

# Basic Git Terminology

| Term               | Definition                                                                                     |
|--------------------|-----------------------------------------------------------------------------------------------|
| **Repository**      | A project directory where Git tracks changes, locally or remotely.                           |
| **Commit**          | A snapshot of changes saved in the repository's history.                                      |
| **Branch**          | A separate line of development within a repository.                                           |
| **Merge**           | Combines changes from one branch into another.                                                |
| **Push**            | Sends local changes to a remote repository.                                                  |
| **Pull**            | Fetches and integrates changes from a remote repository.                                     |
| **Clone**           | Creates a local copy of a remote repository.                                                 |
| **Staging Area**    | A space where changes are prepared before committing.                                         |
| **Conflict**        | An issue that occurs during a merge when changes in branches conflict.                       |
| **.gitignore**      | A file used to specify files or directories that Git should ignore.                           |

<br>

<h2>Creating our first repository<h2/>
  
1. Sign In to GitHub
Go to (https://github.com/) and log in to your account.
<img width="958" alt="Screenshot 2025-01-10 221224" src="https://github.com/user-attachments/assets/84730ecf-4e55-4523-8ea2-ce0a0126169d" />
