# cmd-alias
记录自己在开发中使用的别名，让自己变懒

## 使用在 `laravel` 中的别名
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

## 使用在 `vagrant` 中的别名
```shell
alias vu='cd ~/Homestead && sudo vagrant up'
alias vs='sudo vagrant suspend'
alias vssh='sudo vagrant ssh'
alias vsp='sudo vagrant provision'
alias vsup='sudo vagrant up -provision'
alias eh='sudo vim /etc/hosts'
alias ehh='sudo vim ~/.homestead/Homestead.yaml'
```

## 使用在 `git` 中的别名
```shell
alias gl='git log'
alias gc='git config'
alias gs='git status'
alias gpl='git pull'
alias gps='git push'
alias gct='git checkout'
```
