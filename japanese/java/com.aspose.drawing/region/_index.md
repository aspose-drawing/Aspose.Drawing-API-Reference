---
title: Region
second_title: Aspose.Drawing for Java API リファレンス
description: 矩形とパスで構成されたグラフィック形状の内部を記述します。
type: docs
weight: 40
url: /ja/java/com.aspose.drawing/region/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Region implements System.IDisposable
```

矩形とパスで構成されたグラフィック形状の内部を記述します。このクラスは継承できません。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Region()](#Region--) | 新しい [Region](../../com.aspose.drawing/region) クラスのインスタンスを初期化します。 |
| [Region(RectangleF rect)](#Region-com.aspose.drawing.RectangleF-) | 指定された [RectangleF](../../com.aspose.drawing/rectanglef) 構造体から新しい [Region](../../com.aspose.drawing/region) クラスのインスタンスを初期化します。 |
| [Region(Rectangle rect)](#Region-com.aspose.drawing.Rectangle-) | 指定された [Rectangle](../../com.aspose.drawing/rectangle) 構造体から新しい [Region](../../com.aspose.drawing/region) クラスのインスタンスを初期化します。 |
| [Region(GraphicsPath path)](#Region-com.aspose.drawing.drawing2d.GraphicsPath-) | 指定された [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) を使用して新しい [Region](../../com.aspose.drawing/region) クラスのインスタンスを初期化します。 |
| [Region(RegionData rgnData)](#Region-com.aspose.drawing.drawing2d.RegionData-) | 指定されたデータから新しい [Region](../../com.aspose.drawing/region) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [dispose()](#dispose--) | この [Region](../../com.aspose.drawing/region) が使用するすべてのリソースを解放します。 |
| [equals(Region region, Graphics g)](#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-) | 指定された描画サーフェス上で、指定された [Region](../../com.aspose.drawing/region) がこの [Region](../../com.aspose.drawing/region) と同一かどうかをテストします。 |
| [deepClone()](#deepClone--) | この [Region](../../com.aspose.drawing/region) の正確なコピーを作成します。 |
| [makeInfinite()](#makeInfinite--) | この [Region](../../com.aspose.drawing/region) オブジェクトを無限の内部に初期化します。 |
| [makeEmpty()](#makeEmpty--) | この [Region](../../com.aspose.drawing/region) を空の内部に初期化します。 |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | この [Region](../../com.aspose.drawing/region) を、指定された [RectangleF](../../com.aspose.drawing/rectanglef) 構造体との交差に更新します。 |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | この [Region](../../com.aspose.drawing/region) を、指定された [Rectangle](../../com.aspose.drawing/rectangle) 構造体との交差に更新します。 |
| [intersect(GraphicsPath path)](#intersect-com.aspose.drawing.drawing2d.GraphicsPath-) | この [Region](../../com.aspose.drawing/region) を、指定された [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) との交差に更新します。 |
| [intersect(Region region)](#intersect-com.aspose.drawing.Region-) | この [Region](../../com.aspose.drawing/region) を、指定された [Region](../../com.aspose.drawing/region) との交差に更新します。 |
| [union(RectangleF rect)](#union-com.aspose.drawing.RectangleF-) | この [Region](../../com.aspose.drawing/region) を、指定された [RectangleF](../../com.aspose.drawing/rectanglef) 構造体との合成に更新します。 |
| [union(Rectangle rect)](#union-com.aspose.drawing.Rectangle-) | この [Region](../../com.aspose.drawing/region) を、指定された [Rectangle](../../com.aspose.drawing/rectangle) 構造体との合成に更新します。 |
| [union(GraphicsPath path)](#union-com.aspose.drawing.drawing2d.GraphicsPath-) | この [Region](../../com.aspose.drawing/region) を、指定された [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) との合成に更新します。 |
| [union(Region region)](#union-com.aspose.drawing.Region-) | この [Region](../../com.aspose.drawing/region) を、指定された [Region](../../com.aspose.drawing/region) との合成に更新します。 |
| [getRegionData()](#getRegionData--) | この [Region](../../com.aspose.drawing/region) を記述する情報を表す [RegionData](../../com.aspose.drawing.drawing2d/regiondata) を返します。 |
| [xor(RectangleF rect)](#xor-com.aspose.drawing.RectangleF-) | この [Region](../../com.aspose.drawing/region) を、指定された [RectangleF](../../com.aspose.drawing/rectanglef) 構造体との交差を除いた合成に更新します。 |
| [xor(Rectangle rect)](#xor-com.aspose.drawing.Rectangle-) | この [Region](../../com.aspose.drawing/region) を、指定された [Rectangle](../../com.aspose.drawing/rectangle) 構造体との交差を除いた合成に更新します。 |
| [xor(GraphicsPath path)](#xor-com.aspose.drawing.drawing2d.GraphicsPath-) | この [Region](../../com.aspose.drawing/region) を、指定された [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) との交差を除いた合成に更新します。 |
| [xor(Region region)](#xor-com.aspose.drawing.Region-) | この [Region](../../com.aspose.drawing/region) を、指定された [Region](../../com.aspose.drawing/region) との交差を除いた合成に更新します。 |
| [exclude(RectangleF rect)](#exclude-com.aspose.drawing.RectangleF-) | この [Region](../../com.aspose.drawing/region) の内部で、指定された [RectangleF](../../com.aspose.drawing/rectanglef) 構造体と交差しない部分のみを保持するように更新します。 |
| [exclude(Rectangle rect)](#exclude-com.aspose.drawing.Rectangle-) | この [Region](../../com.aspose.drawing/region) の内部で、指定された [Rectangle](../../com.aspose.drawing/rectangle) 構造体と交差しない部分のみを保持するように更新します。 |
| [exclude(GraphicsPath path)](#exclude-com.aspose.drawing.drawing2d.GraphicsPath-) | この [Region](../../com.aspose.drawing/region) の内部で、指定された [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) と交差しない部分のみを保持するように更新します。 |
| [exclude(Region region)](#exclude-com.aspose.drawing.Region-) | この [Region](../../com.aspose.drawing/region) の内部で、指定された [Region](../../com.aspose.drawing/region) と交差しない部分のみを保持するように更新します。 |
| [complement(RectangleF rect)](#complement-com.aspose.drawing.RectangleF-) | 指定された [RectangleF](../../com.aspose.drawing/rectanglef) 構造体で、この [Region](../../com.aspose.drawing/region) と交差しない部分を保持するようにこの [Region](../../com.aspose.drawing/region) を更新します。 |
| [complement(Rectangle rect)](#complement-com.aspose.drawing.Rectangle-) | 指定された [Rectangle](../../com.aspose.drawing/rectangle) 構造体で、この [Region](../../com.aspose.drawing/region) と交差しない部分を保持するようにこの [Region](../../com.aspose.drawing/region) を更新します。 |
| [complement(GraphicsPath path)](#complement-com.aspose.drawing.drawing2d.GraphicsPath-) | 指定された [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) で、この [Region](../../com.aspose.drawing/region) と交差しない部分を保持するようにこの [Region](../../com.aspose.drawing/region) を更新します。 |
| [complement(Region region)](#complement-com.aspose.drawing.Region-) | この[Region](../../com.aspose.drawing/region) を、指定された[Region](../../com.aspose.drawing/region) と交差しない部分を含むように更新します。 |
| [translate(float dx, float dy)](#translate-float-float-) | この[Region](../../com.aspose.drawing/region) の座標を指定された量だけオフセットします。 |
| [translate(int dx, int dy)](#translate-int-int-) | この[Region](../../com.aspose.drawing/region) の座標を指定された量だけオフセットします。 |
| [transform(Matrix matrix)](#transform-com.aspose.drawing.drawing2d.Matrix-) | この[Region](../../com.aspose.drawing/region) を指定された[Matrix](../../com.aspose.drawing.drawing2d/matrix) で変換します。 |
| [getBounds(Graphics g)](#getBounds-com.aspose.drawing.Graphics-) | [Graphics](../../com.aspose.drawing/graphics) オブジェクトの描画サーフェス上でこの[Region](../../com.aspose.drawing/region) を境界とする矩形を表す[RectangleF](../../com.aspose.drawing/rectanglef) 構造体を取得します。 |
| [getRegionScans(Matrix matrix)](#getRegionScans-com.aspose.drawing.drawing2d.Matrix-) | 指定された行列変換が適用された後のこの[Region](../../com.aspose.drawing/region) を近似する[RectangleF](../../com.aspose.drawing/rectanglef) 構造体の配列を返します。 |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.drawing.Graphics-) | 指定された描画サーフェス上でこの[Region](../../com.aspose.drawing/region) の内部が空であるかどうかをテストします。 |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.drawing.Graphics-) | 指定された描画サーフェス上でこの[Region](../../com.aspose.drawing/region) の内部が無限であるかどうかをテストします。 |
| [isVisible(float x, float y)](#isVisible-float-float-) | 指定された点がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。 |
| [isVisible(PointF point)](#isVisible-com.aspose.drawing.PointF-) | 指定された[PointF](../../com.aspose.drawing/pointf) 構造体がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。 |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.drawing.Graphics-) | 指定された[Graphics](../../com.aspose.drawing/graphics) を使用して描画した場合に、指定された点がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。 |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-) | 指定された[Graphics](../../com.aspose.drawing/graphics) を使用して描画した場合に、指定された[PointF](../../com.aspose.drawing/pointf) 構造体がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。 |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | 指定された矩形の任意の部分がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。 |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.drawing.RectangleF-) | 指定された[RectangleF](../../com.aspose.drawing/rectanglef) 構造体の任意の部分がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。 |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.drawing.Graphics-) | 指定された[Graphics](../../com.aspose.drawing/graphics) を使用して描画した場合に、指定された矩形の任意の部分がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。 |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-) | 指定された[Graphics](../../com.aspose.drawing/graphics) を使用して描画した場合に、指定された[RectangleF](../../com.aspose.drawing/rectanglef) 構造体の任意の部分がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。 |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.drawing.Graphics-) | 指定された[Graphics](../../com.aspose.drawing/graphics) オブジェクトを使用して描画した場合に、指定された点がこの[Region](../../com.aspose.drawing/region) オブジェクト内に含まれるかどうかをテストします。 |
| [isVisible(Point point)](#isVisible-com.aspose.drawing.Point-) | 指定された[Point](../../com.aspose.drawing/point) 構造体がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。 |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-) | 指定された[Graphics](../../com.aspose.drawing/graphics) を使用して描画した場合に、指定された[Point](../../com.aspose.drawing/point) 構造体がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。 |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | 指定された矩形の任意の部分がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。 |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.drawing.Rectangle-) | 指定された[Rectangle](../../com.aspose.drawing/rectangle) 構造体の任意の部分がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。 |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.drawing.Graphics-) | 指定された[Graphics](../../com.aspose.drawing/graphics) を使用して描画した場合に、指定された矩形の任意の部分がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。 |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-) | 指定された[Graphics](../../com.aspose.drawing/graphics) を使用して描画した場合に、指定された[Rectangle](../../com.aspose.drawing/rectangle) 構造体の任意の部分がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。 |
### Region() {#Region--}
```
public Region()
```


新しい [Region](../../com.aspose.drawing/region) クラスのインスタンスを初期化します。

### Region(RectangleF rect) {#Region-com.aspose.drawing.RectangleF-}
```
public Region(RectangleF rect)
```


指定された [RectangleF](../../com.aspose.drawing/rectanglef) 構造体から新しい [Region](../../com.aspose.drawing/region) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | 新しい[Region](../../com.aspose.drawing/region) の内部を定義する[RectangleF](../../com.aspose.drawing/rectanglef) 構造体です。 |

### Region(Rectangle rect) {#Region-com.aspose.drawing.Rectangle-}
```
public Region(Rectangle rect)
```


指定された [Rectangle](../../com.aspose.drawing/rectangle) 構造体から新しい [Region](../../com.aspose.drawing/region) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | 新しい[Region](../../com.aspose.drawing/region) の内部を定義する[Rectangle](../../com.aspose.drawing/rectangle) 構造体です。 |

### Region(GraphicsPath path) {#Region-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public Region(GraphicsPath path)
```


