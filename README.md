# odin-recipes

Learn Summary

~ GIT ~

I've been know how to create SSH key, and connect to ssh key.
Using 'git clone git@github.com' (if SSH) if it's "Https" mean from http
How to use 'touch <file>' (to create a file from git)
How to use 'git add' to adding a stagging area file before commtting
How to use "git commit -m <'message'>" to commit a changes with message and "git commit" without a change

-- git commit -m "messages"-- (rule)
head "Add/Edit/Remove file"
body "Simple explanation the bug and fix"
body "simple explanation solving problem"

Using 'git push' or 'git push origin main' to push our local file into the github. (the file has to be in stage area) **This need to a include our password phprase

Using 'git pull' to pull from github file to our local file machine.

--Some Miscellaneous--
cd .. (back to folder 1 time)
cd 'folder name' if a folder have a blank space (space)


~ HTML ~

in tag <a href="" rel="noopener"> </a> **To prevent access the original page.
in tag <a href="" rel="noreferrer"></a> **For Privacy and Security, they don't know where we come from.

I've been using <a> tags to connecting "mainpage" into some recipes pages.

~ CSS ~
using width: {value}; and margin: 0 auto; to centered manually.
using display: block, inline-block, flex, inline-flex;
overlay brightness for image using "filter: brightness (1); background-color:white; overlay: {value}";
some safety font-family list like "Verdana, Arial, sans-serif";

using a <- symbol to go backpage or mainpage
#backPage::before {
    content: "\2190  "; /* simple left arrow */
}