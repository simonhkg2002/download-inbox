# Download Inbox

下載完成，順手命名和歸位。  
Rename and file your downloads while you still remember what they are.

> 狀態：產品規劃階段（Planning）。目前只有專案文件，尚未有可執行 App 或安裝版本。

Download Inbox 是一個規劃中的 macOS 效率工具（Productivity Tool）：下載完成後顯示輕量卡片，讓你重新命名、選擇目的地，或留待稍後處理。

## 預期操作

1. 下載完成，顯示檔名及整理卡片。
2. 輸入有意義的名稱，選取最近使用的目的地。
3. 按 Enter 完成歸檔，或選擇稍後處理。
4. 誤操作時使用撤銷（Undo）還原。

## 第一版範圍（MVP）

- 監察使用者選定的 Downloads 資料夾，確認下載完成後才提示。
- 同一卡片內重新命名與移動檔案。
- 記住最近使用的目的地。
- 提供選單列（Menu Bar）待整理清單及暫停提示。
- 支援安全的撤銷，不覆寫同名檔案。
- 採本機處理（Local Processing），基本流程不需要帳戶或 AI API。

## 文件

- [產品定義與互動原則](docs/PRODUCT.md)
- [開發里程碑](docs/ROADMAP.md)
- [協作指引](AGENTS.md)

## 目前待驗證

下載後的提示能否降低整理成本，同時避免打擾？第一個原型會優先驗證提示時機、鍵盤操作和稍後處理流程。

歡迎透過 Issues 描述你的下載整理情境，尤其是目前最麻煩的操作及希望如何改善。
