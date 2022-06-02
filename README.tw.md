<div align ="center">
      <img alt ="" src ="https://kaisunc.github.io/vscodevimacademy/data/images/banner.png" />
</div>

<h1> VSCODE VIM 學院 </h1>

# 注意! 購買沒收到License
購買license若沒在5分鐘以內拿到，請聯絡: kaisun.c@gmail.com，我會補寄給你。
這問題還在觀察中，目前是有一些中國的email會漏掉。

# 注意! 切換中文
若在移動模式(Normal Mode)切換到中文輸入只會讓你卡住！
Vscode Vim 有設定可以記住在編輯模式(Insert Mode)最後的輸入法，而且換到移動模式(Normal Mode)的時候進入關掉輸入法(Input Method - IM)。

**先下載 [im-select](https://github.com/daipeihust/im-select#installation)**

**至vscode settings > extensions > vim 找到以下四個設定**
1. Auto Switch Input Method: Default IM: 1033
2. Auto Switch Input Method: Enable: 勾選
3. Auto Switch Input Method: Obtain IMCmd: c:\任何位置\im-select.exe
4. Auto Switch Input Method: Switch IMCmd: c:\任何位置\im-select.exe {im}

**註解:**
1. 1033 是英數輸入法的代碼，當進入 Normal Mode 時會把輸入法切還成這邊設定的。
2. 使用自動切換輸入法
3. 切換輸入法程式
4. 切換輸入法程式指令


# 關於

這是一個教育性遊戲來學習vim和vscode的常用按鍵。每個關卡會讓你學習或複習2~5個常用按鍵。
例如，

1. 往前或後移至單字**頭**
1. 往前或後移至單字**尾**
1. 以單字頭前後移頭
1. 上下移動任何行數
1. 從當前位置向前或向後刪除單字
1. 刪除單字，恢復原狀(UNDO)或重做(REDO)
1. 選擇，刪除或更改行
1. 刪除，複製或粘貼單詞
1. 還有更多

玩家只需盡可能少地按一下鍵，就可以快速完成10組任務。提示和手冊將列在右側面板(CONSOLE)上，將根據您執行的速度和使用的按鍵次數記錄每個任務的性能。

---

<br>

## 類別
級別分為五個類別。

1. ![](https://via.placeholder.com/15/1589F0/000000?text=+)`移動`
2. ![](https://via.placeholder.com/15/1589F0/000000?text=+)`橫向編輯`
3. ![](https://via.placeholder.com/15/1589F0/000000?text=+)`直向編輯`
4. ![](https://via.placeholder.com/15/1589F0/000000?text=+)`文字物件 包圍`
5. ![](https://via.placeholder.com/15/1589F0/000000?text=+)`介面`

## 顏色編碼
在編輯器中，任務將在文本周圍顯示為顏色輪廓。它可以是單個字符，單詞，線條，文本對像或塊。

1. ![](https://via.placeholder.com/15/f9cc6c/000000?text=+)`內部-將光標移到黃色框中`
1. ![](https://via.placeholder.com/15/fd6883/000000?text=+)`刪除-刪除紅色框的內容`
1. ![](https://via.placeholder.com/15/f38d70/000000?text=+)`選擇-選擇橙色框的內容`
1. ![](https://via.placeholder.com/15/addb78/000000?text=+)`貼上-將綠色框的內容粘貼到綠色光標位置`
1. ![](https://via.placeholder.com/15/e4d2d4/000000?text=+)`複製-複製灰色框的內容`
1. ![](https://via.placeholder.com/15/b267e6/000000?text=+)`編輯-取決於關卡，更改，插入，縮進，註釋，添加，減去`
1. ![](https://via.placeholder.com/15/1589f0/000000?text=+)`外部-幫助類型，移到外部即可完成任務。`

<br>

# 快速開始

1. 安裝[VSCODE VIM](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)外掛，以在vscode中啟用vim模擬。
2. 安裝[VSCODE VIM ACADEMY](https://marketplace.visualstudio.com/items?itemName=kaisun.vscodevimacademy)
3. 打開命令面板(command palette)[ctrl + shift + p]()
4. 在命令面板中輸入[" start vva"]()以啟動遊戲。
   <details>
   <summary>
    影片教學
   </summary>

   <img alt ="" src =" https://kaisunc.github.io/vscodevimacademy/data/images/activation.gif" />
   </details>
5. 切換至中文介面，ctrl+, 進設定，搜尋vva，Language

<br> </br>

## 使用介面

### 資訊(CONSOLE)

1. 右上角的星級是重要性
1. 關卡總時間
1. 效率，嘗試將青色線(目前關卡任務)保持在紅線(建議標準速度)之下
   1. ![](https://via.placeholder.com/15/01B5B8/000000?text=+)`Current-當前任務速度`
   1. ![](https://via.placeholder.com/15/BE9E3B/000000?text=+)`Current Avg-當前級別任務的平均值`
   1. ![](https://via.placeholder.com/15/C64349/000000?text=+)`Target-基於我的時間`
   1. ![](https://via.placeholder.com/15/000000/000000?text=+)`Hist-歷史記錄-這些基於我在遊戲測試中的時間`
1. 任務表
1. 目前關卡的按鍵和說明

<img alt ="" src =" https://kaisunc.github.io/vscodevimacademy/data/images/uiLevelInfo.png" />

---

<br> </br>

### 選關
<img alt ="" src ="https://kaisunc.github.io/vscodevimacademy/data/images/endCursor.gif" />

手不離鍵盤選下一個關卡，使用vim鍵移動光標，

1. ![](https://via.placeholder.com/15/f9cc6c/000000?text=+)`0-上一關`
1. ![](https://via.placeholder.com/15/f9cc6c/000000?text=+)`b-重試目前的關`
1. ![](https://via.placeholder.com/15/f9cc6c/000000?text=+)`w-下一關`
1. ![](https://via.placeholder.com/15/f9cc6c/000000?text=+)`$-打開"購買此外掛"頁面`

要選擇特定級別，請使用控制台返回到級別選擇頁面
您還可以為上一個，下一個和重試級別綁定鍵

1. ![](https://via.placeholder.com/15/f9cc6c/000000?text=+)`vva.prevLevel`
1. ![](https://via.placeholder.com/15/f9cc6c/000000?text=+)`vva.retryLevel`
1. ![](https://via.placeholder.com/15/f9cc6c/000000?text=+)`vva.nextLevel`


---

<br> </br>

### Vim按鍵HUD

精心打造的SVG動畫!

按[ctrl + alt + c]()在編輯器中切換HUD，此功能不需要購買或啟動VVA

<img alt="" src="https://kaisunc.github.io/vscodevimacademy/data/images/cheatSheetsm.gif" />

---

**圖片版本**

|                                                                                               亮(可印)                                                                                               |                                                                                                  暗                                                                                                  |
| :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| <a href="https://kaisunc.github.io/vscodevimacademy/data/images/cheatsheetLight.png"><img alt="" width="300" src="https://kaisunc.github.io/vscodevimacademy/data/images/cheatsheetLight.png" /></a> | <a href="https://kaisunc.github.io/vscodevimacademy/data/images/cheatsheetDark.png"> <img alt="" width="300" src="https://kaisunc.github.io/vscodevimacademy/data/images/cheatsheetDark.png" /> </a> |
*CC BY-NC-ND 4.0*
<br></br>

# 示範
<img alt="" src="https://kaisunc.github.io/vscodevimacademy/data/images/quickDemo.gif" />

---

<details>
<summary>
基本關卡與介面
</summary>
<img alt="" src="https://kaisunc.github.io/vscodevimacademy/data/images/basics.gif" />
</details>

<details>
<summary>
左右移動至單字開頭
</summary>
<img alt="" src="https://kaisunc.github.io/vscodevimacademy/data/images/word.gif" />
</details>

<details>
<summary>
多項編輯&複數移動
</summary>
<img alt="" src="https://kaisunc.github.io/vscodevimacademy/data/images/actions_motion.gif" />
</details>

<br>

# 關卡細節

<details>
<summary>
移動
</summary>

1. 左右1
1. 上下1
1. 所有方向
1. 左右2
1. 上下2
1. 單字左右1
1. 單字左右2
1. 單字尾1
1. 複習 - 單字開與尾
1. 行首，行尾，行第一字母
1. 複習 - wb ， 行首，行尾，行第一字母
1. 單字左右3
1. 單字尾2
1. 複習 - WB & ege
1. 頁面頂部和底部
1. 相對上下
1. 複習 - 頁面頂部和底部 ，跳至行
1. 跳至行
1. 複習 - 跳至行，相對行
1. 屏幕的頂部，中間，​​底部
1. 半屏上下
1. 全屏上下
1. 複習 -
1. 上下至章節
1. 轉到下一句
1. 上下至'}'分段
1. 上下至'{'分段
1. 上下至分段
1. 上下至分段
1. 轉到文件百分比
1. 鼠標懸停
1. 下對配對
1. 搜索字母1
1. 單字搜索1
1. 單字搜索2
1. 單字搜索2
1. 跳至定義
1. 書籤
</details>

<details>
<summary>
橫向編輯
</summary>

1. 視覺模式1-選擇並退出
1. 視覺模式2-漸進式選擇
1. 選擇單詞
1. 刪除單詞
1. 貼詞
1. 刪除單詞
1. 複製字詞
1. 更改單詞
1. 替代單詞
1. 重新命名變數/功能/物件
1. 動作+移動
1. 動作+動作
1. 恢復重做
1. 選擇至字母(包含)
1. 選擇至字母(不包含)
1. 刪除和退格
1. 刪除和退格
1. 大小寫
1. 加減1
1. 加減2 - 1-100
1. 插入字符或字
1. 替換字符並替換為
1. 光標處或光標後編輯
1. 插入到EOL和FCOL


</details>

<details>
<summary>
直向編輯
</summary>

1. 選擇行模式1-選擇並退出
1. 選擇行模式2-漸進式選擇
1. 刪除行
1. 複製行
1. 改變行
1. 貼行
1. 插入行
1. 替換行
1. 複習-單行全部
1. 選擇多行
1. 複製多行
1. 插入多行
1. 刪除多行
1. 替換多行
1. 複製行貼上
1. 兩行合一
1. 上下對換行
1. 縮進行
1. 註解行


</details>

<details>
<summary>
文字物件 包圍
</summary>

1. 選擇文字物件
1. 選擇括弧，引號內(包含)
1. 選擇括弧，引號內(不包含)
1. 刪除/改變括弧，引號內(包含)
1. 刪除/改變括弧，引號內(不包含)
1. 增加括弧，引號
1. 刪除括弧，引號
1. 改變括弧，引號
1. 刪除HTML TAG ，內(包含TAG)，內(不包含TAG)

</details>

<details>
<summary>
UI 介面
</summary>

1. 選擇編輯組
1. 左右文件
1. 左右編輯組
1. 快速選擇檔案1-搜尋
1. 快速選擇檔案2-上次開

</details>

<br>

# 購買

購買KEY以解鎖所有關卡

[![paypal](https://www.paypalobjects.com/en_US/TW/i/btn/btn_buynowCC_LG_wCUP.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=7SQ5JH6B6MHFJ)

會收到一封email含 license key，在console 右上方可以進入license 介面
