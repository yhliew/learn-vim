# Learn VIM

## Seven habits of effective text editing 2.0
Presentation given by Bram Moolenaar at Google, 2007 February 13

https://www.moolenaar.net/habits_2007.pdf

https://youtu.be/p6K4iIMlouI?feature=shared

* [habits_2007.pdf](habits_2007.pdf)


## Cheatsheet

Not by me. Found from googling. A lot cheatsheet available, pick the one you like most and print it.

* [vim-cheatsheet.png](vim-cheatsheet.png)

* [ultimate-vim-keyboard-shortcuts-4.pdf](ultimate-vim-keyboard-shortcuts-4.pdf)


## My Picks

1. New to VIM? Start with `vimtutor`. This is the best 30 minutes you might ever spend.

2. Master VIM regex. Vim regex has sight differences compare to regex for grep or perl.

3. Recording and playback
   ```
   record:   qq - do your things - q
   playback: @q  or `[num]`@q
   ```

4. Block select
   ```
   Ctrl-v  <arrow key> 
   ```

5. Mark line number in register, use later
   ```
   ma
   mb
   'a  # go to a
   :'a,'bs/aaa/bbb/g    # execute substitube for a to b range
   ```

6. Use bufdo to apply changes to multiple files. Use with caution. make backup first if needed.
   ```
   :autowrite
   :bufdo <cmd>
   ```

7. split screen is handy
   ```
   Ctrl-w s   # window split horizontally
   Ctrl-w v   # window split vertically
   ```
   


