---
title: HatchStyle
second_title: Aspose.Drawing for Java API リファレンス
description: 利用可能なさまざまなパターンをオブジェクトに指定します。
type: docs
weight: 27
url: /ja/java/com.aspose.drawing.drawing2d/hatchstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HatchStyle extends System.Enum
```

利用可能なさまざまなパターンを [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) オブジェクトに指定します。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [Horizontal](#Horizontal) | 水平線のパターンです。 |
| [Vertical](#Vertical) | 垂直線のパターンです。 |
| [ForwardDiagonal](#ForwardDiagonal) | 左上から右下へ対角線上に配置された線のパターンです。 |
| [BackwardDiagonal](#BackwardDiagonal) | 右上から左下へ対角線上に配置された線のパターンです。 |
| [Cross](#Cross) | 水平線と垂直線が交差することを指定します。 |
| [DiagonalCross](#DiagonalCross) | 交差する対角線のパターンです。 |
| [Percent05](#Percent05) | 5％のハッチを指定します。 |
| [Percent10](#Percent10) | 10％のハッチを指定します。 |
| [Percent20](#Percent20) | 20％のハッチを指定します。 |
| [Percent25](#Percent25) | 25％のハッチを指定します。 |
| [Percent30](#Percent30) | 30％のハッチを指定します。 |
| [Percent40](#Percent40) | 40％のハッチを指定します。 |
| [Percent50](#Percent50) | 50％のハッチを指定します。 |
| [Percent60](#Percent60) | 60％のハッチを指定します。 |
| [Percent70](#Percent70) | 70％のハッチを指定します。 |
| [Percent75](#Percent75) | 75％のハッチを指定します。 |
| [Percent80](#Percent80) | 80％のハッチを指定します。 |
| [Percent90](#Percent90) | 90％のハッチを指定します。 |
| [LightDownwardDiagonal](#LightDownwardDiagonal) | 上部の点から下部の点へ右方向に傾く対角線を指定し、`System.Drawing.drawing2d.HatchStyle.ForwardDiagonal` より 50％ 間隔が狭く配置しますが、アンチエイリアスは適用されません。 |
| [LightUpwardDiagonal](#LightUpwardDiagonal) | 上部の点から下部の点へ左方向に傾く対角線を指定し、`System.Drawing.drawing2d.HatchStyle.BackwardDiagonal` より 50％ 間隔が狭く配置しますが、アンチエイリアスは適用されません。 |
| [DarkDownwardDiagonal](#DarkDownwardDiagonal) | 上部の点から下部の点へ右方向に傾く対角線を指定し、`System.Drawing.drawing2d.HatchStyle.ForwardDiagonal` より 50％ 間隔が狭く、幅が 2 倍です。 |
| [DarkUpwardDiagonal](#DarkUpwardDiagonal) | 上部の点から下部の点へ左方向に傾く対角線を指定し、`System.Drawing.drawing2d.HatchStyle.BackwardDiagonal` より 50％ 間隔が狭く、幅が 2 倍ですが、アンチエイリアスは適用されません。 |
| [WideDownwardDiagonal](#WideDownwardDiagonal) | 上部の点から下部の点へ右方向に傾く対角線を指定し、ハッチスタイル `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal` と同じ間隔で、幅が 3 倍ですが、アンチエイリアスは適用されません。 |
| [WideUpwardDiagonal](#WideUpwardDiagonal) | 上部の点から下部の点へ左方向に傾く対角線を指定し、ハッチスタイル `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal` と同じ間隔で、幅が 3 倍ですが、アンチエイリアスは適用されません。 |
| [LightVertical](#LightVertical) | `System.Drawing.drawing2d.HatchStyle.Vertical` より 50％ 間隔が狭い垂直線を指定します。 |
| [LightHorizontal](#LightHorizontal) | `System.Drawing.drawing2d.HatchStyle.Horizontal` より 50％ 間隔が狭い水平線を指定します。 |
| [NarrowVertical](#NarrowVertical) | `System.Drawing.drawing2d.HatchStyle.Vertical` より 75％ 間隔が狭い（または `System.Drawing.drawing2d.HatchStyle.LightVertical` より 25％ 間隔が狭い）垂直線を指定します。 |
| [NarrowHorizontal](#NarrowHorizontal) | ハッチスタイル `System.Drawing.drawing2d.HatchStyle.Horizontal` より 75% 間隔が狭い水平線を指定します（または `System.Drawing.drawing2d.HatchStyle.LightHorizontal` より 25% 間隔が狭い）。 |
| [DarkVertical](#DarkVertical) | ハッチスタイル `System.Drawing.drawing2d.HatchStyle.Vertical` より 50% 間隔が狭く、幅がその 2 倍の垂直線を指定します。 |
| [DarkHorizontal](#DarkHorizontal) | ハッチスタイル `System.Drawing.drawing2d.HatchStyle.Horizontal` より 50% 間隔が狭く、幅が `System.Drawing.drawing2d.HatchStyle.Horizontal` の 2 倍の水平線を指定します。 |
| [DashedDownwardDiagonal](#DashedDownwardDiagonal) | 上部から下部へ右方向に傾く破線の対角線を指定します。 |
| [DashedUpwardDiagonal](#DashedUpwardDiagonal) | 上部から下部へ左方向に傾く破線の対角線を指定します。 |
| [DashedHorizontal](#DashedHorizontal) | 破線の水平線を指定します。 |
| [DashedVertical](#DashedVertical) | 破線の垂直線を指定します。 |
| [SmallConfetti](#SmallConfetti) | 紙吹雪のような外観を持つハッチを指定します。 |
| [LargeConfetti](#LargeConfetti) | 紙吹雪のような外観を持ち、`System.Drawing.drawing2d.HatchStyle.SmallConfetti` より大きなピースで構成されたハッチを指定します。 |
| [ZigZag](#ZigZag) | ジグザグで構成された水平線を指定します。 |
| [Wave](#Wave) | チルダで構成された水平線を指定します。 |
| [DiagonalBrick](#DiagonalBrick) | 上部から下部へ左方向に傾く層状のレンガのような外観を持つハッチを指定します。 |
| [HorizontalBrick](#HorizontalBrick) | 水平に層状のレンガのような外観を持つハッチを指定します。 |
| [Weave](#Weave) | 織物のような外観を持つハッチを指定します。 |
| [Plaid](#Plaid) | チェック柄のような外観を持つハッチを指定します。 |
| [Divot](#Divot) | 凹みのような外観を持つハッチを指定します。 |
| [DottedGrid](#DottedGrid) | 点で構成された水平線と垂直線が交差するハッチを指定します。 |
| [DottedDiamond](#DottedDiamond) | 点で構成された前方対角線と後方対角線が交差するハッチを指定します。 |
| [Shingle](#Shingle) | 上部から下部へ右方向に傾く対角に層状のシングル（屋根瓦）のような外観を持つハッチを指定します。 |
| [Trellis](#Trellis) | 格子のような外観を持つハッチを指定します。 |
| [Sphere](#Sphere) | 隣接して配置された球体のような外観を持つハッチを指定します。 |
| [SmallGrid](#SmallGrid) | ハッチスタイル `System.Drawing.drawing2d.HatchStyle.Cross` より 50% 間隔が狭く交差する水平線と垂直線を指定します。 |
| [SmallCheckerBoard](#SmallCheckerBoard) | チェッカーボードのような外観を持つハッチを指定します。 |
| [LargeCheckerBoard](#LargeCheckerBoard) | `System.Drawing.drawing2d.HatchStyle.SmallCheckerBoard` の 2 倍サイズの正方形を持つチェッカーボードのような外観を持つハッチを指定します。 |
| [OutlinedDiamond](#OutlinedDiamond) | 交差するがアンチエイリアスされていない前方対角線と後方対角線を指定します。 |
| [SolidDiamond](#SolidDiamond) | 対角線上に配置されたチェッカーボードの外観を持つハッチを指定します。 |
| [LargeGrid](#LargeGrid) | `System.Drawing.drawing2d.HatchStyle.Cross` ハッチスタイルを指定します。 |
| [Min](#Min) | `System.Drawing.drawing2d.HatchStyle.Horizontal` ハッチスタイルを指定します。 |
| [Max](#Max) | `System.Drawing.drawing2d.HatchStyle.SolidDiamond` ハッチスタイルを指定します。 |
### Horizontal {#Horizontal}
```
public static final int Horizontal
```


水平線のパターンです。

### Vertical {#Vertical}
```
public static final int Vertical
```


垂直線のパターンです。

### ForwardDiagonal {#ForwardDiagonal}
```
public static final int ForwardDiagonal
```


左上から右下へ対角線上に配置された線のパターンです。

### BackwardDiagonal {#BackwardDiagonal}
```
public static final int BackwardDiagonal
```


右上から左下へ対角線上に配置された線のパターンです。

### Cross {#Cross}
```
public static final int Cross
```


水平線と垂直線が交差することを指定します。

### DiagonalCross {#DiagonalCross}
```
public static final int DiagonalCross
```


交差する対角線のパターンです。

### Percent05 {#Percent05}
```
public static final int Percent05
```


5% のハッチを指定します。前景色と背景色の比率は 5:100 です。

### Percent10 {#Percent10}
```
public static final int Percent10
```


10% のハッチを指定します。前景色と背景色の比率は 10:100 です。

### Percent20 {#Percent20}
```
public static final int Percent20
```


20% のハッチを指定します。前景色と背景色の比率は 20:100 です。

### Percent25 {#Percent25}
```
public static final int Percent25
```


25% のハッチを指定します。前景色と背景色の比率は 25:100 です。

### Percent30 {#Percent30}
```
public static final int Percent30
```


30% のハッチを指定します。前景色と背景色の比率は 30:100 です。

### Percent40 {#Percent40}
```
public static final int Percent40
```


40% のハッチを指定します。前景色と背景色の比率は 40:100 です。

### Percent50 {#Percent50}
```
public static final int Percent50
```


50% のハッチを指定します。前景色と背景色の比率は 50:100 です。

### Percent60 {#Percent60}
```
public static final int Percent60
```


60% のハッチを指定します。前景色と背景色の比率は 60:100 です。

### Percent70 {#Percent70}
```
public static final int Percent70
```


70% のハッチを指定します。前景色と背景色の比率は 70:100 です。

### Percent75 {#Percent75}
```
public static final int Percent75
```


75% のハッチを指定します。前景色と背景色の比率は 75:100 です。

### Percent80 {#Percent80}
```
public static final int Percent80
```


80% のハッチを指定します。前景色と背景色の比率は 80:100 です。

### Percent90 {#Percent90}
```
public static final int Percent90
```


90% のハッチを指定します。前景色と背景色の比率は 90:100 です。

### LightDownwardDiagonal {#LightDownwardDiagonal}
```
public static final int LightDownwardDiagonal
```


上部の点から下部の点へ右方向に傾く対角線を指定し、`System.Drawing.drawing2d.HatchStyle.ForwardDiagonal` より 50％ 間隔が狭く配置しますが、アンチエイリアスは適用されません。

### LightUpwardDiagonal {#LightUpwardDiagonal}
```
public static final int LightUpwardDiagonal
```


上部の点から下部の点へ左方向に傾く対角線を指定し、`System.Drawing.drawing2d.HatchStyle.BackwardDiagonal` より 50％ 間隔が狭く配置しますが、アンチエイリアスは適用されません。

### DarkDownwardDiagonal {#DarkDownwardDiagonal}
```
public static final int DarkDownwardDiagonal
```


上部の点から下部の点へ右方向に傾く対角線を指定します。間隔は `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal` の 50% だけ狭く、幅はその 2 倍です。このハッチパターンはアンチエイリアスされていません。

### DarkUpwardDiagonal {#DarkUpwardDiagonal}
```
public static final int DarkUpwardDiagonal
```


上部の点から下部の点へ左方向に傾く対角線を指定し、`System.Drawing.drawing2d.HatchStyle.BackwardDiagonal` より 50％ 間隔が狭く、幅が 2 倍ですが、アンチエイリアスは適用されません。

### WideDownwardDiagonal {#WideDownwardDiagonal}
```
public static final int WideDownwardDiagonal
```


上部の点から下部の点へ右方向に傾く対角線を指定し、ハッチスタイル `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal` と同じ間隔で、幅が 3 倍ですが、アンチエイリアスは適用されません。

### WideUpwardDiagonal {#WideUpwardDiagonal}
```
public static final int WideUpwardDiagonal
```


上部の点から下部の点へ左方向に傾く対角線を指定し、ハッチスタイル `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal` と同じ間隔で、幅が 3 倍ですが、アンチエイリアスは適用されません。

### LightVertical {#LightVertical}
```
public static final int LightVertical
```


`System.Drawing.drawing2d.HatchStyle.Vertical` より 50％ 間隔が狭い垂直線を指定します。

### LightHorizontal {#LightHorizontal}
```
public static final int LightHorizontal
```


`System.Drawing.drawing2d.HatchStyle.Horizontal` より 50％ 間隔が狭い水平線を指定します。

### NarrowVertical {#NarrowVertical}
```
public static final int NarrowVertical
```


`System.Drawing.drawing2d.HatchStyle.Vertical` より 75％ 間隔が狭い（または `System.Drawing.drawing2d.HatchStyle.LightVertical` より 25％ 間隔が狭い）垂直線を指定します。

### NarrowHorizontal {#NarrowHorizontal}
```
public static final int NarrowHorizontal
```


ハッチスタイル `System.Drawing.drawing2d.HatchStyle.Horizontal` より 75% 間隔が狭い水平線を指定します（または `System.Drawing.drawing2d.HatchStyle.LightHorizontal` より 25% 間隔が狭い）。

### DarkVertical {#DarkVertical}
```
public static final int DarkVertical
```


ハッチスタイル `System.Drawing.drawing2d.HatchStyle.Vertical` より 50% 間隔が狭く、幅がその 2 倍の垂直線を指定します。

### DarkHorizontal {#DarkHorizontal}
```
public static final int DarkHorizontal
```


ハッチスタイル `System.Drawing.drawing2d.HatchStyle.Horizontal` より 50% 間隔が狭く、幅が `System.Drawing.drawing2d.HatchStyle.Horizontal` の 2 倍の水平線を指定します。

### DashedDownwardDiagonal {#DashedDownwardDiagonal}
```
public static final int DashedDownwardDiagonal
```


上部から下部へ右方向に傾く破線の対角線を指定します。

### DashedUpwardDiagonal {#DashedUpwardDiagonal}
```
public static final int DashedUpwardDiagonal
```


上部から下部へ左方向に傾く破線の対角線を指定します。

### DashedHorizontal {#DashedHorizontal}
```
public static final int DashedHorizontal
```


破線の水平線を指定します。

### DashedVertical {#DashedVertical}
```
public static final int DashedVertical
```


破線の垂直線を指定します。

### SmallConfetti {#SmallConfetti}
```
public static final int SmallConfetti
```


紙吹雪のような外観を持つハッチを指定します。

### LargeConfetti {#LargeConfetti}
```
public static final int LargeConfetti
```


紙吹雪のような外観を持ち、`System.Drawing.drawing2d.HatchStyle.SmallConfetti` より大きなピースで構成されたハッチを指定します。

### ZigZag {#ZigZag}
```
public static final int ZigZag
```


ジグザグで構成された水平線を指定します。

### Wave {#Wave}
```
public static final int Wave
```


チルダで構成された水平線を指定します。

### DiagonalBrick {#DiagonalBrick}
```
public static final int DiagonalBrick
```


上部から下部へ左方向に傾く層状のレンガのような外観を持つハッチを指定します。

### HorizontalBrick {#HorizontalBrick}
```
public static final int HorizontalBrick
```


水平に層状のレンガのような外観を持つハッチを指定します。

### Weave {#Weave}
```
public static final int Weave
```


織物のような外観を持つハッチを指定します。

### Plaid {#Plaid}
```
public static final int Plaid
```


チェック柄のような外観を持つハッチを指定します。

### Divot {#Divot}
```
public static final int Divot
```


凹みのような外観を持つハッチを指定します。

### DottedGrid {#DottedGrid}
```
public static final int DottedGrid
```


点で構成された水平線と垂直線が交差するハッチを指定します。

### DottedDiamond {#DottedDiamond}
```
public static final int DottedDiamond
```


点で構成された前方対角線と後方対角線が交差するハッチを指定します。

### Shingle {#Shingle}
```
public static final int Shingle
```


上部から下部へ右方向に傾く対角に層状のシングル（屋根瓦）のような外観を持つハッチを指定します。

### Trellis {#Trellis}
```
public static final int Trellis
```


格子のような外観を持つハッチを指定します。

### Sphere {#Sphere}
```
public static final int Sphere
```


隣接して配置された球体のような外観を持つハッチを指定します。

### SmallGrid {#SmallGrid}
```
public static final int SmallGrid
```


ハッチスタイル `System.Drawing.drawing2d.HatchStyle.Cross` より 50% 間隔が狭く交差する水平線と垂直線を指定します。

### SmallCheckerBoard {#SmallCheckerBoard}
```
public static final int SmallCheckerBoard
```


チェッカーボードのような外観を持つハッチを指定します。

### LargeCheckerBoard {#LargeCheckerBoard}
```
public static final int LargeCheckerBoard
```


`System.Drawing.drawing2d.HatchStyle.SmallCheckerBoard` の 2 倍サイズの正方形を持つチェッカーボードのような外観を持つハッチを指定します。

### OutlinedDiamond {#OutlinedDiamond}
```
public static final int OutlinedDiamond
```


交差するがアンチエイリアスされていない前方対角線と後方対角線を指定します。

### SolidDiamond {#SolidDiamond}
```
public static final int SolidDiamond
```


対角線上に配置されたチェッカーボードの外観を持つハッチを指定します。

### LargeGrid {#LargeGrid}
```
public static final int LargeGrid
```


`System.Drawing.drawing2d.HatchStyle.Cross` ハッチスタイルを指定します。

### Min {#Min}
```
public static final int Min
```


`System.Drawing.drawing2d.HatchStyle.Horizontal` ハッチスタイルを指定します。

### Max {#Max}
```
public static final int Max
```


`System.Drawing.drawing2d.HatchStyle.SolidDiamond` ハッチスタイルを指定します。

