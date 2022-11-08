---
sidebar_position: 4
---

# 导航参数

## 视图模式

每一个打开或聚焦到一个分栏的动作都支持`viewmode`参数。接受如下值：

- `source`：设置编辑器为源码模式。
- `preview`：设置编辑器为阅读模式。
- `live`：设置编辑器为实时阅览模式。

## 新分栏

每一个打开分栏的动作都支持`newpane`参数。接受如下值：

- `true` 如果未打开当前文件则在新分栏中打开。
- `false` 如果未打开当前文件则在当前分栏中打开。
- 如果文件已经在另一分栏中打开，则切换焦点到该分栏。

你可以在插件设置中设置默认值。当在 URI 中定义该值时将替代默认值