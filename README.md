# Git Ignore
- nano ~/.gitignore_global
- example files `.gitignore_global` check on this [link](https://raw.githubusercontent.com/xhilmi/gitignore/master/gitignore-bak) 
- git config --global core.excludesfile ~/.gitignore_global
- git rm --cached -r *
- git add .
- git status
- git commit -m 'ignoring something'
- git push origin master

# Reference
- https://stackoverflow.com/questions/11058207/how-to-get-git-to-exclude-a-local-directory-from-push-to-remote-but-still-part
- https://www.freecodecamp.org/news/gitignore-file-how-to-ignore-files-and-folders-in-git
- https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files
