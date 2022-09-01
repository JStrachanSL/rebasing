# rebasing

A small project to show people how to rebase properly

Commnads to use:

git rebase master

git rebase origin/master

git rebase -i HEAD~2 //squashing commits

git rebase -i master //for really cleaning up your branch

git commit --amend //allows you to update the last commit, real good for changing those commits messages

git reflog

git reset HEAD@{2} // for reflog undoing

Long file about rebase: https://docs.github.com/en/get-started/using-git/about-git-rebase

Reflog : https://www.atlassian.com/git/tutorials/rewriting-history/git-reflog

Handy tool for sorting mistakes: https://github.blog/2015-06-08-how-to-undo-almost-anything-with-git/

Cheatsheet for getting out of messes: http://justinhileman.info/article/git-pretty/git-pretty.png

Structure of git: https://ndpsoftware.com/git-cheatsheet.html

The blog post on how to combine some of these things into a guide for rewriting history: https://thoughtbot.com/blog/git-interactive-rebase-squash-amend-rewriting-history
