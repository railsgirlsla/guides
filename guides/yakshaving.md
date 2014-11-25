# Yak Shaving

The first thing you have to do is to get your environment set up. Getting set up takes time. Don't get frustrated. It is something we all have to do and it is part of the process. 

Think about it as furnishing your home. Sure you can have a place to live but it isn't really nice to live in until you have a bed and some other essentials.

## Setting up your Environment

I think you should use this set up.  
[https://www.railstutorial.org/book/beginning#sec-up_and_running](https://www.railstutorial.org/book/beginning#sec-up_and_running)

This is from Michael Hartl's Rails Tutorial. This set up guide uses Cloud 9 which is a great way for you to start out. It includes all the elements you need in one place a text editor, a local development viewer, and a terminal window. This is an IDE (integrated development environment.)

## Things to know

Even though you are using an IDE (integrated development environment) you need to know how to use each element within it.

### The Text Editor 

This is where you type your text files. That will be self explanitory. It is like most others that you have probably used. A text editor is what you will use to write your code. A real text editor won't add any extra code to what you write. These are some other text editors.

+ Sublime
+ Komodo Edit
+ Gedit
+ vim
+ Notepad++
+ Emacs
+ Nano

### The Terminal

The Terminal or the Commandline is how you will give your computer instructions on what you want it to do. Anything that should be written in the terminal will often start with a $ (dollar sign) like this:

    $ man ls

When you see this type of command written this way the $ (dollar sign) is giving you a sign to type what follows into your terminal. P.Sp.- You do not type in the $ (dollar sign.)

Check out this slide deck and practice the commands in your terminal.  
[https://speakerdeck.com/jendiamond/the-terminal-know-your-command-line-an-introduction](https://speakerdeck.com/jendiamond/the-terminal-know-your-command-line-an-introduction)

If you are in a Windows environment use this tutorial. Basic Windows Terminal Commands.  
[http://www.youtube.com/watch?v=jbvqCqb-HJk&feature=youtu.be](http://www.youtube.com/watch?v=jbvqCqb-HJk&feature=youtu.be)

### The Local Server

### Version Contraol
 
#### Git

    $ git init

    $ git status

    $ git add .

    $ git status

    $ git commit -m "first commit"

#### Github or Bitbucket

Sign up for a free account with one of these services.

    $ git remote add origin https://github.com/railsgirlsla/guides.git

    $ git push -u origin master

### The Remote Server

#### Heroku

Heroku is a server where you can launch your Rails app on the web. 
Sign up for a free account. [https://signup.heroku.com/www-header](https://signup.heroku.com/www-header)

    $ git remote add

    $ git push heroku master

    $ heroku open
