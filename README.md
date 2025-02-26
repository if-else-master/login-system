留言板系統

這是一個簡單的留言板系統，提供用戶註冊、登入、留言、修改留言、刪除留言及登出功能。

功能
- 用戶註冊與登入：使用者可以註冊並登入系統。
- 留言管理：
  - 發佈留言
  - 編輯自己的留言
  - 刪除自己的留言
- 登出功能：用戶可安全登出系統。

安裝與使用
1. 環境需求
- PHP 7.4 以上
- MySQL 5.7 以上
- Apache 或 Nginx 伺服器

2. 安裝步驟
1. 下載專案
   ```sh
   git clone https://github.com/if-else-master/login-system.git
   cd login system
   ```
2. 設定資料庫
   - 建立 MySQL 資料庫，並導入 `database.sql`
   - 更新 `config.php` 內的資料庫設定
3. 啟動伺服器
   - 若使用內建 PHP 伺服器：
     ```sh
     php -S localhost:8000
     ```
   - 或配置至 Apache/Nginx

3. 使用方式
1. 註冊帳號並登入
2. 發佈留言
3. 可選擇編輯或刪除自己的留言
4. 登出系統

## 目錄結構
```
message-board/
│── index.php         # 首頁（顯示留言）
│── login.php         # 登入頁面
│── register.php      # 註冊頁面
│── edit_message.php  # 編輯留言
│── logout.php        # 登出功能
│── config.php        # 資料庫設定
│── database.sql      # 資料庫結構
```

貢獻
歡迎 Fork 和 PR 改進此專案！