指定された [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) を使用して新しい [Region](../../com.aspose.drawing/region) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | 新しい[Region](../../com.aspose.drawing/region) を定義する[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) です。 |

### Region(RegionData rgnData) {#Region-com.aspose.drawing.drawing2d.RegionData-}
```
public Region(RegionData rgnData)
```


指定されたデータから新しい [Region](../../com.aspose.drawing/region) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rgnData | [RegionData](../../com.aspose.drawing.drawing2d/regiondata) | 新しい[Region](../../com.aspose.drawing/region) の内部を定義する[RegionData](../../com.aspose.drawing.drawing2d/regiondata) です。 |

### dispose() {#dispose--}
```
public void dispose()
```


この [Region](../../com.aspose.drawing/region) が使用するすべてのリソースを解放します。

### equals(Region region, Graphics g) {#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-}
```
public boolean equals(Region region, Graphics g)
```


指定された描画サーフェス上で、指定された [Region](../../com.aspose.drawing/region) がこの [Region](../../com.aspose.drawing/region) と同一かどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | テスト対象の[Region](../../com.aspose.drawing/region)です。 |
| g | [Graphics](../../com.aspose.drawing/graphics) | 描画面を表す[Graphics](../../com.aspose.drawing/graphics)です。 |

**Returns:**
boolean - `g` パラメータに関連付けられた変換が適用されたとき、領域の内部がこの領域の内部と同一である場合は true、そうでない場合は false。
### deepClone() {#deepClone--}
```
public Region deepClone()
```


