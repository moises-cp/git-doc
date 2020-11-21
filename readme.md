[TOC]





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

### Set or update Properties

```bash
git config [config file location] [property] [value]		
```

- `[config file location]`

  <img src="./asset/img/config-file-location-500w-min.jpg" alt="Git config file location options" style="zoom:80%;" />

- `[property]`

  - Property can be seem with `git config --list`
  - Ex.  `user.name`, `user.email`, `remote-origin-url`, etc

- `[value]`

  - Ex. `'value'`

<br>

#### Examples

Setting or Updating Global Name 

```bash
git config --global user.name 'first-name last-name'
```

Setting or Updating Global Email

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

```bash
git remote add [remote name] [repo url] 
```

- `[remote name]` 
  - Can be any name.  
  - By convention it is called `origin`

