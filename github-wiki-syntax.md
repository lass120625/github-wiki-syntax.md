# GitHub Wiki 語法參考

## 標題
```markdown
# 一級標題
## 二級標題
### 三級標題
#### 四級標題
##### 五級標題
###### 六級標題
```

## 文字格式
```markdown
**粗體文字**
*斜體文字*
***粗斜體***
~~刪除線~~
`行內程式碼`
```

## 清單
```markdown
# 無序清單
- 項目一
- 項目二
  - 子項目
  - 另一個子項目

# 有序清單
1. 第一項
2. 第二項
   1. 子項目
   2. 另一個子項目
```

## 連結
```markdown
# 外部連結
[連結文字](https://example.com)
[帶標題的連結](https://example.com "標題文字")

# Wiki內部連結
[[頁面名稱]]
[[顯示文字|頁面名稱]]
[[子頁面|Parent-Page/Sub-Page]]

# 自動連結
https://github.com
```

## 圖片
```markdown
![替代文字](圖片URL)
![替代文字](圖片URL "圖片標題")

# 指定圖片大小（HTML）
<img src="圖片URL" alt="替代文字" width="300">
```

## 程式碼
```markdown
# 行內程式碼
使用 `console.log()` 來輸出

# 程式碼區塊
```javascript
function hello() {
    console.log("Hello World!");
}
```

# 程式碼區塊（無語法高亮）
```
純文字程式碼
```
```

## 表格
```markdown
| 欄位1     | 欄位2     | 欄位3     |
|-----------|-----------|-----------|
| 內容1     | 內容2     | 內容3     |
| 較長內容  | 短內容    | 中等內容  |

# 對齊方式
| 左對齊    | 置中      | 右對齊    |
|:----------|:---------:|----------:|
| Left      | Center    | Right     |
```

## 引用與分隔
```markdown
# 引用區塊
> 這是引用文字
> 可以多行引用
>> 巢狀引用

# 水平分隔線
---
或
***
或
___
```

## 核取方塊
```markdown
- [x] 已完成的任務
- [ ] 未完成的任務
- [x] 另一個完成的任務
```

## GitHub 特有功能
```markdown
# 提及用戶和團隊
@username
@organization/team-name

# 連結到 Issues 和 Pull Requests
#123
organization/repository#123
GH-123

# 表情符號
:smile: :thumbsup: :heart: :rocket: :sparkles:
:warning: :information_source: :bulb: :fire:

# SHA 引用
commit SHA: a5c3785ed8d6a35868bc169f07e40e889087fd2e
簡短 SHA: a5c3785
```

## 數學公式
```markdown
# 行內數學公式
這是行內公式 $E = mc^2$

# 區塊數學公式
$$
\sum_{i=1}^{n} x_i = x_1 + x_2 + \cdots + x_n
$$
```

## HTML 標籤支援
```html
# 常用HTML標籤
<kbd>Ctrl</kbd> + <kbd>C</kbd>
<mark>高亮文字</mark>
<sub>下標</sub> 和 <sup>上標</sup>

# 詳細資訊摺疊
<details>
<summary>點擊展開</summary>
這裡是摺疊的內容
</details>

# 居中對齊
<div align="center">
    <img src="圖片URL" alt="描述">
    <p>圖片說明</p>
</div>
```

## Wiki 特殊頁面
```markdown
# 創建特殊頁面（檔案名稱）
Home.md          # Wiki 首頁
_Sidebar.md      # 側邊欄
_Footer.md       # 頁面底部

# 子頁面結構
Parent-Page.md
Parent-Page/Sub-Page-1.md
Parent-Page/Sub-Page-2.md
```

## 實用技巧
```markdown
# 目錄（TOC）
GitHub會自動生成，或手動創建：
- [標題一](#標題一)
- [標題二](#標題二)
- [子標題](#子標題)

# 錨點連結
[跳到特定標題](#標題名稱)
標題名稱會自動轉換為小寫，空格變成連字號

# 換行
在行末加兩個空格  
或使用空行

段落之間用空行分隔

# 跳脫字元
\* \_ \` \# \[ \]
```

## 常用範例模板

### 專案說明模板
```markdown
# 專案名稱

## 簡介
專案的簡短描述

## 安裝
```bash
npm install
```

## 使用方法
說明如何使用

## API 文檔
| 方法 | 參數 | 回傳值 | 描述 |
|------|------|--------|------|
| get  | id   | object | 取得資料 |

## 貢獻指南
1. Fork 專案
2. 建立功能分支
3. 提交變更
4. 發送 Pull Request
```

### 會議記錄模板
```markdown
# 會議記錄 - YYYY/MM/DD

## 參與者
- @user1
- @user2

## 議程
- [ ] 議題一
- [x] 議題二（已完成）

## 決議事項
> 重要決定內容

## 下次會議
**時間**：YYYY/MM/DD  
**地點**：會議室 A
```

## 鍵盤快捷鍵（編輯時）
- `Ctrl/Cmd + B` - 粗體
- `Ctrl/Cmd + I` - 斜體  
- `Ctrl/Cmd + K` - 插入連結
- `Ctrl/Cmd + Shift + P` - 預覽

---
*最後更新：2025年8月*