この [Region](../../com.aspose.drawing/region) の正確なコピーを作成します。

**Returns:**
[Region](../../com.aspose.drawing/region) - The [Region](../../com.aspose.drawing/region) that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


この [Region](../../com.aspose.drawing/region) オブジェクトを無限の内部に初期化します。

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


この [Region](../../com.aspose.drawing/region) を空の内部に初期化します。

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public void intersect(RectangleF rect)
```


この [Region](../../com.aspose.drawing/region) を、指定された [RectangleF](../../com.aspose.drawing/rectanglef) 構造体との交差に更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | この[Region](../../com.aspose.drawing/region)と交差させるための[RectangleF](../../com.aspose.drawing/rectanglef)構造体です。 |

### intersect(Rectangle rect) {#intersect-com.aspose.drawing.Rectangle-}
```
public void intersect(Rectangle rect)
```


この [Region](../../com.aspose.drawing/region) を、指定された [Rectangle](../../com.aspose.drawing/rectangle) 構造体との交差に更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | この[Region](../../com.aspose.drawing/region)と交差させるための[Rectangle](../../com.aspose.drawing/rectangle)構造体です。 |

### intersect(GraphicsPath path) {#intersect-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


この [Region](../../com.aspose.drawing/region) を、指定された [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) との交差に更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | この[Region](../../com.aspose.drawing/region)と交差させるための[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)です。 |

### intersect(Region region) {#intersect-com.aspose.drawing.Region-}
```
public void intersect(Region region)
```


この [Region](../../com.aspose.drawing/region) を、指定された [Region](../../com.aspose.drawing/region) との交差に更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | この[Region](../../com.aspose.drawing/region)と交差させるための[Region](../../com.aspose.drawing/region)です。 |

### union(RectangleF rect) {#union-com.aspose.drawing.RectangleF-}
```
public void union(RectangleF rect)
```


この [Region](../../com.aspose.drawing/region) を、指定された [RectangleF](../../com.aspose.drawing/rectanglef) 構造体との合成に更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | rect | [RectangleF](../../com.aspose.drawing/rectanglef) | この[Region](../../com.aspose.drawing/region)と結合させるための[RectangleF](../../com.aspose.drawing/rectanglef)構造体です。 |

--------------------

結合は無限領域を無限のままにします。 |

### union(Rectangle rect) {#union-com.aspose.drawing.Rectangle-}
```
public void union(Rectangle rect)
```


この [Region](../../com.aspose.drawing/region) を、指定された [Rectangle](../../com.aspose.drawing/rectangle) 構造体との合成に更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | rect | [Rectangle](../../com.aspose.drawing/rectangle) | この[Region](../../com.aspose.drawing/region)と結合させるための[Rectangle](../../com.aspose.drawing/rectangle)構造体です。 |

--------------------

結合は無限領域を無限のままにします。 |

### union(GraphicsPath path) {#union-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void union(GraphicsPath path)
```


