# git-shortcuts
Shortcuts/Aliases for Git

Here's a list of the aliases I find useful with using Git in the terminal. To make add these to your terminal, do the following:

1. Copy and paste the contents of GitAliases.txt into your .bashrc or .zshrc file, which you can find at: ```~/.zshrc``` on Mac
2. Then, run ```source ~/.zshrc``` to have the aliases set in your terminal

* alias gs="git status"
* alias gap="git add -p"
* alias gcb="git checkout -b"
* alias gc="git checkout"
* alias gcm="git commit -m"
* alias gss="git status -s"
* alias dag="log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all"
