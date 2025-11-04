# Git-and-Gitlab-practical-assigment
# Git and GitLab Practical Assignment

## Part 1: GitHub Tasks

### Subtask 1: Repository Setup

* Created two repositories on GitHub:

  * One public repository

![](/img/public_Repo_Github.png)
* One private repository

![](/img/priva_repo_Github.png)
### Subtask 2: Local Development

* Cloned both repositories on my local machine using HTTPS.
bash
git clone https://github.com/RajAhire-1/Private_Repo.git
git clone https://gitlab.com/ashish.pawar.kingsman/git-and-gitlab-practical-assigment.git

* In the private repository:

  * Created a new branch called *dev*
  * Added files like index.html and readme.md
  * Made two commits
  * Pushed the *dev* branch to GitHub

  bash 
  git branch Dev
  git add .
  git commit -m "added index.html"
  git push -u origin Dev
  

### Subtask 3: Collaboration Workflow

* Created a Pull Request (PR) on GitHub to merge *dev* into *main*

![](/img/create_pr.png)

* Reviewed and merged the PR
* Verified that the changes appeared in the *main* branch after merging

![](/img/confirm_merge.png)



## Part 2: GitLab Tasks

### Subtask 4: GitLab Repository Setup

* Created a private repository on GitLab

![](/img/private_repo.png)

* Cloned it on my local machine using SSH


* Added a simple project structure:

  * documents/guide.md

  ![](/img/structure.png)

### Subtask 5: Repository Mirroring


### Key Tasks
## GitHub (Part 1)

Create public and private repositories

Work with branches (dev → main)

Practice pull request workflow

Use HTTPS for cloning

## GitLab (Part 2)

Create private repository

Use SSH for cloning

Set up project structure

Configure mirroring from GitLab to GitHub

## Core Concept

#### Learn to maintain synchronized development across two different Git platforms (GitHub and GitLab) while practicing proper version control and collaboration workflows.

#### This assignment focuses on key Git operations, branch management, pull request workflows, and cross-platform repository mirroring.