この [Region](../../com.aspose.drawing/region) を、指定された [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) との合成に更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | この[Region](../../com.aspose.drawing/region)と結合させるための[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)です。 |

--------------------

結合は無限領域を無限のままにします。 |

### union(Region region) {#union-com.aspose.drawing.Region-}
```
public void union(Region region)
```


この [Region](../../com.aspose.drawing/region) を、指定された [Region](../../com.aspose.drawing/region) との合成に更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | region | [Region](../../com.aspose.drawing/region) | この[Region](../../com.aspose.drawing/region)と結合させるための[Region](../../com.aspose.drawing/region)です。 |

--------------------

結合は無限領域を無限のままにします。 |

### getRegionData() {#getRegionData--}
```
public RegionData getRegionData()
```


この [Region](../../com.aspose.drawing/region) を記述する情報を表す [RegionData](../../com.aspose.drawing.drawing2d/regiondata) を返します。

**Returns:**
[RegionData](../../com.aspose.drawing.drawing2d/regiondata) - A [RegionData](../../com.aspose.drawing.drawing2d/regiondata) that represents the information that describes this [Region](../../com.aspose.drawing/region).
### xor(RectangleF rect) {#xor-com.aspose.drawing.RectangleF-}
```
public void xor(RectangleF rect)
```


