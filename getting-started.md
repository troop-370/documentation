---
layout: default
title: Getting Started
nav_order: 2
---
# Getting started

{: .no_toc }
## Table of contents
{: .no_toc .text-delta }
1. TOC
{:toc}

---

## GitHub
Troop 370 hosts most of its website files on GitHub, so you will need a GitHub account. If you do not have an account, you can [create one on the signup page](https://github.com/join).

---

## Required programs
To contribute to the Troop 370 website, you are going to need several programs:
* GitHub Desktop
* Atom (other text editors also work)
* Ruby
* Jekyll

### GitHub Desktop
GitHub Desktop is the program that enables you to work on the website files locally rather than in the browser. This allows your workflow to be quicker and easier by allowing you to edit multiple files and before publishing them to the web. Follow the following steps:

1. Download and install GitHub Desktop from [desktop.github.com](https://desktop.github.com/).
2. Once installed, open GitHub Desktop.
3. Choose *Sign in to GitHub.com*, enter your credentials. and click *Sign in*.
4. On the Configure Git page, make sure that your name is your first and last name and that your email is the same email you used for your GitHub account.
5. [Clone the troop website repository to your desktop by clicking here](x-github-client://openRepo/https://github.com/troop-370/troop370). If your browser asks if you are trying to open GitHub Desktop, accept the prompt.
6. GitHub Desktop will open a modal titled "Clone a repository". If desired, you can change the local path of the files that are about to be cloned to your computer.
7. Click *Clone* to download the entire repository to your computer.

### Atom
Atom is a text editor with direct integration with GitHub. It is the easiest way for you to modify website files and manage your changes before publishing them to GitHub.

1. Download and install Atom from [atom.io](https://atom.io/).
2. Once installed, open Atom.
3. Got to *File* > *Add Project Folder* and select the folder of the troop website repository (usually named *troop370*) from where you saved it when setting up GitHub Desktop. You should now see the project pane on the left side with all of the site files.

### Ruby

1. Download Ruby for windows from [rubyinstaller.org](https://rubyinstaller.org/downloads/). Choose version Ruby+Devkit 2.5.5 (x64).
2. Open the installer and keep pressing next to install Ruby. Do not change any of the default checked boxes.
3. When the install is complete, check the checkbox to run 'ridk install' and click Finish.
4. When command prompt opens that is labelled "Ruby Installer 2 for Windows" and the prompt "Which components shall be installed? If unsure press ENTER [1,2,3]" appears, press *ENTER*.

### Jekyll
Jekyll is the program that builds the website. You will use Jekyll when you are working on the website to test your changes locally before publishing to the live website.

1. Open PowerShell from the root of the troop370 repository by opening GitHub Desktop, selecting the troop370 repository from the *Current repository dropdown*, and go to *Repository* > *Open in PowerShell*.
2. Type `gem install jekyll bundler` to install Jekyll (the website builder) and Bundler (installs the gems/plugins needed for the website).
3. Check if Jekyll installed properly with `jekyll -v`.
4. Run `bundler install` to install the exact versions of the gems used for building the website.
5. Type `jekyll serve` to build the website. If it works, you should be able to access it in your browser at [localhost:4000](http://localhost:4000).
