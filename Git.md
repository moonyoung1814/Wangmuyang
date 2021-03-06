

# Git简介

Git是一个开源的分布式版本控制系统，可以有效、高速地处理从很小到非常大的项目版本管理。利用Git，可以将项目中的每一个文件都管理起来。每个文件的修改、删除，Git都能跟踪，以便任何时刻都可以追踪历史，或者在将来某个时刻可以“还原”。

## Git管理仓库流程

- 在项目的目录下初始化Git仓库
- 将项目的文件添加到暂存区
- 提交到仓库
- 对项目进行了修改后，将修改的文件添加到暂存区，并提交到本地仓库
- 若项目的某个版本出现问题，可以随时回滚到任一历史版本

## Git操作本地仓库的常用命令

| 命令                          | 操作结果                       |
| ----------------------------- | ------------------------------ |
| `git init`                    | 在当前目录新建一个Git代码库    |
| `git add [file1] [file2] ...` | 添加指定的文件到暂存区         |
| `git add .`                   | 将当前目录所有文件添加到暂存区 |
| `git commit -m"message"`      | 将暂存区文件提交到仓库         |
| `git log`                     | 查看提交历史，与各次的提交说明 |

