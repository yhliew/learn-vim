# Learn VIM

## Seven habits of effective text editing 2.0
Presentation given by Bram Moolenaar at Google, 2007 February 13
https://www.moolenaar.net/habits_2007.pdf

* [habits_2007.pdf](habits_2007.pdf)


## Cheatsheet

* [vim-cheatsheet.png](vim-cheatsheet.png)

* [ultimate-vim-keyboard-shortcuts-4.pdf](ultimate-vim-keyboard-shortcuts-4.pdf)


## Other Picks

1. Master VIM regex. Vim regex has sight differences compare to regex for grep or perl.

1. Recording and playback
   
   ```
   record:   qq - do your things - q
   playback: @q  or `[num]`@q
   ```

2. Block select
  ```
  Ctrl-v -> arrow key 
  ```

3. Mark line number in register, use later
  ```
  ma
  mb
  'a  # go to a
  :'a,'bs/aaa/bbb/g    # execute substitube for a to b range
  ```



