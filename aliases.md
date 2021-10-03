## PATHS EXPORTED
export PATH="/usr/local/opt/postgresql@12/bin:$PATH"

# aliases for faster access

alias wo='cd $HOME/work/iohkwork/'

alias q='cd ..'
alias l='ls'


# stack related aliases

alias sg='stack ghci'
alias sb='stack build'
alias st='stack test'
alias sc='stack test --coverage'
alias se='stack exec'
alias ssc='stack clean'
alias sr='stack run'

# git related aliases

alias gs='git status'
alias gfp='git push -u -f origin'
alias gr2='git rebase -i HEAD~2'
alias gr='git rebase -i HEAD'
alias gc='git commit -a -s -m'
alias gb='git branch'
alias gcb='git checkout'

# postgres related aliases

alias sp='brew services start postgresql'
alias ep='brew services stop postgresql'

# npm related aliases

alias ns='npm start'
alias ni='npm install --save'


# redis related aliases

alias rds='brew services start redis'
alias rde='brew services stop redis'

# miscellaneous alias

alias we='vi $HOME/.bash_profile'
alias so='source $HOME/.bash_profile'

test -e "${HOME}/.iterm2_shell_integration.bash" && source "${HOME}/.iterm2_shell_integration.bash"

# aws related aliases

alias aap='sudo ssh -i pathToSSHKey user@publicIPofAppMachine'
alias aadb='sudo ssh -i pathToSSHKey user@publicIPofDBMachine'

# nginx related

# start nginx server
alias rn='nginx -t && nginx'

# stop nginx server
alias sn='nginx -s stop'

# web development related
alias sl='cd /Users/Deepak/gyan-lahari/scripts && make setLocal'
alias snl='cd /Users/Deepak/gyan-lahari/scripts && make unsetLocal'
alias mm='cd /Users/Deepak/gyan-lahari/scripts && make '

# make related aliases for gyan lahari deployment
alias mmv='less /Users/Deepak/gyan-lahari/scripts/makefile'

# vagrant related
alias onv='cd /Users/Deepak/experiments/ && vagrant up && vagrant ssh'



