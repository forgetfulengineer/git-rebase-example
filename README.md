# git rebase 操作練習

這個 repository 使用於文章 [【Git】使用 git rebase 整理提交歷史](https://forgetfulengineer.github.io/Other/Git/Using-Git-Rebase-to-Organize-Commit-History/) 的操作練習

## 安裝方式

``` bash git
git clone https://github.com/forgetfulengineer/git-rebase-example.git
```

## 練習重點

1. 使用 `git rebase` 把 `dev` 分支的提交銜接到 `main` 的最新進度上，並查看提交歷史的變化

2. 使用 `git rebase -i` 整理歷史提交

- 調整提交順序
- 修改提交訊息（`r, reword`）
- 修改提交內容（`e, edit`）
- 合併提交（`s, squash` 或 `f, fixup`）
- 刪除提交（`d, drop`）

> 嗨！我是健忘工程師 😁，如果這個練習對你有幫助，也歡迎到我的 [網站](https://forgetfulengineer.github.io/Other/Git/Using-Git-Rebase-to-Organize-Commit-History/) 逛逛其他學習筆記唷～
