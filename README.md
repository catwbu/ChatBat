# ChatBat

Zero 是一個使用 Windows 批次檔（Batch）編寫的簡易聊天機器人，能夠根據使用者輸入的關鍵字回應對話。

## 功能
- 根據關鍵字匹配對話內容。
- 隨機變化部分回應，使對話更具變化性。
- 可識別並回應多種常見用語，例如「嗨」、「幾點」、「你好」、「幹嘛」等。
- 內建一些幽默對話與玩梗內容。
- 會對特定關鍵字提供額外功能，例如開啟網站（如 Pornhub、Trivago）。
- 能夠變更命令提示字元（CMD）顏色（如輸入 "紅" 會變成紅色）。

## 使用方式
1. **運行 ChatBat**
   - 直接執行 `ChatBat.bat`，CMD 會開啟並等待使用者輸入。
2. **開始聊天**
   - 在命令提示字元內輸入任何文字，Zero 會根據關鍵字給出回應。
3. **退出程式**
   - 輸入「掰」、「bye」等關鍵字，Zero 會自動關閉。

## 特殊關鍵字
| 關鍵字 | 回應範例 |
|--------|---------|
| A片 | 自動開啟 Pornhub |
| 幾點 | 顯示當前時間 |
| 幾號 | 顯示當前日期 |
| 幾月 | 顯示當前月份 |
| 綠 | 變更 CMD 顏色為綠色 |
| 紅 | 變更 CMD 顏色為紅色 |
| 清頻 | 清除 CMD 畫面 |
| 掰 / bye | 退出程式 |

## 注意事項
- 這個程式是在國中時期編寫，僅作為娛樂用途。
- 批次檔的運行依賴於 Windows 環境，另有編譯過後的執行檔在Package。



