---
title: GraphicsPathIterator
second_title: Aspose.Drawing for Java API リファレンス
description: サブパスを反復処理し、各サブパスに含まれる形状の種類をテストする機能を提供します。
type: docs
weight: 24
url: /ja/java/com.aspose.drawing.drawing2d/graphicspathiterator/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class GraphicsPathIterator implements System.IDisposable
```

サブパスを反復処理し、[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) の各サブパスに含まれるシェイプのタイプをテストする機能を提供します。このクラスは継承できません。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [GraphicsPathIterator(GraphicsPath path)](#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-) | 新しい [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCount()](#getCount--) | パス内のポイント数を取得します。 |
| [getSubpathCount()](#getSubpathCount--) | パス内のサブパス数を取得します。 |
| [dispose()](#dispose--) | アンマネージド リソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| [copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)](#copyData-com.aspose.drawing.PointF-----byte-----int-int-) | 関連付けられた [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) の GraphicsPath.PathPoints プロパティと GraphicsPath.PathTypes プロパティ配列を、指定された 2 つの配列にコピーします。 |
| [enumerate(PointF[][] points, byte[][] types)](#enumerate-com.aspose.drawing.PointF-----byte-----) | 関連付けられた [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) の GraphicsPath.PathPoints プロパティと GraphicsPath.PathTypes プロパティ配列を、指定された 2 つの配列にコピーします。 |
| [hasCurve()](#hasCurve--) | この [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) に関連付けられたパスに曲線が含まれるかどうかを示します。 |
| [nextMarker(int[] startIndex, int[] endIndex)](#nextMarker-int---int---) | [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) をパス内の次のマーカーに進め、[out] パラメーターで開始インデックスと終了インデックスを返します。 |
| [nextMarker(GraphicsPath path)](#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-) | この [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) オブジェクトには、関連付けられた [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) オブジェクトがあります。 |
| [nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)](#nextPathType-byte---int---int---) | 同じタイプを持つ次のデータポイント グループの開始インデックスと終了インデックスを取得します。 |
| [nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)](#nextSubpath-int---int---boolean---) | [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) をパス内の次のサブパスに移動します。 |
| [nextSubpath(GraphicsPath path, boolean[] isClosed)](#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---) | この [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) の関連パスから次の図形（サブパス）を取得します。 |
| [rewind()](#rewind--) | この [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) を関連パスの先頭に巻き戻します。 |
### GraphicsPathIterator(GraphicsPath path) {#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public GraphicsPathIterator(GraphicsPath path)
```


