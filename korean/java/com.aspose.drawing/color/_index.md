---
title: Color
second_title: Aspose.Drawing for Java API 참조
description: ARGB 알파, 빨강, 초록, 파랑 색상을 나타냅니다.
type: docs
weight: 14
url: /ko/java/com.aspose.drawing/color/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Color extends Struct<Color> implements System.IEquatable<Color>, Cloneable
```

ARGB(알파, 빨강, 초록, 파랑) 색상을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Color()](#Color--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
| [EMPTY](#EMPTY) | null인 색상을 나타냅니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTransparent()](#getTransparent--) | 시스템 정의 색상을 가져옵니다. |
| [getAliceBlue()](#getAliceBlue--) | ARGB 값이 \#FFF0F8FF인 시스템 정의 색상을 가져옵니다. |
| [getAntiqueWhite()](#getAntiqueWhite--) | ARGB 값이 \#FFFAEBD7인 시스템 정의 색상을 가져옵니다. |
| [getAqua()](#getAqua--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF00FFFF 입니다. |
| [getAquamarine()](#getAquamarine--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF7FFFD4 입니다. |
| [getAzure()](#getAzure--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFF0FFFF 입니다. |
| [getBeige()](#getBeige--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFF5F5DC 입니다. |
| [getBisque()](#getBisque--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFE4C4 입니다. |
| [getBlack()](#getBlack--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF000000 입니다. |
| [getBlanchedAlmond()](#getBlanchedAlmond--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFEBCD 입니다. |
| [getBlue()](#getBlue--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF0000FF 입니다. |
| [getBlueViolet()](#getBlueViolet--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF8A2BE2 입니다. |
| [getBrown()](#getBrown--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFA52A2A 입니다. |
| [getBurlyWood()](#getBurlyWood--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFDEB887 입니다. |
| [getCadetBlue()](#getCadetBlue--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF5F9EA0 입니다. |
| [getChartreuse()](#getChartreuse--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF7FFF00 입니다. |
| [getChocolate()](#getChocolate--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFD2691E 입니다. |
| [getCoral()](#getCoral--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFF7F50 입니다. |
| [getCornflowerBlue()](#getCornflowerBlue--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF6495ED 입니다. |
| [getCornsilk()](#getCornsilk--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFF8DC 입니다. |
| [getCrimson()](#getCrimson--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFDC143C 입니다. |
| [getCyan()](#getCyan--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF00FFFF 입니다. |
| [getDarkBlue()](#getDarkBlue--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF00008B 입니다. |
| [getDarkCyan()](#getDarkCyan--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF008B8B 입니다. |
| [getDarkGoldenrod()](#getDarkGoldenrod--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFB8860B 입니다. |
| [getDarkGray()](#getDarkGray--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFA9A9A9 입니다. |
| [getDarkGreen()](#getDarkGreen--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF006400 입니다. |
| [getDarkKhaki()](#getDarkKhaki--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFBDB76B 입니다. |
| [getDarkMagenta()](#getDarkMagenta--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF8B008B 입니다. |
| [getDarkOliveGreen()](#getDarkOliveGreen--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF556B2F입니다. |
| [getDarkOrange()](#getDarkOrange--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFF8C00입니다. |
| [getDarkOrchid()](#getDarkOrchid--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF9932CC입니다. |
| [getDarkRed()](#getDarkRed--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF8B0000입니다. |
| [getDarkSalmon()](#getDarkSalmon--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFE9967A입니다. |
| [getDarkSeaGreen()](#getDarkSeaGreen--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF8FBC8F입니다. |
| [getDarkSlateBlue()](#getDarkSlateBlue--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF483D8B입니다. |
| [getDarkSlateGray()](#getDarkSlateGray--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF2F4F4F입니다. |
| [getDarkTurquoise()](#getDarkTurquoise--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF00CED1입니다. |
| [getDarkViolet()](#getDarkViolet--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF9400D3입니다. |
| [getDeepPink()](#getDeepPink--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFF1493입니다. |
| [getDeepSkyBlue()](#getDeepSkyBlue--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF00BFFF입니다. |
| [getDimGray()](#getDimGray--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF696969입니다. |
| [getDodgerBlue()](#getDodgerBlue--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF1E90FF입니다. |
| [getFirebrick()](#getFirebrick--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFB22222입니다. |
| [getFloralWhite()](#getFloralWhite--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFFAF0입니다. |
| [getForestGreen()](#getForestGreen--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF228B22입니다. |
| [getFuchsia()](#getFuchsia--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFF00FF입니다. |
| [getGainsboro()](#getGainsboro--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFDCDCDC입니다. |
| [getGhostWhite()](#getGhostWhite--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFF8F8FF입니다. |
| [getGold()](#getGold--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFD700입니다. |
| [getGoldenrod()](#getGoldenrod--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFDAA520입니다. |
| [getGray()](#getGray--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF808080입니다. |
| [getGreen()](#getGreen--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF008000입니다. |
| [getGreenYellow()](#getGreenYellow--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFADFF2F입니다. |
| [getHoneydew()](#getHoneydew--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFF0FFF0입니다. |
| [getHotPink()](#getHotPink--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFF69B4입니다. |
| [getIndianRed()](#getIndianRed--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFCD5C5C입니다. |
| [getIndigo()](#getIndigo--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF4B0082입니다. |
| [getIvory()](#getIvory--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFFFF0입니다. |
| [getKhaki()](#getKhaki--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFF0E68C입니다. |
| [getLavender()](#getLavender--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFE6E6FA입니다. |
| [getLavenderBlush()](#getLavenderBlush--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFF0F5입니다. |
| [getLawnGreen()](#getLawnGreen--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF7CFC00입니다. |
| [getLemonChiffon()](#getLemonChiffon--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFFACD입니다. |
| [getLightBlue()](#getLightBlue--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFADD8E6입니다. |
| [getLightCoral()](#getLightCoral--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFF08080입니다. |
| [getLightCyan()](#getLightCyan--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFE0FFFF입니다. |
| [getLightGoldenrodYellow()](#getLightGoldenrodYellow--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFAFAD2입니다. |
| [getLightGreen()](#getLightGreen--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF90EE90입니다. |
| [getLightGray()](#getLightGray--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFD3D3D3입니다. |
| [getLightPink()](#getLightPink--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFB6C1입니다. |
| [getLightSalmon()](#getLightSalmon--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFA07A입니다. |
| [getLightSeaGreen()](#getLightSeaGreen--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF20B2AA입니다. |
| [getLightSkyBlue()](#getLightSkyBlue--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF87CEFA입니다. |
| [getLightSlateGray()](#getLightSlateGray--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF778899입니다. |
| [getLightSteelBlue()](#getLightSteelBlue--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFB0C4DE입니다. |
| [getLightYellow()](#getLightYellow--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFFFE0입니다. |
| [getLime()](#getLime--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF00FF00입니다. |
| [getLimeGreen()](#getLimeGreen--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF32CD32입니다. |
| [getLinen()](#getLinen--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFAF0E6 입니다. |
| [getMagenta()](#getMagenta--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFF00FF입니다. |
| [getMaroon()](#getMaroon--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF800000 입니다. |
| [getMediumAquamarine()](#getMediumAquamarine--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF66CDAA 입니다. |
| [getMediumBlue()](#getMediumBlue--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF0000CD 입니다. |
| [getMediumOrchid()](#getMediumOrchid--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFBA55D3 입니다. |
| [getMediumPurple()](#getMediumPurple--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF9370DB 입니다. |
| [getMediumSeaGreen()](#getMediumSeaGreen--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF3CB371 입니다. |
| [getMediumSlateBlue()](#getMediumSlateBlue--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF7B68EE 입니다. |
| [getMediumSpringGreen()](#getMediumSpringGreen--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF00FA9A 입니다. |
| [getMediumTurquoise()](#getMediumTurquoise--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF48D1CC 입니다. |
| [getMediumVioletRed()](#getMediumVioletRed--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFC71585 입니다. |
| [getMidnightBlue()](#getMidnightBlue--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF191970 입니다. |
| [getMintCream()](#getMintCream--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFF5FFFA 입니다. |
| [getMistyRose()](#getMistyRose--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFE4E1 입니다. |
| [getMoccasin()](#getMoccasin--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFE4B5 입니다. |
| [getNavajoWhite()](#getNavajoWhite--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFDEAD 입니다. |
| [getNavy()](#getNavy--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF000080 입니다. |
| [getOldLace()](#getOldLace--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFDF5E6 입니다. |
| [getOlive()](#getOlive--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF808000 입니다. |
| [getOliveDrab()](#getOliveDrab--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF6B8E23 입니다. |
| [getOrange()](#getOrange--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFA500 입니다. |
| [getOrangeRed()](#getOrangeRed--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFFF4500 입니다. |
| [getOrchid()](#getOrchid--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFDA70D6 입니다. |
| [getPaleGoldenrod()](#getPaleGoldenrod--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FFEEE8AA 입니다. |
| [getPaleGreen()](#getPaleGreen--) | 시스템 정의 색상을 가져오며 ARGB 값은 \#FF98FB98 입니다. |
| [getPaleTurquoise()](#getPaleTurquoise--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FFAFEEEE 입니다. |
| [getPaleVioletRed()](#getPaleVioletRed--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FFDB7093 입니다. |
| [getPapayaWhip()](#getPapayaWhip--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FFFFEFD5 입니다. |
| [getPeachPuff()](#getPeachPuff--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FFFFDAB9 입니다. |
| [getPeru()](#getPeru--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FFCD853F 입니다. |
| [getPink()](#getPink--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FFFFC0CB 입니다. |
| [getPlum()](#getPlum--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FFDDA0DD 입니다. |
| [getPowderBlue()](#getPowderBlue--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FFB0E0E6 입니다. |
| [getPurple()](#getPurple--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FF800080 입니다. |
| [getRed()](#getRed--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FFFF0000 입니다. |
| [getRosyBrown()](#getRosyBrown--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FFBC8F8F 입니다. |
| [getRoyalBlue()](#getRoyalBlue--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FF4169E1 입니다. |
| [getSaddleBrown()](#getSaddleBrown--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FF8B4513 입니다. |
| [getSalmon()](#getSalmon--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FFFA8072 입니다. |
| [getSandyBrown()](#getSandyBrown--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FFF4A460 입니다. |
| [getSeaGreen()](#getSeaGreen--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FF2E8B57 입니다. |
| [getSeaShell()](#getSeaShell--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FFFFF5EE 입니다. |
| [getSienna()](#getSienna--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FFA0522D 입니다. |
| [getSilver()](#getSilver--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FFC0C0C0 입니다. |
| [getSkyBlue()](#getSkyBlue--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FF87CEEB 입니다. |
| [getSlateBlue()](#getSlateBlue--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FF6A5ACD 입니다. |
| [getSlateGray()](#getSlateGray--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FF708090 입니다. |
| [getSnow()](#getSnow--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FFFFFAFA 입니다. |
| [getSpringGreen()](#getSpringGreen--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FF00FF7F 입니다. |
| [getSteelBlue()](#getSteelBlue--) | 시스템 정의 색상을 가져오며, ARGB 값은 \#FF4682B4 입니다. |
| [getTan()](#getTan--) | ARGB 값이 \#FFD2B48C인 시스템 정의 색상을 가져옵니다. |
| [getTeal()](#getTeal--) | ARGB 값이 \#FF008080인 시스템 정의 색상을 가져옵니다. |
| [getThistle()](#getThistle--) | ARGB 값이 \#FFD8BFD8인 시스템 정의 색상을 가져옵니다. |
| [getTomato()](#getTomato--) | ARGB 값이 \#FFFF6347인 시스템 정의 색상을 가져옵니다. |
| [getTurquoise()](#getTurquoise--) | ARGB 값이 \#FF40E0D0인 시스템 정의 색상을 가져옵니다. |
| [getViolet()](#getViolet--) | ARGB 값이 \#FFEE82EE인 시스템 정의 색상을 가져옵니다. |
| [getWheat()](#getWheat--) | ARGB 값이 \#FFF5DEB3인 시스템 정의 색상을 가져옵니다. |
| [getWhite()](#getWhite--) | ARGB 값이 \#FFFFFFFF인 시스템 정의 색상을 가져옵니다. |
| [getWhiteSmoke()](#getWhiteSmoke--) | ARGB 값이 \#FFF5F5F5인 시스템 정의 색상을 가져옵니다. |
| [getYellow()](#getYellow--) | ARGB 값이 \#FFFFFF00인 시스템 정의 색상을 가져옵니다. |
| [getYellowGreen()](#getYellowGreen--) | ARGB 값이 \#FF9ACD32인 시스템 정의 색상을 가져옵니다. |
| [getA()](#getA--) | 이 [Color](../../com.aspose.drawing/color) 구조의 알파 구성 요소 값을 가져옵니다. |
| [getR()](#getR--) | 이 [Color](../../com.aspose.drawing/color) 구조의 빨강 구성 요소 값을 가져옵니다. |
| [getG()](#getG--) | 이 [Color](../../com.aspose.drawing/color) 구조의 초록 구성 요소 값을 가져옵니다. |
| [getB()](#getB--) | 이 [Color](../../com.aspose.drawing/color) 구조의 파랑 구성 요소 값을 가져옵니다. |
| [isKnownColor()](#isKnownColor--) | 이 [Color](../../com.aspose.drawing/color) 구조가 미리 정의된 색상인지 여부를 나타내는 값을 가져옵니다. |
| [isEmpty()](#isEmpty--) | 이 [Color](../../com.aspose.drawing/color) 구조가 초기화되지 않았는지 여부를 나타내는 값을 가져옵니다. |
| [isNamedColor()](#isNamedColor--) | 이 [Color](../../com.aspose.drawing/color) 구조가 명명된 색상인지 또는 [KnownColor](../../com.aspose.drawing/knowncolor) 열거형의 멤버인지 여부를 나타내는 값을 가져옵니다. |
| [isSystemColor()](#isSystemColor--) | 이 [Color](../../com.aspose.drawing/color) 구조가 시스템 색상인지 여부를 나타내는 값을 가져옵니다. |
| [getName()](#getName--) | 이 [Color](../../com.aspose.drawing/color)의 이름을 가져옵니다. |
| [fromArgb(int argb)](#fromArgb-int-) | 32비트 ARGB 값에서 [Color](../../com.aspose.drawing/color) 구조를 생성합니다. |
| [fromArgb(int alpha, Color baseColor)](#fromArgb-int-com.aspose.drawing.Color-) | 지정된 [Color](../../com.aspose.drawing/color) 구조에서 새로 지정된 알파 값을 사용하여 [Color](../../com.aspose.drawing/color) 구조를 생성합니다. |
| [fromArgb(int red, int green, int blue)](#fromArgb-int-int-int-) | 지정된 8비트 색상 값(빨강, 초록, 파랑)에서 [Color](../../com.aspose.drawing/color) 구조를 생성합니다. |
| [fromArgb(int alpha, int red, int green, int blue)](#fromArgb-int-int-int-int-) | 네 개의 ARGB 구성 요소(알파, 빨강, 초록, 파랑) 값에서 Color 구조를 생성합니다. |
| [fromKnownColor(int color)](#fromKnownColor-int-) | 지정된 미리 정의된 색상에서 [Color](../../com.aspose.drawing/color) 구조를 생성합니다. |
| [fromName(String name)](#fromName-java.lang.String-) | 지정된 미리 정의된 색상의 이름으로부터 [Color](../../com.aspose.drawing/color) 구조를 생성합니다. |
| [op_Equality(Color left, Color right)](#op-Equality-com.aspose.drawing.Color-com.aspose.drawing.Color-) | 두 지정된 [Color](../../com.aspose.drawing/color) 구조가 동등한지 테스트합니다. |
| [op_Inequality(Color left, Color right)](#op-Inequality-com.aspose.drawing.Color-com.aspose.drawing.Color-) | 두 지정된 [Color](../../com.aspose.drawing/color) 구조가 다른지 테스트합니다. |
| [equals(Color other)](#equals-com.aspose.drawing.Color-) | 지정된 색상이 이 색상과 동등한지 테스트합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 객체가 이 색상과 동등한지 테스트합니다. |
| [toArgb()](#toArgb--) | 이 Color 구조의 32비트 ARGB 값을 가져옵니다. |
| [getBrightness()](#getBrightness--) | 이 [Color](../../com.aspose.drawing/color) 구조에 대한 색조-채도-밝기(HSB) 밝기 값을 가져옵니다. |
| [getHue()](#getHue--) | 이 [Color](../../com.aspose.drawing/color) 구조에 대한 색조-채도-밝기(HSB) 색조 값을 도 단위로 가져옵니다. |
| [getSaturation()](#getSaturation--) | 이 [Color](../../com.aspose.drawing/color) 구조에 대한 색조-채도-밝기(HSB) 채도 값을 가져옵니다. |
| [toKnownColor()](#toKnownColor--) | 이 [Color](../../com.aspose.drawing/color) 구조의 [KnownColor](../../com.aspose.drawing/knowncolor) 값을 가져옵니다. |
| [toString()](#toString--) | 이 인스턴스를 나타내는 문자열을 반환합니다. |
| [hashCode()](#hashCode--) | 이 인스턴스에 대한 해시 코드를 반환합니다. |
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


null인 색상을 나타냅니다.

### getTransparent() {#getTransparent--}
```
public static Color getTransparent()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAliceBlue() {#getAliceBlue--}
```
public static Color getAliceBlue()
```


ARGB 값이 \#FFF0F8FF인 시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAntiqueWhite() {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```


ARGB 값이 \#FFFAEBD7인 시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAqua() {#getAqua--}
```
public static Color getAqua()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF00FFFF 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAquamarine() {#getAquamarine--}
```
public static Color getAquamarine()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF7FFFD4 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAzure() {#getAzure--}
```
public static Color getAzure()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFF0FFFF 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBeige() {#getBeige--}
```
public static Color getBeige()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFF5F5DC 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBisque() {#getBisque--}
```
public static Color getBisque()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFE4C4 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBlack() {#getBlack--}
```
public static Color getBlack()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF000000 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBlanchedAlmond() {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFEBCD 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBlue() {#getBlue--}
```
public static Color getBlue()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF0000FF 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBlueViolet() {#getBlueViolet--}
```
public static Color getBlueViolet()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF8A2BE2 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBrown() {#getBrown--}
```
public static Color getBrown()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFA52A2A 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBurlyWood() {#getBurlyWood--}
```
public static Color getBurlyWood()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFDEB887 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCadetBlue() {#getCadetBlue--}
```
public static Color getCadetBlue()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF5F9EA0 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getChartreuse() {#getChartreuse--}
```
public static Color getChartreuse()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF7FFF00 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getChocolate() {#getChocolate--}
```
public static Color getChocolate()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFD2691E 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCoral() {#getCoral--}
```
public static Color getCoral()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFF7F50 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCornflowerBlue() {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF6495ED 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCornsilk() {#getCornsilk--}
```
public static Color getCornsilk()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFF8DC 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCrimson() {#getCrimson--}
```
public static Color getCrimson()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFDC143C 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCyan() {#getCyan--}
```
public static Color getCyan()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF00FFFF 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkBlue() {#getDarkBlue--}
```
public static Color getDarkBlue()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF00008B 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkCyan() {#getDarkCyan--}
```
public static Color getDarkCyan()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF008B8B 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkGoldenrod() {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFB8860B 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkGray() {#getDarkGray--}
```
public static Color getDarkGray()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFA9A9A9 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkGreen() {#getDarkGreen--}
```
public static Color getDarkGreen()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF006400 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkKhaki() {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFBDB76B 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkMagenta() {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF8B008B 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkOliveGreen() {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF556B2F입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkOrange() {#getDarkOrange--}
```
public static Color getDarkOrange()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFF8C00입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkOrchid() {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF9932CC입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkRed() {#getDarkRed--}
```
public static Color getDarkRed()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF8B0000입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkSalmon() {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFE9967A입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkSeaGreen() {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF8FBC8F입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkSlateBlue() {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF483D8B입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkSlateGray() {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF2F4F4F입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkTurquoise() {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF00CED1입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkViolet() {#getDarkViolet--}
```
public static Color getDarkViolet()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF9400D3입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDeepPink() {#getDeepPink--}
```
public static Color getDeepPink()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFF1493입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDeepSkyBlue() {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF00BFFF입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDimGray() {#getDimGray--}
```
public static Color getDimGray()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF696969입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDodgerBlue() {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF1E90FF입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getFirebrick() {#getFirebrick--}
```
public static Color getFirebrick()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFB22222입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getFloralWhite() {#getFloralWhite--}
```
public static Color getFloralWhite()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFFAF0입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getForestGreen() {#getForestGreen--}
```
public static Color getForestGreen()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF228B22입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getFuchsia() {#getFuchsia--}
```
public static Color getFuchsia()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFF00FF입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGainsboro() {#getGainsboro--}
```
public static Color getGainsboro()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFDCDCDC입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGhostWhite() {#getGhostWhite--}
```
public static Color getGhostWhite()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFF8F8FF입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGold() {#getGold--}
```
public static Color getGold()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFD700입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGoldenrod() {#getGoldenrod--}
```
public static Color getGoldenrod()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFDAA520입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGray() {#getGray--}
```
public static Color getGray()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF808080입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) strcture representing a system-defined color. `1`
### getGreen() {#getGreen--}
```
public static Color getGreen()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF008000입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGreenYellow() {#getGreenYellow--}
```
public static Color getGreenYellow()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFADFF2F입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getHoneydew() {#getHoneydew--}
```
public static Color getHoneydew()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFF0FFF0입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getHotPink() {#getHotPink--}
```
public static Color getHotPink()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFF69B4입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getIndianRed() {#getIndianRed--}
```
public static Color getIndianRed()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFCD5C5C입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getIndigo() {#getIndigo--}
```
public static Color getIndigo()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF4B0082입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getIvory() {#getIvory--}
```
public static Color getIvory()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFFFF0입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getKhaki() {#getKhaki--}
```
public static Color getKhaki()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFF0E68C입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLavender() {#getLavender--}
```
public static Color getLavender()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFE6E6FA입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLavenderBlush() {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFF0F5입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLawnGreen() {#getLawnGreen--}
```
public static Color getLawnGreen()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF7CFC00입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLemonChiffon() {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFFACD입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightBlue() {#getLightBlue--}
```
public static Color getLightBlue()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFADD8E6입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightCoral() {#getLightCoral--}
```
public static Color getLightCoral()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFF08080입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightCyan() {#getLightCyan--}
```
public static Color getLightCyan()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFE0FFFF입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightGoldenrodYellow() {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFAFAD2입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightGreen() {#getLightGreen--}
```
public static Color getLightGreen()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF90EE90입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightGray() {#getLightGray--}
```
public static Color getLightGray()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFD3D3D3입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightPink() {#getLightPink--}
```
public static Color getLightPink()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFB6C1입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSalmon() {#getLightSalmon--}
```
public static Color getLightSalmon()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFA07A입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSeaGreen() {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF20B2AA입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSkyBlue() {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF87CEFA입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSlateGray() {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF778899입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSteelBlue() {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFB0C4DE입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightYellow() {#getLightYellow--}
```
public static Color getLightYellow()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFFFE0입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLime() {#getLime--}
```
public static Color getLime()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF00FF00입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLimeGreen() {#getLimeGreen--}
```
public static Color getLimeGreen()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF32CD32입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLinen() {#getLinen--}
```
public static Color getLinen()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFAF0E6 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMagenta() {#getMagenta--}
```
public static Color getMagenta()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFF00FF입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMaroon() {#getMaroon--}
```
public static Color getMaroon()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF800000 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumAquamarine() {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF66CDAA 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumBlue() {#getMediumBlue--}
```
public static Color getMediumBlue()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF0000CD 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumOrchid() {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFBA55D3 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumPurple() {#getMediumPurple--}
```
public static Color getMediumPurple()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF9370DB 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumSeaGreen() {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF3CB371 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumSlateBlue() {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF7B68EE 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumSpringGreen() {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF00FA9A 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumTurquoise() {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF48D1CC 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumVioletRed() {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFC71585 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMidnightBlue() {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF191970 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMintCream() {#getMintCream--}
```
public static Color getMintCream()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFF5FFFA 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMistyRose() {#getMistyRose--}
```
public static Color getMistyRose()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFE4E1 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMoccasin() {#getMoccasin--}
```
public static Color getMoccasin()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFE4B5 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getNavajoWhite() {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFDEAD 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getNavy() {#getNavy--}
```
public static Color getNavy()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF000080 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOldLace() {#getOldLace--}
```
public static Color getOldLace()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFDF5E6 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOlive() {#getOlive--}
```
public static Color getOlive()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF808000 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOliveDrab() {#getOliveDrab--}
```
public static Color getOliveDrab()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF6B8E23 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOrange() {#getOrange--}
```
public static Color getOrange()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFFA500 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOrangeRed() {#getOrangeRed--}
```
public static Color getOrangeRed()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFFF4500 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOrchid() {#getOrchid--}
```
public static Color getOrchid()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFDA70D6 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPaleGoldenrod() {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FFEEE8AA 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPaleGreen() {#getPaleGreen--}
```
public static Color getPaleGreen()
```


시스템 정의 색상을 가져오며 ARGB 값은 \#FF98FB98 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPaleTurquoise() {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FFAFEEEE 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPaleVioletRed() {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FFDB7093 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPapayaWhip() {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FFFFEFD5 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPeachPuff() {#getPeachPuff--}
```
public static Color getPeachPuff()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FFFFDAB9 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPeru() {#getPeru--}
```
public static Color getPeru()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FFCD853F 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPink() {#getPink--}
```
public static Color getPink()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FFFFC0CB 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPlum() {#getPlum--}
```
public static Color getPlum()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FFDDA0DD 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPowderBlue() {#getPowderBlue--}
```
public static Color getPowderBlue()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FFB0E0E6 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPurple() {#getPurple--}
```
public static Color getPurple()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FF800080 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getRed() {#getRed--}
```
public static Color getRed()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FFFF0000 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getRosyBrown() {#getRosyBrown--}
```
public static Color getRosyBrown()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FFBC8F8F 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getRoyalBlue() {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FF4169E1 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSaddleBrown() {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FF8B4513 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSalmon() {#getSalmon--}
```
public static Color getSalmon()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FFFA8072 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSandyBrown() {#getSandyBrown--}
```
public static Color getSandyBrown()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FFF4A460 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSeaGreen() {#getSeaGreen--}
```
public static Color getSeaGreen()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FF2E8B57 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSeaShell() {#getSeaShell--}
```
public static Color getSeaShell()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FFFFF5EE 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSienna() {#getSienna--}
```
public static Color getSienna()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FFA0522D 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSilver() {#getSilver--}
```
public static Color getSilver()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FFC0C0C0 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSkyBlue() {#getSkyBlue--}
```
public static Color getSkyBlue()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FF87CEEB 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSlateBlue() {#getSlateBlue--}
```
public static Color getSlateBlue()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FF6A5ACD 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSlateGray() {#getSlateGray--}
```
public static Color getSlateGray()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FF708090 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSnow() {#getSnow--}
```
public static Color getSnow()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FFFFFAFA 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSpringGreen() {#getSpringGreen--}
```
public static Color getSpringGreen()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FF00FF7F 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSteelBlue() {#getSteelBlue--}
```
public static Color getSteelBlue()
```


시스템 정의 색상을 가져오며, ARGB 값은 \#FF4682B4 입니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getTan() {#getTan--}
```
public static Color getTan()
```


ARGB 값이 \#FFD2B48C인 시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getTeal() {#getTeal--}
```
public static Color getTeal()
```


ARGB 값이 \#FF008080인 시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getThistle() {#getThistle--}
```
public static Color getThistle()
```


ARGB 값이 \#FFD8BFD8인 시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getTomato() {#getTomato--}
```
public static Color getTomato()
```


ARGB 값이 \#FFFF6347인 시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getTurquoise() {#getTurquoise--}
```
public static Color getTurquoise()
```


ARGB 값이 \#FF40E0D0인 시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getViolet() {#getViolet--}
```
public static Color getViolet()
```


ARGB 값이 \#FFEE82EE인 시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getWheat() {#getWheat--}
```
public static Color getWheat()
```


ARGB 값이 \#FFF5DEB3인 시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getWhite() {#getWhite--}
```
public static Color getWhite()
```


ARGB 값이 \#FFFFFFFF인 시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getWhiteSmoke() {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```


ARGB 값이 \#FFF5F5F5인 시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getYellow() {#getYellow--}
```
public static Color getYellow()
```


ARGB 값이 \#FFFFFF00인 시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getYellowGreen() {#getYellowGreen--}
```
public static Color getYellowGreen()
```


ARGB 값이 \#FF9ACD32인 시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getA() {#getA--}
```
public final int getA()
```


이 [Color](../../com.aspose.drawing/color) 구조의 알파 구성 요소 값을 가져옵니다.

**Returns:**
int - 이 [Color](../../com.aspose.drawing/color)의 알파 구성 요소 값입니다.
### getR() {#getR--}
```
public final int getR()
```


이 [Color](../../com.aspose.drawing/color) 구조의 빨강 구성 요소 값을 가져옵니다.

**Returns:**
int - 이 [Color](../../com.aspose.drawing/color)의 빨간색 구성 요소 값입니다.
### getG() {#getG--}
```
public final int getG()
```


이 [Color](../../com.aspose.drawing/color) 구조의 초록 구성 요소 값을 가져옵니다.

**Returns:**
int - 이 [Color](../../com.aspose.drawing/color)의 녹색 구성 요소 값입니다.
### getB() {#getB--}
```
public final int getB()
```


이 [Color](../../com.aspose.drawing/color) 구조의 파랑 구성 요소 값을 가져옵니다.

**Returns:**
int - 이 [Color](../../com.aspose.drawing/color)의 파란색 구성 요소 값입니다.
### isKnownColor() {#isKnownColor--}
```
public final boolean isKnownColor()
```


이 [Color](../../com.aspose.drawing/color) 구조가 미리 정의된 색상인지 여부를 나타내는 값을 가져옵니다. 미리 정의된 색상은 [KnownColor](../../com.aspose.drawing/knowncolor) 열거형의 요소로 표시됩니다.

값: 이 [Color](../../com.aspose.drawing/color)이 `M:Color.FromName(System.String)` 메서드 또는 `M:Color.FromKnownColor(System.Drawing.KnownColor)` 메서드를 사용하여 미리 정의된 색상에서 생성된 경우 `true`; 그렇지 않으면 `false`.

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


이 [Color](../../com.aspose.drawing/color) 구조가 초기화되지 않았는지 여부를 나타내는 값을 가져옵니다.

값: 이 색상이 초기화되지 않은 경우 이 속성은 true를 반환하고, 그렇지 않으면 false를 반환합니다.

**Returns:**
boolean
### isNamedColor() {#isNamedColor--}
```
public final boolean isNamedColor()
```


이 [Color](../../com.aspose.drawing/color) 구조가 명명된 색상인지 또는 [KnownColor](../../com.aspose.drawing/knowncolor) 열거형의 멤버인지 여부를 나타내는 값을 가져옵니다.

값: 이 [Color](../../com.aspose.drawing/color)이 `M:Color.FromName(System.String)` 메서드 또는 `M:Color.FromKnownColor(System.Drawing.KnownColor)` 메서드를 사용하여 생성된 경우 `true`; 그렇지 않으면 `false`.

**Returns:**
boolean
### isSystemColor() {#isSystemColor--}
```
public final boolean isSystemColor()
```


이 [Color](../../com.aspose.drawing/color) 구조가 시스템 색상인지 여부를 나타내는 값을 가져옵니다. 시스템 색상은 Windows 표시 요소에서 사용되는 색상이며, 시스템 색상은 [KnownColor](../../com.aspose.drawing/knowncolor) 열거형의 요소로 표시됩니다.

값: 이 [Color](../../com.aspose.drawing/color)이 `M:Color.FromName(System.String)` 메서드 또는 `M:Color.FromKnownColor(System.Drawing.KnownColor)` 메서드를 사용하여 시스템 색상에서 생성된 경우 `true`; 그렇지 않으면 `false`.

**Returns:**
boolean
### getName() {#getName--}
```
public final String getName()
```


이 [Color](../../com.aspose.drawing/color)의 이름을 가져옵니다.

**Returns:**
java.lang.String
### fromArgb(int argb) {#fromArgb-int-}
```
public static Color fromArgb(int argb)
```


32비트 ARGB 값에서 [Color](../../com.aspose.drawing/color) 구조를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| argb | int | 32비트 ARGB 값을 지정하는 값입니다. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that this method creates.
### fromArgb(int alpha, Color baseColor) {#fromArgb-int-com.aspose.drawing.Color-}
```
public static Color fromArgb(int alpha, Color baseColor)
```


지정된 [Color](../../com.aspose.drawing/color) 구조에서 새 알파 값을 지정하여 [Color](../../com.aspose.drawing/color) 구조를 생성합니다. 이 메서드는 알파 값으로 32비트 값을 전달할 수 있지만, 값은 8비트로 제한됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| alpha | int | 새 [Color](../../com.aspose.drawing/color)의 알파 값입니다. 유효한 값은 0부터 255까지입니다. |
| baseColor | [Color](../../com.aspose.drawing/color) | 새로운 [Color](../../com.aspose.drawing/color)를 만들기 위한 원본 [Color](../../com.aspose.drawing/color)입니다. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) that this method creates.
### fromArgb(int red, int green, int blue) {#fromArgb-int-int-int-}
```
public static Color fromArgb(int red, int green, int blue)
```


[Color](../../com.aspose.drawing/color) 구조를 지정된 8비트 색상 값(빨강, 초록, 파랑)으로부터 생성합니다. 알파 값은 암시적으로 255(완전 불투명)입니다. 이 메서드는 각 색상 구성 요소에 대해 32비트 값을 전달할 수 있지만, 각 구성 요소의 값은 8비트로 제한됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| red | int | 새로운 [Color](../../com.aspose.drawing/color)의 빨강 구성 요소 값입니다. 유효한 값은 0부터 255까지입니다. |
| green | int | 새로운 [Color](../../com.aspose.drawing/color)의 초록 구성 요소 값입니다. 유효한 값은 0부터 255까지입니다. |
| blue | int | 새로운 [Color](../../com.aspose.drawing/color)의 파랑 구성 요소 값입니다. 유효한 값은 0부터 255까지입니다. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) that this method creates.
### fromArgb(int alpha, int red, int green, int blue) {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int alpha, int red, int green, int blue)
```


네 개의 ARGB 구성 요소(알파, 빨강, 초록, 파랑) 값을 사용하여 Color 구조를 생성합니다. 이 메서드는 각 구성 요소에 대해 32비트 값을 전달할 수 있지만, 각 구성 요소의 값은 8비트로 제한됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 알파 | int | 알파 구성 요소입니다. 유효한 값은 0부터 255까지입니다. |
| 빨강 | int | 빨강 구성 요소입니다. 유효한 값은 0부터 255까지입니다. |
| 초록 | int | 초록 구성 요소입니다. 유효한 값은 0부터 255까지입니다. |
| 파랑 | int | 파랑 구성 요소입니다. 유효한 값은 0부터 255까지입니다. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The Color that this method creates.
### fromKnownColor(int color) {#fromKnownColor-int-}
```
public static Color fromKnownColor(int color)
```


지정된 미리 정의된 색상에서 [Color](../../com.aspose.drawing/color) 구조를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| color | int | [KnownColor](../../com.aspose.drawing/knowncolor) 열거형의 요소입니다. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) that this method creates.
### fromName(String name) {#fromName-java.lang.String-}
```
public static Color fromName(String name)
```


지정된 미리 정의된 색상의 이름으로부터 [Color](../../com.aspose.drawing/color) 구조를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 미리 정의된 색상의 이름인 문자열입니다. 유효한 이름은 [KnownColor](../../com.aspose.drawing/knowncolor) 열거형 요소들의 이름과 동일합니다. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) that this method creates.
### op_Equality(Color left, Color right) {#op-Equality-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public static boolean op_Equality(Color left, Color right)
```


두 지정된 [Color](../../com.aspose.drawing/color) 구조가 동등한지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | [Color](../../com.aspose.drawing/color) | 등호 연산자 왼쪽에 있는 [Color](../../com.aspose.drawing/color)입니다. |
| right | [Color](../../com.aspose.drawing/color) | 등호 연산자 오른쪽에 있는 [Color](../../com.aspose.drawing/color)입니다. |

**Returns:**
boolean - 두 [Color](../../com.aspose.drawing/color) 구조가 동일하면 `true`; 그렇지 않으면 `false`.
### op_Inequality(Color left, Color right) {#op-Inequality-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public static boolean op_Inequality(Color left, Color right)
```


두 지정된 [Color](../../com.aspose.drawing/color) 구조가 다른지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | [Color](../../com.aspose.drawing/color) | 부등호 연산자 왼쪽에 있는 [Color](../../com.aspose.drawing/color)입니다. |
| right | [Color](../../com.aspose.drawing/color) | 부등호 연산자 오른쪽에 있는 [Color](../../com.aspose.drawing/color)입니다. |

**Returns:**
boolean - 두 [Color](../../com.aspose.drawing/color) 구조가 다르면 `true`; 그렇지 않으면 `false`.
### equals(Color other) {#equals-com.aspose.drawing.Color-}
```
public final boolean equals(Color other)
```


지정된 색상이 이 색상과 동등한지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| other | [Color](../../com.aspose.drawing/color) | 테스트할 색상입니다. |

**Returns:**
boolean - 지정된 색상이 이 색상과 동일하면 ``; 그렇지 않으면 ``.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된 객체가 이 색상과 동등한지 테스트합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 테스트할 객체입니다. |

**Returns:**
boolean - 지정된 객체가 이 색상과 동일하면 ``; 그렇지 않으면 ``.
### toArgb() {#toArgb--}
```
public final int toArgb()
```


이 Color 구조의 32비트 ARGB 값을 가져옵니다.

**Returns:**
int - 이 색상의 32비트 ARGB 값.
### getBrightness() {#getBrightness--}
```
public final float getBrightness()
```


이 [Color](../../com.aspose.drawing/color) 구조에 대한 색조-채도-밝기(HSB) 밝기 값을 가져옵니다.

**Returns:**
float - 이 [Color](../../com.aspose.drawing/color)의 밝기. 밝기는 0.0부터 1.0까지이며, 0.0은 검은색을, 1.0은 흰색을 나타냅니다.
### getHue() {#getHue--}
```
public final float getHue()
```


이 [Color](../../com.aspose.drawing/color) 구조에 대한 색조-채도-밝기(HSB) 색조 값을 도 단위로 가져옵니다.

**Returns:**
float - 이 java.awt.Color의 색조(도 단위). 색조는 HSB 색 공간에서 0.0부터 360.0까지 도로 측정됩니다.
### getSaturation() {#getSaturation--}
```
public final float getSaturation()
```


이 [Color](../../com.aspose.drawing/color) 구조에 대한 색조-채도-밝기(HSB) 채도 값을 가져옵니다.

**Returns:**
float - 이 [Color](../../com.aspose.drawing/color)의 채도. 채도는 0.0부터 1.0까지이며, 0.0은 회색조, 1.0은 가장 포화된 상태를 나타냅니다.
### toKnownColor() {#toKnownColor--}
```
public final int toKnownColor()
```


이 [Color](../../com.aspose.drawing/color) 구조의 [KnownColor](../../com.aspose.drawing/knowncolor) 값을 가져옵니다.

**Returns:**
int - [KnownColor](../../com.aspose.drawing/knowncolor) 열거형의 요소이며, [Color](../../com.aspose.drawing/color)가 `M:Color.FromName(System.String)` 메서드 또는 `M:Color.FromKnownColor(KnownColor)` 메서드를 사용하여 미리 정의된 색상으로 생성된 경우; 그렇지 않으면 0입니다.
### toString() {#toString--}
```
public String toString()
```


이 인스턴스를 나타내는 문자열을 반환합니다.

**Returns:**
java.lang.String - 이 인스턴스를 나타내는 문자열.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스에 대한 해시 코드를 반환합니다.

**Returns:**
int - 이 인스턴스에 대한 해시 코드로, 해시 알고리즘 및 해시 테이블과 같은 데이터 구조에 사용하기에 적합합니다.
### isEquals(Color obj1, Color obj2) {#isEquals-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public static boolean isEquals(Color obj1, Color obj2)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| that | [Color](../../com.aspose.drawing/color) |  |

### Clone() {#Clone--}
```
public Color Clone()
```




**Returns:**
[Color](../../com.aspose.drawing/color)
