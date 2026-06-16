---
title: Color
second_title: Aspose.Drawing for Java API リファレンス
description: ARGB（アルファ、赤、緑、青）カラーを表します。
type: docs
weight: 14
url: /ja/java/com.aspose.drawing/color/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Color extends Struct<Color> implements System.IEquatable<Color>, Cloneable
```

ARGB（アルファ、赤、緑、青）カラーを表します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Color()](#Color--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [EMPTY](#EMPTY) | null のカラーを表します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTransparent()](#getTransparent--) | システム定義のカラーを取得します。 |
| [getAliceBlue()](#getAliceBlue--) | ARGB 値が \#FFF0F8FF のシステム定義カラーを取得します。 |
| [getAntiqueWhite()](#getAntiqueWhite--) | ARGB 値が \#FFFAEBD7 のシステム定義カラーを取得します。 |
| [getAqua()](#getAqua--) | ARGB 値 \#FF00FFFF を持つシステム定義の色を取得します。 |
| [getAquamarine()](#getAquamarine--) | ARGB 値 \#FF7FFFD4 を持つシステム定義の色を取得します。 |
| [getAzure()](#getAzure--) | ARGB 値 \#FFF0FFFF を持つシステム定義の色を取得します。 |
| [getBeige()](#getBeige--) | ARGB 値 \#FFF5F5DC を持つシステム定義の色を取得します。 |
| [getBisque()](#getBisque--) | ARGB 値 \#FFFFE4C4 を持つシステム定義の色を取得します。 |
| [getBlack()](#getBlack--) | ARGB 値 \#FF000000 を持つシステム定義の色を取得します。 |
| [getBlanchedAlmond()](#getBlanchedAlmond--) | ARGB 値 \#FFFFEBCD を持つシステム定義の色を取得します。 |
| [getBlue()](#getBlue--) | ARGB 値 \#FF0000FF を持つシステム定義の色を取得します。 |
| [getBlueViolet()](#getBlueViolet--) | ARGB 値 \#FF8A2BE2 を持つシステム定義の色を取得します。 |
| [getBrown()](#getBrown--) | ARGB 値 \#FFA52A2A を持つシステム定義の色を取得します。 |
| [getBurlyWood()](#getBurlyWood--) | ARGB 値 \#FFDEB887 を持つシステム定義の色を取得します。 |
| [getCadetBlue()](#getCadetBlue--) | ARGB 値 \#FF5F9EA0 を持つシステム定義の色を取得します。 |
| [getChartreuse()](#getChartreuse--) | ARGB 値 \#FF7FFF00 を持つシステム定義の色を取得します。 |
| [getChocolate()](#getChocolate--) | ARGB 値 \#FFD2691E を持つシステム定義の色を取得します。 |
| [getCoral()](#getCoral--) | ARGB 値 \#FFFF7F50 を持つシステム定義の色を取得します。 |
| [getCornflowerBlue()](#getCornflowerBlue--) | ARGB 値 \#FF6495ED を持つシステム定義の色を取得します。 |
| [getCornsilk()](#getCornsilk--) | ARGB 値 \#FFFFF8DC を持つシステム定義の色を取得します。 |
| [getCrimson()](#getCrimson--) | ARGB 値 \#FFDC143C を持つシステム定義の色を取得します。 |
| [getCyan()](#getCyan--) | ARGB 値 \#FF00FFFF を持つシステム定義の色を取得します。 |
| [getDarkBlue()](#getDarkBlue--) | ARGB 値 \#FF00008B を持つシステム定義の色を取得します。 |
| [getDarkCyan()](#getDarkCyan--) | ARGB 値 \#FF008B8B を持つシステム定義の色を取得します。 |
| [getDarkGoldenrod()](#getDarkGoldenrod--) | ARGB 値 \#FFB8860B を持つシステム定義の色を取得します。 |
| [getDarkGray()](#getDarkGray--) | ARGB 値 \#FFA9A9A9 を持つシステム定義の色を取得します。 |
| [getDarkGreen()](#getDarkGreen--) | ARGB 値 \#FF006400 を持つシステム定義の色を取得します。 |
| [getDarkKhaki()](#getDarkKhaki--) | ARGB 値 \#FFBDB76B を持つシステム定義の色を取得します。 |
| [getDarkMagenta()](#getDarkMagenta--) | ARGB 値 \#FF8B008B を持つシステム定義の色を取得します。 |
| [getDarkOliveGreen()](#getDarkOliveGreen--) | ARGB 値が \#FF556B2F のシステム定義の色を取得します。 |
| [getDarkOrange()](#getDarkOrange--) | ARGB 値が \#FFFF8C00 のシステム定義の色を取得します。 |
| [getDarkOrchid()](#getDarkOrchid--) | ARGB 値が \#FF9932CC のシステム定義の色を取得します。 |
| [getDarkRed()](#getDarkRed--) | ARGB 値が \#FF8B0000 のシステム定義の色を取得します。 |
| [getDarkSalmon()](#getDarkSalmon--) | ARGB 値が \#FFE9967A のシステム定義の色を取得します。 |
| [getDarkSeaGreen()](#getDarkSeaGreen--) | ARGB 値が \#FF8FBC8F のシステム定義の色を取得します。 |
| [getDarkSlateBlue()](#getDarkSlateBlue--) | ARGB 値が \#FF483D8B のシステム定義の色を取得します。 |
| [getDarkSlateGray()](#getDarkSlateGray--) | ARGB 値が \#FF2F4F4F のシステム定義の色を取得します。 |
| [getDarkTurquoise()](#getDarkTurquoise--) | ARGB 値が \#FF00CED1 のシステム定義の色を取得します。 |
| [getDarkViolet()](#getDarkViolet--) | ARGB 値が \#FF9400D3 のシステム定義の色を取得します。 |
| [getDeepPink()](#getDeepPink--) | ARGB 値が \#FFFF1493 のシステム定義の色を取得します。 |
| [getDeepSkyBlue()](#getDeepSkyBlue--) | ARGB 値が \#FF00BFFF のシステム定義の色を取得します。 |
| [getDimGray()](#getDimGray--) | ARGB 値が \#FF696969 のシステム定義の色を取得します。 |
| [getDodgerBlue()](#getDodgerBlue--) | ARGB 値が \#FF1E90FF のシステム定義の色を取得します。 |
| [getFirebrick()](#getFirebrick--) | ARGB 値が \#FFB22222 のシステム定義の色を取得します。 |
| [getFloralWhite()](#getFloralWhite--) | ARGB 値が \#FFFFFAF0 のシステム定義の色を取得します。 |
| [getForestGreen()](#getForestGreen--) | ARGB 値が \#FF228B22 のシステム定義の色を取得します。 |
| [getFuchsia()](#getFuchsia--) | ARGB 値が \#FFFF00FF のシステム定義の色を取得します。 |
| [getGainsboro()](#getGainsboro--) | ARGB 値が \#FFDCDCDC のシステム定義の色を取得します。 |
| [getGhostWhite()](#getGhostWhite--) | ARGB 値が \#FFF8F8FF のシステム定義の色を取得します。 |
| [getGold()](#getGold--) | ARGB 値が \#FFFFD700 のシステム定義の色を取得します。 |
| [getGoldenrod()](#getGoldenrod--) | ARGB 値が \#FFDAA520 のシステム定義の色を取得します。 |
| [getGray()](#getGray--) | ARGB 値が \#FF808080 のシステム定義の色を取得します。 |
| [getGreen()](#getGreen--) | ARGB 値が \#FF008000 のシステム定義の色を取得します。 |
| [getGreenYellow()](#getGreenYellow--) | ARGB 値が \#FFADFF2F のシステム定義の色を取得します。 |
| [getHoneydew()](#getHoneydew--) | ARGB 値が \#FFF0FFF0 のシステム定義の色を取得します。 |
| [getHotPink()](#getHotPink--) | ARGB 値が \#FFFF69B4 のシステム定義の色を取得します。 |
| [getIndianRed()](#getIndianRed--) | ARGB 値が \#FFCD5C5C のシステム定義の色を取得します。 |
| [getIndigo()](#getIndigo--) | ARGB 値が \#FF4B0082 のシステム定義の色を取得します。 |
| [getIvory()](#getIvory--) | ARGB 値が \#FFFFFFF0 のシステム定義の色を取得します。 |
| [getKhaki()](#getKhaki--) | ARGB 値が \#FFF0E68C のシステム定義の色を取得します。 |
| [getLavender()](#getLavender--) | ARGB 値が \#FFE6E6FA のシステム定義の色を取得します。 |
| [getLavenderBlush()](#getLavenderBlush--) | ARGB 値が \#FFFFF0F5 のシステム定義の色を取得します。 |
| [getLawnGreen()](#getLawnGreen--) | ARGB 値が \#FF7CFC00 のシステム定義の色を取得します。 |
| [getLemonChiffon()](#getLemonChiffon--) | ARGB 値が \#FFFFFACD のシステム定義の色を取得します。 |
| [getLightBlue()](#getLightBlue--) | ARGB 値が \#FFADD8E6 のシステム定義の色を取得します。 |
| [getLightCoral()](#getLightCoral--) | ARGB 値が \#FFF08080 のシステム定義の色を取得します。 |
| [getLightCyan()](#getLightCyan--) | ARGB 値が \#FFE0FFFF のシステム定義の色を取得します。 |
| [getLightGoldenrodYellow()](#getLightGoldenrodYellow--) | ARGB 値が \#FFFAFAD2 のシステム定義の色を取得します。 |
| [getLightGreen()](#getLightGreen--) | ARGB 値が \#FF90EE90 のシステム定義の色を取得します。 |
| [getLightGray()](#getLightGray--) | ARGB 値が \#FFD3D3D3 のシステム定義の色を取得します。 |
| [getLightPink()](#getLightPink--) | ARGB 値が \#FFFFB6C1 のシステム定義の色を取得します。 |
| [getLightSalmon()](#getLightSalmon--) | ARGB 値が \#FFFFA07A のシステム定義の色を取得します。 |
| [getLightSeaGreen()](#getLightSeaGreen--) | ARGB 値が \#FF20B2AA のシステム定義の色を取得します。 |
| [getLightSkyBlue()](#getLightSkyBlue--) | ARGB 値が \#FF87CEFA のシステム定義の色を取得します。 |
| [getLightSlateGray()](#getLightSlateGray--) | ARGB 値が \#FF778899 のシステム定義の色を取得します。 |
| [getLightSteelBlue()](#getLightSteelBlue--) | ARGB 値が \#FFB0C4DE のシステム定義の色を取得します。 |
| [getLightYellow()](#getLightYellow--) | ARGB 値が \#FFFFFFE0 のシステム定義の色を取得します。 |
| [getLime()](#getLime--) | ARGB 値が \#FF00FF00 のシステム定義の色を取得します。 |
| [getLimeGreen()](#getLimeGreen--) | ARGB 値が \#FF32CD32 のシステム定義の色を取得します。 |
| [getLinen()](#getLinen--) | システム定義の色を取得します（ARGB 値は \#FFFAF0E6）。 |
| [getMagenta()](#getMagenta--) | ARGB 値が \#FFFF00FF のシステム定義の色を取得します。 |
| [getMaroon()](#getMaroon--) | システム定義の色を取得します（ARGB 値は \#FF800000）。 |
| [getMediumAquamarine()](#getMediumAquamarine--) | システム定義の色を取得します（ARGB 値は \#FF66CDAA）。 |
| [getMediumBlue()](#getMediumBlue--) | システム定義の色を取得します（ARGB 値は \#FF0000CD）。 |
| [getMediumOrchid()](#getMediumOrchid--) | システム定義の色を取得します（ARGB 値は \#FFBA55D3）。 |
| [getMediumPurple()](#getMediumPurple--) | システム定義の色を取得します（ARGB 値は \#FF9370DB）。 |
| [getMediumSeaGreen()](#getMediumSeaGreen--) | システム定義の色を取得します（ARGB 値は \#FF3CB371）。 |
| [getMediumSlateBlue()](#getMediumSlateBlue--) | システム定義の色を取得します（ARGB 値は \#FF7B68EE）。 |
| [getMediumSpringGreen()](#getMediumSpringGreen--) | システム定義の色を取得します（ARGB 値は \#FF00FA9A）。 |
| [getMediumTurquoise()](#getMediumTurquoise--) | システム定義の色を取得します（ARGB 値は \#FF48D1CC）。 |
| [getMediumVioletRed()](#getMediumVioletRed--) | システム定義の色を取得します（ARGB 値は \#FFC71585）。 |
| [getMidnightBlue()](#getMidnightBlue--) | システム定義の色を取得します（ARGB 値は \#FF191970）。 |
| [getMintCream()](#getMintCream--) | システム定義の色を取得します（ARGB 値は \#FFF5FFFA）。 |
| [getMistyRose()](#getMistyRose--) | システム定義の色を取得します（ARGB 値は \#FFFFE4E1）。 |
| [getMoccasin()](#getMoccasin--) | システム定義の色を取得します（ARGB 値は \#FFFFE4B5）。 |
| [getNavajoWhite()](#getNavajoWhite--) | システム定義の色を取得します（ARGB 値は \#FFFFDEAD）。 |
| [getNavy()](#getNavy--) | システム定義の色を取得します（ARGB 値は \#FF000080）。 |
| [getOldLace()](#getOldLace--) | システム定義の色を取得します（ARGB 値は \#FFFDF5E6）。 |
| [getOlive()](#getOlive--) | システム定義の色を取得します（ARGB 値は \#FF808000）。 |
| [getOliveDrab()](#getOliveDrab--) | システム定義の色を取得します（ARGB 値は \#FF6B8E23）。 |
| [getOrange()](#getOrange--) | システム定義の色を取得します（ARGB 値は \#FFFFA500）。 |
| [getOrangeRed()](#getOrangeRed--) | システム定義の色を取得します（ARGB 値は \#FFFF4500）。 |
| [getOrchid()](#getOrchid--) | システム定義の色を取得します（ARGB 値は \#FFDA70D6）。 |
| [getPaleGoldenrod()](#getPaleGoldenrod--) | システム定義の色を取得します（ARGB 値は \#FFEEE8AA）。 |
| [getPaleGreen()](#getPaleGreen--) | システム定義の色を取得します（ARGB 値は \#FF98FB98）。 |
| [getPaleTurquoise()](#getPaleTurquoise--) | システム定義の色を取得します。この色の ARGB 値は \#FFAFEEEE です。 |
| [getPaleVioletRed()](#getPaleVioletRed--) | システム定義の色を取得します。この色の ARGB 値は \#FFDB7093 です。 |
| [getPapayaWhip()](#getPapayaWhip--) | システム定義の色を取得します。この色の ARGB 値は \#FFFFEFD5 です。 |
| [getPeachPuff()](#getPeachPuff--) | システム定義の色を取得します。この色の ARGB 値は \#FFFFDAB9 です。 |
| [getPeru()](#getPeru--) | システム定義の色を取得します。この色の ARGB 値は \#FFCD853F です。 |
| [getPink()](#getPink--) | システム定義の色を取得します。この色の ARGB 値は \#FFFFC0CB です。 |
| [getPlum()](#getPlum--) | システム定義の色を取得します。この色の ARGB 値は \#FFDDA0DD です。 |
| [getPowderBlue()](#getPowderBlue--) | システム定義の色を取得します。この色の ARGB 値は \#FFB0E0E6 です。 |
| [getPurple()](#getPurple--) | システム定義の色を取得します。この色の ARGB 値は \#FF800080 です。 |
| [getRed()](#getRed--) | システム定義の色を取得します。この色の ARGB 値は \#FFFF0000 です。 |
| [getRosyBrown()](#getRosyBrown--) | システム定義の色を取得します。この色の ARGB 値は \#FFBC8F8F です。 |
| [getRoyalBlue()](#getRoyalBlue--) | システム定義の色を取得します。この色の ARGB 値は \#FF4169E1 です。 |
| [getSaddleBrown()](#getSaddleBrown--) | システム定義の色を取得します。この色の ARGB 値は \#FF8B4513 です。 |
| [getSalmon()](#getSalmon--) | システム定義の色を取得します。この色の ARGB 値は \#FFFA8072 です。 |
| [getSandyBrown()](#getSandyBrown--) | システム定義の色を取得します。この色の ARGB 値は \#FFF4A460 です。 |
| [getSeaGreen()](#getSeaGreen--) | システム定義の色を取得します。この色の ARGB 値は \#FF2E8B57 です。 |
| [getSeaShell()](#getSeaShell--) | システム定義の色を取得します。この色の ARGB 値は \#FFFFF5EE です。 |
| [getSienna()](#getSienna--) | システム定義の色を取得します。この色の ARGB 値は \#FFA0522D です。 |
| [getSilver()](#getSilver--) | システム定義の色を取得します。この色の ARGB 値は \#FFC0C0C0 です。 |
| [getSkyBlue()](#getSkyBlue--) | システム定義の色を取得します。この色の ARGB 値は \#FF87CEEB です。 |
| [getSlateBlue()](#getSlateBlue--) | システム定義の色を取得します。この色の ARGB 値は \#FF6A5ACD です。 |
| [getSlateGray()](#getSlateGray--) | システム定義の色を取得します。この色の ARGB 値は \#FF708090 です。 |
| [getSnow()](#getSnow--) | システム定義の色を取得します。この色の ARGB 値は \#FFFFFAFA です。 |
| [getSpringGreen()](#getSpringGreen--) | システム定義の色を取得します。この色の ARGB 値は \#FF00FF7F です。 |
| [getSteelBlue()](#getSteelBlue--) | システム定義の色を取得します。この色の ARGB 値は \#FF4682B4 です。 |
| [getTan()](#getTan--) | ARGB 値が \#FFD2B48C のシステム定義カラーを取得します。 |
| [getTeal()](#getTeal--) | ARGB 値が \#FF008080 のシステム定義カラーを取得します。 |
| [getThistle()](#getThistle--) | ARGB 値が \#FFD8BFD8 のシステム定義カラーを取得します。 |
| [getTomato()](#getTomato--) | ARGB 値が \#FFFF6347 のシステム定義カラーを取得します。 |
| [getTurquoise()](#getTurquoise--) | ARGB 値が \#FF40E0D0 のシステム定義カラーを取得します。 |
| [getViolet()](#getViolet--) | ARGB 値が \#FFEE82EE のシステム定義カラーを取得します。 |
| [getWheat()](#getWheat--) | ARGB 値が \#FFF5DEB3 のシステム定義カラーを取得します。 |
| [getWhite()](#getWhite--) | ARGB 値が \#FFFFFFFF のシステム定義カラーを取得します。 |
| [getWhiteSmoke()](#getWhiteSmoke--) | ARGB 値が \#FFF5F5F5 のシステム定義カラーを取得します。 |
| [getYellow()](#getYellow--) | ARGB 値が \#FFFFFF00 のシステム定義カラーを取得します。 |
| [getYellowGreen()](#getYellowGreen--) | ARGB 値が \#FF9ACD32 のシステム定義カラーを取得します。 |
| [getA()](#getA--) | この [Color](../../com.aspose.drawing/color) 構造体のアルファ コンポーネント値を取得します。 |
| [getR()](#getR--) | この [Color](../../com.aspose.drawing/color) 構造体の赤 コンポーネント値を取得します。 |
| [getG()](#getG--) | この [Color](../../com.aspose.drawing/color) 構造体の緑 コンポーネント値を取得します。 |
| [getB()](#getB--) | この [Color](../../com.aspose.drawing/color) 構造体の青 コンポーネント値を取得します。 |
| [isKnownColor()](#isKnownColor--) | この [Color](../../com.aspose.drawing/color) 構造体が事前定義された色かどうかを示す値を取得します。 |
| [isEmpty()](#isEmpty--) | この [Color](../../com.aspose.drawing/color) 構造体が初期化されていないかどうかを示す値を取得します。 |
| [isNamedColor()](#isNamedColor--) | この [Color](../../com.aspose.drawing/color) 構造体が名前付きの色か、[KnownColor](../../com.aspose.drawing/knowncolor) 列挙体のメンバーかどうかを示す値を取得します。 |
| [isSystemColor()](#isSystemColor--) | この [Color](../../com.aspose.drawing/color) 構造体がシステムカラーかどうかを示す値を取得します。 |
| [getName()](#getName--) | この [Color](../../com.aspose.drawing/color) の名前を取得します。 |
| [fromArgb(int argb)](#fromArgb-int-) | 32 ビット ARGB 値から [Color](../../com.aspose.drawing/color) 構造体を作成します。 |
| [fromArgb(int alpha, Color baseColor)](#fromArgb-int-com.aspose.drawing.Color-) | 指定された [Color](../../com.aspose.drawing/color) 構造体から、新しいアルファ値を指定した [Color](../../com.aspose.drawing/color) 構造体を作成します。 |
| [fromArgb(int red, int green, int blue)](#fromArgb-int-int-int-) | 指定された 8 ビットのカラー値（赤、緑、青）から [Color](../../com.aspose.drawing/color) 構造体を作成します。 |
| [fromArgb(int alpha, int red, int green, int blue)](#fromArgb-int-int-int-int-) | 4 つの ARGB コンポーネント（アルファ、赤、緑、青）の値から Color 構造体を作成します。 |
| [fromKnownColor(int color)](#fromKnownColor-int-) | 指定された事前定義色から [Color](../../com.aspose.drawing/color) 構造体を作成します。 |
| [fromName(String name)](#fromName-java.lang.String-) | 指定された既定の色名から [Color](../../com.aspose.drawing/color) 構造体を作成します。 |
| [op_Equality(Color left, Color right)](#op-Equality-com.aspose.drawing.Color-com.aspose.drawing.Color-) | 指定された 2 つの [Color](../../com.aspose.drawing/color) 構造体が等しいかどうかをテストします。 |
| [op_Inequality(Color left, Color right)](#op-Inequality-com.aspose.drawing.Color-com.aspose.drawing.Color-) | 指定された 2 つの [Color](../../com.aspose.drawing/color) 構造体が異なるかどうかをテストします。 |
| [equals(Color other)](#equals-com.aspose.drawing.Color-) | 指定された色がこの色と等しいかどうかをテストします。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定されたオブジェクトがこの色と等しいかどうかをテストします。 |
| [toArgb()](#toArgb--) | この Color 構造体の 32 ビット ARGB 値を取得します。 |
| [getBrightness()](#getBrightness--) | この [Color](../../com.aspose.drawing/color) 構造体の色相・彩度・明度 (HSB) の明度値を取得します。 |
| [getHue()](#getHue--) | この [Color](../../com.aspose.drawing/color) 構造体の色相・彩度・明度 (HSB) の色相値（度単位）を取得します。 |
| [getSaturation()](#getSaturation--) | この [Color](../../com.aspose.drawing/color) 構造体の色相・彩度・明度 (HSB) の彩度値を取得します。 |
| [toKnownColor()](#toKnownColor--) | この [Color](../../com.aspose.drawing/color) 構造体の [KnownColor](../../com.aspose.drawing/knowncolor) 値を取得します。 |
| [toString()](#toString--) | このインスタンスを表す文字列を返します。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
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


null のカラーを表します。

### getTransparent() {#getTransparent--}
```
public static Color getTransparent()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAliceBlue() {#getAliceBlue--}
```
public static Color getAliceBlue()
```


ARGB 値が \#FFF0F8FF のシステム定義カラーを取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAntiqueWhite() {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```


ARGB 値が \#FFFAEBD7 のシステム定義カラーを取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAqua() {#getAqua--}
```
public static Color getAqua()
```


ARGB 値 \#FF00FFFF を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAquamarine() {#getAquamarine--}
```
public static Color getAquamarine()
```


ARGB 値 \#FF7FFFD4 を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getAzure() {#getAzure--}
```
public static Color getAzure()
```


ARGB 値 \#FFF0FFFF を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBeige() {#getBeige--}
```
public static Color getBeige()
```


ARGB 値 \#FFF5F5DC を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBisque() {#getBisque--}
```
public static Color getBisque()
```


ARGB 値 \#FFFFE4C4 を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBlack() {#getBlack--}
```
public static Color getBlack()
```


ARGB 値 \#FF000000 を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBlanchedAlmond() {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```


ARGB 値 \#FFFFEBCD を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBlue() {#getBlue--}
```
public static Color getBlue()
```


ARGB 値 \#FF0000FF を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBlueViolet() {#getBlueViolet--}
```
public static Color getBlueViolet()
```


ARGB 値 \#FF8A2BE2 を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBrown() {#getBrown--}
```
public static Color getBrown()
```


ARGB 値 \#FFA52A2A を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getBurlyWood() {#getBurlyWood--}
```
public static Color getBurlyWood()
```


ARGB 値 \#FFDEB887 を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCadetBlue() {#getCadetBlue--}
```
public static Color getCadetBlue()
```


ARGB 値 \#FF5F9EA0 を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getChartreuse() {#getChartreuse--}
```
public static Color getChartreuse()
```


ARGB 値 \#FF7FFF00 を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getChocolate() {#getChocolate--}
```
public static Color getChocolate()
```


ARGB 値 \#FFD2691E を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCoral() {#getCoral--}
```
public static Color getCoral()
```


ARGB 値 \#FFFF7F50 を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCornflowerBlue() {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```


ARGB 値 \#FF6495ED を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCornsilk() {#getCornsilk--}
```
public static Color getCornsilk()
```


ARGB 値 \#FFFFF8DC を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCrimson() {#getCrimson--}
```
public static Color getCrimson()
```


ARGB 値 \#FFDC143C を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getCyan() {#getCyan--}
```
public static Color getCyan()
```


ARGB 値 \#FF00FFFF を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkBlue() {#getDarkBlue--}
```
public static Color getDarkBlue()
```


ARGB 値 \#FF00008B を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkCyan() {#getDarkCyan--}
```
public static Color getDarkCyan()
```


ARGB 値 \#FF008B8B を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkGoldenrod() {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```


ARGB 値 \#FFB8860B を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkGray() {#getDarkGray--}
```
public static Color getDarkGray()
```


ARGB 値 \#FFA9A9A9 を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkGreen() {#getDarkGreen--}
```
public static Color getDarkGreen()
```


ARGB 値 \#FF006400 を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkKhaki() {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```


ARGB 値 \#FFBDB76B を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkMagenta() {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```


ARGB 値 \#FF8B008B を持つシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkOliveGreen() {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```


ARGB 値が \#FF556B2F のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkOrange() {#getDarkOrange--}
```
public static Color getDarkOrange()
```


ARGB 値が \#FFFF8C00 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkOrchid() {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```


ARGB 値が \#FF9932CC のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkRed() {#getDarkRed--}
```
public static Color getDarkRed()
```


ARGB 値が \#FF8B0000 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkSalmon() {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```


ARGB 値が \#FFE9967A のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkSeaGreen() {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```


ARGB 値が \#FF8FBC8F のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkSlateBlue() {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```


ARGB 値が \#FF483D8B のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkSlateGray() {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```


ARGB 値が \#FF2F4F4F のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkTurquoise() {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```


ARGB 値が \#FF00CED1 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDarkViolet() {#getDarkViolet--}
```
public static Color getDarkViolet()
```


ARGB 値が \#FF9400D3 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDeepPink() {#getDeepPink--}
```
public static Color getDeepPink()
```


ARGB 値が \#FFFF1493 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDeepSkyBlue() {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```


ARGB 値が \#FF00BFFF のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDimGray() {#getDimGray--}
```
public static Color getDimGray()
```


ARGB 値が \#FF696969 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getDodgerBlue() {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```


ARGB 値が \#FF1E90FF のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getFirebrick() {#getFirebrick--}
```
public static Color getFirebrick()
```


ARGB 値が \#FFB22222 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getFloralWhite() {#getFloralWhite--}
```
public static Color getFloralWhite()
```


ARGB 値が \#FFFFFAF0 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getForestGreen() {#getForestGreen--}
```
public static Color getForestGreen()
```


ARGB 値が \#FF228B22 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getFuchsia() {#getFuchsia--}
```
public static Color getFuchsia()
```


ARGB 値が \#FFFF00FF のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGainsboro() {#getGainsboro--}
```
public static Color getGainsboro()
```


ARGB 値が \#FFDCDCDC のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGhostWhite() {#getGhostWhite--}
```
public static Color getGhostWhite()
```


ARGB 値が \#FFF8F8FF のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGold() {#getGold--}
```
public static Color getGold()
```


ARGB 値が \#FFFFD700 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGoldenrod() {#getGoldenrod--}
```
public static Color getGoldenrod()
```


ARGB 値が \#FFDAA520 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGray() {#getGray--}
```
public static Color getGray()
```


ARGB 値が \#FF808080 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) strcture representing a system-defined color. `1`
### getGreen() {#getGreen--}
```
public static Color getGreen()
```


ARGB 値が \#FF008000 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getGreenYellow() {#getGreenYellow--}
```
public static Color getGreenYellow()
```


ARGB 値が \#FFADFF2F のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getHoneydew() {#getHoneydew--}
```
public static Color getHoneydew()
```


ARGB 値が \#FFF0FFF0 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getHotPink() {#getHotPink--}
```
public static Color getHotPink()
```


ARGB 値が \#FFFF69B4 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getIndianRed() {#getIndianRed--}
```
public static Color getIndianRed()
```


ARGB 値が \#FFCD5C5C のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getIndigo() {#getIndigo--}
```
public static Color getIndigo()
```


ARGB 値が \#FF4B0082 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getIvory() {#getIvory--}
```
public static Color getIvory()
```


ARGB 値が \#FFFFFFF0 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getKhaki() {#getKhaki--}
```
public static Color getKhaki()
```


ARGB 値が \#FFF0E68C のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLavender() {#getLavender--}
```
public static Color getLavender()
```


ARGB 値が \#FFE6E6FA のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLavenderBlush() {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```


ARGB 値が \#FFFFF0F5 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLawnGreen() {#getLawnGreen--}
```
public static Color getLawnGreen()
```


ARGB 値が \#FF7CFC00 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLemonChiffon() {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```


ARGB 値が \#FFFFFACD のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightBlue() {#getLightBlue--}
```
public static Color getLightBlue()
```


ARGB 値が \#FFADD8E6 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightCoral() {#getLightCoral--}
```
public static Color getLightCoral()
```


ARGB 値が \#FFF08080 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightCyan() {#getLightCyan--}
```
public static Color getLightCyan()
```


ARGB 値が \#FFE0FFFF のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightGoldenrodYellow() {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```


ARGB 値が \#FFFAFAD2 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightGreen() {#getLightGreen--}
```
public static Color getLightGreen()
```


ARGB 値が \#FF90EE90 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightGray() {#getLightGray--}
```
public static Color getLightGray()
```


ARGB 値が \#FFD3D3D3 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightPink() {#getLightPink--}
```
public static Color getLightPink()
```


ARGB 値が \#FFFFB6C1 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSalmon() {#getLightSalmon--}
```
public static Color getLightSalmon()
```


ARGB 値が \#FFFFA07A のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSeaGreen() {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```


ARGB 値が \#FF20B2AA のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSkyBlue() {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```


ARGB 値が \#FF87CEFA のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSlateGray() {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```


ARGB 値が \#FF778899 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightSteelBlue() {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```


ARGB 値が \#FFB0C4DE のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLightYellow() {#getLightYellow--}
```
public static Color getLightYellow()
```


ARGB 値が \#FFFFFFE0 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLime() {#getLime--}
```
public static Color getLime()
```


ARGB 値が \#FF00FF00 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLimeGreen() {#getLimeGreen--}
```
public static Color getLimeGreen()
```


ARGB 値が \#FF32CD32 のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getLinen() {#getLinen--}
```
public static Color getLinen()
```


システム定義の色を取得します（ARGB 値は \#FFFAF0E6）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMagenta() {#getMagenta--}
```
public static Color getMagenta()
```


ARGB 値が \#FFFF00FF のシステム定義の色を取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMaroon() {#getMaroon--}
```
public static Color getMaroon()
```


システム定義の色を取得します（ARGB 値は \#FF800000）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumAquamarine() {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```


システム定義の色を取得します（ARGB 値は \#FF66CDAA）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumBlue() {#getMediumBlue--}
```
public static Color getMediumBlue()
```


システム定義の色を取得します（ARGB 値は \#FF0000CD）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumOrchid() {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```


システム定義の色を取得します（ARGB 値は \#FFBA55D3）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumPurple() {#getMediumPurple--}
```
public static Color getMediumPurple()
```


システム定義の色を取得します（ARGB 値は \#FF9370DB）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumSeaGreen() {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```


システム定義の色を取得します（ARGB 値は \#FF3CB371）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumSlateBlue() {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```


システム定義の色を取得します（ARGB 値は \#FF7B68EE）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumSpringGreen() {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```


システム定義の色を取得します（ARGB 値は \#FF00FA9A）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumTurquoise() {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```


システム定義の色を取得します（ARGB 値は \#FF48D1CC）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMediumVioletRed() {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```


システム定義の色を取得します（ARGB 値は \#FFC71585）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMidnightBlue() {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```


システム定義の色を取得します（ARGB 値は \#FF191970）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMintCream() {#getMintCream--}
```
public static Color getMintCream()
```


システム定義の色を取得します（ARGB 値は \#FFF5FFFA）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMistyRose() {#getMistyRose--}
```
public static Color getMistyRose()
```


システム定義の色を取得します（ARGB 値は \#FFFFE4E1）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getMoccasin() {#getMoccasin--}
```
public static Color getMoccasin()
```


システム定義の色を取得します（ARGB 値は \#FFFFE4B5）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getNavajoWhite() {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```


システム定義の色を取得します（ARGB 値は \#FFFFDEAD）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getNavy() {#getNavy--}
```
public static Color getNavy()
```


システム定義の色を取得します（ARGB 値は \#FF000080）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOldLace() {#getOldLace--}
```
public static Color getOldLace()
```


システム定義の色を取得します（ARGB 値は \#FFFDF5E6）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOlive() {#getOlive--}
```
public static Color getOlive()
```


システム定義の色を取得します（ARGB 値は \#FF808000）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOliveDrab() {#getOliveDrab--}
```
public static Color getOliveDrab()
```


システム定義の色を取得します（ARGB 値は \#FF6B8E23）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOrange() {#getOrange--}
```
public static Color getOrange()
```


システム定義の色を取得します（ARGB 値は \#FFFFA500）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOrangeRed() {#getOrangeRed--}
```
public static Color getOrangeRed()
```


システム定義の色を取得します（ARGB 値は \#FFFF4500）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getOrchid() {#getOrchid--}
```
public static Color getOrchid()
```


システム定義の色を取得します（ARGB 値は \#FFDA70D6）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPaleGoldenrod() {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```


システム定義の色を取得します（ARGB 値は \#FFEEE8AA）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPaleGreen() {#getPaleGreen--}
```
public static Color getPaleGreen()
```


システム定義の色を取得します（ARGB 値は \#FF98FB98）。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPaleTurquoise() {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```


システム定義の色を取得します。この色の ARGB 値は \#FFAFEEEE です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPaleVioletRed() {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```


システム定義の色を取得します。この色の ARGB 値は \#FFDB7093 です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPapayaWhip() {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```


システム定義の色を取得します。この色の ARGB 値は \#FFFFEFD5 です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPeachPuff() {#getPeachPuff--}
```
public static Color getPeachPuff()
```


システム定義の色を取得します。この色の ARGB 値は \#FFFFDAB9 です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPeru() {#getPeru--}
```
public static Color getPeru()
```


システム定義の色を取得します。この色の ARGB 値は \#FFCD853F です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPink() {#getPink--}
```
public static Color getPink()
```


システム定義の色を取得します。この色の ARGB 値は \#FFFFC0CB です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPlum() {#getPlum--}
```
public static Color getPlum()
```


システム定義の色を取得します。この色の ARGB 値は \#FFDDA0DD です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPowderBlue() {#getPowderBlue--}
```
public static Color getPowderBlue()
```


システム定義の色を取得します。この色の ARGB 値は \#FFB0E0E6 です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getPurple() {#getPurple--}
```
public static Color getPurple()
```


システム定義の色を取得します。この色の ARGB 値は \#FF800080 です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getRed() {#getRed--}
```
public static Color getRed()
```


システム定義の色を取得します。この色の ARGB 値は \#FFFF0000 です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getRosyBrown() {#getRosyBrown--}
```
public static Color getRosyBrown()
```


システム定義の色を取得します。この色の ARGB 値は \#FFBC8F8F です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getRoyalBlue() {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```


システム定義の色を取得します。この色の ARGB 値は \#FF4169E1 です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSaddleBrown() {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```


システム定義の色を取得します。この色の ARGB 値は \#FF8B4513 です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSalmon() {#getSalmon--}
```
public static Color getSalmon()
```


システム定義の色を取得します。この色の ARGB 値は \#FFFA8072 です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSandyBrown() {#getSandyBrown--}
```
public static Color getSandyBrown()
```


システム定義の色を取得します。この色の ARGB 値は \#FFF4A460 です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSeaGreen() {#getSeaGreen--}
```
public static Color getSeaGreen()
```


システム定義の色を取得します。この色の ARGB 値は \#FF2E8B57 です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSeaShell() {#getSeaShell--}
```
public static Color getSeaShell()
```


システム定義の色を取得します。この色の ARGB 値は \#FFFFF5EE です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSienna() {#getSienna--}
```
public static Color getSienna()
```


システム定義の色を取得します。この色の ARGB 値は \#FFA0522D です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSilver() {#getSilver--}
```
public static Color getSilver()
```


システム定義の色を取得します。この色の ARGB 値は \#FFC0C0C0 です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSkyBlue() {#getSkyBlue--}
```
public static Color getSkyBlue()
```


システム定義の色を取得します。この色の ARGB 値は \#FF87CEEB です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSlateBlue() {#getSlateBlue--}
```
public static Color getSlateBlue()
```


システム定義の色を取得します。この色の ARGB 値は \#FF6A5ACD です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSlateGray() {#getSlateGray--}
```
public static Color getSlateGray()
```


システム定義の色を取得します。この色の ARGB 値は \#FF708090 です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSnow() {#getSnow--}
```
public static Color getSnow()
```


システム定義の色を取得します。この色の ARGB 値は \#FFFFFAFA です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSpringGreen() {#getSpringGreen--}
```
public static Color getSpringGreen()
```


システム定義の色を取得します。この色の ARGB 値は \#FF00FF7F です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getSteelBlue() {#getSteelBlue--}
```
public static Color getSteelBlue()
```


システム定義の色を取得します。この色の ARGB 値は \#FF4682B4 です。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getTan() {#getTan--}
```
public static Color getTan()
```


ARGB 値が \#FFD2B48C のシステム定義カラーを取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getTeal() {#getTeal--}
```
public static Color getTeal()
```


ARGB 値が \#FF008080 のシステム定義カラーを取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getThistle() {#getThistle--}
```
public static Color getThistle()
```


ARGB 値が \#FFD8BFD8 のシステム定義カラーを取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getTomato() {#getTomato--}
```
public static Color getTomato()
```


ARGB 値が \#FFFF6347 のシステム定義カラーを取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getTurquoise() {#getTurquoise--}
```
public static Color getTurquoise()
```


ARGB 値が \#FF40E0D0 のシステム定義カラーを取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getViolet() {#getViolet--}
```
public static Color getViolet()
```


ARGB 値が \#FFEE82EE のシステム定義カラーを取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getWheat() {#getWheat--}
```
public static Color getWheat()
```


ARGB 値が \#FFF5DEB3 のシステム定義カラーを取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getWhite() {#getWhite--}
```
public static Color getWhite()
```


ARGB 値が \#FFFFFFFF のシステム定義カラーを取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getWhiteSmoke() {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```


ARGB 値が \#FFF5F5F5 のシステム定義カラーを取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getYellow() {#getYellow--}
```
public static Color getYellow()
```


ARGB 値が \#FFFFFF00 のシステム定義カラーを取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getYellowGreen() {#getYellowGreen--}
```
public static Color getYellowGreen()
```


ARGB 値が \#FF9ACD32 のシステム定義カラーを取得します。

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) representing a system-defined color. `1`
### getA() {#getA--}
```
public final int getA()
```


