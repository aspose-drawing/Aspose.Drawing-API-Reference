---
title: HatchStyle
second_title: Referencia de la API de Aspose.Drawing para Java
description: Especifica los diferentes patrones disponibles para objetos.
type: docs
weight: 27
url: /es/java/com.aspose.drawing.drawing2d/hatchstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HatchStyle extends System.Enum
```

Especifica los diferentes patrones disponibles para objetos [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).
## Campos

| Campo | Descripción |
| --- | --- |
| [Horizontal](#Horizontal) | Un patrón de líneas horizontales. |
| [Vertical](#Vertical) | Un patrón de líneas verticales. |
| [ForwardDiagonal](#ForwardDiagonal) | Un patrón de líneas en diagonal desde la esquina superior izquierda hasta la esquina inferior derecha. |
| [BackwardDiagonal](#BackwardDiagonal) | Un patrón de líneas en diagonal desde la esquina superior derecha hasta la esquina inferior izquierda. |
| [Cross](#Cross) | Especifica líneas horizontales y verticales que se cruzan. |
| [DiagonalCross](#DiagonalCross) | Un patrón de líneas diagonales entrecruzadas. |
| [Percent05](#Percent05) | Especifica un tramado del 5 por ciento. |
| [Percent10](#Percent10) | Especifica un tramado del 10 por ciento. |
| [Percent20](#Percent20) | Especifica un tramado del 20 por ciento. |
| [Percent25](#Percent25) | Especifica un tramado del 25 por ciento. |
| [Percent30](#Percent30) | Especifica un tramado del 30 por ciento. |
| [Percent40](#Percent40) | Especifica un tramado del 40 por ciento. |
| [Percent50](#Percent50) | Especifica un tramado del 50 por ciento. |
| [Percent60](#Percent60) | Especifica un tramado del 60 por ciento. |
| [Percent70](#Percent70) | Especifica un tramado del 70 por ciento. |
| [Percent75](#Percent75) | Especifica un tramado del 75 por ciento. |
| [Percent80](#Percent80) | Especifica un tramado del 80 por ciento. |
| [Percent90](#Percent90) | Especifica un tramado del 90 por ciento. |
| [LightDownwardDiagonal](#LightDownwardDiagonal) | Especifica líneas diagonales que se inclinan a la derecha desde los puntos superiores a los puntos inferiores y están espaciadas un 50 por ciento más cerca que `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, pero no están antialiasadas. |
| [LightUpwardDiagonal](#LightUpwardDiagonal) | Especifica líneas diagonales que se inclinan a la izquierda desde los puntos superiores a los puntos inferiores y están espaciadas un 50 por ciento más cerca que `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, pero no están antialiasadas. |
| [DarkDownwardDiagonal](#DarkDownwardDiagonal) | Especifica líneas diagonales que se inclinan a la derecha desde los puntos superiores a los puntos inferiores, están espaciadas un 50 por ciento más cerca y tienen el doble de ancho que `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`. |
| [DarkUpwardDiagonal](#DarkUpwardDiagonal) | Especifica líneas diagonales que se inclinan a la izquierda desde los puntos superiores a los puntos inferiores, están espaciadas un 50 por ciento más cerca que `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal` y tienen el doble de ancho, pero las líneas no están antialiasadas. |
| [WideDownwardDiagonal](#WideDownwardDiagonal) | Especifica líneas diagonales que se inclinan a la derecha desde los puntos superiores a los puntos inferiores, tienen el mismo espaciado que el estilo de tramado `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal` y son triple de su ancho, pero no están antialiasadas. |
| [WideUpwardDiagonal](#WideUpwardDiagonal) | Especifica líneas diagonales que se inclinan a la izquierda desde los puntos superiores a los puntos inferiores, tienen el mismo espaciado que el estilo de tramado `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal` y son triple de su ancho, pero no están antialiasadas. |
| [LightVertical](#LightVertical) | Especifica líneas verticales que están espaciadas un 50 por ciento más cerca que `System.Drawing.drawing2d.HatchStyle.Vertical`. |
| [LightHorizontal](#LightHorizontal) | Especifica líneas horizontales que están espaciadas un 50 por ciento más cerca que `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [NarrowVertical](#NarrowVertical) | Especifica líneas verticales que están espaciadas un 75 por ciento más cerca que el estilo de tramado `System.Drawing.drawing2d.HatchStyle.Vertical` (o un 25 por ciento más cerca que `System.Drawing.drawing2d.HatchStyle.LightVertical`). |
| [NarrowHorizontal](#NarrowHorizontal) | Especifica líneas horizontales que están espaciadas un 75 % más cerca que el estilo de trama `System.Drawing.drawing2d.HatchStyle.Horizontal` (o un 25 % más cerca que `System.Drawing.drawing2d.HatchStyle.LightHorizontal`). |
| [DarkVertical](#DarkVertical) | Especifica líneas verticales que están espaciadas un 50 % más cerca que `System.Drawing.drawing2d.HatchStyle.Vertical` y tienen el doble de su ancho. |
| [DarkHorizontal](#DarkHorizontal) | Especifica líneas horizontales que están espaciadas un 50 % más cerca que `System.Drawing.drawing2d.HatchStyle.Horizontal` y tienen el doble del ancho de `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [DashedDownwardDiagonal](#DashedDownwardDiagonal) | Especifica líneas diagonales discontinuas que se inclinan a la derecha desde los puntos superiores hasta los puntos inferiores. |
| [DashedUpwardDiagonal](#DashedUpwardDiagonal) | Especifica líneas diagonales discontinuas que se inclinan a la izquierda desde los puntos superiores hasta los puntos inferiores. |
| [DashedHorizontal](#DashedHorizontal) | Especifica líneas horizontales discontinuas. |
| [DashedVertical](#DashedVertical) | Especifica líneas verticales discontinuas. |
| [SmallConfetti](#SmallConfetti) | Especifica una trama que tiene la apariencia de confeti. |
| [LargeConfetti](#LargeConfetti) | Especifica una trama que tiene la apariencia de confeti y está compuesta por piezas más grandes que `System.Drawing.drawing2d.HatchStyle.SmallConfetti`. |
| [ZigZag](#ZigZag) | Especifica líneas horizontales compuestas de zigzags. |
| [Wave](#Wave) | Especifica líneas horizontales compuestas de tildes. |
| [DiagonalBrick](#DiagonalBrick) | Especifica una trama que tiene la apariencia de ladrillos en capas que se inclinan a la izquierda desde los puntos superiores hasta los puntos inferiores. |
| [HorizontalBrick](#HorizontalBrick) | Especifica una trama que tiene la apariencia de ladrillos en capas horizontales. |
| [Weave](#Weave) | Especifica una trama que tiene la apariencia de un material tejido. |
| [Plaid](#Plaid) | Especifica una trama que tiene la apariencia de un material a cuadros. |
| [Divot](#Divot) | Especifica una trama que tiene la apariencia de huecos. |
| [DottedGrid](#DottedGrid) | Especifica líneas horizontales y verticales, cada una compuesta de puntos, que se cruzan. |
| [DottedDiamond](#DottedDiamond) | Especifica líneas diagonales hacia adelante y hacia atrás, cada una compuesta de puntos, que se cruzan. |
| [Shingle](#Shingle) | Especifica una trama que tiene la apariencia de tejas en capas diagonales que se inclinan a la derecha desde los puntos superiores hasta los puntos inferiores. |
| [Trellis](#Trellis) | Especifica una trama que tiene la apariencia de una celosía. |
| [Sphere](#Sphere) | Especifica una trama que tiene la apariencia de esferas colocadas una al lado de la otra. |
| [SmallGrid](#SmallGrid) | Especifica líneas horizontales y verticales que se cruzan y están espaciadas un 50 % más cerca que el estilo de trama `System.Drawing.drawing2d.HatchStyle.Cross`. |
| [SmallCheckerBoard](#SmallCheckerBoard) | Especifica una trama que tiene la apariencia de un tablero de ajedrez. |
| [LargeCheckerBoard](#LargeCheckerBoard) | Especifica una trama que tiene la apariencia de un tablero de ajedrez con casillas que son el doble del tamaño de `System.Drawing.drawing2d.HatchStyle.SmallCheckerBoard`. |
| [OutlinedDiamond](#OutlinedDiamond) | Especifica líneas diagonales hacia adelante y hacia atrás que se cruzan pero no están antialiasadas. |
| [SolidDiamond](#SolidDiamond) | Especifica una trama que tiene la apariencia de un tablero de ajedrez colocado diagonalmente. |
| [LargeGrid](#LargeGrid) | Especifica el estilo de trama `System.Drawing.drawing2d.HatchStyle.Cross`. |
| [Min](#Min) | Especifica el estilo de trama `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [Max](#Max) | Especifica el estilo de trama `System.Drawing.drawing2d.HatchStyle.SolidDiamond`. |
### Horizontal {#Horizontal}
```
public static final int Horizontal
```


Un patrón de líneas horizontales.

### Vertical {#Vertical}
```
public static final int Vertical
```


Un patrón de líneas verticales.

### ForwardDiagonal {#ForwardDiagonal}
```
public static final int ForwardDiagonal
```


Un patrón de líneas en diagonal desde la esquina superior izquierda hasta la esquina inferior derecha.

### BackwardDiagonal {#BackwardDiagonal}
```
public static final int BackwardDiagonal
```


Un patrón de líneas en diagonal desde la esquina superior derecha hasta la esquina inferior izquierda.

### Cross {#Cross}
```
public static final int Cross
```


Especifica líneas horizontales y verticales que se cruzan.

### DiagonalCross {#DiagonalCross}
```
public static final int DiagonalCross
```


Un patrón de líneas diagonales entrecruzadas.

### Percent05 {#Percent05}
```
public static final int Percent05
```


Especifica una trama del 5 por ciento. La proporción del color de primer plano al color de fondo es 5:100.

### Percent10 {#Percent10}
```
public static final int Percent10
```


Especifica una trama del 10 por ciento. La proporción del color de primer plano al color de fondo es 10:100.

### Percent20 {#Percent20}
```
public static final int Percent20
```


Especifica una trama del 20 por ciento. La proporción del color de primer plano al color de fondo es 20:100.

### Percent25 {#Percent25}
```
public static final int Percent25
```


Especifica una trama del 25 por ciento. La proporción del color de primer plano al color de fondo es 25:100.

### Percent30 {#Percent30}
```
public static final int Percent30
```


Especifica una trama del 30 por ciento. La proporción del color de primer plano al color de fondo es 30:100.

### Percent40 {#Percent40}
```
public static final int Percent40
```


Especifica una trama del 40 por ciento. La proporción del color de primer plano al color de fondo es 40:100.

### Percent50 {#Percent50}
```
public static final int Percent50
```


Especifica una trama del 50 por ciento. La proporción del color de primer plano al color de fondo es 50:100.

### Percent60 {#Percent60}
```
public static final int Percent60
```


Especifica una trama del 60 por ciento. La proporción del color de primer plano al color de fondo es 60:100.

### Percent70 {#Percent70}
```
public static final int Percent70
```


Especifica una trama del 70 por ciento. La proporción del color de primer plano al color de fondo es 70:100.

### Percent75 {#Percent75}
```
public static final int Percent75
```


Especifica una trama del 75 por ciento. La proporción del color de primer plano al color de fondo es 75:100.

### Percent80 {#Percent80}
```
public static final int Percent80
```


Especifica una trama del 80 por ciento. La proporción del color de primer plano al color de fondo es 80:100.

### Percent90 {#Percent90}
```
public static final int Percent90
```


Especifica una trama del 90 por ciento. La proporción del color de primer plano al color de fondo es 90:100.

### LightDownwardDiagonal {#LightDownwardDiagonal}
```
public static final int LightDownwardDiagonal
```


Especifica líneas diagonales que se inclinan a la derecha desde los puntos superiores a los puntos inferiores y están espaciadas un 50 por ciento más cerca que `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, pero no están antialiasadas.

### LightUpwardDiagonal {#LightUpwardDiagonal}
```
public static final int LightUpwardDiagonal
```


Especifica líneas diagonales que se inclinan a la izquierda desde los puntos superiores a los puntos inferiores y están espaciadas un 50 por ciento más cerca que `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, pero no están antialiasadas.

### DarkDownwardDiagonal {#DarkDownwardDiagonal}
```
public static final int DarkDownwardDiagonal
```


Especifica líneas diagonales que se inclinan a la derecha desde los puntos superiores a los puntos inferiores, están espaciadas un 50 por ciento más cerca y tienen el doble de ancho que `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`. Este patrón de trama no está antialiasado.

### DarkUpwardDiagonal {#DarkUpwardDiagonal}
```
public static final int DarkUpwardDiagonal
```


Especifica líneas diagonales que se inclinan a la izquierda desde los puntos superiores a los puntos inferiores, están espaciadas un 50 por ciento más cerca que `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal` y tienen el doble de ancho, pero las líneas no están antialiasadas.

### WideDownwardDiagonal {#WideDownwardDiagonal}
```
public static final int WideDownwardDiagonal
```


Especifica líneas diagonales que se inclinan a la derecha desde los puntos superiores a los puntos inferiores, tienen el mismo espaciado que el estilo de tramado `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal` y son triple de su ancho, pero no están antialiasadas.

### WideUpwardDiagonal {#WideUpwardDiagonal}
```
public static final int WideUpwardDiagonal
```


Especifica líneas diagonales que se inclinan a la izquierda desde los puntos superiores a los puntos inferiores, tienen el mismo espaciado que el estilo de tramado `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal` y son triple de su ancho, pero no están antialiasadas.

### LightVertical {#LightVertical}
```
public static final int LightVertical
```


Especifica líneas verticales que están espaciadas un 50 por ciento más cerca que `System.Drawing.drawing2d.HatchStyle.Vertical`.

### LightHorizontal {#LightHorizontal}
```
public static final int LightHorizontal
```


Especifica líneas horizontales que están espaciadas un 50 por ciento más cerca que `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### NarrowVertical {#NarrowVertical}
```
public static final int NarrowVertical
```


Especifica líneas verticales que están espaciadas un 75 por ciento más cerca que el estilo de tramado `System.Drawing.drawing2d.HatchStyle.Vertical` (o un 25 por ciento más cerca que `System.Drawing.drawing2d.HatchStyle.LightVertical`).

### NarrowHorizontal {#NarrowHorizontal}
```
public static final int NarrowHorizontal
```


Especifica líneas horizontales que están espaciadas un 75 % más cerca que el estilo de trama `System.Drawing.drawing2d.HatchStyle.Horizontal` (o un 25 % más cerca que `System.Drawing.drawing2d.HatchStyle.LightHorizontal`).

### DarkVertical {#DarkVertical}
```
public static final int DarkVertical
```


Especifica líneas verticales que están espaciadas un 50 % más cerca que `System.Drawing.drawing2d.HatchStyle.Vertical` y tienen el doble de su ancho.

### DarkHorizontal {#DarkHorizontal}
```
public static final int DarkHorizontal
```


Especifica líneas horizontales que están espaciadas un 50 % más cerca que `System.Drawing.drawing2d.HatchStyle.Horizontal` y tienen el doble del ancho de `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### DashedDownwardDiagonal {#DashedDownwardDiagonal}
```
public static final int DashedDownwardDiagonal
```


Especifica líneas diagonales discontinuas que se inclinan a la derecha desde los puntos superiores hasta los puntos inferiores.

### DashedUpwardDiagonal {#DashedUpwardDiagonal}
```
public static final int DashedUpwardDiagonal
```


Especifica líneas diagonales discontinuas que se inclinan a la izquierda desde los puntos superiores hasta los puntos inferiores.

### DashedHorizontal {#DashedHorizontal}
```
public static final int DashedHorizontal
```


Especifica líneas horizontales discontinuas.

### DashedVertical {#DashedVertical}
```
public static final int DashedVertical
```


Especifica líneas verticales discontinuas.

### SmallConfetti {#SmallConfetti}
```
public static final int SmallConfetti
```


Especifica una trama que tiene la apariencia de confeti.

### LargeConfetti {#LargeConfetti}
```
public static final int LargeConfetti
```


Especifica una trama que tiene la apariencia de confeti y está compuesta por piezas más grandes que `System.Drawing.drawing2d.HatchStyle.SmallConfetti`.

### ZigZag {#ZigZag}
```
public static final int ZigZag
```


Especifica líneas horizontales compuestas de zigzags.

### Wave {#Wave}
```
public static final int Wave
```


Especifica líneas horizontales compuestas de tildes.

### DiagonalBrick {#DiagonalBrick}
```
public static final int DiagonalBrick
```


Especifica una trama que tiene la apariencia de ladrillos en capas que se inclinan a la izquierda desde los puntos superiores hasta los puntos inferiores.

### HorizontalBrick {#HorizontalBrick}
```
public static final int HorizontalBrick
```


Especifica una trama que tiene la apariencia de ladrillos en capas horizontales.

### Weave {#Weave}
```
public static final int Weave
```


Especifica una trama que tiene la apariencia de un material tejido.

### Plaid {#Plaid}
```
public static final int Plaid
```


Especifica una trama que tiene la apariencia de un material a cuadros.

### Divot {#Divot}
```
public static final int Divot
```


Especifica una trama que tiene la apariencia de huecos.

### DottedGrid {#DottedGrid}
```
public static final int DottedGrid
```


Especifica líneas horizontales y verticales, cada una compuesta de puntos, que se cruzan.

### DottedDiamond {#DottedDiamond}
```
public static final int DottedDiamond
```


Especifica líneas diagonales hacia adelante y hacia atrás, cada una compuesta de puntos, que se cruzan.

### Shingle {#Shingle}
```
public static final int Shingle
```


Especifica una trama que tiene la apariencia de tejas en capas diagonales que se inclinan a la derecha desde los puntos superiores hasta los puntos inferiores.

### Trellis {#Trellis}
```
public static final int Trellis
```


Especifica una trama que tiene la apariencia de una celosía.

### Sphere {#Sphere}
```
public static final int Sphere
```


Especifica una trama que tiene la apariencia de esferas colocadas una al lado de la otra.

### SmallGrid {#SmallGrid}
```
public static final int SmallGrid
```


Especifica líneas horizontales y verticales que se cruzan y están espaciadas un 50 % más cerca que el estilo de trama `System.Drawing.drawing2d.HatchStyle.Cross`.

### SmallCheckerBoard {#SmallCheckerBoard}
```
public static final int SmallCheckerBoard
```


Especifica una trama que tiene la apariencia de un tablero de ajedrez.

### LargeCheckerBoard {#LargeCheckerBoard}
```
public static final int LargeCheckerBoard
```


Especifica una trama que tiene la apariencia de un tablero de ajedrez con casillas que son el doble del tamaño de `System.Drawing.drawing2d.HatchStyle.SmallCheckerBoard`.

### OutlinedDiamond {#OutlinedDiamond}
```
public static final int OutlinedDiamond
```


Especifica líneas diagonales hacia adelante y hacia atrás que se cruzan pero no están antialiasadas.

### SolidDiamond {#SolidDiamond}
```
public static final int SolidDiamond
```


Especifica una trama que tiene la apariencia de un tablero de ajedrez colocado diagonalmente.

### LargeGrid {#LargeGrid}
```
public static final int LargeGrid
```


Especifica el estilo de trama `System.Drawing.drawing2d.HatchStyle.Cross`.

### Min {#Min}
```
public static final int Min
```


Especifica el estilo de trama `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### Max {#Max}
```
public static final int Max
```


Especifica el estilo de trama `System.Drawing.drawing2d.HatchStyle.SolidDiamond`.

