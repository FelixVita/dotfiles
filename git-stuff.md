# Git Config

Things related to global or local `.gitconfig` files.

## git lol

Custom git command that lists git log in a nice format. Courtesy of Omer from the 'Brief' YouTube channel ([link]([url](https://gist.github.com/Omerr/8134a61b56ca82dd90e546e7ef04eb77)))

`log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit`

To configure as an alias git lol:

`git config --global alias.lol "log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"`

