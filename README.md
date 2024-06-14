# ai-startup-website

## This project showcases my practical experience with GitHub and Git in implementing collaborative project management using these technologies.

Create an empty file `index.html` and add content to it.

![](./img/1.indexandcontent.png)

- Check the status to observe that it has not been staged.

![](./img/2.statusindex.png)

- Stage the changes

![](./img/3.gitadd.png)

- Commit changes

![](./img/4.gitcommit.png)

- Push main branch to Github

![](./img/5.gitpushoriginmain.png)

## Simulating Tom and Jerry's Work

# TOM'S WORK

- Check current branch

![](./img/6.checkbranch.png)

- Create a new branch for Tom's work

![](./img/7.tombranch.png)

- Open the index.html and add Tom's update

![](./img/8.tomupdate.png)

- Check changes

![](./img/9.statustomupdate.png)

- Stage Tom's changes

![](./img/10.tomstaged.png)


Commit Tom's Changes

![](./img/11.tomcommit.png)

Push Tom's branch to Github

![](./img/12.gitpushtom.png)

### The last command sends Tom's commit from my local branch on my laptop to GitHub (Remote Repository)

# JERRY'S WORK

- Switch back to the main branch

- Pull the Latest Changes

![](./img/13.gitpullorigin.png)

- Create a New Branch for Jerry's Work

![](./img/14.jerrybranch.png)

- Open index.html and Add Contact Information

![](./img/15.jerrycontactinfo.png)

- Stage Jerry's Changes

![](./img/16.jerryadd.png)

![](./img/17.jerrycommit.png)

- Push Jerry's Branch to GitHub

![](./img/18.gitpushjerrywork.png)

## Merging Changes

### After both Tom and Jerry have pushed their changes, myself (or another team member) can review and merge these changesinto the main project. The process involves

1. Creating a `Pull Request`
2. Merging the Pull Request into the `main` branch.

## How to create `Pull Request`

- Navigate to GitHub Repository and switch to the branch that Tom have been working on

![](./img/19.pullrequestTOM.png)

- Create New Pull Request

![](./img/20.newpullrequestTOM.png)

### Review Tom Changes and Create Pull Request.

## Updating Jerry's Branch with Latest Changes

- Swich to Jerry's branch - `git checkout add-contact-info`
- Pull the latest changes from the main branch - `git pull origin main`

- Push the Updated Branch to GitHub: `git push origin add-contact-info`

### The above process demonstrates my proficiency with GitHub and Git in collaborating with other professionals on the same project, utilizing these technologies to manage and divide tasks efficiently.










