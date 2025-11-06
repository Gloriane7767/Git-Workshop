# Introduction to Git

## Table of Content

1. [Setting Up a New Git Repository](https://your-link-here.com)
2. [Setting Up a New GitHub Repository](https://your-link-here.com)
3. [Git/ Git WorkFlow](https://your-link-here.com)
   
   - [Using VS Code](https://your-link-here.com)
   - [Using Git Commands](https://your-link-here.com)
   
#### Setting Up and Initialize a New Git Repository

1. **Make a New Project Directory in your machine** <br>
Open the Terminal and use the command &lt;mkdir&gt; then specify the *Directory Name* to create a new project directory.
   
2. **Navigate to the Project Directory**<br>
Enter the Project Directory by using &lt;cd directory name&gt;
   
3. **Initialize the Project Directory**<br>
Use the command &lt;git init&gt;. This command creates a hidden folder called .git/ in your Project Directory. The folder will store all the versions history and configuration for the project.

  
#### Setting a New GitHub Repository

1. Navigate to [GitHub.com](https://your-link-here.com) <br>

2. Enter a Repository Name <br>

3. Description (optional) <br>

4. Click on `<Create Repository>`
   
   
#### Git/ Git WorkFlow

1. **Back to the Terminal**<br>
To connect your Local Repo to your Remote Repo with this command: <br>

```git remote add origin <URL>```

Replace the &lt;URL&gt; with the copied URL from GitHub. <br>

This wiil synch your Local Repo with your Remote Repo.

2. **Adding Udates to the Repos**<br>

- **Add changes to the Staging Area:** <br>
This command add push your changes to the staging area in your local repo.

  ```git add .```
  
- **Commiting Changes to the Local Repo:**

  ```git commit -m "add commit message" .```

- **To Check Repo Status:**

  ```git status```

- **To Check List of Commits:**

  ```git log```

- **Commiting Changes to the Remote Repo:**

  ```git branch -M main```

  ```git push -u origin main```

  

\## Cloning a  remote Repository

* Open the project in your remote repository

* Click on the \[**Code**] the green button on your right

* Copy the Https link

* Open the \[**Terminal**], then the directory where you want the project to be saved and run these commands:

* \[**git clone**] then paste the copied \[**Link**]

* It will save a copy of the project in this directory.

\## Branching and Merging

* Open the repo you want to create a branch

* Click on \[**main**] on the left of the screen

* Enter the branch name to create a branch


&nbsp;

