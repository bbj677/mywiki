# cmd-tools


## bat

```bash
sudo apt install bat

```



## starship

```toml


[directory]
#ディレクトリ表示
truncation_length = 10
truncate_to_repo = false

[git_status]
#Gitのステータス表示用アイコン
conflicted = "💥"
ahead = "🏎💨"
behind = "😰"
diverged = "😵"
untracked = "🌚‍"
stashed = "📦"
modified = "📝"
staged = '🔦'
renamed = "🏷"
deleted = "🗑"

[[battery.display]]
#バッテリーを表示するタイミング、表示する際の文字のスタイル
threshold = 100
style = "bold blue"

[battery]
#バッテリーの各状態のアイコン、上からフル充電、充電中、バッテリー残量低下
full_symbol = "🤗"
charging_symbol = "😌"
discharging_symbol = "😨"

[time]
#時間の表示をオンにして12時間表示に
disabled = false
use_12hr = true

```

## tmux

* tmux
* oh-my-tmux

## ranger

* i: 切换全屏预览
* d: 删除
* r: 打开
* a: 重命名
* 空格：选择文件
    - dd：剪贴
    - pp: 粘贴
    - yy: 复制
* 搜索：/
* 显示隐藏的文件：<C-h>
* 



- [http://ranger.github.io/](http://ranger.github.io/)
- [https://blog.csdn.net/lxyoucan/article/details/115671189](https://blog.csdn.net/lxyoucan/article/details/115671189) 
- [https://github.com/alexanderjeurissen/ranger_devicons](https://github.com/alexanderjeurissen/ranger_devicons) 


## ag

* github: [https://github.com/ggreer/the_silver_searcher](https://github.com/ggreer/the_silver_searcher) 
* ubuntu install ag : `sudo apt-get install silversearcher-ag`
* Usage: `ag [FILE-TYPE] [OPTIONS] PATTERN [PATH]`
* e.g. : `ag -i aaa .`


## fzf

* github: [https://github.com/junegunn/fzf](https://github.com/junegunn/fzf)
* ubuntu install fzf: `sudo apt-get install fzf`




## fish

### fish

* github: [https://github.com/fish-shell/fish-shell](https://github.com/fish-shell/fish-shell)
* install: `sudo apt-get install fish`
* Default shell

    * Add the line /usr/local/bin/fish to /etc/shells.`echo /usr/local/bin/fish | sudo tee -a /etc/shells`
    * Change your default shell with `chsh -s /usr/local/bin/fish`.




### omf


* GitHut: [https://github.com/oh-my-fish/oh-my-fish](https://github.com/oh-my-fish/oh-my-fish)
* Install: Reference GitHut `curl https://raw.githubusercontent.com/oh-my-fish/oh-my-fish/master/bin/install | fish`
* Dotfiles: 
  * `$OMF_CONFIG`
  * init.fish
  
* Usage:
    * 查看可用的主题：`omf theme`
    * 安装主题：`omf install <theme>`
    * 应用主题：`omf theme <theme>`
    * 查看安装的packages: `omf list`
    * 安装包：`omf install [<name>|<url>]`


* 推荐:
    * plugins:
        * autojump
        * fzf
        * omf
        * fish-spec
        * fzf-autojump
        * z
    * themes:
        * clearance,正在使用
        * default
        * eclm
    


### fisher

* GitHut: [https://github.com/jorgebucaran/fisher](https://github.com/jorgebucaran/fisher)
* Install: `curl -sL https://git.io/fisher | source && fisher install jorgebucaran/fisher`

    * 本地: `cat fisher.fish | source && fisher install jorgebucaran/fisher`

* 使用: `fisher --help`

    * fisher install : `fisher install ilancosman/tide`
    * fisher list: 查看当前插件，简写：`fisher ls`
    * 移除插件：`fisher rm <name>`

* 推荐插件

    * jorgebucaran/fisher
    * ilancosman/tide
    * jorgebucaran/autopair.fish
    * gazorby/fish-abbreviation-tips

* Looking for plugins: [https://github.com/jorgebucaran/awsm.fish](https://github.com/jorgebucaran/awsm.fish) 
































































