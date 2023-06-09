# Git Login Helper
- git config --global credential.helper store
- cat ~/.git-credentials | reference: https://stackoverflow.com/questions/6565357/git-push-requires-username-and-password

# Git Ignore
- nano ~/.gitignore_global
- example files `.gitignore_global` check on this [link](https://raw.githubusercontent.com/xhilmi/gitignore/master/.gitignore_global) 
- git config --global core.excludesfile ~/.gitignore_global
- git rm --cached -r *
- git add .
- git status
- git commit -m 'ignoring something'
- git push origin master

# Git Ignore Template
- Follow and see this [link](https://github.com/github/gitignore)

# Git Commit Autogenerate Message
- Checkout this [link](https://github.com/xhilmi/git-tools/blob/master/.gitconfig)

# Git Size Finder
- https://github.com/github/git-sizer
- https://github.com/jtloong/git-status-size

# Reference
- https://stackoverflow.com/questions/11058207/how-to-get-git-to-exclude-a-local-directory-from-push-to-remote-but-still-part
- https://www.freecodecamp.org/news/gitignore-file-how-to-ignore-files-and-folders-in-git
- https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files
