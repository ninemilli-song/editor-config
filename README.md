# editor-config

## vscode vim plugin 设置

### 资源管理器(keybinding.json)

```
j： 向下移动
k： 向上移动
space： 打开文件或目录
// 手动新增：
i： 新增文件
o： 新增目录
r： 刷新目录
a： 重命名文件或目录
d： 删除文件或目录
x： 剪切文件或目录
y： 复制文件或目录
p： 粘贴文件或目录
```

### 全局命令(keybinding.json)

```
cmd + g c ： 显示命令面板
cmd + g s ： 打开设置页面
cmd + g k ： 打开热键映射
cmd + g m ： 打开一个目录
cmd + g f ： 打开一个文件
cmd + g h ： 打开最近记录
cmd + g n ： 新建vscode实例
cmd + g q ： 关闭vscode示例
```

### 侧边栏（keybinding.json）

```json
cmd + b： 切换侧边栏显示状态(系统)
cmd + shift + e： 显示文件资源管理器
cmd + shift + t： 显示TODOTree
cmd + shift + g： 显示版本控制
cmd + n 7： 显示Docker
```

### 编辑区域操作(keybinding.json)

```
cmd+ q ：关闭当前选项卡或分屏
cmd+ w s ：拆分一个上下分屏
cmd+ w v ：拆分一个左右分屏
cmd+ w k ：将光标向上移动1屏
cmd+ w j ：将光标向下移动1屏
cmd+ w h ：将光标向左移动1屏
cmd+ w l ：将光标向右移动1屏
cmd + alt + <方向键> ：切换tab
cmd + 1 ：切换到第一个编辑器组
cmd + e q ：关闭编辑器组
cmd + ctrl + <方向键> ：将编辑器移到到其它组
```

### 代码编辑器命令(keybinding.json)

```
cmd + h ： 触发帮助提示
cmd + j ： 触发参数提示
cmd + k ： 触发建议提示
tab ： 选择下一个建议 
enter ： 选择当前建议
cmd + alt + l ： 格式化代码（个人习惯）
cmd + = ： 放大字体
cmd + - ： 缩小字体
shift + alt + F8：转到上一个问题（系统）
```

### 终端操作（keybinding.json）

```
cmd + t \ : 切换到终端tabs
cmd + t c : 创建终端(编辑区右侧)
cmd + t n : 创建终端
cmd + t f : 聚焦到终端
cmd + t e : 终端移动到编辑器
cmd + t r : 终端移动到面板
cmd + t q : 终止活动终端实例
cmd + ` : 显示/隐藏终端
```
