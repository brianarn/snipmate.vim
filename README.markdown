# snipmate - personal fork

## Summary

This is my personal fork of snipmate with other things in it. Mostly for my
personal use, although others might find some level of value. I try to keep
some project-specific things out of here but I know it's not clean.

## Reference

For my own personal reference, when setting this repo up, I want to do the
following:

    git remote add upstream git://github.com/msanders/snipmate.vim.git

Then when I update:

	git fetch upstream
	git merge --no-commit upstream/master

This way, I can use the master branch (makes my dotfiles config easier)
without having to maintain my stuff on a secondary branch, so that I can
easily just do a submodule sync to pull in their respective master branches.
