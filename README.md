### Setup
~/.zshrc: 

```zsh
if [ -f ~/.config/zsh/zshrc_init ]; then
  source ~/.config/zsh/zshrc_init
fi
```

oh-my-zsh plugins:

```zsh
plugins=(git zsh-syntax-highlighting zsh-completions docker docker-compose kubectl)
```
