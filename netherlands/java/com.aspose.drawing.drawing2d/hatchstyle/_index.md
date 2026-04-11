---
title: HatchStyle
second_title: Aspose.Drawing voor Java API-referentie
description: Specificeert de verschillende patronen die beschikbaar zijn voor objecten.
type: docs
weight: 27
url: /nl/java/com.aspose.drawing.drawing2d/hatchstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HatchStyle extends System.Enum
```

Specificeert de verschillende patronen die beschikbaar zijn voor [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) objecten.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Horizontal](#Horizontal) | Een patroon van horizontale lijnen. |
| [Vertical](#Vertical) | Een patroon van verticale lijnen. |
| [ForwardDiagonal](#ForwardDiagonal) | Een patroon van lijnen diagonaal van linksboven naar rechtsonder. |
| [BackwardDiagonal](#BackwardDiagonal) | Een patroon van lijnen diagonaal van rechtsboven naar linksonder. |
| [Cross](#Cross) | Specificeert horizontale en verticale lijnen die kruisen. |
| [DiagonalCross](#DiagonalCross) | Een patroon van kruislings diagonale lijnen. |
| [Percent05](#Percent05) | Specificeert een 5-procent hatch. |
| [Percent10](#Percent10) | Specificeert een 10-procent hatch. |
| [Percent20](#Percent20) | Specificeert een 20-procent hatch. |
| [Percent25](#Percent25) | Specificeert een 25-procent hatch. |
| [Percent30](#Percent30) | Specificeert een 30-procent hatch. |
| [Percent40](#Percent40) | Specificeert een 40-procent hatch. |
| [Percent50](#Percent50) | Specificeert een 50-procent hatch. |
| [Percent60](#Percent60) | Specificeert een 60-procent hatch. |
| [Percent70](#Percent70) | Specificeert een 70-procent hatch. |
| [Percent75](#Percent75) | Specificeert een 75-procent hatch. |
| [Percent80](#Percent80) | Specificeert een 80-procent hatch. |
| [Percent90](#Percent90) | Specificeert een 90-procent hatch. |
| [LightDownwardDiagonal](#LightDownwardDiagonal) | Specificeert diagonale lijnen die naar rechts hellen van bovenste punten naar onderste punten en 50 procent dichter op elkaar staan dan `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, maar niet anti-aliased zijn. |
| [LightUpwardDiagonal](#LightUpwardDiagonal) | Specificeert diagonale lijnen die naar links hellen van bovenste punten naar onderste punten en 50 procent dichter op elkaar staan dan `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, maar ze zijn niet anti-aliased. |
| [DarkDownwardDiagonal](#DarkDownwardDiagonal) | Specificeert diagonale lijnen die naar rechts hellen van bovenste punten naar onderste punten, 50 procent dichter op elkaar staan dan `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, en twee keer zo breed zijn als `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`. |
| [DarkUpwardDiagonal](#DarkUpwardDiagonal) | Specificeert diagonale lijnen die naar links hellen van bovenste punten naar onderste punten, 50 procent dichter op elkaar staan dan `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, en twee keer zo breed zijn als deze, maar de lijnen zijn niet anti-aliased. |
| [WideDownwardDiagonal](#WideDownwardDiagonal) | Specificeert diagonale lijnen die naar rechts hellen van bovenste punten naar onderste punten, dezelfde afstand hebben als hatch‑stijl `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, en drie keer zo breed zijn als deze, maar zijn niet anti-aliased. |
| [WideUpwardDiagonal](#WideUpwardDiagonal) | Specificeert diagonale lijnen die naar links hellen van bovenste punten naar onderste punten, dezelfde afstand hebben als hatch‑stijl `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, en drie keer zo breed zijn als deze, maar zijn niet anti-aliased. |
| [LightVertical](#LightVertical) | Specificeert verticale lijnen die 50 procent dichter op elkaar staan dan `System.Drawing.drawing2d.HatchStyle.Vertical`. |
| [LightHorizontal](#LightHorizontal) | Specificeert horizontale lijnen die 50 procent dichter op elkaar staan dan `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [NarrowVertical](#NarrowVertical) | Specificeert verticale lijnen die 75 procent dichter op elkaar staan dan hatch‑stijl `System.Drawing.drawing2d.HatchStyle.Vertical` (of 25 procent dichter op elkaar dan `System.Drawing.drawing2d.HatchStyle.LightVertical`). |
| [NarrowHorizontal](#NarrowHorizontal) | Specificeert horizontale lijnen die 75 procent dichter op elkaar staan dan hatch-stijl `System.Drawing.drawing2d.HatchStyle.Horizontal` (of 25 procent dichter op elkaar dan `System.Drawing.drawing2d.HatchStyle.LightHorizontal`). |
| [DarkVertical](#DarkVertical) | Specificeert verticale lijnen die 50 procent dichter op elkaar staan dan `System.Drawing.drawing2d.HatchStyle.Vertical` en twee keer zo breed zijn. |
| [DarkHorizontal](#DarkHorizontal) | Specificeert horizontale lijnen die 50 procent dichter op elkaar staan dan `System.Drawing.drawing2d.HatchStyle.Horizontal` en twee keer de breedte hebben van `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [DashedDownwardDiagonal](#DashedDownwardDiagonal) | Specificeert gestippelde diagonale lijnen die naar rechts hellen van bovenste punten naar onderste punten. |
| [DashedUpwardDiagonal](#DashedUpwardDiagonal) | Specificeert gestippelde diagonale lijnen die naar links hellen van bovenste punten naar onderste punten. |
| [DashedHorizontal](#DashedHorizontal) | Specificeert gestippelde horizontale lijnen. |
| [DashedVertical](#DashedVertical) | Specificeert gestippelde verticale lijnen. |
| [SmallConfetti](#SmallConfetti) | Specificeert een hatch met het uiterlijk van confetti. |
| [LargeConfetti](#LargeConfetti) | Specificeert een hatch met het uiterlijk van confetti, en bestaat uit grotere stukjes dan `System.Drawing.drawing2d.HatchStyle.SmallConfetti`. |
| [ZigZag](#ZigZag) | Specificeert horizontale lijnen die bestaan uit zigzagpatronen. |
| [Wave](#Wave) | Specificeert horizontale lijnen die bestaan uit tildes. |
| [DiagonalBrick](#DiagonalBrick) | Specificeert een hatch met het uiterlijk van gelaagde bakstenen die naar links hellen van bovenste punten naar onderste punten. |
| [HorizontalBrick](#HorizontalBrick) | Specificeert een hatch met het uiterlijk van horizontaal gelaagde bakstenen. |
| [Weave](#Weave) | Specificeert een hatch met het uiterlijk van een geweven materiaal. |
| [Plaid](#Plaid) | Specificeert een hatch met het uiterlijk van een geruite stof. |
| [Divot](#Divot) | Specificeert een hatch met het uiterlijk van inkepingen. |
| [DottedGrid](#DottedGrid) | Specificeert horizontale en verticale lijnen, elk bestaande uit stippen, die kruisen. |
| [DottedDiamond](#DottedDiamond) | Specificeert voorwaartse diagonale en achterwaartse diagonale lijnen, elk bestaande uit stippen, die kruisen. |
| [Shingle](#Shingle) | Specificeert een hatch met het uiterlijk van diagonaal gelaagde dakpannen die naar rechts hellen van bovenste punten naar onderste punten. |
| [Trellis](#Trellis) | Specificeert een hatch met het uiterlijk van een latwerk. |
| [Sphere](#Sphere) | Specificeert een hatch met het uiterlijk van naast elkaar gelegde bollen. |
| [SmallGrid](#SmallGrid) | Specificeert horizontale en verticale lijnen die kruisen en 50 procent dichter op elkaar staan dan hatch-stijl `System.Drawing.drawing2d.HatchStyle.Cross`. |
| [SmallCheckerBoard](#SmallCheckerBoard) | Specificeert een hatch met het uiterlijk van een dambord. |
| [LargeCheckerBoard](#LargeCheckerBoard) | Specificeert een hatch met het uiterlijk van een dambord met vakjes die twee keer zo groot zijn als `System.Drawing.drawing2d.HatchStyle.SmallCheckerBoard`. |
| [OutlinedDiamond](#OutlinedDiamond) | Specificeert voorwaartse diagonale en achterwaartse diagonale lijnen die kruisen maar niet anti-aliased zijn. |
| [SolidDiamond](#SolidDiamond) | Specificeert een hatch die eruitziet als een schaakbord dat diagonaal is geplaatst. |
| [LargeGrid](#LargeGrid) | Specificeert de hatch-stijl `System.Drawing.drawing2d.HatchStyle.Cross`. |
| [Min](#Min) | Specificeert de hatch-stijl `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [Max](#Max) | Specificeert de hatch-stijl `System.Drawing.drawing2d.HatchStyle.SolidDiamond`. |
### Horizontal {#Horizontal}
```
public static final int Horizontal
```


Een patroon van horizontale lijnen.

### Vertical {#Vertical}
```
public static final int Vertical
```


Een patroon van verticale lijnen.

### ForwardDiagonal {#ForwardDiagonal}
```
public static final int ForwardDiagonal
```


Een patroon van lijnen diagonaal van linksboven naar rechtsonder.

### BackwardDiagonal {#BackwardDiagonal}
```
public static final int BackwardDiagonal
```


Een patroon van lijnen diagonaal van rechtsboven naar linksonder.

### Cross {#Cross}
```
public static final int Cross
```


Specificeert horizontale en verticale lijnen die kruisen.

### DiagonalCross {#DiagonalCross}
```
public static final int DiagonalCross
```


Een patroon van kruislings diagonale lijnen.

### Percent05 {#Percent05}
```
public static final int Percent05
```


Specificeert een hatch van 5 procent. De verhouding van voorgrondkleur tot achtergrondkleur is 5:100.

### Percent10 {#Percent10}
```
public static final int Percent10
```


Specificeert een hatch van 10 procent. De verhouding van voorgrondkleur tot achtergrondkleur is 10:100.

### Percent20 {#Percent20}
```
public static final int Percent20
```


Specificeert een hatch van 20 procent. De verhouding van voorgrondkleur tot achtergrondkleur is 20:100.

### Percent25 {#Percent25}
```
public static final int Percent25
```


Specificeert een hatch van 25 procent. De verhouding van voorgrondkleur tot achtergrondkleur is 25:100.

### Percent30 {#Percent30}
```
public static final int Percent30
```


Specificeert een hatch van 30 procent. De verhouding van voorgrondkleur tot achtergrondkleur is 30:100.

### Percent40 {#Percent40}
```
public static final int Percent40
```


Specificeert een hatch van 40 procent. De verhouding van voorgrondkleur tot achtergrondkleur is 40:100.

### Percent50 {#Percent50}
```
public static final int Percent50
```


Specificeert een hatch van 50 procent. De verhouding van voorgrondkleur tot achtergrondkleur is 50:100.

### Percent60 {#Percent60}
```
public static final int Percent60
```


Specificeert een hatch van 60 procent. De verhouding van voorgrondkleur tot achtergrondkleur is 60:100.

### Percent70 {#Percent70}
```
public static final int Percent70
```


Specificeert een hatch van 70 procent. De verhouding van voorgrondkleur tot achtergrondkleur is 70:100.

### Percent75 {#Percent75}
```
public static final int Percent75
```


Specificeert een hatch van 75 procent. De verhouding van voorgrondkleur tot achtergrondkleur is 75:100.

### Percent80 {#Percent80}
```
public static final int Percent80
```


Specificeert een hatch van 80 procent. De verhouding van voorgrondkleur tot achtergrondkleur is 80:100.

### Percent90 {#Percent90}
```
public static final int Percent90
```


Specificeert een hatch van 90 procent. De verhouding van voorgrondkleur tot achtergrondkleur is 90:100.

### LightDownwardDiagonal {#LightDownwardDiagonal}
```
public static final int LightDownwardDiagonal
```


Specificeert diagonale lijnen die naar rechts hellen van bovenste punten naar onderste punten en 50 procent dichter op elkaar staan dan `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, maar niet anti-aliased zijn.

### LightUpwardDiagonal {#LightUpwardDiagonal}
```
public static final int LightUpwardDiagonal
```


Specificeert diagonale lijnen die naar links hellen van bovenste punten naar onderste punten en 50 procent dichter op elkaar staan dan `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, maar ze zijn niet anti-aliased.

### DarkDownwardDiagonal {#DarkDownwardDiagonal}
```
public static final int DarkDownwardDiagonal
```


Specificeert diagonale lijnen die naar rechts hellen van bovenpunten naar onderpunten, staan 50 procent dichter bij elkaar dan, en hebben de dubbele breedte van `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`. Dit hatch-patroon is niet anti-aliased.

### DarkUpwardDiagonal {#DarkUpwardDiagonal}
```
public static final int DarkUpwardDiagonal
```


Specificeert diagonale lijnen die naar links hellen van bovenste punten naar onderste punten, 50 procent dichter op elkaar staan dan `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, en twee keer zo breed zijn als deze, maar de lijnen zijn niet anti-aliased.

### WideDownwardDiagonal {#WideDownwardDiagonal}
```
public static final int WideDownwardDiagonal
```


Specificeert diagonale lijnen die naar rechts hellen van bovenste punten naar onderste punten, dezelfde afstand hebben als hatch‑stijl `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, en drie keer zo breed zijn als deze, maar zijn niet anti-aliased.

### WideUpwardDiagonal {#WideUpwardDiagonal}
```
public static final int WideUpwardDiagonal
```


Specificeert diagonale lijnen die naar links hellen van bovenste punten naar onderste punten, dezelfde afstand hebben als hatch‑stijl `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, en drie keer zo breed zijn als deze, maar zijn niet anti-aliased.

### LightVertical {#LightVertical}
```
public static final int LightVertical
```


Specificeert verticale lijnen die 50 procent dichter op elkaar staan dan `System.Drawing.drawing2d.HatchStyle.Vertical`.

### LightHorizontal {#LightHorizontal}
```
public static final int LightHorizontal
```


Specificeert horizontale lijnen die 50 procent dichter op elkaar staan dan `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### NarrowVertical {#NarrowVertical}
```
public static final int NarrowVertical
```


Specificeert verticale lijnen die 75 procent dichter op elkaar staan dan hatch‑stijl `System.Drawing.drawing2d.HatchStyle.Vertical` (of 25 procent dichter op elkaar dan `System.Drawing.drawing2d.HatchStyle.LightVertical`).

### NarrowHorizontal {#NarrowHorizontal}
```
public static final int NarrowHorizontal
```


Specificeert horizontale lijnen die 75 procent dichter op elkaar staan dan hatch-stijl `System.Drawing.drawing2d.HatchStyle.Horizontal` (of 25 procent dichter op elkaar dan `System.Drawing.drawing2d.HatchStyle.LightHorizontal`).

### DarkVertical {#DarkVertical}
```
public static final int DarkVertical
```


Specificeert verticale lijnen die 50 procent dichter op elkaar staan dan `System.Drawing.drawing2d.HatchStyle.Vertical` en twee keer zo breed zijn.

### DarkHorizontal {#DarkHorizontal}
```
public static final int DarkHorizontal
```


Specificeert horizontale lijnen die 50 procent dichter op elkaar staan dan `System.Drawing.drawing2d.HatchStyle.Horizontal` en twee keer de breedte hebben van `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### DashedDownwardDiagonal {#DashedDownwardDiagonal}
```
public static final int DashedDownwardDiagonal
```


Specificeert gestippelde diagonale lijnen die naar rechts hellen van bovenste punten naar onderste punten.

### DashedUpwardDiagonal {#DashedUpwardDiagonal}
```
public static final int DashedUpwardDiagonal
```


Specificeert gestippelde diagonale lijnen die naar links hellen van bovenste punten naar onderste punten.

### DashedHorizontal {#DashedHorizontal}
```
public static final int DashedHorizontal
```


Specificeert gestippelde horizontale lijnen.

### DashedVertical {#DashedVertical}
```
public static final int DashedVertical
```


Specificeert gestippelde verticale lijnen.

### SmallConfetti {#SmallConfetti}
```
public static final int SmallConfetti
```


Specificeert een hatch met het uiterlijk van confetti.

### LargeConfetti {#LargeConfetti}
```
public static final int LargeConfetti
```


Specificeert een hatch met het uiterlijk van confetti, en bestaat uit grotere stukjes dan `System.Drawing.drawing2d.HatchStyle.SmallConfetti`.

### ZigZag {#ZigZag}
```
public static final int ZigZag
```


Specificeert horizontale lijnen die bestaan uit zigzagpatronen.

### Wave {#Wave}
```
public static final int Wave
```


Specificeert horizontale lijnen die bestaan uit tildes.

### DiagonalBrick {#DiagonalBrick}
```
public static final int DiagonalBrick
```


Specificeert een hatch met het uiterlijk van gelaagde bakstenen die naar links hellen van bovenste punten naar onderste punten.

### HorizontalBrick {#HorizontalBrick}
```
public static final int HorizontalBrick
```


Specificeert een hatch met het uiterlijk van horizontaal gelaagde bakstenen.

### Weave {#Weave}
```
public static final int Weave
```


Specificeert een hatch met het uiterlijk van een geweven materiaal.

### Plaid {#Plaid}
```
public static final int Plaid
```


Specificeert een hatch met het uiterlijk van een geruite stof.

### Divot {#Divot}
```
public static final int Divot
```


Specificeert een hatch met het uiterlijk van inkepingen.

### DottedGrid {#DottedGrid}
```
public static final int DottedGrid
```


Specificeert horizontale en verticale lijnen, elk bestaande uit stippen, die kruisen.

### DottedDiamond {#DottedDiamond}
```
public static final int DottedDiamond
```


Specificeert voorwaartse diagonale en achterwaartse diagonale lijnen, elk bestaande uit stippen, die kruisen.

### Shingle {#Shingle}
```
public static final int Shingle
```


Specificeert een hatch met het uiterlijk van diagonaal gelaagde dakpannen die naar rechts hellen van bovenste punten naar onderste punten.

### Trellis {#Trellis}
```
public static final int Trellis
```


Specificeert een hatch met het uiterlijk van een latwerk.

### Sphere {#Sphere}
```
public static final int Sphere
```


Specificeert een hatch met het uiterlijk van naast elkaar gelegde bollen.

### SmallGrid {#SmallGrid}
```
public static final int SmallGrid
```


Specificeert horizontale en verticale lijnen die kruisen en 50 procent dichter op elkaar staan dan hatch-stijl `System.Drawing.drawing2d.HatchStyle.Cross`.

### SmallCheckerBoard {#SmallCheckerBoard}
```
public static final int SmallCheckerBoard
```


Specificeert een hatch met het uiterlijk van een dambord.

### LargeCheckerBoard {#LargeCheckerBoard}
```
public static final int LargeCheckerBoard
```


Specificeert een hatch met het uiterlijk van een dambord met vakjes die twee keer zo groot zijn als `System.Drawing.drawing2d.HatchStyle.SmallCheckerBoard`.

### OutlinedDiamond {#OutlinedDiamond}
```
public static final int OutlinedDiamond
```


Specificeert voorwaartse diagonale en achterwaartse diagonale lijnen die kruisen maar niet anti-aliased zijn.

### SolidDiamond {#SolidDiamond}
```
public static final int SolidDiamond
```


Specificeert een hatch die eruitziet als een schaakbord dat diagonaal is geplaatst.

### LargeGrid {#LargeGrid}
```
public static final int LargeGrid
```


Specificeert de hatch-stijl `System.Drawing.drawing2d.HatchStyle.Cross`.

### Min {#Min}
```
public static final int Min
```


Specificeert de hatch-stijl `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### Max {#Max}
```
public static final int Max
```


Specificeert de hatch-stijl `System.Drawing.drawing2d.HatchStyle.SolidDiamond`.