この [Color](../../com.aspose.drawing/color) 構造体のアルファ コンポーネント値を取得します。

**Returns:**
int - この [Color](../../com.aspose.drawing/color) のアルファ成分の値。
### getR() {#getR--}
```
public final int getR()
```


この [Color](../../com.aspose.drawing/color) 構造体の赤 コンポーネント値を取得します。

**Returns:**
int - この [Color](../../com.aspose.drawing/color) の赤成分の値。
### getG() {#getG--}
```
public final int getG()
```


この [Color](../../com.aspose.drawing/color) 構造体の緑 コンポーネント値を取得します。

**Returns:**
int - この [Color](../../com.aspose.drawing/color) の緑成分の値。
### getB() {#getB--}
```
public final int getB()
```


この [Color](../../com.aspose.drawing/color) 構造体の青 コンポーネント値を取得します。

**Returns:**
int - この [Color](../../com.aspose.drawing/color) の青成分の値。
### isKnownColor() {#isKnownColor--}
```
public final boolean isKnownColor()
```


この [Color](../../com.aspose.drawing/color) 構造体が既定の色かどうかを示す値を取得します。既定の色は [KnownColor](../../com.aspose.drawing/knowncolor) 列挙体の要素で表されます。

値: この [Color](../../com.aspose.drawing/color) が `M:Color.FromName(System.String)` メソッドまたは `M:Color.FromKnownColor(System.Drawing.KnownColor)` メソッドのいずれかを使用して既定の色から作成された場合は `true`、それ以外の場合は `false`。

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


