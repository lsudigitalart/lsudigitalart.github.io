---
layout: default
---
# [&#8598;](/) [Creative Coding](.)
ART 2210 Creative Coding is an applied course that focuses on creating internet based projects that impact media and culture. Students will learn current web design and development workflows with an emphasis on networked interaction and visualization. Current trends in online media will be examined with special attention paid to how projects can exist on multiple platforms such as mobile phones, tablets, and desktop computers. Through in-class exercises, projects, critique, hands-on workshops, readings and discussion we will explore the role of the digital artist/designer in a constantly evolving digital landscape. Students will develop an understanding of web technologies in order to implement creative systems.

## 2019 Assignments
- [Assignment 01](https://classroom.github.com/a/YckizPdM)

## 2016 Assignments
- [Assignment 01](https://github.com/lsudigitalart/lsuart2210-hw-01) [(Submissions)](https://github.com/lsudigitalart?q=hw-01) [(Example)](https://github.com/lsudigitalart/2210-hw-01-fredeerock)
- [Assignment 02](https://github.com/lsudigitalart/2210hw2)  [(Submissions)](https://github.com/lsudigitalart?q=2210hw2)   [(Example)](https://github.com/lsudigitalart/2210hw2-fredeerock)
- [Assignment 03](https://github.com/lsudigitalart/2210hw3)  [(Submissions)](https://github.com/lsudigitalart?q=2210hw3)   [(Example)](https://github.com/lsudigitalart/2210hw3-fredeerock)
- [Assignment 04](https://github.com/lsudigitalart/2210hw4)  [(Submissions)](https://github.com/lsudigitalart?q=2210hw4)   [(Example)](https://github.com/lsudigitalart/2210hw4-fredeerock)
- [Assignment 05](https://github.com/lsudigitalart/2210hw5)  [(Submissions)](https://github.com/lsudigitalart?q=2210hw5)   [(Example)](https://github.com/lsudigitalart/2210hw5-fredeerock)
- [Assignment 06](https://github.com/lsudigitalart/2210hw6)  [(Submissions)](https://github.com/lsudigitalart?q=2210hw6)   [(Example)](https://github.com/lsudigitalart/2210hw6-fredeerock)
- [Assignment 07](https://github.com/lsudigitalart/2210hw7)  [(Submissions)](https://github.com/lsudigitalart?q=2210hw7)   [(Example)](https://github.com/lsudigitalart/2210hw7-fredeerock)
- [Assignment 08](https://github.com/lsudigitalart/2210hw8)  [(Submissions)](https://github.com/lsudigitalart?q=2210hw8)   [(Example)](https://github.com/lsudigitalart/2210hw8-fredeerock)
- [Assignment 09](https://github.com/lsudigitalart/2210hw9)  [(Submissions)](https://github.com/lsudigitalart?q=2210hw9)   [(Example)](https://github.com/lsudigitalart/2210hw9-fredeerock)
- [Assignment 10](https://github.com/lsudigitalart/2210hw10) [(Submissions)](https://github.com/lsudigitalart?q=2210hw10)  [(Example)](https://github.com/lsudigitalart/2210hw10-fredeerock)
- [Assignment 11](https://github.com/lsudigitalart/2210hw11) [(Submissions)](https://github.com/lsudigitalart?q=2210hw11)  [(Example)](https://github.com/lsudigitalart/2210hw11-fredeerock)
- [Assignment 12](https://github.com/lsudigitalart/2210hw12) [(Submissions)](https://github.com/lsudigitalart?q=2210hw12)  [(Example)](https://github.com/lsudigitalart/2210hw12-fredeerock)
- [Assignment 13](https://github.com/lsudigitalart/2210hw13) [(Submissions)](https://github.com/lsudigitalart?q=2210hw13)  [(Example)](https://github.com/lsudigitalart/2210hw13-fredeerock)

## Dependencies
- [Class Syllabus](https://docs.google.com/document/d/1yk3bP_PSSpOtV43bXvR_NRi34WBWfM9RBCf83GoEyjQ/edit?usp=sharing)
- [Getting Started with p5.js by Lauren McCarthy](https://www.amazon.com/Make-Interactive-Graphics-JavaScript-Processing/dp/1457186772)
- Visual Studio Code <https://code.visualstudio.com>
- Git: <https://git-scm.com>
- Github: <http://github.com>
- p5.js: <http://p5js.org> (use p5.min.js)

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

### Start a server

- **Mac**
  - open terminal
  - `cd` into your sketch directory
  - type `python -m SimpleHTTPServer`
  - visit your site at `http://localhost:8000`

- **Windows**
  - Download and Install Python 2 from python.org
  - `cd` into your sketch directory
  - Open command prompt or git bash and type `C:/Python27/python.exe -m SimpleHTTPServer`
  - visit your site at `http://localhost:8000`

## Resources

### Course Specific
- [Class Github Repos](http://github.com/lsudigitalart)
- [How to browse in-class commit history](https://drive.google.com/file/d/0B666kg0WyOiBeGhFNWpibXBhbEU/view?usp=sharing)

### Processing
- <http://processing.org>
- <http://p5js.org>
- <http://learningprocessing.com>
- <http://openprocessing.org>

### JavaScript
- [p5.js Wiki JavaScript Basics](https://github.com/processing/p5.js/wiki/JavaScript-basics)
- [W3 Schools JavaScript Reference](http://www.w3schools.com/js)
- [Mozilla JavaScript Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

### Git
- <http://rogerdudler.github.io/git-guide/>
- <https://www.atlassian.com/git/tutorials/what-is-version-control>

### HTML
- <http://www.w3schools.com/tags/>
- <https://developer.mozilla.org/en-US/docs/Web/HTML/Element>

### Terminal
- <https://github.com/processing/p5.js/wiki/Terminal-and-the-Command-Line>
- <http://computers.tutsplus.com/tutorials/navigating-the-terminal-a-gentle-introduction--mac-3855>

### Some Creative Coders
- [Casey Reas](https://duckduckgo.com/?q=!ducky+Casey Reas)
- [Olia Lialina](https://duckduckgo.com/?q=!ducky+Olia Lialina)
- [John Maeda](https://duckduckgo.com/?q=!ducky+John Maeda)
- [Camille Utterback ](https://duckduckgo.com/?q=!ducky+Camille Utterback )
- [Petra Cortright](https://duckduckgo.com/?q=!ducky+Petra Cortright)
- [Scott Snibbe](https://duckduckgo.com/?q=!ducky+Scott Snibbe)
- [Aaron Koblin](https://duckduckgo.com/?q=!ducky+Aaron Koblin)
- [Marius Watz](https://duckduckgo.com/?q=!ducky+Marius Watz)
- [Eva and Franco Mattes](https://duckduckgo.com/?q=!ducky+Eva and Franco Mattes)
- [Alexei Shulgin](https://duckduckgo.com/?q=!ducky+Alexei Shulgin)
- [Daniel Shiffman](https://duckduckgo.com/?q=!ducky+Daniel Shiffman)
- [Ben Fry](https://duckduckgo.com/?q=!ducky+Ben Fry)
- [Golan Levin](https://duckduckgo.com/?q=!ducky+Golan Levin)
- [Myron Krueger](https://duckduckgo.com/?q=!ducky+Myron Krueger)
- [Justin Manor](https://duckduckgo.com/?q=!ducky+Justin Manor)
- [Lauren McCarthy](https://duckduckgo.com/?q=!ducky+Lauren McCarthy)
- [Kyle McDonald](https://duckduckgo.com/?q=!ducky+Kyle McDonald)
- [Luke DuBois](https://duckduckgo.com/?q=!ducky+Luke DuBois)
- [Nicky Case](https://duckduckgo.com/?q=!ducky+Nicky Case)
- [Zach Lieberman](https://duckduckgo.com/?q=!ducky+Zach Lieberman)
- [Theo Watson](https://duckduckgo.com/?q=!ducky+Theo Watson)
- [Brian House](https://duckduckgo.com/?q=!ducky+Brian House)
- [Ben Rubin](https://duckduckgo.com/?q=!ducky+Ben Rubin)
- [Rafael Lozano Hemmer](https://duckduckgo.com/?q=!ducky+Rafael Lozano Hemmer)
- [Marcus Wendt](https://duckduckgo.com/?q=!ducky+Marcus Wendt)
- [Jer Thorp](https://duckduckgo.com/?q=!ducky+Jer Thorp)
- [Emily Gobeille](https://duckduckgo.com/?q=!ducky+Emily Gobeille)
- [Ryoji Ikeda](https://duckduckgo.com/?q=!ducky+Ryoji Ikeda)
- [Rafael Lozano-Hemmer](https://duckduckgo.com/?q=!ducky+Rafael Lozano-Hemmer)
- [David Rokeby](https://duckduckgo.com/?q=!ducky+David Rokeby)
- [Eduardo Kac](https://duckduckgo.com/?q=!ducky+Eduardo Kac)
- [Mark Nappier](https://duckduckgo.com/?q=!ducky+Mark Nappier)
- [Cory Arcangel](https://duckduckgo.com/?q=!ducky+Cory Arcangel)
- [Brody Condon](https://duckduckgo.com/?q=!ducky+Brody Condon)
- [Beatriz da Costa](https://duckduckgo.com/?q=!ducky+Beatriz da Costa)
- [Char Davies](https://duckduckgo.com/?q=!ducky+Char Davies)
- [Mary Flanagan](https://duckduckgo.com/?q=!ducky+Mary Flanagan)
- [Jonah Brucker-Cohen](https://duckduckgo.com/?q=!ducky+Jonah Brucker-Cohen)

### Inspiration
- http://eyeofestival.com/
- https://processing.org/exhibition
- Rhizome
- Creative Applications
- ...
