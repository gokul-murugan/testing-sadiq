local   --> your PC
remote  --> Repo

1) Freshly creating a REPO

- git init     ==> Initialise your local 
- git status   ==> Status of you changes
- git add * (or)
  git add . (or)
  git add --all
    (OR) 
  git add <Filename>

- git rm --cached <Filename>
- git commit -m "<message>"
- git remote add origin <repo-link>
- git push 
   

2) REPO already exist but you are adding new codes/features

- git clone <repo-link>           ==> Take a copy of the code to your local
- git checkout -b <branch_name>   ==> Create a new branch
- git branch                      ==> check the current branch that you are working
- git diff                        ==> Comparison between your previous and current state


Different branch
feature
bugfix
release

