# cmd-tools





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
        * clearance
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

* Looking for plugins: [https://github.com/jorgebucaran/awsm.fish](https://github.com/jorgebucaran/awsm.fish) 































































