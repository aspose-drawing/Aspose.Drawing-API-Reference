---
title: HatchStyle
second_title: Aspose.Drawing for Java API 참조
description: 객체에 사용할 수 있는 다양한 패턴을 지정합니다.
type: docs
weight: 27
url: /ko/java/com.aspose.drawing.drawing2d/hatchstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HatchStyle extends System.Enum
```

[HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) 객체에 사용할 수 있는 다양한 패턴을 지정합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [Horizontal](#Horizontal) | 가로선 패턴입니다. |
| [Vertical](#Vertical) | 세로선 패턴입니다. |
| [ForwardDiagonal](#ForwardDiagonal) | 왼쪽 위에서 오른쪽 아래로 대각선 방향에 있는 선 패턴. |
| [BackwardDiagonal](#BackwardDiagonal) | 오른쪽 위에서 왼쪽 아래로 대각선 방향에 있는 선 패턴. |
| [Cross](#Cross) | 교차하는 가로선과 세로선을 지정합니다. |
| [DiagonalCross](#DiagonalCross) | 교차하는 대각선 선 패턴. |
| [Percent05](#Percent05) | 5% 해치를 지정합니다. |
| [Percent10](#Percent10) | 10% 해치를 지정합니다. |
| [Percent20](#Percent20) | 20% 해치를 지정합니다. |
| [Percent25](#Percent25) | 25% 해치를 지정합니다. |
| [Percent30](#Percent30) | 30% 해치를 지정합니다. |
| [Percent40](#Percent40) | 40% 해치를 지정합니다. |
| [Percent50](#Percent50) | 50% 해치를 지정합니다. |
| [Percent60](#Percent60) | 60% 해치를 지정합니다. |
| [Percent70](#Percent70) | 70% 해치를 지정합니다. |
| [Percent75](#Percent75) | 75% 해치를 지정합니다. |
| [Percent80](#Percent80) | 80% 해치를 지정합니다. |
| [Percent90](#Percent90) | 90% 해치를 지정합니다. |
| [LightDownwardDiagonal](#LightDownwardDiagonal) | 위쪽 점에서 아래쪽 점으로 오른쪽으로 기울어진 대각선 선을 지정하며, `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`보다 50% 더 촘촘히 배치되지만 안티앨리어싱되지 않습니다. |
| [LightUpwardDiagonal](#LightUpwardDiagonal) | 위쪽 점에서 아래쪽 점으로 왼쪽으로 기울어진 대각선 선을 지정하며, `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`보다 50% 더 촘촘히 배치되지만 안티앨리어싱되지 않습니다. |
| [DarkDownwardDiagonal](#DarkDownwardDiagonal) | 위쪽 점에서 아래쪽 점으로 오른쪽으로 기울어진 대각선 선을 지정하고, `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`보다 50% 더 촘촘히 배치되며, 두께는 두 배입니다. |
| [DarkUpwardDiagonal](#DarkUpwardDiagonal) | 위쪽 점에서 아래쪽 점으로 왼쪽으로 기울어진 대각선 선을 지정하며, `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`보다 50% 더 촘촘히 배치되고, 두께가 두 배이지만 안티앨리어싱되지 않습니다. |
| [WideDownwardDiagonal](#WideDownwardDiagonal) | 위쪽 점에서 아래쪽 점으로 오른쪽으로 기울어진 대각선 선을 지정하고, 해치 스타일 `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`와 동일한 간격을 가지며, 두께는 세 배이지만 안티앨리어싱되지 않습니다. |
| [WideUpwardDiagonal](#WideUpwardDiagonal) | 위쪽 점에서 아래쪽 점으로 왼쪽으로 기울어진 대각선 선을 지정하고, 해치 스타일 `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`와 동일한 간격을 가지며, 두께는 세 배이지만 안티앨리어싱되지 않습니다. |
| [LightVertical](#LightVertical) | `System.Drawing.drawing2d.HatchStyle.Vertical`보다 50% 더 촘촘히 배치된 세로선을 지정합니다. |
| [LightHorizontal](#LightHorizontal) | `System.Drawing.drawing2d.HatchStyle.Horizontal`보다 50% 더 촘촘히 배치된 가로선을 지정합니다. |
| [NarrowVertical](#NarrowVertical) | 해치 스타일 `System.Drawing.drawing2d.HatchStyle.Vertical`보다 75% 더 촘촘히(또는 `System.Drawing.drawing2d.HatchStyle.LightVertical`보다 25% 더 촘촘히) 배치된 세로선을 지정합니다. |
| [NarrowHorizontal](#NarrowHorizontal) | 수평선이 해치 스타일 `System.Drawing.drawing2d.HatchStyle.Horizontal`보다 75% 더 가깝게 배치되고 (`System.Drawing.drawing2d.HatchStyle.LightHorizontal`보다 25% 더 가깝게) 지정됩니다. |
| [DarkVertical](#DarkVertical) | `System.Drawing.drawing2d.HatchStyle.Vertical`보다 50% 더 가깝게 배치되고 두께가 두 배인 수직선을 지정합니다. |
| [DarkHorizontal](#DarkHorizontal) | `System.Drawing.drawing2d.HatchStyle.Horizontal`보다 50% 더 가깝게 배치되고, `System.Drawing.drawing2d.HatchStyle.Horizontal`의 두께의 두 배인 수평선을 지정합니다. |
| [DashedDownwardDiagonal](#DashedDownwardDiagonal) | 위쪽 점에서 아래쪽 점으로 오른쪽으로 기울어지는 대시 대각선 라인을 지정합니다. |
| [DashedUpwardDiagonal](#DashedUpwardDiagonal) | 위쪽 점에서 아래쪽 점으로 왼쪽으로 기울어지는 대시 대각선 라인을 지정합니다. |
| [DashedHorizontal](#DashedHorizontal) | 대시 수평선을 지정합니다. |
| [DashedVertical](#DashedVertical) | 대시 수직선을 지정합니다. |
| [SmallConfetti](#SmallConfetti) | 컨페티 모양의 해치를 지정합니다. |
| [LargeConfetti](#LargeConfetti) | `System.Drawing.drawing2d.HatchStyle.SmallConfetti`보다 큰 조각으로 구성된 컨페티 모양의 해치를 지정합니다. |
| [ZigZag](#ZigZag) | 지그재그로 구성된 수평선을 지정합니다. |
| [Wave](#Wave) | 틸드(~)로 구성된 수평선을 지정합니다. |
| [DiagonalBrick](#DiagonalBrick) | 위쪽 점에서 아래쪽 점으로 왼쪽으로 기울어지는 층이 있는 벽돌 모양의 해치를 지정합니다. |
| [HorizontalBrick](#HorizontalBrick) | 수평으로 층이 있는 벽돌 모양의 해치를 지정합니다. |
| [Weave](#Weave) | 직조된 재료 모양의 해치를 지정합니다. |
| [Plaid](#Plaid) | 격자무늬 재료 모양의 해치를 지정합니다. |
| [Divot](#Divot) | 작은 움푹 들어간 부분 모양의 해치를 지정합니다. |
| [DottedGrid](#DottedGrid) | 점으로 구성된 수평선과 수직선이 교차하도록 지정합니다. |
| [DottedDiamond](#DottedDiamond) | 점으로 구성된 전방 대각선과 후방 대각선이 교차하도록 지정합니다. |
| [Shingle](#Shingle) | 위쪽 점에서 아래쪽 점으로 오른쪽으로 기울어지는 대각선 층이 있는 기와 모양의 해치를 지정합니다. |
| [Trellis](#Trellis) | 격자 구조물 모양의 해치를 지정합니다. |
| [Sphere](#Sphere) | 인접하게 배치된 구형 모양의 해치를 지정합니다. |
| [SmallGrid](#SmallGrid) | `System.Drawing.drawing2d.HatchStyle.Cross`보다 50% 더 가깝게 배치되고 교차하는 수평선과 수직선을 지정합니다. |
| [SmallCheckerBoard](#SmallCheckerBoard) | 체커보드 모양의 해치를 지정합니다. |
| [LargeCheckerBoard](#LargeCheckerBoard) | `System.Drawing.drawing2d.HatchStyle.SmallCheckerBoard`보다 두 배 크기의 정사각형을 가진 체커보드 모양의 해치를 지정합니다. |
| [OutlinedDiamond](#OutlinedDiamond) | 교차하지만 안티앨리어싱되지 않은 전방 대각선과 후방 대각선을 지정합니다. |
| [SolidDiamond](#SolidDiamond) | 대각선으로 배치된 체커보드 모양의 해치를 지정합니다. |
| [LargeGrid](#LargeGrid) | `System.Drawing.drawing2d.HatchStyle.Cross` 해치 스타일을 지정합니다. |
| [Min](#Min) | `System.Drawing.drawing2d.HatchStyle.Horizontal` 해치 스타일을 지정합니다. |
| [Max](#Max) | `System.Drawing.drawing2d.HatchStyle.SolidDiamond` 해치 스타일을 지정합니다. |
### Horizontal {#Horizontal}
```
public static final int Horizontal
```


가로선 패턴입니다.

### Vertical {#Vertical}
```
public static final int Vertical
```


세로선 패턴입니다.

### ForwardDiagonal {#ForwardDiagonal}
```
public static final int ForwardDiagonal
```


왼쪽 위에서 오른쪽 아래로 대각선 방향에 있는 선 패턴.

### BackwardDiagonal {#BackwardDiagonal}
```
public static final int BackwardDiagonal
```


오른쪽 위에서 왼쪽 아래로 대각선 방향에 있는 선 패턴.

### Cross {#Cross}
```
public static final int Cross
```


교차하는 가로선과 세로선을 지정합니다.

### DiagonalCross {#DiagonalCross}
```
public static final int DiagonalCross
```


교차하는 대각선 선 패턴.

### Percent05 {#Percent05}
```
public static final int Percent05
```


5% 해치를 지정합니다. 전경색과 배경색의 비율은 5:100입니다.

### Percent10 {#Percent10}
```
public static final int Percent10
```


10% 해치를 지정합니다. 전경색과 배경색의 비율은 10:100입니다.

### Percent20 {#Percent20}
```
public static final int Percent20
```


20% 해치를 지정합니다. 전경색과 배경색의 비율은 20:100입니다.

### Percent25 {#Percent25}
```
public static final int Percent25
```


25% 해치를 지정합니다. 전경색과 배경색의 비율은 25:100입니다.

### Percent30 {#Percent30}
```
public static final int Percent30
```


30% 해치를 지정합니다. 전경색과 배경색의 비율은 30:100입니다.

### Percent40 {#Percent40}
```
public static final int Percent40
```


40% 해치를 지정합니다. 전경색과 배경색의 비율은 40:100입니다.

### Percent50 {#Percent50}
```
public static final int Percent50
```


50% 해치를 지정합니다. 전경색과 배경색의 비율은 50:100입니다.

### Percent60 {#Percent60}
```
public static final int Percent60
```


60% 해치를 지정합니다. 전경색과 배경색의 비율은 60:100입니다.

### Percent70 {#Percent70}
```
public static final int Percent70
```


70% 해치를 지정합니다. 전경색과 배경색의 비율은 70:100입니다.

### Percent75 {#Percent75}
```
public static final int Percent75
```


75% 해치를 지정합니다. 전경색과 배경색의 비율은 75:100입니다.

### Percent80 {#Percent80}
```
public static final int Percent80
```


80% 해치를 지정합니다. 전경색과 배경색의 비율은 80:100입니다.

### Percent90 {#Percent90}
```
public static final int Percent90
```


90% 해치를 지정합니다. 전경색과 배경색의 비율은 90:100입니다.

### LightDownwardDiagonal {#LightDownwardDiagonal}
```
public static final int LightDownwardDiagonal
```


위쪽 점에서 아래쪽 점으로 오른쪽으로 기울어진 대각선 선을 지정하며, `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`보다 50% 더 촘촘히 배치되지만 안티앨리어싱되지 않습니다.

### LightUpwardDiagonal {#LightUpwardDiagonal}
```
public static final int LightUpwardDiagonal
```


위쪽 점에서 아래쪽 점으로 왼쪽으로 기울어진 대각선 선을 지정하며, `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`보다 50% 더 촘촘히 배치되지만 안티앨리어싱되지 않습니다.

### DarkDownwardDiagonal {#DarkDownwardDiagonal}
```
public static final int DarkDownwardDiagonal
```


위쪽 점에서 아래쪽 점으로 오른쪽으로 기울어지는 대각선 선을 지정합니다. 이 선은 `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`보다 50% 더 가깝게 배치되고 두께가 두 배이며, 이 해치 패턴은 안티앨리어싱되지 않습니다.

### DarkUpwardDiagonal {#DarkUpwardDiagonal}
```
public static final int DarkUpwardDiagonal
```


위쪽 점에서 아래쪽 점으로 왼쪽으로 기울어진 대각선 선을 지정하며, `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`보다 50% 더 촘촘히 배치되고, 두께가 두 배이지만 안티앨리어싱되지 않습니다.

### WideDownwardDiagonal {#WideDownwardDiagonal}
```
public static final int WideDownwardDiagonal
```


위쪽 점에서 아래쪽 점으로 오른쪽으로 기울어진 대각선 선을 지정하고, 해치 스타일 `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`와 동일한 간격을 가지며, 두께는 세 배이지만 안티앨리어싱되지 않습니다.

### WideUpwardDiagonal {#WideUpwardDiagonal}
```
public static final int WideUpwardDiagonal
```


위쪽 점에서 아래쪽 점으로 왼쪽으로 기울어진 대각선 선을 지정하고, 해치 스타일 `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`와 동일한 간격을 가지며, 두께는 세 배이지만 안티앨리어싱되지 않습니다.

### LightVertical {#LightVertical}
```
public static final int LightVertical
```


`System.Drawing.drawing2d.HatchStyle.Vertical`보다 50% 더 촘촘히 배치된 세로선을 지정합니다.

### LightHorizontal {#LightHorizontal}
```
public static final int LightHorizontal
```


`System.Drawing.drawing2d.HatchStyle.Horizontal`보다 50% 더 촘촘히 배치된 가로선을 지정합니다.

### NarrowVertical {#NarrowVertical}
```
public static final int NarrowVertical
```


해치 스타일 `System.Drawing.drawing2d.HatchStyle.Vertical`보다 75% 더 촘촘히(또는 `System.Drawing.drawing2d.HatchStyle.LightVertical`보다 25% 더 촘촘히) 배치된 세로선을 지정합니다.

### NarrowHorizontal {#NarrowHorizontal}
```
public static final int NarrowHorizontal
```


수평선이 해치 스타일 `System.Drawing.drawing2d.HatchStyle.Horizontal`보다 75% 더 가깝게 배치되고 (`System.Drawing.drawing2d.HatchStyle.LightHorizontal`보다 25% 더 가깝게) 지정됩니다.

### DarkVertical {#DarkVertical}
```
public static final int DarkVertical
```


`System.Drawing.drawing2d.HatchStyle.Vertical`보다 50% 더 가깝게 배치되고 두께가 두 배인 수직선을 지정합니다.

### DarkHorizontal {#DarkHorizontal}
```
public static final int DarkHorizontal
```


`System.Drawing.drawing2d.HatchStyle.Horizontal`보다 50% 더 가깝게 배치되고, `System.Drawing.drawing2d.HatchStyle.Horizontal`의 두께의 두 배인 수평선을 지정합니다.

### DashedDownwardDiagonal {#DashedDownwardDiagonal}
```
public static final int DashedDownwardDiagonal
```


위쪽 점에서 아래쪽 점으로 오른쪽으로 기울어지는 대시 대각선 라인을 지정합니다.

### DashedUpwardDiagonal {#DashedUpwardDiagonal}
```
public static final int DashedUpwardDiagonal
```


위쪽 점에서 아래쪽 점으로 왼쪽으로 기울어지는 대시 대각선 라인을 지정합니다.

### DashedHorizontal {#DashedHorizontal}
```
public static final int DashedHorizontal
```


대시 수평선을 지정합니다.

### DashedVertical {#DashedVertical}
```
public static final int DashedVertical
```


대시 수직선을 지정합니다.

### SmallConfetti {#SmallConfetti}
```
public static final int SmallConfetti
```


컨페티 모양의 해치를 지정합니다.

### LargeConfetti {#LargeConfetti}
```
public static final int LargeConfetti
```


`System.Drawing.drawing2d.HatchStyle.SmallConfetti`보다 큰 조각으로 구성된 컨페티 모양의 해치를 지정합니다.

### ZigZag {#ZigZag}
```
public static final int ZigZag
```


지그재그로 구성된 수평선을 지정합니다.

### Wave {#Wave}
```
public static final int Wave
```


틸드(~)로 구성된 수평선을 지정합니다.

### DiagonalBrick {#DiagonalBrick}
```
public static final int DiagonalBrick
```


위쪽 점에서 아래쪽 점으로 왼쪽으로 기울어지는 층이 있는 벽돌 모양의 해치를 지정합니다.

### HorizontalBrick {#HorizontalBrick}
```
public static final int HorizontalBrick
```


수평으로 층이 있는 벽돌 모양의 해치를 지정합니다.

### Weave {#Weave}
```
public static final int Weave
```


직조된 재료 모양의 해치를 지정합니다.

### Plaid {#Plaid}
```
public static final int Plaid
```


격자무늬 재료 모양의 해치를 지정합니다.

### Divot {#Divot}
```
public static final int Divot
```


작은 움푹 들어간 부분 모양의 해치를 지정합니다.

### DottedGrid {#DottedGrid}
```
public static final int DottedGrid
```


점으로 구성된 수평선과 수직선이 교차하도록 지정합니다.

### DottedDiamond {#DottedDiamond}
```
public static final int DottedDiamond
```


점으로 구성된 전방 대각선과 후방 대각선이 교차하도록 지정합니다.

### Shingle {#Shingle}
```
public static final int Shingle
```


위쪽 점에서 아래쪽 점으로 오른쪽으로 기울어지는 대각선 층이 있는 기와 모양의 해치를 지정합니다.

### Trellis {#Trellis}
```
public static final int Trellis
```


격자 구조물 모양의 해치를 지정합니다.

### Sphere {#Sphere}
```
public static final int Sphere
```


인접하게 배치된 구형 모양의 해치를 지정합니다.

### SmallGrid {#SmallGrid}
```
public static final int SmallGrid
```


`System.Drawing.drawing2d.HatchStyle.Cross`보다 50% 더 가깝게 배치되고 교차하는 수평선과 수직선을 지정합니다.

### SmallCheckerBoard {#SmallCheckerBoard}
```
public static final int SmallCheckerBoard
```


체커보드 모양의 해치를 지정합니다.

### LargeCheckerBoard {#LargeCheckerBoard}
```
public static final int LargeCheckerBoard
```


`System.Drawing.drawing2d.HatchStyle.SmallCheckerBoard`보다 두 배 크기의 정사각형을 가진 체커보드 모양의 해치를 지정합니다.

### OutlinedDiamond {#OutlinedDiamond}
```
public static final int OutlinedDiamond
```


교차하지만 안티앨리어싱되지 않은 전방 대각선과 후방 대각선을 지정합니다.

### SolidDiamond {#SolidDiamond}
```
public static final int SolidDiamond
```


대각선으로 배치된 체커보드 모양의 해치를 지정합니다.

### LargeGrid {#LargeGrid}
```
public static final int LargeGrid
```


`System.Drawing.drawing2d.HatchStyle.Cross` 해치 스타일을 지정합니다.

### Min {#Min}
```
public static final int Min
```


`System.Drawing.drawing2d.HatchStyle.Horizontal` 해치 스타일을 지정합니다.

### Max {#Max}
```
public static final int Max
```


`System.Drawing.drawing2d.HatchStyle.SolidDiamond` 해치 스타일을 지정합니다.

