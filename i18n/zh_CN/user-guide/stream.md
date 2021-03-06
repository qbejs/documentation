# 流

EspoCRM中的“流”是一种源（feed），你可以从中看到更新的内容和你所关注的记录的添加情况。你既可以把内容发布到自己的流中，也可以发布到别的用户的流中（从3.8.0版开始）     EspoCRM的流有两种：记录流和用户流。

在默认的情况下，以下的实体都有一个流：账户、联系人、潜在客户、机会、案例。管理员可以在“[实体管理器](../administration/entity-manager.md)”启用或停用特定实体的流。

## 记录流

在细节视图中，“记录流”在某个特定记录的“流”面板中显示。帖子、更新内容和有关当前记录的新添项目都在这里显示。

## 用户流

用户在“流”组件（dashlet）中，在“流”选项卡下面都可以看到自己的流，如果用户拥有由“角色”中的`用户权限`字段所决定的访问权，他们也可以在用户细节视图中查看另一名用户的流。

在用户流中，你可以看到帖子、更新内容和与用户所关注的记录相关的新增内容，以及发给这位用户的帖子。这些帖子都不与任何记录相关联。

## 通知

如果别的用户在你的流中增添了新内容，你就会收到通知。

## 帖子

你可以创建与某个记录相关的帖子，还可以在帖子上附上多份文件与图像。如果你要在帖子中提及某位用户，只需输入`@`符号，接着输入用户名。这样，帖子中提到的用户就会收到通知。

## 向用户发帖

_这项功能始于3.8.0.版。_

用户的帖子可以写给不同的对象：特定的用户、特定的团队、全部用户，还有用户自己。这项功能的使用权限由“角色”中的`指派权限`字段来决定。

## 筛选功能

让什么内容显示在流中，这是可以进行筛选的：`全部`、`帖子`或`更新`。
