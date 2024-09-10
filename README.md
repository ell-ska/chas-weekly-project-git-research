# weekly project: git research

## 3 terminal commands shown during lectures
- `cd file-path`
  - navigate folders and files
- `ls`
  - list content of a folder
- `mkdir folder-name`
  - create a new folder

## 1 terminal command i found on my own
- `openssl rand --base64 12`
  - generates a randomized string with base64 that's 12 characters long
  - useful for generating secrets
  - [source](https://wiki.openssl.org/index.php/Command_Line_Utilities)

## 3 git commands shown during lectures
- `git add file-name`
  - stage changed files
- `git commit -m "message"`
  - commit all staged files and add a commit message
- `git pull`
  - fetch remote changes and merge/rebase changes to reconcile diverging branches

## 1 git command i found on my own
*or rather my favorite way of saving when you need to run but are not finished with your work*
- `git add .`
- `git commit -m "save"`
  - create a "temporary" commit (even tho nothing is really temporary in git)
- `git push`

![one eternity later](./spongebob.jpg)

- `git reset HEAD~1`
  - kinda reverts back to the state you had before the previous commands. you will see your changes as if you've just made them
- **finish your task!**
- `git add .`
- `git commit -m "message"`
- `git push -f`
  - force push and override the "save" commit

## 1 fun fact i've learnt about github
every active public github repository as of 02/02/2020 is stored on physical disks in the Arctic World Archive on Svalbard! [soruce](https://www.tiktok.com/t/ZGeKA5vDT/)

## 1 fun fact i've learnt about markdown
even though it's rarely used you can <ins>underline text</ins> with this syntax: `<ins>this will be underlined</ins>`