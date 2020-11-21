## Branch

### Rename Branch

````bash
git branch -m [old branch name] [new branch name]
````

<br><br>

## Config

### Display Configuration Properties and Values

```bash
git config --list
```

<br>

### Set or update Git User Email Globally

```bash
git config --global user.email 'my-new-email@company.com'
```



<br><br>



## Pull

### Allow pulling unrelated history from remote branch

```bash
git pull [remote name] [branch name] --allow-unrelated-histories
```



<br><br>



## Remote

### Add remote repo

- `[remote name]` can be any name.  By convention it is called origin.

  ```bash
  git remote add [remote name] [repo url] 
  ```

  