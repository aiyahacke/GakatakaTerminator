# 伽卡他卡终结者 V2.0 Bata


本软件为Bata版，功能尚不稳定，如果有任何问题欢迎联系作者反馈！

请不要使用此软件做任何违反课堂纪律的事，造成一切后果，与软件作者无关！

本软件采用易语言编写，依赖精易模块自行百度查找。

## 包含功能：

* 解除禁止键盘
* 解除广播全屏化
* 阻止黑屏肃静
* 禁止闪屏
* 阻止教师查看自己屏幕
* 禁止隐藏任务栏
* 阻止守护进程

## 使用方法：

1. 将伽卡他卡安装目录的 Exams.dll 重命名为 Exams_old.dll
2. 将源码编译成动态链接库 Exams.dll，并放入安装目录
3. 将 Exams.dll 设置为只读
4. 断网打开伽卡他卡，如果有终结者提示，则安装成功，关闭后联网重新打开即可正常使用

由于终结者已禁用创建守护进程，所以直接打开任务管理器结束 Student.exe 即可关闭伽卡他卡。
