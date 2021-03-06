title: Webstrom
categories:
 - Apps
author: 宋玉
date: 2020-03-30 15:02:10
---

## 操作定义
整理常用快捷键，按规则定义快捷键

- 使用频率
- 见名知意
- 操作方便




| 规则 | 描述 |
| --- | --- |
| command + * | 系统操作 |
| command + shift + *  | 系统操作增强 |
| option + *  | 普通操作 |
| option + shift + * | 普通操作增强 |
| option/command/control + 上/下/左/右 移动 | 跳转操作 |




---


## 常用操作

### 配置
Command-, 打开配置


### 增删改查
`command + C` 复制、快速复制一<br />`command + X` 剪切<br />`command + V` 粘贴<br />`command + shift + V` 从剪贴板里选择粘贴<br />`command + D` 对文件使用时是比较两个文本，对代码使用删除当前行<br />command + delete 隔单词删除<br />option + delete 隔单词删除<br />`command + F` 查找当前文档<br />**Control-H **全局查找<br />command + option + ⬇️ 复制上一行<br />control + k cut up to line end<br />`command + R` 替换当前文档<br />`command + G` 查找下一个<br />`command + shift + G` 查找上一个<br />优化导入<br />


### 提醒
`command + P` 显示参数信息<br />`command + shift + T` 增加环绕标签(if..else, try..catch, for, etc.)<br />`command + Y` 小浮窗显示变量声明时的行<br />`control + J` 获取变量相关信息（类型、注释等，注释是拿上一行的注释）<br />`command + F12` 文件结构弹出式菜单<br />`option+/` 代码补全<br />`F2, shift + F2` 切换到上\下一个突出错误的位置


### 跳转
`command+[, command+]` 光标现在的位置和之前的位置切换<br />`command + ←, command + →` 光标跳转到首尾    <br />`alt + ← →` 隔单词跳转<br />`command + O`  跳转到某个类<br />`command + alt + O` 跳转到某个符号<br />`command + L` 跳转行<br />`command + E` 弹出最近文件<br />**Control-Tab **编辑器内切换文件<br />command-shift-R 查找文件<br />option + command + 左/右Tab 直接切换<br />`command + shift + delete` 导航到上一个编辑的位置<br />`command + B` 跳转到变量声明处<br />`command + ↑` 跳转到导航栏


### 光标(caret)
![image.png](https://cdn.nlark.com/yuque/0/2019/png/394169/1574058359287-3a1361b7-5525-49f7-b716-a1239fe50923.png#align=left&display=inline&height=670&name=image.png&originHeight=670&originWidth=1529&size=167488&status=done&style=none&width=1529)<br />
<br />option  + shift + -> 选择单词<br />


### 选项页
`command + W` 关闭当前文件的选项页<br />`command + shift + [ ]` 文件选项卡快速切换


### 注释
`command + /` 注释/取消注释的行注释<br />`control+ shift + /` 注释/取消注释与块注释


### 调整缩进
`tab, shift + tab` 调整缩进<br />`control + shift + +/-` 把下面行的缩进收到上一行<br />`command + shift + F` 格式化代码


### 换行
`shift + enter` 快速向下换一行<br />`command + option + enter` 快速向上换一行<br />`command + enter` 换行光标还在原先位置


### 展开代码
`command + 加号, command + 减号` 收缩/展开光标对应的代码块<br />`command + shift + 加号, command + shift + 减号` 收缩/展开整个文档的代码块


### 文件操作
`shift + F6`   可以使文件、标签、变量名重命名<br />`command + shift + C` 复制文件的路径<br />`command + E`  打开最近打开的文件


### 代码操作
`option+ Up/Down`代码向上/下移动，只能移动至一块区域<br />`command + shift + X `大小写转换<br />`alt + 单击` 光标在多处定位<br />光标-shift 选中多行文本<br />contral + shift + x 收起目录


### 标记
`F3` 添加✔️标记<br />`alt + F3` 添加带字母或者是数字的标记<br />`command+F3` 打开标记列表


### 收藏
`alt + shift + F` 将文件加入到收藏夹


### 调试
`command + F8` 添加断点<br />`control + alt + R` 运行项目<br />`command + control + R` 运行Debug<br />


### 屏幕控制
`command + F3`屏幕缩小<br />`F3`  查看其他屏幕<br />`command + control + R` 屏幕录制<br />**Option-v/h**多屏编辑（竖屏/横屏）


### 自定义代码块
