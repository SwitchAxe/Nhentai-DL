# Nhentai-DL
a Nhentai sauce number to pdf converter.

# Usage  
`NHDL hentai_id` where `hentai id` is the manga id, for instance, to download [242460](https://www.nhentai.net/g/242460)
you must write `NHDL 242460`. the program aborts if the argument is not a number or if no argument was provided, 
but makes no check on the existance of the related manga, so its behaviour in that case is undefined. 

# Dependencies
NHDL is really light, and only the fish shell, grep, wget, [img2pdf](https://github.com/myollie/img2pdf) and sed are needed. other utilities, like cd and mkdir, are 
standard \*nix commands, and hopefully don't need installation (if you're on \*nix or *nix-like systems, that is).

# Installation
you can either install the tool by putting it manually in one of the directories in your path, by linking it in said directories, or by using the handy (and very broken, but functional) installation script. just
run `./install` under fish.
if the installation script is run as sudo (super user), the directory in which the binary is going to be put will be /usr/bin/. if run as a normal user, the directory will be $HOME/.local/bin and the directories 
will be created if missing. 

# DISCLAIMER
this program ONLY and EXCLUSIVELY runs under fish (the friendly interactive shell, that you can find [here](https://fishshell.com/) or on github [here](https://github.com/fish-shell/fish-shell/)) 
