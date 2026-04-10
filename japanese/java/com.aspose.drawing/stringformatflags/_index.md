---
title: StringFormatFlags
second_title: Aspose.Drawing for Java API リファレンス
description: テキスト文字列の表示およびレイアウト情報を指定します。
type: docs
weight: 48
url: /ja/java/com.aspose.drawing/stringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StringFormatFlags extends System.Enum
```

テキスト文字列の表示およびレイアウト情報を指定します。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [DirectionRightToLeft](#DirectionRightToLeft) | Text is displayed from right to left. |
| [DirectionVertical](#DirectionVertical) | Text is vertically aligned. |
| [FitBlackBox](#FitBlackBox) | Parts of characters are allowed to overhang the string's layout rectangle. |
| [DisplayFormatControl](#DisplayFormatControl) | Control characters such as the left-to-right mark are shown in the output with a representative glyph. |
| [NoFontFallback](#NoFontFallback) | Fallback to alternate fonts for characters not supported in the requested font is disabled. |
| [MeasureTrailingSpaces](#MeasureTrailingSpaces) | Includes the trailing space at the end of each line. |
| [NoWrap](#NoWrap) | Text wrapping between lines when formatting within a rectangle is disabled. |
| [LineLimit](#LineLimit) | Only entire lines are laid out in the formatting rectangle. |
| [NoClip](#NoClip) | Overhanging parts of glyphs, and unwrapped text reaching outside the formatting rectangle are allowed to show. |
| [ExactAlignment](#ExactAlignment) | The exact alignment, correct padding GDI+ |
### DirectionRightToLeft {#DirectionRightToLeft}
```
public static final int DirectionRightToLeft
```


Text is displayed from right to left.

### DirectionVertical {#DirectionVertical}
```
public static final int DirectionVertical
```


Text is vertically aligned.

### FitBlackBox {#FitBlackBox}
```
public static final int FitBlackBox
```


Parts of characters are allowed to overhang the string's layout rectangle. By default, characters are repositioned to avoid any overhang.

### DisplayFormatControl {#DisplayFormatControl}
```
public static final int DisplayFormatControl
```


Control characters such as the left-to-right mark are shown in the output with a representative glyph.

### NoFontFallback {#NoFontFallback}
```
public static final int NoFontFallback
```


Fallback to alternate fonts for characters not supported in the requested font is disabled. Any missing characters are displayed with the fonts missing glyph, usually an open square.

### MeasureTrailingSpaces {#MeasureTrailingSpaces}
```
public static final int MeasureTrailingSpaces
```


Includes the trailing space at the end of each line. By default the boundary rectangle returned by the MeasureString method excludes the space at the end of each line. Set this flag to include that space in measurement.

### NoWrap {#NoWrap}
```
public static final int NoWrap
```


Text wrapping between lines when formatting within a rectangle is disabled. This flag is implied when a point is passed instead of a rectangle, or when the specified rectangle has a zero line length.

### LineLimit {#LineLimit}
```
public static final int LineLimit
```


フォーマット矩形には全行のみが配置されます。デフォルトでは、レイアウトはテキストの末尾まで、またはクリッピングの結果としてこれ以上行が表示されなくなるまで続きます（どちらが先に起こっても）。デフォルト設定では、行の高さの整数倍でないフォーマット矩形により、最後の行が部分的に隠れることがあります。全行が確実に表示されるようにするには、この値を指定し、少なくとも1行分の高さのフォーマット矩形を提供してください。

### NoClip {#NoClip}
```
public static final int NoClip
```


グリフのはみ出し部分や、フォーマット矩形の外に達する折り返しなしテキストは表示が許可されます。デフォルトでは、フォーマット矩形の外に出たすべてのテキストとグリフの部分はクリップされます。

### ExactAlignment {#ExactAlignment}
```
public static final int ExactAlignment
```


The exact alignment, correct padding GDI+

