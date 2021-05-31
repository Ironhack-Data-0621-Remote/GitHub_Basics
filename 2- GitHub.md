# Cloning a repository 

- [Cloning a repository](#cloning-a-repository)
  - [**Cloning a repository using the command line (terminal)**](#cloning-a-repository-using-the-command-line-terminal)
      - [**¿How to clone a new repo?**](#how-to-clone-a-new-repo)
  - [**Cloning a repository to GitHub Desktop**](#cloning-a-repository-to-github-desktop)
      - [**¿How to clone a new repo?**](#how-to-clone-a-new-repo-1)

Git is a version control software. It trackes the changes made to a document or a group of documents. We could use git and Github throught the terminal or using GitHub desktop


## **Cloning a repository using the command line (terminal)** 

1. Go to github and create an account: https://github.com

2. Tell git what your github info is:

    ⚠️ Please do make sure that you replace “YOUR_GITHUB_USERNAME” by your actual username. Same with your email. ⚠️

        git config --global user.name “YOUR_GITHUB_USERNAME”

        git config --global user.email YOUR_EMAIL@DOMAIN.COM

3. Run this command so that you won't be asked your github password every time:

        git config --global credential.helper store

We are doing this so that next time you want to use git, you won't be asked for your password.


#### **¿How to clone a new repo?**

**1. On GitHub, navigate to the main page of the repository.** 

**2. Above the list of files, click `Code`.**

You can clone a repository to create a local copy on your computer and sync between the two locations (in local and remote). ﹗ When you clone a repository, you copy the repository from GitHub to your local machine﹗

![clone](https://github.com/Ironhack-Data-0621-Remote/GitHub_Basics/blob/main/Images/clone_repo_terminal.png)

**3. Open Terminal.**

**4. Change the current working directory to the location where you want the cloned directory.**

**5. Type git clone, and then paste the URL you copied earlier.**

        git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY

**6. Press Enter to create your local clone.**

        git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
        > Cloning into `Spoon-Knife`...
        > remote: Counting objects: 10, done.
        > remote: Compressing objects: 100% (8/8), done.
        > remove: Total 10 (delta 1), reused 10 (delta 1)
        > Unpacking objects: 100% (10/10), done.
        ---
---


## **Cloning a repository to GitHub Desktop**

1. Go to github and create an account: https://github.com

2. Go to github website and download the application: https://desktop.github.com/


#### **¿How to clone a new repo?**

**1. On GitHub, navigate to the main page of the repository.**

**2. Above the list of files, click  `Code`.**  

![repo](https://github.com/Ironhack-Data-0621-Remote/Classroom-Materials/blob/main/Images/clone_repo_terminal.png)


**3. Click `Open with GitHub Desktop` to clone and open the repository with GitHub Desktop**  

![clonedesktop](https://github.com/Ironhack-Data-0621-Remote/GitHub_Basics/blob/main/Images/clone_desktop.png)

**5. Click `Choose...` and, using the Finder window, navigate to a local path where you want to clone the repository.**
![choose](https://github.com/Ironhack-Data-0621-Remote/GitHub_Basics/blob/main/Images/choose...png)

**6. Click `Clone`.**
