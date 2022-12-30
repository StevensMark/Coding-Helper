Practice these coding skills daily until they become part of working memory.

# Table of contents
1. [Introduction](#introduction)
2. [Some paragraph](#paragraph1)
    1. [Sub paragraph](#subparagraph1)
3. [Another paragraph](#paragraph2)

## This is the introduction <a name="introduction"></a>
Some introduction text, formatted in heading 2 style

## Some paragraph <a name="paragraph1"></a>
The first paragraph text

### Sub paragraph <a name="subparagraph1"></a>
This is a sub paragraph, formatted in heading 3 style

## Another paragraph <a name="paragraph2"></a>
The second paragraph text

*****

# Build new project using Bitbucket

1. Create new repository in Bitbucket
2. Clone repository to local machine
3. Build project; i.e. Gatsby, Angular, etc
4. Push changes to Bitbucket

### Create new repository in Bitbucket

[![chrome-KSo-Ply-Bh95.png](https://i.postimg.cc/G2hVJSqq/chrome-KSo-Ply-Bh95.png)](https://postimg.cc/SX3gmV0M)


### Clone repository to local machine
On local machine, point to the directory where you want the Bitbucket repo cloned. In this example, it will be inserted in the Dev folder.

```markdown
C:\Users\StephenMBassett\Dev -> git clone git@bitbucket.org:stephenmbassett/my-new-project.git
```

### Build project
Example: Building a Gatsby starter landing page. Build within my-new-project folder.

```markdown
C:\Users\StephenMBassett\Dev/my-new-project -> npx gatsby new my-homepage https://github.com/gatsbyjs/gatsby-starter-contentful-homepage
```


### Push changes to Bitbucket
Point to repo directory

Add all changes to git
```markdown
C:\Users\StephenMBassett\Dev/my-new-project -> git add .
```

Commit changes to git
```markdown
C:\Users\StephenMBassett\Dev/my-new-project -> git commit -m 'first commit'
```

Push changes to git
```markdown
C:\Users\StephenMBassett\Dev/my-new-project -> git push
```


# Steps for using Git in a software dev group project


### Clone repository to local machine

1. Create project folder
2. Point to project folder in the command line
3. Clone the repository using the SSH url

```markdown
git clone [ SSH url ]
```

### Create new branch

```markdown
git checkout -b [branch name]
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
Best practice when commiting multiple code changes is to combine those commits into
a single commit, before pushing to the repository. For example, if you made 4 commits,
then...

```markdown
git reset --soft HEAD~4
git status
git commit -m "styling ideas"
git log master.. --oneline
git push --set-upstream <name-of-branch>
git push -f
```

### Push the branch to the repository
 
```markdown
git push --set-upstream origin [branch name]
```
<br>

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

# Angular
*****

### Install Angular to your system
```markdown
npm install -g @angular/cli
```

### Cmd to check Angular version
```markdown
ng version
```

### Creating new Angular project
```markdown
ng new "name-of-project"
```

### Cloning an Angular repo
Remember to install packages!

```markdown
npm install
```


