# tricks


## bashrc

```
source /usr/local/bin/virtualenvwrapper.sh
export WORKON_HOME=$HOME/.virtualenvs

export PS1='\[\033[01;32m\]\u@\h\[\033[01;34m\] \w \$\[\033[00m\] '

alias ll='/bin/ls -l'
#alias ls='/bin/ls --color=auto'
alias grep='grep --color=auto'
alias glg='git log --pretty=format:'\''%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bo\
ld blue)<%an>%Creset'\'' --abbrev-commit'

# Max OS X specific
alias cyclewifi='networksetup -setairportpower en0 off && networksetup -setairportpower en0 on'
```
