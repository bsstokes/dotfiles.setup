# Dotfiles Setup

- [ ] Install [Homebrew](https://brew.sh/)
- [ ] `brew install yadm`
- [ ] Download SSH key
- [ ] Clone `dotfiles`

```sh
export GIT_SSH_COMMAND='ssh -i key'
yadm clone --no-bootstrap git@github.com:bsstokes/dotfiles.git
```

- [ ] Follow `~/.config/dotfiles/SETUP.md`