この [Region](../../com.aspose.drawing/region) を、指定された [RectangleF](../../com.aspose.drawing/rectanglef) 構造体との交差を除いた合成に更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | この[Region](../../com.aspose.drawing/region)と `M:Region.Xor(Drawing2D.GraphicsPath)` するための[RectangleF](../../com.aspose.drawing/rectanglef)構造体です。 |

### xor(Rectangle rect) {#xor-com.aspose.drawing.Rectangle-}
```
public void xor(Rectangle rect)
```


この [Region](../../com.aspose.drawing/region) を、指定された [Rectangle](../../com.aspose.drawing/rectangle) 構造体との交差を除いた合成に更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | この[Region](../../com.aspose.drawing/region)と `M:Region.Xor(Rectangle)` するための[Rectangle](../../com.aspose.drawing/rectangle)構造体です。 |

### xor(GraphicsPath path) {#xor-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


この [Region](../../com.aspose.drawing/region) を、指定された [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) との交差を除いた合成に更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | この[Region](../../com.aspose.drawing/region)と `M:Region.Xor(GraphicsPath)` するための[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)です。 |

### xor(Region region) {#xor-com.aspose.drawing.Region-}
```
public void xor(Region region)
```


この [Region](../../com.aspose.drawing/region) を、指定された [Region](../../com.aspose.drawing/region) との交差を除いた合成に更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | この[Region](../../com.aspose.drawing/region)と `M:Region.Xor(Region)` するための[Region](../../com.aspose.drawing/region)です。 |

### exclude(RectangleF rect) {#exclude-com.aspose.drawing.RectangleF-}
```
public void exclude(RectangleF rect)
```


この [Region](../../com.aspose.drawing/region) の内部で、指定された [RectangleF](../../com.aspose.drawing/rectanglef) 構造体と交差しない部分のみを保持するように更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | この[Region](../../com.aspose.drawing/region)から除外するための[RectangleF](../../com.aspose.drawing/rectanglef)構造体です。 |

### exclude(Rectangle rect) {#exclude-com.aspose.drawing.Rectangle-}
```
public void exclude(Rectangle rect)
```


この [Region](../../com.aspose.drawing/region) の内部で、指定された [Rectangle](../../com.aspose.drawing/rectangle) 構造体と交差しない部分のみを保持するように更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | この[Region](../../com.aspose.drawing/region)から除外するための[Rectangle](../../com.aspose.drawing/rectangle)構造体です。 |

### exclude(GraphicsPath path) {#exclude-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


この [Region](../../com.aspose.drawing/region) の内部で、指定された [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) と交差しない部分のみを保持するように更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | この[Region](../../com.aspose.drawing/region)から除外するための[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)です。 |

### exclude(Region region) {#exclude-com.aspose.drawing.Region-}
```
public void exclude(Region region)
```


この [Region](../../com.aspose.drawing/region) の内部で、指定された [Region](../../com.aspose.drawing/region) と交差しない部分のみを保持するように更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | この[Region](../../com.aspose.drawing/region)から除外するための[Region](../../com.aspose.drawing/region)です。 |

### complement(RectangleF rect) {#complement-com.aspose.drawing.RectangleF-}
```
public void complement(RectangleF rect)
```


