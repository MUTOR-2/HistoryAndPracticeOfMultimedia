# MUTOR Template

## Setting up a new MUTOR course

In order to set up a new MUTOR course, you will begin with
a copy, not a clone, of this repository. There are a number of ways to
do this--the following steps will take you through one of them.

### Create an empty repository on GitHub

Let's say we want to create a course called 
[Underwater Basket Weaving](https://en.wikipedia.org/wiki/Underwater_basket_weaving).
We would start by making a new, empty repository on GitHub:
[https://github.com/organizations/MUTOR-2/repositories/new](https://github.com/organizations/MUTOR-2/repositories/new).

You will see a screen like this: 

![](assets/images/gh_create_repo.png)

Make your repo Public, not Private, and be sure to NOT include a README, 
license or .gitignore--those will be provided
by this Template.

Click `Create repository`, and ignore GitHub's post-creation instructions:

![](assets/images/gh_post_creation.png)

The following instructions use the commandline to set up your repo. (It may
be possible to do this with the Desktop client, but probably easier to
use the terminal...)

### Create a copy of this MUTOR Template repository

Make a new empty directory for the class, and initialize it as an empty
git repo:

    $ mkdir UnderwaterBasketWeaving
    $ cd UnderwaterBasketWeaving
    $ git init .
    
Next, we `pull` a copy of this template into our new repository.
This is a different process than cloning the Template repo, as it
does not set the remote origin.

    $ git pull https://github.com/mutor-2/Template
    
Now pull the submodules:

    $ git submodule update --init --recursive
    
### Link your local repo to GitHub

Now we set the remote origin to point to the GitHub repo we created above,
and set the branch to `main`:

    $ git remote add origin https://github.com/mutor-2/UnderwaterBasketWeaving
    $ git branch -M main
    
Finally, push your repo up to GitHub, setting it up to track the remote 
in the process:

    $ git push -u origin main

## Edit _config.yml with the details of your course

`_config.yml` contains a number of site-wide variables that need to be 
set with the details of the new course. See that file for instructions.

## Set up GitHub Pages

Go to the GitHub page for your repository 
(e.g. https://github.com/mutor-2/UnderwaterBasketWeaving)
and choose Settings from the top menu. Scroll down to the GitHub Pages
section, and select the `main` branch from the dropdown menu and hit `Save`.
The site will now be published at, e.g., 
https://mutor-2.github.io/UnderwaterBasketWeaving.

## Add content

### Top level files

The top level files such as `index.md`, `about.md`, and `team.md` will need
to be filled with information regarding the new course.

Some files such as `references.md`, and `discussion_questions.md` are 
autopopulated from the material contained in the units.

The README.md file contains information that people will see when they
go to the GitHub repository (https://github.com/mutor-2/...), 
but will not be rendered as part of the website 
(https://mutor-2.github.io/...). It should contain information that
the contributors and maintainers of this particular course may need
in order to build content and adjust the website to suit the needs
of the course.

### Adding units

A unit consists of a folder named with a two digit number 
(01, 02, 11, 12, etc.) that contains an `index.md` file, and any supporting 
media (images, audio files, videos, etc.). 

The dropdown menu for the site
will automatically add units as they are added to the `_units` folder, and
similarly, autopopulated top-level files like `references.md` will
pull from newly added units.
