---
title: HatchStyle
second_title: Aspose.Drawing för Java API‑referens
description: Anger de olika mönstren som finns tillgängliga för objekt.
type: docs
weight: 27
url: /sv/java/com.aspose.drawing.drawing2d/hatchstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HatchStyle extends System.Enum
```

Anger de olika mönstren som finns tillgängliga för [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush)-objekt.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Horizontal](#Horizontal) | Ett mönster av horisontella linjer. |
| [Vertical](#Vertical) | Ett mönster av vertikala linjer. |
| [ForwardDiagonal](#ForwardDiagonal) | Ett mönster av linjer på en diagonal från övre vänster till nedre höger. |
| [BackwardDiagonal](#BackwardDiagonal) | Ett mönster av linjer på en diagonal från övre höger till nedre vänster. |
| [Cross](#Cross) | Anger horisontella och vertikala linjer som korsar. |
| [DiagonalCross](#DiagonalCross) | Ett mönster av korsande diagonala linjer. |
| [Percent05](#Percent05) | Anger ett 5-procentshack. |
| [Percent10](#Percent10) | Anger ett 10-procentshack. |
| [Percent20](#Percent20) | Anger ett 20-procentshack. |
| [Percent25](#Percent25) | Anger ett 25-procentshack. |
| [Percent30](#Percent30) | Anger ett 30-procentshack. |
| [Percent40](#Percent40) | Anger ett 40-procentshack. |
| [Percent50](#Percent50) | Anger ett 50-procentshack. |
| [Percent60](#Percent60) | Anger ett 60-procentshack. |
| [Percent70](#Percent70) | Anger ett 70-procentshack. |
| [Percent75](#Percent75) | Anger ett 75-procentshack. |
| [Percent80](#Percent80) | Anger ett 80-procentshack. |
| [Percent90](#Percent90) | Anger ett 90-procentshack. |
| [LightDownwardDiagonal](#LightDownwardDiagonal) | Anger diagonala linjer som lutar åt höger från toppunkter till bottenpunkter och är placerade 50 procent närmare varandra än `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, men som inte är antialiasade. |
| [LightUpwardDiagonal](#LightUpwardDiagonal) | Anger diagonala linjer som lutar åt vänster från toppunkter till bottenpunkter och är placerade 50 procent närmare varandra än `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, men de är inte antialiasade. |
| [DarkDownwardDiagonal](#DarkDownwardDiagonal) | Anger diagonala linjer som lutar åt höger från toppunkter till bottenpunkter, är placerade 50 procent närmare varandra än, och är dubbelt så breda som `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`. |
| [DarkUpwardDiagonal](#DarkUpwardDiagonal) | Anger diagonala linjer som lutar åt vänster från toppunkter till bottenpunkter, är placerade 50 procent närmare varandra än `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, och är dubbelt så breda som den, men linjerna är inte antialiasade. |
| [WideDownwardDiagonal](#WideDownwardDiagonal) | Anger diagonala linjer som lutar åt höger från toppunkter till bottenpunkter, har samma avstånd som hatch-stilen `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, och är tre gånger så breda som den, men är inte antialiasade. |
| [WideUpwardDiagonal](#WideUpwardDiagonal) | Anger diagonala linjer som lutar åt vänster från toppunkter till bottenpunkter, har samma avstånd som hatch-stilen `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, och är tre gånger så breda som den, men är inte antialiasade. |
| [LightVertical](#LightVertical) | Anger vertikala linjer som är placerade 50 procent närmare varandra än `System.Drawing.drawing2d.HatchStyle.Vertical`. |
| [LightHorizontal](#LightHorizontal) | Anger horisontella linjer som är placerade 50 procent närmare varandra än `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [NarrowVertical](#NarrowVertical) | Anger vertikala linjer som är placerade 75 procent närmare varandra än hatch-stilen `System.Drawing.drawing2d.HatchStyle.Vertical` (eller 25 procent närmare varandra än `System.Drawing.drawing2d.HatchStyle.LightVertical`). |
| [NarrowHorizontal](#NarrowHorizontal) | Anger horisontella linjer som är placerade 75 procent närmare varandra än hatch‑stilen `System.Drawing.drawing2d.HatchStyle.Horizontal` (eller 25 procent närmare varandra än `System.Drawing.drawing2d.HatchStyle.LightHorizontal`). |
| [DarkVertical](#DarkVertical) | Anger vertikala linjer som är placerade 50 procent närmare varandra än `System.Drawing.drawing2d.HatchStyle.Vertical` och är dubbelt så breda som den. |
| [DarkHorizontal](#DarkHorizontal) | Anger horisontella linjer som är placerade 50 procent närmare varandra än `System.Drawing.drawing2d.HatchStyle.Horizontal` och är dubbelt så breda som `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [DashedDownwardDiagonal](#DashedDownwardDiagonal) | Anger streckade diagonala linjer som lutar åt höger från övre punkter till nedre punkter. |
| [DashedUpwardDiagonal](#DashedUpwardDiagonal) | Anger streckade diagonala linjer som lutar åt vänster från övre punkter till nedre punkter. |
| [DashedHorizontal](#DashedHorizontal) | Anger streckade horisontella linjer. |
| [DashedVertical](#DashedVertical) | Anger streckade vertikala linjer. |
| [SmallConfetti](#SmallConfetti) | Anger ett mönster som ser ut som konfetti. |
| [LargeConfetti](#LargeConfetti) | Anger ett mönster som ser ut som konfetti och som består av större bitar än `System.Drawing.drawing2d.HatchStyle.SmallConfetti`. |
| [ZigZag](#ZigZag) | Anger horisontella linjer som består av zickzack. |
| [Wave](#Wave) | Anger horisontella linjer som består av tilde-tecken. |
| [DiagonalBrick](#DiagonalBrick) | Anger ett mönster som ser ut som lager av tegel som lutar åt vänster från övre punkter till nedre punkter. |
| [HorizontalBrick](#HorizontalBrick) | Anger ett mönster som ser ut som horisontellt lager av tegel. |
| [Weave](#Weave) | Anger ett mönster som ser ut som ett vävt material. |
| [Plaid](#Plaid) | Anger ett mönster som ser ut som ett rutigt material. |
| [Divot](#Divot) | Anger ett mönster som ser ut som fördjupningar. |
| [DottedGrid](#DottedGrid) | Anger horisontella och vertikala linjer, var och en bestående av prickar, som korsar varandra. |
| [DottedDiamond](#DottedDiamond) | Anger framåtlutande och bakåtlutande diagonala linjer, var och en bestående av prickar, som korsar varandra. |
| [Shingle](#Shingle) | Anger ett mönster som ser ut som diagonalt lager av takpannor som lutar åt höger från övre punkter till nedre punkter. |
| [Trellis](#Trellis) | Anger ett mönster som ser ut som ett spaljé. |
| [Sphere](#Sphere) | Anger ett mönster som ser ut som sfärer placerade intill varandra. |
| [SmallGrid](#SmallGrid) | Anger horisontella och vertikala linjer som korsar varandra och är placerade 50 procent närmare varandra än hatch‑stilen `System.Drawing.drawing2d.HatchStyle.Cross`. |
| [SmallCheckerBoard](#SmallCheckerBoard) | Anger ett mönster som ser ut som ett schackbräde. |
| [LargeCheckerBoard](#LargeCheckerBoard) | Anger ett mönster som ser ut som ett schackbräde med rutor som är dubbelt så stora som `System.Drawing.drawing2d.HatchStyle.SmallCheckerBoard`. |
| [OutlinedDiamond](#OutlinedDiamond) | Anger framåtlutande och bakåtlutande diagonala linjer som korsar varandra men som inte är kantutjämnade. |
| [SolidDiamond](#SolidDiamond) | Anger en skraffering som har utseendet av ett schackbräde placerat diagonalt. |
| [LargeGrid](#LargeGrid) | Anger skrafferingstilen `System.Drawing.drawing2d.HatchStyle.Cross`. |
| [Min](#Min) | Anger skrafferingstilen `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [Max](#Max) | Anger skrafferingstilen `System.Drawing.drawing2d.HatchStyle.SolidDiamond`. |
### Horizontal {#Horizontal}
```
public static final int Horizontal
```


Ett mönster av horisontella linjer.

### Vertical {#Vertical}
```
public static final int Vertical
```


Ett mönster av vertikala linjer.

### ForwardDiagonal {#ForwardDiagonal}
```
public static final int ForwardDiagonal
```


Ett mönster av linjer på en diagonal från övre vänster till nedre höger.

### BackwardDiagonal {#BackwardDiagonal}
```
public static final int BackwardDiagonal
```


Ett mönster av linjer på en diagonal från övre höger till nedre vänster.

### Cross {#Cross}
```
public static final int Cross
```


Anger horisontella och vertikala linjer som korsar.

### DiagonalCross {#DiagonalCross}
```
public static final int DiagonalCross
```


Ett mönster av korsande diagonala linjer.

### Percent05 {#Percent05}
```
public static final int Percent05
```


Anger en 5-procentig skraffering. Förhållandet mellan förgrundsfärg och bakgrundsfärg är 5:100.

### Percent10 {#Percent10}
```
public static final int Percent10
```


Anger en 10-procentig skraffering. Förhållandet mellan förgrundsfärg och bakgrundsfärg är 10:100.

### Percent20 {#Percent20}
```
public static final int Percent20
```


Anger en 20-procentig skraffering. Förhållandet mellan förgrundsfärg och bakgrundsfärg är 20:100.

### Percent25 {#Percent25}
```
public static final int Percent25
```


Anger en 25-procentig skraffering. Förhållandet mellan förgrundsfärg och bakgrundsfärg är 25:100.

### Percent30 {#Percent30}
```
public static final int Percent30
```


Anger en 30-procentig skraffering. Förhållandet mellan förgrundsfärg och bakgrundsfärg är 30:100.

### Percent40 {#Percent40}
```
public static final int Percent40
```


Anger en 40-procentig skraffering. Förhållandet mellan förgrundsfärg och bakgrundsfärg är 40:100.

### Percent50 {#Percent50}
```
public static final int Percent50
```


Anger en 50-procentig skraffering. Förhållandet mellan förgrundsfärg och bakgrundsfärg är 50:100.

### Percent60 {#Percent60}
```
public static final int Percent60
```


Anger en 60-procentig skraffering. Förhållandet mellan förgrundsfärg och bakgrundsfärg är 60:100.

### Percent70 {#Percent70}
```
public static final int Percent70
```


Anger en 70-procentig skraffering. Förhållandet mellan förgrundsfärg och bakgrundsfärg är 70:100.

### Percent75 {#Percent75}
```
public static final int Percent75
```


Anger en 75-procentig skraffering. Förhållandet mellan förgrundsfärg och bakgrundsfärg är 75:100.

### Percent80 {#Percent80}
```
public static final int Percent80
```


Anger en 80-procentig skraffering. Förhållandet mellan förgrundsfärg och bakgrundsfärg är 80:100.

### Percent90 {#Percent90}
```
public static final int Percent90
```


Anger en 90-procentig skraffering. Förhållandet mellan förgrundsfärg och bakgrundsfärg är 90:100.

### LightDownwardDiagonal {#LightDownwardDiagonal}
```
public static final int LightDownwardDiagonal
```


Anger diagonala linjer som lutar åt höger från toppunkter till bottenpunkter och är placerade 50 procent närmare varandra än `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, men som inte är antialiasade.

### LightUpwardDiagonal {#LightUpwardDiagonal}
```
public static final int LightUpwardDiagonal
```


Anger diagonala linjer som lutar åt vänster från toppunkter till bottenpunkter och är placerade 50 procent närmare varandra än `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, men de är inte antialiasade.

### DarkDownwardDiagonal {#DarkDownwardDiagonal}
```
public static final int DarkDownwardDiagonal
```


Anger diagonala linjer som lutar åt höger från övre punkter till nedre punkter, är placerade 50 procent närmare varandra än `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, och är dubbelt så breda som den. Detta skraffermönster är inte kantutjämnat.

### DarkUpwardDiagonal {#DarkUpwardDiagonal}
```
public static final int DarkUpwardDiagonal
```


Anger diagonala linjer som lutar åt vänster från toppunkter till bottenpunkter, är placerade 50 procent närmare varandra än `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, och är dubbelt så breda som den, men linjerna är inte antialiasade.

### WideDownwardDiagonal {#WideDownwardDiagonal}
```
public static final int WideDownwardDiagonal
```


Anger diagonala linjer som lutar åt höger från toppunkter till bottenpunkter, har samma avstånd som hatch-stilen `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, och är tre gånger så breda som den, men är inte antialiasade.

### WideUpwardDiagonal {#WideUpwardDiagonal}
```
public static final int WideUpwardDiagonal
```


Anger diagonala linjer som lutar åt vänster från toppunkter till bottenpunkter, har samma avstånd som hatch-stilen `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, och är tre gånger så breda som den, men är inte antialiasade.

### LightVertical {#LightVertical}
```
public static final int LightVertical
```


Anger vertikala linjer som är placerade 50 procent närmare varandra än `System.Drawing.drawing2d.HatchStyle.Vertical`.

### LightHorizontal {#LightHorizontal}
```
public static final int LightHorizontal
```


Anger horisontella linjer som är placerade 50 procent närmare varandra än `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### NarrowVertical {#NarrowVertical}
```
public static final int NarrowVertical
```


Anger vertikala linjer som är placerade 75 procent närmare varandra än hatch-stilen `System.Drawing.drawing2d.HatchStyle.Vertical` (eller 25 procent närmare varandra än `System.Drawing.drawing2d.HatchStyle.LightVertical`).

### NarrowHorizontal {#NarrowHorizontal}
```
public static final int NarrowHorizontal
```


Anger horisontella linjer som är placerade 75 procent närmare varandra än hatch‑stilen `System.Drawing.drawing2d.HatchStyle.Horizontal` (eller 25 procent närmare varandra än `System.Drawing.drawing2d.HatchStyle.LightHorizontal`).

### DarkVertical {#DarkVertical}
```
public static final int DarkVertical
```


Anger vertikala linjer som är placerade 50 procent närmare varandra än `System.Drawing.drawing2d.HatchStyle.Vertical` och är dubbelt så breda som den.

### DarkHorizontal {#DarkHorizontal}
```
public static final int DarkHorizontal
```


Anger horisontella linjer som är placerade 50 procent närmare varandra än `System.Drawing.drawing2d.HatchStyle.Horizontal` och är dubbelt så breda som `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### DashedDownwardDiagonal {#DashedDownwardDiagonal}
```
public static final int DashedDownwardDiagonal
```


Anger streckade diagonala linjer som lutar åt höger från övre punkter till nedre punkter.

### DashedUpwardDiagonal {#DashedUpwardDiagonal}
```
public static final int DashedUpwardDiagonal
```


Anger streckade diagonala linjer som lutar åt vänster från övre punkter till nedre punkter.

### DashedHorizontal {#DashedHorizontal}
```
public static final int DashedHorizontal
```


Anger streckade horisontella linjer.

### DashedVertical {#DashedVertical}
```
public static final int DashedVertical
```


Anger streckade vertikala linjer.

### SmallConfetti {#SmallConfetti}
```
public static final int SmallConfetti
```


Anger ett mönster som ser ut som konfetti.

### LargeConfetti {#LargeConfetti}
```
public static final int LargeConfetti
```


Anger ett mönster som ser ut som konfetti och som består av större bitar än `System.Drawing.drawing2d.HatchStyle.SmallConfetti`.

### ZigZag {#ZigZag}
```
public static final int ZigZag
```


Anger horisontella linjer som består av zickzack.

### Wave {#Wave}
```
public static final int Wave
```


Anger horisontella linjer som består av tilde-tecken.

### DiagonalBrick {#DiagonalBrick}
```
public static final int DiagonalBrick
```


Anger ett mönster som ser ut som lager av tegel som lutar åt vänster från övre punkter till nedre punkter.

### HorizontalBrick {#HorizontalBrick}
```
public static final int HorizontalBrick
```


Anger ett mönster som ser ut som horisontellt lager av tegel.

### Weave {#Weave}
```
public static final int Weave
```


Anger ett mönster som ser ut som ett vävt material.

### Plaid {#Plaid}
```
public static final int Plaid
```


Anger ett mönster som ser ut som ett rutigt material.

### Divot {#Divot}
```
public static final int Divot
```


Anger ett mönster som ser ut som fördjupningar.

### DottedGrid {#DottedGrid}
```
public static final int DottedGrid
```


Anger horisontella och vertikala linjer, var och en bestående av prickar, som korsar varandra.

### DottedDiamond {#DottedDiamond}
```
public static final int DottedDiamond
```


Anger framåtlutande och bakåtlutande diagonala linjer, var och en bestående av prickar, som korsar varandra.

### Shingle {#Shingle}
```
public static final int Shingle
```


Anger ett mönster som ser ut som diagonalt lager av takpannor som lutar åt höger från övre punkter till nedre punkter.

### Trellis {#Trellis}
```
public static final int Trellis
```


Anger ett mönster som ser ut som ett spaljé.

### Sphere {#Sphere}
```
public static final int Sphere
```


Anger ett mönster som ser ut som sfärer placerade intill varandra.

### SmallGrid {#SmallGrid}
```
public static final int SmallGrid
```


Anger horisontella och vertikala linjer som korsar varandra och är placerade 50 procent närmare varandra än hatch‑stilen `System.Drawing.drawing2d.HatchStyle.Cross`.

### SmallCheckerBoard {#SmallCheckerBoard}
```
public static final int SmallCheckerBoard
```


Anger ett mönster som ser ut som ett schackbräde.

### LargeCheckerBoard {#LargeCheckerBoard}
```
public static final int LargeCheckerBoard
```


Anger ett mönster som ser ut som ett schackbräde med rutor som är dubbelt så stora som `System.Drawing.drawing2d.HatchStyle.SmallCheckerBoard`.

### OutlinedDiamond {#OutlinedDiamond}
```
public static final int OutlinedDiamond
```


Anger framåtlutande och bakåtlutande diagonala linjer som korsar varandra men som inte är kantutjämnade.

### SolidDiamond {#SolidDiamond}
```
public static final int SolidDiamond
```


Anger en skraffering som har utseendet av ett schackbräde placerat diagonalt.

### LargeGrid {#LargeGrid}
```
public static final int LargeGrid
```


Anger skrafferingstilen `System.Drawing.drawing2d.HatchStyle.Cross`.

### Min {#Min}
```
public static final int Min
```


Anger skrafferingstilen `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### Max {#Max}
```
public static final int Max
```


Anger skrafferingstilen `System.Drawing.drawing2d.HatchStyle.SolidDiamond`.

