---
title: Färg
second_title: Aspose.Drawing för Java API‑referens
description: Representerar en ARGB alfa röd grön blå färg.
type: docs
weight: 14
url: /sv/java/com.aspose.drawing/color/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Color extends Struct<Color> implements System.IEquatable<Color>, Cloneable
```

Representerar en ARGB (alpha, röd, grön, blå) färg.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Color()](#Color--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [EMPTY](#EMPTY) | Representerar en färg som är null. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTransparent()](#getTransparent--) | Hämtar en systemdefinierad färg. |
| [getAliceBlue()](#getAliceBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFF0F8FF. |
| [getAntiqueWhite()](#getAntiqueWhite--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFAEBD7. |
| [getAqua()](#getAqua--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF00FFFF. |
| [getAquamarine()](#getAquamarine--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF7FFFD4. |
| [getAzure()](#getAzure--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFF0FFFF. |
| [getBeige()](#getBeige--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFF5F5DC. |
| [getBisque()](#getBisque--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFFFE4C4. |
| [getBlack()](#getBlack--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF000000. |
| [getBlanchedAlmond()](#getBlanchedAlmond--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFFFEBCD. |
| [getBlue()](#getBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF0000FF. |
| [getBlueViolet()](#getBlueViolet--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF8A2BE2. |
| [getBrown()](#getBrown--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFA52A2A. |
| [getBurlyWood()](#getBurlyWood--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFDEB887. |
| [getCadetBlue()](#getCadetBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF5F9EA0. |
| [getChartreuse()](#getChartreuse--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF7FFF00. |
| [getChocolate()](#getChocolate--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFD2691E. |
| [getCoral()](#getCoral--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFFF7F50. |
| [getCornflowerBlue()](#getCornflowerBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF6495ED. |
| [getCornsilk()](#getCornsilk--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFFFF8DC. |
| [getCrimson()](#getCrimson--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFDC143C. |
| [getCyan()](#getCyan--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF00FFFF. |
| [getDarkBlue()](#getDarkBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF00008B. |
| [getDarkCyan()](#getDarkCyan--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF008B8B. |
| [getDarkGoldenrod()](#getDarkGoldenrod--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFB8860B. |
| [getDarkGray()](#getDarkGray--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFA9A9A9. |
| [getDarkGreen()](#getDarkGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF006400. |
| [getDarkKhaki()](#getDarkKhaki--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFBDB76B. |
| [getDarkMagenta()](#getDarkMagenta--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF8B008B. |
| [getDarkOliveGreen()](#getDarkOliveGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF556B2F. |
| [getDarkOrange()](#getDarkOrange--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFF8C00. |
| [getDarkOrchid()](#getDarkOrchid--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF9932CC. |
| [getDarkRed()](#getDarkRed--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF8B0000. |
| [getDarkSalmon()](#getDarkSalmon--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFE9967A. |
| [getDarkSeaGreen()](#getDarkSeaGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF8FBC8F. |
| [getDarkSlateBlue()](#getDarkSlateBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF483D8B. |
| [getDarkSlateGray()](#getDarkSlateGray--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF2F4F4F. |
| [getDarkTurquoise()](#getDarkTurquoise--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF00CED1. |
| [getDarkViolet()](#getDarkViolet--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF9400D3. |
| [getDeepPink()](#getDeepPink--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFF1493. |
| [getDeepSkyBlue()](#getDeepSkyBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF00BFFF. |
| [getDimGray()](#getDimGray--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF696969. |
| [getDodgerBlue()](#getDodgerBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF1E90FF. |
| [getFirebrick()](#getFirebrick--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFB22222. |
| [getFloralWhite()](#getFloralWhite--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFFAF0. |
| [getForestGreen()](#getForestGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF228B22. |
| [getFuchsia()](#getFuchsia--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFF00FF. |
| [getGainsboro()](#getGainsboro--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFDCDCDC. |
| [getGhostWhite()](#getGhostWhite--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFF8F8FF. |
| [getGold()](#getGold--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFD700. |
| [getGoldenrod()](#getGoldenrod--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFDAA520. |
| [getGray()](#getGray--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF808080. |
| [getGreen()](#getGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF008000. |
| [getGreenYellow()](#getGreenYellow--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFADFF2F. |
| [getHoneydew()](#getHoneydew--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFF0FFF0. |
| [getHotPink()](#getHotPink--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFF69B4. |
| [getIndianRed()](#getIndianRed--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFCD5C5C. |
| [getIndigo()](#getIndigo--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF4B0082. |
| [getIvory()](#getIvory--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFFFF0. |
| [getKhaki()](#getKhaki--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFF0E68C. |
| [getLavender()](#getLavender--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFE6E6FA. |
| [getLavenderBlush()](#getLavenderBlush--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFF0F5. |
| [getLawnGreen()](#getLawnGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF7CFC00. |
| [getLemonChiffon()](#getLemonChiffon--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFFACD. |
| [getLightBlue()](#getLightBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFADD8E6. |
| [getLightCoral()](#getLightCoral--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFF08080. |
| [getLightCyan()](#getLightCyan--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFE0FFFF. |
| [getLightGoldenrodYellow()](#getLightGoldenrodYellow--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFAFAD2. |
| [getLightGreen()](#getLightGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF90EE90. |
| [getLightGray()](#getLightGray--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFD3D3D3. |
| [getLightPink()](#getLightPink--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFB6C1. |
| [getLightSalmon()](#getLightSalmon--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFA07A. |
| [getLightSeaGreen()](#getLightSeaGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF20B2AA. |
| [getLightSkyBlue()](#getLightSkyBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF87CEFA. |
| [getLightSlateGray()](#getLightSlateGray--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF778899. |
| [getLightSteelBlue()](#getLightSteelBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFB0C4DE. |
| [getLightYellow()](#getLightYellow--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFFFE0. |
| [getLime()](#getLime--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF00FF00. |
| [getLimeGreen()](#getLimeGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF32CD32. |
| [getLinen()](#getLinen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFAF0E6. |
| [getMagenta()](#getMagenta--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFF00FF. |
| [getMaroon()](#getMaroon--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF800000. |
| [getMediumAquamarine()](#getMediumAquamarine--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF66CDAA. |
| [getMediumBlue()](#getMediumBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF0000CD. |
| [getMediumOrchid()](#getMediumOrchid--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFBA55D3. |
| [getMediumPurple()](#getMediumPurple--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF9370DB. |
| [getMediumSeaGreen()](#getMediumSeaGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF3CB371. |
| [getMediumSlateBlue()](#getMediumSlateBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF7B68EE. |
| [getMediumSpringGreen()](#getMediumSpringGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF00FA9A. |
| [getMediumTurquoise()](#getMediumTurquoise--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF48D1CC. |
| [getMediumVioletRed()](#getMediumVioletRed--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFC71585. |
| [getMidnightBlue()](#getMidnightBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF191970. |
| [getMintCream()](#getMintCream--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFF5FFFA. |
| [getMistyRose()](#getMistyRose--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFE4E1. |
| [getMoccasin()](#getMoccasin--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFE4B5. |
| [getNavajoWhite()](#getNavajoWhite--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFDEAD. |
| [getNavy()](#getNavy--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF000080. |
| [getOldLace()](#getOldLace--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFDF5E6. |
| [getOlive()](#getOlive--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF808000. |
| [getOliveDrab()](#getOliveDrab--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF6B8E23. |
| [getOrange()](#getOrange--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFA500. |
| [getOrangeRed()](#getOrangeRed--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFF4500. |
| [getOrchid()](#getOrchid--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFDA70D6. |
| [getPaleGoldenrod()](#getPaleGoldenrod--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFEEE8AA. |
| [getPaleGreen()](#getPaleGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF98FB98. |
| [getPaleTurquoise()](#getPaleTurquoise--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFAFEEEE. |
| [getPaleVioletRed()](#getPaleVioletRed--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFDB7093. |
| [getPapayaWhip()](#getPapayaWhip--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFEFD5. |
| [getPeachPuff()](#getPeachPuff--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFDAB9. |
| [getPeru()](#getPeru--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFCD853F. |
| [getPink()](#getPink--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFC0CB. |
| [getPlum()](#getPlum--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFDDA0DD. |
| [getPowderBlue()](#getPowderBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFB0E0E6. |
| [getPurple()](#getPurple--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF800080. |
| [getRed()](#getRed--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFF0000. |
| [getRosyBrown()](#getRosyBrown--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFBC8F8F. |
| [getRoyalBlue()](#getRoyalBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF4169E1. |
| [getSaddleBrown()](#getSaddleBrown--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF8B4513. |
| [getSalmon()](#getSalmon--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFA8072. |
| [getSandyBrown()](#getSandyBrown--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFF4A460. |
| [getSeaGreen()](#getSeaGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF2E8B57. |
| [getSeaShell()](#getSeaShell--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFF5EE. |
| [getSienna()](#getSienna--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFA0522D. |
| [getSilver()](#getSilver--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFC0C0C0. |
| [getSkyBlue()](#getSkyBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF87CEEB. |
| [getSlateBlue()](#getSlateBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF6A5ACD. |
| [getSlateGray()](#getSlateGray--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF708090. |
| [getSnow()](#getSnow--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFFAFA. |
| [getSpringGreen()](#getSpringGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF00FF7F. |
| [getSteelBlue()](#getSteelBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF4682B4. |
| [getTan()](#getTan--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFD2B48C. |
| [getTeal()](#getTeal--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF008080. |
| [getThistle()](#getThistle--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFD8BFD8. |
| [getTomato()](#getTomato--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFF6347. |
| [getTurquoise()](#getTurquoise--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF40E0D0. |
| [getViolet()](#getViolet--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFEE82EE. |
| [getWheat()](#getWheat--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFF5DEB3. |
| [getWhite()](#getWhite--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFFFFF. |
| [getWhiteSmoke()](#getWhiteSmoke--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFF5F5F5. |
| [getYellow()](#getYellow--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFFF00. |
| [getYellowGreen()](#getYellowGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF9ACD32. |
| [getA()](#getA--) | Hämtar alfa‑komponentens värde för den här [Color](../../com.aspose.drawing/color)-strukturen. |
| [getR()](#getR--) | Hämtar röd‑komponentens värde för den här [Color](../../com.aspose.drawing/color)-strukturen. |
| [getG()](#getG--) | Hämtar grön‑komponentens värde för den här [Color](../../com.aspose.drawing/color)-strukturen. |
| [getB()](#getB--) | Hämtar blå‑komponentens värde för den här [Color](../../com.aspose.drawing/color)-strukturen. |
| [isKnownColor()](#isKnownColor--) | Hämtar ett värde som anger om den här [Color](../../com.aspose.drawing/color)-strukturen är en fördefinierad färg. |
| [isEmpty()](#isEmpty--) | Hämtar ett värde som anger om den här [Color](../../com.aspose.drawing/color)-strukturen är oinitierad. |
| [isNamedColor()](#isNamedColor--) | Hämtar ett värde som anger om den här [Color](../../com.aspose.drawing/color)-strukturen är en namngiven färg eller en medlem av [KnownColor](../../com.aspose.drawing/knowncolor)-enumerationen. |
| [isSystemColor()](#isSystemColor--) | Hämtar ett värde som anger om den här [Color](../../com.aspose.drawing/color)-strukturen är en systemfärg. |
| [getName()](#getName--) | Hämtar namnet på den här [Color](../../com.aspose.drawing/color). |
| [fromArgb(int argb)](#fromArgb-int-) | Skapar en [Color](../../com.aspose.drawing/color)-struktur från ett 32‑bitars ARGB‑värde. |
| [fromArgb(int alpha, Color baseColor)](#fromArgb-int-com.aspose.drawing.Color-) | Skapar en [Color](../../com.aspose.drawing/color)-struktur från den angivna [Color](../../com.aspose.drawing/color)-strukturen, men med det nya angivna alfa‑värdet. |
| [fromArgb(int red, int green, int blue)](#fromArgb-int-int-int-) | Skapar en [Color](../../com.aspose.drawing/color)-struktur från de angivna 8‑bitars färgvärdena (röd, grön och blå). |
| [fromArgb(int alpha, int red, int green, int blue)](#fromArgb-int-int-int-int-) | Skapar en Color‑struktur från de fyra ARGB‑komponenterna (alfa, röd, grön och blå). |
| [fromKnownColor(int color)](#fromKnownColor-int-) | Skapar en [Color](../../com.aspose.drawing/color)-struktur från den angivna fördefinierade färgen. |
| [fromName(String name)](#fromName-java.lang.String-) | Skapar en [Color](../../com.aspose.drawing/color) struktur från det angivna namnet på en fördefinierad färg. |
| [op_Equality(Color left, Color right)](#op-Equality-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Testar om två angivna [Color](../../com.aspose.drawing/color) strukturer är ekvivalenta. |
| [op_Inequality(Color left, Color right)](#op-Inequality-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Testar om två angivna [Color](../../com.aspose.drawing/color) strukturer är olika. |
| [equals(Color other)](#equals-com.aspose.drawing.Color-) | Testar om den angivna färgen är ekvivalent med denna färg. |
| [equals(Object obj)](#equals-java.lang.Object-) | Testar om det angivna objektet är ekvivalent med denna färg. |
| [toArgb()](#toArgb--) | Hämtar 32-bitars ARGB‑värdet för denna Color‑struktur. |
| [getBrightness()](#getBrightness--) | Hämtar ljusstyrkevärdet för hue‑saturation‑brightness (HSB) för denna [Color](../../com.aspose.drawing/color) struktur. |
| [getHue()](#getHue--) | Hämtar nyansvärdet för hue‑saturation‑brightness (HSB), i grader, för denna [Color](../../com.aspose.drawing/color) struktur. |
| [getSaturation()](#getSaturation--) | Hämtar mättnadsvärdet för hue‑saturation‑brightness (HSB) för denna [Color](../../com.aspose.drawing/color) struktur. |
| [toKnownColor()](#toKnownColor--) | Hämtar [KnownColor](../../com.aspose.drawing/knowncolor)-värdet för denna [Color](../../com.aspose.drawing/color) struktur. |
| [toString()](#toString--) | Returnerar en sträng som representerar detta objekt. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för denna instans. |
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


Representerar en färg som är null.

### getTransparent() {#getTransparent--}
```
public static Color getTransparent()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAliceBlue() {#getAliceBlue--}
```
public static Color getAliceBlue()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFF0F8FF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAntiqueWhite() {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFAEBD7.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAqua() {#getAqua--}
```
public static Color getAqua()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF00FFFF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAquamarine() {#getAquamarine--}
```
public static Color getAquamarine()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF7FFFD4.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAzure() {#getAzure--}
```
public static Color getAzure()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFF0FFFF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBeige() {#getBeige--}
```
public static Color getBeige()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFF5F5DC.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBisque() {#getBisque--}
```
public static Color getBisque()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFFFE4C4.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBlack() {#getBlack--}
```
public static Color getBlack()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF000000.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBlanchedAlmond() {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFFFEBCD.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBlue() {#getBlue--}
```
public static Color getBlue()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF0000FF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBlueViolet() {#getBlueViolet--}
```
public static Color getBlueViolet()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF8A2BE2.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBrown() {#getBrown--}
```
public static Color getBrown()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFA52A2A.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBurlyWood() {#getBurlyWood--}
```
public static Color getBurlyWood()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFDEB887.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCadetBlue() {#getCadetBlue--}
```
public static Color getCadetBlue()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF5F9EA0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getChartreuse() {#getChartreuse--}
```
public static Color getChartreuse()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF7FFF00.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getChocolate() {#getChocolate--}
```
public static Color getChocolate()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFD2691E.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCoral() {#getCoral--}
```
public static Color getCoral()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFFF7F50.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCornflowerBlue() {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF6495ED.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCornsilk() {#getCornsilk--}
```
public static Color getCornsilk()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFFFF8DC.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCrimson() {#getCrimson--}
```
public static Color getCrimson()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFDC143C.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCyan() {#getCyan--}
```
public static Color getCyan()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF00FFFF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkBlue() {#getDarkBlue--}
```
public static Color getDarkBlue()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF00008B.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkCyan() {#getDarkCyan--}
```
public static Color getDarkCyan()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF008B8B.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkGoldenrod() {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFB8860B.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkGray() {#getDarkGray--}
```
public static Color getDarkGray()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFA9A9A9.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkGreen() {#getDarkGreen--}
```
public static Color getDarkGreen()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF006400.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkKhaki() {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FFBDB76B.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkMagenta() {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde av \#FF8B008B.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkOliveGreen() {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF556B2F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkOrange() {#getDarkOrange--}
```
public static Color getDarkOrange()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFF8C00.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkOrchid() {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF9932CC.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkRed() {#getDarkRed--}
```
public static Color getDarkRed()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF8B0000.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkSalmon() {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFE9967A.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkSeaGreen() {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF8FBC8F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkSlateBlue() {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF483D8B.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkSlateGray() {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF2F4F4F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkTurquoise() {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF00CED1.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkViolet() {#getDarkViolet--}
```
public static Color getDarkViolet()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF9400D3.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDeepPink() {#getDeepPink--}
```
public static Color getDeepPink()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFF1493.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDeepSkyBlue() {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF00BFFF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDimGray() {#getDimGray--}
```
public static Color getDimGray()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF696969.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDodgerBlue() {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF1E90FF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getFirebrick() {#getFirebrick--}
```
public static Color getFirebrick()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFB22222.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getFloralWhite() {#getFloralWhite--}
```
public static Color getFloralWhite()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFFAF0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getForestGreen() {#getForestGreen--}
```
public static Color getForestGreen()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF228B22.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getFuchsia() {#getFuchsia--}
```
public static Color getFuchsia()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFF00FF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGainsboro() {#getGainsboro--}
```
public static Color getGainsboro()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFDCDCDC.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGhostWhite() {#getGhostWhite--}
```
public static Color getGhostWhite()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFF8F8FF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGold() {#getGold--}
```
public static Color getGold()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFD700.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGoldenrod() {#getGoldenrod--}
```
public static Color getGoldenrod()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFDAA520.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGray() {#getGray--}
```
public static Color getGray()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF808080.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) strcture representing a system-defined color. `1`
### getGreen() {#getGreen--}
```
public static Color getGreen()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF008000.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGreenYellow() {#getGreenYellow--}
```
public static Color getGreenYellow()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFADFF2F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getHoneydew() {#getHoneydew--}
```
public static Color getHoneydew()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFF0FFF0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getHotPink() {#getHotPink--}
```
public static Color getHotPink()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFF69B4.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getIndianRed() {#getIndianRed--}
```
public static Color getIndianRed()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFCD5C5C.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getIndigo() {#getIndigo--}
```
public static Color getIndigo()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF4B0082.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getIvory() {#getIvory--}
```
public static Color getIvory()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFFFF0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getKhaki() {#getKhaki--}
```
public static Color getKhaki()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFF0E68C.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLavender() {#getLavender--}
```
public static Color getLavender()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFE6E6FA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLavenderBlush() {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFF0F5.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLawnGreen() {#getLawnGreen--}
```
public static Color getLawnGreen()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF7CFC00.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLemonChiffon() {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFFACD.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightBlue() {#getLightBlue--}
```
public static Color getLightBlue()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFADD8E6.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightCoral() {#getLightCoral--}
```
public static Color getLightCoral()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFF08080.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightCyan() {#getLightCyan--}
```
public static Color getLightCyan()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFE0FFFF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightGoldenrodYellow() {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFAFAD2.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightGreen() {#getLightGreen--}
```
public static Color getLightGreen()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF90EE90.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightGray() {#getLightGray--}
```
public static Color getLightGray()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFD3D3D3.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightPink() {#getLightPink--}
```
public static Color getLightPink()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFB6C1.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSalmon() {#getLightSalmon--}
```
public static Color getLightSalmon()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFA07A.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSeaGreen() {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF20B2AA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSkyBlue() {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF87CEFA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSlateGray() {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF778899.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSteelBlue() {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFB0C4DE.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightYellow() {#getLightYellow--}
```
public static Color getLightYellow()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFFFE0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLime() {#getLime--}
```
public static Color getLime()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF00FF00.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLimeGreen() {#getLimeGreen--}
```
public static Color getLimeGreen()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF32CD32.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLinen() {#getLinen--}
```
public static Color getLinen()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFAF0E6.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMagenta() {#getMagenta--}
```
public static Color getMagenta()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFF00FF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMaroon() {#getMaroon--}
```
public static Color getMaroon()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF800000.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumAquamarine() {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF66CDAA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumBlue() {#getMediumBlue--}
```
public static Color getMediumBlue()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF0000CD.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumOrchid() {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFBA55D3.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumPurple() {#getMediumPurple--}
```
public static Color getMediumPurple()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF9370DB.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumSeaGreen() {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF3CB371.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumSlateBlue() {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF7B68EE.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumSpringGreen() {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF00FA9A.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumTurquoise() {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF48D1CC.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumVioletRed() {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFC71585.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMidnightBlue() {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF191970.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMintCream() {#getMintCream--}
```
public static Color getMintCream()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFF5FFFA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMistyRose() {#getMistyRose--}
```
public static Color getMistyRose()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFE4E1.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMoccasin() {#getMoccasin--}
```
public static Color getMoccasin()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFE4B5.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getNavajoWhite() {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFDEAD.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getNavy() {#getNavy--}
```
public static Color getNavy()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF000080.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOldLace() {#getOldLace--}
```
public static Color getOldLace()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFDF5E6.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOlive() {#getOlive--}
```
public static Color getOlive()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF808000.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOliveDrab() {#getOliveDrab--}
```
public static Color getOliveDrab()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF6B8E23.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOrange() {#getOrange--}
```
public static Color getOrange()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFA500.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOrangeRed() {#getOrangeRed--}
```
public static Color getOrangeRed()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFF4500.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOrchid() {#getOrchid--}
```
public static Color getOrchid()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFDA70D6.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPaleGoldenrod() {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFEEE8AA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPaleGreen() {#getPaleGreen--}
```
public static Color getPaleGreen()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF98FB98.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPaleTurquoise() {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFAFEEEE.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPaleVioletRed() {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFDB7093.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPapayaWhip() {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFEFD5.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPeachPuff() {#getPeachPuff--}
```
public static Color getPeachPuff()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFDAB9.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPeru() {#getPeru--}
```
public static Color getPeru()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFCD853F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPink() {#getPink--}
```
public static Color getPink()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFC0CB.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPlum() {#getPlum--}
```
public static Color getPlum()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFDDA0DD.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPowderBlue() {#getPowderBlue--}
```
public static Color getPowderBlue()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFB0E0E6.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPurple() {#getPurple--}
```
public static Color getPurple()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF800080.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getRed() {#getRed--}
```
public static Color getRed()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFF0000.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getRosyBrown() {#getRosyBrown--}
```
public static Color getRosyBrown()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFBC8F8F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getRoyalBlue() {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF4169E1.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSaddleBrown() {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF8B4513.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSalmon() {#getSalmon--}
```
public static Color getSalmon()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFA8072.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSandyBrown() {#getSandyBrown--}
```
public static Color getSandyBrown()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFF4A460.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSeaGreen() {#getSeaGreen--}
```
public static Color getSeaGreen()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF2E8B57.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSeaShell() {#getSeaShell--}
```
public static Color getSeaShell()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFF5EE.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSienna() {#getSienna--}
```
public static Color getSienna()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFA0522D.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSilver() {#getSilver--}
```
public static Color getSilver()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFC0C0C0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSkyBlue() {#getSkyBlue--}
```
public static Color getSkyBlue()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF87CEEB.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSlateBlue() {#getSlateBlue--}
```
public static Color getSlateBlue()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF6A5ACD.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSlateGray() {#getSlateGray--}
```
public static Color getSlateGray()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF708090.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSnow() {#getSnow--}
```
public static Color getSnow()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFFAFA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSpringGreen() {#getSpringGreen--}
```
public static Color getSpringGreen()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF00FF7F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSteelBlue() {#getSteelBlue--}
```
public static Color getSteelBlue()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF4682B4.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getTan() {#getTan--}
```
public static Color getTan()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFD2B48C.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getTeal() {#getTeal--}
```
public static Color getTeal()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF008080.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getThistle() {#getThistle--}
```
public static Color getThistle()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFD8BFD8.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getTomato() {#getTomato--}
```
public static Color getTomato()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFF6347.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getTurquoise() {#getTurquoise--}
```
public static Color getTurquoise()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF40E0D0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getViolet() {#getViolet--}
```
public static Color getViolet()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFEE82EE.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getWheat() {#getWheat--}
```
public static Color getWheat()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFF5DEB3.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getWhite() {#getWhite--}
```
public static Color getWhite()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFFFFF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getWhiteSmoke() {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFF5F5F5.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getYellow() {#getYellow--}
```
public static Color getYellow()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FFFFFF00.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getYellowGreen() {#getYellowGreen--}
```
public static Color getYellowGreen()
```


Hämtar en systemdefinierad färg som har ett ARGB‑värde på \#FF9ACD32.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getA() {#getA--}
```
public final int getA()
```


Hämtar alfa‑komponentens värde för den här [Color](../../com.aspose.drawing/color)-strukturen.

**Returns:**
int – Alfa‑komponentvärdet för denna [Color](../../com.aspose.drawing/color).
### getR() {#getR--}
```
public final int getR()
```


Hämtar röd‑komponentens värde för den här [Color](../../com.aspose.drawing/color)-strukturen.

**Returns:**
int – Röd‑komponentvärdet för denna [Color](../../com.aspose.drawing/color).
### getG() {#getG--}
```
public final int getG()
```


Hämtar grön‑komponentens värde för den här [Color](../../com.aspose.drawing/color)-strukturen.

**Returns:**
int – Grön‑komponentvärdet för denna [Color](../../com.aspose.drawing/color).
### getB() {#getB--}
```
public final int getB()
```


Hämtar blå‑komponentens värde för den här [Color](../../com.aspose.drawing/color)-strukturen.

**Returns:**
int – Blå‑komponentvärdet för denna [Color](../../com.aspose.drawing/color).
### isKnownColor() {#isKnownColor--}
```
public final boolean isKnownColor()
```


Hämtar ett värde som indikerar om denna [Color](../../com.aspose.drawing/color) struktur är en fördefinierad färg. Fördefinierade färger representeras av elementen i [KnownColor](../../com.aspose.drawing/knowncolor)-enumerationen.

Värde: `true` om denna [Color](../../com.aspose.drawing/color) skapades från en fördefinierad färg genom att använda antingen `M:Color.FromName(System.String)`‑metoden eller `M:Color.FromKnownColor(System.Drawing.KnownColor)`‑metoden; annars `false`.

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Hämtar ett värde som anger om den här [Color](../../com.aspose.drawing/color)-strukturen är oinitierad.

Värde: Denna egenskap returnerar true om denna färg är oinitierad; annars false.

**Returns:**
boolean
### isNamedColor() {#isNamedColor--}
```
public final boolean isNamedColor()
```


Hämtar ett värde som anger om den här [Color](../../com.aspose.drawing/color)-strukturen är en namngiven färg eller en medlem av [KnownColor](../../com.aspose.drawing/knowncolor)-enumerationen.

Värde: `true` om denna [Color](../../com.aspose.drawing/color) skapades genom att använda antingen `M:Color.FromName(System.String)`‑metoden eller `M:Color.FromKnownColor(System.Drawing.KnownColor)`‑metoden; annars `false`.

**Returns:**
boolean
### isSystemColor() {#isSystemColor--}
```
public final boolean isSystemColor()
```


Hämtar ett värde som indikerar om denna [Color](../../com.aspose.drawing/color) struktur är en systemfärg. En systemfärg är en färg som används i ett Windows‑display‑element. Systemfärger representeras av element i [KnownColor](../../com.aspose.drawing/knowncolor)-enumerationen.

Värde: `true` om denna [Color](../../com.aspose.drawing/color) skapades från en systemfärg genom att använda antingen `M:Color.FromName(System.String)`‑metoden eller `M:Color.FromKnownColor(System.Drawing.KnownColor)`‑metoden; annars `false`.

**Returns:**
boolean
### getName() {#getName--}
```
public final String getName()
```


Hämtar namnet på den här [Color](../../com.aspose.drawing/color).

**Returns:**
java.lang.String
### fromArgb(int argb) {#fromArgb-int-}
```
public static Color fromArgb(int argb)
```


Skapar en [Color](../../com.aspose.drawing/color)-struktur från ett 32‑bitars ARGB‑värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argb | int | Ett värde som specificerar 32-bitars ARGB‑värdet. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that this method creates.
### fromArgb(int alpha, Color baseColor) {#fromArgb-int-com.aspose.drawing.Color-}
```
public static Color fromArgb(int alpha, Color baseColor)
```


Skapar en [Color](../../com.aspose.drawing/color) struktur från den angivna [Color](../../com.aspose.drawing/color) strukturen, men med det nya angivna alfa‑värdet. Även om denna metod tillåter att ett 32-bitars värde skickas för alfa‑värdet, är värdet begränsat till 8 bitar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alpha | int | Alfa‑värdet för den nya [Color](../../com.aspose.drawing/color). Giltiga värden är 0 till 255. |
| baseColor | [Color](../../com.aspose.drawing/color) | Den [Color](../../com.aspose.drawing/color) som ska användas för att skapa den nya [Color](../../com.aspose.drawing/color). |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) that this method creates.
### fromArgb(int red, int green, int blue) {#fromArgb-int-int-int-}
```
public static Color fromArgb(int red, int green, int blue)
```


Skapar en [Color](../../com.aspose.drawing/color)-struktur från de angivna 8‑bitars färgvärdena (röd, grön och blå). Alfa‑värdet är implicit 255 (fullt ogenomskinligt). Även om den här metoden tillåter att ett 32‑bitars värde skickas för varje färgkomponent, är varje komponents värde begränsat till 8 bitar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| red | int | Rödkomponentens värde för den nya [Color](../../com.aspose.drawing/color). Giltiga värden är 0 till 255. |
| green | int | Grönkomponentens värde för den nya [Color](../../com.aspose.drawing/color). Giltiga värden är 0 till 255. |
| blue | int | Blåkomponentens värde för den nya [Color](../../com.aspose.drawing/color). Giltiga värden är 0 till 255. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) that this method creates.
### fromArgb(int alpha, int red, int green, int blue) {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int alpha, int red, int green, int blue)
```


Skapar en Color-struktur från de fyra ARGB‑komponenterna (alfa, röd, grön och blå). Även om den här metoden tillåter att ett 32‑bitars värde skickas för varje komponent, är varje komponents värde begränsat till 8 bitar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alfa | int | Alfakomponenten. Giltiga värden är 0 till 255. |
| röd | int | Röd komponent. Giltiga värden är 0 till 255. |
| grön | int | Grön komponent. Giltiga värden är 0 till 255. |
| blå | int | Blå komponent. Giltiga värden är 0 till 255. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The Color that this method creates.
### fromKnownColor(int color) {#fromKnownColor-int-}
```
public static Color fromKnownColor(int color)
```


Skapar en [Color](../../com.aspose.drawing/color)-struktur från den angivna fördefinierade färgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| color | int | Ett element i uppräkningen [KnownColor](../../com.aspose.drawing/knowncolor). |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) that this method creates.
### fromName(String name) {#fromName-java.lang.String-}
```
public static Color fromName(String name)
```


Skapar en [Color](../../com.aspose.drawing/color) struktur från det angivna namnet på en fördefinierad färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | En sträng som är namnet på en fördefinierad färg. Giltiga namn är samma som namnen på elementen i uppräkningen [KnownColor](../../com.aspose.drawing/knowncolor). |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) that this method creates.
### op_Equality(Color left, Color right) {#op-Equality-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public static boolean op_Equality(Color left, Color right)
```


Testar om två angivna [Color](../../com.aspose.drawing/color) strukturer är ekvivalenta.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [Color](../../com.aspose.drawing/color) | Den [Color](../../com.aspose.drawing/color) som är till vänster om likhetsoperatorn. |
| right | [Color](../../com.aspose.drawing/color) | Den [Color](../../com.aspose.drawing/color) som är till höger om likhetsoperatorn. |

**Returns:**
boolean - `true` om de två [Color](../../com.aspose.drawing/color)-strukturerna är lika; annars `false`.
### op_Inequality(Color left, Color right) {#op-Inequality-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public static boolean op_Inequality(Color left, Color right)
```


Testar om två angivna [Color](../../com.aspose.drawing/color) strukturer är olika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [Color](../../com.aspose.drawing/color) | Den [Color](../../com.aspose.drawing/color) som är till vänster om ojämlikhetsoperatorn. |
| right | [Color](../../com.aspose.drawing/color) | Den [Color](../../com.aspose.drawing/color) som är till höger om ojämlikhetsoperatorn. |

**Returns:**
boolean - `true` om de två [Color](../../com.aspose.drawing/color)-strukturerna är olika; annars `false`.
### equals(Color other) {#equals-com.aspose.drawing.Color-}
```
public final boolean equals(Color other)
```


Testar om den angivna färgen är ekvivalent med denna färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [Color](../../com.aspose.drawing/color) | Färgen att testa. |

**Returns:**
boolean - `` om den angivna färgen är ekvivalent med denna färg; annars ``.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Testar om det angivna objektet är ekvivalent med denna färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att testa. |

**Returns:**
boolean - `` om det angivna objektet är ekvivalent med denna färg; annars ``.
### toArgb() {#toArgb--}
```
public final int toArgb()
```


Hämtar 32-bitars ARGB‑värdet för denna Color‑struktur.

**Returns:**
int - Det 32-bitars ARGB‑värdet för detta Color.
### getBrightness() {#getBrightness--}
```
public final float getBrightness()
```


Hämtar ljusstyrkevärdet för hue‑saturation‑brightness (HSB) för denna [Color](../../com.aspose.drawing/color) struktur.

**Returns:**
float - Ljusstyrkan för detta [Color](../../com.aspose.drawing/color). Ljusstyrkan varierar från 0.0 till 1.0, där 0.0 representerar svart och 1.0 representerar vitt.
### getHue() {#getHue--}
```
public final float getHue()
```


Hämtar nyansvärdet för hue‑saturation‑brightness (HSB), i grader, för denna [Color](../../com.aspose.drawing/color) struktur.

**Returns:**
float - Nyansen, i grader, för detta java.awt.Color. Nyansen mäts i grader och varierar från 0.0 till 360.0 i HSB-färgrymden.
### getSaturation() {#getSaturation--}
```
public final float getSaturation()
```


Hämtar mättnadsvärdet för hue‑saturation‑brightness (HSB) för denna [Color](../../com.aspose.drawing/color) struktur.

**Returns:**
float - Mättnaden för detta [Color](../../com.aspose.drawing/color). Mättnaden varierar från 0.0 till 1.0, där 0.0 är gråskala och 1.0 är mest mättad.
### toKnownColor() {#toKnownColor--}
```
public final int toKnownColor()
```


Hämtar [KnownColor](../../com.aspose.drawing/knowncolor)-värdet för denna [Color](../../com.aspose.drawing/color) struktur.

**Returns:**
int - Ett element i [KnownColor](../../com.aspose.drawing/knowncolor)-enumerationen, om [Color](../../com.aspose.drawing/color) skapas från en fördefinierad färg genom att använda antingen metoden `M:Color.FromName(System.String)` eller metoden `M:Color.FromKnownColor(KnownColor)`; annars 0.
### toString() {#toString--}
```
public String toString()
```


Returnerar en sträng som representerar detta objekt.

**Returns:**
java.lang.String - En String som representerar detta objekt.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för denna instans.

**Returns:**
int - En hashkod för denna instans, lämplig för användning i hash-algoritmer och datastrukturer som en hash-tabell.
### isEquals(Color obj1, Color obj2) {#isEquals-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public static boolean isEquals(Color obj1, Color obj2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| that | [Color](../../com.aspose.drawing/color) |  |

### Clone() {#Clone--}
```
public Color Clone()
```




**Returns:**
[Color](../../com.aspose.drawing/color)
