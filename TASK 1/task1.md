**c**

**Dell@YUTA MINGW64 \~ (master)**

**$ cd /d**



**Dell@YUTA MINGW64 /d**

**$ mkdir student-portfolio**



**Dell@YUTA MINGW64 /d**

**$ cd student-portfolio**



**Dell@YUTA MINGW64 /d/student-portfolio**

**$ git init**

**Initialized empty Git repository in D:/student-portfolio/.git/**



**Dell@YUTA MINGW64 /d/student-portfolio (master)**

**$ git status**

**On branch master**



**No commits yet**



**nothing to commit (create/copy files and use "git add" to track)**



**Dell@YUTA MINGW64 /d/student-portfolio (master)**

**$ notepad readme.md**



**Dell@YUTA MINGW64 /d/student-portfolio (master)**

**$ git status**

**On branch master**



**No commits yet**



**Untracked files:**

&#x20; **(use "git add <file>..." to include in what will be committed)**

&#x20;       **readme.md**



**nothing added to commit but untracked files present (use "git add" to track)**



**Dell@YUTA MINGW64 /d/student-portfolio (master)**

**$ git add readme.md**



**Dell@YUTA MINGW64 /d/student-portfolio (master)**

**$ git status**

**On branch master**



**No commits yet**



**Changes to be committed:**

&#x20; **(use "git rm --cached <file>..." to unstage)**

&#x20;       **new file:   readme.md**





**Dell@YUTA MINGW64 /d/student-portfolio (master)**

**$ git commit -m "INITIAL COMMIT WITH README"**

**\[master (root-commit) 0c26aac] INITIAL COMMIT WITH README**

&#x20;**1 file changed, 8 insertions(+)**

&#x20;**create mode 100644 readme.md**



**Dell@YUTA MINGW64 /d/student-portfolio (master)**

**$ git log --oneline**

**0c26aac (HEAD -> master) INITIAL COMMIT WITH README**



**Dell@YUTA MINGW64 /d/student-portfolio (master)**

**$ notepad .gitignore**



**Dell@YUTA MINGW64 /d/student-portfolio (master)**

**$ echo Application started > app.log**



**Dell@YUTA MINGW64 /d/student-portfolio (master)**

**$ git status**

**On branch master**

**Untracked files:**

&#x20; **(use "git add <file>..." to include in what will be committed)**

&#x20;       **.gitignore**



**nothing added to commit but untracked files present (use "git add" to track)**



**Dell@YUTA MINGW64 /d/student-portfolio (master)**

**$ git status --ignored**

**On branch master**

**Untracked files:**

&#x20; **(use "git add <file>..." to include in what will be committed)**

&#x20;       **.gitignore**



**Ignored files:**

&#x20; **(use "git add -f <file>..." to include in what will be committed)**

&#x20;       **app.log**



**nothing added to commit but untracked files present (use "git add" to track)**



**Dell@YUTA MINGW64 /d/student-portfolio (master)**

**$ git add .gitignore**



**Dell@YUTA MINGW64 /d/student-portfolio (master)**

**$ git commit -m "added gitignore"**

**\[master c8553f8] added gitignore**

&#x20;**1 file changed, 3 insertions(+)**

&#x20;**create mode 100644 .gitignore**



**Dell@YUTA MINGW64 /d/student-portfolio (master)**

**$ git log --oneline**

**c8553f8 (HEAD -> master) added gitignore**

**0c26aac INITIAL COMMIT WITH README**



**Dell@YUTA MINGW64 /d/student-portfolio (master)**

**$**



