---
title: CharacterRange
second_title: Aspose.Drawing for Java API リファレンス
description: 文字列内の文字位置の範囲を指定します。
type: docs
weight: 13
url: /ja/java/com.aspose.drawing/characterrange/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class CharacterRange extends Struct<CharacterRange> implements Cloneable
```

文字列内の文字位置の範囲を指定します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [CharacterRange()](#CharacterRange--) |  |
| [CharacterRange(int first, int length)](#CharacterRange-int-int-) | 新しい [CharacterRange](../../com.aspose.drawing/characterrange) 構造体のインスタンスを初期化し、文字列内の文字位置の範囲を指定します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFirst()](#getFirst--) | この [CharacterRange](../../com.aspose.drawing/characterrange) の最初の文字の文字列内位置を取得または設定します。 |
| [setFirst(int value)](#setFirst-int-) | この [CharacterRange](../../com.aspose.drawing/characterrange) の最初の文字の文字列内位置を取得または設定します。 |
| [getLength()](#getLength--) | この [CharacterRange](../../com.aspose.drawing/characterrange) の位置数を取得または設定します。 |
| [setLength(int value)](#setLength-int-) | この [CharacterRange](../../com.aspose.drawing/characterrange) の位置数を取得または設定します。 |
| [op_Equality(CharacterRange cr1, CharacterRange cr2)](#op-Equality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-) | 2つの [CharacterRange](../../com.aspose.drawing/characterrange) オブジェクトを比較します。 |
| [op_Inequality(CharacterRange cr1, CharacterRange cr2)](#op-Inequality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-) | 2つの [CharacterRange](../../com.aspose.drawing/characterrange) オブジェクトを比較します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | このオブジェクトが指定されたオブジェクトと等価かどうかを示す値を取得します。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [CloneTo(CharacterRange that)](#CloneTo-com.aspose.drawing.CharacterRange-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### CharacterRange() {#CharacterRange--}
```
public CharacterRange()
```


### CharacterRange(int first, int length) {#CharacterRange-int-int-}
```
public CharacterRange(int first, int length)
```


新しい [CharacterRange](../../com.aspose.drawing/characterrange) 構造体のインスタンスを初期化し、文字列内の文字位置の範囲を指定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| first | int | 範囲内の最初の文字の位置です。たとえば、First が 0 に設定されている場合、範囲の最初の位置は文字列の位置 0 です。 |
| length | int | 範囲内の位置数です。 |

### getFirst() {#getFirst--}
```
public final int getFirst()
```


この [CharacterRange](../../com.aspose.drawing/characterrange) の最初の文字の文字列内位置を取得または設定します。

値: この [CharacterRange](../../com.aspose.drawing/characterrange) の最初の位置です。

**Returns:**
int
### setFirst(int value) {#setFirst-int-}
```
public final void setFirst(int value)
```


この [CharacterRange](../../com.aspose.drawing/characterrange) の最初の文字の文字列内位置を取得または設定します。

値: この [CharacterRange](../../com.aspose.drawing/characterrange) の最初の位置です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getLength() {#getLength--}
```
public final int getLength()
```


この [CharacterRange](../../com.aspose.drawing/characterrange) の位置数を取得または設定します。

値: この [CharacterRange](../../com.aspose.drawing/characterrange) の位置数です。

**Returns:**
int
### setLength(int value) {#setLength-int-}
```
public final void setLength(int value)
```


この [CharacterRange](../../com.aspose.drawing/characterrange) の位置数を取得または設定します。

値: この [CharacterRange](../../com.aspose.drawing/characterrange) の位置数です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### op_Equality(CharacterRange cr1, CharacterRange cr2) {#op-Equality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-}
```
public static boolean op_Equality(CharacterRange cr1, CharacterRange cr2)
```


2つの [CharacterRange](../../com.aspose.drawing/characterrange) オブジェクトを比較します。2つの [CharacterRange](../../com.aspose.drawing/characterrange) オブジェクトの First と Length の値が等しいかどうかを示す値を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cr1 | [CharacterRange](../../com.aspose.drawing/characterrange) | 等価比較のための [CharacterRange](../../com.aspose.drawing/characterrange)。 |
| cr2 | [CharacterRange](../../com.aspose.drawing/characterrange) | 等価比較のための [CharacterRange](../../com.aspose.drawing/characterrange)。 |

**Returns:**
boolean - `true` は 2 つの CharacterRange オブジェクトが同じ First と Length の値を持つことを示し、`false` はそれ以外を示します。
### op_Inequality(CharacterRange cr1, CharacterRange cr2) {#op-Inequality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-}
```
public static boolean op_Inequality(CharacterRange cr1, CharacterRange cr2)
```


2つの [CharacterRange](../../com.aspose.drawing/characterrange) オブジェクトを比較します。2つの [CharacterRange](../../com.aspose.drawing/characterrange) オブジェクトの First または Length の値が等しくないかどうかを示す値を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cr1 | [CharacterRange](../../com.aspose.drawing/characterrange) | 不等価比較のための [CharacterRange](../../com.aspose.drawing/characterrange)。 |
| cr2 | [CharacterRange](../../com.aspose.drawing/characterrange) | 不等価比較のための [CharacterRange](../../com.aspose.drawing/characterrange)。 |

**Returns:**
boolean - `true` は 2 つの CharacterRange オブジェクトの First または Length のいずれかの値が異なることを示し、`false` はそれ以外を示します。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このオブジェクトが指定されたオブジェクトと等価かどうかを示す値を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 等価比較のために比較されるオブジェクトです。 |

**Returns:**
boolean - `true` は、指定されたオブジェクトがこのインスタンスと同じ First と Length の値を持つインスタンスであることを示します。そうでない場合は `false`。
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - このインスタンスのハッシュコードとなる 32 ビット符号付き整数です。
### CloneTo(CharacterRange that) {#CloneTo-com.aspose.drawing.CharacterRange-}
```
public void CloneTo(CharacterRange that)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| that | [CharacterRange](../../com.aspose.drawing/characterrange) |  |

### Clone() {#Clone--}
```
public CharacterRange Clone()
```




**Returns:**
[CharacterRange](../../com.aspose.drawing/characterrange)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
