---
title: Color
second_title: Referencia de la API de Aspose.Drawing para Java
description: Representa un color ARGB alfa rojo verde azul.
type: docs
weight: 14
url: /es/java/com.aspose.drawing/color/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Color extends Struct<Color> implements System.IEquatable<Color>, Cloneable
```

Representa un color ARGB (alfa, rojo, verde, azul).
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Color()](#Color--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [EMPTY](#EMPTY) | Representa un color que es nulo. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getTransparent()](#getTransparent--) | Obtiene un color definido por el sistema. |
| [getAliceBlue()](#getAliceBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFF0F8FF. |
| [getAntiqueWhite()](#getAntiqueWhite--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFAEBD7. |
| [getAqua()](#getAqua--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF00FFFF. |
| [getAquamarine()](#getAquamarine--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF7FFFD4. |
| [getAzure()](#getAzure--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFF0FFFF. |
| [getBeige()](#getBeige--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFF5F5DC. |
| [getBisque()](#getBisque--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFE4C4. |
| [getBlack()](#getBlack--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF000000. |
| [getBlanchedAlmond()](#getBlanchedAlmond--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFEBCD. |
| [getBlue()](#getBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF0000FF. |
| [getBlueViolet()](#getBlueViolet--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF8A2BE2. |
| [getBrown()](#getBrown--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFA52A2A. |
| [getBurlyWood()](#getBurlyWood--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFDEB887. |
| [getCadetBlue()](#getCadetBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF5F9EA0. |
| [getChartreuse()](#getChartreuse--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF7FFF00. |
| [getChocolate()](#getChocolate--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFD2691E. |
| [getCoral()](#getCoral--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFF7F50. |
| [getCornflowerBlue()](#getCornflowerBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF6495ED. |
| [getCornsilk()](#getCornsilk--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFF8DC. |
| [getCrimson()](#getCrimson--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFDC143C. |
| [getCyan()](#getCyan--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF00FFFF. |
| [getDarkBlue()](#getDarkBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF00008B. |
| [getDarkCyan()](#getDarkCyan--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF008B8B. |
| [getDarkGoldenrod()](#getDarkGoldenrod--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFB8860B. |
| [getDarkGray()](#getDarkGray--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFA9A9A9. |
| [getDarkGreen()](#getDarkGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF006400. |
| [getDarkKhaki()](#getDarkKhaki--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFBDB76B. |
| [getDarkMagenta()](#getDarkMagenta--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF8B008B. |
| [getDarkOliveGreen()](#getDarkOliveGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF556B2F. |
| [getDarkOrange()](#getDarkOrange--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFF8C00. |
| [getDarkOrchid()](#getDarkOrchid--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF9932CC. |
| [getDarkRed()](#getDarkRed--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF8B0000. |
| [getDarkSalmon()](#getDarkSalmon--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFE9967A. |
| [getDarkSeaGreen()](#getDarkSeaGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF8FBC8F. |
| [getDarkSlateBlue()](#getDarkSlateBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF483D8B. |
| [getDarkSlateGray()](#getDarkSlateGray--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF2F4F4F. |
| [getDarkTurquoise()](#getDarkTurquoise--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF00CED1. |
| [getDarkViolet()](#getDarkViolet--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF9400D3. |
| [getDeepPink()](#getDeepPink--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFF1493. |
| [getDeepSkyBlue()](#getDeepSkyBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF00BFFF. |
| [getDimGray()](#getDimGray--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF696969. |
| [getDodgerBlue()](#getDodgerBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF1E90FF. |
| [getFirebrick()](#getFirebrick--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFB22222. |
| [getFloralWhite()](#getFloralWhite--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFFAF0. |
| [getForestGreen()](#getForestGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF228B22. |
| [getFuchsia()](#getFuchsia--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFF00FF. |
| [getGainsboro()](#getGainsboro--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFDCDCDC. |
| [getGhostWhite()](#getGhostWhite--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFF8F8FF. |
| [getGold()](#getGold--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFD700. |
| [getGoldenrod()](#getGoldenrod--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFDAA520. |
| [getGray()](#getGray--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF808080. |
| [getGreen()](#getGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF008000. |
| [getGreenYellow()](#getGreenYellow--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFADFF2F. |
| [getHoneydew()](#getHoneydew--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFF0FFF0. |
| [getHotPink()](#getHotPink--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFF69B4. |
| [getIndianRed()](#getIndianRed--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFCD5C5C. |
| [getIndigo()](#getIndigo--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF4B0082. |
| [getIvory()](#getIvory--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFFFF0. |
| [getKhaki()](#getKhaki--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFF0E68C. |
| [getLavender()](#getLavender--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFE6E6FA. |
| [getLavenderBlush()](#getLavenderBlush--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFF0F5. |
| [getLawnGreen()](#getLawnGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF7CFC00. |
| [getLemonChiffon()](#getLemonChiffon--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFFACD. |
| [getLightBlue()](#getLightBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFADD8E6. |
| [getLightCoral()](#getLightCoral--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFF08080. |
| [getLightCyan()](#getLightCyan--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFE0FFFF. |
| [getLightGoldenrodYellow()](#getLightGoldenrodYellow--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFAFAD2. |
| [getLightGreen()](#getLightGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF90EE90. |
| [getLightGray()](#getLightGray--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFD3D3D3. |
| [getLightPink()](#getLightPink--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFB6C1. |
| [getLightSalmon()](#getLightSalmon--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFA07A. |
| [getLightSeaGreen()](#getLightSeaGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF20B2AA. |
| [getLightSkyBlue()](#getLightSkyBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF87CEFA. |
| [getLightSlateGray()](#getLightSlateGray--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF778899. |
| [getLightSteelBlue()](#getLightSteelBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFB0C4DE. |
| [getLightYellow()](#getLightYellow--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFFFE0. |
| [getLime()](#getLime--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF00FF00. |
| [getLimeGreen()](#getLimeGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF32CD32. |
| [getLinen()](#getLinen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFAF0E6. |
| [getMagenta()](#getMagenta--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFF00FF. |
| [getMaroon()](#getMaroon--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF800000. |
| [getMediumAquamarine()](#getMediumAquamarine--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF66CDAA. |
| [getMediumBlue()](#getMediumBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF0000CD. |
| [getMediumOrchid()](#getMediumOrchid--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFBA55D3. |
| [getMediumPurple()](#getMediumPurple--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF9370DB. |
| [getMediumSeaGreen()](#getMediumSeaGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF3CB371. |
| [getMediumSlateBlue()](#getMediumSlateBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF7B68EE. |
| [getMediumSpringGreen()](#getMediumSpringGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF00FA9A. |
| [getMediumTurquoise()](#getMediumTurquoise--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF48D1CC. |
| [getMediumVioletRed()](#getMediumVioletRed--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFC71585. |
| [getMidnightBlue()](#getMidnightBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF191970. |
| [getMintCream()](#getMintCream--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFF5FFFA. |
| [getMistyRose()](#getMistyRose--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFE4E1. |
| [getMoccasin()](#getMoccasin--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFE4B5. |
| [getNavajoWhite()](#getNavajoWhite--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFDEAD. |
| [getNavy()](#getNavy--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF000080. |
| [getOldLace()](#getOldLace--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFDF5E6. |
| [getOlive()](#getOlive--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF808000. |
| [getOliveDrab()](#getOliveDrab--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF6B8E23. |
| [getOrange()](#getOrange--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFA500. |
| [getOrangeRed()](#getOrangeRed--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFF4500. |
| [getOrchid()](#getOrchid--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFDA70D6. |
| [getPaleGoldenrod()](#getPaleGoldenrod--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFEEE8AA. |
| [getPaleGreen()](#getPaleGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF98FB98. |
| [getPaleTurquoise()](#getPaleTurquoise--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFAFEEEE. |
| [getPaleVioletRed()](#getPaleVioletRed--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFDB7093. |
| [getPapayaWhip()](#getPapayaWhip--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFEFD5. |
| [getPeachPuff()](#getPeachPuff--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFDAB9. |
| [getPeru()](#getPeru--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFCD853F. |
| [getPink()](#getPink--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFC0CB. |
| [getPlum()](#getPlum--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFDDA0DD. |
| [getPowderBlue()](#getPowderBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFB0E0E6. |
| [getPurple()](#getPurple--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF800080. |
| [getRed()](#getRed--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFF0000. |
| [getRosyBrown()](#getRosyBrown--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFBC8F8F. |
| [getRoyalBlue()](#getRoyalBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF4169E1. |
| [getSaddleBrown()](#getSaddleBrown--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF8B4513. |
| [getSalmon()](#getSalmon--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFA8072. |
| [getSandyBrown()](#getSandyBrown--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFF4A460. |
| [getSeaGreen()](#getSeaGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF2E8B57. |
| [getSeaShell()](#getSeaShell--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFF5EE. |
| [getSienna()](#getSienna--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFA0522D. |
| [getSilver()](#getSilver--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFC0C0C0. |
| [getSkyBlue()](#getSkyBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF87CEEB. |
| [getSlateBlue()](#getSlateBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF6A5ACD. |
| [getSlateGray()](#getSlateGray--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF708090. |
| [getSnow()](#getSnow--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFFAFA. |
| [getSpringGreen()](#getSpringGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF00FF7F. |
| [getSteelBlue()](#getSteelBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF4682B4. |
| [getTan()](#getTan--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFD2B48C. |
| [getTeal()](#getTeal--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF008080. |
| [getThistle()](#getThistle--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFD8BFD8. |
| [getTomato()](#getTomato--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFF6347. |
| [getTurquoise()](#getTurquoise--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF40E0D0. |
| [getViolet()](#getViolet--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFEE82EE. |
| [getWheat()](#getWheat--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFF5DEB3. |
| [getWhite()](#getWhite--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFFFFF. |
| [getWhiteSmoke()](#getWhiteSmoke--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFF5F5F5. |
| [getYellow()](#getYellow--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFFF00. |
| [getYellowGreen()](#getYellowGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF9ACD32. |
| [getA()](#getA--) | Obtiene el valor del componente alfa de esta estructura [Color](../../com.aspose.drawing/color). |
| [getR()](#getR--) | Obtiene el valor del componente rojo de esta estructura [Color](../../com.aspose.drawing/color). |
| [getG()](#getG--) | Obtiene el valor del componente verde de esta estructura [Color](../../com.aspose.drawing/color). |
| [getB()](#getB--) | Obtiene el valor del componente azul de esta estructura [Color](../../com.aspose.drawing/color). |
| [isKnownColor()](#isKnownColor--) | Obtiene un valor que indica si esta estructura [Color](../../com.aspose.drawing/color) es un color predefinido. |
| [isEmpty()](#isEmpty--) | Obtiene un valor que indica si esta estructura [Color](../../com.aspose.drawing/color) no está inicializada. |
| [isNamedColor()](#isNamedColor--) | Obtiene un valor que indica si esta estructura [Color](../../com.aspose.drawing/color) es un color con nombre o un miembro de la enumeración [KnownColor](../../com.aspose.drawing/knowncolor). |
| [isSystemColor()](#isSystemColor--) | Obtiene un valor que indica si esta estructura [Color](../../com.aspose.drawing/color) es un color del sistema. |
| [getName()](#getName--) | Obtiene el nombre de este [Color](../../com.aspose.drawing/color). |
| [fromArgb(int argb)](#fromArgb-int-) | Crea una estructura [Color](../../com.aspose.drawing/color) a partir de un valor ARGB de 32 bits. |
| [fromArgb(int alpha, Color baseColor)](#fromArgb-int-com.aspose.drawing.Color-) | Crea una estructura [Color](../../com.aspose.drawing/color) a partir de la estructura [Color](../../com.aspose.drawing/color) especificada, pero con el nuevo valor alfa especificado. |
| [fromArgb(int red, int green, int blue)](#fromArgb-int-int-int-) | Crea una estructura [Color](../../com.aspose.drawing/color) a partir de los valores de color de 8 bits especificados (rojo, verde y azul). |
| [fromArgb(int alpha, int red, int green, int blue)](#fromArgb-int-int-int-int-) | Crea una estructura Color a partir de los cuatro valores de componentes ARGB (alfa, rojo, verde y azul). |
| [fromKnownColor(int color)](#fromKnownColor-int-) | Crea una estructura [Color](../../com.aspose.drawing/color) a partir del color predefinido especificado. |
| [fromName(String name)](#fromName-java.lang.String-) | Crea una estructura [Color](../../com.aspose.drawing/color) a partir del nombre especificado de un color predefinido. |
| [op_Equality(Color left, Color right)](#op-Equality-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Comprueba si dos estructuras [Color](../../com.aspose.drawing/color) especificadas son equivalentes. |
| [op_Inequality(Color left, Color right)](#op-Inequality-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Comprueba si dos estructuras [Color](../../com.aspose.drawing/color) especificadas son diferentes. |
| [equals(Color other)](#equals-com.aspose.drawing.Color-) | Comprueba si el color especificado es equivalente a este color. |
| [equals(Object obj)](#equals-java.lang.Object-) | Comprueba si el objeto especificado es equivalente a este color. |
| [toArgb()](#toArgb--) | Obtiene el valor ARGB de 32 bits de esta estructura Color. |
| [getBrightness()](#getBrightness--) | Obtiene el valor de brillo hue-saturation-brightness (HSB) de esta estructura [Color](../../com.aspose.drawing/color). |
| [getHue()](#getHue--) | Obtiene el valor de tono hue-saturation-brightness (HSB), en grados, de esta estructura [Color](../../com.aspose.drawing/color). |
| [getSaturation()](#getSaturation--) | Obtiene el valor de saturación hue-saturation-brightness (HSB) de esta estructura [Color](../../com.aspose.drawing/color). |
| [toKnownColor()](#toKnownColor--) | Obtiene el valor [KnownColor](../../com.aspose.drawing/knowncolor) de esta estructura [Color](../../com.aspose.drawing/color). |
| [toString()](#toString--) | Devuelve una String que representa esta instancia. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia. |
| [isEquals(Color obj1, Color obj2)](#isEquals-com.aspose.drawing.Color-com.aspose.drawing.Color-) |  |
| [getEmpty()](#getEmpty--) |  |
| [CloneTo(Color that)](#CloneTo-com.aspose.drawing.Color-) |  |
| [Clone()](#Clone--) |  |
### Color() {#Color--}
```
public Color()
```


### EMPTY {#EMPTY}
```
public static final Color EMPTY
```


Representa un color que es nulo.

### getTransparent() {#getTransparent--}
```
public static Color getTransparent()
```


Obtiene un color definido por el sistema.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAliceBlue() {#getAliceBlue--}
```
public static Color getAliceBlue()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFF0F8FF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAntiqueWhite() {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFAEBD7.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAqua() {#getAqua--}
```
public static Color getAqua()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF00FFFF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAquamarine() {#getAquamarine--}
```
public static Color getAquamarine()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF7FFFD4.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAzure() {#getAzure--}
```
public static Color getAzure()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFF0FFFF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBeige() {#getBeige--}
```
public static Color getBeige()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFF5F5DC.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBisque() {#getBisque--}
```
public static Color getBisque()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFE4C4.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBlack() {#getBlack--}
```
public static Color getBlack()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF000000.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBlanchedAlmond() {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFEBCD.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBlue() {#getBlue--}
```
public static Color getBlue()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF0000FF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBlueViolet() {#getBlueViolet--}
```
public static Color getBlueViolet()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF8A2BE2.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBrown() {#getBrown--}
```
public static Color getBrown()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFA52A2A.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBurlyWood() {#getBurlyWood--}
```
public static Color getBurlyWood()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFDEB887.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCadetBlue() {#getCadetBlue--}
```
public static Color getCadetBlue()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF5F9EA0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getChartreuse() {#getChartreuse--}
```
public static Color getChartreuse()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF7FFF00.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getChocolate() {#getChocolate--}
```
public static Color getChocolate()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFD2691E.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCoral() {#getCoral--}
```
public static Color getCoral()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFF7F50.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCornflowerBlue() {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF6495ED.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCornsilk() {#getCornsilk--}
```
public static Color getCornsilk()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFF8DC.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCrimson() {#getCrimson--}
```
public static Color getCrimson()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFDC143C.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCyan() {#getCyan--}
```
public static Color getCyan()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF00FFFF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkBlue() {#getDarkBlue--}
```
public static Color getDarkBlue()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF00008B.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkCyan() {#getDarkCyan--}
```
public static Color getDarkCyan()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF008B8B.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkGoldenrod() {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFB8860B.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkGray() {#getDarkGray--}
```
public static Color getDarkGray()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFA9A9A9.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkGreen() {#getDarkGreen--}
```
public static Color getDarkGreen()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF006400.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkKhaki() {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFBDB76B.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkMagenta() {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF8B008B.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkOliveGreen() {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF556B2F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkOrange() {#getDarkOrange--}
```
public static Color getDarkOrange()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFF8C00.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkOrchid() {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF9932CC.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkRed() {#getDarkRed--}
```
public static Color getDarkRed()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF8B0000.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkSalmon() {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFE9967A.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkSeaGreen() {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF8FBC8F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkSlateBlue() {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF483D8B.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkSlateGray() {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF2F4F4F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkTurquoise() {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF00CED1.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkViolet() {#getDarkViolet--}
```
public static Color getDarkViolet()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF9400D3.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDeepPink() {#getDeepPink--}
```
public static Color getDeepPink()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFF1493.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDeepSkyBlue() {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF00BFFF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDimGray() {#getDimGray--}
```
public static Color getDimGray()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF696969.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDodgerBlue() {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF1E90FF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getFirebrick() {#getFirebrick--}
```
public static Color getFirebrick()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFB22222.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getFloralWhite() {#getFloralWhite--}
```
public static Color getFloralWhite()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFFAF0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getForestGreen() {#getForestGreen--}
```
public static Color getForestGreen()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF228B22.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getFuchsia() {#getFuchsia--}
```
public static Color getFuchsia()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFF00FF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGainsboro() {#getGainsboro--}
```
public static Color getGainsboro()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFDCDCDC.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGhostWhite() {#getGhostWhite--}
```
public static Color getGhostWhite()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFF8F8FF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGold() {#getGold--}
```
public static Color getGold()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFD700.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGoldenrod() {#getGoldenrod--}
```
public static Color getGoldenrod()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFDAA520.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGray() {#getGray--}
```
public static Color getGray()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF808080.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) strcture representing a system-defined color. `1`
### getGreen() {#getGreen--}
```
public static Color getGreen()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF008000.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGreenYellow() {#getGreenYellow--}
```
public static Color getGreenYellow()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFADFF2F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getHoneydew() {#getHoneydew--}
```
public static Color getHoneydew()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFF0FFF0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getHotPink() {#getHotPink--}
```
public static Color getHotPink()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFF69B4.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getIndianRed() {#getIndianRed--}
```
public static Color getIndianRed()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFCD5C5C.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getIndigo() {#getIndigo--}
```
public static Color getIndigo()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF4B0082.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getIvory() {#getIvory--}
```
public static Color getIvory()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFFFF0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getKhaki() {#getKhaki--}
```
public static Color getKhaki()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFF0E68C.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLavender() {#getLavender--}
```
public static Color getLavender()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFE6E6FA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLavenderBlush() {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFF0F5.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLawnGreen() {#getLawnGreen--}
```
public static Color getLawnGreen()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF7CFC00.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLemonChiffon() {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFFACD.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightBlue() {#getLightBlue--}
```
public static Color getLightBlue()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFADD8E6.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightCoral() {#getLightCoral--}
```
public static Color getLightCoral()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFF08080.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightCyan() {#getLightCyan--}
```
public static Color getLightCyan()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFE0FFFF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightGoldenrodYellow() {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFAFAD2.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightGreen() {#getLightGreen--}
```
public static Color getLightGreen()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF90EE90.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightGray() {#getLightGray--}
```
public static Color getLightGray()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFD3D3D3.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightPink() {#getLightPink--}
```
public static Color getLightPink()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFB6C1.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSalmon() {#getLightSalmon--}
```
public static Color getLightSalmon()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFA07A.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSeaGreen() {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF20B2AA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSkyBlue() {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF87CEFA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSlateGray() {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF778899.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSteelBlue() {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFB0C4DE.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightYellow() {#getLightYellow--}
```
public static Color getLightYellow()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFFFE0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLime() {#getLime--}
```
public static Color getLime()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF00FF00.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLimeGreen() {#getLimeGreen--}
```
public static Color getLimeGreen()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF32CD32.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLinen() {#getLinen--}
```
public static Color getLinen()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFAF0E6.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMagenta() {#getMagenta--}
```
public static Color getMagenta()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFF00FF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMaroon() {#getMaroon--}
```
public static Color getMaroon()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF800000.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumAquamarine() {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF66CDAA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumBlue() {#getMediumBlue--}
```
public static Color getMediumBlue()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF0000CD.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumOrchid() {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFBA55D3.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumPurple() {#getMediumPurple--}
```
public static Color getMediumPurple()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF9370DB.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumSeaGreen() {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF3CB371.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumSlateBlue() {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF7B68EE.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumSpringGreen() {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF00FA9A.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumTurquoise() {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF48D1CC.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumVioletRed() {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFC71585.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMidnightBlue() {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF191970.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMintCream() {#getMintCream--}
```
public static Color getMintCream()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFF5FFFA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMistyRose() {#getMistyRose--}
```
public static Color getMistyRose()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFE4E1.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMoccasin() {#getMoccasin--}
```
public static Color getMoccasin()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFE4B5.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getNavajoWhite() {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFDEAD.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getNavy() {#getNavy--}
```
public static Color getNavy()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF000080.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOldLace() {#getOldLace--}
```
public static Color getOldLace()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFDF5E6.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOlive() {#getOlive--}
```
public static Color getOlive()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF808000.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOliveDrab() {#getOliveDrab--}
```
public static Color getOliveDrab()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF6B8E23.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOrange() {#getOrange--}
```
public static Color getOrange()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFA500.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOrangeRed() {#getOrangeRed--}
```
public static Color getOrangeRed()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFF4500.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOrchid() {#getOrchid--}
```
public static Color getOrchid()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFDA70D6.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPaleGoldenrod() {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFEEE8AA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPaleGreen() {#getPaleGreen--}
```
public static Color getPaleGreen()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF98FB98.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPaleTurquoise() {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFAFEEEE.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPaleVioletRed() {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFDB7093.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPapayaWhip() {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFEFD5.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPeachPuff() {#getPeachPuff--}
```
public static Color getPeachPuff()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFDAB9.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPeru() {#getPeru--}
```
public static Color getPeru()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFCD853F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPink() {#getPink--}
```
public static Color getPink()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFC0CB.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPlum() {#getPlum--}
```
public static Color getPlum()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFDDA0DD.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPowderBlue() {#getPowderBlue--}
```
public static Color getPowderBlue()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFB0E0E6.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPurple() {#getPurple--}
```
public static Color getPurple()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF800080.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getRed() {#getRed--}
```
public static Color getRed()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFF0000.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getRosyBrown() {#getRosyBrown--}
```
public static Color getRosyBrown()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFBC8F8F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getRoyalBlue() {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF4169E1.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSaddleBrown() {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF8B4513.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSalmon() {#getSalmon--}
```
public static Color getSalmon()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFA8072.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSandyBrown() {#getSandyBrown--}
```
public static Color getSandyBrown()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFF4A460.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSeaGreen() {#getSeaGreen--}
```
public static Color getSeaGreen()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF2E8B57.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSeaShell() {#getSeaShell--}
```
public static Color getSeaShell()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFF5EE.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSienna() {#getSienna--}
```
public static Color getSienna()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFA0522D.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSilver() {#getSilver--}
```
public static Color getSilver()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFC0C0C0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSkyBlue() {#getSkyBlue--}
```
public static Color getSkyBlue()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF87CEEB.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSlateBlue() {#getSlateBlue--}
```
public static Color getSlateBlue()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF6A5ACD.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSlateGray() {#getSlateGray--}
```
public static Color getSlateGray()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF708090.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSnow() {#getSnow--}
```
public static Color getSnow()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFFAFA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSpringGreen() {#getSpringGreen--}
```
public static Color getSpringGreen()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF00FF7F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSteelBlue() {#getSteelBlue--}
```
public static Color getSteelBlue()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF4682B4.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getTan() {#getTan--}
```
public static Color getTan()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFD2B48C.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getTeal() {#getTeal--}
```
public static Color getTeal()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF008080.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getThistle() {#getThistle--}
```
public static Color getThistle()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFD8BFD8.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getTomato() {#getTomato--}
```
public static Color getTomato()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFF6347.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getTurquoise() {#getTurquoise--}
```
public static Color getTurquoise()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF40E0D0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getViolet() {#getViolet--}
```
public static Color getViolet()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFEE82EE.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getWheat() {#getWheat--}
```
public static Color getWheat()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFF5DEB3.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getWhite() {#getWhite--}
```
public static Color getWhite()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFFFFF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getWhiteSmoke() {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFF5F5F5.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getYellow() {#getYellow--}
```
public static Color getYellow()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FFFFFF00.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getYellowGreen() {#getYellowGreen--}
```
public static Color getYellowGreen()
```


Obtiene un color definido por el sistema que tiene un valor ARGB de \#FF9ACD32.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getA() {#getA--}
```
public final int getA()
```


Obtiene el valor del componente alfa de esta estructura [Color](../../com.aspose.drawing/color).

**Returns:**
int - El valor del componente alfa de este [Color](../../com.aspose.drawing/color).
### getR() {#getR--}
```
public final int getR()
```


Obtiene el valor del componente rojo de esta estructura [Color](../../com.aspose.drawing/color).

**Returns:**
int - El valor del componente rojo de este [Color](../../com.aspose.drawing/color).
### getG() {#getG--}
```
public final int getG()
```


Obtiene el valor del componente verde de esta estructura [Color](../../com.aspose.drawing/color).

**Returns:**
int - El valor del componente verde de este [Color](../../com.aspose.drawing/color).
### getB() {#getB--}
```
public final int getB()
```


Obtiene el valor del componente azul de esta estructura [Color](../../com.aspose.drawing/color).

**Returns:**
int - El valor del componente azul de este [Color](../../com.aspose.drawing/color).
### isKnownColor() {#isKnownColor--}
```
public final boolean isKnownColor()
```


Obtiene un valor que indica si esta estructura [Color](../../com.aspose.drawing/color) es un color predefinido. Los colores predefinidos están representados por los elementos de la enumeración [KnownColor](../../com.aspose.drawing/knowncolor).

Valor: `true` si este [Color](../../com.aspose.drawing/color) se creó a partir de un color predefinido usando el método `M:Color.FromName(System.String)` o el método `M:Color.FromKnownColor(System.Drawing.KnownColor)`; de lo contrario, `false`.

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Obtiene un valor que indica si esta estructura [Color](../../com.aspose.drawing/color) no está inicializada.

Valor: Esta propiedad devuelve true si este color no está inicializado; de lo contrario, false.

**Returns:**
boolean
### isNamedColor() {#isNamedColor--}
```
public final boolean isNamedColor()
```


Obtiene un valor que indica si esta estructura [Color](../../com.aspose.drawing/color) es un color con nombre o un miembro de la enumeración [KnownColor](../../com.aspose.drawing/knowncolor).

Valor: `true` si este [Color](../../com.aspose.drawing/color) se creó usando el método `M:Color.FromName(System.String)` o el método `M:Color.FromKnownColor(System.Drawing.KnownColor)`; de lo contrario, `false`.

**Returns:**
boolean
### isSystemColor() {#isSystemColor--}
```
public final boolean isSystemColor()
```


Obtiene un valor que indica si esta estructura [Color](../../com.aspose.drawing/color) es un color del sistema. Un color del sistema es un color que se usa en un elemento de visualización de Windows. Los colores del sistema están representados por los elementos de la enumeración [KnownColor](../../com.aspose.drawing/knowncolor).

Valor: `true` si este [Color](../../com.aspose.drawing/color) se creó a partir de un color del sistema usando el método `M:Color.FromName(System.String)` o el método `M:Color.FromKnownColor(System.Drawing.KnownColor)`; de lo contrario, `false`.

**Returns:**
boolean
### getName() {#getName--}
```
public final String getName()
```


Obtiene el nombre de este [Color](../../com.aspose.drawing/color).

**Returns:**
java.lang.String
### fromArgb(int argb) {#fromArgb-int-}
```
public static Color fromArgb(int argb)
```


Crea una estructura [Color](../../com.aspose.drawing/color) a partir de un valor ARGB de 32 bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argb | int | Un valor que especifica el valor ARGB de 32 bits. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that this method creates.
### fromArgb(int alpha, Color baseColor) {#fromArgb-int-com.aspose.drawing.Color-}
```
public static Color fromArgb(int alpha, Color baseColor)
```


Crea una estructura [Color](../../com.aspose.drawing/color) a partir de la estructura [Color](../../com.aspose.drawing/color) especificada, pero con el nuevo valor alfa especificado. Aunque este método permite pasar un valor de 32 bits para el valor alfa, el valor está limitado a 8 bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alpha | int | El valor alfa para el nuevo [Color](../../com.aspose.drawing/color). Los valores válidos son de 0 a 255. |
| baseColor | [Color](../../com.aspose.drawing/color) | El [Color](../../com.aspose.drawing/color) del cual crear el nuevo [Color](../../com.aspose.drawing/color). |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) that this method creates.
### fromArgb(int red, int green, int blue) {#fromArgb-int-int-int-}
```
public static Color fromArgb(int red, int green, int blue)
```


Crea una estructura [Color](../../com.aspose.drawing/color) a partir de los valores de color de 8 bits especificados (rojo, verde y azul). El valor alfa es implícitamente 255 (totalmente opaco). Aunque este método permite pasar un valor de 32 bits para cada componente de color, el valor de cada componente está limitado a 8 bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| red | int | El valor del componente rojo para el nuevo [Color](../../com.aspose.drawing/color). Los valores válidos son de 0 a 255. |
| green | int | El valor del componente verde para el nuevo [Color](../../com.aspose.drawing/color). Los valores válidos son de 0 a 255. |
| blue | int | El valor del componente azul para el nuevo [Color](../../com.aspose.drawing/color). Los valores válidos son de 0 a 255. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) that this method creates.
### fromArgb(int alpha, int red, int green, int blue) {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int alpha, int red, int green, int blue)
```


Crea una estructura Color a partir de los cuatro valores de componentes ARGB (alfa, rojo, verde y azul). Aunque este método permite pasar un valor de 32 bits para cada componente, el valor de cada componente está limitado a 8 bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alfa | int | El componente alfa. Los valores válidos son de 0 a 255. |
| rojo | int | El componente rojo. Los valores válidos son de 0 a 255. |
| verde | int | El componente verde. Los valores válidos son de 0 a 255. |
| azul | int | El componente azul. Los valores válidos son de 0 a 255. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The Color that this method creates.
### fromKnownColor(int color) {#fromKnownColor-int-}
```
public static Color fromKnownColor(int color)
```


Crea una estructura [Color](../../com.aspose.drawing/color) a partir del color predefinido especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color | int | Un elemento de la enumeración [KnownColor](../../com.aspose.drawing/knowncolor). |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) that this method creates.
### fromName(String name) {#fromName-java.lang.String-}
```
public static Color fromName(String name)
```


Crea una estructura [Color](../../com.aspose.drawing/color) a partir del nombre especificado de un color predefinido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Una cadena que es el nombre de un color predefinido. Los nombres válidos son los mismos que los nombres de los elementos de la enumeración [KnownColor](../../com.aspose.drawing/knowncolor). |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) that this method creates.
### op_Equality(Color left, Color right) {#op-Equality-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public static boolean op_Equality(Color left, Color right)
```


Comprueba si dos estructuras [Color](../../com.aspose.drawing/color) especificadas son equivalentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [Color](../../com.aspose.drawing/color) | El [Color](../../com.aspose.drawing/color) que está a la izquierda del operador de igualdad. |
| right | [Color](../../com.aspose.drawing/color) | El [Color](../../com.aspose.drawing/color) que está a la derecha del operador de igualdad. |

**Returns:**
boolean - `true` si las dos estructuras [Color](../../com.aspose.drawing/color) son iguales; de lo contrario, `false`.
### op_Inequality(Color left, Color right) {#op-Inequality-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public static boolean op_Inequality(Color left, Color right)
```


Comprueba si dos estructuras [Color](../../com.aspose.drawing/color) especificadas son diferentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [Color](../../com.aspose.drawing/color) | El [Color](../../com.aspose.drawing/color) que está a la izquierda del operador de desigualdad. |
| right | [Color](../../com.aspose.drawing/color) | El [Color](../../com.aspose.drawing/color) que está a la derecha del operador de desigualdad. |

**Returns:**
boolean - `true` si las dos estructuras [Color](../../com.aspose.drawing/color) son diferentes; de lo contrario, `false`.
### equals(Color other) {#equals-com.aspose.drawing.Color-}
```
public final boolean equals(Color other)
```


Comprueba si el color especificado es equivalente a este color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [Color](../../com.aspose.drawing/color) | El color a probar. |

**Returns:**
boolean - `` si el color especificado es equivalente a este color; de lo contrario, ``.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Comprueba si el objeto especificado es equivalente a este color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El objeto a probar. |

**Returns:**
boolean - `` si el objeto especificado es equivalente a este color; de lo contrario, ``.
### toArgb() {#toArgb--}
```
public final int toArgb()
```


Obtiene el valor ARGB de 32 bits de esta estructura Color.

**Returns:**
int - El valor ARGB de 32 bits de este Color.
### getBrightness() {#getBrightness--}
```
public final float getBrightness()
```


Obtiene el valor de brillo hue-saturation-brightness (HSB) de esta estructura [Color](../../com.aspose.drawing/color).

**Returns:**
float - El brillo de este [Color](../../com.aspose.drawing/color). El brillo varía de 0.0 a 1.0, donde 0.0 representa negro y 1.0 representa blanco.
### getHue() {#getHue--}
```
public final float getHue()
```


Obtiene el valor de tono hue-saturation-brightness (HSB), en grados, de esta estructura [Color](../../com.aspose.drawing/color).

**Returns:**
float - El matiz, en grados, de este java.awt.Color. El matiz se mide en grados, variando de 0.0 a 360.0, en el espacio de color HSB.
### getSaturation() {#getSaturation--}
```
public final float getSaturation()
```


Obtiene el valor de saturación hue-saturation-brightness (HSB) de esta estructura [Color](../../com.aspose.drawing/color).

**Returns:**
float - La saturación de este [Color](../../com.aspose.drawing/color). La saturación varía de 0.0 a 1.0, donde 0.0 es escala de grises y 1.0 es la máxima saturación.
### toKnownColor() {#toKnownColor--}
```
public final int toKnownColor()
```


Obtiene el valor [KnownColor](../../com.aspose.drawing/knowncolor) de esta estructura [Color](../../com.aspose.drawing/color).

**Returns:**
int - Un elemento de la enumeración [KnownColor](../../com.aspose.drawing/knowncolor), si el [Color](../../com.aspose.drawing/color) se crea a partir de un color predefinido usando el método `M:Color.FromName(System.String)` o el método `M:Color.FromKnownColor(KnownColor)`; de lo contrario, 0.
### toString() {#toString--}
```
public String toString()
```


Devuelve una String que representa esta instancia.

**Returns:**
java.lang.String - Una cadena que representa esta instancia.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta instancia.

**Returns:**
int - Un código hash para esta instancia, adecuado para su uso en algoritmos de hash y estructuras de datos como una tabla hash.
### isEquals(Color obj1, Color obj2) {#isEquals-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public static boolean isEquals(Color obj1, Color obj2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj1 | [Color](../../com.aspose.drawing/color) |  |
| obj2 | [Color](../../com.aspose.drawing/color) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static Color getEmpty()
```




**Returns:**
[Color](../../com.aspose.drawing/color)
### CloneTo(Color that) {#CloneTo-com.aspose.drawing.Color-}
```
public void CloneTo(Color that)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| that | [Color](../../com.aspose.drawing/color) |  |

### Clone() {#Clone--}
```
public Color Clone()
```




**Returns:**
[Color](../../com.aspose.drawing/color)
