---
title: LineJoin
second_title: Aspose.Drawing for Java API リファレンス
description: GraphicsPath オブジェクトに含まれる図形サブパス内の連続する直線または曲線セグメントをどのように結合するかを指定します。
type: docs
weight: 30
url: /ja/java/com.aspose.drawing.drawing2d/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LineJoin extends System.Enum
```

GraphicsPath オブジェクトに含まれる図形（サブパス）内の連続する線分または曲線セグメントをどのように結合するかを指定します。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [Miter](#Miter) | マイター結合を指定します。 |
| [Bevel](#Bevel) | ベベル結合を指定します。 |
| [Round](#Round) | 円形結合を指定します。 |
| [MiterClipped](#MiterClipped) | マイター結合を指定します。 |
### Miter {#Miter}
```
public static final int Miter
```


マイター結合を指定します。これは、マイターの長さがマイター制限を超えるかどうかに応じて、鋭い角または切り取られた角を生成します。

--------------------

現在、マイター結合は実際には MiterClipped として機能します。

### Bevel {#Bevel}
```
public static final int Bevel
```


ベベル結合を指定します。これにより対角線の角が生成されます。

### Round {#Round}
```
public static final int Round
```


円形結合を指定します。これにより線間に滑らかな円弧が生成されます。

### MiterClipped {#MiterClipped}
```
public static final int MiterClipped
```


マイター結合を指定します。これは、マイターの長さがマイター制限を超えるかどうかに応じて、鋭い角またはベベル角を生成します。

