## Set of commands to setup git repo and create page on GitHub quickly, all from a local Linux terminal window

```
mkdir newDir
cd newDir/
echo 'readme file' > readme.md
git init
git add .
git status
git commit -m 'initial commit'
gh repo create
```

I'm sure someone might tell me this is perhaps not best practice but a condensed version:
```
mkdir newDir
cd newDir/
echo 'readme file' > readme.md 
git init; git add .; git status; git commit -m 'initial commit';
gh repo create
```

## As a bonus, here's the code to include an image in a .md
```
![inlcuding images in a readme.md](https://github.com/<your-name-on-github>/<your-repo>/blob/master/images/readmeMarkdownWithImages.png "Inlcuding images in a readme.md")
```

![inlcuding images in a readme.md](https://github.com/adasMatt/newDir/blob/master/images/terminalScreenshot.jpg "Inlcuding images in a readme.md")