指定された [RectangleF](../../com.aspose.drawing/rectanglef) 構造体で、この [Region](../../com.aspose.drawing/region) と交差しない部分を保持するようにこの [Region](../../com.aspose.drawing/region) を更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | この[Region](../../com.aspose.drawing/region)を補完するための[RectangleF](../../com.aspose.drawing/rectanglef)構造体です。 |

### complement(Rectangle rect) {#complement-com.aspose.drawing.Rectangle-}
```
public void complement(Rectangle rect)
```


指定された [Rectangle](../../com.aspose.drawing/rectangle) 構造体で、この [Region](../../com.aspose.drawing/region) と交差しない部分を保持するようにこの [Region](../../com.aspose.drawing/region) を更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | この[Region](../../com.aspose.drawing/region)を補完するための[Rectangle](../../com.aspose.drawing/rectangle)構造体です。 |

### complement(GraphicsPath path) {#complement-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


指定された [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) で、この [Region](../../com.aspose.drawing/region) と交差しない部分を保持するようにこの [Region](../../com.aspose.drawing/region) を更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | この[Region](../../com.aspose.drawing/region)を補完するための[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)です。 |

### complement(Region region) {#complement-com.aspose.drawing.Region-}
```
public void complement(Region region)
```


この[Region](../../com.aspose.drawing/region) を、指定された[Region](../../com.aspose.drawing/region) と交差しない部分を含むように更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | この[Region](../../com.aspose.drawing/region)オブジェクトを補完するための[Region](../../com.aspose.drawing/region)オブジェクトです。 |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


この[Region](../../com.aspose.drawing/region) の座標を指定された量だけオフセットします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dx | float | この[Region](../../com.aspose.drawing/region)を水平方向にオフセットする量です。 |
| dy | float | この[Region](../../com.aspose.drawing/region)を垂直方向にオフセットする量です。 |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


この[Region](../../com.aspose.drawing/region) の座標を指定された量だけオフセットします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dx | int | この [Region](../../com.aspose.drawing/region) を水平方向にオフセットする量 |
| dy | int | この[Region](../../com.aspose.drawing/region)を垂直方向にオフセットする量です。 |

### transform(Matrix matrix) {#transform-com.aspose.drawing.drawing2d.Matrix-}
```
public void transform(Matrix matrix)
```


この[Region](../../com.aspose.drawing/region) を指定された[Matrix](../../com.aspose.drawing.drawing2d/matrix) で変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | この [Region](../../com.aspose.drawing/region) を変換するための [Matrix](../../com.aspose.drawing.drawing2d/matrix)です。 |

### getBounds(Graphics g) {#getBounds-com.aspose.drawing.Graphics-}
```
public RectangleF getBounds(Graphics g)
```


[Graphics](../../com.aspose.drawing/graphics) オブジェクトの描画サーフェス上でこの[Region](../../com.aspose.drawing/region) を境界とする矩形を表す[RectangleF](../../com.aspose.drawing/rectanglef) 構造体を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | この [Region](../../com.aspose.drawing/region) が描画される [Graphics](../../com.aspose.drawing/graphics)です。 |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A [RectangleF](../../com.aspose.drawing/rectanglef) structure that represents the bounding rectangle for this [Region](../../com.aspose.drawing/region) on the specified drawing surface.
### getRegionScans(Matrix matrix) {#getRegionScans-com.aspose.drawing.drawing2d.Matrix-}
```
public RectangleF[] getRegionScans(Matrix matrix)
```


指定された行列変換が適用された後のこの[Region](../../com.aspose.drawing/region) を近似する[RectangleF](../../com.aspose.drawing/rectanglef) 構造体の配列を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | 領域に適用する幾何変換を表す [Matrix](../../com.aspose.drawing.drawing2d/matrix)です。 |

**Returns:**
com.aspose.drawing.RectangleF[] - 指定された行列変換が適用された後、この [Region](../../com.aspose.drawing/region) を近似する [RectangleF](../../com.aspose.drawing/rectanglef) 構造体の配列です。
### isEmpty(Graphics g) {#isEmpty-com.aspose.drawing.Graphics-}
```
public boolean isEmpty(Graphics g)
```


指定された描画サーフェス上でこの[Region](../../com.aspose.drawing/region) の内部が空であるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | 描画面を表す[Graphics](../../com.aspose.drawing/graphics)です。 |

