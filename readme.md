install fish

     sudo pacman -S fish pkgfile ttf-dejavu powerline-fonts lnetutils neofetch


edit .bashrc and add exec fish at end.

    kate .bashrc
    kate is an text editor

restart shell and paste the files to the dir:

    home/user/.config/fish/
        with cd home/akash/.config/fish/

to alias

    alias -S <text> "dir"
    alias -S axa "cd /home/akash/git_workspace/"

for custom themes install omf (oh my fish)
    
    https://github.com/oh-my-fish/oh-my-fish#installation

fav theme
    
    omf theme lambda

install lsd a better replacement for ls

    https://github.com/Peltoche/lsd
    
    alias ls='lsd'
    alias lst='lsd --tree'