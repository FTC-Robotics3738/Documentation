# Github 101
## Terminology
- Repository
  - Repo for short
  - Its a folder that a project sits in
- Organization
  - Org for short
  - Orgs have many repos inside of them that correlate with a team/company/organization
- Branch
  - A branch is a clone of a repo that is meant for a single person to make their changes to
  - There is also `Main`/`Master` branch which should have only fully working code
  - When you want to make a change to `Main` you `checkout` a new branch from it, make all your changes to that, then make a `Pull Request` (Also known as `Merge Request`) to have people review your changes
- Pull Request
  - When your changes are complete and you have tested it and are ready to add it to `Main` you create a `Pull Request` (`PR`).
  - Sometimes called `Merge Request` (`MR`)
  - With most repos on this org, it will be set so 2 people have to approve your PRs for you to have the ability to merge it to master
  - A pull request is based off a `Branch`, so if you make a PR, you can still add stuff to your branch and `push` it up without having to make a new PR
- Merge Conflict
  - This is what occurs when your `branch` is changing something that was changed by someone else since you last branched. 
  - When you get one of these, you have to carefully go through the areas where there are issues to determine what to keep/change
- Local vs Remote
  - Local is the repo as you have on your computer
  - Remote, also called `Origin`, is what Github has online that everyone can see
- Commit
  - You can think of a commit like a package that holds all changes you add to it when you are ready
  - You have to add a message to a commit to finalize it
- Push
  - A push occurs when you have at least 1 `commit` ready and it will send it to the branch you are on (assuming you have permissions to push to it!)
  - Assuming I set things up correctly, you should not be able to push to `Main` branches, but you can push to your own branches
- Git vs Github
  - Git is an application that lets you have source control and repos and such. 
  - Github is an implementation of Git
---

## Getting Started
### Account Creation
- This is just like any other website sign up, if you do not have an account yet, [click here](https://github.com/signup?ref_cta=Sign+up) and it will take you to the sign up page. I recommend using your personal email so you can show your origins in the future

### Environment Setup
- There many tools to use Git, you can use a GUI application or the terminal, if this is your first time using Git software, I recommend starting with a GUI tool as it will help you along and you will not need to memorize commands. 
- To start, you can install [this git tool](https://git-scm.com/downloads), it comes with both the terminal client and a GUI.
  - Check the guide on how to setup Git
- Additionally, you will want to download [Visual Studio Code](https://code.visualstudio.com/download) (VSC) as this will be where you write code. We will set this up in a little bit