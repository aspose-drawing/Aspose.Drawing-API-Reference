---
title: StringFormatFlags
second_title: Aspose.Drawing für Java API-Referenz
description: Gibt die Anzeige‑ und Layout‑Informationen für Textzeichenfolgen an.
type: docs
weight: 48
url: /de/java/com.aspose.drawing/stringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StringFormatFlags extends System.Enum
```

Gibt die Anzeige‑ und Layout‑Informationen für Textzeichenfolgen an.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [DirectionRightToLeft](#DirectionRightToLeft) | Text wird von rechts nach links angezeigt. |
| [DirectionVertical](#DirectionVertical) | Text ist vertikal ausgerichtet. |
| [FitBlackBox](#FitBlackBox) | Teile von Zeichen dürfen über das Layout‑Rechteck des Strings hinausragen. |
| [DisplayFormatControl](#DisplayFormatControl) | Steuerzeichen wie das Links‑nach‑Rechts‑Markierung werden in der Ausgabe mit einem repräsentativen Glyphen angezeigt. |
| [NoFontFallback](#NoFontFallback) | Das Ausweichen auf alternative Schriftarten für Zeichen, die in der angeforderten Schriftart nicht unterstützt werden, ist deaktiviert. |
| [MeasureTrailingSpaces](#MeasureTrailingSpaces) | Schließt das nachfolgende Leerzeichen am Ende jeder Zeile ein. |
| [NoWrap](#NoWrap) | Der Zeilenumbruch zwischen Zeilen beim Formatieren innerhalb eines Rechtecks ist deaktiviert. |
| [LineLimit](#LineLimit) | Nur ganze Zeilen werden im Formatierungsrechteck angeordnet. |
| [NoClip](#NoClip) | Überstehende Teile von Glyphen und nicht umgebrochener Text, der außerhalb des Formatierungsrechtecks reicht, dürfen angezeigt werden. |
| [ExactAlignment](#ExactAlignment) | Die exakte Ausrichtung, korrekte Polsterung GDI+ |
### DirectionRightToLeft {#DirectionRightToLeft}
```
public static final int DirectionRightToLeft
```


Text wird von rechts nach links angezeigt.

### DirectionVertical {#DirectionVertical}
```
public static final int DirectionVertical
```


Text ist vertikal ausgerichtet.

### FitBlackBox {#FitBlackBox}
```
public static final int FitBlackBox
```


Teile von Zeichen dürfen über das Layout‑Rechteck des Strings hinausragen. Standardmäßig werden Zeichen neu positioniert, um ein Überstehen zu vermeiden.

### DisplayFormatControl {#DisplayFormatControl}
```
public static final int DisplayFormatControl
```


Steuerzeichen wie das Links‑nach‑Rechts‑Markierung werden in der Ausgabe mit einem repräsentativen Glyphen angezeigt.

### NoFontFallback {#NoFontFallback}
```
public static final int NoFontFallback
```


Das Ausweichen auf alternative Schriftarten für Zeichen, die in der angeforderten Schriftart nicht unterstützt werden, ist deaktiviert. Fehlende Zeichen werden mit dem fehlenden Glyphen der Schriftart angezeigt, üblicherweise ein offenes Quadrat.

### MeasureTrailingSpaces {#MeasureTrailingSpaces}
```
public static final int MeasureTrailingSpaces
```


Schließt das nachfolgende Leerzeichen am Ende jeder Zeile ein. Standardmäßig schließt das von der MeasureString‑Methode zurückgegebene Begrenzungsrechteck das Leerzeichen am Ende jeder Zeile aus. Setzen Sie dieses Flag, um dieses Leerzeichen in die Messung einzubeziehen.

### NoWrap {#NoWrap}
```
public static final int NoWrap
```


Der Zeilenumbruch zwischen Zeilen beim Formatieren innerhalb eines Rechtecks ist deaktiviert. Dieses Flag wird impliziert, wenn anstelle eines Rechtecks ein Punkt übergeben wird oder wenn das angegebene Rechteck eine Zeilenlänge von Null hat.

### LineLimit {#LineLimit}
```
public static final int LineLimit
```


Nur ganze Zeilen werden im Formatierungsrechteck angeordnet. Standardmäßig wird das Layout bis zum Ende des Textes fortgesetzt oder bis keine weiteren Zeilen mehr sichtbar sind, weil sie abgeschnitten wurden, je nachdem, was zuerst eintritt. Beachten Sie, dass die Standardeinstellungen zulassen, dass die letzte Zeile teilweise von einem Formatierungsrechteck verdeckt wird, das kein ganzes Vielfaches der Zeilenhöhe ist. Um sicherzustellen, dass nur ganze Zeilen sichtbar sind, geben Sie diesen Wert an und achten Sie darauf, ein Formatierungsrechteck bereitzustellen, das mindestens so hoch ist wie die Höhe einer Zeile.

### NoClip {#NoClip}
```
public static final int NoClip
```


Überstehende Teile von Glyphen und nicht umbrochener Text, die außerhalb des Formatierungsrechtecks reichen, dürfen angezeigt werden. Standardmäßig werden alle Texte und Glyphen‑Teile, die außerhalb des Formatierungsrechtecks reichen, abgeschnitten.

### ExactAlignment {#ExactAlignment}
```
public static final int ExactAlignment
```


Die exakte Ausrichtung, korrekte Polsterung GDI+