**Returns:**
boolean - `g` に関連付けられた変換が適用されたとき、この [Region](../../com.aspose.drawing/region) の内部が空である場合は true、そうでなければ false。
### isInfinite(Graphics g) {#isInfinite-com.aspose.drawing.Graphics-}
```
public boolean isInfinite(Graphics g)
```


指定された描画サーフェス上でこの[Region](../../com.aspose.drawing/region) の内部が無限であるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | 描画面を表す[Graphics](../../com.aspose.drawing/graphics)です。 |

**Returns:**
boolean - `g` に関連付けられた変換が適用されたとき、この [Region](../../com.aspose.drawing/region) の内部が無限である場合は true、そうでなければ false。
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


指定された点がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | テスト対象の点の x 座標。 |
| y | float | テスト対象ポイントの y 座標。 |

**Returns:**
boolean - 指定された点がこの [Region](../../com.aspose.drawing/region) に含まれる場合は true、そうでなければ false。
### isVisible(PointF point) {#isVisible-com.aspose.drawing.PointF-}
```
public boolean isVisible(PointF point)
```


指定された[PointF](../../com.aspose.drawing/pointf) 構造体がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | テストする [PointF](../../com.aspose.drawing/pointf) 構造体です。 |

**Returns:**
boolean - `point` がこの [Region](../../com.aspose.drawing/region) に含まれる場合は true、そうでなければ false。
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


指定された[Graphics](../../com.aspose.drawing/graphics) を使用して描画した場合に、指定された点がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | テスト対象の点の x 座標。 |
| y | float | テスト対象ポイントの y 座標。 |
| g | [Graphics](../../com.aspose.drawing/graphics) | グラフィックス コンテキストを表す [Graphics](../../com.aspose.drawing/graphics)です。 |

**Returns:**
boolean - 指定された点がこの [Region](../../com.aspose.drawing/region) に含まれる場合は true、そうでなければ false。
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


指定された[Graphics](../../com.aspose.drawing/graphics) を使用して描画した場合に、指定された[PointF](../../com.aspose.drawing/pointf) 構造体がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | テストする [PointF](../../com.aspose.drawing/pointf) 構造体です。 |
| g | [Graphics](../../com.aspose.drawing/graphics) | グラフィックス コンテキストを表す [Graphics](../../com.aspose.drawing/graphics)です。 |

**Returns:**
boolean - `point` がこの [Region](../../com.aspose.drawing/region) に含まれる場合は true、そうでなければ false。
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


指定された矩形の任意の部分がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | テスト対象の矩形の左上隅の x 座標。 |
| y | float | テスト対象の矩形の左上隅の y 座標。 |
| 幅 | float | テスト対象の矩形の幅。 |
| 高さ | float | テスト対象の矩形の高さ。 |

**Returns:**
boolean - 指定された矩形の任意の部分がこの [Region](../../com.aspose.drawing/region) オブジェクトに含まれる場合は true、そうでなければ false。
### isVisible(RectangleF rect) {#isVisible-com.aspose.drawing.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


指定された[RectangleF](../../com.aspose.drawing/rectanglef) 構造体の任意の部分がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | テスト対象の [RectangleF](../../com.aspose.drawing/rectanglef) 構造体です。 |

**Returns:**
boolean - `rect` の任意の部分がこの [Region](../../com.aspose.drawing/region) に含まれる場合は true、そうでなければ false。
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


指定された[Graphics](../../com.aspose.drawing/graphics) を使用して描画した場合に、指定された矩形の任意の部分がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | テスト対象の矩形の左上隅の x 座標。 |
| y | float | テスト対象の矩形の左上隅の y 座標。 |
| 幅 | float | テスト対象の矩形の幅。 |
| 高さ | float | テスト対象の矩形の高さ。 |
| g | [Graphics](../../com.aspose.drawing/graphics) | グラフィックス コンテキストを表す [Graphics](../../com.aspose.drawing/graphics)です。 |

**Returns:**
boolean - 指定された矩形の任意の部分がこの [Region](../../com.aspose.drawing/region) に含まれる場合は true、そうでなければ false。
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


