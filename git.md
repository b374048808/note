<!--
 * @Author: Xjie<374048808@qq.com>
 * @Date: 2022-01-20 13:10:02
 * @LastEditors: Xjie<374048808@qq.com>
 * @LastEditTime: 2022-01-20 13:23:39
 * @Description:
-->

命令行上创建一个新的存储库
写入字符并创建 README 文件

```
echo "# note" >> README.md
```

初始化 git

```
git init
```

添加文件到暂存区

```
git add README.md
git add .
```

命令将暂存区内容添加到本地仓库中。

```
git commit -m "first commit"
```

创建分支

```
git branch -M main
```

添加存储库

```
git remote add origin https://github.com/b374048808/note.git
```

将本地的 master 分支推送到 origin 主机

```
git push -u origin main
```

命令行推送现有存储库

```
git remote add origin https://github.com/b374048808/note.git
git branch -M main
git push -u origin main
```
