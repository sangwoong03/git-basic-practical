## Git commander exercise

---

### SUMMARY

```
$ git init
$ git remote add orgin
$ git add
$ git commit
$ git push origin master
$ git branch
$ git switch
$ git merge
```

I used to use GitKraken application for mananging my programming files.
So, I found that when I am coding without like those programs, I cannot manage my code versions, even hard to share with others.

This repo is just few files for exercising git commmand with my editor, Visual Studio code.

<br>

### 📌 Initialize

---

When uplaod your project files to gihub repository, we should initialize directory.

**Commands:**

```
  git init
```

<br>

### 📌 Remote Repository

---

We can manage our project files on our computer, local computer.
However, we need to share codes when programming, especially for collaborations.

Github helps us this, and it called `remote repository`

**Commands:**  
`github-id` : github user id  
`repository.git` : repository name in github site

```
  gir remote add origin https://github.com/github-id/repository.git
```

<br>

### 📌 Add file

---

Choose files that I want to upload.

If want to all updated files, just write `. (dot)` instead of each files' name.

**Commands:**

```
  git add "file name"

  git add "."
```

<br>

### 📌 Commit

---

After adding each or all files, we can send to file and message of our works.
The command `commit` is same as history of our project.
We can check the previous versions of our project or each files.

**Commands:**  
`-m` : command for write messages.  
`messages` : we can use any words or sentences, however when collaboration,

```
  git commit -m "messages"
```

<br>

### 📌 Push

---

After we made the versions' of our projects, we can share each stages to others with `push`

**Commands:**  
`branch-name` : write the name of branch (e.g. master)

```
  git push origin "branch-name"
```

<br>

### 📌 Branch

---

In developing process, we developers are used to program (coding) like develop and edit, or debug.
On these steps, developers have to share their each source codes based on their original version.

Branch helps us this easily.  
Through branch, there are various ways to manage file versions and even to develop the newest another version.

**Commands:**
`name` : Select any name for branch

```
  git branch "name"
```

<br>

This command is for move to each branches in repository.  
`branch name` : Write a branch name that exist in repository to move and work in that branch.

```
  git switch "branch name"
```

<br>

### 📌 Merge

---

In the steps of testing or debugging of project using some branches, it is essential to `merge` for testig whole codes.
And more, if we made more developed versions or the newest one, we are likely to change the version.

`Merge` can help us.
Before we merge files, check out the branch where we are.
**Command:**
`branch name` : Write the name of branch choosed to merge

```
  (e.g. switch to master branch)

  git swtich master

  git merge "branch name"
```
