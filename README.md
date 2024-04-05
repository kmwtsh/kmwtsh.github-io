```
nano ~/.bashrc
``` 

然后输入
```
#忽略写入历史重复命令  
export HISTCONTROL=ignoredups
#上下健选择历史输入
 bind '"\e[A": history-search-backward'
 bind '"\e[B": history-search-forward'
```

再打开

```
nano ~/.inputrc 
```

然后输入

```
# Bash中自动补全时忽略大小写 
set completion-ignore-case on
# tab 键双击变单击
set show-all-if-ambiguous on
```
```
sudo apt install adb fastboot vlc
```
