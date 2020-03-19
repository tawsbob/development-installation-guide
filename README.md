
# Welcome to Dev guide!

So in this repo I **joined** a mix of things that you must have installed on your machine ;)


## FOR  MAC

First of all Home brew ( package manager )

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```


## Xcode

Download xcode [here](https://apps.apple.com/br/app/xcode/id497799835?mt=12)

## Git

```bash
$ brew install git
```

- [generate ssh keys](https://help.github.com/en/enterprise/2.15/user/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agen)

- [add ssh key to github](https://help.github.com/pt/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account)

## iTerm

#### What is iTerm2?

iTerm2 is a replacement for Terminal and the successor to iTerm. It works on Macs with macOS 10.12 or newer. iTerm2 brings the terminal into the modern age with features you never knew you always wanted.

[Download here](http://iterm2.com)

## Oh My Zsh

[ohmyzsh](https://ohmyz.sh/)

```bash
$ sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## nvm ( for nodejs developers )
[NVM]([https://github.com/nvm-sh/nvma](https://github.com/nvm-sh/nvma)) is a nodejs version manager.

```bash
$ curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
```
Running either of the above commands downloads a script and runs it. The script clones the nvm repository to `~/.nvm`, and attempts to add the source lines from the snippet below to the correct profile file (`~/.bash_profile`, `~/.zshrc`, `~/.profile`, or `~/.bashrc`).

```bash
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
```

## Instaling node.js

```bash
$ nvm install YOUR_NODE_VERSION
```

## Using node.js

```bash
$ nvm use YOUR_NODE_VERSION 
```

## Docker

[download docker here](https://www.docker.com/products/docker-desktop)

## Visual Studio Code

[download vscode here](https://code.visualstudio.com/)
