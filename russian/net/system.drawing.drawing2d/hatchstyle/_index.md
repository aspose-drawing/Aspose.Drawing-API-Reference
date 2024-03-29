---
title: HatchStyle
second_title: Справочник по API Aspose.Drawing для .NET
description: Определяет различные шаблоны доступные дляHatchBrush объекты.
type: docs
weight: 300
url: /ru/net/system.drawing.drawing2d/hatchstyle/
---
## HatchStyle enumeration

Определяет различные шаблоны, доступные дляHatchBrush объекты.

```csharp
public enum HatchStyle
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| Horizontal | `0` | Узор из горизонтальных линий. |
| Vertical | `1` | Узор из вертикальных линий. |
| ForwardDiagonal | `2` | Узор из линий по диагонали от левого верхнего угла к правому нижнему. |
| BackwardDiagonal | `3` | Узор из линий по диагонали от верхнего правого угла к нижнему левому. |
| Cross | `4` | Задает пересекающиеся горизонтальные и вертикальные линии. |
| DiagonalCross | `5` | Узор из перекрещивающихся диагональных линий. |
| Percent05 | `6` | Указывает 5-процентную штриховку. Отношение цвета переднего плана к цвету фона составляет 5:100. |
| Percent10 | `7` | Задает 10-процентную штриховку. Отношение цвета переднего плана к цвету фона составляет 10:100. |
| Percent20 | `8` | Указывает 20-процентную штриховку. Отношение цвета переднего плана к цвету фона составляет 20:100. |
| Percent25 | `9` | Указывает 25-процентную штриховку. Отношение цвета переднего плана к цвету фона составляет 25:100. |
| Percent30 | `10` | Указывает 30-процентную штриховку. Отношение цвета переднего плана к цвету фона составляет 30:100. |
| Percent40 | `11` | Указывает 40-процентную штриховку. Отношение цвета переднего плана к цвету фона составляет 40:100. |
| Percent50 | `12` | Указывает 50-процентную штриховку. Отношение цвета переднего плана к цвету фона составляет 50:100. |
| Percent60 | `13` | Указывает 60-процентную штриховку. Отношение цвета переднего плана к цвету фона составляет 60:100. |
| Percent70 | `14` | Указывает 70-процентную штриховку. Отношение цвета переднего плана к цвету фона составляет 70:100. |
| Percent75 | `15` | Указывает 75-процентную штриховку. Отношение цвета переднего плана к цвету фона составляет 75:100. |
| Percent80 | `16` | Указывает 80-процентную штриховку. Отношение цвета переднего плана к цвету фона составляет 80:100. |
| Percent90 | `17` | Указывает 90-процентную штриховку. Отношение цвета переднего плана к цвету фона составляет 90:100. |
| LightDownwardDiagonal | `18` | Задает диагональные линии, наклоненные вправо от верхних точек к нижним точкам и расположенные на 50 процентов ближе друг к другу, чемForwardDiagonal, но не сглажены. |
| LightUpwardDiagonal | `19` | Задает диагональные линии, наклоненные влево от верхних точек к нижним точкам и расположенные на 50 процентов ближе друг к другу, чемBackwardDiagonal, но они не сглажены. |
| DarkDownwardDiagonal | `20` | Задает диагональные линии, наклоненные вправо от верхних точек к нижним точкам, расположенные на 50 процентов ближе друг к другу, чем и в два раза ширеForwardDiagonal. Этот образец штриховки не сглаживается. |
| DarkUpwardDiagonal | `21` | Задает диагональные линии, которые наклонены влево от верхних точек к нижним точкам и располагаются на 50 процентов ближе друг к другу, чемBackwardDiagonal, и в два раза больше его ширины, но линии не сглажены. |
| WideDownwardDiagonal | `22` | Указывает диагональные линии, которые наклонены вправо от верхних точек к нижним точкам, имеют тот же интервал, что и стиль штриховки.ForwardDiagonal, и утраивают его ширину, но не сглаживаются. |
| WideUpwardDiagonal | `23` | Указывает диагональные линии, которые наклонены влево от верхних точек к нижним точкам, имеют тот же интервал, что и стиль штриховки.BackwardDiagonal, и утраивают его ширину, но не сглаживаются. |
| LightVertical | `24` | Определяет вертикальные линии, расположенные на 50 процентов ближе друг к другу, чемVertical. |
| LightHorizontal | `25` | Указывает горизонтальные линии, расположенные на 50 процентов ближе друг к другу, чемHorizontal. |
| NarrowVertical | `26` | Определяет вертикальные линии, расположенные на 75 процентов ближе друг к другу, чем стиль штриховки.Vertical (или на 25 процентов ближе друг к другу, чемLightVertical). |
| NarrowHorizontal | `27` | Определяет горизонтальные линии, расположенные на 75 процентов ближе друг к другу, чем стиль штриховки.Horizontal (или на 25 процентов ближе друг к другу, чемLightHorizontal). |
| DarkVertical | `28` | Определяет вертикальные линии, расположенные на 50 процентов ближе друг к другу, чемVertical и в два раза больше его ширины. |
| DarkHorizontal | `29` | Указывает горизонтальные линии, расположенные на 50 процентов ближе друг к другу, чемHorizontal и в два раза ширеHorizontal. |
| DashedDownwardDiagonal | `30` | Указывает пунктирные диагональные линии, наклоненные вправо от верхних точек к нижним точкам. |
| DashedUpwardDiagonal | `31` | Указывает пунктирные диагональные линии, наклоненные влево от верхних точек к нижним точкам. |
| DashedHorizontal | `32` | Указывает пунктирные горизонтальные линии. |
| DashedVertical | `33` | Определяет пунктирные вертикальные линии. |
| SmallConfetti | `34` | Определяет штриховку, имеющую вид конфетти. |
| LargeConfetti | `35` | Определяет штриховку, имеющую вид конфетти и состоящую из более крупных частей, чемSmallConfetti. |
| ZigZag | `36` | Задает горизонтальные линии, состоящие из зигзагов. |
| Wave | `37` | Указывает горизонтальные линии, состоящие из тильд. |
| DiagonalBrick | `38` | Определяет штриховку, имеющую вид многослойных кирпичей, наклоненных влево от верхних точек к нижним точкам. |
| HorizontalBrick | `39` | Определяет штриховку, имеющую вид кирпичей с горизонтальными слоями. |
| Weave | `40` | Определяет штриховку, имеющую внешний вид тканого материала. |
| Plaid | `41` | Определяет штриховку, имеющую внешний вид клетчатого материала. |
| Divot | `42` | Определяет штриховку, имеющую вид канавок. |
| DottedGrid | `43` | Указывает горизонтальные и вертикальные линии, каждая из которых состоит из точек, которые пересекаются. |
| DottedDiamond | `44` | Определяет прямые диагональные и обратные диагональные линии, каждая из которых состоит из точек, которые пересекаются. |
| Shingle | `45` | Определяет штриховку, имеющую вид диагональных слоев черепицы с наклоном вправо от верхних точек к нижним точкам. |
| Trellis | `46` | Определяет штриховку, имеющую вид решетки. |
| Sphere | `47` | Определяет штриховку, имеющую вид сфер, расположенных рядом друг с другом. |
| SmallGrid | `48` | Указывает горизонтальные и вертикальные линии, которые пересекаются и располагаются на 50 процентов ближе друг к другу, чем стиль штриховки.Cross. |
| SmallCheckerBoard | `49` | Задает штриховку в виде шахматной доски. |
| LargeCheckerBoard | `50` | Определяет штриховку в виде шахматной доски с квадратами вдвое большеSmallCheckerBoard. |
| OutlinedDiamond | `51` | Определяет прямые диагональные и обратные диагональные линии, которые пересекаются, но не сглаживаются. |
| SolidDiamond | `52` | Определяет штриховку, имеющую вид шахматной доски, расположенной по диагонали. |
| LargeGrid | `4` | Определяет стиль штриховкиCross. |
| Min | `0` | Определяет стиль штриховкиHorizontal. |
| Max | `4` | Определяет стиль штриховкиSolidDiamond. |

### Смотрите также

* пространство имен [System.Drawing.Drawing2D](../../system.drawing.drawing2d)
* сборка [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
