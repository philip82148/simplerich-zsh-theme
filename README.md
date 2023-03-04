# ohmyzsh-theme-passion

An oh-my-zsh theme.

## Introduction

![passion](./image/passion.gif)

* real time prompt.
* command running time cost prompt.
* command running error hint.

## Usage

### Basic ZSH Theme

1. clone repo: ```git clone https://github.com/ChesterYue/ohmyzsh-theme-passion```;
2. copy theme: ```cp ./ohmyzsh-theme-passion/passion.zsh-theme ~/.oh-my-zsh/themes/passion.zsh-theme```;
3. modify rc: open ```~/.zshrc``` find ```ZSH_THEME``` edit to ```ZSH_THEME="passion"```;
4. execute rc: ```source ~./zshrc```;

REF: [Overriding and adding themes](https://github.com/ohmyzsh/ohmyzsh/wiki/Customization#overriding-and-adding-themes);

### Extra iTerm2 Preference

#### Color

<!-- cspell:disable-next-line -->
* iTerm2: settings -> Profiles -> Colors -> Color Presets -> import ```./passion.itermcolors``` ![color.png](./image/color.png)

* alternate terminal: try [Alternate terminal installation and configuration](https://iterm2colorschemes.com/);

#### Status Bar

* iTerm2: settings -> Appearance && settings -> Profiles -> Session -> Configure Status Bar ![status_0.png](./image/status_0.png) ![status_1.png](./image/status_1.png)

#### Font

* install [JetBrains Mono](https://www.jetbrains.com/lp/mono/);
* iTerm2: settings -> Appearance && settings -> Profiles -> Text -> Font ![font.png](./image/font.png)

#### Plugin

* [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions);
* [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting);

## Trouble Shooting

### macOS gdate

passion.zsh-theme depends on cmd ```gdate``` to get current time in milliseconds which is not installed by default in macOS.

to get ```gdate``` by running ```brew install coreutils;```
