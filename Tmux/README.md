# Tmux
## 配置文件说明
### Send prefix
把prefix默认的ctrl+b变为了ctrl+d。
很多其他人改成了ctrl+a，但是考虑到命令行中移动光标的快捷键冲突，改成了ctrl+d。

### Use Alt-arrow keys to switch panes
本设置使得无需按prefix，直接用alt+箭头就能在pane之间switch。
这个很方便。

### Shift arrow to switch windows
本设置使得无需按prefix，直接用shift+箭头就能在window之间switch。
这个也很方便。

### Mouse mode
开启鼠标模式。
用鼠标就能切换window，pane，还能调整pane的大小。
这个特别好用！

### Set easier window split keys
另一种切割窗口方式：prefix + v 代表竖着切，prefix + h 代表横着切。
切割更直观。

### Easy config reload
修改.tmux.conf配置文件后，不需要关掉tmux。直接用prefix+r，就可以重新加载设置。
