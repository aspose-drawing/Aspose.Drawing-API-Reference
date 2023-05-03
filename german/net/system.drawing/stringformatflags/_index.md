---
title: StringFormatFlags
second_title: Aspose.Drawing für .NET-API-Referenz
description: Gibt die Anzeige und Layoutinformationen für Textzeichenfolgen an.
type: docs
weight: 1140
url: /de/net/system.drawing/stringformatflags/
---
## StringFormatFlags enumeration

Gibt die Anzeige- und Layoutinformationen für Textzeichenfolgen an.

```csharp
[Flags]
public enum StringFormatFlags
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| DirectionRightToLeft | `1` | Text wird von rechts nach links angezeigt. |
| DirectionVertical | `2` | Text ist vertikal ausgerichtet. |
| FitBlackBox | `4` | Teile von Zeichen dürfen über das Layoutrechteck der Zeichenfolge hinausragen. Standardmäßig werden Zeichen neu positioniert, um Überhänge zu vermeiden. |
| DisplayFormatControl | `20` | Steuerzeichen wie die Links-nach-rechts-Markierung werden in der Ausgabe mit einer repräsentativen Glyphe angezeigt. |
| NoFontFallback | `400` | Der Fallback auf alternative Schriftarten für Zeichen, die in der angeforderten Schriftart nicht unterstützt werden, ist deaktiviert. Alle fehlenden Zeichen werden mit der fehlenden Glyphe der Schriftart angezeigt, normalerweise ein offenes Quadrat. |
| MeasureTrailingSpaces | `800` | Schließt das nachfolgende Leerzeichen am Ende jeder Zeile ein. Standardmäßig schließt das von der MeasureString-Methode zurückgegebene Begrenzungsrechteck das Leerzeichen am Ende jeder Zeile aus. Setzen Sie dieses Flag, um dieses Leerzeichen in die Messung aufzunehmen. |
| NoWrap | `1000` | Textumbruch zwischen Zeilen, wenn die Formatierung innerhalb eines Rechtecks deaktiviert ist. Dieses Flag wird impliziert, wenn anstelle eines Rechtecks ein Punkt übergeben wird, oder wenn das angegebene Rechteck eine Zeilenlänge von null hat. |
| LineLimit | `2000` | Nur ganze Zeilen werden im Formatierungsrechteck angeordnet. Standardmäßig wird das Layout bis zum Ende des Textes fortgesetzt, oder bis keine Zeilen mehr sichtbar sind, je nachdem, was zuerst eintritt. Beachten Sie, dass die Standardeinstellungen dies zulassen letzte Zeile, die teilweise durch ein Formatierungsrechteck verdeckt wird, das kein ganzzahliges Vielfaches der Zeilenhöhe ist. Um sicherzustellen, dass nur ganze Zeilen zu sehen sind, geben Sie diesen Wert an und achten Sie darauf, ein Formatierungsrechteck bereitzustellen, das mindestens so hoch ist wie die Höhe einer Zeile. |
| NoClip | `4000` | Überhängende Teile von Glyphen und nicht umbrochener Text, der über das Formatierungsrechteck hinausreicht, dürfen angezeigt werden. Standardmäßig werden alle Text- und Glyphenteile, die über das Formatierungsrechteck hinausreichen, abgeschnitten. |

### Siehe auch

* namensraum [System.Drawing](../../system.drawing)
* Montage [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->