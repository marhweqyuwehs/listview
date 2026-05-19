```markdown
# BookListView

圖書管理程式  
使用 C# WinForms 製作的 ListView 圖書管理介面。

## 專案功能

- 顯示書籍封面
- 切換檢視模式
- 顯示借書清單
- 使用大圖示與小圖示顯示書籍
- 模擬簡易圖書管理系統

## 使用技術

- C#
- Windows Forms
- ListView
- ImageList
- ComboBox
- GroupBox
- Panel

## 介面元件

| 元件名稱 | 功能 |
|---|---|
| lvwBooks | 顯示書籍 |
| cmbView | 切換檢視模式 |
| lstBorrow | 借書清單 |
| imgL | 大圖片清單 |
| imgS | 小圖片清單 |
| grpView | 檢視設定區 |
| grpBorrow | 借書區 |
| pnlTools | 工具面板 |

## 檢視模式

程式支援以下檢視模式：

- LargeIcon
- SmallIcon
- List
- Details

使用者可以透過 `cmbView` 切換顯示方式。

## ImageList 設定

### imgL

```text
ImageSize = 90,120
```

用於大圖示顯示。

### imgS

```text
ImageSize = 15,20
```

用於小圖示顯示。

## Dock 設定

| 元件 | Dock |
|---|---|
| lvwBooks | Fill |
| grpView | Top |
| grpBorrow | Fill |
| pnlTools | Right |

## 操作方式

1. 開啟 Visual Studio
2. 載入 `BookListView` 專案
3. 執行程式
4. 使用右上角下拉選單切換檢視模式
5. 點選書籍後可加入借書清單

## 專案畫面說明

左側為書籍顯示區，使用 `ListView` 呈現書籍封面與書名。

右側上方為檢視方式選擇區，使用 `ComboBox` 切換不同顯示模式。

右側下方為借書清單，使用 `ListBox` 顯示目前借出的書籍。


