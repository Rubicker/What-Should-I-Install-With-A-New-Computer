# What-Should-I-Install-With-A-New-Computer
Record the software or plugins that I need for work or fun


| App  | Other Version | Details |
| :------------: |:---------------:| :-----:|
| [Chrome](https://www.google.cn/chrome/index.html)  | [Chrome Canary version](https://www.google.com/chrome/browser/canary.html) | \ |
| [VSCode](https://code.visualstudio.com/)      | \        |   \ |
| [IINA](https://github.com/lhc70000/iina)       |    \ | \ |
| [Reeder3](http://reederapp.com/mac/) | \ | \ |
| [Keka](http://www.kekaosx.com/en/) | \ | \ |
| [Alfred3](https://www.alfredapp.com/) | \ | \ |
| [Dash](https://kapeli.com/dash) | \ | \ |
| [F.lux](https://justgetflux.com/) | \ | Free |
| [ColorSnapper 2](https://colorsnapper.com/) | \ | \ |
| [Fliqlo](https://fliqlo.com/#about-screensaver) | \ | Free |
| [iTerm2](https://www.iterm2.com/) | \ | Free |
| [tmux](https://github.com/tmux/tmux) | \ | Free |

## Chrome

| Plugins  | Details |
|:---------------:| :-----:|
| [Vimium](https://github.com/philc/vimium#release-notes) | \ |
| [为什么你们就是不能加个空格呢？](https://github.com/vinta/pangu.js?utm_source=next.36kr.com) |   \ |
| [GitHub Searchlite](https://chrome.google.com/webstore/detail/github-searchlite/lohekcihaibnhdhlbohicihejbfchikj) |    \ |
| [OctoLinker](https://octolinker.github.io/) |   \ |
|  [CodeCopy](https://github.com/zenorocha/codecopy)| \ |
| [BaiduExporter](https://github.com/acgotaku/BaiduExporter) | \ |
| [言葉 の Tab](https://github.com/keiww/the-tab-of-words)| \ |

## VSCode

常用快捷键 ：

| Keyboards  | Details |
|:---------------:| :-----|
| `⌘` + `P`  | 在当前工作区搜索文件并打开（连按跳转） |
| `⌘` + `B` | 切换侧边栏 |
| `⌘` + `K` + `Z` | 进入专注模式 |
| `Ctrl` + click | 打开某个路径文件（如若不存在则创建） |
| `Ctrl` + `Tab` | 打开文件浏览历史记录 |
| `Ctrl` + G | 跳转到指定行 |
| `Alt` + 上下箭头 | 移动该行位置 |
| `Ctrl` + K , `Ctrl` + F | 格式化指定范围代码 |
| `Ctrl` + K , `Ctrl` + X | Trim trailing whitespace |
| `⌘` + I | 选中当前行 |
| `⌘` + `Alt` + `[` / `]` | 折叠当前代码 |
| `⌘` + 上下箭头 | 跳转到当前代码第一行或最后一行 |

### `⌘` + `P`

- 输入 `@` 可以列出当前文件使用的 methods & variables。输入 `@:` 可以将其分类显示

- 输入 `:` + 数字可以跳转到某行（debug 很方便）

### `⌘` + `J`

唤醒 lower panel (类似于唤起终端，但是不会改变 tab)

### Terminal

- `⌘` + `]` split terminal
- `⌘` + `[` kill current active terminal 
- `⌘` + `M` maximiz terminal or any panels


## Tmux

[Tmux 使用](http://louiszhai.github.io/2017/09/30/tmux/#%E5%AF%BC%E8%AF%BB)

[The Tao of tmux](https://tmuxp.readthedocs.io/en/latest/about_tmux.html)

[gpakosz's tmux config](https://github.com/gpakosz/.tmux)

## Alfred3

| Plugins  | 别名 |
|:---------------:| :-----:|
| [caniuse](https://github.com/willfarrell/alfred-caniuse-workflow) | caniuse |
| [Colors](http://www.packal.org/workflow/colors) |  直接写颜色值 |
| [stackoverflow](https://github.com/zenorocha/alfred-workflows/raw/master/stack-overflow/stack-overflow.alfredworkflow) |   so |
| Dash |   在 Dash 中可以关联 |
| [alfred-fkill](https://github.com/SamVerschueren/alfred-fkill) | kill + 进程名 |

### 唤起 Alfred3 时强制使用英文键盘

Preferences > Advanced > Force Keyboard choose ABC 
## Iterm2

| Plugins  | How |
|:---------------:| :-----:|
| [z](https://github.com/rupa/z/blob/master/z.sh) | 方便导航，用法见下 |
| [imgcat](https://github.com/eddieantonio/imgcat) |  在命令行中查看图片 |
| [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) | 命令行提示（->） |

### z

> 快速跳转到常用文件夹
```bash
brew install z
echo . /usr/local/etc/profile.d/z.sh >> ~/.zshrc
source ~/.zshrc
```

### take

```bash
take my-dir
```

相当于：

```bash
mkdir my-dir & cd my-dir
```

### imgcat

```bash
brew tap eddieantonio/eddieantonio
brew install imgcat
```

### 如何关闭 session stored

Preferences > General > Startup to any option other than Use system window restoration setting

### Git

> [快捷键](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugin:git)

### 一些命令

- 清除当前行  `Ctrl` + `U`
- 清屏 `⌘` + `R`
- 移动光标到行首 `Ctrl` + `A`， 到行尾 `Ctrl` + `E`
- 打开当前 Finder 目录： 拖拽目录到命令行，按回车即可

## 需要安装的包

### [nvm](https://github.com/creationix/nvm)

> [A misleading 'You need to run "nvm install N/A"' message when trying to use a non-installed version](https://github.com/creationix/nvm/issues/1356)

> Mac only

## 管理 dotfiles

> [使用 dotfiles 和 stow 管理你的 dotfiles](https://github.com/jcouyang/dotfiles)

