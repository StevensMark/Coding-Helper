# Coding Workout
Practice these coding skills daily until they become part of working memory.

*****

## Steps for using Git in a sotware dev group project


### Clone repository to local machine

1. Create project folder
2. Point to project folder in the command line
3. Clone the repository using the SSH url

```markdown
git clone [ SSH url ]
```

### Create new branch

```markdown
git checkout-b [branch name]
```

### Open VS Code

```markdown
code .
```

Build project and/or edit code

### Stage the new code

```markdown
git add .
```

### Commit the new code
Include a short, clear message describing the new code or code revisions

```markdown
git commit -m "[message]"
```
### Push the branch to the repository
 
```markdown
git push --set-upstream origin [branch name]
```


# Resolve Common Errors

*****

## npm ERR! code ERESOLVE
ERESOLVE unable to resolve dependency tree


```markdown
npm config set legacy-peer-deps true
```

source: https://www.youtube.com/watch?v=vn97BdYx2K8

<!--- Comments
Create a new repository on the command line

```markdown
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:[GitHub account]/[Repo name].git
git push -u origin main
```

…or push an existing repository from the command line

```markdown
git remote add origin git@github.com:[GitHub account]/[Repo name].git
git branch -M main
git push -u origin main
```
-->

<!--- Comments

```markdown
# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

-->