新しい [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | このヘルパークラスが初期化される対象の [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) オブジェクトです。 |

### getCount() {#getCount--}
```
public int getCount()
```


パス内のポイント数を取得します。

**Returns:**
int - パス内のポイント数。
### getSubpathCount() {#getSubpathCount--}
```
public int getSubpathCount()
```


パス内のサブパス数を取得します。

**Returns:**
int - パス内のサブパス数。
### dispose() {#dispose--}
```
public void dispose()
```


アンマネージド リソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。

### copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex) {#copyData-com.aspose.drawing.PointF-----byte-----int-int-}
```
public int copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)
```


関連付けられた [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) の GraphicsPath.PathPoints プロパティと GraphicsPath.PathTypes プロパティ配列を、指定された 2 つの配列にコピーします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | 戻り時に、パス内のポイントを表す System.Drawing.PointF 構造体の配列が含まれます。 |
| タイプ | byte[][] | 戻り時に、パス内のポイントのタイプを表すバイト配列が含まれます。 |
| startIndex | int | 配列の開始インデックスを指定します。 |
| endIndex | int | 配列の終了インデックスを指定します。 |

**Returns:**
int - コピーされたポイント数。
### enumerate(PointF[][] points, byte[][] types) {#enumerate-com.aspose.drawing.PointF-----byte-----}
```
public int enumerate(PointF[][] points, byte[][] types)
```


関連付けられた [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) の GraphicsPath.PathPoints プロパティと GraphicsPath.PathTypes プロパティ配列を、指定された 2 つの配列にコピーします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | 戻り時に、パス内のポイントを表す System.Drawing.PointF 構造体の配列が含まれます。 |
| タイプ | byte[][] | 戻り時に、パス内のポイントのタイプを表すバイト配列が含まれます。 |

**Returns:**
int - コピーされたポイント数。
### hasCurve() {#hasCurve--}
```
public boolean hasCurve()
```


この [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) に関連付けられたパスに曲線が含まれるかどうかを示します。

**Returns:**
boolean - このメソッドは、現在のサブパスに曲線が含まれている場合は true を返し、そうでない場合は false を返します。
### nextMarker(int[] startIndex, int[] endIndex) {#nextMarker-int---int---}
```
public int nextMarker(int[] startIndex, int[] endIndex)
```


[GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) をパス内の次のマーカーに進め、[out] パラメーターで開始インデックスと終了インデックスを返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startIndex | int[] | [out] このパラメータに供給された整数参照は、サブパスを開始する点のインデックスを受け取ります。 |
| endIndex | int[] | [out] このパラメータに供給された整数参照は、startIndex が指すサブパスの終了点のインデックスを受け取ります。 |

**Returns:**
int - このマーカーと次のマーカーの間の点の数です。
### nextMarker(GraphicsPath path) {#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public int nextMarker(GraphicsPath path)
```


この [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) オブジェクトは、関連付けられた [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) オブジェクトを持ちます。このメソッドは、関連付けられた [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) をパス内の次のマーカーへ進め、現在のマーカーと次のマーカー（またはパスの終端）間に含まれるすべての点を、パラメータとして渡された第2の [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) オブジェクトにコピーします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 点がコピーされる対象の [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) オブジェクトです。 |

**Returns:**
int - このマーカーと次のマーカーの間の点の数です。
### nextPathType(byte[] pathType, int[] startIndex, int[] endIndex) {#nextPathType-byte---int---int---}
```
public int nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)
```


同じタイプを持つ次のデータポイント グループの開始インデックスと終了インデックスを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pathType | byte[] | [out] グループ内のすべての点が共有する点のタイプを受け取ります。可能なタイプは [PathPointType](../../com.aspose.drawing.drawing2d/pathpointtype) 列挙体から取得できます。 |
| startIndex | int[] | [out] 点のグループの開始インデックスを受け取ります。 |
| endIndex | int[] | [out] 点のグループの終了インデックスを受け取ります。 |

**Returns:**
int - このメソッドは、グループ内のデータ点の数を返します。パスにこれ以上グループがない場合は、0 を返します。
### nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed) {#nextSubpath-int---int---boolean---}
```
public int nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)
```


[GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) をパス内の次のサブパスへ移動します。次のサブパスの開始インデックスと終了インデックスは [out] パラメータに格納されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startIndex | int[] | [out] 次のサブパスの開始インデックスを受け取ります。 |
| endIndex | int[] | [out] 次のサブパスの終了インデックスを受け取ります。 |
| isClosed | boolean[] | [out] サブパスが閉じているかどうかを示します。 |

**Returns:**
int - 取得された図形（サブパス）内のデータ点の数です。取得すべき図形がこれ以上ない場合は、0 が返されます。
### nextSubpath(GraphicsPath path, boolean[] isClosed) {#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---}
```
public int nextSubpath(GraphicsPath path, boolean[] isClosed)
```


この [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) の関連パスから次の図形（サブパス）を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | このイテレータ用に取得された図形（サブパス）のデータ点に合わせてデータ点が設定される [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) です。 |
| isClosed | boolean[] | [out] 現在のサブパスが閉じているかどうかを示します。図形が閉じている場合は true、そうでない場合は false です。 |

**Returns:**
int - 取得された図形（サブパス）内のデータ点の数です。取得すべき図形がこれ以上ない場合は、0 が返されます。
### rewind() {#rewind--}
```
public void rewind()
```


この [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) を関連パスの先頭に巻き戻します。

