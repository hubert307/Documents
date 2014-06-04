解決 git did not exits cleanly(exit code 128) 錯誤的方式，

1. Private Key 放置的路徑當中不要有中文或空白。

2. 真的不行的時候放棄 SSH，以 HTTP 的方式進行登入，但要打帳號密碼。

3. TortoiseGit -> Pageant 要記得 Load Private Key，GitHub 網站要 Load Public Key。