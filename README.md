
# 🤡 SB 井字遊戲

> 一款語氣狂妄的井字遊戲，由 Justin 欽定製作，程式語句充滿魔性與羞辱，專為真正的勇者而寫。

![tic-tac-toe](https://img.shields.io/badge/Language-C-blue)
![status](https://img.shields.io/badge/Version-1.0-brightgreen)
![license](https://img.shields.io/badge/License-MIT-yellow)

---

## 🎮 封面圖

```
   1 | 2 | 3
  ---+---+---
   4 | 5 | 6
  ---+---+---
   7 | 8 | 9
```

---

## 🧠 遊戲規則

- 雙人輪流輸入數字（1–9）代表下棋位置。
- 玩家 O 與 X 輪流落子。
- 先連成一線（橫、直、斜）者即為勝利者，但……
- 勝利的一方會被程式宣告為「傻逼」。
- 若棋盤填滿無勝負，雙方一同被表揚為「你們都是SB, 超棒」。

---

## 🕹️ 操作方式

### 1️⃣ 編譯程式

```bash
gcc -o sb_game sb_game.c
```

### 2️⃣ 執行遊戲

```bash
./sb_game
```

### 3️⃣ 遵從指示

依提示輸入 1 到 9 的數字，選擇棋盤上的位置。  
若輸入錯誤或位置已被佔用，將被語言暴打。

---

## ✨ 程式特色

- 陣列 `a[9]` 控制棋盤格狀態。
- 使用 `%c` 巧妙印出 O / X / 空白。
- 勝利條件以條件判斷檢查八種可能。
- 內建高壓式訓練語言：

```text
輸入，傻逼:
you are SB, follow the poops(rule)
O是傻逼!!
X是傻逼
你們都是SB,超棒
```

---

## 📁 檔案內容

| 檔案名稱     | 說明         |
|--------------|--------------|
| `sb_game.c`  | 主程式碼檔案 |

---

## 🧪 範例畫面

```
=============================
   1 | 2 | 3 
  ---+---+---
   4 | 5 | 6 
  ---+---+---
   7 | 8 | 9 
=============================
輸入，傻逼: 5
...
O是傻逼!!
```

---

## 📜 授權 License

本程式碼遵循 MIT License。歡迎自由使用、修改、再發佈。

```text
MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy
...
```

---

## 👑 作者 Justin 宣示：

> 此乃朕親手所寫，罵人乃愛之深責之切。汝若不喜，亦請安然離去；汝若歡喜，願與朕一同笑罵人生。
