# zsh-tfenv
> zsh plugin for installing, updating, and loading `tfenv`
> Inspired by [zsh-pyenv](https://github.com/mattberther/zsh-pyenv)

## Usage
Once the plugin is installed, tfenv will be available.

## Installation

### Using [Antigen](https://github.com/zsh-users/antigen)
Bundle `zsh-tfenv` in your `.zshrc`

```
antigen bundle cda0/zsh-tfenv
```

### Using [zplug](https://github.com/b4b4r07/zplug)
Load `zsh-tfenv` as a plugin in your `.zshrc`

```
zplug "cda0/zsh-tfenv"
```

### Using [zgen](https://github.com/tarjoilija/zgen)
Include the load command in your `.zshrc`

```
zget load cda0/zsh-tfenv
```

### As an [Oh My ZSH!](https://github.com/robbyrussell/oh-my-zsh) custom plugin
Clone `zsh-tfenv` into your custom plugins repo and load as a plugin in your `.zshrc`

```shell
git clone https://github.com/cda0/zsh-tfenv ~/.oh-my-zsh/custom/plugins/zsh-tfenv
```

```
plugins+=(zsh-tfenv)
```

Keep in mind that plugins need to be added before `oh-my-zsh.sh` is sourced.

### Manually
Clone this repository somewhere (`~/.zsh-tfenv` for example) and source it in your `.zshrc`

```shell
git clone https://github.com/cda0/zsh-tfenv ~/.zsh-tfenv
```

```
source ~/.zsh-tfenv/zsh-tfenv.plugin.zsh
```

### License

MIT
