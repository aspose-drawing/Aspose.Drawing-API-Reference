---
title: SystemFonts
second_title: Aspose.Drawing for Java API リファレンス
description: Windows の表示要素でテキストを表示するために使用されるフォントを指定します。
type: docs
weight: 51
url: /ja/java/com.aspose.drawing/systemfonts/
---
**Inheritance:**
java.lang.Object
```
public final class SystemFonts
```

Windows の表示要素でテキストを表示するために使用されるフォントを指定します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCaptionFont()](#getCaptionFont--) | ウィンドウのタイトルバーにテキストを表示するために使用される [Font](../../com.aspose.drawing/font) を取得します。 |
| [getSmallCaptionFont()](#getSmallCaptionFont--) | ツールウィンドウなどの小さなウィンドウのタイトルバーにテキストを表示するために使用される [Font](../../com.aspose.drawing/font) を取得します。 |
| [getMenuFont()](#getMenuFont--) | メニューに使用される [Font](../../com.aspose.drawing/font) を取得します。 |
| [getStatusFont()](#getStatusFont--) | ステータスバーにテキストを表示するために使用される [Font](../../com.aspose.drawing/font) を取得します。 |
| [getMessageBoxFont()](#getMessageBoxFont--) | メッセージボックスに使用される [Font](../../com.aspose.drawing/font) を取得します。 |
| [getIconTitleFont()](#getIconTitleFont--) | アイコンのタイトルに使用される [Font](../../com.aspose.drawing/font) を取得します。 |
| [getDefaultFont()](#getDefaultFont--) | アプリケーションがダイアログボックスやフォームで使用できるデフォルトフォントを取得します。 |
| [getDefaultImageFont()](#getDefaultImageFont--) | アプリケーションがダイアログボックスやフォームで使用できるデフォルトフォントを取得します。 |
| [getDialogFont()](#getDialogFont--) | アプリケーションがダイアログボックスやフォームで使用できるフォントを取得します。 |
| [getFontByName(String systemFontName)](#getFontByName-java.lang.String-) | 指定されたシステムフォント名に対応するフォントオブジェクトを返します。 |
### getCaptionFont() {#getCaptionFont--}
```
public static Font getCaptionFont()
```


ウィンドウのタイトルバーにテキストを表示するために使用される [Font](../../com.aspose.drawing/font) を取得します。

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the title bars of windows.
### getSmallCaptionFont() {#getSmallCaptionFont--}
```
public static Font getSmallCaptionFont()
```


ツールウィンドウなどの小さなウィンドウのタイトルバーにテキストを表示するために使用される [Font](../../com.aspose.drawing/font) を取得します。

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the title bars of small windows, such as tool windows.
### getMenuFont() {#getMenuFont--}
```
public static Font getMenuFont()
```


メニューに使用される [Font](../../com.aspose.drawing/font) を取得します。

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for menus.
### getStatusFont() {#getStatusFont--}
```
public static Font getStatusFont()
```


ステータスバーにテキストを表示するために使用される [Font](../../com.aspose.drawing/font) を取得します。

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the status bar.
### getMessageBoxFont() {#getMessageBoxFont--}
```
public static Font getMessageBoxFont()
```


メッセージボックスに使用される [Font](../../com.aspose.drawing/font) を取得します。

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for message boxes.
### getIconTitleFont() {#getIconTitleFont--}
```
public static Font getIconTitleFont()
```


アイコンのタイトルに使用される [Font](../../com.aspose.drawing/font) を取得します。

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for icon titles.
### getDefaultFont() {#getDefaultFont--}
```
public static Font getDefaultFont()
```


アプリケーションがダイアログボックスやフォームで使用できるデフォルトフォントを取得します。

**Returns:**
[Font](../../com.aspose.drawing/font) - The default [Font](../../com.aspose.drawing/font) of the system. The value returned will vary depending on the user's operating system and the local culture setting of their system.
### getDefaultImageFont() {#getDefaultImageFont--}
```
public static Font getDefaultImageFont()
```


アプリケーションがダイアログボックスやフォームで使用できるデフォルトフォントを取得します。

**Returns:**
[Font](../../com.aspose.imaging/font) - The default [Font](../../com.aspose.drawing/font) of the system. The value returned will vary depending on the user's operating system and the local culture setting of their system.
### getDialogFont() {#getDialogFont--}
```
public static Font getDialogFont()
```


アプリケーションがダイアログボックスやフォームで使用できるフォントを取得します。

**Returns:**
[Font](../../com.aspose.drawing/font) - A [Font](../../com.aspose.drawing/font) that can be used for dialog boxes and forms, depending on the operating system and local culture setting of the system.
### getFontByName(String systemFontName) {#getFontByName-java.lang.String-}
```
public static Font getFontByName(String systemFontName)
```


指定されたシステムフォント名に対応するフォントオブジェクトを返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| systemFontName | java.lang.String | フォントオブジェクトが必要なシステムフォントの名前です。 |

**Returns:**
[Font](../../com.aspose.drawing/font) - A [Font](../../com.aspose.drawing/font) if the specified name matches a value in [SystemFonts](../../com.aspose.drawing/systemfonts); otherwise, null.
