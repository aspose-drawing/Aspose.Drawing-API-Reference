---
title: PageSettings
second_title: Aspose.Drawing for Java API リファレンス
description: 単一の印刷ページに適用される設定を指定します。
type: docs
weight: 10
url: /ja/java/com.aspose.drawing.printing/pagesettings/
---
**Inheritance:**
java.lang.Object
```
public class PageSettings
```

単一の印刷ページに適用される設定を指定します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PageSettings()](#PageSettings--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBounds()](#getBounds--) | [PageSettings](../../com.aspose.drawing.printing/pagesettings) プロパティで指定されたページの向きを考慮して、ページのサイズを取得します。 |
| [getHardMarginX()](#getHardMarginX--) | ページ左側のハードマージンの x 座標（インチの百分の一単位）を取得します。 |
| [getHardMarginY()](#getHardMarginY--) | ページ上部のハードマージンの y 座標（インチの百分の一単位）を取得します。 |
| [getPrinterResolution()](#getPrinterResolution--) | ページのプリンター解像度を取得します。 |
### PageSettings() {#PageSettings--}
```
public PageSettings()
```


### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


[PageSettings](../../com.aspose.drawing.printing/pagesettings) プロパティで指定されたページの向きを考慮して、ページのサイズを取得します。

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the length and width, in hundredths of an inch, of the page.
### getHardMarginX() {#getHardMarginX--}
```
public final float getHardMarginX()
```


ページ左側のハードマージンの x 座標（インチの百分の一単位）を取得します。

**Returns:**
float - 左側ハードマージンの x 座標（インチの百分の一単位）。
### getHardMarginY() {#getHardMarginY--}
```
public final float getHardMarginY()
```


ページ上部のハードマージンの y 座標（インチの百分の一単位）を取得します。

**Returns:**
float - ページ上部のハードマージンの y 座標（インチの百分の一単位）。
### getPrinterResolution() {#getPrinterResolution--}
```
public final PrinterResolution getPrinterResolution()
```


ページのプリンター解像度を取得します。

**Returns:**
[PrinterResolution](../../com.aspose.drawing.printing/printerresolution) - A `PrinterResolution`([.getPrinterResolution](../../null/\#getPrinterResolution)) that specifies the printer resolution for the page. The default is the printer's default resolution.