この [Color](../../com.aspose.drawing/color) 構造体が初期化されていないかどうかを示す値を取得します。

値: このプロパティは、この色が未初期化の場合に true を返し、そうでない場合は false を返します。

**Returns:**
boolean
### isNamedColor() {#isNamedColor--}
```
public final boolean isNamedColor()
```


この [Color](../../com.aspose.drawing/color) 構造体が名前付きの色か、[KnownColor](../../com.aspose.drawing/knowncolor) 列挙体のメンバーかどうかを示す値を取得します。

値: この [Color](../../com.aspose.drawing/color) が `M:Color.FromName(System.String)` メソッドまたは `M:Color.FromKnownColor(System.Drawing.KnownColor)` メソッドのいずれかを使用して作成された場合は `true`、それ以外の場合は `false`。

**Returns:**
boolean
### isSystemColor() {#isSystemColor--}
```
public final boolean isSystemColor()
```


この [Color](../../com.aspose.drawing/color) 構造体がシステムカラーかどうかを示す値を取得します。システムカラーは Windows の表示要素で使用される色です。システムカラーは [KnownColor](../../com.aspose.drawing/knowncolor) 列挙体の要素で表されます。

値: この [Color](../../com.aspose.drawing/color) が `M:Color.FromName(System.String)` メソッドまたは `M:Color.FromKnownColor(System.Drawing.KnownColor)` メソッドのいずれかを使用してシステムカラーから作成された場合は `true`、それ以外の場合は `false`。

