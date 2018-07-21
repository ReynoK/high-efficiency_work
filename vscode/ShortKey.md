##### 命令窗口

| Key | Function|
| :-: | :-:|
| Command + Shift + P | 显示**命令面板**|
| Command + N| 新建窗口| 
| Command + W | 关闭当前窗口|
| Command + B| 隐藏侧边栏 |



##### 编辑

| Key | Function|
| :-: | :-:|
| Command + Shift + K | 删除行|
| C + S + ENTER | 在**上面**插入行|
| Command + Shift + \ | 跳转到**匹配的括号**|
| C +  ← | 跳转到行开头|
| C +  → | 跳转到行结尾|
| C +  ↑ | 跳转到首行 |
| C +  ↓| 跳转到末尾 |
| A + ↑ | 向上移动行|
| A + c | 向下移动行|
| C + / | 切换行注释|
| Shift + Alt + A | 切换 块注释|
| Command + Option + ↑ | 向上插入光标 (编辑多行使用)|
| Command + Option + ↓ | 向下插入光标（编辑多行使用）| 
| Command + Shift + Enter | 向上插入一行|
| Command + Enter |  向下插入一行 |
| Option + ↑ | 将当前行往上移动 |
| Option + ↓ | 将当前行往下移动 |
| Option + ← | 移动到前一个单词开头|
| Option + → | 移动到后一个单词开头| 
| Shfit + Option + ↑ | 将当前行往上复制|
| Shift + Option + ↓ | 将当前行往下复制|


##### 导航

| Key | Function|
| :-: | :-:|
| Ctrl + G | 跳转到指定行|
| Ctrl + P | 跳转到指定文件|

##### 搜索和替换

| Key | Function|
| :-: | :-:|
| Command + F | 在当前文件中搜索 |
| Command + Shift + F | 在文件中搜索 |
| Command + Option + F | 在当前文件中搜索和替换|
| Command + Shift + H | 在文件中:搜索与替换|
| Command + G | 查找下一个|
| Command + Shift + G | 查找上一个|
| Option+ Enter | 选中所有匹配项| 

##### 选择

| Key | Function|
| :-: | :-:|
| Shift + ↑ | 向上选择多行|
| Shift + ↓ | 向下选择多行|
| Command + Shift + ↑| 选择从光标处到文件头，可用shift减少选择的行|
| Command + Shift + ↓ | 选择从光标处到文件尾，可用shift减少选择的行|
| Command + Shift + L | 选中所有与当前选中内容相同的部分|


##### 语言编辑

| Key | Function|
| :-: | :-:|
| Shift + Option + F | 格式化文档|
| Command + K, Command + F | 格式化选择的代码|
| Command + K, M | 更改文件语言|



##### 编辑器管理

| Key | Function|
| :-: | :-:|
| Ctrl + \ | 拆分编辑器|
| Ctrl + 1/2/3..| 聚焦到第n个编辑器|
| Command + Option + ← | 聚焦到前一个编辑器|
| Command + Option + → | 聚焦到右一个编辑器 
| Command + Shift + N | 新视窗|
| Command + Shift + V | 打开markdown预览 |
| Command + Ctrl + F | 全屏/窗口切换 |

##### 文件管理

| Key | Function|
| :-: | :-:|
| Command + K, O | 在新窗口打开文件 |
| Command + K, R | 在资源管理器中查看该文件|
| Command + K, P | 复制当前文件路径|
| Command + Shfit + S |另存为|
| Command + Option + S | 全部保存|
| Command + K, Command W |全部关闭|
| Command + Shift + T| 重新打开被关闭的编辑器 |



#### vim模式

##### 光标移动
>normal 模式

| Key | Function|
| :-: | :-:|
| h | 向左移动 |
| j | 向下移动|
| k | 向上移动 |
| l | 向右移动|
| - | 移动到上一行第一个非空字符|
| +/Enter| 移动到下一行的第一个非空字符|
| gg | 跳到文件开头|
| G | 跳到文件末尾|
| b | 跳转到前一个单词的开头 |
| e | 跳转到下一个单词的结尾 |
| w |跳转到下一个单词的开头 |
| ^ | 跳至开头|
| $ | 跳至行尾|
| n + gg / n + G | 跳转至n行|
| gd | 跳转至光标所在变量声明处|
| f + alpha| 在当前行中寻找alpha字符，并跳转|
| ; | 重复上一条命令 f+alpha|
| * | 查找光标所在处单词，向下查找|
| # | 查找光标所在处单词，向上查找|
| Ctrl + e | 移动页面|
| Ctrl + f | 上翻一页（向下看）|
| Ctrl + b | 下翻一页（向上看）|
| Ctrl + u | 上翻半页|
| Ctrl + d | 下翻半页|

##### 选中
>normal模式

| Key | Function|
| :-: | :-:|
| v + i + w | 放在一个单词任一位置均可选中本单词|
| v + e | 光标放在一个单词的开头可选中本单词|
| v + h/j/k/l | 进入视图模式后按方向键选中区域|

##### 复制/粘贴/剪切
>normal模式

| Key | Function|
| :-: | :-:|
| y | 复制（要先选中）|
| yy|复制当前行|
| n + yy | 复制n行|
| p | 粘贴当前行下面 |
| P | 粘贴当前行上面|
| D | 向后**剪切**行 |
| dd | 剪切所在行 |
| dw | 剪切当前字符所在单词|
| x | 向后单个字符剪切（含光标字符）|
| X | 向前单个字符剪切（不含光标字符） |

##### 编辑模式
>normal

| Key | Function|
| :-: | :-:|
| J | 将下一行和当前行链接在一起|
| cc |删除当前行并进入编辑模式|
| cw | 删除当前单词进入编辑模式|
| c$ | 删除当前至行末尾，进入编辑模式 |
| s | 删除当前字符并进入编辑模式|
| S| 删除当前行并进入编辑模式 |
| xp |  交换当前字符与下一个字符|
| u | 撤销|
| Ctrl + r|重做|
| ~ |当前字符切换大小写|
| >> | 当前行右移一个单位|
| << | 当前行左移一个单位|
| == | 自动缩进当前行|

#### 查找替换 
>normal

| Key | Function|
| :-: | :-:|
| /pattern|向后搜索字符串|
| ?pattern| 向前搜索字符串|
| n | 下一个匹配|
| N| 前一个匹配|
| :%s/old/new/g | 搜索整个文件，将所有的old替换为new |
| :%s/old/new/g | 搜索整个文件，将所有的old替换为new，需要确认 | 

##### 退出编辑器
>normal

| Key | Function|
| :-: | :-:|
| w | 保存修改|
| wq | 保存修改并退出|
| x | 保存修改并退出|
| q | 退出|
| q! | 强制退出|

##### 多文件编辑

| Key | Function|
| :-: | :-:|
| :split/:sp |将当前文件水平分割|
| :split file/:sp file | 水平分割当前窗口，并打开file|
| :vsplit/:vsp| 垂直分割当前窗口|
| :vsplit file/:vsp file | 垂直分割当前窗口，并打开file |
| :new file|同 :sp file|
| :only| 只显示当前窗口， 其他关闭|
| ~~:qall~~| 对所有窗口执行q操作|
| ~~:qall!~~| 对所有窗口执行q!操作||
| ~~:wall~~|对所有窗口执行w操作|
| ~~:wqall~~|对所有窗口执行wa操作|
