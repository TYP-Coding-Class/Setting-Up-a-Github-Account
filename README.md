


![images (1) (1)](https://user-images.githubusercontent.com/79866006/158033705-572f3390-ad06-47b0-892c-64280d925da9.png)


<p align="center"> 
  
  <a href="https://github.com/TYP-Coding-Class" alt="TYP coding Class">
        <img src="https://img.shields.io/badge/GitHub-TYP Coding Class-93b023?&style=for-the-badge&logo=github&logoColor=white" /></a>
 <a href="https://docs.github.com/en/get-started/quickstart/hello-world" alt="Github Docs sub site">
        <img src="https://img.shields.io/badge/sub_web-4285F4?style=for-the-badge&logo=Google-chrome&logoColor=white" /></a>
 <a href="https://github.com/github/docs" alt="Github Docs">
        <img src="https://img.shields.io/badge/Creator-Github Docs-93b023?&style=for-the-badge&logo=github&logoColor=white" /></a>
 <a href="https://docs.github.com/en" alt="Github Docs site">
        <img src="https://img.shields.io/badge/main_web-4285F4?style=for-the-badge&logo=Google-chrome&logoColor=white" /></a>
  
</p>  
  
 <p align="center"><b>
How To Open a Github Account step by step 
  </b></p>

# Introduction

GitHub is a code hosting platform for version control and collaboration.
It lets you and others work together on projects from anywhere.

This tutorial teaches you GitHub essentials like repositories, branches, commits, and pull requests.
You'll create your own Hello World repository and learn GitHub's pull request workflow, a popular way to create and review code.

In this quickstart guide, you will:

- Create an Account
- Create and use a repository
- Start and manage a new branch
- Make changes to a file and push them to GitHub as commits
- Open and merge a pull request


## Creating an Account

To create an an Account go to <a href="http://github.com/" target="_blank"> GitHub</a> and Sign In using your details


## Creating a repository

A repository is usually used to organize a single project. 

Repositories can contain folders and files, images, videos, spreadsheets, and data sets -- anything your project needs.

Often, repositories include a *README* file,
a file with information about your project.

*README* files are written in the plain text Markdown language. 

1. In the upper-right corner of any page, use the **+** drop-down menu, and select **New repository**.

![img 1](https://docs.github.com/assets/cb-11427/images/help/repository/repo-create.png)

2. In the **Repository** name box, enter 'hello-world'.
3. In the **Description** box, write a short description.
4. Select **Add** a **README** file.
5. Select whether your repository will be **Public** or **Private**.
6. Click **Create repository**.

![img 2](https://docs.github.com/assets/cb-106613/images/help/repository/hello-world-repo.png)



## Creating a branch

Branching lets you have different versions of a repository at one time.

By default, your repository has one branch named 'main' that is considered to be the definitive branch.

You can create additional branches off of 'main' in your repository.
You can use branches to have different versions of a project at one time. 
This is helpful when you want to add new features to a project without changing the main source of code. 
The work done on different branches will not show up on the 'main' branch until you merge it, which we will cover later in this guide. You can use branches to experiment and make edits before committing them to 'main'.

When you create a branch off the 'main' branch, you're making a copy, or snapshot, of' main' as it was at that point in time. 
If someone else made changes to the 'main' branch while you were working on your branch, you could pull in those updates.

This diagram shows:

- The 'main' branch
- A new branch called 'feature'
- The journey that 'feature' takes before it's merged into 'main' 

![img 3](https://docs.github.com/assets/cb-23923/images/help/repository/branching.png)

Have you ever saved different versions of a file? Something like:

- 'story.txt'
- 'story-edit.txt'
- 'story-edit-reviewed.txt'

Branches accomplish similar goals in GitHub repositories.

Here at GitHub, our developers, writers, and designers use branches for keeping bug fixes and feature work separate from our 'main' (production) branch.
When a change is ready, they merge their branch into 'main'.

#### Create a branch

1. Click the **Code** tab of your 'hello-world' repository.
2. Click the drop down at the top of the file list that says **main**.

![img 4](https://docs.github.com/assets/cb-6252/images/help/branch/branch-selection-dropdown.png)

3. Type a branch name, 'readme-edits', into the text box.
4. Click **Create branch: readme-edits from main**.

![img 5](https://docs.github.com/assets/cb-27383/images/help/repository/new-branch.png)

Now you have two branches, 'main' and 'readme-edits'. Right now, they look exactly the same. Next you'll add changes to the new branch.



## Making and committing changes 

When you created a new branch in the previous step, GitHub brought you to the code page for your new 'readme-edits' branch, which is a copy of 'main'.

You can make and save changes to the files in your repository.
On GitHub, saved changes are called commits.
Each commit has an associated commit message, which is a description explaining why a particular change was made.
Commit messages capture the history of your changes so that other contributors can understand what you’ve done and why.

1. Under the 'readme-edits' branch you created, click the *README.md* file.
2. Click  to edit the file.
3. In the editor, write a bit about yourself. Try using different Markdown elements.
4. In the **Commit changes** box, write a commit message that describes your changes.
5. Click **Commit changes**.

![img 6](https://docs.github.com/assets/cb-75044/images/help/repository/first-commit.png)

These changes will be made only to the README file on your 'readme-edits' branch, so now this branch contains content that's different from 'main'.



## Opening a pull request

Now that you have changes in a branch off of 'main', you can open a pull request.

Pull requests are the heart of collaboration on GitHub.
When you open a pull request, you're proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch.
Pull requests show diffs, or differences, of the content from both branches.
The changes, additions, and subtractions are shown in different colors.

As soon as you make a commit, you can open a pull request and start a discussion, even before the code is finished.

By using GitHub's '@mention' feature in your pull request message, you can ask for feedback from specific people or teams, whether they're down the hall or 10 time zones away.

You can even open pull requests in your own repository and merge them yourself. It's a great way to learn the GitHub flow before working on larger projects.

1. Click the **Pull requests** tab of your 'hello-world' repository.
2. Click **New pull request**
3. In the **Example Comparisons** box, select the branch you made, 'readme-edits', to compare with 'main' (the original).
4. Look over your changes in the diffs on the Compare page, make sure they're what you want to submit.

![img 7](https://docs.github.com/assets/cb-32937/images/help/repository/diffs.png)

5. Click **Create pull request**.
6. Give your pull request a title and write a brief description of your changes. You can include emojis and drag and drop images and gifs.
7. Optionally, to the right of your title and description, click :gear: next to **Reviewers. Assignees, Labels, Projects**, or **Milestone** to add any of these options to your pull request. You do not need to add any yet, but these options offer different ways to collaborate using pull requests. For more information, see "<a href="https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests" target="_blank">About pull requests.</a>"
8. Click **Create pull request**.

Your collaborators can now review your edits and make suggestions.



## Merging your pull request

In this final step, you will merge your 'readme-edits' branch into the 'main' branch. After you merge your pull request, the changes on your 'readme-edits' branch will be incorporated into 'main'.

Sometimes, a pull request may introduce changes to code that conflict with the existing code on main.
If there are any conflicts, GitHub will alert you about the conflicting code and prevent merging until the conflicts are resolved.
You can make a commit that resolves the conflicts or use comments in the pull request to discuss the conflicts with your team members.

In this walk-through, you should not have any conflicts, so you are ready to merge your branch into the main branch.

1. Click **Merge pull request** to merge the changes into 'main'.

![img 8](https://docs.github.com/assets/cb-13037/images/help/pull_requests/pullrequest-mergebutton.png)

2. Click **Confirm merge**. You will receive a message that the request was successfully merged and the request was closed.
3. Click **Delete branch**. Now that your pull request is merged and your changes are on 'main', you can safely delete the 'readme-edits' branch. If you want to make more changes to your project, you can always create a new branch and repeat this process.


## NOTE

:memo:
:pencil: By completing this tutorial, you've learned to create a project and make a pull request on GitHub.

Here's what you accomplished in this tutorial:

- Creted an Account
- Created an open source repository
- Started and managed a new branch
- Changed a file and committed those changes to GitHub
- Opened and merged a pull request

Take a look at your GitHub profile and you'll see your work reflected on your contribution graph.

For more information about the power of branches and pull requests, see "<a href="https://docs.github.com/en/get-started/quickstart/github-flow" target="_blank">GitHub flow.</a>"

:memo:
:pencil: This Repository is just a copy of the <a href="https://docs.github.com/en/get-started/quickstart/hello-world" target="_blank">GitHub Docs</a>

:memo:
:pencil: All Thanks :pray: and Stars and Medals :trophy: goes to <a href="https://github.com/github/docs" target="_blank">GitHub Docs</a>







































































