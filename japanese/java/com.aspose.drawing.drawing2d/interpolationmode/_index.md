---
title: InterpolationMode
second_title: Aspose.Drawing for Java API リファレンス
description: InterpolationMode 列挙体は、画像が拡大縮小または回転される際に使用されるアルゴリズムを指定します。
type: docs
weight: 28
url: /ja/java/com.aspose.drawing.drawing2d/interpolationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class InterpolationMode extends System.Enum
```

InterpolationMode 列挙体は、画像が拡大縮小または回転される際に使用されるアルゴリズムを指定します。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [Invalid](#Invalid) | QualityMode 列挙体の Invalid 要素に相当します。 |
| [Default](#Default) | デフォルトモードを指定します。 |
| [Low](#Low) | 低品質の補間を指定します。 |
| [High](#High) | 高品質の補間を指定します。 |
| [Bilinear](#Bilinear) | 双一次補間を指定します。 |
| [Bicubic](#Bicubic) | バイキュービック補間を指定します。 |
| [NearestNeighbor](#NearestNeighbor) | 最近傍補間を指定します。 |
| [HighQualityBilinear](#HighQualityBilinear) | 高品質の双一次補間を指定します。 |
| [HighQualityBicubic](#HighQualityBicubic) | 高品質のバイキュービック補間を指定します。 |
### Invalid {#Invalid}
```
public static final int Invalid
```


QualityMode 列挙体の Invalid 要素に相当します。

### Default {#Default}
```
public static final int Default
```


デフォルトモードを指定します。

### Low {#Low}
```
public static final int Low
```


低品質の補間を指定します。

### High {#High}
```
public static final int High
```


高品質の補間を指定します。

### Bilinear {#Bilinear}
```
public static final int Bilinear
```


双一次補間を指定します。事前フィルタリングは行われません。このモードは画像を元のサイズの 50% 未満に縮小する場合には適していません。

### Bicubic {#Bicubic}
```
public static final int Bicubic
```


バイキュービック補間を指定します。事前フィルタリングは行われません。このモードは画像を元のサイズの 25% 未満に縮小する場合には適していません。

### NearestNeighbor {#NearestNeighbor}
```
public static final int NearestNeighbor
```


最近傍補間を指定します。

### HighQualityBilinear {#HighQualityBilinear}
```
public static final int HighQualityBilinear
```


高品質の双一次補間を指定します。高品質な縮小を実現するために事前フィルタリングが実行されます。

### HighQualityBicubic {#HighQualityBicubic}
```
public static final int HighQualityBicubic
```


高品質のバイキュービック補間を指定します。高品質な縮小を実現するために事前フィルタリングが実行されます。このモードは最高品質の変換画像を生成します。

