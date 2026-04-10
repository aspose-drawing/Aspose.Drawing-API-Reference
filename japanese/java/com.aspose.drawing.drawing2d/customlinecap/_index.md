---
title: CustomLineCap
second_title: Aspose.Drawing for Java API リファレンス
description: カスタムのユーザー定義ラインキャップをカプセル化します。
type: docs
weight: 17
url: /ja/java/com.aspose.drawing.drawing2d/customlinecap/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class CustomLineCap implements System.IDisposable
```

カスタムのユーザー定義ラインキャップをカプセル化します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-) | 指定された輪郭と塗りつぶしで [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) クラスの新しいインスタンスを初期化します。 |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-) | 指定された既存の [LineCap](../../com.aspose.drawing.drawing2d/linecap) 列挙体から、指定された輪郭と塗りつぶしで [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) クラスの新しいインスタンスを初期化します。 |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-) | 指定された既存の [LineCap](../../com.aspose.drawing.drawing2d/linecap) 列挙体から、指定された輪郭、塗りつぶし、およびインセットで [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getStrokeJoin()](#getStrokeJoin--) | この [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) オブジェクトを構成する線が結合される方法を決定する [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) 列挙体を取得または設定します。 |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | この [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) オブジェクトを構成する線が結合される方法を決定する [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) 列挙体を取得または設定します。 |
| [getBaseCap()](#getBaseCap--) | この [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) の基礎となる [LineCap](../../com.aspose.drawing.drawing2d/linecap) 列挙体を取得または設定します。 |
| [setBaseCap(int value)](#setBaseCap-int-) | この [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) の基礎となる [LineCap](../../com.aspose.drawing.drawing2d/linecap) 列挙体を取得または設定します。 |
| [getBaseInset()](#getBaseInset--) | キャップと線の間の距離を取得または設定します。 |
| [setBaseInset(float value)](#setBaseInset-float-) | キャップと線の間の距離を取得または設定します。 |
| [getWidthScale()](#getWidthScale--) | この [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) クラスオブジェクトを、[Pen](../../com.aspose.drawing/pen) オブジェクトの幅に対して拡大する量を取得または設定します。 |
| [setWidthScale(float value)](#setWidthScale-float-) | この [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) クラスオブジェクトを、[Pen](../../com.aspose.drawing/pen) オブジェクトの幅に対して拡大する量を取得または設定します。 |
| [dispose()](#dispose--) | この [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) オブジェクトが使用しているすべてのリソースを解放します。 |
| [deepClone()](#deepClone--) | この [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) の正確なコピーを作成します。 |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | このカスタムキャップを構成する線の開始と終了に使用されるキャップを設定します。 |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | このカスタムキャップを構成する線の開始と終了に使用されるキャップを取得します。 |
| [getFillPath()](#getFillPath--) |  |
| [getStrokePath()](#getStrokePath--) | カスタムキャップのアウトラインを定義するオブジェクトを取得します。 |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


指定された輪郭と塗りつぶしで [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | カスタムキャップの塗りつぶしを定義する [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) オブジェクトです。 |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | カスタムキャップのアウトラインを定義する [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) オブジェクトです。 |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


指定された既存の [LineCap](../../com.aspose.drawing.drawing2d/linecap) 列挙体から、指定された輪郭と塗りつぶしで [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | カスタムキャップの塗りつぶしを定義する [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) オブジェクトです。 |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | カスタムキャップのアウトラインを定義する [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) オブジェクトです。 |
| baseCap | int | カスタムキャップを作成する元になるラインキャップです。 |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


指定された既存の [LineCap](../../com.aspose.drawing.drawing2d/linecap) 列挙体から、指定された輪郭、塗りつぶし、およびインセットで [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | カスタムキャップの塗りつぶしを定義する [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) オブジェクトです。 |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | カスタムキャップのアウトラインを定義する [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) オブジェクトです。 |
| baseCap | int | カスタムキャップを作成する元になるラインキャップです。 |
| baseInset | float | キャップとラインの間の距離です。 |

### getStrokeJoin() {#getStrokeJoin--}
```
public final int getStrokeJoin()
```


この [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) オブジェクトを構成する線が結合される方法を決定する [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) 列挙体を取得または設定します。

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public final void setStrokeJoin(int value)
```


この [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) オブジェクトを構成する線が結合される方法を決定する [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) 列挙体を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getBaseCap() {#getBaseCap--}
```
public final int getBaseCap()
```


この [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) の基礎となる [LineCap](../../com.aspose.drawing.drawing2d/linecap) 列挙体を取得または設定します。

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public final void setBaseCap(int value)
```


この [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) の基礎となる [LineCap](../../com.aspose.drawing.drawing2d/linecap) 列挙体を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getBaseInset() {#getBaseInset--}
```
public final float getBaseInset()
```


キャップと線の間の距離を取得または設定します。

**Returns:**
float
### setBaseInset(float value) {#setBaseInset-float-}
```
public final void setBaseInset(float value)
```


キャップと線の間の距離を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getWidthScale() {#getWidthScale--}
```
public final float getWidthScale()
```


この [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) クラスオブジェクトを、[Pen](../../com.aspose.drawing/pen) オブジェクトの幅に対して拡大する量を取得または設定します。

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public final void setWidthScale(float value)
```


この [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) クラスオブジェクトを、[Pen](../../com.aspose.drawing/pen) オブジェクトの幅に対して拡大する量を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### dispose() {#dispose--}
```
public final void dispose()
```


この [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) オブジェクトが使用しているすべてのリソースを解放します。

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


この [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) の正確なコピーを作成します。

**Returns:**
java.lang.Object - このメソッドが作成する [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) をオブジェクトとしてキャストしたものです。
### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public final void setStrokeCaps(int startCap, int endCap)
```


このカスタムキャップを構成する線の開始と終了に使用されるキャップを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startCap | int | このキャップ内のラインの開始時に使用される [LineCap](../../com.aspose.drawing.drawing2d/linecap) 列挙です。 |
| endCap | int | このキャップ内のラインの終了時に使用される [LineCap](../../com.aspose.drawing.drawing2d/linecap) 列挙です。 |

### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public final void getStrokeCaps(int[] startCap, int[] endCap)
```


このカスタムキャップを構成する線の開始と終了に使用されるキャップを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startCap | int[] | このキャップ内のラインの開始時に使用される [LineCap](../../com.aspose.drawing.drawing2d/linecap) 列挙です。 |
| endCap | int[] | このキャップ内のラインの終了時に使用される [LineCap](../../com.aspose.drawing.drawing2d/linecap) 列挙です。 |

### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```




**Returns:**
[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)
### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


カスタムキャップのアウトラインを定義するオブジェクトを取得します。

**Returns:**
[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) - The object that defines the outline of the custom cap.
