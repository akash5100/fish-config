install fish
~~~~~~~~~~~~~~~~~~ 
 sudo pacman -S fish pkgfile ttf-dejavu powerline-fonts lnetutils neofetch
~~~~~~~~~~~~~~~~~~
edit .bashrc and add exec fish at end.

    kate .bashrc
    kate is an text editor

restart shell and paste the files to the dir:
    home/user/.config/fish/
        with cd home/akash/.config/fish/

~~~~~~~~~~~~~~~~~~
to alias
    alias -S <text> "dir"
    alias -S axa "cd /home/akash/git_workspace/"