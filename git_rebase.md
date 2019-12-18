下载了自己的仓库，然后在本地复制了该仓库中的文件到 repo A，但不包括.git文件夹下的内容。在repo A 中运行 git init, 在本地做版本控制，开发完后需要和远程仓库合并。此时使用git fetch 后，再使用git rebase 来解决冲突等问题。在rebase 过程中不断的 add 就好，不需要 commit。

参考：
1.https://www.yiibai.com/git/git_rebase.html
2.https://www.cnblogs.com/sinojelly/archive/2011/08/07/2130172.html
