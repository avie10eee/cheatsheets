
## Git CheatSheet

**setup a repo**
`git init -b [branch name] = initalizes the repository`

**clone or add an existing repository**
>`git clone [url]`
`git remote add origin [url] = adds remote from a url`
`git remote -v = verifies the remote repository`

---

>**add files**
>>- `git add . = adds all files to index (ESSENTIAL)`
>> - `git add [file] = adds a file to the index`

---

**tagging**
>`git tag -a [version-number] -m "[description]"`

**commiting**
>use the after the setup instead of `git add .`
`git commit -am "[commit message]" = commit and stage your changes with a message`

---

**pull**
>`git pull origin [repo]`

**push**
>`git push -u [remote-name] ([branch-name]optional)`

------------------------------------------------------------------------------------

**branch stuff**
>`git branch = list branches`
`git checkout = go to a branch`
`git checkout [new-branch] = make new brach and switch to it`
`git merge [current branch name] = merge this branch to main`
`git merge master = merge master into your branch`