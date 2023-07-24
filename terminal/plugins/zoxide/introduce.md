# Zoxide

https://github.com/ajeetdsouza/zoxide#getting-started

zoxide is a smarter cd command, it will remember our cd patch by its command (z or zoxide)

e.g.

`shell
z ~/M/dotfiles/

# next time, you can cd ~/M/dotfiles by then following eg

z dotfiles
`

## install

`brew install zoxide`

and

add this to the end of your shell config fil (~/.zshrc)

`eval "$(zoxide init zsh)"`

and

you can set other alias by --cmd

`eval "$(zoxide init --cmd j zsh)"` j instance of z

## dependencies

-   fzf
    
    如果有一些 path 拥有类似的名字, 需要使用 fzf 选择
