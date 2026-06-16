---
title: StringFormat
second_title: Aspose.Drawing for Java API リファレンス
description: 配置方向やタブ位置などの表示操作、例えば省略記号の挿入、数字のローカライズ置換、OpenType 機能など、テキストレイアウト情報をカプセル化します。
type: docs
weight: 47
url: /ja/java/com.aspose.drawing/stringformat/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class StringFormat implements System.IDisposable
```

テキストレイアウト情報（配置、向き、タブストップなど）と表示操作（省略記号の挿入や国内数字の置換など）および OpenType 機能をカプセル化します。このクラスは継承できません。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [StringFormat()](#StringFormat--) | 新しい [StringFormat](../../com.aspose.drawing/stringformat) クラスのインスタンスを初期化します。 |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.drawing.StringFormat-) | 指定された既存の [StringFormat](../../com.aspose.drawing/stringformat) オブジェクトから新しい [StringFormat](../../com.aspose.drawing/stringformat) クラスのインスタンスを初期化します。 |
| [StringFormat(int options, int language)](#StringFormat-int-int-) | 指定された [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 列挙体と言語を使用して、新しい [StringFormat](../../com.aspose.drawing/stringformat) クラスのインスタンスを初期化します。 |
| [StringFormat(int options)](#StringFormat-int-) | 指定された [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 列挙体を使用して、新しい [StringFormat](../../com.aspose.drawing/stringformat) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) |  |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) |  |
| [getFirstTabOffset()](#getFirstTabOffset--) |  |
| [getGenericDefault()](#getGenericDefault--) | 汎用のデフォルト [StringFormat](../../com.aspose.drawing/stringformat) オブジェクトを取得します。 |
| [getGenericTypographic()](#getGenericTypographic--) | 汎用の組版用 [StringFormat](../../com.aspose.drawing/stringformat) オブジェクトを取得します。 |
| [getFormatFlags()](#getFormatFlags--) | [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 列挙体（書式情報を含む）を取得または設定します。 |
| [setFormatFlags(int value)](#setFormatFlags-int-) | [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 列挙体（書式情報を含む）を取得または設定します。 |
| [getAlignment()](#getAlignment--) | 垂直方向のテキスト配置情報を取得または設定します。 |
| [setAlignment(int value)](#setAlignment-int-) | 垂直方向のテキスト配置情報を取得または設定します。 |
| [getLineAlignment()](#getLineAlignment--) | 水平方向の行配置を取得または設定します。 |
| [setLineAlignment(int value)](#setLineAlignment-int-) | 水平方向の行配置を取得または設定します。 |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | `HotkeyPrefix` オブジェクト（[.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)）をこの [StringFormat](../../com.aspose.drawing/stringformat) オブジェクトに対して取得または設定します。 |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | `HotkeyPrefix` オブジェクト（[.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)）をこの [StringFormat](../../com.aspose.drawing/stringformat) オブジェクトに対して取得または設定します。 |
| [getTrimming()](#getTrimming--) | この [StringFormat](../../com.aspose.drawing/stringformat) オブジェクトの [StringTrimming](../../com.aspose.drawing/stringtrimming) 列挙体を取得または設定します。 |
| [setTrimming(int value)](#setTrimming-int-) | この [StringFormat](../../com.aspose.drawing/stringformat) オブジェクトの [StringTrimming](../../com.aspose.drawing/stringtrimming) 列挙体を取得または設定します。 |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | ローカル数字が西洋数字に置換される際に使用される言語を取得します。 |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | 数字置換に使用される方法を取得します。 |
| [dispose()](#dispose--) | この [StringFormat](../../com.aspose.drawing/stringformat) オブジェクトが使用しているすべてのリソースを解放します。 |
| [deepClone()](#deepClone--) | この [StringFormat](../../com.aspose.drawing/stringformat) オブジェクトの正確なコピーを作成します。 |
| [getTabStops(float[] firstTabOffset)](#getTabStops-float---) | この [StringFormat](../../com.aspose.drawing/stringformat) オブジェクトのタブストップを取得します。 |
| [getTabStops()](#getTabStops--) | `Aspose.Imaging.getGraphics().PageUnit` プロパティで指定された単位で、タブストップ間の距離の配列を取得します。 |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | この [StringFormat](../../com.aspose.drawing/stringformat) オブジェクトのタブストップを設定します。 |
| [setDigitSubstitution(int language, int substitute)](#setDigitSubstitution-int-int-) | ローカル数字が西洋数字に置換される際に使用される言語と方法を指定します。 |
| [setMeasurableCharacterRanges(CharacterRange[] ranges)](#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---) | `MeasureCharacterRanges` メソッドの呼び出しで測定される文字範囲を表す [CharacterRange](../../com.aspose.drawing/characterrange) 構造体の配列を指定します。 |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


新しい [StringFormat](../../com.aspose.drawing/stringformat) クラスのインスタンスを初期化します。

### StringFormat(StringFormat format) {#StringFormat-com.aspose.drawing.StringFormat-}
```
public StringFormat(StringFormat format)
```


指定された既存の [StringFormat](../../com.aspose.drawing/stringformat) オブジェクトから新しい [StringFormat](../../com.aspose.drawing/stringformat) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.drawing/stringformat) | 新しい [StringFormat](../../com.aspose.drawing/stringformat) オブジェクトを初期化する元となる [StringFormat](../../com.aspose.drawing/stringformat) オブジェクトです。 |

### StringFormat(int options, int language) {#StringFormat-int-int-}
```
public StringFormat(int options, int language)
```


指定された [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 列挙体と言語を使用して、新しい [StringFormat](../../com.aspose.drawing/stringformat) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| options | int | 新しい [StringFormat](../../com.aspose.drawing/stringformat) オブジェクト用の [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 列挙体です。 |
| 言語 | int | テキストの言語を示す値です。 |

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


指定された [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 列挙体を使用して、新しい [StringFormat](../../com.aspose.drawing/stringformat) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| options | int | 新しい [StringFormat](../../com.aspose.drawing/stringformat) オブジェクト用の [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 列挙体です。 |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```




