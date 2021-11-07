# 20211005 Code Camp

To the reader,

This will be a bit of a crash course in absolutely everything - using Git, VS Code and some code snippets. For full context - if was to label myself - it would be python developer so that would probably be where you would get the most bang for your buck in terms of leveraging my time - but that's not to say I won't be able to assist with HTML, CSS or any other language. Once you've learnt one - you've pretty much learnt them all - just need to know what syntax to use etc.

If you're not already using Git - I would highly encourage you to. Not only is it a mainstay of Software Developers in the workforce but it's also a fantastic bit of kit to version control and track bugs/issues as well as revert if you fall down the rabbit hole so far - the best way back to the top is the nuclear option and starting again.

Additionally - if you don't have a preferred IDE (Integrated Development Environment) I would also highly encourage using VS Code (I'm writing this in VS Code right now!). One of the perks of owning Microsoft, and Github is that you can make your IDE (Visual Studio Code) Open directly in Github and vice versa. Pretty Nifty - but also a touch anti competitive. A download link for VS Code can be found [here](https://code.visualstudio.com/). Know that VS Code isn't python specific like PyCharm or Spyder but is language agnostic - meaning that it supports most languages under the sun. Additionally - it comes with support for 3rd party mods called "Extensions" which allow you to download other peoples handy dandy mods for VS code which make your coding life that little bit more easy.

## GIT - Version Control and Collaboration

We'll start you off slow - and try to get you linked into Git through the CMD.
On your Macbook go ahead and download [Git](https://git-scm.com/).

Git itself is the open source software made by the fella who made Linux - he didn't like working problems out with people so he made a software that would help with the journey. Initially he made it to distribute different kernels of Linux but since it's creation it's been used in other ways (the names GitLab and GitHub [what we're using] will probably come to mind.)

Once you've got those setup - at least initially - we'll setup your username and password and pass things back and forth between your laptop and Git through HTTPS. You are able to setup an ssh connection too but let's leave that for another day.

Once you've installed git - pop open the git terminal through either Git Bash or Git CMD. Try to avoid using the GUI's. Although they're easier - if you want to pursue Software Engineering further, being comfortable in a terminal environment will take you far. It'll look super similar to your regular terminal. You'll need to configure your Username and Email. These will be the Username and Email that will appear in your Push/Pull/Commit Requests in Git. To do this you'll need to use the following:

`git config --global user.name "John Smith"`

`git config --global user.email "john_smith@fake_domain.co.uk"`

Obviously - replace John Smith and the Email with your own (unless that is you want to be John Smith..) On running the above two commands - you shouldn't get any output - just a new line and returning to a new line.

Once done - run the following to confirm that your changes have taken on your machine.

`git config --global user.name`

` git config --global user.email`

What you should find now is that Git is now spitting out your Name and Email. If anything looks wrong - go back to the start with ` git config --global user.name "John Smith"` and you should be able to get it sorted.

## Visual Studio Code - VS Code - The GOAT

I won't lie to you. I only started using VS Code this year. I was previously using Spyder - a Python specific IDE which was _fine_ but that was it - it was just _fine_. With VS Code - there's Version Control Integration, Mutilple Language Support - and a dark theme (perfect for evenings spent coding). This part is completely optional as IDE's are like cars - everyone has their own preference (even if one is objectively better than the other) so if you don't want to use VS Code just yet feel free to skip to the exercise at the bottom. Once you've installed VS Code though - let's get you started with version controlling. You'll have some of the following icons on the left hand side of VS Code when you open it up.

![The VS Code Sidebar](/source/2021/assetts/vs_code_bar.png?raw=true)

The middle icon is the SCM or Source Control Management tab and is where we'll be focusing for today. When you first click into it - you'll be greeted with the following.

![SCM Menu](/source/2021/assetts/scm.png?raw=true)

Let's try to clone this repository of code and save it somewhere on your laptop. Let's click on Clone Repository and move on from there - click on Clone from Github.

![Clone](/source/2021/assetts/clone.png?raw=true)

You'll then get the following prompt (or something like it if you're on Mac).

![Prompt](/source/2021/assetts/prompt.png?raw=true)

Once you've gotten here - allow and you'll be redirected to a page asking you to sign in with your VS Code credentials. Follow the Prompts and Voila! You should be integrated with Git now in VS Code.

Now onto actually cloning the repository (commonly referred to as a repo). If all has gone well - you should find yourself redirected back to the VS Code window with a search bar appearing at the top now. This search bar is now effectively hooked into your Github Account and able to see all of the different repo's you have available to you (including all the public facing ones). If you type in practicalcs_101 - you should be able to find ours!

![Prompt](/source/2021/assetts/practicalcs_101.png?raw=true)

If you click on that - you should now be directed to a File Browser to select a location on your machine to save all of this. Once selected - you'll be prompted if you want to open up the folder as so and you're done!

![Prompt](/source/2021/assetts/confirm.png?raw=true)

Congratulations! You've just completed your first pull request! This can also be achieved through the command line interface as well (I know - I know - I said avoid GUIs but here I am showing you how to do it through the GUI - We can cover the CLI afterwards.)

## Exercises

Right - now that that's all out of the way - I thought let's start with Python as that's the stuff front of mind for you right now. In 15 minutes - I want you to write in either [hellowworld.py](/source/2021/Python/helloworld.py) or [hellowworld.ipynb](/source/2021/Python/helloworld.ipynb) _everything_ you know about Python - no matter how small or how large. I actually want you to focus on this more than the challenge question - as I can just provide the answer to that one and we can code it up together.

If you have any questions mate - feel free to hit me up!

T