**Returns:**
boolean
### getName() {#getName--}
```
public final String getName()
```


この [Color](../../com.aspose.drawing/color) の名前を取得します。

**Returns:**
java.lang.String
### fromArgb(int argb) {#fromArgb-int-}
```
public static Color fromArgb(int argb)
```


32 ビット ARGB 値から [Color](../../com.aspose.drawing/color) 構造体を作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| argb | int | 32 ビット ARGB 値を指定する値。 |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that this method creates.
### fromArgb(int alpha, Color baseColor) {#fromArgb-int-com.aspose.drawing.Color-}
```
public static Color fromArgb(int alpha, Color baseColor)
```


指定された [Color](../../com.aspose.drawing/color) 構造体から新しいアルファ値を指定して [Color](../../com.aspose.drawing/color) 構造体を作成します。このメソッドはアルファ値に 32 ビットの値を渡すことを許可しますが、値は 8 ビットに制限されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| alpha | int | 新しい [Color](../../com.aspose.drawing/color) のアルファ値です。有効な値は 0 から 255 です。 |
| baseColor | [Color](../../com.aspose.drawing/color) | 新しい [Color](../../com.aspose.drawing/color) を作成する元となる [Color](../../com.aspose.drawing/color)です。 |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) that this method creates.
### fromArgb(int red, int green, int blue) {#fromArgb-int-int-int-}
```
public static Color fromArgb(int red, int green, int blue)
```


