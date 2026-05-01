# 🐕 理性瘋狗 Nuke Team Raider

Discord 多功能工具，支援 Token 管理、頻道轟炸、私訊轟炸等 50 種功能。

---

## ⚠️ 免責聲明

本工具出事作者不負責，使用後果自負。

---

## 📦 安裝

1. 安裝 Python 3.13

下載網址：https://www.python.org/downloads/

安裝時勾選：
- Add Python to PATH
- pip

2. 安裝套件

py -3.13 -m pip install requests colorama

3. 下載程式碼

將 nuketeam_raider.py 下載到你的電腦

---

## 📁 準備 Token

建立 token.txt，每行放一個 Discord Token：

你的第一個Token
你的第二個Token
你的第三個Token

如何取得 Token？

1. 打開 Discord 網頁版，按 F12
2. 切換到 Console（控制台）
3. 貼上以下代碼，按 Enter：

(webpackChunkdiscord_app.push([[''],{},e=>{m=[];for(let c in e.c)m.push(e.c[c])}]),m).find(m=>m?.exports?.default?.getToken!).exports.default.getToken()

4. 複製出現的 Token

---

## 🚀 執行程式

cd 你的程式資料夾
py -3.13 nuketeam_raider.py

第一次使用請選擇 2 註冊，之後用 1 登入。

---

## 📖 功能列表

01 Token 檢查器      11 幽靈轟炸
02 Token 上線器      12 討論串轟炸
03 Token 加入伺服器  13 投票轟炸
04 Token 退出伺服器  14 大量交友
05 Token 分類器      15 Token 資訊
06 頻道轟炸          16 大量檢舉
07 表情轟炸          17 私訊轟炸
08 回覆轟炸          18 驗證碼繞過
09 論壇轟炸          19 @everyone 轟炸
10 審計轟炸          20 Token 人性化

按 P 進入第二頁（26-50）

---

## ❓ 常見問題

Q: 出現 No module named 'requests'？

py -3.13 -m pip install requests colorama

Q: Token 無效？

重新獲取 Token，不要改密碼。

Q: 出現 429？

發送太快，降低每秒次數。

---

## ⚠️ 注意事項

- 不要用主帳號
- 不要改密碼
- 後果自負

---

## 📌 版本資訊

v2.2.1 | Python 3.13 | 2026-05-01
