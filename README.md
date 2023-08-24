# dotfiles

inspired by chezmoi.io

### install homebrew
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

### install chezmoi
`brew install chezmoi`

### pull dotfiles
`chezmoi init https://github.com/rogery7/dotfiles.git`

### diff then apply
`chezmoi diff`

`chezmoi apply`