# 🐕 理性瘋狗 Nuke Team Raider

一個功能完整的 Discord 多功能工具，支援 Token 管理、伺服器轟炸、私訊轟炸等 50+ 種功能。

![版本](https://img.shields.io/badge/version-2.2.1-brightgreen)
![Python](https://img.shields.io/badge/python-3.13-blue)
![Discord](https://img.shields.io/badge/discord-api-purple)

---

## ⚠️ 免責聲明

**本工具僅供教育用途，使用本工具造成的任何後果請自行負責。**

- 使用 User Token 違反 Discord 服務條款
- 可能會導致你的 Discord 帳號被永久停權
- 請勿用於非法或惡意用途
- 作者不負任何法律責任

---

## 📦 安裝需求

### 1. 安裝 Python 3.13

請先安裝 Python 3.13 或更高版本

下載網址：https://www.python.org/downloads/

安裝時請勾選：
- ✅ Add Python to PATH
- ✅ pip

### 2. 安裝必要套件

打開命令提示字元 (CMD)，輸入以下指令：


py -3.13 -m pip install requests colorama
如果下載太慢，可以使用國內鏡像：

bash
py -3.13 -m pip install requests colorama -i https://pypi.tuna.tsinghua.edu.cn/simple
3. 下載程式碼
將 nuketeam_raider.py 下載到你的電腦

📁 檔案準備
建立 token.txt
在程式同一個資料夾建立 token.txt 檔案，每行放一個 Discord Token：

text
你的第一個Token
你的第二個Token
你的第三個Token
如何取得 Discord Token？
打開 Discord 網頁版 (https://discord.com/login)

按 F12 打開開發者工具

切換到 Console（控制台） 標籤

貼上以下代碼並按 Enter：

javascript
(webpackChunkdiscord_app.push([[''],{},e=>{m=[];for(let c in e.c)m.push(e.c[c])}]),m).find(m=>m?.exports?.default?.getToken!).exports.default.getToken()
複製輸出的 Token（很長的一串）

🚀 執行程式
1. 打開命令提示字元
按 Win + R，輸入 cmd，按 Enter

2. 切換到程式資料夾
bash
cd C:\Users\你的用戶名\下載\NukeTeamRaider
3. 執行程式
bash
py -3.13 nuketeam_raider.py
📖 使用教學
第一次使用
執行程式後，會看到登入畫面

選擇 2 註冊新帳號

輸入用戶名和密碼

註冊完成後，選擇 1 登入

進入主選單

主選單介面
text
[01] Token 檢查器          [06] 頻道轟炸       [11] 幽靈轟炸        [16] 大量檢舉
[02] Token 上線器          [07] 表情轟炸       [12] 討論串轟炸      [17] 私訊轟炸
[03] Token 加入伺服器      [08] 回覆轟炸       [13] 投票轟炸        [18] 驗證碼繞過
[04] Token 退出伺服器      [09] 論壇轟炸       [14] 大量交友        [19] @everyone 轟炸
[05] Token 分類器          [10] 審計轟炸       [15] Token 資訊      [20] Token 人性化

[P] 下一頁                      [00] 退出程式
功能說明
第一頁 (01-20)
編號	功能	說明
01	Token 檢查器	檢查所有 Token 是否有效
02	Token 上線器	將 Token 設為上線狀態
03	Token 加入伺服器	用 Token 加入伺服器
04	Token 退出伺服器	讓 Token 退出指定伺服器
05	Token 分類器	分出有效/無效 Token
06	頻道轟炸	大量發送訊息到頻道
07	表情轟炸	大量添加表情反應
08	回覆轟炸	大量回覆指定訊息
09	論壇轟炸	論壇頻道轟炸
10	審計轟炸	大量創建頻道填滿審計日誌
11	幽靈轟炸	發送訊息後快速刪除
12	討論串轟炸	大量創建討論串
13	投票轟炸	大量創建投票
14	大量交友	大量發送好友邀請
15	Token 資訊	顯示 Token 詳細資訊
16	大量檢舉	⚠️ 高風險功能
17	私訊轟炸	大量發送私訊
18	驗證碼繞過	說明教學（無法繞過）
19	@everyone 轟炸	大量發送 @everyone 訊息
20	Token 人性化	模擬真人行為
第二頁 (26-50)
按 P 進入第二頁

編號	功能	說明
26	伺服器炸彈	大量創建頻道+角色
27	多頻道轟炸	在多個頻道同時轟炸
28	驗證繞過	繞過伺服器驗證（已失效）
29	狀態輪播	自動切換上線/閒置/勿擾
30	Token偽裝	偽裝 Token 顯示格式
31	防封鎖	防封鎖建議教學
32	大量票券	大量創建票券頻道
33	語音騷擾	語音頻道騷擾（需 discum）
34	大量發送	同頻道轟炸
35	語音加入	加入語音頻道（需 discum）
36	語音加入轟炸	大量加入語音頻道
37	邀請蒐集	蒐集伺服器邀請連結
38	音效板轟炸	音效板轟炸
39	QR碼記錄	QR碼登入記錄
40	聊天鏡像	鏡像聊天訊息到另一個頻道
41	語音炸彈	語音頻道炸彈
42	成員蒐集	蒐集伺服器所有成員
43	抽獎加入	自動加入抽獎
44	貼圖轟炸	貼圖轟炸
45	私訊服主	私訊伺服器擁有者
46	多重加入	用所有 Token 加入伺服器
47	語音YT音樂	播放 YouTube 音樂
48	退出所有伺服器	退出所有伺服器
49	兌換碼	兌換 Discord 禮物
50	AI聊天	AI 對話機器人
🔧 常見問題
Q1: 出現「ModuleNotFoundError: No module named 'requests'」
解決方法： 安裝缺少的套件

bash
py -3.13 -m pip install requests colorama
Q2: 出現「No module named 'colorama'」
解決方法： 安裝 colorama

bash
py -3.13 -m pip install colorama
Q3: Token 無效怎麼辦？
重新獲取新的 Token

確認 Token 沒有複製錯誤

確認沒有更改 Discord 密碼

Q4: 出現 429 錯誤
發送速度太快，Discord 限制了

建議降低每秒發送次數

Q5: 出現「需要驗證」提示
Token 被 Discord 風控了

需要手動用手機驗證

Q6: 如何關閉程式？
在主選單輸入 00

或直接關閉視窗

📝 速度調整建議
用途	建議每秒次數	說明
低調使用	5-10 次/秒	較不容易被偵測
一般使用	15-20 次/秒	平衡速度與安全
極限測試	30-50 次/秒	容易觸發 429
⚠️ 注意事項
不要使用主帳號：建議使用小號

不要改密碼：改密碼會讓 Token 失效

避免 24 小時運行：容易被 Discord 偵測

使用代理 IP：多 Token 建議用不同 IP

後果自負：使用本工具風險自負

📌 版本資訊
當前版本：2.2.1

Python 版本：3.13

最後更新：2026-05-01

🎯 總結
安裝 Python 3.13

安裝套件：py -3.13 -m pip install requests colorama

建立 token.txt 放入 Token

執行程式：py -3.13 nuketeam_raider.py

註冊帳號並登入

選擇功能編號開始使用
