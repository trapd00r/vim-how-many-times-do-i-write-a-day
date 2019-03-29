# how many times do I :w a day?

This is for science. Add this to your vim conf:

    au BufWritePost * silent  !shortdate  >> ~/vim_writes

and move the files in ./bin to somewhere in your $PATH.


    I have smashed :w 38 times today.

# see also

[time-spent-in-vim](https://github.com/trapd00r/time-spent-in-vim)
