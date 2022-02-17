# archlinux-alias
Contains useful Arch Linux Aliases and shortcuts.

## Recommended Installation:
Before Quick-Installing, make sure that all required packages are installed.
Check out the required Packages at **Details**

**For Bash**
```bash
git clone https://github.com/normannator/archlinux-alias.git && cd archlinux-alias/ && ./insert-alias-prefix && ./link-alias-to-bashrc
```

**For ZSH**
Before executing this command, toggle the uncommended lines in *insert-alias-prefix* to insert the prefixes to zsh and not to bash.
```bash
git clone https://github.com/normannator/archlinux-alias.git && cd archlinux-alias/ && ./insert-alias-prefix && ./link-alias-to-zshrc
```

## Details
Additionaly I added some useful bashrc commands, to improve the command line workflow.

Use the alias "help-alias" to get an overview of all useful alias commands

Required Packages
* neofetch

Optional Packages:
* kali-undercover
* pgadmin4
* hw
* youtube-dl
* rg - RipGrep
* yay
* wget
* cyberghostvpn
* ghci

**Configure for Bash**
```bash
git clone https://github.com/normannator/archlinux-alias.git && cd archlinux-alias/ && ./link-alias-to-bashrc
```

**Configure for Zsh**
```bash
git clone https://github.com/normannator/archlinux-alias.git && cd archlinux-alias/ && ./link-alias-to-zshrc
```

**Configure for Bash AND Zsh**
You can use both Bash and Zsh.
```bash
git clone https://github.com/normannator/archlinux-alias.git && cd archlinux-alias/ && ./link-alias-to-bashrc && ./link-alias-to-zshrc
```

**Note**
Feel free to look into the file *alias-prefix* to get some recommendations into bashrc setup. Use the *alias-prefix* script before adding the *nator-alias* script! This will improve the performance of bash (scripts).

Insert the Alias Prefix (before adding aliases) by using the following command:
```bash
./insert-alias-prefix
```
Required Packages:
* most
* archive:
  * tar
  * bunzip2
  * unrar
  * gunzip
  * unzip
  * uncompress
  * 7z
  * ar
* nano
* (shopt)
