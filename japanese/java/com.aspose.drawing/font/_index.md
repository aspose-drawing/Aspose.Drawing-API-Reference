---
title: Font
second_title: Aspose.Drawing for Java API リファレンス
description: フォントの顔、サイズ、スタイル属性を含むテキストの特定の書式を定義します。
type: docs
weight: 21
url: /ja/java/com.aspose.drawing/font/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Font implements System.IDisposable
```

フォントの顔、サイズ、スタイル属性を含むテキストの特定の書式を定義します。このクラスは継承できません。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.drawing.Font-int-) | 指定された既存の [Font](../../com.aspose.drawing/font) と [FontStyle](../../com.aspose.drawing/fontstyle) 列挙体を使用して、[Font](../../com.aspose.drawing/font) クラスの新しいインスタンスを初期化します。 |
| [Font(FontFamily family, float emSize)](#Font-com.aspose.drawing.FontFamily-float-) | 新しい [Font](../../com.aspose.drawing/font) クラスのインスタンスを初期化します。 |
| [Font(FontFamily family, float emSize, int style)](#Font-com.aspose.drawing.FontFamily-float-int-) | 指定されたサイズとスタイルを使用して、新しい [Font](../../com.aspose.drawing/font) クラスのインスタンスを初期化します。 |
| [Font(FontFamily family, float emSize, int style, int unit)](#Font-com.aspose.drawing.FontFamily-float-int-int-) | 指定されたサイズ、スタイル、単位を使用して、新しい [Font](../../com.aspose.drawing/font) クラスのインスタンスを初期化します。 |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-) | 指定されたサイズ、スタイル、単位、文字セットを使用して、新しい [Font](../../com.aspose.drawing/font) クラスのインスタンスを初期化します。 |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-) | 指定されたサイズ、スタイル、単位、文字セットを使用して、新しい [Font](../../com.aspose.drawing/font) クラスのインスタンスを初期化します。 |
| [Font(String familyName, float emSize)](#Font-java.lang.String-float-) | 指定されたサイズを使用して、新しい [Font](../../com.aspose.drawing/font) クラスのインスタンスを初期化します。 |
| [Font(String familyName, float emSize, int style)](#Font-java.lang.String-float-int-) | 指定されたサイズとスタイルを使用して、新しい [Font](../../com.aspose.drawing/font) クラスのインスタンスを初期化します。 |
| [Font(String familyName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | 指定されたサイズ、スタイル、単位を使用して、新しい [Font](../../com.aspose.drawing/font) クラスのインスタンスを初期化します。 |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)](#Font-java.lang.String-float-int-int-byte-) | 指定されたサイズ、スタイル、単位、文字セットを使用して、新しい [Font](../../com.aspose.drawing/font) クラスのインスタンスを初期化します。 |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-java.lang.String-float-int-int-byte-boolean-) | 指定されたサイズ、スタイル、単位、文字セットを使用して、新しい [Font](../../com.aspose.drawing/font) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFontFamily()](#getFontFamily--) | `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) に関連付けられたこの [Font](../../com.aspose.drawing/font) を取得します。 |
| [getBold()](#getBold--) | この [Font](../../com.aspose.drawing/font) が太字かどうかを示す値を取得します。 |
| [getGdiCharSet()](#getGdiCharSet--) | この [Font](../../com.aspose.drawing/font) が使用する GDI 文字セットを指定するバイト値を取得します。 |
| [getGdiVerticalFont()](#getGdiVerticalFont--) | この [Font](../../com.aspose.drawing/font) が GDI 垂直フォントから派生しているかどうかを示す値を取得します。 |
| [getItalic()](#getItalic--) | この [Font](../../com.aspose.drawing/font) がイタリック体かどうかを示す値を取得します。 |
| [getName()](#getName--) | この [Font](../../com.aspose.drawing/font) のフェイス名を取得します。 |
| [getStrikeout()](#getStrikeout--) | この [Font](../../com.aspose.drawing/font) がフォントに水平の取り消し線を指定しているかどうかを示す値を取得します。 |
| [getUnderline()](#getUnderline--) | この [Font](../../com.aspose.drawing/font) が下線付きかどうかを示す値を取得します。 |
| [getStyle()](#getStyle--) | この [Font](../../com.aspose.drawing/font) のスタイル情報を取得します。 |
| [getSize()](#getSize--) | `Font.Unit` プロパティで指定された単位で測定された、この [Font](../../com.aspose.drawing/font) の em サイズを取得します。 |
| [getSizeInPoints()](#getSizeInPoints--) | ポイント単位での、この [Font](../../com.aspose.drawing/font) の em サイズを取得します。 |
| [getUnit()](#getUnit--) | この [Font](../../com.aspose.drawing/font) の測定単位を取得します。 |
| [getHeight_Rename_Namesake()](#getHeight-Rename-Namesake--) | このフォントの行間隔を取得します。 |
| [isSystemFont()](#isSystemFont--) | フォントが [SystemFonts](../../com.aspose.drawing/systemfonts) のメンバーかどうかを示す値を取得します。 |
| [getSystemFontName()](#getSystemFontName--) | IsSystemFont プロパティが true を返す場合、システムフォントの名前を取得します。 |
| [getOriginalFontName()](#getOriginalFontName--) | 元々指定されたフォントの名前を取得します。 |
| [deepClone()](#deepClone--) | この [Font](../../com.aspose.drawing/font) の正確なコピーを作成します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定されたオブジェクトが [Font](../../com.aspose.drawing/font) であり、この [Font](../../com.aspose.drawing/font) と同じ `FontFamily`([.getFontFamily](../../null/\#getFontFamily))、`M:GdiVerticalFont`、`M:GdiCharSet`、`M:Style`、`M:Size`、`M:Unit` プロパティ値を持つかどうかを示します。 |
| [hashCode()](#hashCode--) | この [Font](../../com.aspose.drawing/font) のハッシュコードを取得します。 |
| [getHeight()](#getHeight--) | このフォントの行間隔（ピクセル単位）を返します。 |
| [getHeight(Graphics graphics)](#getHeight-com.aspose.drawing.Graphics-) | 指定された [Graphics](../../com.aspose.drawing/graphics) の現在の単位で、このフォントの行間隔を返します。 |
| [getHeight(float dpi)](#getHeight-float-) | 指定された垂直解像度のデバイスに描画されたときの、この [Font](../../com.aspose.drawing/font) の高さ（ピクセル単位）を返します。 |
| [dispose()](#dispose--) | この [Font](../../com.aspose.drawing/font) が使用しているすべてのリソースを解放します。 |
| [toString()](#toString--) | この [Font](../../com.aspose.drawing/font) の人間が読みやすい文字列表現を返します。 |
| [getCharacterSet()](#getCharacterSet--) | この `Font` が使用する文字セットを指定するバイト値を取得します。 |
### Font(Font prototype, int newStyle) {#Font-com.aspose.drawing.Font-int-}
```
public Font(Font prototype, int newStyle)
```


指定された既存の [Font](../../com.aspose.drawing/font) と [FontStyle](../../com.aspose.drawing/fontstyle) 列挙体を使用して、[Font](../../com.aspose.drawing/font) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.drawing/font) | 新しい [Font](../../com.aspose.drawing/font) を作成する元となる既存の [Font](../../com.aspose.drawing/font)。 |
| newStyle | int | 新しい [Font](../../com.aspose.drawing/font) に適用する [FontStyle](../../com.aspose.drawing/fontstyle)。[FontStyle](../../com.aspose.drawing/fontstyle) 列挙体の複数の値は OR 演算子で組み合わせることができます。 |

### Font(FontFamily family, float emSize) {#Font-com.aspose.drawing.FontFamily-float-}
```
public Font(FontFamily family, float emSize)
```


新しい [Font](../../com.aspose.drawing/font) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | 新しい [Font](../../com.aspose.drawing/font) の `FontFamily`([.getFontFamily](../../null/\#getFontFamily))。 |
| emSize | float | 新しいフォントの em サイズ（ポイント単位）。 |

### Font(FontFamily family, float emSize, int style) {#Font-com.aspose.drawing.FontFamily-float-int-}
```
public Font(FontFamily family, float emSize, int style)
```


指定されたサイズとスタイルを使用して、新しい [Font](../../com.aspose.drawing/font) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | 新しい [Font](../../com.aspose.drawing/font) の `FontFamily`([.getFontFamily](../../null/\#getFontFamily))。 |
| emSize | float | 新しいフォントの em サイズ（ポイント単位）。 |
| style | int | 新しいフォントの [FontStyle](../../com.aspose.drawing/fontstyle)。 |

### Font(FontFamily family, float emSize, int style, int unit) {#Font-com.aspose.drawing.FontFamily-float-int-int-}
```
public Font(FontFamily family, float emSize, int style, int unit)
```


指定されたサイズ、スタイル、単位を使用して、新しい [Font](../../com.aspose.drawing/font) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | 新しい [Font](../../com.aspose.drawing/font) の `FontFamily`([.getFontFamily](../../null/\#getFontFamily))。 |
| emSize | float | `unit` パラメーターで指定された単位での新しいフォントの em サイズ。 |
| style | int | 新しいフォントの [FontStyle](../../com.aspose.drawing/fontstyle)。 |
| unit | int | 新しいフォントの [GraphicsUnit](../../com.aspose.drawing/graphicsunit)。 |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)
```


指定されたサイズ、スタイル、単位、文字セットを使用して、新しい [Font](../../com.aspose.drawing/font) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | 新しい [Font](../../com.aspose.drawing/font) の `FontFamily`([.getFontFamily](../../null/\#getFontFamily))。 |
| emSize | float | `unit` パラメーターで指定された単位での新しいフォントの em サイズ。 |
| style | int | 新しいフォントの [FontStyle](../../com.aspose.drawing/fontstyle)。 |
| unit | int | 新しいフォントの [GraphicsUnit](../../com.aspose.drawing/graphicsunit)。 |
| gdiCharSet | byte | 新しいフォントで使用する GDI 文字セット。 |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


指定されたサイズ、スタイル、単位、文字セットを使用して、新しい [Font](../../com.aspose.drawing/font) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | 新しい [Font](../../com.aspose.drawing/font) の `FontFamily`([.getFontFamily](../../null/\#getFontFamily))。 |
| emSize | float | `unit` パラメーターで指定された単位での新しいフォントの em サイズ。 |
| style | int | 新しいフォントの [FontStyle](../../com.aspose.drawing/fontstyle)。 |
| unit | int | 新しいフォントの [GraphicsUnit](../../com.aspose.drawing/graphicsunit)。 |
| gdiCharSet | byte | 新しいフォントで使用する GDI 文字セット。 |
| gdiVerticalFont | boolean | 新しいフォントが GDI 垂直フォントから派生しているかどうかを示すブール値。 |

### Font(String familyName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String familyName, float emSize)
```


指定されたサイズを使用して、新しい [Font](../../com.aspose.drawing/font) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| familyName | java.lang.String | 新しい [Font](../../com.aspose.drawing/font) の FontFamily の文字列表現。 |
| emSize | float | 新しいフォントの em サイズ（ポイント単位）。 |

### Font(String familyName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String familyName, float emSize, int style)
```


指定されたサイズとスタイルを使用して、新しい [Font](../../com.aspose.drawing/font) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| familyName | java.lang.String | 新しい [Font](../../com.aspose.drawing/font) の FontFamily の文字列表現。 |
| emSize | float | 新しいフォントの em サイズ（ポイント単位）。 |
| style | int | 新しいフォントの [FontStyle](../../com.aspose.drawing/fontstyle)。 |

### Font(String familyName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String familyName, float emSize, int style, int unit)
```


指定されたサイズ、スタイル、単位を使用して、新しい [Font](../../com.aspose.drawing/font) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| familyName | java.lang.String | 新しい [Font](../../com.aspose.drawing/font) の `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) の文字列表現。 |
| emSize | float | `unit` パラメーターで指定された単位での新しいフォントの em サイズ。 |
| style | int | 新しいフォントの [FontStyle](../../com.aspose.drawing/fontstyle)。 |
| unit | int | 新しいフォントの [GraphicsUnit](../../com.aspose.drawing/graphicsunit)。 |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet) {#Font-java.lang.String-float-int-int-byte-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)
```


指定されたサイズ、スタイル、単位、文字セットを使用して、新しい [Font](../../com.aspose.drawing/font) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| familyName | java.lang.String | 新しい [Font](../../com.aspose.drawing/font) の FontFamily の文字列表現。 |
| emSize | float | `unit` パラメーターで指定された単位での新しいフォントの em サイズ。 |
| style | int | 新しいフォントの [FontStyle](../../com.aspose.drawing/fontstyle)。 |
| unit | int | 新しいフォントの [GraphicsUnit](../../com.aspose.drawing/graphicsunit)。 |
| gdiCharSet | byte | このフォントで使用する GDI 文字セットを指定するバイト。 |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-java.lang.String-float-int-int-byte-boolean-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


指定されたサイズ、スタイル、単位、文字セットを使用して、新しい [Font](../../com.aspose.drawing/font) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| familyName | java.lang.String | 新しい [Font](../../com.aspose.drawing/font) の FontFamily の文字列表現。 |
| emSize | float | `unit` パラメーターで指定された単位での新しいフォントの em サイズ。 |
| style | int | 新しいフォントの [FontStyle](../../com.aspose.drawing/fontstyle)。 |
| unit | int | 新しいフォントの [GraphicsUnit](../../com.aspose.drawing/graphicsunit)。 |
| gdiCharSet | byte | このフォントで使用する GDI 文字セットを指定するバイト。 |
| gdiVerticalFont | boolean | 新しい [Font](../../com.aspose.drawing/font) が GDI 垂直フォントから派生しているかどうかを示すブール値。 |

### getFontFamily() {#getFontFamily--}
```
public FontFamily getFontFamily()
```


`FontFamily`([.getFontFamily](../../null/\#getFontFamily)) に関連付けられたこの [Font](../../com.aspose.drawing/font) を取得します。

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - The `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) associated with this [Font](../../com.aspose.drawing/font).
### getBold() {#getBold--}
```
public boolean getBold()
```


この [Font](../../com.aspose.drawing/font) が太字かどうかを示す値を取得します。

**Returns:**
boolean - この [Font](../../com.aspose.drawing/font) が太字かどうかを示す値。
### getGdiCharSet() {#getGdiCharSet--}
```
public byte getGdiCharSet()
```


この [Font](../../com.aspose.drawing/font) が使用する GDI 文字セットを指定するバイト値を取得します。

**Returns:**
byte - この [Font](../../com.aspose.drawing/font) が使用する GDI 文字セットを指定するバイト値。
### getGdiVerticalFont() {#getGdiVerticalFont--}
```
public boolean getGdiVerticalFont()
```


この [Font](../../com.aspose.drawing/font) が GDI 垂直フォントから派生しているかどうかを示す値を取得します。

値: この [Font](../../com.aspose.drawing/font) が GDI 縦書きフォントから派生している場合は `true`、それ以外は `false`。

**Returns:**
boolean - この [Font](../../com.aspose.drawing/font) が GDI 縦書きフォントから派生しているかどうかを示す値。
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


この [Font](../../com.aspose.drawing/font) がイタリック体かどうかを示す値を取得します。

**Returns:**
boolean - この [Font](../../com.aspose.drawing/font) が斜体かどうかを示す値。
### getName() {#getName--}
```
public String getName()
```


この [Font](../../com.aspose.drawing/font) のフェイス名を取得します。

**Returns:**
java.lang.String - この [Font](../../com.aspose.drawing/font) のフォント名。
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


この [Font](../../com.aspose.drawing/font) がフォントに水平の取り消し線を指定しているかどうかを示す値を取得します。

**Returns:**
boolean - この [Font](../../com.aspose.drawing/font) がフォントに水平線を指定しているかどうかを示す値。
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


この [Font](../../com.aspose.drawing/font) が下線付きかどうかを示す値を取得します。

**Returns:**
boolean - この [Font](../../com.aspose.drawing/font) が下線付きかどうかを示す値。
### getStyle() {#getStyle--}
```
public int getStyle()
```


この [Font](../../com.aspose.drawing/font) のスタイル情報を取得します。

**Returns:**
int - この [Font](../../com.aspose.drawing/font) のスタイル情報。
### getSize() {#getSize--}
```
public float getSize()
```


`Font.Unit` プロパティで指定された単位で測定された、この [Font](../../com.aspose.drawing/font) の em サイズを取得します。

**Returns:**
float - この [Font](../../com.aspose.drawing/font) の em サイズで、\{@code Font} が指定する単位で測定されたもの。
### getSizeInPoints() {#getSizeInPoints--}
```
public float getSizeInPoints()
```


ポイント単位での、この [Font](../../com.aspose.drawing/font) の em サイズを取得します。

**Returns:**
float - この [Font](../../com.aspose.drawing/font) の em サイズ（ポイント単位）。
### getUnit() {#getUnit--}
```
public int getUnit()
```


この [Font](../../com.aspose.drawing/font) の測定単位を取得します。

**Returns:**
int - この [Font](../../com.aspose.drawing/font) の測定単位。
### getHeight_Rename_Namesake() {#getHeight-Rename-Namesake--}
```
public int getHeight_Rename_Namesake()
```


このフォントの行間隔を取得します。

値: このフォントの行間（ピクセル単位）。

**Returns:**
int - このフォントの行間。
### isSystemFont() {#isSystemFont--}
```
public boolean isSystemFont()
```


フォントが [SystemFonts](../../com.aspose.drawing/systemfonts) のメンバーかどうかを示す値を取得します。

値: フォントが [SystemFonts](../../com.aspose.drawing/systemfonts) のメンバーである場合は `true`、それ以外は `false`。

**Returns:**
boolean - フォントが [SystemFonts](../../com.aspose.drawing/systemfonts) のメンバーかどうかを示す値。
### getSystemFontName() {#getSystemFontName--}
```
public String getSystemFontName()
```


IsSystemFont プロパティが true を返す場合、システムフォントの名前を取得します。

値: IsSystemFont が true を返す場合のシステムフォント名。そうでない場合は空文字列 (\"\").

**Returns:**
java.lang.String - IsSystemFont プロパティが true を返す場合のシステムフォント名。
### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


元々指定されたフォントの名前を取得します。

値: 元々指定されたフォント名を表す文字列。

**Returns:**
java.lang.String - 元々指定されたフォント名。
### deepClone() {#deepClone--}
```
public Font deepClone()
```


この [Font](../../com.aspose.drawing/font) の正確なコピーを作成します。

**Returns:**
[Font](../../com.aspose.drawing/font) - The [Font](../../com.aspose.drawing/font) this method creates, cast as an Object.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定されたオブジェクトが [Font](../../com.aspose.drawing/font) であり、この [Font](../../com.aspose.drawing/font) と同じ `FontFamily`([.getFontFamily](../../null/\#getFontFamily))、`M:GdiVerticalFont`、`M:GdiCharSet`、`M:Style`、`M:Size`、`M:Unit` プロパティ値を持つかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | テスト対象のオブジェクトです。 |

**Returns:**
boolean - `obj` パラメータが [Font](../../com.aspose.drawing/font) であり、`FontFamily`([.getFontFamily](../../null/\#getFontFamily))、`M:GdiVerticalFont`、`M:GdiCharSet`、`M:Style`、`M:Size`、`M:Unit` プロパティの値がこの [Font](../../com.aspose.drawing/font) と同じ場合は `true`、それ以外は `false`。
### hashCode() {#hashCode--}
```
public int hashCode()
```


この [Font](../../com.aspose.drawing/font) のハッシュコードを取得します。

**Returns:**
int - この [Font](../../com.aspose.drawing/font) のハッシュコード。
### getHeight() {#getHeight--}
```
public int getHeight()
```


このフォントの行間隔（ピクセル単位）を返します。

**Returns:**
int - このフォントの行間（ピクセル単位）。
### getHeight(Graphics graphics) {#getHeight-com.aspose.drawing.Graphics-}
```
public float getHeight(Graphics graphics)
```


指定された [Graphics](../../com.aspose.drawing/graphics) の現在の単位で、このフォントの行間隔を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| graphics | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) は、ディスプレイデバイスの垂直解像度（dpi）とページ単位およびページスケールの設定を保持します。 |

**Returns:**
float - このフォントの行間（ピクセル単位）。
### getHeight(float dpi) {#getHeight-float-}
```
public int getHeight(float dpi)
```


指定された垂直解像度のデバイスに描画されたときの、この [Font](../../com.aspose.drawing/font) の高さ（ピクセル単位）を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dpi | float | フォントの高さを計算するために使用される、インチあたりドット数で表した垂直解像度です。 |

**Returns:**
int - この[Font](../../com.aspose.drawing/font)の高さ（ピクセル単位）。
### dispose() {#dispose--}
```
public void dispose()
```


この [Font](../../com.aspose.drawing/font) が使用しているすべてのリソースを解放します。

### toString() {#toString--}
```
public String toString()
```


この [Font](../../com.aspose.drawing/font) の人間が読みやすい文字列表現を返します。

**Returns:**
java.lang.String - この[Font](../../com.aspose.drawing/font)を表す文字列です。
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


この `Font` が使用する文字セットを指定するバイト値を取得します。

**Returns:**
int - この`Font`が使用する文字セットです。