**Returns:**
float
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


汎用のデフォルト [StringFormat](../../com.aspose.drawing/stringformat) オブジェクトを取得します。

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat)
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


汎用の組版用 [StringFormat](../../com.aspose.drawing/stringformat) オブジェクトを取得します。

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - A generic typographic [StringFormat](../../com.aspose.drawing/stringformat) object.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


[StringFormatFlags](../../com.aspose.drawing/stringformatflags) 列挙体（書式情報を含む）を取得または設定します。

**Returns:**
int
### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


[StringFormatFlags](../../com.aspose.drawing/stringformatflags) 列挙体（書式情報を含む）を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


垂直方向のテキスト配置情報を取得または設定します。

**Returns:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


垂直方向のテキスト配置情報を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


水平方向の行配置を取得または設定します。

**Returns:**
int
### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


水平方向の行配置を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


`HotkeyPrefix` オブジェクト（[.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)）をこの [StringFormat](../../com.aspose.drawing/stringformat) オブジェクトに対して取得または設定します。

**Returns:**
int
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


`HotkeyPrefix` オブジェクト（[.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)）をこの [StringFormat](../../com.aspose.drawing/stringformat) オブジェクトに対して取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


この [StringFormat](../../com.aspose.drawing/stringformat) オブジェクトの [StringTrimming](../../com.aspose.drawing/stringtrimming) 列挙体を取得または設定します。

**Returns:**
int
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


この [StringFormat](../../com.aspose.drawing/stringformat) オブジェクトの [StringTrimming](../../com.aspose.drawing/stringtrimming) 列挙体を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


ローカル数字が西洋数字に置換される際に使用される言語を取得します。

