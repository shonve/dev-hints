title: git submodule
categories:
 - Git
author: 宋玉
date: 2020-02-22 12:14:35
---
<a name="Mr2db"></a>
### 优雅的删除子模块

```bash
# 逆初始化模块，其中{MOD_NAME}为模块目录，执行后可发现模块目录被清空
git submodule deinit {MOD_NAME} 
# 删除.gitmodules中记录的模块信息（--cached选项清除.git/modules中的缓存）
git rm --cached {MOD_NAME} 
# 提交更改到代码库，可观察到'.gitmodules'内容发生变更
git commit -am "Remove a submodule."
```


