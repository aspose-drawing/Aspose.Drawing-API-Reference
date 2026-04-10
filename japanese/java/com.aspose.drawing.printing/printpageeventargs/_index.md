---
title: PrintPageEventArgs
second_title: Aspose.Drawing for Java API リファレンス
description: EPrintDocument.PrintPage イベントに対するデータを提供します。
type: docs
weight: 13
url: /ja/java/com.aspose.drawing.printing/printpageeventargs/
---
**Inheritance:**
java.lang.Object
```
public class PrintPageEventArgs
```

`E:PrintDocument.PrintPage` イベントのデータを提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PrintPageEventArgs()](#PrintPageEventArgs--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getGraphics()](#getGraphics--) | ページの描画に使用される `Graphics`([.getGraphics](../../null/\#getGraphics)) を取得します。 |
| [hasMorePages()](#hasMorePages--) | 追加ページを印刷すべきかどうかを示す値を取得します。 |
| [setMorePages(boolean value)](#setMorePages-boolean-) | 追加ページを印刷すべきかどうかを示す値を設定します。 |
| [getPageSettings()](#getPageSettings--) | 現在のページのページ設定を取得します。 |
### PrintPageEventArgs() {#PrintPageEventArgs--}
```
public PrintPageEventArgs()
```


### getGraphics() {#getGraphics--}
```
public final Graphics getGraphics()
```


ページの描画に使用される `Graphics`([.getGraphics](../../null/\#getGraphics)) を取得します。

**Returns:**
[Graphics](../../com.aspose.drawing/graphics) - The `Graphics`([.getGraphics](../../null/\#getGraphics)) used to paint the page.
### hasMorePages() {#hasMorePages--}
```
public final boolean hasMorePages()
```


追加ページを印刷すべきかどうかを示す値を取得します。

**Returns:**
boolean - 追加ページを印刷すべき場合は `true`、それ以外は false。デフォルトは `false` です。
### setMorePages(boolean value) {#setMorePages-boolean-}
```
public final void setMorePages(boolean value)
```


追加ページを印刷すべきかどうかを示す値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean | 追加ページを印刷すべきかどうかを示す値。 |

### getPageSettings() {#getPageSettings--}
```
public final PageSettings getPageSettings()
```


現在のページのページ設定を取得します。

**Returns:**
[PageSettings](../../com.aspose.drawing.printing/pagesettings) - The page settings for the current page.
