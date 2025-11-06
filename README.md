# Introduction to Git and GitHub

## Table of Content

1. [Setting Up a New Git Repository](https://your-link-here.com)
2. [Setting Up a New GitHub Repository](https://your-link-here.com)
3. [Git/ GitHub WorkFlow](https://your-link-here.com)
   
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

  
#### Cloning a Remonte Repository

1. Open the project in your remote repository

2. Click on the &lt;CODE&gt; the green button on your right conner of the page

3. Copy the &lt;URL&gt; 

4. Back &lt;Terminal&gt;, open the directory where you want the project to be saved &lt;cd directory name&gt;

5. Use the command &lt;git clone&gt; then paste the &lt;URL&gt; and &lt;Enter&gt;

The Repository is now saved in the Project Directory.


#### Create a .gitignore File

1. Create a .gitignore file inside your repository.
2. Open with Note Pad and add all the files you want to ignore
3. Use these command to stage and push the file:

  
  ```git add.ignore```
  
  ```git commit -m "commit message"```
  
  ```git push```


#### Branching 

1. Open the repo you want to create a branch

2. Click on &lt;main&gt; on the top-left  side of the page

3. Enter a branch name to create a branch


#### Merging

1. **Check out to the Branch you want to Merge int**:

   ```git checkout main```
   
3. **Update your Branch**:
   Pull the latest changes from GitHub so your branch is up to date:**

   ```git pull origin main```

5. **Merge the other branch into your current branch**

    ```git merge feature-login```

6. **Push the merged branch to GitHub**:

After merging locally, send the changes to GitHub

 ```git push origin main```

 #### Optional: Delete the merged branch<br>

 If you don’t need the feature branch anymore

- Delete locally:
  
   ```git branch -d feature-login```

- Delete on GitHub:

   ```git push origin --delete feature-login```

#### Collaborating with Pull Requests

1. Navigate the agithub repo using owners &lt;URL&gt;

2. On the Top Right hand Conner, click on &lt;Fork&gt;

3. Then below the page on the Right Conner, click on &lt;Create fork&gt;
   The Repo is forked to your github. Below &lt;Code&gt;, your will see &lt;sync fork&gt;

5. Make some changes and commit

6. Go to the forked repo and clkick on &lt;Pull requests&gt; at the top

7. Click on &lt;New pull request&gt;

8. Add your comments and then click on &lt;Comment&gt;

9. Otherwise if you want to close the pull request click on &lt;Close with comment&gt;
   
&nbsp;

