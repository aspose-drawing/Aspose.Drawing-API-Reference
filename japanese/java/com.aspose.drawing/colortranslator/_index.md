---
title: ColorTranslator
second_title: Aspose.Drawing for Java API リファレンス
description: 色を GDI の構造体に変換したり、GDI の構造体から変換したりします。
type: docs
weight: 16
url: /ja/java/com.aspose.drawing/colortranslator/
---
**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

色を GDI+ の [Color](../../com.aspose.drawing/color) 構造体に変換したり、そこから変換したりします。このクラスは継承できません。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ColorTranslator()](#ColorTranslator--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | HTML のカラー表現を GDI+ の [Color](../../com.aspose.drawing/color) 構造体に変換します。 |
| [toHtml(Color c)](#toHtml-com.aspose.drawing.Color-) | 指定された [Color](../../com.aspose.drawing/color) 構造体を HTML 文字列のカラー表現に変換します。 |
| [fromWin32(int win32Color)](#fromWin32-int-) | Windows のカラー値を GDI+ の [Color](../../com.aspose.drawing/color) 構造体に変換します。 |
| [fromOle(int oleColor)](#fromOle-int-) | OLE のカラー値を GDI+ の [Color](../../com.aspose.drawing/color) 構造体に変換します。 |
| [toWin32(Color c)](#toWin32-com.aspose.drawing.Color-) | [Color](../../com.aspose.drawing/color) 構造体を Win32 のカラー表現に変換します。 |
| [toOle(Color c)](#toOle-com.aspose.drawing.Color-) | [Color](../../com.aspose.drawing/color) 構造体を OLE のカラー表現に変換します。 |
### ColorTranslator() {#ColorTranslator--}
```
public ColorTranslator()
```


### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


HTML のカラー表現を GDI+ の [Color](../../com.aspose.drawing/color) 構造体に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| htmlColor | java.lang.String | 変換対象となる Html カラーの文字列表現です。 |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated HTML color or `Empty` if htmlColor is null.
### toHtml(Color c) {#toHtml-com.aspose.drawing.Color-}
```
public static String toHtml(Color c)
```


指定された [Color](../../com.aspose.drawing/color) 構造体を HTML 文字列のカラー表現に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | 変換対象の [Color](../../com.aspose.drawing/color) 構造体です。 |

**Returns:**
java.lang.String - HTML 色を表す文字列です。
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


Windows のカラー値を GDI+ の [Color](../../com.aspose.drawing/color) 構造体に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| win32Color | int | 変換対象の Windows カラーです。 |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated Windows color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


OLE のカラー値を GDI+ の [Color](../../com.aspose.drawing/color) 構造体に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| oleColor | int | 変換対象の OLE カラーです。 |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated OLE color.
### toWin32(Color c) {#toWin32-com.aspose.drawing.Color-}
```
public static int toWin32(Color c)
```


[Color](../../com.aspose.drawing/color) 構造体を Win32 のカラー表現に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | 変換する [Color](../../com.aspose.drawing/color) 構造体です。 |

**Returns:**
int - Win32 形式のカラーを表す値です。
### toOle(Color c) {#toOle-com.aspose.drawing.Color-}
```
public static int toOle(Color c)
```


[Color](../../com.aspose.drawing/color) 構造体を OLE のカラー表現に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | 変換する [Color](../../com.aspose.drawing/color) 構造体です。 |

**Returns:**
int - OLE 形式のカラーを表す値です。
