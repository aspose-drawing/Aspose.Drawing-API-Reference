---
title: StringFormatFlags
second_title: Αναφορά API του Aspose.Drawing for Java
description: Specifies the display and layout information for text strings.
type: docs
weight: 48
url: /el/java/com.aspose.drawing/stringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StringFormatFlags extends System.Enum
```

Specifies the display and layout information for text strings.
## Fields

| Field | Περιγραφή |
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


Μόνο ολόκληρες γραμμές τοποθετούνται στο ορθογώνιο μορφοποίησης. Από προεπιλογή η διάταξη συνεχίζεται μέχρι το τέλος του κειμένου ή μέχρι να μην είναι ορατές άλλες γραμμές ως αποτέλεσμα του περικοπής, ό,τι συμβεί πρώτο. Σημειώστε ότι οι προεπιλεγμένες ρυθμίσεις επιτρέπουν στην τελευταία γραμμή να καλύπτεται μερικώς από ένα ορθογώνιο μορφοποίησης που δεν είναι πολλαπλάσιο του ύψους της γραμμής. Για να διασφαλίσετε ότι εμφανίζονται μόνο ολόκληρες γραμμές, καθορίστε αυτήν την τιμή και προσέξτε να παρέχετε ένα ορθογώνιο μορφοποίησης τουλάχιστον τόσο ψηλό όσο το ύψος μιας γραμμής.

### NoClip {#NoClip}
```
public static final int NoClip
```


Τα προεξέχοντα τμήματα των γλύφων και το μη αναδιπλωμένο κείμενο που εκτείνεται έξω από το ορθογώνιο μορφοποίησης επιτρέπεται να εμφανίζονται. Από προεπιλογή όλα τα κείμενα και τα τμήματα γλύφων που εκτείνονται έξω από το ορθογώνιο μορφοποίησης περικόπτονται.

### ExactAlignment {#ExactAlignment}
```
public static final int ExactAlignment
```


The exact alignment, correct padding GDI+

