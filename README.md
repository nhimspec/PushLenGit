## GIT HELPER ##

### …or create a new repository on the command line ###

```bash
  echo "# PushLenGit" >> README.md
  git init
  git add README.md
  git commit -m "first commit"
  git remote add origin https://github.com/nhimspec/PushLenGit.git
  git push -u origin master  / git push origin --mirror
```

### …or push an existing repository from the command line ###

```bash
  git remote add origin https://github.com/nhimspec/PushLenGit.git
  git push -u origin master
  …or import code from another repository
  You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
```
