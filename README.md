# Setup files for my mac

This repository contains the everything that I need to set up my mac.

Many of the set up instructions are derived / enhanced from http://sourabhbajaj.com/mac-setup/

## iTerm
1. Download iTerm2
2. Replace `~/.bash_profile` file with the one in this repository
3. Install [sexy-bash-prompt](`https://github.com/twolfson/sexy-bash-prompt`). See website for latest installation instructions
    ```bash
    (cd /tmp && git clone --depth 1 --config core.autocrlf=false https://github.com/twolfson/sexy-bash-prompt && cd sexy-bash-prompt && make install) && source ~/.bashrc
    ```

    Sexy-bash-prompt will automatically add the most up to date `.bash_prompt`
    file to your home directory, and append the line
    ```bash
    . ~/.bash_prompt
    ```
    to your
    `.bashrc`

4. Configure iTerm2 to sync preferences in dotfiles
(thanks to [Trevor Brown's blog post](`http://stratus3d.com/blog/2015/02/28/sync-iterm2-profile-with-dotfiles-repository/`))
    - Open iTerm2
    - Select iTerm2 > Preferences
    - Under the General tab, check the box "Load preferences from a custom folder or URL"
    - Press "Browse" and point to `~/dotfiles/iTerm2_profile`               





<!--  Keyboard keys useful for drafting keyboard shortcuts
See [this](`http://macbiblioblog.blogspot.ca/2005/05/special-key-symbols.html`)
<kbd>←</kbd>
<kbd>→</kbd>
<kbd>↑</kbd>
<kbd>↓</kbd>
<kbd>Command ⌘</kbd>
<kbd>Shift ⇧</kbd>
<kbd>Option ⌥</kbd>
<kbd>Control ⌃</kbd>
<kbd>Caps Lock ⇪</kbd>
<kbd>Delete ⌫</kbd>
<kbd>Fn</kbd>
<kbd> </kbd>
-->

My custom keyboard shortcuts for iTerm2 as as follows:  

<kbd>Command ⌘</kbd> <kbd>Shift ⇧</kbd> <kbd>i</kbd> Global open/close iTerm2  

<!--  Splitting panes -->
<kbd>Command ⌘</kbd> <kbd>Shift ⇧</kbd> <kbd>k</kbd> Split pane horizontally (aka get one up and one down)  
<kbd>Command ⌘</kbd> <kbd>Shift ⇧</kbd> <kbd>l</kbd> Split pane vertically (aka get one left one right)  

<!-- Select splitting panes -->
<kbd>Command ⌘</kbd> <kbd>←</kbd> Select split pane on left  
<kbd>Command ⌘</kbd> <kbd>→</kbd> Select split pane on left  
<kbd>Command ⌘</kbd> <kbd>↑</kbd> Select split pane above  
<kbd>Command ⌘</kbd> <kbd>↓</kbd> Select split pane below  

<!-- Swap split panes -->
<kbd>Command ⌘</kbd> <kbd>Option ⌥</kbd> <kbd>←</kbd> Swap with split pane on left  
<kbd>Command ⌘</kbd> <kbd>Option ⌥</kbd> <kbd>→</kbd> Swap with split pane on left  
<kbd>Command ⌘</kbd> <kbd>Option ⌥</kbd> <kbd>↑</kbd> Swap with split pane above  
<kbd>Command ⌘</kbd> <kbd>Option ⌥</kbd> <kbd>↓</kbd> Swap with split pane below  

<!-- Moving the cursor -->
<kbd>Shift ⇧</kbd> <kbd>←</kbd> Cursor left one word  (Send ESC SEQ + b)  
<kbd>Shift ⇧</kbd> <kbd>→</kbd> Cursor right one word  (Send ESC SEQ + f)  
<kbd>Command ⌘</kbd> <kbd>Shift ⇧</kbd> <kbd>→</kbd> Cursor to beginning of line  (Send ESC SEQ + OH)  
<kbd>Command ⌘</kbd> <kbd>Shift ⇧</kbd> <kbd>→</kbd> Cursor to end of line (Send ESC SEQ + OF)  

<!-- Deleting words or line-->
<kbd>Shift ⇧</kbd> <kbd>Delete ⌫</kbd> Delete one word  (Send Hex Code 0x17)  
<kbd>Command ⌘</kbd> <kbd>Shift ⇧</kbd> <kbd>Delete ⌫</kbd> Delete line  (Send Hex Code 0x15)  
