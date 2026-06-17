---
title: HatchStyle
second_title: Riferimento API di Aspose.Drawing per Java
description: Specifica i diversi motivi disponibili per gli oggetti.
type: docs
weight: 27
url: /it/java/com.aspose.drawing.drawing2d/hatchstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HatchStyle extends System.Enum
```

Specifica i diversi motivi disponibili per gli oggetti [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).
## Campi

| Campo | Descrizione |
| --- | --- |
| [Horizontal](#Horizontal) | Un motivo di linee orizzontali. |
| [Vertical](#Vertical) | Un motivo di linee verticali. |
| [ForwardDiagonal](#ForwardDiagonal) | Un motivo di linee su una diagonale dall'angolo superiore sinistro a quello inferiore destro. |
| [BackwardDiagonal](#BackwardDiagonal) | Un motivo di linee su una diagonale dall'angolo superiore destro a quello inferiore sinistro. |
| [Cross](#Cross) | Specifica linee orizzontali e verticali che si incrociano. |
| [DiagonalCross](#DiagonalCross) | Un motivo di linee diagonali incrociate. |
| [Percent05](#Percent05) | Specifica una trama del 5%. |
| [Percent10](#Percent10) | Specifica una trama del 10%. |
| [Percent20](#Percent20) | Specifica una trama del 20%. |
| [Percent25](#Percent25) | Specifica una trama del 25%. |
| [Percent30](#Percent30) | Specifica una trama del 30%. |
| [Percent40](#Percent40) | Specifica una trama del 40%. |
| [Percent50](#Percent50) | Specifica una trama del 50%. |
| [Percent60](#Percent60) | Specifica una trama del 60%. |
| [Percent70](#Percent70) | Specifica una trama del 70%. |
| [Percent75](#Percent75) | Specifica una trama del 75%. |
| [Percent80](#Percent80) | Specifica una trama del 80%. |
| [Percent90](#Percent90) | Specifica una trama del 90%. |
| [LightDownwardDiagonal](#LightDownwardDiagonal) | Specifica linee diagonali che si inclinano verso destra dai punti superiori a quelli inferiori e sono distanziate del 50 percento più vicino rispetto a `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, ma non sono antialiasate. |
| [LightUpwardDiagonal](#LightUpwardDiagonal) | Specifica linee diagonali che si inclinano verso sinistra dai punti superiori a quelli inferiori e sono distanziate del 50 percento più vicino rispetto a `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, ma non sono antialiasate. |
| [DarkDownwardDiagonal](#DarkDownwardDiagonal) | Specifica linee diagonali che si inclinano verso destra dai punti superiori a quelli inferiori, sono distanziate del 50 percento più vicino rispetto a `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal` e hanno il doppio della larghezza di `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`. |
| [DarkUpwardDiagonal](#DarkUpwardDiagonal) | Specifica linee diagonali che si inclinano verso sinistra dai punti superiori a quelli inferiori, sono distanziate del 50 percento più vicino rispetto a `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal` e hanno il doppio della sua larghezza, ma le linee non sono antialiasate. |
| [WideDownwardDiagonal](#WideDownwardDiagonal) | Specifica linee diagonali che si inclinano verso destra dai punti superiori a quelli inferiori, hanno la stessa spaziatura dello stile di trama `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal` e sono tre volte la sua larghezza, ma non sono antialiasate. |
| [WideUpwardDiagonal](#WideUpwardDiagonal) | Specifica linee diagonali che si inclinano verso sinistra dai punti superiori a quelli inferiori, hanno la stessa spaziatura dello stile di trama `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal` e sono tre volte la sua larghezza, ma non sono antialiasate. |
| [LightVertical](#LightVertical) | Specifica linee verticali che sono distanziate del 50 percento più vicino rispetto a `System.Drawing.drawing2d.HatchStyle.Vertical`. |
| [LightHorizontal](#LightHorizontal) | Specifica linee orizzontali che sono distanziate del 50 percento più vicino rispetto a `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [NarrowVertical](#NarrowVertical) | Specifica linee verticali che sono distanziate del 75 percento più vicino rispetto allo stile di trama `System.Drawing.drawing2d.HatchStyle.Vertical` (o del 25 percento più vicino rispetto a `System.Drawing.drawing2d.HatchStyle.LightVertical`). |
| [NarrowHorizontal](#NarrowHorizontal) | Specifica linee orizzontali che sono più vicine del 75 percento rispetto allo stile di tratteggio `System.Drawing.drawing2d.HatchStyle.Horizontal` (o del 25 percento più vicine rispetto a `System.Drawing.drawing2d.HatchStyle.LightHorizontal`). |
| [DarkVertical](#DarkVertical) | Specifica linee verticali che sono più vicine del 50 percento rispetto a `System.Drawing.drawing2d.HatchStyle.Vertical` e hanno il doppio della sua larghezza. |
| [DarkHorizontal](#DarkHorizontal) | Specifica linee orizzontali che sono più vicine del 50 percento rispetto a `System.Drawing.drawing2d.HatchStyle.Horizontal` e hanno il doppio della larghezza di `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [DashedDownwardDiagonal](#DashedDownwardDiagonal) | Specifica linee diagonali tratteggiate, inclinate verso destra dal punto superiore al punto inferiore. |
| [DashedUpwardDiagonal](#DashedUpwardDiagonal) | Specifica linee diagonali tratteggiate, inclinate verso sinistra dal punto superiore al punto inferiore. |
| [DashedHorizontal](#DashedHorizontal) | Specifica linee orizzontali tratteggiate. |
| [DashedVertical](#DashedVertical) | Specifica linee verticali tratteggiate. |
| [SmallConfetti](#SmallConfetti) | Specifica un tratteggio che ha l'aspetto di confetti. |
| [LargeConfetti](#LargeConfetti) | Specifica un tratteggio che ha l'aspetto di confetti e è composto da pezzi più grandi rispetto a `System.Drawing.drawing2d.HatchStyle.SmallConfetti`. |
| [ZigZag](#ZigZag) | Specifica linee orizzontali composte da zigzag. |
| [Wave](#Wave) | Specifica linee orizzontali composte da tilde. |
| [DiagonalBrick](#DiagonalBrick) | Specifica un tratteggio che ha l'aspetto di mattoni a strati inclinati verso sinistra dal punto superiore al punto inferiore. |
| [HorizontalBrick](#HorizontalBrick) | Specifica un tratteggio che ha l'aspetto di mattoni a strati orizzontali. |
| [Weave](#Weave) | Specifica un tratteggio che ha l'aspetto di un materiale intrecciato. |
| [Plaid](#Plaid) | Specifica un tratteggio che ha l'aspetto di un materiale a quadri. |
| [Divot](#Divot) | Specifica un tratteggio che ha l'aspetto di incavi. |
| [DottedGrid](#DottedGrid) | Specifica linee orizzontali e verticali, ciascuna composta da punti, che si incrociano. |
| [DottedDiamond](#DottedDiamond) | Specifica linee diagonali in avanti e indietro, ciascuna composta da punti, che si incrociano. |
| [Shingle](#Shingle) | Specifica un tratteggio che ha l'aspetto di tegole a strati diagonali inclinate verso destra dal punto superiore al punto inferiore. |
| [Trellis](#Trellis) | Specifica un tratteggio che ha l'aspetto di una grata. |
| [Sphere](#Sphere) | Specifica un tratteggio che ha l'aspetto di sfere disposte adiacenti tra loro. |
| [SmallGrid](#SmallGrid) | Specifica linee orizzontali e verticali che si incrociano e sono più vicine del 50 percento rispetto allo stile di tratteggio `System.Drawing.drawing2d.HatchStyle.Cross`. |
| [SmallCheckerBoard](#SmallCheckerBoard) | Specifica un tratteggio che ha l'aspetto di una scacchiera. |
| [LargeCheckerBoard](#LargeCheckerBoard) | Specifica un tratteggio che ha l'aspetto di una scacchiera con quadrati il doppio della dimensione di `System.Drawing.drawing2d.HatchStyle.SmallCheckerBoard`. |
| [OutlinedDiamond](#OutlinedDiamond) | Specifica linee diagonali in avanti e indietro che si incrociano ma non sono antialiasate. |
| [SolidDiamond](#SolidDiamond) | Specifica un motivo a trama che ha l'aspetto di una scacchiera posizionata diagonalmente. |
| [LargeGrid](#LargeGrid) | Specifica lo stile di trama `System.Drawing.drawing2d.HatchStyle.Cross`. |
| [Min](#Min) | Specifica lo stile di trama `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [Max](#Max) | Specifica lo stile di trama `System.Drawing.drawing2d.HatchStyle.SolidDiamond`. |
### Horizontal {#Horizontal}
```
public static final int Horizontal
```


Un motivo di linee orizzontali.

### Vertical {#Vertical}
```
public static final int Vertical
```


Un motivo di linee verticali.

### ForwardDiagonal {#ForwardDiagonal}
```
public static final int ForwardDiagonal
```


Un motivo di linee su una diagonale dall'angolo superiore sinistro a quello inferiore destro.

### BackwardDiagonal {#BackwardDiagonal}
```
public static final int BackwardDiagonal
```


Un motivo di linee su una diagonale dall'angolo superiore destro a quello inferiore sinistro.

### Cross {#Cross}
```
public static final int Cross
```


Specifica linee orizzontali e verticali che si incrociano.

### DiagonalCross {#DiagonalCross}
```
public static final int DiagonalCross
```


Un motivo di linee diagonali incrociate.

### Percent05 {#Percent05}
```
public static final int Percent05
```


Specifica una trama al 5%. Il rapporto tra il colore di primo piano e quello di sfondo è 5:100.

### Percent10 {#Percent10}
```
public static final int Percent10
```


Specifica una trama al 10%. Il rapporto tra il colore di primo piano e quello di sfondo è 10:100.

### Percent20 {#Percent20}
```
public static final int Percent20
```


Specifica una trama al 20%. Il rapporto tra il colore di primo piano e quello di sfondo è 20:100.

### Percent25 {#Percent25}
```
public static final int Percent25
```


Specifica una trama al 25%. Il rapporto tra il colore di primo piano e quello di sfondo è 25:100.

### Percent30 {#Percent30}
```
public static final int Percent30
```


Specifica una trama al 30%. Il rapporto tra il colore di primo piano e quello di sfondo è 30:100.

### Percent40 {#Percent40}
```
public static final int Percent40
```


Specifica una trama al 40%. Il rapporto tra il colore di primo piano e quello di sfondo è 40:100.

### Percent50 {#Percent50}
```
public static final int Percent50
```


Specifica una trama al 50%. Il rapporto tra il colore di primo piano e quello di sfondo è 50:100.

### Percent60 {#Percent60}
```
public static final int Percent60
```


Specifica una trama al 60%. Il rapporto tra il colore di primo piano e quello di sfondo è 60:100.

### Percent70 {#Percent70}
```
public static final int Percent70
```


Specifica una trama al 70%. Il rapporto tra il colore di primo piano e quello di sfondo è 70:100.

### Percent75 {#Percent75}
```
public static final int Percent75
```


Specifica una trama al 75%. Il rapporto tra il colore di primo piano e quello di sfondo è 75:100.

### Percent80 {#Percent80}
```
public static final int Percent80
```


Specifica una trama al 80%. Il rapporto tra il colore di primo piano e quello di sfondo è 80:100.

### Percent90 {#Percent90}
```
public static final int Percent90
```


Specifica una trama al 90%. Il rapporto tra il colore di primo piano e quello di sfondo è 90:100.

### LightDownwardDiagonal {#LightDownwardDiagonal}
```
public static final int LightDownwardDiagonal
```


Specifica linee diagonali che si inclinano verso destra dai punti superiori a quelli inferiori e sono distanziate del 50 percento più vicino rispetto a `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, ma non sono antialiasate.

### LightUpwardDiagonal {#LightUpwardDiagonal}
```
public static final int LightUpwardDiagonal
```


Specifica linee diagonali che si inclinano verso sinistra dai punti superiori a quelli inferiori e sono distanziate del 50 percento più vicino rispetto a `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, ma non sono antialiasate.

### DarkDownwardDiagonal {#DarkDownwardDiagonal}
```
public static final int DarkDownwardDiagonal
```


Specifica linee diagonali che pendono verso destra dai punti superiori a quelli inferiori, sono distanziate del 50% più vicine rispetto a, e hanno il doppio della larghezza di `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`. Questo motivo a trama non è antialiasato.

### DarkUpwardDiagonal {#DarkUpwardDiagonal}
```
public static final int DarkUpwardDiagonal
```


Specifica linee diagonali che si inclinano verso sinistra dai punti superiori a quelli inferiori, sono distanziate del 50 percento più vicino rispetto a `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal` e hanno il doppio della sua larghezza, ma le linee non sono antialiasate.

### WideDownwardDiagonal {#WideDownwardDiagonal}
```
public static final int WideDownwardDiagonal
```


Specifica linee diagonali che si inclinano verso destra dai punti superiori a quelli inferiori, hanno la stessa spaziatura dello stile di trama `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal` e sono tre volte la sua larghezza, ma non sono antialiasate.

### WideUpwardDiagonal {#WideUpwardDiagonal}
```
public static final int WideUpwardDiagonal
```


Specifica linee diagonali che si inclinano verso sinistra dai punti superiori a quelli inferiori, hanno la stessa spaziatura dello stile di trama `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal` e sono tre volte la sua larghezza, ma non sono antialiasate.

### LightVertical {#LightVertical}
```
public static final int LightVertical
```


Specifica linee verticali che sono distanziate del 50 percento più vicino rispetto a `System.Drawing.drawing2d.HatchStyle.Vertical`.

### LightHorizontal {#LightHorizontal}
```
public static final int LightHorizontal
```


Specifica linee orizzontali che sono distanziate del 50 percento più vicino rispetto a `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### NarrowVertical {#NarrowVertical}
```
public static final int NarrowVertical
```


Specifica linee verticali che sono distanziate del 75 percento più vicino rispetto allo stile di trama `System.Drawing.drawing2d.HatchStyle.Vertical` (o del 25 percento più vicino rispetto a `System.Drawing.drawing2d.HatchStyle.LightVertical`).

### NarrowHorizontal {#NarrowHorizontal}
```
public static final int NarrowHorizontal
```


Specifica linee orizzontali che sono più vicine del 75 percento rispetto allo stile di tratteggio `System.Drawing.drawing2d.HatchStyle.Horizontal` (o del 25 percento più vicine rispetto a `System.Drawing.drawing2d.HatchStyle.LightHorizontal`).

### DarkVertical {#DarkVertical}
```
public static final int DarkVertical
```


Specifica linee verticali che sono più vicine del 50 percento rispetto a `System.Drawing.drawing2d.HatchStyle.Vertical` e hanno il doppio della sua larghezza.

### DarkHorizontal {#DarkHorizontal}
```
public static final int DarkHorizontal
```


Specifica linee orizzontali che sono più vicine del 50 percento rispetto a `System.Drawing.drawing2d.HatchStyle.Horizontal` e hanno il doppio della larghezza di `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### DashedDownwardDiagonal {#DashedDownwardDiagonal}
```
public static final int DashedDownwardDiagonal
```


Specifica linee diagonali tratteggiate, inclinate verso destra dal punto superiore al punto inferiore.

### DashedUpwardDiagonal {#DashedUpwardDiagonal}
```
public static final int DashedUpwardDiagonal
```


Specifica linee diagonali tratteggiate, inclinate verso sinistra dal punto superiore al punto inferiore.

### DashedHorizontal {#DashedHorizontal}
```
public static final int DashedHorizontal
```


Specifica linee orizzontali tratteggiate.

### DashedVertical {#DashedVertical}
```
public static final int DashedVertical
```


Specifica linee verticali tratteggiate.

### SmallConfetti {#SmallConfetti}
```
public static final int SmallConfetti
```


Specifica un tratteggio che ha l'aspetto di confetti.

### LargeConfetti {#LargeConfetti}
```
public static final int LargeConfetti
```


Specifica un tratteggio che ha l'aspetto di confetti e è composto da pezzi più grandi rispetto a `System.Drawing.drawing2d.HatchStyle.SmallConfetti`.

### ZigZag {#ZigZag}
```
public static final int ZigZag
```


Specifica linee orizzontali composte da zigzag.

### Wave {#Wave}
```
public static final int Wave
```


Specifica linee orizzontali composte da tilde.

### DiagonalBrick {#DiagonalBrick}
```
public static final int DiagonalBrick
```


Specifica un tratteggio che ha l'aspetto di mattoni a strati inclinati verso sinistra dal punto superiore al punto inferiore.

### HorizontalBrick {#HorizontalBrick}
```
public static final int HorizontalBrick
```


Specifica un tratteggio che ha l'aspetto di mattoni a strati orizzontali.

### Weave {#Weave}
```
public static final int Weave
```


Specifica un tratteggio che ha l'aspetto di un materiale intrecciato.

### Plaid {#Plaid}
```
public static final int Plaid
```


Specifica un tratteggio che ha l'aspetto di un materiale a quadri.

### Divot {#Divot}
```
public static final int Divot
```


Specifica un tratteggio che ha l'aspetto di incavi.

### DottedGrid {#DottedGrid}
```
public static final int DottedGrid
```


Specifica linee orizzontali e verticali, ciascuna composta da punti, che si incrociano.

### DottedDiamond {#DottedDiamond}
```
public static final int DottedDiamond
```


Specifica linee diagonali in avanti e indietro, ciascuna composta da punti, che si incrociano.

### Shingle {#Shingle}
```
public static final int Shingle
```


Specifica un tratteggio che ha l'aspetto di tegole a strati diagonali inclinate verso destra dal punto superiore al punto inferiore.

### Trellis {#Trellis}
```
public static final int Trellis
```


Specifica un tratteggio che ha l'aspetto di una grata.

### Sphere {#Sphere}
```
public static final int Sphere
```


Specifica un tratteggio che ha l'aspetto di sfere disposte adiacenti tra loro.

### SmallGrid {#SmallGrid}
```
public static final int SmallGrid
```


Specifica linee orizzontali e verticali che si incrociano e sono più vicine del 50 percento rispetto allo stile di tratteggio `System.Drawing.drawing2d.HatchStyle.Cross`.

### SmallCheckerBoard {#SmallCheckerBoard}
```
public static final int SmallCheckerBoard
```


Specifica un tratteggio che ha l'aspetto di una scacchiera.

### LargeCheckerBoard {#LargeCheckerBoard}
```
public static final int LargeCheckerBoard
```


Specifica un tratteggio che ha l'aspetto di una scacchiera con quadrati il doppio della dimensione di `System.Drawing.drawing2d.HatchStyle.SmallCheckerBoard`.

### OutlinedDiamond {#OutlinedDiamond}
```
public static final int OutlinedDiamond
```


Specifica linee diagonali in avanti e indietro che si incrociano ma non sono antialiasate.

### SolidDiamond {#SolidDiamond}
```
public static final int SolidDiamond
```


Specifica un motivo a trama che ha l'aspetto di una scacchiera posizionata diagonalmente.

### LargeGrid {#LargeGrid}
```
public static final int LargeGrid
```


Specifica lo stile di trama `System.Drawing.drawing2d.HatchStyle.Cross`.

### Min {#Min}
```
public static final int Min
```


Specifica lo stile di trama `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### Max {#Max}
```
public static final int Max
```


Specifica lo stile di trama `System.Drawing.drawing2d.HatchStyle.SolidDiamond`.

