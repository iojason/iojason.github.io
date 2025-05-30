# Linker
[Linker] is a landing page to connect your entire social media in one place (similar to [Linktree]).

This is part of a free tutorial that I host to help students learn basic web development by building their own profile webpage and hosting it for free on [GitHub Pages]. 

**You can skip to [Quick Use](#quick-use) to *quickly* deploy your Linker page.**

## How To Use This Tutorial
`git checkout main` = project intro.

`git checkout start` for the tutorial.

`git checkout complete` for the final code.

## What You Will Learn In Class
- How to create your own landing page to reference all your social media contents in a single minimalistic place.
- A Tree called DOM.
- HTML, CSS, JavaScript/JS
- GitHub - how to version control your project. A key skill that every developer needs to know to track code changes.

## Tech
- HTML 
- CSS
- JavaScript/JS
- [GitHub]
- [Visual Studio Code] 
- [Material Design by Google]

## Quick Use
Create a [new repository in GitHub] named as username.github.io (replace **username** with your github username)

Clone the new repository you just created
```
git clone https://github.com/username/username.github.io
```

Clone the **linker** repository and switch to branch **complete**
```
git clone https://github.com/iojason/linker.git
git checkout complete
```

Move everything within the **linker** directory into your *username.github.io* folder, then delete **linker**.
```
mv linker/* username.github.io
rm -d linker
```

Open up [VS Code] or your favorite IDE and make the necessary updates (name, tag, background image, labels/links) within index.html and linker-style.css files (I might make this easier later. Yes, always care about UX).

Then do a simple git push
```
git add -A
git commit -am "my linker page."
git push
```


## Things I Would Add
Google Analytics, API integration, Subsciption, Alerts, and many other ideas I have. 

## See a Bug?
email me at hi@iojason.com

## License

MIT

**It's FREE. Oh yeah!**

Like this project? [Buy me a 🍕](https://www.buymeacoffee.com/iojason)

> Technology is best when it brings people together.
> —Matt Mullenweg


*Appreciate the love*

Jason


[Linker]: <https://github.com/iojason/linker>
[LinkTree]: <https://linktr.ee/>
[Material Design by Google]: <https://m2.material.io/>
[Visual Studio Code]: <https://code.visualstudio.com/>
[VS Code]: <https://code.visualstudio.com/>
[GitHub]: <https://github.com/>
[GitHub Pages]: <https://pages.github.com/>
[new repository in GitHub]: <https://github.com/new/>
