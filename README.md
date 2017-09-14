# 命令行别名
记录自己在开发中使用的别名，让自己变懒，更换全局的需要在 `/etc` 文件下面，如果是当前用户的需要在 `～` 下
## 使用 `bash` 的用户，需要修改 `~/.bash_aliases`
```shell
sudo vim ~/.bash_aliases
```
## 使用 `zsh` 的用户，需要在 `~/.zshrc` 文件中新增 `~/.zsh_aliases` 文件
```shell
if [ -f ~/.zsh_aliases ]; then
     . ~/.zsh_aliases
fi
```
```shell
sudo vim ~/.zsh_aliases
```

## Laravel
```shell
alias pa='php artisan'
alias par:l='php artisan route:list'
alias pam='php artisan migrate'
alias pam:r='php artisan migrate:refresh'
alias pam:rs='php artisan migrate:refresh --seed'
alias cu='composer update'
alias ci='composer install'
alias cda='composer dump-autoload -o'
```

## Vagrant
```shell
alias vu='cd ~/Homestead && sudo vagrant up'
alias vs='sudo vagrant suspend'
alias vssh='sudo vagrant ssh'
alias vsp='sudo vagrant provision'
alias vsup='sudo vagrant up -provision'
alias eh='sudo vim /etc/hosts'
alias ehh='sudo vim ~/.homestead/Homestead.yaml'
```

## Git
```shell
alias gl='git log'
alias gc='git config'
alias gs='git status'
alias gpl='git pull'
alias gps='git push'
alias gct='git checkout'
```

## Ruby
```shell
alias bs='./bin/rails'
```