指定された 8 ビットのカラー値（赤、緑、青）から [Color](../../com.aspose.drawing/color) 構造体を作成します。アルファ値は暗黙的に 255（完全に不透明）です。このメソッドは各カラーコンポーネントに 32 ビットの値を渡すことを許可しますが、各コンポーネントの値は 8 ビットに制限されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| red | int | 新しい [Color](../../com.aspose.drawing/color) の赤コンポーネントの値です。有効な値は 0 から 255 です。 |
| green | int | 新しい [Color](../../com.aspose.drawing/color) の緑コンポーネントの値です。有効な値は 0 から 255 です。 |
| blue | int | 新しい [Color](../../com.aspose.drawing/color) の青コンポーネントの値です。有効な値は 0 から 255 です。 |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) that this method creates.
### fromArgb(int alpha, int red, int green, int blue) {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int alpha, int red, int green, int blue)
```


4 つの ARGB コンポーネント（アルファ、赤、緑、青）の値から Color 構造体を作成します。このメソッドは各コンポーネントに 32 ビットの値を渡すことを許可しますが、各コンポーネントの値は 8 ビットに制限されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| アルファ | int | アルファコンポーネントです。有効な値は 0 から 255 です。 |
| 赤 | int | 赤コンポーネントです。有効な値は 0 から 255 です。 |
| 緑 | int | 緑コンポーネントです。有効な値は 0 から 255 です。 |
| 青 | int | 青コンポーネントです。有効な値は 0 から 255 です。 |

**Returns:**
[Color](../../com.aspose.drawing/color) - The Color that this method creates.
### fromKnownColor(int color) {#fromKnownColor-int-}
```
public static Color fromKnownColor(int color)
```


指定された事前定義色から [Color](../../com.aspose.drawing/color) 構造体を作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| color | int | [KnownColor](../../com.aspose.drawing/knowncolor) 列挙体の要素です。 |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) that this method creates.
### fromName(String name) {#fromName-java.lang.String-}
```
public static Color fromName(String name)
```


指定された既定の色名から [Color](../../com.aspose.drawing/color) 構造体を作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 事前定義されたカラーの名前である文字列です。有効な名前は [KnownColor](../../com.aspose.drawing/knowncolor) 列挙体の要素名と同じです。 |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) that this method creates.
### op_Equality(Color left, Color right) {#op-Equality-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public static boolean op_Equality(Color left, Color right)
```


