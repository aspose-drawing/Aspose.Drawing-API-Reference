---
title: HatchStyle
second_title: Aspose.Drawing für Java API-Referenz
description: Gibt die verschiedenen Muster an, die für Objekte verfügbar sind.
type: docs
weight: 27
url: /de/java/com.aspose.drawing.drawing2d/hatchstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HatchStyle extends System.Enum
```

Gibt die verschiedenen Muster an, die für [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush)-Objekte verfügbar sind.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Horizontal](#Horizontal) | Ein Muster aus horizontalen Linien. |
| [Vertical](#Vertical) | Ein Muster aus vertikalen Linien. |
| [ForwardDiagonal](#ForwardDiagonal) | Ein Muster von Linien auf einer Diagonale von oben links nach unten rechts. |
| [BackwardDiagonal](#BackwardDiagonal) | Ein Muster von Linien auf einer Diagonale von oben rechts nach unten links. |
| [Cross](#Cross) | Gibt horizontale und vertikale Linien an, die sich kreuzen. |
| [DiagonalCross](#DiagonalCross) | Ein Muster aus kreuzenden diagonalen Linien. |
| [Percent05](#Percent05) | Gibt ein 5‑Prozent‑Schraffurmuster an. |
| [Percent10](#Percent10) | Gibt ein 10‑Prozent‑Schraffurmuster an. |
| [Percent20](#Percent20) | Gibt ein 20‑Prozent‑Schraffurmuster an. |
| [Percent25](#Percent25) | Gibt ein 25‑Prozent‑Schraffurmuster an. |
| [Percent30](#Percent30) | Gibt ein 30‑Prozent‑Schraffurmuster an. |
| [Percent40](#Percent40) | Gibt ein 40‑Prozent‑Schraffurmuster an. |
| [Percent50](#Percent50) | Gibt ein 50‑Prozent‑Schraffurmuster an. |
| [Percent60](#Percent60) | Gibt ein 60‑Prozent‑Schraffurmuster an. |
| [Percent70](#Percent70) | Gibt ein 70‑Prozent‑Schraffurmuster an. |
| [Percent75](#Percent75) | Gibt ein 75‑Prozent‑Schraffurmuster an. |
| [Percent80](#Percent80) | Gibt ein 80‑Prozent‑Schraffurmuster an. |
| [Percent90](#Percent90) | Gibt ein 90‑Prozent‑Schraffurmuster an. |
| [LightDownwardDiagonal](#LightDownwardDiagonal) | Gibt diagonale Linien an, die von den oberen Punkten zu den unteren Punkten nach rechts geneigt sind und 50 Prozent dichter beabstandet sind als `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, jedoch nicht antialiasiert sind. |
| [LightUpwardDiagonal](#LightUpwardDiagonal) | Gibt diagonale Linien an, die von den oberen Punkten zu den unteren Punkten nach links geneigt sind und 50 Prozent dichter beabstandet sind als `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, jedoch nicht antialiasiert sind. |
| [DarkDownwardDiagonal](#DarkDownwardDiagonal) | Gibt diagonale Linien an, die von den oberen Punkten zu den unteren Punkten nach rechts geneigt sind, 50 Prozent dichter beabstandet sind als `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal` und doppelt so breit wie diese. |
| [DarkUpwardDiagonal](#DarkUpwardDiagonal) | Gibt diagonale Linien an, die von den oberen Punkten zu den unteren Punkten nach links geneigt sind, 50 Prozent dichter beabstandet sind als `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal` und doppelt so breit wie diese, jedoch sind die Linien nicht antialiasiert. |
| [WideDownwardDiagonal](#WideDownwardDiagonal) | Gibt diagonale Linien an, die von den oberen Punkten zu den unteren Punkten nach rechts geneigt sind, denselben Abstand wie Schraffurstil `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal` haben und dreimal so breit sind, jedoch nicht antialiasiert sind. |
| [WideUpwardDiagonal](#WideUpwardDiagonal) | Gibt diagonale Linien an, die von den oberen Punkten zu den unteren Punkten nach links geneigt sind, denselben Abstand wie Schraffurstil `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal` haben und dreimal so breit sind, jedoch nicht antialiasiert sind. |
| [LightVertical](#LightVertical) | Gibt vertikale Linien an, die 50 Prozent dichter beabstandet sind als `System.Drawing.drawing2d.HatchStyle.Vertical`. |
| [LightHorizontal](#LightHorizontal) | Gibt horizontale Linien an, die 50 Prozent dichter beabstandet sind als `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [NarrowVertical](#NarrowVertical) | Gibt vertikale Linien an, die 75 Prozent dichter beabstandet sind als Schraffurstil `System.Drawing.drawing2d.HatchStyle.Vertical` (oder 25 Prozent dichter als `System.Drawing.drawing2d.HatchStyle.LightVertical`). |
| [NarrowHorizontal](#NarrowHorizontal) | Gibt horizontale Linien an, die 75 Prozent dichter beieinander liegen als der Hatch-Stil `System.Drawing.drawing2d.HatchStyle.Horizontal` (oder 25 Prozent dichter als `System.Drawing.drawing2d.HatchStyle.LightHorizontal`). |
| [DarkVertical](#DarkVertical) | Gibt vertikale Linien an, die 50 Prozent dichter beieinander liegen als `System.Drawing.drawing2d.HatchStyle.Vertical` und doppelt so breit sind. |
| [DarkHorizontal](#DarkHorizontal) | Gibt horizontale Linien an, die 50 Prozent dichter beieinander liegen als `System.Drawing.drawing2d.HatchStyle.Horizontal` und doppelt so breit sind wie `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [DashedDownwardDiagonal](#DashedDownwardDiagonal) | Gibt gestrichelte diagonale Linien an, die von den oberen Punkten zu den unteren Punkten nach rechts verlaufen. |
| [DashedUpwardDiagonal](#DashedUpwardDiagonal) | Gibt gestrichelte diagonale Linien an, die von den oberen Punkten zu den unteren Punkten nach links verlaufen. |
| [DashedHorizontal](#DashedHorizontal) | Gibt gestrichelte horizontale Linien an. |
| [DashedVertical](#DashedVertical) | Gibt gestrichelte vertikale Linien an. |
| [SmallConfetti](#SmallConfetti) | Gibt eine Schraffur an, die das Aussehen von Konfetti hat. |
| [LargeConfetti](#LargeConfetti) | Gibt eine Schraffur an, die das Aussehen von Konfetti hat und aus größeren Stücken besteht als `System.Drawing.drawing2d.HatchStyle.SmallConfetti`. |
| [ZigZag](#ZigZag) | Gibt horizontale Linien an, die aus Zickzacklinien bestehen. |
| [Wave](#Wave) | Gibt horizontale Linien an, die aus Tilden bestehen. |
| [DiagonalBrick](#DiagonalBrick) | Gibt eine Schraffur an, die das Aussehen von geschichteten Ziegeln hat, die von den oberen Punkten zu den unteren Punkten nach links geneigt sind. |
| [HorizontalBrick](#HorizontalBrick) | Gibt eine Schraffur an, die das Aussehen von horizontal geschichteten Ziegeln hat. |
| [Weave](#Weave) | Gibt eine Schraffur an, die das Aussehen eines gewebten Materials hat. |
| [Plaid](#Plaid) | Gibt eine Schraffur an, die das Aussehen eines Karomusters hat. |
| [Divot](#Divot) | Gibt eine Schraffur an, die das Aussehen von Dellen hat. |
| [DottedGrid](#DottedGrid) | Gibt horizontale und vertikale Linien an, die jeweils aus Punkten bestehen und sich kreuzen. |
| [DottedDiamond](#DottedDiamond) | Gibt vorwärts gerichtete diagonale und rückwärts gerichtete diagonale Linien an, die jeweils aus Punkten bestehen und sich kreuzen. |
| [Shingle](#Shingle) | Gibt eine Schraffur an, die das Aussehen von diagonal geschichteten Schindeln hat, die von den oberen Punkten zu den unteren Punkten nach rechts geneigt sind. |
| [Trellis](#Trellis) | Gibt eine Schraffur an, die das Aussehen eines Spaliers hat. |
| [Sphere](#Sphere) | Gibt eine Schraffur an, die das Aussehen von nebeneinander liegenden Kugeln hat. |
| [SmallGrid](#SmallGrid) | Gibt horizontale und vertikale Linien an, die sich kreuzen und 50 Prozent dichter beieinander liegen als der Hatch-Stil `System.Drawing.drawing2d.HatchStyle.Cross`. |
| [SmallCheckerBoard](#SmallCheckerBoard) | Gibt eine Schraffur an, die das Aussehen eines Schachbretts hat. |
| [LargeCheckerBoard](#LargeCheckerBoard) | Gibt eine Schraffur an, die das Aussehen eines Schachbretts mit Feldern hat, die doppelt so groß sind wie `System.Drawing.drawing2d.HatchStyle.SmallCheckerBoard`. |
| [OutlinedDiamond](#OutlinedDiamond) | Gibt vorwärts gerichtete diagonale und rückwärts gerichtete diagonale Linien an, die sich kreuzen, aber nicht antialiasiert sind. |
| [SolidDiamond](#SolidDiamond) | Gibt ein Schraffurmuster an, das das Aussehen eines diagonal platzierten Schachbretts hat. |
| [LargeGrid](#LargeGrid) | Gibt den Schraffurstil `System.Drawing.drawing2d.HatchStyle.Cross` an. |
| [Min](#Min) | Gibt den Schraffurstil `System.Drawing.drawing2d.HatchStyle.Horizontal` an. |
| [Max](#Max) | Gibt den Schraffurstil `System.Drawing.drawing2d.HatchStyle.SolidDiamond` an. |
### Horizontal {#Horizontal}
```
public static final int Horizontal
```


Ein Muster aus horizontalen Linien.

### Vertical {#Vertical}
```
public static final int Vertical
```


Ein Muster aus vertikalen Linien.

### ForwardDiagonal {#ForwardDiagonal}
```
public static final int ForwardDiagonal
```


Ein Muster von Linien auf einer Diagonale von oben links nach unten rechts.

### BackwardDiagonal {#BackwardDiagonal}
```
public static final int BackwardDiagonal
```


Ein Muster von Linien auf einer Diagonale von oben rechts nach unten links.

### Cross {#Cross}
```
public static final int Cross
```


Gibt horizontale und vertikale Linien an, die sich kreuzen.

### DiagonalCross {#DiagonalCross}
```
public static final int DiagonalCross
```


Ein Muster aus kreuzenden diagonalen Linien.

### Percent05 {#Percent05}
```
public static final int Percent05
```


Gibt ein 5‑Prozent‑Schraffurmuster an. Das Verhältnis von Vordergrundfarbe zu Hintergrundfarbe beträgt 5:100.

### Percent10 {#Percent10}
```
public static final int Percent10
```


Gibt ein 10‑Prozent‑Schraffurmuster an. Das Verhältnis von Vordergrundfarbe zu Hintergrundfarbe beträgt 10:100.

### Percent20 {#Percent20}
```
public static final int Percent20
```


Gibt ein 20‑Prozent‑Schraffurmuster an. Das Verhältnis von Vordergrundfarbe zu Hintergrundfarbe beträgt 20:100.

### Percent25 {#Percent25}
```
public static final int Percent25
```


Gibt ein 25‑Prozent‑Schraffurmuster an. Das Verhältnis von Vordergrundfarbe zu Hintergrundfarbe beträgt 25:100.

### Percent30 {#Percent30}
```
public static final int Percent30
```


Gibt ein 30‑Prozent‑Schraffurmuster an. Das Verhältnis von Vordergrundfarbe zu Hintergrundfarbe beträgt 30:100.

### Percent40 {#Percent40}
```
public static final int Percent40
```


Gibt ein 40‑Prozent‑Schraffurmuster an. Das Verhältnis von Vordergrundfarbe zu Hintergrundfarbe beträgt 40:100.

### Percent50 {#Percent50}
```
public static final int Percent50
```


Gibt ein 50‑Prozent‑Schraffurmuster an. Das Verhältnis von Vordergrundfarbe zu Hintergrundfarbe beträgt 50:100.

### Percent60 {#Percent60}
```
public static final int Percent60
```


Gibt ein 60‑Prozent‑Schraffurmuster an. Das Verhältnis von Vordergrundfarbe zu Hintergrundfarbe beträgt 60:100.

### Percent70 {#Percent70}
```
public static final int Percent70
```


Gibt ein 70‑Prozent‑Schraffurmuster an. Das Verhältnis von Vordergrundfarbe zu Hintergrundfarbe beträgt 70:100.

### Percent75 {#Percent75}
```
public static final int Percent75
```


Gibt ein 75‑Prozent‑Schraffurmuster an. Das Verhältnis von Vordergrundfarbe zu Hintergrundfarbe beträgt 75:100.

### Percent80 {#Percent80}
```
public static final int Percent80
```


Gibt ein 80‑Prozent‑Schraffurmuster an. Das Verhältnis von Vordergrundfarbe zu Hintergrundfarbe beträgt 80:100.

### Percent90 {#Percent90}
```
public static final int Percent90
```


Gibt ein 90‑Prozent‑Schraffurmuster an. Das Verhältnis von Vordergrundfarbe zu Hintergrundfarbe beträgt 90:100.

### LightDownwardDiagonal {#LightDownwardDiagonal}
```
public static final int LightDownwardDiagonal
```


Gibt diagonale Linien an, die von den oberen Punkten zu den unteren Punkten nach rechts geneigt sind und 50 Prozent dichter beabstandet sind als `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, jedoch nicht antialiasiert sind.

### LightUpwardDiagonal {#LightUpwardDiagonal}
```
public static final int LightUpwardDiagonal
```


Gibt diagonale Linien an, die von den oberen Punkten zu den unteren Punkten nach links geneigt sind und 50 Prozent dichter beabstandet sind als `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, jedoch nicht antialiasiert sind.

### DarkDownwardDiagonal {#DarkDownwardDiagonal}
```
public static final int DarkDownwardDiagonal
```


Gibt diagonale Linien an, die von den oberen Punkten zu den unteren Punkten nach rechts geneigt sind, 50 Prozent dichter beieinander liegen als `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal` und doppelt so breit sind. Dieses Schraffurmuster ist nicht antialiasiert.

### DarkUpwardDiagonal {#DarkUpwardDiagonal}
```
public static final int DarkUpwardDiagonal
```


Gibt diagonale Linien an, die von den oberen Punkten zu den unteren Punkten nach links geneigt sind, 50 Prozent dichter beabstandet sind als `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal` und doppelt so breit wie diese, jedoch sind die Linien nicht antialiasiert.

### WideDownwardDiagonal {#WideDownwardDiagonal}
```
public static final int WideDownwardDiagonal
```


Gibt diagonale Linien an, die von den oberen Punkten zu den unteren Punkten nach rechts geneigt sind, denselben Abstand wie Schraffurstil `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal` haben und dreimal so breit sind, jedoch nicht antialiasiert sind.

### WideUpwardDiagonal {#WideUpwardDiagonal}
```
public static final int WideUpwardDiagonal
```


Gibt diagonale Linien an, die von den oberen Punkten zu den unteren Punkten nach links geneigt sind, denselben Abstand wie Schraffurstil `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal` haben und dreimal so breit sind, jedoch nicht antialiasiert sind.

### LightVertical {#LightVertical}
```
public static final int LightVertical
```


Gibt vertikale Linien an, die 50 Prozent dichter beabstandet sind als `System.Drawing.drawing2d.HatchStyle.Vertical`.

### LightHorizontal {#LightHorizontal}
```
public static final int LightHorizontal
```


Gibt horizontale Linien an, die 50 Prozent dichter beabstandet sind als `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### NarrowVertical {#NarrowVertical}
```
public static final int NarrowVertical
```


Gibt vertikale Linien an, die 75 Prozent dichter beabstandet sind als Schraffurstil `System.Drawing.drawing2d.HatchStyle.Vertical` (oder 25 Prozent dichter als `System.Drawing.drawing2d.HatchStyle.LightVertical`).

### NarrowHorizontal {#NarrowHorizontal}
```
public static final int NarrowHorizontal
```


Gibt horizontale Linien an, die 75 Prozent dichter beieinander liegen als der Hatch-Stil `System.Drawing.drawing2d.HatchStyle.Horizontal` (oder 25 Prozent dichter als `System.Drawing.drawing2d.HatchStyle.LightHorizontal`).

### DarkVertical {#DarkVertical}
```
public static final int DarkVertical
```


Gibt vertikale Linien an, die 50 Prozent dichter beieinander liegen als `System.Drawing.drawing2d.HatchStyle.Vertical` und doppelt so breit sind.

### DarkHorizontal {#DarkHorizontal}
```
public static final int DarkHorizontal
```


Gibt horizontale Linien an, die 50 Prozent dichter beieinander liegen als `System.Drawing.drawing2d.HatchStyle.Horizontal` und doppelt so breit sind wie `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### DashedDownwardDiagonal {#DashedDownwardDiagonal}
```
public static final int DashedDownwardDiagonal
```


Gibt gestrichelte diagonale Linien an, die von den oberen Punkten zu den unteren Punkten nach rechts verlaufen.

### DashedUpwardDiagonal {#DashedUpwardDiagonal}
```
public static final int DashedUpwardDiagonal
```


Gibt gestrichelte diagonale Linien an, die von den oberen Punkten zu den unteren Punkten nach links verlaufen.

### DashedHorizontal {#DashedHorizontal}
```
public static final int DashedHorizontal
```


Gibt gestrichelte horizontale Linien an.

### DashedVertical {#DashedVertical}
```
public static final int DashedVertical
```


Gibt gestrichelte vertikale Linien an.

### SmallConfetti {#SmallConfetti}
```
public static final int SmallConfetti
```


Gibt eine Schraffur an, die das Aussehen von Konfetti hat.

### LargeConfetti {#LargeConfetti}
```
public static final int LargeConfetti
```


Gibt eine Schraffur an, die das Aussehen von Konfetti hat und aus größeren Stücken besteht als `System.Drawing.drawing2d.HatchStyle.SmallConfetti`.

### ZigZag {#ZigZag}
```
public static final int ZigZag
```


Gibt horizontale Linien an, die aus Zickzacklinien bestehen.

### Wave {#Wave}
```
public static final int Wave
```


Gibt horizontale Linien an, die aus Tilden bestehen.

### DiagonalBrick {#DiagonalBrick}
```
public static final int DiagonalBrick
```


Gibt eine Schraffur an, die das Aussehen von geschichteten Ziegeln hat, die von den oberen Punkten zu den unteren Punkten nach links geneigt sind.

### HorizontalBrick {#HorizontalBrick}
```
public static final int HorizontalBrick
```


Gibt eine Schraffur an, die das Aussehen von horizontal geschichteten Ziegeln hat.

### Weave {#Weave}
```
public static final int Weave
```


Gibt eine Schraffur an, die das Aussehen eines gewebten Materials hat.

### Plaid {#Plaid}
```
public static final int Plaid
```


Gibt eine Schraffur an, die das Aussehen eines Karomusters hat.

### Divot {#Divot}
```
public static final int Divot
```


Gibt eine Schraffur an, die das Aussehen von Dellen hat.

### DottedGrid {#DottedGrid}
```
public static final int DottedGrid
```


Gibt horizontale und vertikale Linien an, die jeweils aus Punkten bestehen und sich kreuzen.

### DottedDiamond {#DottedDiamond}
```
public static final int DottedDiamond
```


Gibt vorwärts gerichtete diagonale und rückwärts gerichtete diagonale Linien an, die jeweils aus Punkten bestehen und sich kreuzen.

### Shingle {#Shingle}
```
public static final int Shingle
```


Gibt eine Schraffur an, die das Aussehen von diagonal geschichteten Schindeln hat, die von den oberen Punkten zu den unteren Punkten nach rechts geneigt sind.

### Trellis {#Trellis}
```
public static final int Trellis
```


Gibt eine Schraffur an, die das Aussehen eines Spaliers hat.

### Sphere {#Sphere}
```
public static final int Sphere
```


Gibt eine Schraffur an, die das Aussehen von nebeneinander liegenden Kugeln hat.

### SmallGrid {#SmallGrid}
```
public static final int SmallGrid
```


Gibt horizontale und vertikale Linien an, die sich kreuzen und 50 Prozent dichter beieinander liegen als der Hatch-Stil `System.Drawing.drawing2d.HatchStyle.Cross`.

### SmallCheckerBoard {#SmallCheckerBoard}
```
public static final int SmallCheckerBoard
```


Gibt eine Schraffur an, die das Aussehen eines Schachbretts hat.

### LargeCheckerBoard {#LargeCheckerBoard}
```
public static final int LargeCheckerBoard
```


Gibt eine Schraffur an, die das Aussehen eines Schachbretts mit Feldern hat, die doppelt so groß sind wie `System.Drawing.drawing2d.HatchStyle.SmallCheckerBoard`.

### OutlinedDiamond {#OutlinedDiamond}
```
public static final int OutlinedDiamond
```


Gibt vorwärts gerichtete diagonale und rückwärts gerichtete diagonale Linien an, die sich kreuzen, aber nicht antialiasiert sind.

### SolidDiamond {#SolidDiamond}
```
public static final int SolidDiamond
```


Gibt ein Schraffurmuster an, das das Aussehen eines diagonal platzierten Schachbretts hat.

### LargeGrid {#LargeGrid}
```
public static final int LargeGrid
```


Gibt den Schraffurstil `System.Drawing.drawing2d.HatchStyle.Cross` an.

### Min {#Min}
```
public static final int Min
```


Gibt den Schraffurstil `System.Drawing.drawing2d.HatchStyle.Horizontal` an.

### Max {#Max}
```
public static final int Max
```


Gibt den Schraffurstil `System.Drawing.drawing2d.HatchStyle.SolidDiamond` an.

