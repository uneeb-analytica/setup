## 禁用SSH密码输入

每次跟远程的代码库交流的时候都问你要密码是件很烦的事。所以呀，你需要给`oh my zsh`加上一个`ssh-agent`插件：

首先，打开`.zshrc`文件：

```bash
code ~/.zshrc
```

然后：
- 找到`plugins=`开始的这一行
- 在插件（plugin）列表里加上`ssh-agent`

这个列表现在看起来应该是这样的：

```
plugins=(gitfast last-working-dir common-aliases zsh-syntax-highlighting history-substring-search pyenv ssh-agent)
```

:heavy_check_mark: 按下`Ctrl` + `S` 保存`.zshrc`文件，然后关掉你的代码编辑器。