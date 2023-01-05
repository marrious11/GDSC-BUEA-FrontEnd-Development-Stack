# The-Odin-Project-mate
 The Odin Project is one of those "What I wish I had when I was learning" resources.
This project is designed to fill in the gap for people who are trying to hack it on their own but still want a high quality education.

#  Full Stack JavaScript- PROGRAM 2022/2023 

This is a repository where we will be sending our exercices and track our progrogress.

## How can I submit my work for the first time?

Prerequisite Fork and Make the project available locally. and clone the project form your repository.

How to fork a repo coul be ound here

**Fork rule*

  - fork the repository into yours
  - while you are doing the fork uncheck this box[copy the {main} branch only], to enable you to copy all the branches
  - now you are on your repository from here you click on code and copy the link as shown by the arrow
  - and you enter git clone plus the link you just copy 

Create a branch for the task

```
    git branch -M my-mates

    git checkout my-mates
```

After that, follow the steps below.
Step 1: under every question you create a new file having as name you github handle(username) (e.g (filename=`<marrius11.js>) and answer the question there
Step 2: Commit the change made and push

```
   git add <githubusername.js> 
   
    git commit -am "The odin exercise  from <githubHandle or githubusername>"

    git push -u origin my-mates
```

**if you did many question at once use:**

```
   git add .
   
    git commit -am "The odin exercises[1 to 3] from <githubHandle or githubusername>"

   git push -u origin my-mates
```

Come back to our github repo here and do a pull request.

![open a pull request](https://i0.wp.com/user-images.githubusercontent.com/3477155/52671177-5d0e0100-2ee8-11e9-8645-bdd923b7d93b.gif?resize=1024%2C512&ssl=1)

## Submission

To submit your task, create a pull request to this repository. You can find more information about how to create a pull request [here](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

- Done!

## Second submission
 
 just continue from step 1

## To Check for Updates

This command will help  us stay up to date with changes made in the Odin project repository.
So, before you start writing code and carrying out `git commands and pull requests`, first run the update command.

```
git push origin HEAD
```