**Returns:**
int - ローカル数字が西洋数字に置き換えられる際に使用される言語を識別する、National Language Support (NLS) 言語識別子です。`System.Globalization.CultureInfo.LCID` プロパティ（java.util.Locale オブジェクトの）を NLS 言語識別子として渡すことができます。例として、文字列 "ar-EG" を java.util.Locale コンストラクタに渡して java.util.Locale オブジェクトを作成したとします。その java.util.Locale オブジェクトの `System.Globalization.CultureInfo.LCID` プロパティを `StringDigitSubstitute.Traditional` と共に [.setDigitSubstitution(int,int)](../../null/\#setDigitSubstitution-int-int-) メソッドに渡すと、表示時にアラビア・インディック数字が西洋数字に置き換えられます。
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


数字置換に使用される方法を取得します。

**Returns:**
int - 現在のフォントでサポートされていないため表示できない文字列内の文字をどのように置き換えるかを指定する [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute) 列挙値です。
### dispose() {#dispose--}
```
public void dispose()
```


この [StringFormat](../../com.aspose.drawing/stringformat) オブジェクトが使用しているすべてのリソースを解放します。

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


この [StringFormat](../../com.aspose.drawing/stringformat) オブジェクトの正確なコピーを作成します。

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - The [StringFormat](../../com.aspose.drawing/stringformat) object this method creates.
### getTabStops(float[] firstTabOffset) {#getTabStops-float---}
```
public float[] getTabStops(float[] firstTabOffset)
```


この [StringFormat](../../com.aspose.drawing/stringformat) オブジェクトのタブストップを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| firstTabOffset | float[] | テキスト行の開始位置と最初のタブ位置の間のスペース数です。 |

**Returns:**
float[] - タブ位置間の距離（スペース数）を格納した配列です。
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


`Aspose.Imaging.getGraphics().PageUnit` プロパティで指定された単位で、タブストップ間の距離の配列を取得します。

**Returns:**
float[] - タブ位置です。

このプロパティは削除されたメソッド GetTabStops 用に導入されました。
### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


この [StringFormat](../../com.aspose.drawing/stringformat) オブジェクトのタブストップを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| firstTabOffset | float | テキスト行の開始位置と最初のタブ位置の間のスペース数です。 |
| tabStops | float[] | Graphics.PageUnit プロパティで指定された単位で表した、タブ位置間の距離を格納した配列です。 |

### setDigitSubstitution(int language, int substitute) {#setDigitSubstitution-int-int-}
```
public void setDigitSubstitution(int language, int substitute)
```


ローカル数字が西洋数字に置換される際に使用される言語と方法を指定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 言語 | int | National Language Support (NLS) 言語識別子は、ローカル数字が西洋数字に置き換えられる際に使用される言語を識別します。`System.Globalization.CultureInfo.LCID` プロパティ（java.util.Locale オブジェクトの）を NLS 言語識別子として渡すことができます。例として、文字列 `"ar-EG"` を java.util.Locale コンストラクタに渡して java.util.Locale オブジェクトを作成したとします。その java.util.Locale オブジェクトの `System.Globalization.CultureInfo.LCID` プロパティを `StringDigitSubstitute.Traditional` と共に `M:StringFormat.SetDigitSubstitution(System.Int32,StringDigitSubstitute)` メソッドに渡すと、表示時にアラビア・インディック数字が西洋数字に置き換えられます。 |
| substitute | int | [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute) 列挙体の要素で、数字の表示方法を指定します。 |

### setMeasurableCharacterRanges(CharacterRange[] ranges) {#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---}
```
public void setMeasurableCharacterRanges(CharacterRange[] ranges)
```


`MeasureCharacterRanges` メソッドの呼び出しで測定される文字範囲を表す [CharacterRange](../../com.aspose.drawing/characterrange) 構造体の配列を指定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ranges | [CharacterRange\[\]](../../com.aspose.drawing/characterrange) | `MeasureCharacterRanges` メソッドの呼び出しで測定される文字の範囲を指定する [CharacterRange](../../com.aspose.drawing/characterrange) 構造体の配列です。 |

