目标：本地更改github上代码


1. clone已有仓库。  通过 git clone 下载至本地。如：`git clone git@github.com:KaryDean/note.git`

2. 编写代码 。如：写入新的代码或者更新已有代码。可以通过 `git status`检查，返回 Untracked files

3. 提交代码。 通过git add 命令添加至暂存区。`git add hello_world.go`。再通过`git commit -m "add hello world by go"`提交。可以通过`git log`查看日志

4. 进行push。通过执行`git push`，github仓库就会更新

> tips: git是管理代码的仓库，githup相当于界面，这里的git是本地的，需要上传至github的仓库
