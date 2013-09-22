# Vim Github Markdown
Github-flavored markdown syntax highlighting for VIm.


## Installing
Copy the syntax folder into the shared library of (the current) VIm:
```sh
$ [sudo] cp -r -u -v syntax/ /usr/share/vim/vimcurrent/
```

You might want to use another name for the vim syntax (for example
`gitmarkdown` instead of just `markdown`, then do the following:

```sh
$ mv syntax/markdown.vim syntax/gitmarkdown.vim
# Open the syntax/gitmarkdown.vim file and change on the last line:
#
# let b:current_syntax = "markdown"
# to
# let b:current_syntax = "gitmarkdown"
$ [sudo] cp -r -u -v syntax/ /usr/share/vim/vimcurrent/
```

> On the `cp` command, I've used some flags, but you might want to ignore
> the `-u` and `-v` flag, since it will only display an output message when
> the copying went succesfull.
