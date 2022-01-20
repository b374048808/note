<!--
 * @Author: Xjie<374048808@qq.com>
 * @Date: 2022-01-20 13:10:02
 * @LastEditors: Xjie<374048808@qq.com>
 * @LastEditTime: 2022-01-20 13:11:08
 * @Description:
-->

命令行上创建一个新的存储库

```
echo "# note" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/b374048808/note.git
git push -u origin main
```

命令行推送现有存储库

```
git remote add origin https://github.com/b374048808/note.git
git branch -M main
git push -u origin main
```
