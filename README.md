#Swift 雨燕編程語言 繁體中文版
The Swift Programming Language in Traditional Chinese
=====================================================

繁體中文版 Apple 官方 Swift 教程《The Swift Programming Language》

請幫忙翻譯或者校對,謝謝！

# 在線閱讀

使用Gitbook製作，可以直接[在線閱讀](swiftplus.github.io/The-Swift-Programming-Language-in-Traditional-Chinese)。

其他格式可以通過PDF轉換

# 當前階段

文章翻譯中...


# 貢獻力量

如果想做出貢獻的話，你可以：

- 幫忙校對，挑錯別字、病句等等
- 提出修改建議
- 提出術語翻譯建議

# 翻譯建議

如果你願意一起校對的話，請仔細閱讀：

- 使用markdown進行翻譯，文件名必須使用英文，因為中文的話gitbook編譯的時候會出問題
- 翻譯後的文檔請放到source文件夾下的對應章節中，然後pull request即可，我會用gitbook編譯成網頁
- 工作分支為gh-pages，用於GitHub的pages服務
- fork過去之後新建一個分支進行翻譯，完成後pull request這個分支，沒問題的話我會合併到gh-pages分支中
- 有其他任何問題都歡迎發issue，我看到了會盡快回复

謝謝！

# 關於專業術語

翻譯術語的時候請參考這個流程：

- 盡量確認和已翻譯的內容一致
- 先搜索，編程語言的大部分術語是一樣的，可以參考[微軟官方術語搜索](http://www.microsoft.com/Language/zh-hk/Search.aspx)
- 如果以上兩條都沒有找到合適的結果，請自己決定一個合適的翻譯或者直接使用英文原文，後期校對的時候會進行統一

# 參考流程

有些朋友可能不太清楚如何幫忙翻譯，這裡寫一個簡單的流程，參考一下：

1. 首先fork項目
2. 把fork過去的項目也就是你的項目clone到你的本地
3. 在命令行運行`git branch develop` 來創建一個新分支
4. 運行`git checkout develop` 來切換到新分支
5. 運行`git remote add upstream https://github.com/SwiftPlus/The-Swift-Programming-Language-in-Traditional-Chinese.git` 把庫添加為遠端庫
6. 運行 `git remote update`更新
7. 運行`git fetch upstream gh-pages` 拉取庫的更新到本地
8. 運行`git rebase upstream/gh-pages` 將更新合併到你的分支

這是一個初始化流程，只需要做一遍就行，之後請一直在develop分支進行修改。

如果修改過程中我的庫有了更新，請重複6、7、8步。

修改之後，首先push到你的庫，然後登錄GitHub，在你的庫的首頁可以看到一個`pull request` 按鈕，點擊它，填寫一些說明信息，然後提交即可。
