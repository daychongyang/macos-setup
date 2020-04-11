# MacOS 初始化

## 浏览器

- [Google Chrome](https://www.google.cn/chrome/)

## 输入法

- [搜狗输入法](https://pinyin.sogou.com/mac/)

## 科学上网

- [V2rayU](https://github.com/yanue/V2rayU/releases)
- [ShadowsocksX](https://github.com/shadowsocks/ShadowsocksX-NG/releases)
- [ShadowsocksX-NG-R8](https://github.com/paradiseduo/ShadowsocksX-NG-R8/releases)

## App Store 常用软件

- QQ
- 微信
- 钉钉
- 网易云音乐
- Magnet(桌面窗口管理工具)
- iHosts
- IPViewer

## 工作环境

### [iTerm2(Mac 终端神器)](https://www.iterm2.com/downloads.html)

### [Homebrew](https://brew.sh/index_zh-cn)

```sh
# 阿里云镜像 https://mirrors.aliyun.com/homebrew
$ git clone https://mirrors.aliyun.com/homebrew/homebrew-core.git/ /usr/local/Homebrew/Library/Taps/homebrew/homebrew-core
$ sh ./brew-install.sh
```

### oh-my-zsh

```sh
$ sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

[Themes:ys](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes)

```sh
$ vim ~/.zshrc

# If you come from bash you might have to change your $PATH.
export PATH=$HOME/bin:/usr/local/bin:$PATH

# NVM Stuff
export NVM_DIR="$HOME/.nvm"
. "$(brew --prefix nvm)/nvm.sh"
```

### ssh

```sh
$ ssh-keygen
```

### git

```sh
$ brew install git
```

### Node.js

```sh
# node.js
$ brew install node

# yarn
$ brew install yarn

# nvm
$ brew install nvm

# nrm
$ yarn config set registry https://registry.npm.taobao.org/
$ yarn global add nrm
```

### [Visual Studio Code](https://code.visualstudio.com/)

- One Dark Pro(theme)
- Atom One Dark (theme)
- Material Icon Theme
- Chinese (Simplified) Language Pack for Visual Studio Code(VS Code 的中文（简体）语言包)
- Markdown All in One（Markdown Support for Visual Studio Code）
- Markdown Preview Github Styling
- Prettier - Code formatter
- Formatting Toggle
- ESLint
- GitLens — Git supercharged
- Git History
- Git Blame
- Git History Diff
- Git Merger
- npm Intellisense
- Import Cost
- Code Runner
- Auto Rename Tag
- Auto Close Tag
- Better Comments
- Color Highlight
- DotENV
- Concourse CI Pipeline Editor
- EditorConfig for VS Code
- gi
- Vetur

### [Source Tree](https://www.sourcetreeapp.com/)