指定された 2 つの [Color](../../com.aspose.drawing/color) 構造体が等しいかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [Color](../../com.aspose.drawing/color) | 等価演算子の左側にある [Color](../../com.aspose.drawing/color) です。 |
| right | [Color](../../com.aspose.drawing/color) | 等価演算子の右側にある [Color](../../com.aspose.drawing/color) です。 |

**Returns:**
boolean - 2 つの [Color](../../com.aspose.drawing/color) 構造体が等しい場合は `true`、それ以外は `false`。
### op_Inequality(Color left, Color right) {#op-Inequality-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public static boolean op_Inequality(Color left, Color right)
```


指定された 2 つの [Color](../../com.aspose.drawing/color) 構造体が異なるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [Color](../../com.aspose.drawing/color) | 不等価演算子の左側にある [Color](../../com.aspose.drawing/color) です。 |
| right | [Color](../../com.aspose.drawing/color) | 不等価演算子の右側にある [Color](../../com.aspose.drawing/color) です。 |

**Returns:**
boolean - 2 つの [Color](../../com.aspose.drawing/color) 構造体が異なる場合は `true`、それ以外は `false`。
### equals(Color other) {#equals-com.aspose.drawing.Color-}
```
public final boolean equals(Color other)
```


指定された色がこの色と等しいかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | [Color](../../com.aspose.drawing/color) | テスト対象のカラーです。 |

**Returns:**
boolean - 指定されたカラーがこのカラーと等しい場合は ``,それ以外は ``。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定されたオブジェクトがこの色と等しいかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | テスト対象のオブジェクトです。 |

**Returns:**
boolean - 指定されたオブジェクトがこのカラーと等しい場合は ``,それ以外は ``。
### toArgb() {#toArgb--}
```
public final int toArgb()
```


この Color 構造体の 32 ビット ARGB 値を取得します。

**Returns:**
int - この Color の 32 ビット ARGB 値です。
### getBrightness() {#getBrightness--}
```
public final float getBrightness()
```


この [Color](../../com.aspose.drawing/color) 構造体の色相・彩度・明度 (HSB) の明度値を取得します。

**Returns:**
float - この [Color](../../com.aspose.drawing/color) の明度です。明度は 0.0 から 1.0 の範囲で、0.0 は黒、1.0 は白を表します。
### getHue() {#getHue--}
```
public final float getHue()
```


この [Color](../../com.aspose.drawing/color) 構造体の色相・彩度・明度 (HSB) の色相値（度単位）を取得します。

**Returns:**
float - この java.awt.Color の色相（度単位）です。色相は度で測定され、HSB カラースペースで 0.0 から 360.0 の範囲です。
### getSaturation() {#getSaturation--}
```
public final float getSaturation()
```


この [Color](../../com.aspose.drawing/color) 構造体の色相・彩度・明度 (HSB) の彩度値を取得します。

**Returns:**
float - この [Color](../../com.aspose.drawing/color) の彩度です。彩度は 0.0 から 1.0 の範囲で、0.0 はグレースケール、1.0 は最も彩度が高い状態を表します。
### toKnownColor() {#toKnownColor--}
```
public final int toKnownColor()
```


この [Color](../../com.aspose.drawing/color) 構造体の [KnownColor](../../com.aspose.drawing/knowncolor) 値を取得します。

**Returns:**
int - [KnownColor](../../com.aspose.drawing/knowncolor) 列挙体の要素です。ただし、[Color](../../com.aspose.drawing/color) が `M:Color.FromName(System.String)` メソッドまたは `M:Color.FromKnownColor(KnownColor)` メソッドのいずれかを使用して事前定義された色から作成された場合はその要素、そうでなければ 0 です。
### toString() {#toString--}
```
public String toString()
```


このインスタンスを表す文字列を返します。

**Returns:**
java.lang.String - このインスタンスを表す文字列です。
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - ハッシュテーブルなどのハッシュアルゴリズムやデータ構造で使用できる、このインスタンスのハッシュコード。
### isEquals(Color obj1, Color obj2) {#isEquals-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public static boolean isEquals(Color obj1, Color obj2)
```




**Parameters:**
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| that | [Color](../../com.aspose.drawing/color) |  |

### Clone() {#Clone--}
```
public Color Clone()
```




**Returns:**
[Color](../../com.aspose.drawing/color)
