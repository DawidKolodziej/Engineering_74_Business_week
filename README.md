
## Repos

- Go to [Github](www.github.com) make a new repo
- With your folder from before open in Bash
- `git init` => Initialize a repo
- If you have files in that folder use `git add <file_name>`
- If you want to add all files `git add *` or `git add .`
- To add all files with similar name `git add some_*` => `*` is an ANY sign in linux
- If you want to make a file `touch FILE_NAME.FORMAT`
- Example: `touch README.md`
- Edit the file either by manually opening it on your Explorer
- or use `nano README.md` => Save with `CTRL + X` => `y`
- `git commit -m "commit name"` => Commit all the files
- `git branch -M main` => Makes the "main" branch
- `git remote add origin git@github.com:USER_NAME/Repo_name.git` => Link your folder to the github repo you've created (step 1)
- `git push -u origin main` => Uploads all files
- If you don't get any errors => PROFIT £££
- If you make changes to any files:
- You need to add those files again (as above)
- Make a new commit (again)
- Push to origin
- Essentially everything again apart from `init` and `branch` if you not switching branches

### Notes

- Github Desktop skips the entire [Repos](https://github.com/deviljin112/Sparta/tree/master/Day_2#repos) section
- Allows for easy push, pull, branch selection etc etc.
- Visual Studio Code (VSC) => Allows for ease of coding in any language
- Also allows for Git Management directly as you code
