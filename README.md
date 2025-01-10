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
Open dashboard and click on new
<img width="1344" alt="github com_new" src="https://github.com/user-attachments/assets/2e45057c-3b6b-4365-8d58-228a73da07b4" />
Give name to your repo(ChaiCode) ,give it a description, add a README file (
A README file is a text file that serves as the documentation for a project) after that click on create repository
<br>
<img width="943" alt="image" src="https://github.com/user-attachments/assets/8840b544-99b1-4593-b5cf-310e2110cab4" />
Hurray! 🎉 Your repo has been created! 🚀



<h1>Cloning the ChaiCode Repository:<h1/>
Now firstly create a folder(chaicohort) in your system and open it in your codeEditor
<img width="959" alt="image" src="https://github.com/user-attachments/assets/3d142573-719f-44ff-8fb5-c903f5fae891" />
  <br>
  No code editor? No worries, we’ve got you covered! 🚀💻
  <br>
To install Visual Studio Code (VS Code), follow the steps
Go to(https://code.visualstudio.com/download)
<img width="936" alt="image" src="https://github.com/user-attachments/assets/62c5eb0c-00a7-4677-90e6-7e874f77edee" />
Download based on your operating system:

Now,
to clone your repository present in your Githuhub account to your local machine
<img width="931" alt="image" src="https://github.com/user-attachments/assets/c770f87f-1dd4-471b-89f1-97961e1aad86" />
<br>
click on code
<br>
<img width="799" alt="image" src="https://github.com/user-attachments/assets/33cf52e0-d1c6-4366-819a-b54fe9ac92ac" />
<br>
copy this link
<br>
Now open terminal in your code editor and write command
```
git clone <repository-url>

```
<img width="718" alt="image" src="https://github.com/user-attachments/assets/244258f7-788c-4fbd-92f7-f48eaf902fb3" />
<img width="956" alt="image" src="https://github.com/user-attachments/assets/beafe905-e0ea-40a8-8bd1-9fd9956fece0" />
Hurray! 🎉 Your chaicode repository has been cloned from your Github account to your local machine! 🚀

<h1>Basic Git Commands:<h1/>

```
git status
```
<img width="584" alt="image" src="https://github.com/user-attachments/assets/e4d7a57d-9216-41f1-93b3-7b0c4e507c3e" />
<br>
here cd means change directory i.e now i m inside chaiCode folder
<br>
status command displays the state of code
<br>
2.Git add command
```
git add <filename>
```
The git add command stages changes in your working directory, preparing them to be committed to the local repository.
<img width="902" alt="Screenshot 2025-01-10 232623" src="https://github.com/user-attachments/assets/533cfeec-bee1-4f63-80f1-3ebaa5f5a915" />
<img width="653" alt="image" src="https://github.com/user-attachments/assets/b4049dd5-0047-4ae2-8365-4a035f29e844" />
<br>
Now the file test.txt is tracked by git and is ready to commit
<br>
3. commit command
```
git commit -m "some message"
```

The git commit command is used to save the staged changes to the local repository, creating a snapshot of your project at that point in time.
<br>
<img width="689" alt="image" src="https://github.com/user-attachments/assets/ff7a742d-08b2-4348-8b02-da486c2e840b" />
<br>
4.Push command
The git push command is used to upload local repository content to a remote repository.
```
git push origin main
```
<img width="690" alt="image" src="https://github.com/user-attachments/assets/b4861b8c-9679-4bab-8043-14175b276344" />
<br>
test.txt has been uploaded on your Github

<br>

5 git log

```
git log
```
<img width="797" alt="image" src="https://github.com/user-attachments/assets/a8f7563b-ead3-407a-afa4-9569e2d884e1" />

The git log command is used to view the commit history of a repository.
<br>
<img width="925" alt="image" src="https://github.com/user-attachments/assets/51fefb01-31dd-4f91-95d5-b14fc7628f76" />

<br>

6.Git pull
```
git pull <remote> <branch>
git pull origin main
```
The git pull command is used to fetch and integrate changes from a remote repository into your local repository
<br>
<img width="928" alt="image" src="https://github.com/user-attachments/assets/7e8c36ec-5eee-4a73-b0c9-e146985fdbc6" />


<img width="887" alt="image" src="https://github.com/user-attachments/assets/9dc71990-fd9c-4426-bd60-26745edcf799" />


<br>

<hr>

### Commit Message Rules

To ensure meaningful and standardized commit messages, follow these rules:

#### 1. **Use Present Tense**
   - Always use the present tense to describe your changes.
   - **Example**: `Add new user authentication feature` (not `Added new user authentication feature`).

#### 2. **Capitalize the First Letter**
   - Start your commit message with a capital letter.
   - **Example**: `Fix typo in login form` (not `fix typo in login form`).

#### 3. **Keep It Short and Concise**
   - Keep the commit message **50 characters or fewer** for the **subject line**. It should be a brief summary of the change.
   - If necessary, add a detailed explanation in the body (after a blank line), but **avoid long descriptions in the subject**.
   - **Example**: `Fix login issue with invalid credentials`.

#### 4. **Use Prefixes for Categorization**
   - Use standardized prefixes to categorize the nature of the commit. Common prefixes include:
     - `fix:` – For bug fixes.
     - `feat:` – For new features.
     - `docs:` – For documentation changes.
     - `chore:` – For routine tasks, such as refactoring or maintenance.
     - `style:` – For formatting changes (e.g., code style).
     - `test:` – For adding or modifying tests.
   
   - **Examples**:
     - `feat: Add user registration page`
     - `fix: Resolve issue with form validation`
     - `docs: Update README with setup instructions`
     - `chore: Refactor authentication module`

#### 5. **Provide Context**
   - If necessary, provide **context** for why the change is being made, especially for larger or more complex changes. If the commit is not self-explanatory, add a detailed explanation in the body of the message.
   
   - **Example**:
     ```plaintext
     feat: Add social login options

     Added Google and Facebook login options to improve user onboarding experience.
     ```
   
#### 6. **Avoid Redundancy**
   - Don't repeat the same information. For example, don’t start the message with "Update" or "Fix," as these are implied by the context.
   - **Bad**: `Update the login page`
   - **Good**: `Fix login page display issue`

#### 7. **Reference Issues or Pull Requests**
   - If your commit relates to an open issue or pull request, reference it in the commit message (e.g., `Fixes #123` or `Closes #45`).
   - **Example**: `fix: Correct user permissions logic (Closes #123)`

<br>

<hr>

<h1>Branching<h1/>
<br>
Git branching allows you to create separate lines of development for different features, bug fixes, or experiments, without affecting the main codebase.

1 git branch
To check branch
```
git branch
```
<img width="557" alt="image" src="https://github.com/user-attachments/assets/f84058b8-18b7-42d9-9f66-0c60b5052726" />

<br>

2 To create new branch
```
git checkout -b <new branch name>
```
<img width="659" alt="image" src="https://github.com/user-attachments/assets/1ff21e5f-bb10-4db0-bbc3-8d529067a462" />

<br>

3 to delete branch
```
git branch -d <branch name>
```
<img width="658" alt="image" src="https://github.com/user-attachments/assets/46d1e993-f934-409e-b3d7-dffdc566eb47" />

<br>

<br>
4. Merge Code
<br>
<img width="699" alt="image" src="https://github.com/user-attachments/assets/f49f9f62-6354-454f-8ee8-f225b9a77760" />
<img width="682" alt="image" src="https://github.com/user-attachments/assets/43b503f0-cd45-4054-ad57-1368ee0b3edc" />
<br>
Now merging both codes 
<br>
<img width="692" alt="image" src="https://github.com/user-attachments/assets/c0906135-cba2-4e41-a9de-49a2351a88c8" />
<br>
Use circled options to resolve merge conflict
<br>



<hr>

<h1>Pull Request</h1>
<br>
It lets you tell others about changes you've pushed to a branch in a repository on github
<br>
added dashboard feature to main
<img width="674" alt="image" src="https://github.com/user-attachments/assets/a046de99-6070-4719-9274-20f026e6dea0" />
<br>
added button to bug-fix
<img width="605" alt="image" src="https://github.com/user-attachments/assets/5e05f603-0528-4a5f-8b89-446b63c63fcf" />

<br>
now we have made changes in main and bug-fix branch 
<br>

<img width="728" alt="image" src="https://github.com/user-attachments/assets/04a28d01-beb5-48d1-904d-f7b7c306ec1f" />
<br>
click on compare&merge pull request

<br>
<img width="713" alt="image" src="https://github.com/user-attachments/assets/30cd2f5c-fdae-4836-8f9e-3abe44d2bcb3" />
<br>
click on create pull request
<br>


<br>
<img width="937" alt="image" src="https://github.com/user-attachments/assets/b42d611f-1be7-42a9-9eeb-3b37b79f58ec" />
<br>
resolve conflicts and merge
<br>
<img width="647" alt="image" src="https://github.com/user-attachments/assets/7ce42a2c-63da-4630-9acc-27a5298c9b9b" />

<br>
<img width="674" alt="image" src="https://github.com/user-attachments/assets/ee490d11-39c8-4c07-8d78-9943bae63016" />

<br>
🎉 Hurray! Merge Completed! 🎉

<hr>

### Conclusion

Great job! 🎉 You've learned the basics of Git and GitHub, including branching, committing, and collaborating. Keep practicing, follow good Git practices, and happy coding! 🚀

Feel free to reach out if you have any questions. 😊







