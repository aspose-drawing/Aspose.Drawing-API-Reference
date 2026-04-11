---
title: HatchStyle
second_title: Справочник API Aspose.Drawing для Java
description: Указывает различные шаблоны, доступные для объектов.
type: docs
weight: 27
url: /ru/java/com.aspose.drawing.drawing2d/hatchstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HatchStyle extends System.Enum
```

Указывает различные шаблоны, доступные для объектов [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).
## Поля

| Поле | Описание |
| --- | --- |
| [Horizontal](#Horizontal) | Шаблон из горизонтальных линий. |
| [Vertical](#Vertical) | Шаблон из вертикальных линий. |
| [ForwardDiagonal](#ForwardDiagonal) | Шаблон линий по диагонали от верхнего левого угла к нижнему правому. |
| [BackwardDiagonal](#BackwardDiagonal) | Шаблон линий по диагонали от верхнего правого угла к нижнему левому. |
| [Cross](#Cross) | Указывает горизонтальные и вертикальные линии, которые пересекаются. |
| [DiagonalCross](#DiagonalCross) | Шаблон пересекающихся диагональных линий. |
| [Percent05](#Percent05) | Указывает штриховку 5 %. |
| [Percent10](#Percent10) | Указывает штриховку 10 %. |
| [Percent20](#Percent20) | Указывает штриховку 20 %. |
| [Percent25](#Percent25) | Указывает штриховку 25 %. |
| [Percent30](#Percent30) | Указывает штриховку 30 %. |
| [Percent40](#Percent40) | Указывает штриховку 40 %. |
| [Percent50](#Percent50) | Указывает штриховку 50 %. |
| [Percent60](#Percent60) | Указывает штриховку 60 %. |
| [Percent70](#Percent70) | Указывает штриховку 70 %. |
| [Percent75](#Percent75) | Указывает штриховку 75 %. |
| [Percent80](#Percent80) | Указывает штриховку 80 %. |
| [Percent90](#Percent90) | Указывает штриховку 90 %. |
| [LightDownwardDiagonal](#LightDownwardDiagonal) | Указывает диагональные линии, наклонённые вправо от верхних точек к нижним точкам и расположенные на 50 % ближе друг к другу, чем `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, но без сглаживания. |
| [LightUpwardDiagonal](#LightUpwardDiagonal) | Указывает диагональные линии, наклонённые влево от верхних точек к нижним точкам и расположенные на 50 % ближе друг к другу, чем `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, но они не сглажены. |
| [DarkDownwardDiagonal](#DarkDownwardDiagonal) | Указывает диагональные линии, наклонённые вправо от верхних точек к нижним точкам, расположенные на 50 % ближе друг к другу и в два раза шире, чем `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`. |
| [DarkUpwardDiagonal](#DarkUpwardDiagonal) | Указывает диагональные линии, наклонённые влево от верхних точек к нижним точкам, расположенные на 50 % ближе друг к другу, чем `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, и в два раза шире его, но линии не сглажены. |
| [WideDownwardDiagonal](#WideDownwardDiagonal) | Указывает диагональные линии, наклонённые вправо от верхних точек к нижним точкам, имеющие такое же расстояние, как штриховка `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, и в три раза шире её, но без сглаживания. |
| [WideUpwardDiagonal](#WideUpwardDiagonal) | Указывает диагональные линии, наклонённые влево от верхних точек к нижним точкам, имеющие такое же расстояние, как штриховка `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, и в три раза шире её, но без сглаживания. |
| [LightVertical](#LightVertical) | Указывает вертикальные линии, расположенные на 50 % ближе друг к другу, чем `System.Drawing.drawing2d.HatchStyle.Vertical`. |
| [LightHorizontal](#LightHorizontal) | Указывает горизонтальные линии, расположенные на 50 % ближе друг к другу, чем `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [NarrowVertical](#NarrowVertical) | Указывает вертикальные линии, расположенные на 75 % ближе друг к другу, чем штриховка `System.Drawing.drawing2d.HatchStyle.Vertical` (или на 25 % ближе, чем `System.Drawing.drawing2d.HatchStyle.LightVertical`). |
| [NarrowHorizontal](#NarrowHorizontal) | Указывает горизонтальные линии, расположенные на 75 процентов ближе друг к другу, чем стиль штриховки `System.Drawing.drawing2d.HatchStyle.Horizontal` (или на 25 процентов ближе, чем `System.Drawing.drawing2d.HatchStyle.LightHorizontal`). |
| [DarkVertical](#DarkVertical) | Указывает вертикальные линии, расположенные на 50 процентов ближе друг к другу, чем `System.Drawing.drawing2d.HatchStyle.Vertical`, и в два раза шире их. |
| [DarkHorizontal](#DarkHorizontal) | Указывает горизонтальные линии, расположенные на 50 процентов ближе друг к другу, чем `System.Drawing.drawing2d.HatchStyle.Horizontal`, и в два раза шире `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [DashedDownwardDiagonal](#DashedDownwardDiagonal) | Указывает пунктирные диагональные линии, наклонённые вправо от верхних точек к нижним. |
| [DashedUpwardDiagonal](#DashedUpwardDiagonal) | Указывает пунктирные диагональные линии, наклонённые влево от верхних точек к нижним. |
| [DashedHorizontal](#DashedHorizontal) | Указывает пунктирные горизонтальные линии. |
| [DashedVertical](#DashedVertical) | Указывает пунктирные вертикальные линии. |
| [SmallConfetti](#SmallConfetti) | Указывает штриховку, имеющую вид конфетти. |
| [LargeConfetti](#LargeConfetti) | Указывает штриховку, имеющую вид конфетти и состоящую из более крупных элементов, чем `System.Drawing.drawing2d.HatchStyle.SmallConfetti`. |
| [ZigZag](#ZigZag) | Указывает горизонтальные линии, состоящие из зигзагов. |
| [Wave](#Wave) | Указывает горизонтальные линии, состоящие из тильд. |
| [DiagonalBrick](#DiagonalBrick) | Указывает штриховку, имитирующую слоистые кирпичи, наклонённые влево от верхних точек к нижним. |
| [HorizontalBrick](#HorizontalBrick) | Указывает штриховку, имитирующую горизонтально слоистые кирпичи. |
| [Weave](#Weave) | Указывает штриховку, имитирующую тканый материал. |
| [Plaid](#Plaid) | Указывает штриховку, имитирующую клетчатый материал. |
| [Divot](#Divot) | Указывает штриховку, имитирующую ямки. |
| [DottedGrid](#DottedGrid) | Указывает горизонтальные и вертикальные линии, каждая из которых состоит из точек и пересекаются. |
| [DottedDiamond](#DottedDiamond) | Указывает прямые диагональные и обратные диагональные линии, каждая из которой состоит из точек и пересекаются. |
| [Shingle](#Shingle) | Указывает штриховку, имитирующую диагонально слоистые гонты, наклонённые вправо от верхних точек к нижним. |
| [Trellis](#Trellis) | Указывает штриховку, имитирующую решётку. |
| [Sphere](#Sphere) | Указывает штриховку, имитирующую сферы, расположенные рядом друг с другом. |
| [SmallGrid](#SmallGrid) | Указывает горизонтальные и вертикальные линии, пересекающиеся и расположенные на 50 процентов ближе друг к другу, чем стиль штриховки `System.Drawing.drawing2d.HatchStyle.Cross`. |
| [SmallCheckerBoard](#SmallCheckerBoard) | Указывает штриховку, имитирующую шахматную доску. |
| [LargeCheckerBoard](#LargeCheckerBoard) | Указывает штриховку, имитирующую шахматную доску с квадратами, в два раза больше `System.Drawing.drawing2d.HatchStyle.SmallCheckerBoard`. |
| [OutlinedDiamond](#OutlinedDiamond) | Указывает прямые и обратные диагональные линии, которые пересекаются, но не сглажены. |
| [SolidDiamond](#SolidDiamond) | Указывает штриховку, имеющую вид шахматной доски, размещённой по диагонали. |
| [LargeGrid](#LargeGrid) | Указывает стиль штриховки `System.Drawing.drawing2d.HatchStyle.Cross`. |
| [Min](#Min) | Указывает стиль штриховки `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [Max](#Max) | Указывает стиль штриховки `System.Drawing.drawing2d.HatchStyle.SolidDiamond`. |
### Horizontal {#Horizontal}
```
public static final int Horizontal
```


Шаблон из горизонтальных линий.

### Vertical {#Vertical}
```
public static final int Vertical
```


Шаблон из вертикальных линий.

### ForwardDiagonal {#ForwardDiagonal}
```
public static final int ForwardDiagonal
```


Шаблон линий по диагонали от верхнего левого угла к нижнему правому.

### BackwardDiagonal {#BackwardDiagonal}
```
public static final int BackwardDiagonal
```


Шаблон линий по диагонали от верхнего правого угла к нижнему левому.

### Cross {#Cross}
```
public static final int Cross
```


Указывает горизонтальные и вертикальные линии, которые пересекаются.

### DiagonalCross {#DiagonalCross}
```
public static final int DiagonalCross
```


Шаблон пересекающихся диагональных линий.

### Percent05 {#Percent05}
```
public static final int Percent05
```


Указывает 5‑процентную штриховку. Соотношение цвета переднего плана к цвету фона составляет 5:100.

### Percent10 {#Percent10}
```
public static final int Percent10
```


Указывает 10‑процентную штриховку. Соотношение цвета переднего плана к цвету фона составляет 10:100.

### Percent20 {#Percent20}
```
public static final int Percent20
```


Указывает 20‑процентную штриховку. Соотношение цвета переднего плана к цвету фона составляет 20:100.

### Percent25 {#Percent25}
```
public static final int Percent25
```


Указывает 25‑процентную штриховку. Соотношение цвета переднего плана к цвету фона составляет 25:100.

### Percent30 {#Percent30}
```
public static final int Percent30
```


Указывает 30‑процентную штриховку. Соотношение цвета переднего плана к цвету фона составляет 30:100.

### Percent40 {#Percent40}
```
public static final int Percent40
```


Указывает 40‑процентную штриховку. Соотношение цвета переднего плана к цвету фона составляет 40:100.

### Percent50 {#Percent50}
```
public static final int Percent50
```


Указывает 50‑процентную штриховку. Соотношение цвета переднего плана к цвету фона составляет 50:100.

### Percent60 {#Percent60}
```
public static final int Percent60
```


Указывает 60‑процентную штриховку. Соотношение цвета переднего плана к цвету фона составляет 60:100.

### Percent70 {#Percent70}
```
public static final int Percent70
```


Указывает 70‑процентную штриховку. Соотношение цвета переднего плана к цвету фона составляет 70:100.

### Percent75 {#Percent75}
```
public static final int Percent75
```


Указывает 75‑процентную штриховку. Соотношение цвета переднего плана к цвету фона составляет 75:100.

### Percent80 {#Percent80}
```
public static final int Percent80
```


Указывает 80‑процентную штриховку. Соотношение цвета переднего плана к цвету фона составляет 80:100.

### Percent90 {#Percent90}
```
public static final int Percent90
```


Указывает 90‑процентную штриховку. Соотношение цвета переднего плана к цвету фона составляет 90:100.

### LightDownwardDiagonal {#LightDownwardDiagonal}
```
public static final int LightDownwardDiagonal
```


Указывает диагональные линии, наклонённые вправо от верхних точек к нижним точкам и расположенные на 50 % ближе друг к другу, чем `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, но без сглаживания.

### LightUpwardDiagonal {#LightUpwardDiagonal}
```
public static final int LightUpwardDiagonal
```


Указывает диагональные линии, наклонённые влево от верхних точек к нижним точкам и расположенные на 50 % ближе друг к другу, чем `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, но они не сглажены.

### DarkDownwardDiagonal {#DarkDownwardDiagonal}
```
public static final int DarkDownwardDiagonal
```


Указывает диагональные линии, наклонённые вправо от верхних точек к нижним, расположенные на 50 процентов ближе друг к другу и в два раза шире, чем `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`. Этот шаблон штриховки не сглаживается.

### DarkUpwardDiagonal {#DarkUpwardDiagonal}
```
public static final int DarkUpwardDiagonal
```


Указывает диагональные линии, наклонённые влево от верхних точек к нижним точкам, расположенные на 50 % ближе друг к другу, чем `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, и в два раза шире его, но линии не сглажены.

### WideDownwardDiagonal {#WideDownwardDiagonal}
```
public static final int WideDownwardDiagonal
```


Указывает диагональные линии, наклонённые вправо от верхних точек к нижним точкам, имеющие такое же расстояние, как штриховка `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, и в три раза шире её, но без сглаживания.

### WideUpwardDiagonal {#WideUpwardDiagonal}
```
public static final int WideUpwardDiagonal
```


Указывает диагональные линии, наклонённые влево от верхних точек к нижним точкам, имеющие такое же расстояние, как штриховка `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, и в три раза шире её, но без сглаживания.

### LightVertical {#LightVertical}
```
public static final int LightVertical
```


Указывает вертикальные линии, расположенные на 50 % ближе друг к другу, чем `System.Drawing.drawing2d.HatchStyle.Vertical`.

### LightHorizontal {#LightHorizontal}
```
public static final int LightHorizontal
```


Указывает горизонтальные линии, расположенные на 50 % ближе друг к другу, чем `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### NarrowVertical {#NarrowVertical}
```
public static final int NarrowVertical
```


Указывает вертикальные линии, расположенные на 75 % ближе друг к другу, чем штриховка `System.Drawing.drawing2d.HatchStyle.Vertical` (или на 25 % ближе, чем `System.Drawing.drawing2d.HatchStyle.LightVertical`).

### NarrowHorizontal {#NarrowHorizontal}
```
public static final int NarrowHorizontal
```


Указывает горизонтальные линии, расположенные на 75 процентов ближе друг к другу, чем стиль штриховки `System.Drawing.drawing2d.HatchStyle.Horizontal` (или на 25 процентов ближе, чем `System.Drawing.drawing2d.HatchStyle.LightHorizontal`).

### DarkVertical {#DarkVertical}
```
public static final int DarkVertical
```


Указывает вертикальные линии, расположенные на 50 процентов ближе друг к другу, чем `System.Drawing.drawing2d.HatchStyle.Vertical`, и в два раза шире их.

### DarkHorizontal {#DarkHorizontal}
```
public static final int DarkHorizontal
```


Указывает горизонтальные линии, расположенные на 50 процентов ближе друг к другу, чем `System.Drawing.drawing2d.HatchStyle.Horizontal`, и в два раза шире `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### DashedDownwardDiagonal {#DashedDownwardDiagonal}
```
public static final int DashedDownwardDiagonal
```


Указывает пунктирные диагональные линии, наклонённые вправо от верхних точек к нижним.

### DashedUpwardDiagonal {#DashedUpwardDiagonal}
```
public static final int DashedUpwardDiagonal
```


Указывает пунктирные диагональные линии, наклонённые влево от верхних точек к нижним.

### DashedHorizontal {#DashedHorizontal}
```
public static final int DashedHorizontal
```


Указывает пунктирные горизонтальные линии.

### DashedVertical {#DashedVertical}
```
public static final int DashedVertical
```


Указывает пунктирные вертикальные линии.

### SmallConfetti {#SmallConfetti}
```
public static final int SmallConfetti
```


Указывает штриховку, имеющую вид конфетти.

### LargeConfetti {#LargeConfetti}
```
public static final int LargeConfetti
```


Указывает штриховку, имеющую вид конфетти и состоящую из более крупных элементов, чем `System.Drawing.drawing2d.HatchStyle.SmallConfetti`.

### ZigZag {#ZigZag}
```
public static final int ZigZag
```


Указывает горизонтальные линии, состоящие из зигзагов.

### Wave {#Wave}
```
public static final int Wave
```


Указывает горизонтальные линии, состоящие из тильд.

### DiagonalBrick {#DiagonalBrick}
```
public static final int DiagonalBrick
```


Указывает штриховку, имитирующую слоистые кирпичи, наклонённые влево от верхних точек к нижним.

### HorizontalBrick {#HorizontalBrick}
```
public static final int HorizontalBrick
```


Указывает штриховку, имитирующую горизонтально слоистые кирпичи.

### Weave {#Weave}
```
public static final int Weave
```


Указывает штриховку, имитирующую тканый материал.

### Plaid {#Plaid}
```
public static final int Plaid
```


Указывает штриховку, имитирующую клетчатый материал.

### Divot {#Divot}
```
public static final int Divot
```


Указывает штриховку, имитирующую ямки.

### DottedGrid {#DottedGrid}
```
public static final int DottedGrid
```


Указывает горизонтальные и вертикальные линии, каждая из которых состоит из точек и пересекаются.

### DottedDiamond {#DottedDiamond}
```
public static final int DottedDiamond
```


Указывает прямые диагональные и обратные диагональные линии, каждая из которой состоит из точек и пересекаются.

### Shingle {#Shingle}
```
public static final int Shingle
```


Указывает штриховку, имитирующую диагонально слоистые гонты, наклонённые вправо от верхних точек к нижним.

### Trellis {#Trellis}
```
public static final int Trellis
```


Указывает штриховку, имитирующую решётку.

### Sphere {#Sphere}
```
public static final int Sphere
```


Указывает штриховку, имитирующую сферы, расположенные рядом друг с другом.

### SmallGrid {#SmallGrid}
```
public static final int SmallGrid
```


Указывает горизонтальные и вертикальные линии, пересекающиеся и расположенные на 50 процентов ближе друг к другу, чем стиль штриховки `System.Drawing.drawing2d.HatchStyle.Cross`.

### SmallCheckerBoard {#SmallCheckerBoard}
```
public static final int SmallCheckerBoard
```


Указывает штриховку, имитирующую шахматную доску.

### LargeCheckerBoard {#LargeCheckerBoard}
```
public static final int LargeCheckerBoard
```


Указывает штриховку, имитирующую шахматную доску с квадратами, в два раза больше `System.Drawing.drawing2d.HatchStyle.SmallCheckerBoard`.

### OutlinedDiamond {#OutlinedDiamond}
```
public static final int OutlinedDiamond
```


Указывает прямые и обратные диагональные линии, которые пересекаются, но не сглажены.

### SolidDiamond {#SolidDiamond}
```
public static final int SolidDiamond
```


Указывает штриховку, имеющую вид шахматной доски, размещённой по диагонали.

### LargeGrid {#LargeGrid}
```
public static final int LargeGrid
```


Указывает стиль штриховки `System.Drawing.drawing2d.HatchStyle.Cross`.

### Min {#Min}
```
public static final int Min
```


Указывает стиль штриховки `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### Max {#Max}
```
public static final int Max
```


Указывает стиль штриховки `System.Drawing.drawing2d.HatchStyle.SolidDiamond`.

