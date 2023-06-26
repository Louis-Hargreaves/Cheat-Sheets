- [Basic writing and formatting syntax for github pages](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [Documentation for GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages)
- [Github and Jekyll - Further customisation of Github Pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll)

To open a repository:
```markdown
- git init
- git >> README.md
- git >> LISCENCE.md
- git >> .gitignore
- pip3 freeze > requirements.txt      #for virtual environment
- git add .
- git commit -m "first commit"
- git branch -M main
- git remote add origin https://github.com/Louis-Hargreaves/React-Tutorial.git
- git push -u origin main
```
To make changes:
```markdown
- git add .
- git branch -M main
- git commit -m "commit"
- git push -u origin main
```

To get repository information onto a local machine
First time (creates a copy):
```markdown
- git clone "repository file location"
```
Not first time: 
```markdown
git pull origin <branch name>
```
