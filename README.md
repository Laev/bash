<h4 align="center">Powerful Git Bash</h4>
<p align="center">
    <img alt="Git Bash" src="https://user-images.githubusercontent.com/38936252/48936837-180cab00-ef47-11e8-8925-71eea5980e74.png" width="750">
</p>

> 以下所有命令都需在 `Git Bash` 中执行。

## 一键配置

```bash
$ curl https://github.com/Laev/bash/blob/master/install.sh | sh
```

执行以上命令即可安装我的所有配置，其中有:

- 一套配色完善的 `Git Bash` 主题 (仿 oh-my-zsh 默认主题)
- 我常用的 alias
- tree 和 wget 命令
- 终端复用神器 `tmux` (包含插件)、
- `DejaVu Sans Mono Bold` 字体 (可正常显示 unicode 字符)、
- `vim` 主题 `molokai` (已默认开启鼠标操作)
- utf8 字符集设置 (大多数情况下可正常显示中文)

请先用管理员身份打开 `Git Bash`，然后再运行命令，期间会开两个窗口，需要手动复制下文件，这个过程是在安装字体，命令无法操作。

我录了一张动态图，由于图片过大无法展示，所以需要手动点击观看（32MB）: [Bash.gif](https://xnngs.oss-cn-shanghai.aliyuncs.com/img/bash.gif)

## 按需配置

- [在 Windows 一键上打造体验良好的 Linux 终端](https://xnngs.cn/new/terminal.html)

## 更新日志

- 2018-12-24 
  
  - 新增 tmux 插件使 session 能持久化到本地
  - 终端背景色由绿色修改为灰色
  - 将红色颜色配置由橙色改回红色

## License

[MIT](./LICENSE)
