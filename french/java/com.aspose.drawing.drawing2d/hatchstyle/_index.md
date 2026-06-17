---
title: HatchStyle
second_title: Référence de l'API Aspose.Drawing pour Java
description: Spécifie les différents motifs disponibles pour les objets.
type: docs
weight: 27
url: /fr/java/com.aspose.drawing.drawing2d/hatchstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HatchStyle extends System.Enum
```

Spécifie les différents motifs disponibles pour les objets [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).
## Champs

| Champ | Description |
| --- | --- |
| [Horizontal](#Horizontal) | Un motif de lignes horizontales. |
| [Vertical](#Vertical) | Un motif de lignes verticales. |
| [ForwardDiagonal](#ForwardDiagonal) | Un motif de lignes en diagonale du coin supérieur gauche au coin inférieur droit. |
| [BackwardDiagonal](#BackwardDiagonal) | Un motif de lignes en diagonale du coin supérieur droit au coin inférieur gauche. |
| [Cross](#Cross) | Spécifie des lignes horizontales et verticales qui se croisent. |
| [DiagonalCross](#DiagonalCross) | Un motif de lignes diagonales en croix. |
| [Percent05](#Percent05) | Spécifie un hachurage à 5 %. |
| [Percent10](#Percent10) | Spécifie un hachurage à 10 %. |
| [Percent20](#Percent20) | Spécifie un hachurage à 20 %. |
| [Percent25](#Percent25) | Spécifie un hachurage à 25 %. |
| [Percent30](#Percent30) | Spécifie un hachurage à 30 %. |
| [Percent40](#Percent40) | Spécifie un hachurage à 40 %. |
| [Percent50](#Percent50) | Spécifie un hachurage à 50 %. |
| [Percent60](#Percent60) | Spécifie un hachurage à 60 %. |
| [Percent70](#Percent70) | Spécifie un hachurage à 70 %. |
| [Percent75](#Percent75) | Spécifie un hachurage à 75 %. |
| [Percent80](#Percent80) | Spécifie un hachurage à 80 %. |
| [Percent90](#Percent90) | Spécifie un hachurage à 90 %. |
| [LightDownwardDiagonal](#LightDownwardDiagonal) | Spécifie des lignes diagonales qui s’inclinent vers la droite des points supérieurs aux points inférieurs et sont espacées 50 % plus près les unes des autres que `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, mais ne sont pas antialiasées. |
| [LightUpwardDiagonal](#LightUpwardDiagonal) | Spécifie des lignes diagonales qui s’inclinent vers la gauche des points supérieurs aux points inférieurs et sont espacées 50 % plus près les unes des autres que `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, mais elles ne sont pas antialiasées. |
| [DarkDownwardDiagonal](#DarkDownwardDiagonal) | Spécifie des lignes diagonales qui s’inclinent vers la droite des points supérieurs aux points inférieurs, sont espacées 50 % plus près les unes des autres que, et ont le double de la largeur de `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`. |
| [DarkUpwardDiagonal](#DarkUpwardDiagonal) | Spécifie des lignes diagonales qui s’inclinent vers la gauche des points supérieurs aux points inférieurs, sont espacées 50 % plus près les unes des autres que `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, et ont le double de sa largeur, mais les lignes ne sont pas antialiasées. |
| [WideDownwardDiagonal](#WideDownwardDiagonal) | Spécifie des lignes diagonales qui s’inclinent vers la droite des points supérieurs aux points inférieurs, ont le même espacement que le style de hachure `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, et ont le triple de sa largeur, mais ne sont pas antialiasées. |
| [WideUpwardDiagonal](#WideUpwardDiagonal) | Spécifie des lignes diagonales qui s’inclinent vers la gauche des points supérieurs aux points inférieurs, ont le même espacement que le style de hachure `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, et ont le triple de sa largeur, mais ne sont pas antialiasées. |
| [LightVertical](#LightVertical) | Spécifie des lignes verticales qui sont espacées 50 % plus près les unes des autres que `System.Drawing.drawing2d.HatchStyle.Vertical`. |
| [LightHorizontal](#LightHorizontal) | Spécifie des lignes horizontales qui sont espacées 50 % plus près les unes des autres que `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [NarrowVertical](#NarrowVertical) | Spécifie des lignes verticales qui sont espacées 75 % plus près les unes des autres que le style de hachure `System.Drawing.drawing2d.HatchStyle.Vertical` (ou 25 % plus près les unes des autres que `System.Drawing.drawing2d.HatchStyle.LightVertical`). |
| [NarrowHorizontal](#NarrowHorizontal) | Spécifie des lignes horizontales espacées de 75 % plus proches les unes des autres que le style de hachure `System.Drawing.drawing2d.HatchStyle.Horizontal` (ou de 25 % plus proches que `System.Drawing.drawing2d.HatchStyle.LightHorizontal`). |
| [DarkVertical](#DarkVertical) | Spécifie des lignes verticales espacées de 50 % plus proches les unes des autres que `System.Drawing.drawing2d.HatchStyle.Vertical` et dont la largeur est le double. |
| [DarkHorizontal](#DarkHorizontal) | Spécifie des lignes horizontales espacées de 50 % plus proches les unes des autres que `System.Drawing.drawing2d.HatchStyle.Horizontal` et dont la largeur est le double de `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [DashedDownwardDiagonal](#DashedDownwardDiagonal) | Spécifie des lignes diagonales en pointillés, qui s’inclinent vers la droite du haut vers le bas. |
| [DashedUpwardDiagonal](#DashedUpwardDiagonal) | Spécifie des lignes diagonales en pointillés, qui s’inclinent vers la gauche du haut vers le bas. |
| [DashedHorizontal](#DashedHorizontal) | Spécifie des lignes horizontales en pointillés. |
| [DashedVertical](#DashedVertical) | Spécifie des lignes verticales en pointillés. |
| [SmallConfetti](#SmallConfetti) | Spécifie un hachurage qui a l’apparence de confettis. |
| [LargeConfetti](#LargeConfetti) | Spécifie un hachurage qui a l’apparence de confettis, et composé de pièces plus grandes que `System.Drawing.drawing2d.HatchStyle.SmallConfetti`. |
| [ZigZag](#ZigZag) | Spécifie des lignes horizontales composées de zigzags. |
| [Wave](#Wave) | Spécifie des lignes horizontales composées de tildes. |
| [DiagonalBrick](#DiagonalBrick) | Spécifie un hachurage qui a l’apparence de briques superposées s’inclinant vers la gauche du haut vers le bas. |
| [HorizontalBrick](#HorizontalBrick) | Spécifie un hachurage qui a l’apparence de briques superposées horizontalement. |
| [Weave](#Weave) | Spécifie un hachurage qui a l’apparence d’un matériau tissé. |
| [Plaid](#Plaid) | Spécifie un hachurage qui a l’apparence d’un tissu à carreaux. |
| [Divot](#Divot) | Spécifie un hachurage qui a l’apparence de fossettes. |
| [DottedGrid](#DottedGrid) | Spécifie des lignes horizontales et verticales, chacune composée de points, qui se croisent. |
| [DottedDiamond](#DottedDiamond) | Spécifie des lignes diagonales avant et arrière, chacune composée de points, qui se croisent. |
| [Shingle](#Shingle) | Spécifie un hachurage qui a l’apparence de bardeaux superposés en diagonale s’inclinant vers la droite du haut vers le bas. |
| [Trellis](#Trellis) | Spécifie un hachurage qui a l’apparence d’un treillis. |
| [Sphere](#Sphere) | Spécifie un hachurage qui a l’apparence de sphères disposées côte à côte. |
| [SmallGrid](#SmallGrid) | Spécifie des lignes horizontales et verticales qui se croisent et sont espacées de 50 % plus proches les unes des autres que le style de hachure `System.Drawing.drawing2d.HatchStyle.Cross`. |
| [SmallCheckerBoard](#SmallCheckerBoard) | Spécifie un hachurage qui a l’apparence d’un damier. |
| [LargeCheckerBoard](#LargeCheckerBoard) | Spécifie un hachurage qui a l’apparence d’un damier avec des carrés deux fois plus grands que `System.Drawing.drawing2d.HatchStyle.SmallCheckerBoard`. |
| [OutlinedDiamond](#OutlinedDiamond) | Spécifie des lignes diagonales avant et arrière qui se croisent mais ne sont pas antialiasées. |
| [SolidDiamond](#SolidDiamond) | Spécifie un hachurage qui a l'apparence d'un damier placé en diagonale. |
| [LargeGrid](#LargeGrid) | Spécifie le style de hachure `System.Drawing.drawing2d.HatchStyle.Cross`. |
| [Min](#Min) | Spécifie le style de hachure `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [Max](#Max) | Spécifie le style de hachure `System.Drawing.drawing2d.HatchStyle.SolidDiamond`. |
### Horizontal {#Horizontal}
```
public static final int Horizontal
```


Un motif de lignes horizontales.

### Vertical {#Vertical}
```
public static final int Vertical
```


Un motif de lignes verticales.

### ForwardDiagonal {#ForwardDiagonal}
```
public static final int ForwardDiagonal
```


Un motif de lignes en diagonale du coin supérieur gauche au coin inférieur droit.

### BackwardDiagonal {#BackwardDiagonal}
```
public static final int BackwardDiagonal
```


Un motif de lignes en diagonale du coin supérieur droit au coin inférieur gauche.

### Cross {#Cross}
```
public static final int Cross
```


Spécifie des lignes horizontales et verticales qui se croisent.

### DiagonalCross {#DiagonalCross}
```
public static final int DiagonalCross
```


Un motif de lignes diagonales en croix.

### Percent05 {#Percent05}
```
public static final int Percent05
```


Spécifie un hachurage à 5 % . Le rapport de la couleur de premier plan à la couleur d'arrière-plan est de 5 :100.

### Percent10 {#Percent10}
```
public static final int Percent10
```


Spécifie un hachurage à 10 % . Le rapport de la couleur de premier plan à la couleur d'arrière-plan est de 10 :100.

### Percent20 {#Percent20}
```
public static final int Percent20
```


Spécifie un hachurage à 20 % . Le rapport de la couleur de premier plan à la couleur d'arrière-plan est de 20 :100.

### Percent25 {#Percent25}
```
public static final int Percent25
```


Spécifie un hachurage à 25 % . Le rapport de la couleur de premier plan à la couleur d'arrière-plan est de 25 :100.

### Percent30 {#Percent30}
```
public static final int Percent30
```


Spécifie un hachurage à 30 % . Le rapport de la couleur de premier plan à la couleur d'arrière-plan est de 30 :100.

### Percent40 {#Percent40}
```
public static final int Percent40
```


Spécifie un hachurage à 40 % . Le rapport de la couleur de premier plan à la couleur d'arrière-plan est de 40 :100.

### Percent50 {#Percent50}
```
public static final int Percent50
```


Spécifie un hachurage à 50 % . Le rapport de la couleur de premier plan à la couleur d'arrière-plan est de 50 :100.

### Percent60 {#Percent60}
```
public static final int Percent60
```


Spécifie un hachurage à 60 % . Le rapport de la couleur de premier plan à la couleur d'arrière-plan est de 60 :100.

### Percent70 {#Percent70}
```
public static final int Percent70
```


Spécifie un hachurage à 70 % . Le rapport de la couleur de premier plan à la couleur d'arrière-plan est de 70 :100.

### Percent75 {#Percent75}
```
public static final int Percent75
```


Spécifie un hachurage à 75 % . Le rapport de la couleur de premier plan à la couleur d'arrière-plan est de 75 :100.

### Percent80 {#Percent80}
```
public static final int Percent80
```


Spécifie un hachurage à 80 % . Le rapport de la couleur de premier plan à la couleur d'arrière-plan est de 80 :100.

### Percent90 {#Percent90}
```
public static final int Percent90
```


Spécifie un hachurage à 90 % . Le rapport de la couleur de premier plan à la couleur d'arrière-plan est de 90 :100.

### LightDownwardDiagonal {#LightDownwardDiagonal}
```
public static final int LightDownwardDiagonal
```


Spécifie des lignes diagonales qui s’inclinent vers la droite des points supérieurs aux points inférieurs et sont espacées 50 % plus près les unes des autres que `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, mais ne sont pas antialiasées.

### LightUpwardDiagonal {#LightUpwardDiagonal}
```
public static final int LightUpwardDiagonal
```


Spécifie des lignes diagonales qui s’inclinent vers la gauche des points supérieurs aux points inférieurs et sont espacées 50 % plus près les unes des autres que `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, mais elles ne sont pas antialiasées.

### DarkDownwardDiagonal {#DarkDownwardDiagonal}
```
public static final int DarkDownwardDiagonal
```


Spécifie des lignes diagonales qui s'inclinent vers la droite du haut vers le bas, espacées de 50 % plus près les unes des autres que, et deux fois plus larges que `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`. Ce motif de hachure n'est pas antialiasé.

### DarkUpwardDiagonal {#DarkUpwardDiagonal}
```
public static final int DarkUpwardDiagonal
```


Spécifie des lignes diagonales qui s’inclinent vers la gauche des points supérieurs aux points inférieurs, sont espacées 50 % plus près les unes des autres que `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, et ont le double de sa largeur, mais les lignes ne sont pas antialiasées.

### WideDownwardDiagonal {#WideDownwardDiagonal}
```
public static final int WideDownwardDiagonal
```


Spécifie des lignes diagonales qui s’inclinent vers la droite des points supérieurs aux points inférieurs, ont le même espacement que le style de hachure `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, et ont le triple de sa largeur, mais ne sont pas antialiasées.

### WideUpwardDiagonal {#WideUpwardDiagonal}
```
public static final int WideUpwardDiagonal
```


Spécifie des lignes diagonales qui s’inclinent vers la gauche des points supérieurs aux points inférieurs, ont le même espacement que le style de hachure `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, et ont le triple de sa largeur, mais ne sont pas antialiasées.

### LightVertical {#LightVertical}
```
public static final int LightVertical
```


Spécifie des lignes verticales qui sont espacées 50 % plus près les unes des autres que `System.Drawing.drawing2d.HatchStyle.Vertical`.

### LightHorizontal {#LightHorizontal}
```
public static final int LightHorizontal
```


Spécifie des lignes horizontales qui sont espacées 50 % plus près les unes des autres que `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### NarrowVertical {#NarrowVertical}
```
public static final int NarrowVertical
```


Spécifie des lignes verticales qui sont espacées 75 % plus près les unes des autres que le style de hachure `System.Drawing.drawing2d.HatchStyle.Vertical` (ou 25 % plus près les unes des autres que `System.Drawing.drawing2d.HatchStyle.LightVertical`).

### NarrowHorizontal {#NarrowHorizontal}
```
public static final int NarrowHorizontal
```


Spécifie des lignes horizontales espacées de 75 % plus proches les unes des autres que le style de hachure `System.Drawing.drawing2d.HatchStyle.Horizontal` (ou de 25 % plus proches que `System.Drawing.drawing2d.HatchStyle.LightHorizontal`).

### DarkVertical {#DarkVertical}
```
public static final int DarkVertical
```


Spécifie des lignes verticales espacées de 50 % plus proches les unes des autres que `System.Drawing.drawing2d.HatchStyle.Vertical` et dont la largeur est le double.

### DarkHorizontal {#DarkHorizontal}
```
public static final int DarkHorizontal
```


Spécifie des lignes horizontales espacées de 50 % plus proches les unes des autres que `System.Drawing.drawing2d.HatchStyle.Horizontal` et dont la largeur est le double de `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### DashedDownwardDiagonal {#DashedDownwardDiagonal}
```
public static final int DashedDownwardDiagonal
```


Spécifie des lignes diagonales en pointillés, qui s’inclinent vers la droite du haut vers le bas.

### DashedUpwardDiagonal {#DashedUpwardDiagonal}
```
public static final int DashedUpwardDiagonal
```


Spécifie des lignes diagonales en pointillés, qui s’inclinent vers la gauche du haut vers le bas.

### DashedHorizontal {#DashedHorizontal}
```
public static final int DashedHorizontal
```


Spécifie des lignes horizontales en pointillés.

### DashedVertical {#DashedVertical}
```
public static final int DashedVertical
```


Spécifie des lignes verticales en pointillés.

### SmallConfetti {#SmallConfetti}
```
public static final int SmallConfetti
```


Spécifie un hachurage qui a l’apparence de confettis.

### LargeConfetti {#LargeConfetti}
```
public static final int LargeConfetti
```


Spécifie un hachurage qui a l’apparence de confettis, et composé de pièces plus grandes que `System.Drawing.drawing2d.HatchStyle.SmallConfetti`.

### ZigZag {#ZigZag}
```
public static final int ZigZag
```


Spécifie des lignes horizontales composées de zigzags.

### Wave {#Wave}
```
public static final int Wave
```


Spécifie des lignes horizontales composées de tildes.

### DiagonalBrick {#DiagonalBrick}
```
public static final int DiagonalBrick
```


Spécifie un hachurage qui a l’apparence de briques superposées s’inclinant vers la gauche du haut vers le bas.

### HorizontalBrick {#HorizontalBrick}
```
public static final int HorizontalBrick
```


Spécifie un hachurage qui a l’apparence de briques superposées horizontalement.

### Weave {#Weave}
```
public static final int Weave
```


Spécifie un hachurage qui a l’apparence d’un matériau tissé.

### Plaid {#Plaid}
```
public static final int Plaid
```


Spécifie un hachurage qui a l’apparence d’un tissu à carreaux.

### Divot {#Divot}
```
public static final int Divot
```


Spécifie un hachurage qui a l’apparence de fossettes.

### DottedGrid {#DottedGrid}
```
public static final int DottedGrid
```


Spécifie des lignes horizontales et verticales, chacune composée de points, qui se croisent.

### DottedDiamond {#DottedDiamond}
```
public static final int DottedDiamond
```


Spécifie des lignes diagonales avant et arrière, chacune composée de points, qui se croisent.

### Shingle {#Shingle}
```
public static final int Shingle
```


Spécifie un hachurage qui a l’apparence de bardeaux superposés en diagonale s’inclinant vers la droite du haut vers le bas.

### Trellis {#Trellis}
```
public static final int Trellis
```


Spécifie un hachurage qui a l’apparence d’un treillis.

### Sphere {#Sphere}
```
public static final int Sphere
```


Spécifie un hachurage qui a l’apparence de sphères disposées côte à côte.

### SmallGrid {#SmallGrid}
```
public static final int SmallGrid
```


Spécifie des lignes horizontales et verticales qui se croisent et sont espacées de 50 % plus proches les unes des autres que le style de hachure `System.Drawing.drawing2d.HatchStyle.Cross`.

### SmallCheckerBoard {#SmallCheckerBoard}
```
public static final int SmallCheckerBoard
```


Spécifie un hachurage qui a l’apparence d’un damier.

### LargeCheckerBoard {#LargeCheckerBoard}
```
public static final int LargeCheckerBoard
```


Spécifie un hachurage qui a l’apparence d’un damier avec des carrés deux fois plus grands que `System.Drawing.drawing2d.HatchStyle.SmallCheckerBoard`.

### OutlinedDiamond {#OutlinedDiamond}
```
public static final int OutlinedDiamond
```


Spécifie des lignes diagonales avant et arrière qui se croisent mais ne sont pas antialiasées.

### SolidDiamond {#SolidDiamond}
```
public static final int SolidDiamond
```


Spécifie un hachurage qui a l'apparence d'un damier placé en diagonale.

### LargeGrid {#LargeGrid}
```
public static final int LargeGrid
```


Spécifie le style de hachure `System.Drawing.drawing2d.HatchStyle.Cross`.

### Min {#Min}
```
public static final int Min
```


Spécifie le style de hachure `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### Max {#Max}
```
public static final int Max
```


Spécifie le style de hachure `System.Drawing.drawing2d.HatchStyle.SolidDiamond`.

