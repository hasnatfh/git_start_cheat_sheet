## …or create a new repository on the command line
```
echo "# Just-start" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:hasnatfh/Just-start.git
git push -u origin main
```

## …or push an existing repository from the command line
```
git remote add origin git@github.com:hasnatfh/Just-start.git
git branch -M main
git push -u origin main

```

    ### To clone a repo form github:
    
  ```
  git clone <HTTPS>/URL
  ```

## After modifying the file: 
Do 4 steps 

1. Status
``` 
git status
```
	
2. Add
``` 
git add [FILENAME] [FILENAME] [...] 
```

Example: 
```
git add README.md 
```
	
For all files: 
	
``` 
git add --all 
```
or,
```
git add . 
```
	
3. Commit
``` 
git commit -m "Added README.md with good description in it."
```
4. Push 
``` 
$ git push [remote name] [branch name]
```

Example: 
``` 
git push -u origin main

```
For bitbucket:	
``` 
git push -u origin master

```	
Done! Our Modified file uploaded in to the repository
	
	
…or create a new repository on the command line	
	echo "# Fffrepo" >> README.md
```	
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:hasnatfh/repo-2.git
git push -u origin main
```	
```	
…or push an existing repository from the command line	
git remote add origin git@github.com:hasnatfh/repo-2.git
git branch -M main
git push -u origin main	
```	
	
	.......................................
		
	.........Editable ....................
	
…or create a new repository on the command line	
	echo "# This is title" >> README.md
```	
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:hasnatfh/repo-2.git
git push -u origin main
```	
```	
…or push an existing repository from the command line	
git remote add origin git@github.com:hasnatfh/rssfeed-finiara-upwork.git
git branch -M main
git push -u origin main	
```	
	
..........push after editing or adding a new file.............................
```	
git add .
git commit -m ""
git push -u origin main
```
add and commit [together](short form) 
```
git commit -a -m "Updated "
```
...for bitbucket...	

```
git push -u origin master 	
	
```
	

..........pull ( update local file ) when you/anyone edit file in Github.............................	

```
git pull origin
```
	
..........see if the file edited in Github.............................	
	
```
git fetch origin	
```	
	

## How to disable git for some project and other project not disable git in Visual Studio Code?


Below snippet would be added into  `.vscode/settings.json` </em> to apply for that workspace only:
```
{
    "git.enabled": false
}
```

Here's an example folder structure:
```
myproject/
├── .vscode/
│   ├── settings.json <----
├── html/
│   ├── index.html
│   └── 404.html
└── js/
    ├── bootstrap.js
    └── bootstrap.min.js
```
	
	
	
	
	
	
	
	
	
	
	
	
	
	
