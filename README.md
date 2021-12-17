# archlinux-alias
Contains useful Arch Linux Aliases and shortcuts. 

Additionaly I added some useful bashrc commands, to improve the command line workflow.

Use the alias "help-alias" to get an overview of all useful alias commands

Required Packages:
* kali-undercover

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
Feel free to look into the file *alias-prefix* to get some recommendations into bashrc setup

Insert the Alias Prefix (before adding aliases) by using the following command:
```bash
./insert-alias-prefix
```
Required Packages:
* most
