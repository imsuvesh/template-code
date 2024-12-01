# Aliases

### Set alias
    open bash profile
    nano ~/.bash_profile
    
    load bash profile
    source ~/.bash_profile
    
    open zshrc profile
    nano ~/.zshrc
    
    load zshrc profile
    source ~/.zshrc

### package
    alias pn=pnpm
    alias pnd=pnpm dev
    alias nm=npm
    alias nms=npm start

### terminal 
    alias .. = 'cd ..'
    alias ... = 'cd ../../'
    alias c='clear'
    alias e='exit'

 ### some aliases
    alias ll='ls -alF'
    alias la='ls -A'
    alias eb="sudo nano ~/.bash_profile && source ~/.bash_profile"
    
### docker aliases
    alias d='docker'
    alias dc='docker-compose'
    alias dnax="docker rm $(docker ps -aq)"
### git aliases
    alias g='git'
    alias new="git checkout -b"
    alias last="git log -2"
    alias gg='git status'
    alias lg="git log --pretty=format:'%h was %an, %ar, message: %s' --graph"
    alias nah="git reset --hard && git clean -df"
    alias squash="git rebase -i HEAD~2"
