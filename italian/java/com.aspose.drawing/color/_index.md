---
title: Color
second_title: Riferimento API di Aspose.Drawing per Java
description: Rappresenta un colore ARGB alfa rosso verde blu.
type: docs
weight: 14
url: /it/java/com.aspose.drawing/color/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Color extends Struct<Color> implements System.IEquatable<Color>, Cloneable
```

Rappresenta un colore ARGB (alpha, rosso, verde, blu).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Color()](#Color--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [EMPTY](#EMPTY) | Rappresenta un colore che è nullo. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTransparent()](#getTransparent--) | Restituisce un colore definito dal sistema. |
| [getAliceBlue()](#getAliceBlue--) | Restituisce un colore definito dal sistema che ha un valore ARGB di \\#FFF0F8FF. |
| [getAntiqueWhite()](#getAntiqueWhite--) | Restituisce un colore definito dal sistema che ha un valore ARGB di \\#FFFAEBD7. |
| [getAqua()](#getAqua--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF00FFFF. |
| [getAquamarine()](#getAquamarine--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF7FFFD4. |
| [getAzure()](#getAzure--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFF0FFFF. |
| [getBeige()](#getBeige--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFF5F5DC. |
| [getBisque()](#getBisque--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFE4C4. |
| [getBlack()](#getBlack--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF000000. |
| [getBlanchedAlmond()](#getBlanchedAlmond--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFEBCD. |
| [getBlue()](#getBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF0000FF. |
| [getBlueViolet()](#getBlueViolet--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF8A2BE2. |
| [getBrown()](#getBrown--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFA52A2A. |
| [getBurlyWood()](#getBurlyWood--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFDEB887. |
| [getCadetBlue()](#getCadetBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF5F9EA0. |
| [getChartreuse()](#getChartreuse--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF7FFF00. |
| [getChocolate()](#getChocolate--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFD2691E. |
| [getCoral()](#getCoral--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFF7F50. |
| [getCornflowerBlue()](#getCornflowerBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF6495ED. |
| [getCornsilk()](#getCornsilk--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFF8DC. |
| [getCrimson()](#getCrimson--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFDC143C. |
| [getCyan()](#getCyan--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF00FFFF. |
| [getDarkBlue()](#getDarkBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF00008B. |
| [getDarkCyan()](#getDarkCyan--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF008B8B. |
| [getDarkGoldenrod()](#getDarkGoldenrod--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFB8860B. |
| [getDarkGray()](#getDarkGray--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFA9A9A9. |
| [getDarkGreen()](#getDarkGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF006400. |
| [getDarkKhaki()](#getDarkKhaki--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFBDB76B. |
| [getDarkMagenta()](#getDarkMagenta--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF8B008B. |
| [getDarkOliveGreen()](#getDarkOliveGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF556B2F. |
| [getDarkOrange()](#getDarkOrange--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFF8C00. |
| [getDarkOrchid()](#getDarkOrchid--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF9932CC. |
| [getDarkRed()](#getDarkRed--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF8B0000. |
| [getDarkSalmon()](#getDarkSalmon--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFE9967A. |
| [getDarkSeaGreen()](#getDarkSeaGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF8FBC8F. |
| [getDarkSlateBlue()](#getDarkSlateBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF483D8B. |
| [getDarkSlateGray()](#getDarkSlateGray--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF2F4F4F. |
| [getDarkTurquoise()](#getDarkTurquoise--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF00CED1. |
| [getDarkViolet()](#getDarkViolet--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF9400D3. |
| [getDeepPink()](#getDeepPink--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFF1493. |
| [getDeepSkyBlue()](#getDeepSkyBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF00BFFF. |
| [getDimGray()](#getDimGray--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF696969. |
| [getDodgerBlue()](#getDodgerBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF1E90FF. |
| [getFirebrick()](#getFirebrick--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFB22222. |
| [getFloralWhite()](#getFloralWhite--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFFAF0. |
| [getForestGreen()](#getForestGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF228B22. |
| [getFuchsia()](#getFuchsia--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFF00FF. |
| [getGainsboro()](#getGainsboro--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFDCDCDC. |
| [getGhostWhite()](#getGhostWhite--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFF8F8FF. |
| [getGold()](#getGold--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFD700. |
| [getGoldenrod()](#getGoldenrod--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFDAA520. |
| [getGray()](#getGray--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF808080. |
| [getGreen()](#getGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF008000. |
| [getGreenYellow()](#getGreenYellow--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFADFF2F. |
| [getHoneydew()](#getHoneydew--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFF0FFF0. |
| [getHotPink()](#getHotPink--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFF69B4. |
| [getIndianRed()](#getIndianRed--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFCD5C5C. |
| [getIndigo()](#getIndigo--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF4B0082. |
| [getIvory()](#getIvory--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFFFF0. |
| [getKhaki()](#getKhaki--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFF0E68C. |
| [getLavender()](#getLavender--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFE6E6FA. |
| [getLavenderBlush()](#getLavenderBlush--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFF0F5. |
| [getLawnGreen()](#getLawnGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF7CFC00. |
| [getLemonChiffon()](#getLemonChiffon--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFFACD. |
| [getLightBlue()](#getLightBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFADD8E6. |
| [getLightCoral()](#getLightCoral--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFF08080. |
| [getLightCyan()](#getLightCyan--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFE0FFFF. |
| [getLightGoldenrodYellow()](#getLightGoldenrodYellow--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFAFAD2. |
| [getLightGreen()](#getLightGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF90EE90. |
| [getLightGray()](#getLightGray--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFD3D3D3. |
| [getLightPink()](#getLightPink--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFB6C1. |
| [getLightSalmon()](#getLightSalmon--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFA07A. |
| [getLightSeaGreen()](#getLightSeaGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF20B2AA. |
| [getLightSkyBlue()](#getLightSkyBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF87CEFA. |
| [getLightSlateGray()](#getLightSlateGray--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF778899. |
| [getLightSteelBlue()](#getLightSteelBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFB0C4DE. |
| [getLightYellow()](#getLightYellow--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFFFE0. |
| [getLime()](#getLime--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF00FF00. |
| [getLimeGreen()](#getLimeGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF32CD32. |
| [getLinen()](#getLinen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFAF0E6. |
| [getMagenta()](#getMagenta--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFF00FF. |
| [getMaroon()](#getMaroon--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF800000. |
| [getMediumAquamarine()](#getMediumAquamarine--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF66CDAA. |
| [getMediumBlue()](#getMediumBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF0000CD. |
| [getMediumOrchid()](#getMediumOrchid--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFBA55D3. |
| [getMediumPurple()](#getMediumPurple--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF9370DB. |
| [getMediumSeaGreen()](#getMediumSeaGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF3CB371. |
| [getMediumSlateBlue()](#getMediumSlateBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF7B68EE. |
| [getMediumSpringGreen()](#getMediumSpringGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF00FA9A. |
| [getMediumTurquoise()](#getMediumTurquoise--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF48D1CC. |
| [getMediumVioletRed()](#getMediumVioletRed--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFC71585. |
| [getMidnightBlue()](#getMidnightBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF191970. |
| [getMintCream()](#getMintCream--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFF5FFFA. |
| [getMistyRose()](#getMistyRose--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFE4E1. |
| [getMoccasin()](#getMoccasin--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFE4B5. |
| [getNavajoWhite()](#getNavajoWhite--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFDEAD. |
| [getNavy()](#getNavy--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF000080. |
| [getOldLace()](#getOldLace--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFDF5E6. |
| [getOlive()](#getOlive--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF808000. |
| [getOliveDrab()](#getOliveDrab--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF6B8E23. |
| [getOrange()](#getOrange--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFA500. |
| [getOrangeRed()](#getOrangeRed--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFF4500. |
| [getOrchid()](#getOrchid--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFDA70D6. |
| [getPaleGoldenrod()](#getPaleGoldenrod--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFEEE8AA. |
| [getPaleGreen()](#getPaleGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF98FB98. |
| [getPaleTurquoise()](#getPaleTurquoise--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFAFEEEE. |
| [getPaleVioletRed()](#getPaleVioletRed--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFDB7093. |
| [getPapayaWhip()](#getPapayaWhip--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFEFD5. |
| [getPeachPuff()](#getPeachPuff--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFDAB9. |
| [getPeru()](#getPeru--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFCD853F. |
| [getPink()](#getPink--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFC0CB. |
| [getPlum()](#getPlum--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFDDA0DD. |
| [getPowderBlue()](#getPowderBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFB0E0E6. |
| [getPurple()](#getPurple--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF800080. |
| [getRed()](#getRed--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFF0000. |
| [getRosyBrown()](#getRosyBrown--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFBC8F8F. |
| [getRoyalBlue()](#getRoyalBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF4169E1. |
| [getSaddleBrown()](#getSaddleBrown--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF8B4513. |
| [getSalmon()](#getSalmon--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFA8072. |
| [getSandyBrown()](#getSandyBrown--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFF4A460. |
| [getSeaGreen()](#getSeaGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF2E8B57. |
| [getSeaShell()](#getSeaShell--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFF5EE. |
| [getSienna()](#getSienna--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFA0522D. |
| [getSilver()](#getSilver--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFC0C0C0. |
| [getSkyBlue()](#getSkyBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF87CEEB. |
| [getSlateBlue()](#getSlateBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF6A5ACD. |
| [getSlateGray()](#getSlateGray--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF708090. |
| [getSnow()](#getSnow--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFFAFA. |
| [getSpringGreen()](#getSpringGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF00FF7F. |
| [getSteelBlue()](#getSteelBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF4682B4. |
| [getTan()](#getTan--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFD2B48C. |
| [getTeal()](#getTeal--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF008080. |
| [getThistle()](#getThistle--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFD8BFD8. |
| [getTomato()](#getTomato--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFF6347. |
| [getTurquoise()](#getTurquoise--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF40E0D0. |
| [getViolet()](#getViolet--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFEE82EE. |
| [getWheat()](#getWheat--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFF5DEB3. |
| [getWhite()](#getWhite--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFFFFF. |
| [getWhiteSmoke()](#getWhiteSmoke--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFF5F5F5. |
| [getYellow()](#getYellow--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFFF00. |
| [getYellowGreen()](#getYellowGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF9ACD32. |
| [getA()](#getA--) | Ottiene il valore del componente alfa di questa struttura [Color](../../com.aspose.drawing/color). |
| [getR()](#getR--) | Ottiene il valore del componente rosso di questa struttura [Color](../../com.aspose.drawing/color). |
| [getG()](#getG--) | Ottiene il valore del componente verde di questa struttura [Color](../../com.aspose.drawing/color). |
| [getB()](#getB--) | Ottiene il valore del componente blu di questa struttura [Color](../../com.aspose.drawing/color). |
| [isKnownColor()](#isKnownColor--) | Ottiene un valore che indica se questa struttura [Color](../../com.aspose.drawing/color) è un colore predefinito. |
| [isEmpty()](#isEmpty--) | Ottiene un valore che indica se questa struttura [Color](../../com.aspose.drawing/color) è non inizializzata. |
| [isNamedColor()](#isNamedColor--) | Ottiene un valore che indica se questa struttura [Color](../../com.aspose.drawing/color) è un colore con nome o un membro dell'enumerazione [KnownColor](../../com.aspose.drawing/knowncolor). |
| [isSystemColor()](#isSystemColor--) | Ottiene un valore che indica se questa struttura [Color](../../com.aspose.drawing/color) è un colore di sistema. |
| [getName()](#getName--) | Ottiene il nome di questa struttura [Color](../../com.aspose.drawing/color). |
| [fromArgb(int argb)](#fromArgb-int-) | Crea una struttura [Color](../../com.aspose.drawing/color) da un valore ARGB a 32 bit. |
| [fromArgb(int alpha, Color baseColor)](#fromArgb-int-com.aspose.drawing.Color-) | Crea una struttura [Color](../../com.aspose.drawing/color) dalla struttura [Color](../../com.aspose.drawing/color) specificata, ma con il nuovo valore alfa specificato. |
| [fromArgb(int red, int green, int blue)](#fromArgb-int-int-int-) | Crea una struttura [Color](../../com.aspose.drawing/color) dai valori di colore a 8 bit specificati (rosso, verde e blu). |
| [fromArgb(int alpha, int red, int green, int blue)](#fromArgb-int-int-int-int-) | Crea una struttura Color dai quattro valori dei componenti ARGB (alfa, rosso, verde e blu). |
| [fromKnownColor(int color)](#fromKnownColor-int-) | Crea una struttura [Color](../../com.aspose.drawing/color) dal colore predefinito specificato. |
| [fromName(String name)](#fromName-java.lang.String-) | Crea una struttura [Color](../../com.aspose.drawing/color) dal nome specificato di un colore predefinito. |
| [op_Equality(Color left, Color right)](#op-Equality-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Verifica se due strutture [Color](../../com.aspose.drawing/color) specificate sono equivalenti. |
| [op_Inequality(Color left, Color right)](#op-Inequality-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Verifica se due strutture [Color](../../com.aspose.drawing/color) specificate sono diverse. |
| [equals(Color other)](#equals-com.aspose.drawing.Color-) | Verifica se il colore specificato è equivalente a questo colore. |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se l'oggetto specificato è equivalente a questo colore. |
| [toArgb()](#toArgb--) | Restituisce il valore ARGB a 32 bit di questa struttura Color. |
| [getBrightness()](#getBrightness--) | Restituisce il valore di luminosità hue-saturation-brightness (HSB) per questa struttura [Color](../../com.aspose.drawing/color). |
| [getHue()](#getHue--) | Restituisce il valore di tonalità hue-saturation-brightness (HSB), in gradi, per questa struttura [Color](../../com.aspose.drawing/color). |
| [getSaturation()](#getSaturation--) | Restituisce il valore di saturazione hue-saturation-brightness (HSB) per questa struttura [Color](../../com.aspose.drawing/color). |
| [toKnownColor()](#toKnownColor--) | Restituisce il valore [KnownColor](../../com.aspose.drawing/knowncolor) di questa struttura [Color](../../com.aspose.drawing/color). |
| [toString()](#toString--) | Restituisce una Stringa che rappresenta questa istanza. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza. |
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


Rappresenta un colore che è nullo.

### getTransparent() {#getTransparent--}
```
public static Color getTransparent()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAliceBlue() {#getAliceBlue--}
```
public static Color getAliceBlue()
```


Restituisce un colore definito dal sistema che ha un valore ARGB di \\#FFF0F8FF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAntiqueWhite() {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```


Restituisce un colore definito dal sistema che ha un valore ARGB di \\#FFFAEBD7.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAqua() {#getAqua--}
```
public static Color getAqua()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF00FFFF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAquamarine() {#getAquamarine--}
```
public static Color getAquamarine()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF7FFFD4.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAzure() {#getAzure--}
```
public static Color getAzure()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFF0FFFF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBeige() {#getBeige--}
```
public static Color getBeige()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFF5F5DC.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBisque() {#getBisque--}
```
public static Color getBisque()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFE4C4.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBlack() {#getBlack--}
```
public static Color getBlack()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF000000.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBlanchedAlmond() {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFEBCD.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBlue() {#getBlue--}
```
public static Color getBlue()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF0000FF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBlueViolet() {#getBlueViolet--}
```
public static Color getBlueViolet()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF8A2BE2.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBrown() {#getBrown--}
```
public static Color getBrown()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFA52A2A.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBurlyWood() {#getBurlyWood--}
```
public static Color getBurlyWood()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFDEB887.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCadetBlue() {#getCadetBlue--}
```
public static Color getCadetBlue()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF5F9EA0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getChartreuse() {#getChartreuse--}
```
public static Color getChartreuse()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF7FFF00.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getChocolate() {#getChocolate--}
```
public static Color getChocolate()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFD2691E.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCoral() {#getCoral--}
```
public static Color getCoral()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFF7F50.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCornflowerBlue() {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF6495ED.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCornsilk() {#getCornsilk--}
```
public static Color getCornsilk()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFF8DC.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCrimson() {#getCrimson--}
```
public static Color getCrimson()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFDC143C.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCyan() {#getCyan--}
```
public static Color getCyan()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF00FFFF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkBlue() {#getDarkBlue--}
```
public static Color getDarkBlue()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF00008B.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkCyan() {#getDarkCyan--}
```
public static Color getDarkCyan()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF008B8B.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkGoldenrod() {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFB8860B.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkGray() {#getDarkGray--}
```
public static Color getDarkGray()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFA9A9A9.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkGreen() {#getDarkGreen--}
```
public static Color getDarkGreen()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF006400.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkKhaki() {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFBDB76B.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkMagenta() {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF8B008B.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkOliveGreen() {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF556B2F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkOrange() {#getDarkOrange--}
```
public static Color getDarkOrange()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFF8C00.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkOrchid() {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF9932CC.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkRed() {#getDarkRed--}
```
public static Color getDarkRed()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF8B0000.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkSalmon() {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFE9967A.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkSeaGreen() {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF8FBC8F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkSlateBlue() {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF483D8B.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkSlateGray() {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF2F4F4F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkTurquoise() {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF00CED1.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkViolet() {#getDarkViolet--}
```
public static Color getDarkViolet()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF9400D3.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDeepPink() {#getDeepPink--}
```
public static Color getDeepPink()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFF1493.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDeepSkyBlue() {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF00BFFF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDimGray() {#getDimGray--}
```
public static Color getDimGray()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF696969.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDodgerBlue() {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF1E90FF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getFirebrick() {#getFirebrick--}
```
public static Color getFirebrick()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFB22222.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getFloralWhite() {#getFloralWhite--}
```
public static Color getFloralWhite()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFFAF0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getForestGreen() {#getForestGreen--}
```
public static Color getForestGreen()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF228B22.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getFuchsia() {#getFuchsia--}
```
public static Color getFuchsia()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFF00FF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGainsboro() {#getGainsboro--}
```
public static Color getGainsboro()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFDCDCDC.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGhostWhite() {#getGhostWhite--}
```
public static Color getGhostWhite()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFF8F8FF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGold() {#getGold--}
```
public static Color getGold()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFD700.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGoldenrod() {#getGoldenrod--}
```
public static Color getGoldenrod()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFDAA520.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGray() {#getGray--}
```
public static Color getGray()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF808080.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) strcture representing a system-defined color. `1`
### getGreen() {#getGreen--}
```
public static Color getGreen()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF008000.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGreenYellow() {#getGreenYellow--}
```
public static Color getGreenYellow()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFADFF2F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getHoneydew() {#getHoneydew--}
```
public static Color getHoneydew()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFF0FFF0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getHotPink() {#getHotPink--}
```
public static Color getHotPink()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFF69B4.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getIndianRed() {#getIndianRed--}
```
public static Color getIndianRed()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFCD5C5C.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getIndigo() {#getIndigo--}
```
public static Color getIndigo()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF4B0082.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getIvory() {#getIvory--}
```
public static Color getIvory()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFFFF0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getKhaki() {#getKhaki--}
```
public static Color getKhaki()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFF0E68C.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLavender() {#getLavender--}
```
public static Color getLavender()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFE6E6FA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLavenderBlush() {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFF0F5.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLawnGreen() {#getLawnGreen--}
```
public static Color getLawnGreen()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF7CFC00.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLemonChiffon() {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFFACD.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightBlue() {#getLightBlue--}
```
public static Color getLightBlue()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFADD8E6.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightCoral() {#getLightCoral--}
```
public static Color getLightCoral()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFF08080.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightCyan() {#getLightCyan--}
```
public static Color getLightCyan()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFE0FFFF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightGoldenrodYellow() {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFAFAD2.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightGreen() {#getLightGreen--}
```
public static Color getLightGreen()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF90EE90.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightGray() {#getLightGray--}
```
public static Color getLightGray()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFD3D3D3.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightPink() {#getLightPink--}
```
public static Color getLightPink()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFB6C1.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSalmon() {#getLightSalmon--}
```
public static Color getLightSalmon()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFA07A.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSeaGreen() {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF20B2AA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSkyBlue() {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF87CEFA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSlateGray() {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF778899.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSteelBlue() {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFB0C4DE.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightYellow() {#getLightYellow--}
```
public static Color getLightYellow()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFFFE0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLime() {#getLime--}
```
public static Color getLime()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF00FF00.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLimeGreen() {#getLimeGreen--}
```
public static Color getLimeGreen()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF32CD32.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLinen() {#getLinen--}
```
public static Color getLinen()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFAF0E6.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMagenta() {#getMagenta--}
```
public static Color getMagenta()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFF00FF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMaroon() {#getMaroon--}
```
public static Color getMaroon()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF800000.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumAquamarine() {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF66CDAA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumBlue() {#getMediumBlue--}
```
public static Color getMediumBlue()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF0000CD.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumOrchid() {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFBA55D3.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumPurple() {#getMediumPurple--}
```
public static Color getMediumPurple()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF9370DB.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumSeaGreen() {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF3CB371.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumSlateBlue() {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF7B68EE.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumSpringGreen() {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF00FA9A.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumTurquoise() {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF48D1CC.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumVioletRed() {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFC71585.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMidnightBlue() {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF191970.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMintCream() {#getMintCream--}
```
public static Color getMintCream()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFF5FFFA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMistyRose() {#getMistyRose--}
```
public static Color getMistyRose()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFE4E1.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMoccasin() {#getMoccasin--}
```
public static Color getMoccasin()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFE4B5.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getNavajoWhite() {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFDEAD.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getNavy() {#getNavy--}
```
public static Color getNavy()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF000080.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOldLace() {#getOldLace--}
```
public static Color getOldLace()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFDF5E6.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOlive() {#getOlive--}
```
public static Color getOlive()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF808000.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOliveDrab() {#getOliveDrab--}
```
public static Color getOliveDrab()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF6B8E23.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOrange() {#getOrange--}
```
public static Color getOrange()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFA500.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOrangeRed() {#getOrangeRed--}
```
public static Color getOrangeRed()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFF4500.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOrchid() {#getOrchid--}
```
public static Color getOrchid()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFDA70D6.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPaleGoldenrod() {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFEEE8AA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPaleGreen() {#getPaleGreen--}
```
public static Color getPaleGreen()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF98FB98.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPaleTurquoise() {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFAFEEEE.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPaleVioletRed() {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFDB7093.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPapayaWhip() {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFEFD5.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPeachPuff() {#getPeachPuff--}
```
public static Color getPeachPuff()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFDAB9.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPeru() {#getPeru--}
```
public static Color getPeru()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFCD853F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPink() {#getPink--}
```
public static Color getPink()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFC0CB.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPlum() {#getPlum--}
```
public static Color getPlum()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFDDA0DD.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPowderBlue() {#getPowderBlue--}
```
public static Color getPowderBlue()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFB0E0E6.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPurple() {#getPurple--}
```
public static Color getPurple()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF800080.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getRed() {#getRed--}
```
public static Color getRed()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFF0000.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getRosyBrown() {#getRosyBrown--}
```
public static Color getRosyBrown()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFBC8F8F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getRoyalBlue() {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF4169E1.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSaddleBrown() {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF8B4513.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSalmon() {#getSalmon--}
```
public static Color getSalmon()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFA8072.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSandyBrown() {#getSandyBrown--}
```
public static Color getSandyBrown()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFF4A460.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSeaGreen() {#getSeaGreen--}
```
public static Color getSeaGreen()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF2E8B57.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSeaShell() {#getSeaShell--}
```
public static Color getSeaShell()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFF5EE.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSienna() {#getSienna--}
```
public static Color getSienna()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFA0522D.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSilver() {#getSilver--}
```
public static Color getSilver()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFC0C0C0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSkyBlue() {#getSkyBlue--}
```
public static Color getSkyBlue()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF87CEEB.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSlateBlue() {#getSlateBlue--}
```
public static Color getSlateBlue()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF6A5ACD.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSlateGray() {#getSlateGray--}
```
public static Color getSlateGray()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF708090.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSnow() {#getSnow--}
```
public static Color getSnow()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFFAFA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSpringGreen() {#getSpringGreen--}
```
public static Color getSpringGreen()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF00FF7F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSteelBlue() {#getSteelBlue--}
```
public static Color getSteelBlue()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF4682B4.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getTan() {#getTan--}
```
public static Color getTan()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFD2B48C.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getTeal() {#getTeal--}
```
public static Color getTeal()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF008080.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getThistle() {#getThistle--}
```
public static Color getThistle()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFD8BFD8.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getTomato() {#getTomato--}
```
public static Color getTomato()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFF6347.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getTurquoise() {#getTurquoise--}
```
public static Color getTurquoise()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF40E0D0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getViolet() {#getViolet--}
```
public static Color getViolet()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFEE82EE.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getWheat() {#getWheat--}
```
public static Color getWheat()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFF5DEB3.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getWhite() {#getWhite--}
```
public static Color getWhite()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFFFFF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getWhiteSmoke() {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFF5F5F5.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getYellow() {#getYellow--}
```
public static Color getYellow()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FFFFFF00.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getYellowGreen() {#getYellowGreen--}
```
public static Color getYellowGreen()
```


Ottiene un colore definito dal sistema che ha un valore ARGB di \#FF9ACD32.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getA() {#getA--}
```
public final int getA()
```


Ottiene il valore del componente alfa di questa struttura [Color](../../com.aspose.drawing/color).

**Returns:**
int - Il valore del componente alfa di questo [Color](../../com.aspose.drawing/color).
### getR() {#getR--}
```
public final int getR()
```


Ottiene il valore del componente rosso di questa struttura [Color](../../com.aspose.drawing/color).

**Returns:**
int - Il valore del componente rosso di questo [Color](../../com.aspose.drawing/color).
### getG() {#getG--}
```
public final int getG()
```


Ottiene il valore del componente verde di questa struttura [Color](../../com.aspose.drawing/color).

**Returns:**
int - Il valore del componente verde di questo [Color](../../com.aspose.drawing/color).
### getB() {#getB--}
```
public final int getB()
```


Ottiene il valore del componente blu di questa struttura [Color](../../com.aspose.drawing/color).

**Returns:**
int - Il valore del componente blu di questo [Color](../../com.aspose.drawing/color).
### isKnownColor() {#isKnownColor--}
```
public final boolean isKnownColor()
```


Restituisce un valore che indica se questa struttura [Color](../../com.aspose.drawing/color) è un colore predefinito. I colori predefiniti sono rappresentati dagli elementi dell'enumerazione [KnownColor](../../com.aspose.drawing/knowncolor).

Valore: `true` se questo [Color](../../com.aspose.drawing/color) è stato creato da un colore predefinito utilizzando il metodo `M:Color.FromName(System.String)` o il metodo `M:Color.FromKnownColor(System.Drawing.KnownColor)`; altrimenti, `false`.

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Ottiene un valore che indica se questa struttura [Color](../../com.aspose.drawing/color) è non inizializzata.

Valore: Questa proprietà restituisce true se questo colore non è inizializzato; altrimenti, false.

**Returns:**
boolean
### isNamedColor() {#isNamedColor--}
```
public final boolean isNamedColor()
```


Ottiene un valore che indica se questa struttura [Color](../../com.aspose.drawing/color) è un colore con nome o un membro dell'enumerazione [KnownColor](../../com.aspose.drawing/knowncolor).

Valore: `true` se questo [Color](../../com.aspose.drawing/color) è stato creato utilizzando il metodo `M:Color.FromName(System.String)` o il metodo `M:Color.FromKnownColor(System.Drawing.KnownColor)`; altrimenti, `false`.

**Returns:**
boolean
### isSystemColor() {#isSystemColor--}
```
public final boolean isSystemColor()
```


Restituisce un valore che indica se questa struttura [Color](../../com.aspose.drawing/color) è un colore di sistema. Un colore di sistema è un colore utilizzato in un elemento di visualizzazione di Windows. I colori di sistema sono rappresentati dagli elementi dell'enumerazione [KnownColor](../../com.aspose.drawing/knowncolor).

Valore: `true` se questo [Color](../../com.aspose.drawing/color) è stato creato da un colore di sistema utilizzando il metodo `M:Color.FromName(System.String)` o il metodo `M:Color.FromKnownColor(System.Drawing.KnownColor)`; altrimenti, `false`.

**Returns:**
boolean
### getName() {#getName--}
```
public final String getName()
```


Ottiene il nome di questa struttura [Color](../../com.aspose.drawing/color).

**Returns:**
java.lang.String
### fromArgb(int argb) {#fromArgb-int-}
```
public static Color fromArgb(int argb)
```


Crea una struttura [Color](../../com.aspose.drawing/color) da un valore ARGB a 32 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argb | int | Un valore che specifica il valore ARGB a 32 bit. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that this method creates.
### fromArgb(int alpha, Color baseColor) {#fromArgb-int-com.aspose.drawing.Color-}
```
public static Color fromArgb(int alpha, Color baseColor)
```


Crea una struttura [Color](../../com.aspose.drawing/color) dalla struttura [Color](../../com.aspose.drawing/color) specificata, ma con il nuovo valore alfa specificato. Sebbene questo metodo consenta di passare un valore a 32 bit per il valore alfa, il valore è limitato a 8 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alpha | int | Il valore alfa per il nuovo [Color](../../com.aspose.drawing/color). I valori validi sono da 0 a 255. |
| baseColor | [Color](../../com.aspose.drawing/color) | Il [Color](../../com.aspose.drawing/color) da cui creare il nuovo [Color](../../com.aspose.drawing/color). |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) that this method creates.
### fromArgb(int red, int green, int blue) {#fromArgb-int-int-int-}
```
public static Color fromArgb(int red, int green, int blue)
```


Crea una struttura [Color](../../com.aspose.drawing/color) dai valori di colore a 8 bit specificati (rosso, verde e blu). Il valore alpha è implicitamente 255 (completamente opaco). Sebbene questo metodo consenta di passare un valore a 32 bit per ciascun componente del colore, il valore di ogni componente è limitato a 8 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| red | int | Il valore del componente rosso per il nuovo [Color](../../com.aspose.drawing/color). I valori validi sono da 0 a 255. |
| green | int | Il valore del componente verde per il nuovo [Color](../../com.aspose.drawing/color). I valori validi sono da 0 a 255. |
| blue | int | Il valore del componente blu per il nuovo [Color](../../com.aspose.drawing/color). I valori validi sono da 0 a 255. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) that this method creates.
### fromArgb(int alpha, int red, int green, int blue) {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int alpha, int red, int green, int blue)
```


Crea una struttura Color dai quattro valori dei componenti ARGB (alpha, rosso, verde e blu). Sebbene questo metodo consenta di passare un valore a 32 bit per ciascun componente, il valore di ogni componente è limitato a 8 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alpha | int | Il componente alpha. I valori validi sono da 0 a 255. |
| rosso | int | Il componente rosso. I valori validi sono da 0 a 255. |
| verde | int | Il componente verde. I valori validi sono da 0 a 255. |
| blu | int | Il componente blu. I valori validi sono da 0 a 255. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The Color that this method creates.
### fromKnownColor(int color) {#fromKnownColor-int-}
```
public static Color fromKnownColor(int color)
```


Crea una struttura [Color](../../com.aspose.drawing/color) dal colore predefinito specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| color | int | Un elemento dell'enumerazione [KnownColor](../../com.aspose.drawing/knowncolor). |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) that this method creates.
### fromName(String name) {#fromName-java.lang.String-}
```
public static Color fromName(String name)
```


Crea una struttura [Color](../../com.aspose.drawing/color) dal nome specificato di un colore predefinito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Una stringa che è il nome di un colore predefinito. I nomi validi sono gli stessi dei nomi degli elementi dell'enumerazione [KnownColor](../../com.aspose.drawing/knowncolor). |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) that this method creates.
### op_Equality(Color left, Color right) {#op-Equality-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public static boolean op_Equality(Color left, Color right)
```


Verifica se due strutture [Color](../../com.aspose.drawing/color) specificate sono equivalenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [Color](../../com.aspose.drawing/color) | Il [Color](../../com.aspose.drawing/color) che si trova a sinistra dell'operatore di uguaglianza. |
| right | [Color](../../com.aspose.drawing/color) | Il [Color](../../com.aspose.drawing/color) che si trova a destra dell'operatore di uguaglianza. |

**Returns:**
boolean - `true` se le due strutture [Color](../../com.aspose.drawing/color) sono uguali; altrimenti, `false`.
### op_Inequality(Color left, Color right) {#op-Inequality-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public static boolean op_Inequality(Color left, Color right)
```


Verifica se due strutture [Color](../../com.aspose.drawing/color) specificate sono diverse.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [Color](../../com.aspose.drawing/color) | Il [Color](../../com.aspose.drawing/color) che si trova a sinistra dell'operatore di disuguaglianza. |
| right | [Color](../../com.aspose.drawing/color) | Il [Color](../../com.aspose.drawing/color) che si trova a destra dell'operatore di disuguaglianza. |

**Returns:**
boolean - `true` se le due strutture [Color](../../com.aspose.drawing/color) sono diverse; altrimenti, `false`.
### equals(Color other) {#equals-com.aspose.drawing.Color-}
```
public final boolean equals(Color other)
```


Verifica se il colore specificato è equivalente a questo colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [Color](../../com.aspose.drawing/color) | Il colore da testare. |

**Returns:**
boolean - `` se il colore specificato è equivalente a questo colore; altrimenti, ``.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Verifica se l'oggetto specificato è equivalente a questo colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'oggetto da testare. |

**Returns:**
boolean - `` se l'oggetto specificato è equivalente a questo colore; altrimenti, ``.
### toArgb() {#toArgb--}
```
public final int toArgb()
```


Restituisce il valore ARGB a 32 bit di questa struttura Color.

**Returns:**
int - Il valore ARGB a 32 bit di questo Color.
### getBrightness() {#getBrightness--}
```
public final float getBrightness()
```


Restituisce il valore di luminosità hue-saturation-brightness (HSB) per questa struttura [Color](../../com.aspose.drawing/color).

**Returns:**
float - La luminosità di questo [Color](../../com.aspose.drawing/color). La luminosità varia da 0.0 a 1.0, dove 0.0 rappresenta il nero e 1.0 rappresenta il bianco.
### getHue() {#getHue--}
```
public final float getHue()
```


Restituisce il valore di tonalità hue-saturation-brightness (HSB), in gradi, per questa struttura [Color](../../com.aspose.drawing/color).

**Returns:**
float - La tonalità, in gradi, di questo java.awt.Color. La tonalità è misurata in gradi, variando da 0.0 a 360.0, nello spazio colore HSB.
### getSaturation() {#getSaturation--}
```
public final float getSaturation()
```


Restituisce il valore di saturazione hue-saturation-brightness (HSB) per questa struttura [Color](../../com.aspose.drawing/color).

**Returns:**
float - La saturazione di questo [Color](../../com.aspose.drawing/color). La saturazione varia da 0.0 a 1.0, dove 0.0 è in scala di grigi e 1.0 è la massima saturazione.
### toKnownColor() {#toKnownColor--}
```
public final int toKnownColor()
```


Restituisce il valore [KnownColor](../../com.aspose.drawing/knowncolor) di questa struttura [Color](../../com.aspose.drawing/color).

**Returns:**
int - Un elemento dell'enumerazione [KnownColor](../../com.aspose.drawing/knowncolor), se il [Color](../../com.aspose.drawing/color) è creato da un colore predefinito utilizzando il metodo `M:Color.FromName(System.String)` o il metodo `M:Color.FromKnownColor(KnownColor)`; altrimenti, 0.
### toString() {#toString--}
```
public String toString()
```


Restituisce una Stringa che rappresenta questa istanza.

**Returns:**
java.lang.String - Una stringa che rappresenta questa istanza.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questa istanza.

**Returns:**
int - Un codice hash per questa istanza, adatto per l'uso in algoritmi di hashing e strutture dati come una tabella hash.
### isEquals(Color obj1, Color obj2) {#isEquals-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public static boolean isEquals(Color obj1, Color obj2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| that | [Color](../../com.aspose.drawing/color) |  |

### Clone() {#Clone--}
```
public Color Clone()
```




**Returns:**
[Color](../../com.aspose.drawing/color)