指定された[Graphics](../../com.aspose.drawing/graphics) を使用して描画した場合に、指定された[RectangleF](../../com.aspose.drawing/rectanglef) 構造体の任意の部分がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | テスト対象の [RectangleF](../../com.aspose.drawing/rectanglef) 構造体です。 |
| g | [Graphics](../../com.aspose.drawing/graphics) | グラフィックス コンテキストを表す [Graphics](../../com.aspose.drawing/graphics)です。 |

**Returns:**
boolean - `rect` がこの [Region](../../com.aspose.drawing/region) に含まれる場合は true、そうでなければ false。
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


指定された[Graphics](../../com.aspose.drawing/graphics) オブジェクトを使用して描画した場合に、指定された点がこの[Region](../../com.aspose.drawing/region) オブジェクト内に含まれるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | テスト対象の点の x 座標。 |
| y | int | テスト対象ポイントの y 座標。 |
| g | [Graphics](../../com.aspose.drawing/graphics) | グラフィックス コンテキストを表す [Graphics](../../com.aspose.drawing/graphics)です。 |

**Returns:**
boolean - 指定された点がこの [Region](../../com.aspose.drawing/region) に含まれる場合は true、そうでなければ false。
### isVisible(Point point) {#isVisible-com.aspose.drawing.Point-}
```
public boolean isVisible(Point point)
```


指定された[Point](../../com.aspose.drawing/point) 構造体がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | テスト対象の [Point](../../com.aspose.drawing/point) 構造体です。 |

**Returns:**
boolean - `point` がこの [Region](../../com.aspose.drawing/region) に含まれる場合は true、そうでなければ false。
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


指定された[Graphics](../../com.aspose.drawing/graphics) を使用して描画した場合に、指定された[Point](../../com.aspose.drawing/point) 構造体がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | テスト対象の [Point](../../com.aspose.drawing/point) 構造体です。 |
| g | [Graphics](../../com.aspose.drawing/graphics) | グラフィックス コンテキストを表す [Graphics](../../com.aspose.drawing/graphics)です。 |

**Returns:**
boolean - `point` がこの [Region](../../com.aspose.drawing/region) に含まれる場合は true、そうでなければ false。
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


指定された矩形の任意の部分がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | テスト対象の矩形の左上隅の x 座標。 |
| y | int | テスト対象の矩形の左上隅の y 座標。 |
| 幅 | int | テスト対象の矩形の幅。 |
| 高さ | int | テスト対象の矩形の高さ。 |

**Returns:**
boolean - 指定された矩形の任意の部分がこの [Region](../../com.aspose.drawing/region) に含まれる場合は true、そうでなければ false。
### isVisible(Rectangle rect) {#isVisible-com.aspose.drawing.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


指定された[Rectangle](../../com.aspose.drawing/rectangle) 構造体の任意の部分がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | テスト対象の [Rectangle](../../com.aspose.drawing/rectangle) 構造体です。 |

**Returns:**
boolean - このメソッドは `rect` の任意の部分がこの [Region](../../com.aspose.drawing/region) に含まれる場合に true を返し、そうでなければ false を返します。
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


指定された[Graphics](../../com.aspose.drawing/graphics) を使用して描画した場合に、指定された矩形の任意の部分がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | テスト対象の矩形の左上隅の x 座標。 |
| y | int | テスト対象の矩形の左上隅の y 座標。 |
| 幅 | int | テスト対象の矩形の幅。 |
| 高さ | int | テスト対象の矩形の高さ。 |
| g | [Graphics](../../com.aspose.drawing/graphics) | グラフィックス コンテキストを表す [Graphics](../../com.aspose.drawing/graphics)です。 |

**Returns:**
boolean - 指定された矩形の任意の部分がこの [Region](../../com.aspose.drawing/region) に含まれる場合は true、そうでなければ false。
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


指定された[Graphics](../../com.aspose.drawing/graphics) を使用して描画した場合に、指定された[Rectangle](../../com.aspose.drawing/rectangle) 構造体の任意の部分がこの[Region](../../com.aspose.drawing/region) 内に含まれるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | テスト対象の [Rectangle](../../com.aspose.drawing/rectangle) 構造体です。 |
| g | [Graphics](../../com.aspose.drawing/graphics) | グラフィックス コンテキストを表す [Graphics](../../com.aspose.drawing/graphics)です。 |

**Returns:**
boolean - `rect` の任意の部分がこの [Region](../../com.aspose.drawing/region) に含まれる場合は true、そうでなければ false。
