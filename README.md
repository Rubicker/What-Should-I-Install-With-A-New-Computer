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

## Alfred3

| Plugins  | 别名 |
|:---------------:| :-----:|
| [caniuse](https://github.com/willfarrell/alfred-caniuse-workflow) | caniuse |
| [Colors](http://www.packal.org/workflow/colors) |  直接写颜色值 |
| [stackoverflow](https://github.com/zenorocha/alfred-workflows/raw/master/stack-overflow/stack-overflow.alfredworkflow) |   so |
| Dash |   在 Dash 中可以关联 |
| [alfred-fkill](https://github.com/SamVerschueren/alfred-fkill) | kill + 进程名 |

## Iterm2

| Plugins  | How |
|:---------------:| :-----:|
| [z](https://github.com/rupa/z/blob/master/z.sh) | 方便导航，用法见下 |
| [imgcat](https://github.com/eddieantonio/imgcat) |  在命令行中查看图片 |
| [stackoverflow](https://github.com/zenorocha/alfred-workflows/raw/master/stack-overflow/stack-overflow.alfredworkflow) |   so |
| Dash |   在 Dash 中可以关联 |

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

### Git

> [快捷键](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugin:git)

### 一些命令

- 清除当前行  `Ctrl` + `U`
- 清屏 `Ctrl` + `R`

## 需要安装的包

### [nvm](https://github.com/creationix/nvm)

> Mac only

## 管理 dotfiles

> [使用 dotfiles 和 stow 管理你的 dotfiles](https://github.com/jcouyang/dotfiles)
