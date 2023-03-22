hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use 
## Make a global main branch 
```bash
git config --global init.defaultBranch <name>
```

## Initialize a main branch
```bash
git branch -m <name>
```
## git config --global user.name "Your Name"
   
```bash
 git config --global user.email you@example.com
```

## After doing this, you may fix the identity used for this commit with:

```bash
 git commit --amend --reset-author
```
