# Intro to colaboration using git

We are going to create a README file colaboratively. The idea is that we practice the git commands and the workflow of colaboration through git, as well as we can learn what can we do when a conflict hapens. 

We have a new github profile for the [Life History Evolution](https://github.com/Life-History-Evolution-Research-group) lab, and the plan is to write a simple description of the lab, that will apper in the profile page. 
You can use the [lab website](https://www.helsinki.fi/en/researchgroups/life-history-evolution) to get a description of the lab or any other informaton, but you don't need to add a too long description. 

Follow the instruction given during the workshop. Here you will find some resources that could help you during the activity. 

## Git commands

We recomend that you do the activity using the git bash (the command line) in your own computer during the activity. You can do everything directly on github webpage, but it will not help to get familiar with the git commands and the workflow of colaborating. 

Here is just a list of useful git commands that can help you throught the activity: 

```
git clone [REPO-URL] # to clone a repository to your local folder
git add [path/to/file] # to stage a file
git commit -m "add the message" # to commit your staged files
git push # to push (upload) your commits to the remote repository (github)
git pull # to pull (download) remote repo to your local repo. It updates your local repository
git status # to check the files you have changed, add or that are staged (ready to commit) 

git log # see history of commits and their messages, newest first
git graph #see a detailed graph of commits. Create this command with 'git config --global alias.graph "log --all --graph --decorate --oneline"'

```

Here you can find a [cheatsheet for git](https://aaltoscicomp.github.io/cheatsheets/git-the-way-you-need-it-cheatsheet.pdf). 

## Markdown

Files with .md use markdown to format the text. With markdown you add style to your text file easily. 

You can create headers, put emphasis on text with *italics* or **bold**. 
You can create list:
- item 1
- item 2
- item 3

You can share links, code chuncks and even add images to your rendered files. 
Here you can find a [cheatsheet for Markdown](https://www.markdownguide.org/cheat-sheet/)

For example with the folloing code is displaying here the image from the lab webpage.
 `![](https://www.helsinki.fi/assets/drupal/s3fs-public/styles/hero_image/public/migrated-research-group/paragraph-images/cinxia_wing.png.webp?itok=-70oP6Fj)` 

`![](https://www.helsinki.fi/assets/drupal/s3fs-public/styles/hero_image/public/migrated-research-group/paragraph-images/cinxia_wing.png.webp?itok=-70oP6Fj)



