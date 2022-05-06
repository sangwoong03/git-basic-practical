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
