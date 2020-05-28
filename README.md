# zsh
Zsh alias

ZSH Aliases from:
https://news.ycombinator.com/item?id=23309310 


My personal favourite

alias -g NF='./*(oc[1])'

This points to the newest file/dir in my current dir, and it is very easy for me to untar a downloaded file and then cd into it without caring about the name of the file/dir.

tar xf NF; cd NF 
