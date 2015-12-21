---
layout: page
title: "Compile"
category: teensybase
date: 2015-12-18 23:19:00
order: 2
permalink: /teensybase/compile
---

This page is about compiling Teensybase to run it locally offline on your own computer for editing pages and/or writing new pages before publishing to your GitHub Pages fork to submit a pull request against teensybase.github.io.

All pages are written using a dialect of Markdown. [Markdown Cheat sheet.](http://nestacms.com/docs/creating-content/markdown-cheat-sheet)

###Windows 7 Installation

####Check out GitHub repository

- Sign up to GitHub.
- Install [Chocolatey.](https://chocolatey.org/)
- Run this command in an Administrator command prompt

	```
	choco install github -y
	```

- On GitHub fork [Teensybase GitHub repository.](https://github.com/Teensybase/teensybase.github.io)
- Clone your fork into an appropriate location on your computer using the GitHub for Windows client that was installed using the choco command.

####Install Jekyll

- Install [Chocolatey](https://chocolatey.org/) (if not already installed).
- Run these commands in an Administrator command prompt. You will probably have to close and reopen the administrator command prompt after each command is complete.

	```
	choco install ruby -y
	```

	```
	gem install jekyll
	```

- In command prompt navigate to checked out GitHub repository.
- Run Jeykll

	```
	jekyll serve
	```
	
- Assuming no compilation errors, Teensybase should be available at [http://localhost:4000](http://localhost:4000)

### Mac OS X Installation

tbd

### Linux Installation (apt-get)

tbd
