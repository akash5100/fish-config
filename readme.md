install fish

     sudo pacman -S fish pkgfile ttf-dejavu powerline-fonts lnetutils neofetch figlet lolcat


edit .bashrc and add exec fish at end.

    kate .bashrc
    //kate is an text editor

restart shell and paste the files to the dir:
    
    //create a new file 'config.fish' at .config/fish/
    home/usr/.config/fish/
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
    alias lsa='lsd --all' //show hidden file

install ranger a better terminal browser
    
    sudo pacman -S ranger

install figlet font

    git clone https://github.com/xero/figlet-fonts
    sudo mv figlet-fonts/* /usr/share/figlet/fonts

