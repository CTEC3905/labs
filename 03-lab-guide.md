## Exercise 1: solution to last week's lab exercise

1. Navigate to your CTEC3905 labs folder and open a command prompt (CMD in Windows or terminal on OSX) in that folder, or you can shift-right-click and select Open Powershell or Command prompt. NOTE: if you have a "02-lab" folder there, rename it to "02-lab-my-code" or something else, because the lab code folder you're about to clone is also called "02-lab"
2. Type in `git clone https://github.com/CTEC3905/02-lab.git` (NOTE: you may need to log in with your GitHub credentials at this stage, more than once, so just keep signing in!) - you can ignore the separate first-time git setup request asking for your email etc. - it's not needed)
3. Open this folder in Atom and look through all the code
4. Open your own code from last week and compare it with the solution
5. If your code is very close, nice work! If not, take note of how you can simplify or improve your solution

---

## Exercise 2: introduction to GIT

1. Open a command prompt in the folder containing the code that you wrote last week and type `git status` which should tell you that it’s not a GIT repository
2. Type `git init` to turn your code into a repository, then `git status` which will show your files not yet added in **red**
3. Type `git add .` (the dot is a wildcard that means “all files”) - this “stages” your files ready for saving. Type `git status` again to see that your files are now coloured **green**
4. Type `git commit -m "my first commit"` which will save or “commit” your “staged” files to the repository
5. Now, make a simple change to your code and type `git status` again - your changed file will be coloured **red**. Repeat steps 3 and 4, using a different commit message in step 4

---

## Exercise 3: introduction to GitHub

1. Sign in to your GitHub account and create a new repository - do not add a readme file or change any of the default options
2. The next GitHub screen will show the **URL for your new repository** which we’re going to use to add your files from lab 02. Make a note of this URL or copy it
3. From the command prompt inside your 02-lab repository folder, type `git remote set-url origin your_repo_url.git` (replace `your_repo_url.git` with the URL from step 2), then check that it’s correct by typing `git remote -v`
4. `git status` will check if your repo is ready to go (if not, “add” and “commit” as in steps 3 and 4 in the previous exercise), then `git push -u origin master` will push your code to GitHub and set the remote for this repo permanently - after this, in future `git push` is all you need - reload your repository page on GitHub and your code should have appeared
5. Add a file “readme.md” - .md means [Markdown (GitHub guide here)](https://guides.github.com/features/mastering-markdown/) which is a simplified syntax for writing semantically-structured text. In the “readme.md” file, type a title “# 02-lab code” (a single `#` is Markdown for `h1`), two newlines and the sentence “Code from CTEC3905 second lab” (which will automatically create an HTML `p` tag on your GitHub code page), then in the command prompt type `git add .` and `git commit` as before, then `git push`. Wait for GIT to finish pushing your code to GitHub, then reload the GitHub page to see your changes

---

Now **follow this link to the [GitHub classroom](https://classroom.github.com/a/s7_vowLZ)** (you may be asked to log into your GitHub account). You must then find your P-number from the (sorry very long) list. This will generate a repo and simple starter code in the CTEC3905 organisation. You then need to **clone this repo to the computer on which you are working**. This is the repo for your assignment code. This is private, so can be viewed only by you and module staff. You can now push any work you do on your assignment to this repo. **If you have existing code, please examine the starter files carefully** before adding any of your own code to them - they contain essential code required for the assignment.