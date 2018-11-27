# SublimeText3User
本仓库存放自用的 Sublime Text 3 的 User 文件夹，以便在多设备之间同步配置。

## 文件夹路径
- `Windows`：`C:\Users\用户名\AppData\Roaming\Sublime Text 3\Packages\User`
- `Linux`：`~/.config/sublime-text-3/Packages/User`

## 安装步骤
- 新安装 `Sublime Text 3` 并输入 `License`
- 安装 `Package Control`：https://packagecontrol.io/installation
- 关闭 `Sublime Text 3`，然后复制本仓库到上述**文件夹路径**
- 启动 `Sublime Text 3`，等待 `Package Control` 安装所有插件（*并没有任何提示，需要耐心等待*）

## 快捷键一览
由于习惯了 `Jetbrains` 系的 `IDE`，我把 `Sublime Text 3` 的很多快捷键做了改动。
这里放一份常用快捷键备忘。
- `ctrl + d`：复制行
- `shift + enter`：在下方新建一行
- `ctrl + alt + l`：自动 `PEP 8` 格式化
- `shift + 10`：运行 `.py` 文件
- `ctrl + shift + t`：在当前位置打开终端
- `ctrl + 数字`：切换工作区
- `ctrl + w`：关闭标签页

**`vim` 模式常用快捷键**
- `hjkl` 左下上右
- `w` 下一词首
- `e` 下一词尾
- `b` 上一词首
- `0` 行首
- `^` 行首（不含空格）
- `$` 行尾
- `gg` 文件头
- `G` 文件尾
- `i` 光标后插入
- `I` 行末插入
- `a` 光标前插入
- `A` 行首插入
- `o` 下方新开一行
- `O` 上方新开一行
- `v` 可视模式
- `V` 行可视模式
- `ctrl + b` 上一页
- `ctrl + f` 下一页

## 参考资料
- https://forum.sublimetext.com/t/what-s-the-best-way-to-backup-the-st3-configuration/25494/2
- https://github.com/math2001/st-user-package
- https://github.com/4sStylZ/SublimeText3Settings
