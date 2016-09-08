---
layout: default
---
# [&#8598;](/) [Creative Coding](.)
ART 2210 Creative Coding is an applied course that focuses on creating internet based projects that impact media and culture. Students will learn current web design and development workflows with an emphasis on networked interaction and visualization. Current trends in online media will be examined with special attention paid to how projects can exist on multiple platforms such as mobile phones, tablets, and desktop computers. Through in-class exercises, projects, critique, hands-on workshops, readings and discussion we will explore the role of the digital artist/designer in a constantly evolving digital landscape. Students will develop an understanding of web technologies in order to implement creative systems.

## Assignments
- [Assignment 1](https://github.com/lsudigitalart/lsuart2210-hw-01)
- [Assignment 2](https://github.com/lsudigitalart/2210hw2)
- [Assignment 3](https://github.com/lsudigitalart/2210hw3)

## Dependencies
- [Class Syllabus](https://docs.google.com/document/d/1yk3bP_PSSpOtV43bXvR_NRi34WBWfM9RBCf83GoEyjQ/edit?usp=sharing)
- [Getting Started with p5.js by Lauren McCarthy](https://www.amazon.com/Make-Interactive-Graphics-JavaScript-Processing/dp/1457186772)
- Atom: <http://atom.io>
- Git: <https://git-scm.com>
- Github: <http://github.com>
- p5.js: <http://p5js.org>

## Notes

### To work on your HW
1. Open terminal.
1. `cd /to/where/you/store/your/classwork`
1. `git clone` your github repo
1. `cd /to/the/name/of/your/repo`
1. Work on your code, see "set up p5js" below.
1. `git add -A` to stage your files
1. `git commit -m "your message here"`
1. `git push`
1. *when you make changes...*
  - `git commit -m "your message here"`
1. *when you add or delete files...*
  - `git add -A`

### Set up a p5js project
1. `cd /to/your/repo`
3. `touch index.html`
4. `touch sketch.js`
5. `curl -LO https://github.com/processing/p5.js/releases/download/0.5.3/p5.min.js`
6. `atom .`

### To create a website from your code
1. `cd /your/code/directory/here`
2. `git checkout -b "gh-pages"``
3. `git push --set-upstream origin gh-pages`
4. visit your website at: http://lsudigitalart.github.io/\<your repo name\>

### Helpful Bash Commands
- List the contents of a directory: `ls`
- Display the present working directory: `pwd`
- Open current directory in atom: `atom .`
- Traverse up a directory: `cd ..`
- Shortcut for home directory: "~"
- Create a directory: `mkdir <dir name>`
- Create an empty file: `touch <filename>`
- delete a file `rm <file>`
- copy a file `cp <source> <destination>`
- hotkey to complete pathnames: "TAB"
- to display contents of a file `cat <filename>`

### Helpful Git Commands
- How to download a repo: `git clone <url of repo>`
- Check status of a local rep `git status`
- Take a peek at any changes made to remote repo: `git fetch`
- Download any changes made to a repo `git pull`
- See what you've done to your repo `git log`

## External Resources

### Processing
- <http://processing.org>
- <http://p5js.org>

### JavaScript
- [JavaScript Basics](https://github.com/processing/p5.js/wiki/JavaScript-basics)
- <http://www.w3schools.com/js>
- <https://developer.mozilla.org/en-US/docs/Web/JavaScript>

### Git
- <http://rogerdudler.github.io/git-guide/>
- <https://www.atlassian.com/git/tutorials/what-is-version-control>

### HTML
- <http://www.w3schools.com/tags/>
- <https://developer.mozilla.org/en-US/docs/Web/HTML/Element>

### Terminal
- <https://github.com/processing/p5.js/wiki/Terminal-and-the-Command-Line>
- <http://computers.tutsplus.com/tutorials/navigating-the-terminal-a-gentle-introduction--mac-3855>

### Misc
- RGB Color Picker 1: <http://www.rapidtables.com/web/color/RGB_Color.htm>
- RGB Color Picker 2: <http://www.w3schools.com/colors/colors_picker.asp>
