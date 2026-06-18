---
title: Color
second_title: Αναφορά API του Aspose.Drawing for Java
description: Αναπαριστά ένα χρώμα ARGB (άλφα, κόκκινο, πράσινο, μπλε).
type: docs
weight: 14
url: /el/java/com.aspose.drawing/color/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Color extends Struct<Color> implements System.IEquatable<Color>, Cloneable
```

Αναπαριστά ένα χρώμα ARGB (άλφα, κόκκινο, πράσινο, μπλε).
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Color()](#Color--) |  |
## Fields

| Field | Περιγραφή |
| --- | --- |
| [EMPTY](#EMPTY) | Αναπαριστά ένα χρώμα που είναι null. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getTransparent()](#getTransparent--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα. |
| [getAliceBlue()](#getAliceBlue--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFF0F8FF. |
| [getAntiqueWhite()](#getAntiqueWhite--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFFAEBD7. |
| [getAqua()](#getAqua--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF00FFFF. |
| [getAquamarine()](#getAquamarine--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF7FFFD4. |
| [getAzure()](#getAzure--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFF0FFFF. |
| [getBeige()](#getBeige--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFF5F5DC. |
| [getBisque()](#getBisque--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFE4C4. |
| [getBlack()](#getBlack--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF000000. |
| [getBlanchedAlmond()](#getBlanchedAlmond--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFEBCD. |
| [getBlue()](#getBlue--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF0000FF. |
| [getBlueViolet()](#getBlueViolet--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF8A2BE2. |
| [getBrown()](#getBrown--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFA52A2A. |
| [getBurlyWood()](#getBurlyWood--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFDEB887. |
| [getCadetBlue()](#getCadetBlue--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF5F9EA0. |
| [getChartreuse()](#getChartreuse--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF7FFF00. |
| [getChocolate()](#getChocolate--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFD2691E. |
| [getCoral()](#getCoral--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFF7F50. |
| [getCornflowerBlue()](#getCornflowerBlue--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF6495ED. |
| [getCornsilk()](#getCornsilk--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFF8DC. |
| [getCrimson()](#getCrimson--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFDC143C. |
| [getCyan()](#getCyan--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF00FFFF. |
| [getDarkBlue()](#getDarkBlue--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF00008B. |
| [getDarkCyan()](#getDarkCyan--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF008B8B. |
| [getDarkGoldenrod()](#getDarkGoldenrod--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFB8860B. |
| [getDarkGray()](#getDarkGray--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFA9A9A9. |
| [getDarkGreen()](#getDarkGreen--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF006400. |
| [getDarkKhaki()](#getDarkKhaki--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFBDB76B. |
| [getDarkMagenta()](#getDarkMagenta--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF8B008B. |
| [getDarkOliveGreen()](#getDarkOliveGreen--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF556B2F. |
| [getDarkOrange()](#getDarkOrange--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FFFF8C00. |
| [getDarkOrchid()](#getDarkOrchid--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF9932CC. |
| [getDarkRed()](#getDarkRed--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF8B0000. |
| [getDarkSalmon()](#getDarkSalmon--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FFE9967A. |
| [getDarkSeaGreen()](#getDarkSeaGreen--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF8FBC8F. |
| [getDarkSlateBlue()](#getDarkSlateBlue--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF483D8B. |
| [getDarkSlateGray()](#getDarkSlateGray--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF2F4F4F. |
| [getDarkTurquoise()](#getDarkTurquoise--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF00CED1. |
| [getDarkViolet()](#getDarkViolet--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF9400D3. |
| [getDeepPink()](#getDeepPink--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FFFF1493. |
| [getDeepSkyBlue()](#getDeepSkyBlue--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF00BFFF. |
| [getDimGray()](#getDimGray--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF696969. |
| [getDodgerBlue()](#getDodgerBlue--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF1E90FF. |
| [getFirebrick()](#getFirebrick--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FFB22222. |
| [getFloralWhite()](#getFloralWhite--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FFFFFAF0. |
| [getForestGreen()](#getForestGreen--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF228B22. |
| [getFuchsia()](#getFuchsia--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FFFF00FF. |
| [getGainsboro()](#getGainsboro--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FFDCDCDC. |
| [getGhostWhite()](#getGhostWhite--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FFF8F8FF. |
| [getGold()](#getGold--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FFFFD700. |
| [getGoldenrod()](#getGoldenrod--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FFDAA520. |
| [getGray()](#getGray--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF808080. |
| [getGreen()](#getGreen--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF008000. |
| [getGreenYellow()](#getGreenYellow--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FFADFF2F. |
| [getHoneydew()](#getHoneydew--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFF0FFF0. |
| [getHotPink()](#getHotPink--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFF69B4. |
| [getIndianRed()](#getIndianRed--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFCD5C5C. |
| [getIndigo()](#getIndigo--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF4B0082. |
| [getIvory()](#getIvory--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFFFF0. |
| [getKhaki()](#getKhaki--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFF0E68C. |
| [getLavender()](#getLavender--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFE6E6FA. |
| [getLavenderBlush()](#getLavenderBlush--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFF0F5. |
| [getLawnGreen()](#getLawnGreen--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF7CFC00. |
| [getLemonChiffon()](#getLemonChiffon--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFFACD. |
| [getLightBlue()](#getLightBlue--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFADD8E6. |
| [getLightCoral()](#getLightCoral--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFF08080. |
| [getLightCyan()](#getLightCyan--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFE0FFFF. |
| [getLightGoldenrodYellow()](#getLightGoldenrodYellow--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFAFAD2. |
| [getLightGreen()](#getLightGreen--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF90EE90. |
| [getLightGray()](#getLightGray--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFD3D3D3. |
| [getLightPink()](#getLightPink--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFB6C1. |
| [getLightSalmon()](#getLightSalmon--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFA07A. |
| [getLightSeaGreen()](#getLightSeaGreen--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF20B2AA. |
| [getLightSkyBlue()](#getLightSkyBlue--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF87CEFA. |
| [getLightSlateGray()](#getLightSlateGray--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF778899. |
| [getLightSteelBlue()](#getLightSteelBlue--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFB0C4DE. |
| [getLightYellow()](#getLightYellow--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFFFE0. |
| [getLime()](#getLime--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF00FF00. |
| [getLimeGreen()](#getLimeGreen--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF32CD32. |
| [getLinen()](#getLinen--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFFAF0E6. |
| [getMagenta()](#getMagenta--) | Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FFFF00FF. |
| [getMaroon()](#getMaroon--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF800000. |
| [getMediumAquamarine()](#getMediumAquamarine--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF66CDAA. |
| [getMediumBlue()](#getMediumBlue--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF0000CD. |
| [getMediumOrchid()](#getMediumOrchid--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFBA55D3. |
| [getMediumPurple()](#getMediumPurple--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF9370DB. |
| [getMediumSeaGreen()](#getMediumSeaGreen--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF3CB371. |
| [getMediumSlateBlue()](#getMediumSlateBlue--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF7B68EE. |
| [getMediumSpringGreen()](#getMediumSpringGreen--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF00FA9A. |
| [getMediumTurquoise()](#getMediumTurquoise--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF48D1CC. |
| [getMediumVioletRed()](#getMediumVioletRed--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFC71585. |
| [getMidnightBlue()](#getMidnightBlue--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF191970. |
| [getMintCream()](#getMintCream--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFF5FFFA. |
| [getMistyRose()](#getMistyRose--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFFFE4E1. |
| [getMoccasin()](#getMoccasin--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFFFE4B5. |
| [getNavajoWhite()](#getNavajoWhite--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFFFDEAD. |
| [getNavy()](#getNavy--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF000080. |
| [getOldLace()](#getOldLace--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFFDF5E6. |
| [getOlive()](#getOlive--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF808000. |
| [getOliveDrab()](#getOliveDrab--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF6B8E23. |
| [getOrange()](#getOrange--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFFFA500. |
| [getOrangeRed()](#getOrangeRed--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFFF4500. |
| [getOrchid()](#getOrchid--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFDA70D6. |
| [getPaleGoldenrod()](#getPaleGoldenrod--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFEEE8AA. |
| [getPaleGreen()](#getPaleGreen--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF98FB98. |
| [getPaleTurquoise()](#getPaleTurquoise--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFAFEEEE. |
| [getPaleVioletRed()](#getPaleVioletRed--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFDB7093. |
| [getPapayaWhip()](#getPapayaWhip--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFEFD5. |
| [getPeachPuff()](#getPeachPuff--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFDAB9. |
| [getPeru()](#getPeru--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFCD853F. |
| [getPink()](#getPink--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFC0CB. |
| [getPlum()](#getPlum--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFDDA0DD. |
| [getPowderBlue()](#getPowderBlue--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFB0E0E6. |
| [getPurple()](#getPurple--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF800080. |
| [getRed()](#getRed--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFF0000. |
| [getRosyBrown()](#getRosyBrown--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFBC8F8F. |
| [getRoyalBlue()](#getRoyalBlue--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF4169E1. |
| [getSaddleBrown()](#getSaddleBrown--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF8B4513. |
| [getSalmon()](#getSalmon--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFA8072. |
| [getSandyBrown()](#getSandyBrown--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFF4A460. |
| [getSeaGreen()](#getSeaGreen--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF2E8B57. |
| [getSeaShell()](#getSeaShell--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFF5EE. |
| [getSienna()](#getSienna--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFA0522D. |
| [getSilver()](#getSilver--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFC0C0C0. |
| [getSkyBlue()](#getSkyBlue--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF87CEEB. |
| [getSlateBlue()](#getSlateBlue--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF6A5ACD. |
| [getSlateGray()](#getSlateGray--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF708090. |
| [getSnow()](#getSnow--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFFAFA. |
| [getSpringGreen()](#getSpringGreen--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF00FF7F. |
| [getSteelBlue()](#getSteelBlue--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF4682B4. |
| [getTan()](#getTan--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFD2B48C. |
| [getTeal()](#getTeal--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF008080. |
| [getThistle()](#getThistle--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFD8BFD8. |
| [getTomato()](#getTomato--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFF6347. |
| [getTurquoise()](#getTurquoise--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF40E0D0. |
| [getViolet()](#getViolet--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFEE82EE. |
| [getWheat()](#getWheat--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFF5DEB3. |
| [getWhite()](#getWhite--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFFFFF. |
| [getWhiteSmoke()](#getWhiteSmoke--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFF5F5F5. |
| [getYellow()](#getYellow--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFFF00. |
| [getYellowGreen()](#getYellowGreen--) | Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF9ACD32. |
| [getA()](#getA--) | Λαμβάνει την τιμή του συστατικού άλφα αυτής της δομής [Color](../../com.aspose.drawing/color). |
| [getR()](#getR--) | Λαμβάνει την τιμή του συστατικού κόκκινου αυτής της δομής [Color](../../com.aspose.drawing/color). |
| [getG()](#getG--) | Λαμβάνει την τιμή του συστατικού πράσινου αυτής της δομής [Color](../../com.aspose.drawing/color). |
| [getB()](#getB--) | Λαμβάνει την τιμή του συστατικού μπλε αυτής της δομής [Color](../../com.aspose.drawing/color). |
| [isKnownColor()](#isKnownColor--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η δομή [Color](../../com.aspose.drawing/color) είναι προκαθορισμένο χρώμα. |
| [isEmpty()](#isEmpty--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η δομή [Color](../../com.aspose.drawing/color) δεν έχει αρχικοποιηθεί. |
| [isNamedColor()](#isNamedColor--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η δομή [Color](../../com.aspose.drawing/color) είναι ένα ονομαστικό χρώμα ή μέλος της απαρίθμησης [KnownColor](../../com.aspose.drawing/knowncolor). |
| [isSystemColor()](#isSystemColor--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η δομή [Color](../../com.aspose.drawing/color) είναι χρώμα του συστήματος. |
| [getName()](#getName--) | Λαμβάνει το όνομα αυτής της [Color](../../com.aspose.drawing/color). |
| [fromArgb(int argb)](#fromArgb-int-) | Δημιουργεί μια δομή [Color](../../com.aspose.drawing/color) από μια 32-bit τιμή ARGB. |
| [fromArgb(int alpha, Color baseColor)](#fromArgb-int-com.aspose.drawing.Color-) | Δημιουργεί μια δομή [Color](../../com.aspose.drawing/color) από τη συγκεκριμένη δομή [Color](../../com.aspose.drawing/color), αλλά με τη νέα καθορισμένη τιμή άλφα. |
| [fromArgb(int red, int green, int blue)](#fromArgb-int-int-int-) | Δημιουργεί μια δομή [Color](../../com.aspose.drawing/color) από τις καθορισμένες 8-bit τιμές χρώματος (κόκκινο, πράσινο και μπλε). |
| [fromArgb(int alpha, int red, int green, int blue)](#fromArgb-int-int-int-int-) | Δημιουργεί μια δομή Color από τις τέσσερις τιμές των συστατικών ARGB (άλφα, κόκκινο, πράσινο και μπλε). |
| [fromKnownColor(int color)](#fromKnownColor-int-) | Δημιουργεί μια δομή [Color](../../com.aspose.drawing/color) από το καθορισμένο προκαθορισμένο χρώμα. |
| [fromName(String name)](#fromName-java.lang.String-) | Δημιουργεί μια δομή [Color](../../com.aspose.drawing/color) από το καθορισμένο όνομα ενός προεπιλεγμένου χρώματος. |
| [op_Equality(Color left, Color right)](#op-Equality-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Ελέγχει εάν δύο καθορισμένες δομές [Color](../../com.aspose.drawing/color) είναι ισοδύναμες. |
| [op_Inequality(Color left, Color right)](#op-Inequality-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Ελέγχει εάν δύο καθορισμένες δομές [Color](../../com.aspose.drawing/color) είναι διαφορετικές. |
| [equals(Color other)](#equals-com.aspose.drawing.Color-) | Ελέγχει εάν το καθορισμένο χρώμα είναι ισοδύναμο με αυτό το χρώμα. |
| [equals(Object obj)](#equals-java.lang.Object-) | Ελέγχει εάν το καθορισμένο αντικείμενο είναι ισοδύναμο με αυτό το χρώμα. |
| [toArgb()](#toArgb--) | Αποκτά την 32-bit τιμή ARGB αυτής της δομής Color. |
| [getBrightness()](#getBrightness--) | Αποκτά την τιμή φωτεινότητας hue-saturation-brightness (HSB) για αυτή τη δομή [Color](../../com.aspose.drawing/color). |
| [getHue()](#getHue--) | Αποκτά την τιμή απόχρωσης hue-saturation-brightness (HSB), σε μοίρες, για αυτή τη δομή [Color](../../com.aspose.drawing/color). |
| [getSaturation()](#getSaturation--) | Αποκτά την τιμή κορεσμού hue-saturation-brightness (HSB) για αυτή τη δομή [Color](../../com.aspose.drawing/color). |
| [toKnownColor()](#toKnownColor--) | Αποκτά την τιμή [KnownColor](../../com.aspose.drawing/knowncolor) αυτής της δομής [Color](../../com.aspose.drawing/color). |
| [toString()](#toString--) | Επιστρέφει ένα String που αντιπροσωπεύει αυτήν την παρουσία. |
| [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού για αυτήν την instance. |
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


Αναπαριστά ένα χρώμα που είναι null.

### getTransparent() {#getTransparent--}
```
public static Color getTransparent()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAliceBlue() {#getAliceBlue--}
```
public static Color getAliceBlue()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFF0F8FF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAntiqueWhite() {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFFAEBD7.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAqua() {#getAqua--}
```
public static Color getAqua()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF00FFFF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAquamarine() {#getAquamarine--}
```
public static Color getAquamarine()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF7FFFD4.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAzure() {#getAzure--}
```
public static Color getAzure()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFF0FFFF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBeige() {#getBeige--}
```
public static Color getBeige()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFF5F5DC.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBisque() {#getBisque--}
```
public static Color getBisque()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFE4C4.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBlack() {#getBlack--}
```
public static Color getBlack()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF000000.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBlanchedAlmond() {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFEBCD.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBlue() {#getBlue--}
```
public static Color getBlue()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF0000FF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBlueViolet() {#getBlueViolet--}
```
public static Color getBlueViolet()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF8A2BE2.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBrown() {#getBrown--}
```
public static Color getBrown()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFA52A2A.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBurlyWood() {#getBurlyWood--}
```
public static Color getBurlyWood()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFDEB887.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCadetBlue() {#getCadetBlue--}
```
public static Color getCadetBlue()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF5F9EA0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getChartreuse() {#getChartreuse--}
```
public static Color getChartreuse()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF7FFF00.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getChocolate() {#getChocolate--}
```
public static Color getChocolate()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFD2691E.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCoral() {#getCoral--}
```
public static Color getCoral()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFF7F50.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCornflowerBlue() {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF6495ED.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCornsilk() {#getCornsilk--}
```
public static Color getCornsilk()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFF8DC.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCrimson() {#getCrimson--}
```
public static Color getCrimson()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFDC143C.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCyan() {#getCyan--}
```
public static Color getCyan()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF00FFFF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkBlue() {#getDarkBlue--}
```
public static Color getDarkBlue()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF00008B.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkCyan() {#getDarkCyan--}
```
public static Color getDarkCyan()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF008B8B.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkGoldenrod() {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFB8860B.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkGray() {#getDarkGray--}
```
public static Color getDarkGray()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFA9A9A9.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkGreen() {#getDarkGreen--}
```
public static Color getDarkGreen()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF006400.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkKhaki() {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFBDB76B.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkMagenta() {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF8B008B.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkOliveGreen() {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF556B2F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkOrange() {#getDarkOrange--}
```
public static Color getDarkOrange()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FFFF8C00.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkOrchid() {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF9932CC.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkRed() {#getDarkRed--}
```
public static Color getDarkRed()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF8B0000.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkSalmon() {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FFE9967A.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkSeaGreen() {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF8FBC8F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkSlateBlue() {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF483D8B.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkSlateGray() {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF2F4F4F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkTurquoise() {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF00CED1.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkViolet() {#getDarkViolet--}
```
public static Color getDarkViolet()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF9400D3.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDeepPink() {#getDeepPink--}
```
public static Color getDeepPink()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FFFF1493.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDeepSkyBlue() {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF00BFFF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDimGray() {#getDimGray--}
```
public static Color getDimGray()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF696969.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDodgerBlue() {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF1E90FF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getFirebrick() {#getFirebrick--}
```
public static Color getFirebrick()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FFB22222.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getFloralWhite() {#getFloralWhite--}
```
public static Color getFloralWhite()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FFFFFAF0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getForestGreen() {#getForestGreen--}
```
public static Color getForestGreen()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF228B22.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getFuchsia() {#getFuchsia--}
```
public static Color getFuchsia()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FFFF00FF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGainsboro() {#getGainsboro--}
```
public static Color getGainsboro()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FFDCDCDC.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGhostWhite() {#getGhostWhite--}
```
public static Color getGhostWhite()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FFF8F8FF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGold() {#getGold--}
```
public static Color getGold()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FFFFD700.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGoldenrod() {#getGoldenrod--}
```
public static Color getGoldenrod()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FFDAA520.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGray() {#getGray--}
```
public static Color getGray()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF808080.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) strcture representing a system-defined color. `1`
### getGreen() {#getGreen--}
```
public static Color getGreen()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FF008000.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGreenYellow() {#getGreenYellow--}
```
public static Color getGreenYellow()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FFADFF2F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getHoneydew() {#getHoneydew--}
```
public static Color getHoneydew()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFF0FFF0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getHotPink() {#getHotPink--}
```
public static Color getHotPink()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFF69B4.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getIndianRed() {#getIndianRed--}
```
public static Color getIndianRed()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFCD5C5C.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getIndigo() {#getIndigo--}
```
public static Color getIndigo()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF4B0082.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getIvory() {#getIvory--}
```
public static Color getIvory()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFFFF0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getKhaki() {#getKhaki--}
```
public static Color getKhaki()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFF0E68C.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLavender() {#getLavender--}
```
public static Color getLavender()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFE6E6FA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLavenderBlush() {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFF0F5.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLawnGreen() {#getLawnGreen--}
```
public static Color getLawnGreen()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF7CFC00.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLemonChiffon() {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFFACD.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightBlue() {#getLightBlue--}
```
public static Color getLightBlue()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFADD8E6.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightCoral() {#getLightCoral--}
```
public static Color getLightCoral()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFF08080.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightCyan() {#getLightCyan--}
```
public static Color getLightCyan()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFE0FFFF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightGoldenrodYellow() {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFAFAD2.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightGreen() {#getLightGreen--}
```
public static Color getLightGreen()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF90EE90.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightGray() {#getLightGray--}
```
public static Color getLightGray()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFD3D3D3.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightPink() {#getLightPink--}
```
public static Color getLightPink()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFB6C1.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSalmon() {#getLightSalmon--}
```
public static Color getLightSalmon()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFA07A.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSeaGreen() {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF20B2AA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSkyBlue() {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF87CEFA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSlateGray() {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF778899.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSteelBlue() {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFB0C4DE.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightYellow() {#getLightYellow--}
```
public static Color getLightYellow()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFFFE0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLime() {#getLime--}
```
public static Color getLime()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF00FF00.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLimeGreen() {#getLimeGreen--}
```
public static Color getLimeGreen()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF32CD32.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLinen() {#getLinen--}
```
public static Color getLinen()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFFAF0E6.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMagenta() {#getMagenta--}
```
public static Color getMagenta()
```


Λαμβάνει ένα χρώμα ορισμένο από το σύστημα που έχει τιμή ARGB \#FFFF00FF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMaroon() {#getMaroon--}
```
public static Color getMaroon()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF800000.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumAquamarine() {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF66CDAA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumBlue() {#getMediumBlue--}
```
public static Color getMediumBlue()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF0000CD.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumOrchid() {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFBA55D3.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumPurple() {#getMediumPurple--}
```
public static Color getMediumPurple()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF9370DB.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumSeaGreen() {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF3CB371.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumSlateBlue() {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF7B68EE.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumSpringGreen() {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF00FA9A.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumTurquoise() {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF48D1CC.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumVioletRed() {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFC71585.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMidnightBlue() {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF191970.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMintCream() {#getMintCream--}
```
public static Color getMintCream()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFF5FFFA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMistyRose() {#getMistyRose--}
```
public static Color getMistyRose()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFFFE4E1.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMoccasin() {#getMoccasin--}
```
public static Color getMoccasin()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFFFE4B5.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getNavajoWhite() {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFFFDEAD.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getNavy() {#getNavy--}
```
public static Color getNavy()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF000080.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOldLace() {#getOldLace--}
```
public static Color getOldLace()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFFDF5E6.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOlive() {#getOlive--}
```
public static Color getOlive()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF808000.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOliveDrab() {#getOliveDrab--}
```
public static Color getOliveDrab()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF6B8E23.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOrange() {#getOrange--}
```
public static Color getOrange()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFFFA500.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOrangeRed() {#getOrangeRed--}
```
public static Color getOrangeRed()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFFF4500.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOrchid() {#getOrchid--}
```
public static Color getOrchid()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFDA70D6.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPaleGoldenrod() {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FFEEE8AA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPaleGreen() {#getPaleGreen--}
```
public static Color getPaleGreen()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα με τιμή ARGB \#FF98FB98.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPaleTurquoise() {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFAFEEEE.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPaleVioletRed() {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFDB7093.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPapayaWhip() {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFEFD5.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPeachPuff() {#getPeachPuff--}
```
public static Color getPeachPuff()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFDAB9.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPeru() {#getPeru--}
```
public static Color getPeru()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFCD853F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPink() {#getPink--}
```
public static Color getPink()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFC0CB.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPlum() {#getPlum--}
```
public static Color getPlum()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFDDA0DD.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPowderBlue() {#getPowderBlue--}
```
public static Color getPowderBlue()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFB0E0E6.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPurple() {#getPurple--}
```
public static Color getPurple()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF800080.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getRed() {#getRed--}
```
public static Color getRed()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFF0000.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getRosyBrown() {#getRosyBrown--}
```
public static Color getRosyBrown()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFBC8F8F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getRoyalBlue() {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF4169E1.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSaddleBrown() {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF8B4513.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSalmon() {#getSalmon--}
```
public static Color getSalmon()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFA8072.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSandyBrown() {#getSandyBrown--}
```
public static Color getSandyBrown()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFF4A460.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSeaGreen() {#getSeaGreen--}
```
public static Color getSeaGreen()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF2E8B57.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSeaShell() {#getSeaShell--}
```
public static Color getSeaShell()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFF5EE.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSienna() {#getSienna--}
```
public static Color getSienna()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFA0522D.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSilver() {#getSilver--}
```
public static Color getSilver()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFC0C0C0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSkyBlue() {#getSkyBlue--}
```
public static Color getSkyBlue()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF87CEEB.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSlateBlue() {#getSlateBlue--}
```
public static Color getSlateBlue()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF6A5ACD.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSlateGray() {#getSlateGray--}
```
public static Color getSlateGray()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF708090.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSnow() {#getSnow--}
```
public static Color getSnow()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFFAFA.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSpringGreen() {#getSpringGreen--}
```
public static Color getSpringGreen()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF00FF7F.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSteelBlue() {#getSteelBlue--}
```
public static Color getSteelBlue()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF4682B4.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getTan() {#getTan--}
```
public static Color getTan()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFD2B48C.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getTeal() {#getTeal--}
```
public static Color getTeal()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF008080.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getThistle() {#getThistle--}
```
public static Color getThistle()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFD8BFD8.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getTomato() {#getTomato--}
```
public static Color getTomato()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFF6347.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getTurquoise() {#getTurquoise--}
```
public static Color getTurquoise()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF40E0D0.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getViolet() {#getViolet--}
```
public static Color getViolet()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFEE82EE.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getWheat() {#getWheat--}
```
public static Color getWheat()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFF5DEB3.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getWhite() {#getWhite--}
```
public static Color getWhite()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFFFFF.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getWhiteSmoke() {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFF5F5F5.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getYellow() {#getYellow--}
```
public static Color getYellow()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FFFFFF00.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getYellowGreen() {#getYellowGreen--}
```
public static Color getYellowGreen()
```


Λαμβάνει ένα χρώμα που ορίζεται από το σύστημα και έχει τιμή ARGB \#FF9ACD32.

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getA() {#getA--}
```
public final int getA()
```


Λαμβάνει την τιμή του συστατικού άλφα αυτής της δομής [Color](../../com.aspose.drawing/color).

**Returns:**
int - Η τιμή του συστατικού άλφα αυτής της [Color](../../com.aspose.drawing/color).
### getR() {#getR--}
```
public final int getR()
```


Λαμβάνει την τιμή του συστατικού κόκκινου αυτής της δομής [Color](../../com.aspose.drawing/color).

**Returns:**
int - Η τιμή του συστατικού κόκκινου αυτής της [Color](../../com.aspose.drawing/color).
### getG() {#getG--}
```
public final int getG()
```


Λαμβάνει την τιμή του συστατικού πράσινου αυτής της δομής [Color](../../com.aspose.drawing/color).

**Returns:**
int - Η τιμή του συστατικού πράσινου αυτής της [Color](../../com.aspose.drawing/color).
### getB() {#getB--}
```
public final int getB()
```


Λαμβάνει την τιμή του συστατικού μπλε αυτής της δομής [Color](../../com.aspose.drawing/color).

**Returns:**
int - Η τιμή του συστατικού μπλε αυτής της [Color](../../com.aspose.drawing/color).
### isKnownColor() {#isKnownColor--}
```
public final boolean isKnownColor()
```


Αποκτά μια τιμή που υποδεικνύει εάν αυτή η δομή [Color](../../com.aspose.drawing/color) είναι προεπιλεγμένο χρώμα. Τα προεπιλεγμένα χρώματα αντιπροσωπεύονται από τα στοιχεία της απαρίθμησης [KnownColor](../../com.aspose.drawing/knowncolor).

Τιμή: `true` εάν αυτή η [Color](../../com.aspose.drawing/color) δημιουργήθηκε από προεπιλεγμένο χρώμα χρησιμοποιώντας είτε τη μέθοδο `M:Color.FromName(System.String)` είτε τη μέθοδο `M:Color.FromKnownColor(System.Drawing.KnownColor)`· διαφορετικά, `false`.

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η δομή [Color](../../com.aspose.drawing/color) δεν έχει αρχικοποιηθεί.

Τιμή: Αυτή η ιδιότητα επιστρέφει true εάν αυτό το χρώμα δεν έχει αρχικοποιηθεί· διαφορετικά, false.

**Returns:**
boolean
### isNamedColor() {#isNamedColor--}
```
public final boolean isNamedColor()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η δομή [Color](../../com.aspose.drawing/color) είναι ένα ονομαστικό χρώμα ή μέλος της απαρίθμησης [KnownColor](../../com.aspose.drawing/knowncolor).

Τιμή: `true` εάν αυτή η [Color](../../com.aspose.drawing/color) δημιουργήθηκε χρησιμοποιώντας είτε τη μέθοδο `M:Color.FromName(System.String)` είτε τη μέθοδο `M:Color.FromKnownColor(System.Drawing.KnownColor)`· διαφορετικά, `false`.

**Returns:**
boolean
### isSystemColor() {#isSystemColor--}
```
public final boolean isSystemColor()
```


Αποκτά μια τιμή που υποδεικνύει εάν αυτή η δομή [Color](../../com.aspose.drawing/color) είναι χρώμα συστήματος. Ένα χρώμα συστήματος είναι ένα χρώμα που χρησιμοποιείται σε στοιχείο εμφάνισης των Windows. Τα χρώματα συστήματος αντιπροσωπεύονται από στοιχεία της απαρίθμησης [KnownColor](../../com.aspose.drawing/knowncolor).

Τιμή: `true` εάν αυτή η [Color](../../com.aspose.drawing/color) δημιουργήθηκε από χρώμα συστήματος χρησιμοποιώντας είτε τη μέθοδο `M:Color.FromName(System.String)` είτε τη μέθοδο `M:Color.FromKnownColor(System.Drawing.KnownColor)`· διαφορετικά, `false`.

**Returns:**
boolean
### getName() {#getName--}
```
public final String getName()
```


Λαμβάνει το όνομα αυτής της [Color](../../com.aspose.drawing/color).

**Returns:**
java.lang.String
### fromArgb(int argb) {#fromArgb-int-}
```
public static Color fromArgb(int argb)
```


Δημιουργεί μια δομή [Color](../../com.aspose.drawing/color) από μια 32-bit τιμή ARGB.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| argb | int | Μια τιμή που καθορίζει την 32-bit τιμή ARGB. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that this method creates.
### fromArgb(int alpha, Color baseColor) {#fromArgb-int-com.aspose.drawing.Color-}
```
public static Color fromArgb(int alpha, Color baseColor)
```


Δημιουργεί μια δομή [Color](../../com.aspose.drawing/color) από την καθορισμένη δομή [Color](../../com.aspose.drawing/color), αλλά με τη νέα καθορισμένη τιμή άλφα. Παρόλο που αυτή η μέθοδος επιτρέπει τη μεταφορά μιας 32-bit τιμής για την τιμή άλφα, η τιμή περιορίζεται σε 8 bits.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alpha | int | Η τιμή άλφα για το νέο [Color](../../com.aspose.drawing/color). Οι έγκυρες τιμές είναι από 0 έως 255. |
| baseColor | [Color](../../com.aspose.drawing/color) | Το [Color](../../com.aspose.drawing/color) από το οποίο θα δημιουργηθεί το νέο [Color](../../com.aspose.drawing/color). |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) that this method creates.
### fromArgb(int red, int green, int blue) {#fromArgb-int-int-int-}
```
public static Color fromArgb(int red, int green, int blue)
```


Δημιουργεί μια δομή [Color](../../com.aspose.drawing/color) από τις καθορισμένες τιμές χρώματος 8-bit (κόκκινο, πράσινο και μπλε). Η τιμή alpha είναι έμμεσα 255 (πλήρως αδιαφανής). Αν και αυτή η μέθοδος επιτρέπει τη μεταβίβαση μιας τιμής 32-bit για κάθε συνιστώσα χρώματος, η τιμή κάθε συνιστώσας περιορίζεται σε 8 bit.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| red | int | Η τιμή της κόκκινης συνιστώσας για το νέο [Color](../../com.aspose.drawing/color). Οι έγκυρες τιμές είναι από 0 έως 255. |
| green | int | Η τιμή της πράσινης συνιστώσας για το νέο [Color](../../com.aspose.drawing/color). Οι έγκυρες τιμές είναι από 0 έως 255. |
| blue | int | Η τιμή της μπλε συνιστώσας για το νέο [Color](../../com.aspose.drawing/color). Οι έγκυρες τιμές είναι από 0 έως 255. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) that this method creates.
### fromArgb(int alpha, int red, int green, int blue) {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int alpha, int red, int green, int blue)
```


Δημιουργεί μια δομή Color από τις τέσσερις τιμές των συνιστωσών ARGB (alpha, κόκκινο, πράσινο και μπλε). Αν και αυτή η μέθοδος επιτρέπει τη μεταβίβαση μιας τιμής 32-bit για κάθε συνιστώσα, η τιμή κάθε συνιστώσας περιορίζεται σε 8 bit.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alpha | int | Η συνιστώσα alpha. Οι έγκυρες τιμές είναι από 0 έως 255. |
| red | int | Η κόκκινη συνιστώσα. Οι έγκυρες τιμές είναι από 0 έως 255. |
| green | int | Η πράσινη συνιστώσα. Οι έγκυρες τιμές είναι από 0 έως 255. |
| blue | int | Η μπλε συνιστώσα. Οι έγκυρες τιμές είναι από 0 έως 255. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The Color that this method creates.
### fromKnownColor(int color) {#fromKnownColor-int-}
```
public static Color fromKnownColor(int color)
```


Δημιουργεί μια δομή [Color](../../com.aspose.drawing/color) από το καθορισμένο προκαθορισμένο χρώμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| color | int | Ένα στοιχείο της απαρίθμησης [KnownColor](../../com.aspose.drawing/knowncolor). |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) that this method creates.
### fromName(String name) {#fromName-java.lang.String-}
```
public static Color fromName(String name)
```


Δημιουργεί μια δομή [Color](../../com.aspose.drawing/color) από το καθορισμένο όνομα ενός προεπιλεγμένου χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Μια συμβολοσειρά που είναι το όνομα ενός προκαθορισμένου χρώματος. Τα έγκυρα ονόματα είναι τα ίδια με τα ονόματα των στοιχείων της απαρίθμησης [KnownColor](../../com.aspose.drawing/knowncolor). |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) that this method creates.
### op_Equality(Color left, Color right) {#op-Equality-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public static boolean op_Equality(Color left, Color right)
```


Ελέγχει εάν δύο καθορισμένες δομές [Color](../../com.aspose.drawing/color) είναι ισοδύναμες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [Color](../../com.aspose.drawing/color) | Το [Color](../../com.aspose.drawing/color) που βρίσκεται αριστερά του τελεστή ισότητας. |
| right | [Color](../../com.aspose.drawing/color) | Το [Color](../../com.aspose.drawing/color) που βρίσκεται δεξιά του τελεστή ισότητας. |

**Returns:**
boolean - `true` εάν οι δύο δομές [Color](../../com.aspose.drawing/color) είναι ίσες· διαφορετικά, `false`.
### op_Inequality(Color left, Color right) {#op-Inequality-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public static boolean op_Inequality(Color left, Color right)
```


Ελέγχει εάν δύο καθορισμένες δομές [Color](../../com.aspose.drawing/color) είναι διαφορετικές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [Color](../../com.aspose.drawing/color) | Το [Color](../../com.aspose.drawing/color) που βρίσκεται αριστερά του τελεστή ανισότητας. |
| right | [Color](../../com.aspose.drawing/color) | Το [Color](../../com.aspose.drawing/color) που βρίσκεται δεξιά του τελεστή ανισότητας. |

**Returns:**
boolean - `true` εάν οι δύο δομές [Color](../../com.aspose.drawing/color) είναι διαφορετικές· διαφορετικά, `false`.
### equals(Color other) {#equals-com.aspose.drawing.Color-}
```
public final boolean equals(Color other)
```


Ελέγχει εάν το καθορισμένο χρώμα είναι ισοδύναμο με αυτό το χρώμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [Color](../../com.aspose.drawing/color) | Το χρώμα προς δοκιμή. |

**Returns:**
boolean - `` εάν το καθορισμένο χρώμα είναι ισοδύναμο με αυτό το χρώμα· διαφορετικά, ``.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Ελέγχει εάν το καθορισμένο αντικείμενο είναι ισοδύναμο με αυτό το χρώμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το αντικείμενο προς δοκιμή. |

**Returns:**
boolean - `` εάν το καθορισμένο αντικείμενο είναι ισοδύναμο με αυτό το χρώμα· διαφορετικά, ``.
### toArgb() {#toArgb--}
```
public final int toArgb()
```


Αποκτά την 32-bit τιμή ARGB αυτής της δομής Color.

**Returns:**
int - Η 32-bit τιμή ARGB αυτού του Color.
### getBrightness() {#getBrightness--}
```
public final float getBrightness()
```


Αποκτά την τιμή φωτεινότητας hue-saturation-brightness (HSB) για αυτή τη δομή [Color](../../com.aspose.drawing/color).

**Returns:**
float - Η φωτεινότητα αυτού του [Color](../../com.aspose.drawing/color). Η φωτεινότητα κυμαίνεται από 0.0 έως 1.0, όπου 0.0 αντιπροσωπεύει το μαύρο και 1.0 το λευκό.
### getHue() {#getHue--}
```
public final float getHue()
```


Αποκτά την τιμή απόχρωσης hue-saturation-brightness (HSB), σε μοίρες, για αυτή τη δομή [Color](../../com.aspose.drawing/color).

**Returns:**
float - Η απόχρωση, σε μοίρες, αυτού του java.awt.Color. Η απόχρωση μετράται σε μοίρες, κυμαινόμενη από 0.0 έως 360.0, στο χρωματικό χώρο HSB.
### getSaturation() {#getSaturation--}
```
public final float getSaturation()
```


Αποκτά την τιμή κορεσμού hue-saturation-brightness (HSB) για αυτή τη δομή [Color](../../com.aspose.drawing/color).

**Returns:**
float - Ο κορεσμός αυτού του [Color](../../com.aspose.drawing/color). Ο κορεσμός κυμαίνεται από 0.0 έως 1.0, όπου 0.0 είναι σε αποχρώσεις του γκρι και 1.0 είναι ο μέγιστος κορεσμός.
### toKnownColor() {#toKnownColor--}
```
public final int toKnownColor()
```


Αποκτά την τιμή [KnownColor](../../com.aspose.drawing/knowncolor) αυτής της δομής [Color](../../com.aspose.drawing/color).

**Returns:**
int - Ένα στοιχείο της απαρίθμησης [KnownColor](../../com.aspose.drawing/knowncolor), εάν το [Color](../../com.aspose.drawing/color) δημιουργείται από προεπιλεγμένο χρώμα χρησιμοποιώντας είτε τη μέθοδο `M:Color.FromName(System.String)` είτε τη μέθοδο `M:Color.FromKnownColor(KnownColor)`· διαφορετικά, 0.
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει ένα String που αντιπροσωπεύει αυτήν την παρουσία.

**Returns:**
java.lang.String - Μια String που αντιπροσωπεύει αυτήν την παρουσία.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό κατακερματισμού για αυτήν την instance.

**Returns:**
int - Ένας κωδικός κατακερματισμού για αυτήν την παρουσία, κατάλληλος για χρήση σε αλγόριθμους κατακερματισμού και δομές δεδομένων όπως ένας πίνακας κατακερματισμού.
### isEquals(Color obj1, Color obj2) {#isEquals-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public static boolean isEquals(Color obj1, Color obj2)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| that | [Color](../../com.aspose.drawing/color) |  |

### Clone() {#Clone--}
```
public Color Clone()
```




**Returns:**
[Color](../../com.aspose.drawing/color)
