# 文件相关操作

> 在仓库页面试着按下键盘的 t 键，然后输入要找的目录或文件的部分名称.筛选器会在仓库的目录和文件中进行筛 选，搜索出您要找的文件。这种方式要比一级级查看目录和文件快得多，请积极利用。

# 查看区别
## 在 GitHub 上，直接修改 URL 就可以让用户以多种形式查看差别
1. 查看分支间的区别
> 比如我们想查看 4-0-stable 分支与 3-2-stable 分支之间的差别，可以 像下面这样将分支名加到 URL 里。
> [https://github.com/rails/rails/compare/4-0-stable...3-2-stable](https://github.com/rails/rails/compare/4-0-stable...3-2-stable)

2. 查看与指定日期之间的区别
> 假如我们想查看 master 分支在最近 7 天内的差别，可以像下面这样 这样将时间加入 URL。
> [https://github.com/rails/rails/compare/master@{7.day.ago}...master](https://github.com/rails/rails/compare/master@{7.day.ago}...master)

> 假设我们想查看 master 分支 2013 年 1 月 1 日与现在的区别，可以 将日期加入 URL。
> [https://github.com/rails/rails/compare/master@{2013-01-01}...master](https://github.com/rails/rails/compare/master@{2013-01-01}...master)
