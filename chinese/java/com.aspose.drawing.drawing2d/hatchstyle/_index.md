---
title: HatchStyle
second_title: Aspose.Drawing for Java API 参考
description: 指定可用于对象的不同图案。
type: docs
weight: 27
url: /zh/java/com.aspose.drawing.drawing2d/hatchstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HatchStyle extends System.Enum
```

指定可用于 [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 对象的不同图案。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Horizontal](#Horizontal) | 水平线图案。 |
| [Vertical](#Vertical) | 垂直线图案。 |
| [ForwardDiagonal](#ForwardDiagonal) | 左上到右下的对角线线条图案。 |
| [BackwardDiagonal](#BackwardDiagonal) | 右上到左下的对角线线条图案。 |
| [Cross](#Cross) | 指定水平线和垂直线交叉。 |
| [DiagonalCross](#DiagonalCross) | 交叉的对角线图案。 |
| [Percent05](#Percent05) | 指定 5% 的填充。 |
| [Percent10](#Percent10) | 指定 10% 的填充。 |
| [Percent20](#Percent20) | 指定 20% 的填充。 |
| [Percent25](#Percent25) | 指定 25% 的填充。 |
| [Percent30](#Percent30) | 指定 30% 的填充。 |
| [Percent40](#Percent40) | 指定 40% 的填充。 |
| [Percent50](#Percent50) | 指定 50% 的填充。 |
| [Percent60](#Percent60) | 指定 60% 的填充。 |
| [Percent70](#Percent70) | 指定 70% 的填充。 |
| [Percent75](#Percent75) | 指定 75% 的填充。 |
| [Percent80](#Percent80) | 指定 80% 的填充。 |
| [Percent90](#Percent90) | 指定 90% 的填充。 |
| [LightDownwardDiagonal](#LightDownwardDiagonal) | 指定从顶部点到底部点向右倾斜的对角线，并且间距比 `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal` 小 50%，但不进行抗锯齿处理。 |
| [LightUpwardDiagonal](#LightUpwardDiagonal) | 指定从顶部点到底部点向左倾斜的对角线，并且间距比 `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal` 小 50%，但不进行抗锯齿处理。 |
| [DarkDownwardDiagonal](#DarkDownwardDiagonal) | 指定从顶部点到底部点向右倾斜的对角线，间距比 `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal` 小 50%，且宽度是其两倍。 |
| [DarkUpwardDiagonal](#DarkUpwardDiagonal) | 指定从顶部点到底部点向左倾斜的对角线，间距比 `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal` 小 50%，宽度是其两倍，但这些线条不进行抗锯齿处理。 |
| [WideDownwardDiagonal](#WideDownwardDiagonal) | 指定从顶部点到底部点向右倾斜的对角线，间距与 `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal` 相同，宽度是其三倍，但不进行抗锯齿处理。 |
| [WideUpwardDiagonal](#WideUpwardDiagonal) | 指定从顶部点到底部点向左倾斜的对角线，间距与 `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal` 相同，宽度是其三倍，但不进行抗锯齿处理。 |
| [LightVertical](#LightVertical) | 指定垂直线，其间距比 `System.Drawing.drawing2d.HatchStyle.Vertical` 小 50%。 |
| [LightHorizontal](#LightHorizontal) | 指定水平线，其间距比 `System.Drawing.drawing2d.HatchStyle.Horizontal` 小 50%。 |
| [NarrowVertical](#NarrowVertical) | 指定垂直线，其间距比 hatch 样式 `System.Drawing.drawing2d.HatchStyle.Vertical` 小 75%（或比 `System.Drawing.drawing2d.HatchStyle.LightVertical` 小 25%）。 |
| [NarrowHorizontal](#NarrowHorizontal) | 指定水平线，其间距比 hatch 样式 `System.Drawing.drawing2d.HatchStyle.Horizontal` 缩小 75%，（或比 `System.Drawing.drawing2d.HatchStyle.LightHorizontal` 缩小 25%）。 |
| [DarkVertical](#DarkVertical) | 指定垂直线，其间距比 `System.Drawing.drawing2d.HatchStyle.Vertical` 缩小 50%，且宽度是其两倍。 |
| [DarkHorizontal](#DarkHorizontal) | 指定水平线，其间距比 `System.Drawing.drawing2d.HatchStyle.Horizontal` 缩小 50%，且宽度是 `System.Drawing.drawing2d.HatchStyle.Horizontal` 的两倍。 |
| [DashedDownwardDiagonal](#DashedDownwardDiagonal) | 指定虚线对角线，从上点向右倾斜至下点。 |
| [DashedUpwardDiagonal](#DashedUpwardDiagonal) | 指定虚线对角线，从上点向左倾斜至下点。 |
| [DashedHorizontal](#DashedHorizontal) | 指定虚线水平线。 |
| [DashedVertical](#DashedVertical) | 指定虚线垂直线。 |
| [SmallConfetti](#SmallConfetti) | 指定一种外观为彩纸屑的填充图案。 |
| [LargeConfetti](#LargeConfetti) | 指定一种外观为彩纸屑的填充图案，其组成的碎片比 `System.Drawing.drawing2d.HatchStyle.SmallConfetti` 更大。 |
| [ZigZag](#ZigZag) | 指定由锯齿组成的水平线。 |
| [Wave](#Wave) | 指定由波浪线组成的水平线。 |
| [DiagonalBrick](#DiagonalBrick) | 指定一种外观为层叠砖块的填充图案，砖块从上点向左倾斜至下点。 |
| [HorizontalBrick](#HorizontalBrick) | 指定一种外观为水平层叠砖块的填充图案。 |
| [Weave](#Weave) | 指定一种外观为编织材质的填充图案。 |
| [Plaid](#Plaid) | 指定一种外观为格子织物的填充图案。 |
| [Divot](#Divot) | 指定一种外观为凹痕的填充图案。 |
| [DottedGrid](#DottedGrid) | 指定水平线和垂直线，均由点组成，并相交。 |
| [DottedDiamond](#DottedDiamond) | 指定正向对角线和反向对角线，均由点组成，并相交。 |
| [Shingle](#Shingle) | 指定一种外观为对角层叠瓦片的填充图案，瓦片从上点向右倾斜至下点。 |
| [Trellis](#Trellis) | 指定一种外观为格子架的填充图案。 |
| [Sphere](#Sphere) | 指定一种外观为相邻球体排列的填充图案。 |
| [SmallGrid](#SmallGrid) | 指定水平线和垂直线相交，且其间距比 hatch 样式 `System.Drawing.drawing2d.HatchStyle.Cross` 缩小 50%。 |
| [SmallCheckerBoard](#SmallCheckerBoard) | 指定一种外观为棋盘格的填充图案。 |
| [LargeCheckerBoard](#LargeCheckerBoard) | 指定一种外观为棋盘格的填充图案，其方格大小是 `System.Drawing.drawing2d.HatchStyle.SmallCheckerBoard` 的两倍。 |
| [OutlinedDiamond](#OutlinedDiamond) | 指定正向对角线和反向对角线相交，但未进行抗锯齿处理。 |
| [SolidDiamond](#SolidDiamond) | 指定一种外观为对角放置棋盘格的填充图案。 |
| [LargeGrid](#LargeGrid) | 指定填充样式 `System.Drawing.drawing2d.HatchStyle.Cross`。 |
| [Min](#Min) | 指定填充样式 `System.Drawing.drawing2d.HatchStyle.Horizontal`。 |
| [Max](#Max) | 指定填充样式 `System.Drawing.drawing2d.HatchStyle.SolidDiamond`。 |
### Horizontal {#Horizontal}
```
public static final int Horizontal
```


水平线图案。

### Vertical {#Vertical}
```
public static final int Vertical
```


垂直线图案。

### ForwardDiagonal {#ForwardDiagonal}
```
public static final int ForwardDiagonal
```


左上到右下的对角线线条图案。

### BackwardDiagonal {#BackwardDiagonal}
```
public static final int BackwardDiagonal
```


右上到左下的对角线线条图案。

### Cross {#Cross}
```
public static final int Cross
```


指定水平线和垂直线交叉。

### DiagonalCross {#DiagonalCross}
```
public static final int DiagonalCross
```


交叉的对角线图案。

### Percent05 {#Percent05}
```
public static final int Percent05
```


指定 5% 的填充。前景色与背景色的比例为 5:100。

### Percent10 {#Percent10}
```
public static final int Percent10
```


指定 10% 的填充。前景色与背景色的比例为 10:100。

### Percent20 {#Percent20}
```
public static final int Percent20
```


指定 20% 的填充。前景色与背景色的比例为 20:100。

### Percent25 {#Percent25}
```
public static final int Percent25
```


指定 25% 的填充。前景色与背景色的比例为 25:100。

### Percent30 {#Percent30}
```
public static final int Percent30
```


指定 30% 的填充。前景色与背景色的比例为 30:100。

### Percent40 {#Percent40}
```
public static final int Percent40
```


指定 40% 的填充。前景色与背景色的比例为 40:100。

### Percent50 {#Percent50}
```
public static final int Percent50
```


指定 50% 的填充。前景色与背景色的比例为 50:100。

### Percent60 {#Percent60}
```
public static final int Percent60
```


指定 60% 的填充。前景色与背景色的比例为 60:100。

### Percent70 {#Percent70}
```
public static final int Percent70
```


指定 70% 的填充。前景色与背景色的比例为 70:100。

### Percent75 {#Percent75}
```
public static final int Percent75
```


指定 75% 的填充。前景色与背景色的比例为 75:100。

### Percent80 {#Percent80}
```
public static final int Percent80
```


指定 80% 的填充。前景色与背景色的比例为 80:100。

### Percent90 {#Percent90}
```
public static final int Percent90
```


指定 90% 的填充。前景色与背景色的比例为 90:100。

### LightDownwardDiagonal {#LightDownwardDiagonal}
```
public static final int LightDownwardDiagonal
```


指定从顶部点到底部点向右倾斜的对角线，并且间距比 `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal` 小 50%，但不进行抗锯齿处理。

### LightUpwardDiagonal {#LightUpwardDiagonal}
```
public static final int LightUpwardDiagonal
```


指定从顶部点到底部点向左倾斜的对角线，并且间距比 `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal` 小 50%，但不进行抗锯齿处理。

### DarkDownwardDiagonal {#DarkDownwardDiagonal}
```
public static final int DarkDownwardDiagonal
```


指定从上点到下点向右倾斜的对角线，其间距比 `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal` 小 50%，且宽度为其两倍。此填充图案未进行抗锯齿处理。

### DarkUpwardDiagonal {#DarkUpwardDiagonal}
```
public static final int DarkUpwardDiagonal
```


指定从顶部点到底部点向左倾斜的对角线，间距比 `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal` 小 50%，宽度是其两倍，但这些线条不进行抗锯齿处理。

### WideDownwardDiagonal {#WideDownwardDiagonal}
```
public static final int WideDownwardDiagonal
```


指定从顶部点到底部点向右倾斜的对角线，间距与 `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal` 相同，宽度是其三倍，但不进行抗锯齿处理。

### WideUpwardDiagonal {#WideUpwardDiagonal}
```
public static final int WideUpwardDiagonal
```


指定从顶部点到底部点向左倾斜的对角线，间距与 `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal` 相同，宽度是其三倍，但不进行抗锯齿处理。

### LightVertical {#LightVertical}
```
public static final int LightVertical
```


指定垂直线，其间距比 `System.Drawing.drawing2d.HatchStyle.Vertical` 小 50%。

### LightHorizontal {#LightHorizontal}
```
public static final int LightHorizontal
```


指定水平线，其间距比 `System.Drawing.drawing2d.HatchStyle.Horizontal` 小 50%。

### NarrowVertical {#NarrowVertical}
```
public static final int NarrowVertical
```


指定垂直线，其间距比 hatch 样式 `System.Drawing.drawing2d.HatchStyle.Vertical` 小 75%（或比 `System.Drawing.drawing2d.HatchStyle.LightVertical` 小 25%）。

### NarrowHorizontal {#NarrowHorizontal}
```
public static final int NarrowHorizontal
```


指定水平线，其间距比 hatch 样式 `System.Drawing.drawing2d.HatchStyle.Horizontal` 缩小 75%，（或比 `System.Drawing.drawing2d.HatchStyle.LightHorizontal` 缩小 25%）。

### DarkVertical {#DarkVertical}
```
public static final int DarkVertical
```


指定垂直线，其间距比 `System.Drawing.drawing2d.HatchStyle.Vertical` 缩小 50%，且宽度是其两倍。

### DarkHorizontal {#DarkHorizontal}
```
public static final int DarkHorizontal
```


指定水平线，其间距比 `System.Drawing.drawing2d.HatchStyle.Horizontal` 缩小 50%，且宽度是 `System.Drawing.drawing2d.HatchStyle.Horizontal` 的两倍。

### DashedDownwardDiagonal {#DashedDownwardDiagonal}
```
public static final int DashedDownwardDiagonal
```


指定虚线对角线，从上点向右倾斜至下点。

### DashedUpwardDiagonal {#DashedUpwardDiagonal}
```
public static final int DashedUpwardDiagonal
```


指定虚线对角线，从上点向左倾斜至下点。

### DashedHorizontal {#DashedHorizontal}
```
public static final int DashedHorizontal
```


指定虚线水平线。

### DashedVertical {#DashedVertical}
```
public static final int DashedVertical
```


指定虚线垂直线。

### SmallConfetti {#SmallConfetti}
```
public static final int SmallConfetti
```


指定一种外观为彩纸屑的填充图案。

### LargeConfetti {#LargeConfetti}
```
public static final int LargeConfetti
```


指定一种外观为彩纸屑的填充图案，其组成的碎片比 `System.Drawing.drawing2d.HatchStyle.SmallConfetti` 更大。

### ZigZag {#ZigZag}
```
public static final int ZigZag
```


指定由锯齿组成的水平线。

### Wave {#Wave}
```
public static final int Wave
```


指定由波浪线组成的水平线。

### DiagonalBrick {#DiagonalBrick}
```
public static final int DiagonalBrick
```


指定一种外观为层叠砖块的填充图案，砖块从上点向左倾斜至下点。

### HorizontalBrick {#HorizontalBrick}
```
public static final int HorizontalBrick
```


指定一种外观为水平层叠砖块的填充图案。

### Weave {#Weave}
```
public static final int Weave
```


指定一种外观为编织材质的填充图案。

### Plaid {#Plaid}
```
public static final int Plaid
```


指定一种外观为格子织物的填充图案。

### Divot {#Divot}
```
public static final int Divot
```


指定一种外观为凹痕的填充图案。

### DottedGrid {#DottedGrid}
```
public static final int DottedGrid
```


指定水平线和垂直线，均由点组成，并相交。

### DottedDiamond {#DottedDiamond}
```
public static final int DottedDiamond
```


指定正向对角线和反向对角线，均由点组成，并相交。

### Shingle {#Shingle}
```
public static final int Shingle
```


指定一种外观为对角层叠瓦片的填充图案，瓦片从上点向右倾斜至下点。

### Trellis {#Trellis}
```
public static final int Trellis
```


指定一种外观为格子架的填充图案。

### Sphere {#Sphere}
```
public static final int Sphere
```


指定一种外观为相邻球体排列的填充图案。

### SmallGrid {#SmallGrid}
```
public static final int SmallGrid
```


指定水平线和垂直线相交，且其间距比 hatch 样式 `System.Drawing.drawing2d.HatchStyle.Cross` 缩小 50%。

### SmallCheckerBoard {#SmallCheckerBoard}
```
public static final int SmallCheckerBoard
```


指定一种外观为棋盘格的填充图案。

### LargeCheckerBoard {#LargeCheckerBoard}
```
public static final int LargeCheckerBoard
```


指定一种外观为棋盘格的填充图案，其方格大小是 `System.Drawing.drawing2d.HatchStyle.SmallCheckerBoard` 的两倍。

### OutlinedDiamond {#OutlinedDiamond}
```
public static final int OutlinedDiamond
```


指定正向对角线和反向对角线相交，但未进行抗锯齿处理。

### SolidDiamond {#SolidDiamond}
```
public static final int SolidDiamond
```


指定一种外观为对角放置棋盘格的填充图案。

### LargeGrid {#LargeGrid}
```
public static final int LargeGrid
```


指定填充样式 `System.Drawing.drawing2d.HatchStyle.Cross`。

### Min {#Min}
```
public static final int Min
```


指定填充样式 `System.Drawing.drawing2d.HatchStyle.Horizontal`。

### Max {#Max}
```
public static final int Max
```


指定填充样式 `System.Drawing.drawing2d.HatchStyle.SolidDiamond`。

