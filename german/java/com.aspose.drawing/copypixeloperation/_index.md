---
title: CopyPixelOperation
second_title: Aspose.Drawing für Java API-Referenz
description: Bestimmt, wie die Quellfarbe bei einer Kopier-Pixel-Operation mit der Ziel­farbe kombiniert wird, um eine Endfarbe zu ergeben.
type: docs
weight: 18
url: /de/java/com.aspose.drawing/copypixeloperation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CopyPixelOperation extends System.Enum
```

Bestimmt, wie die Quellfarbe bei einer Kopier-Pixel-Operation mit der Ziel­farbe kombiniert wird, um eine Endfarbe zu ergeben.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [NoMirrorBitmap](#NoMirrorBitmap) | Das Bitmap ist nicht gespiegelt. |
| [Blackness](#Blackness) | Der Zielbereich wird mit der Farbe gefüllt, die dem Index 0 in der physischen Palette zugeordnet ist. |
| [NotSourceErase](#NotSourceErase) | Die Quell- und Zielfarben werden mit dem booleschen `OR`-Operator kombiniert und anschließend wird die resultierende Farbe invertiert. |
| [NotSourceCopy](#NotSourceCopy) | Der invertierte Quellbereich wird zum Ziel kopiert. |
| [SourceErase](#SourceErase) | Die invertierten Farben des Zielbereichs werden mit den Farben des Quellbereichs mittels des booleschen `AND`-Operators kombiniert. |
| [DestinationInvert](#DestinationInvert) | Der Zielbereich wird invertiert. |
| [PatInvert](#PatInvert) | Die Farben des aktuell im Ziel‑Geräte‑Kontext ausgewählten Pinsels werden mit den Farben des Ziels mittels des booleschen `XOR`-Operators kombiniert. |
| [SourceInvert](#SourceInvert) | Die Farben der Quell‑ und Zielbereiche werden mit dem booleschen `XOR`-Operator kombiniert. |
| [SourceAnd](#SourceAnd) | Die Farben der Quell‑ und Zielbereiche werden mit dem booleschen `AND`-Operator kombiniert. |
| [MergePaint](#MergePaint) | Die Farben des invertierten Quellbereichs werden mit den Farben des Zielbereichs mittels des booleschen `OR`-Operators zusammengeführt. |
| [MergeCopy](#MergeCopy) | Die Farben des Quellbereichs werden mit den Farben des im Ziel‑Geräte‑Kontext ausgewählten Pinsels mittels des booleschen `AND`-Operators zusammengeführt. |
| [SourceCopy](#SourceCopy) | Der Quellbereich wird direkt in den Zielbereich kopiert. |
| [SourcePaint](#SourcePaint) | Die Farben der Quell‑ und Zielbereiche werden mit dem booleschen `OR`-Operator kombiniert. |
| [PatCopy](#PatCopy) | Der im Ziel‑Geräte‑Kontext aktuell ausgewählte Pinsel wird in das Ziel‑Bitmap kopiert. |
| [PatPaint](#PatPaint) | Die Farben des im Ziel‑Geräte‑Kontext aktuell ausgewählten Pinsels werden mit den Farben des invertierten Quellbereichs mittels des booleschen `OR`-Operators kombiniert. |
| [Whiteness](#Whiteness) | Der Zielbereich wird mit der Farbe gefüllt, die dem Index 1 in der physischen Palette zugeordnet ist. |
| [CaptureBlt](#CaptureBlt) | Fenster, die über Ihrem Fenster geschichtet sind, werden in das resultierende Bild einbezogen. |
### NoMirrorBitmap {#NoMirrorBitmap}
```
public static final int NoMirrorBitmap
```


Das Bitmap ist nicht gespiegelt.

### Blackness {#Blackness}
```
public static final int Blackness
```


Der Zielbereich wird mit der Farbe gefüllt, die dem Index 0 in der physischen Palette zugeordnet ist. (Diese Farbe ist Schwarz für die Standard‑physische Palette.)

### NotSourceErase {#NotSourceErase}
```
public static final int NotSourceErase
```


Die Quell- und Zielfarben werden mit dem booleschen `OR`-Operator kombiniert und anschließend wird die resultierende Farbe invertiert.

### NotSourceCopy {#NotSourceCopy}
```
public static final int NotSourceCopy
```


Der invertierte Quellbereich wird zum Ziel kopiert.

### SourceErase {#SourceErase}
```
public static final int SourceErase
```


Die invertierten Farben des Zielbereichs werden mit den Farben des Quellbereichs mittels des booleschen `AND`-Operators kombiniert.

### DestinationInvert {#DestinationInvert}
```
public static final int DestinationInvert
```


Der Zielbereich wird invertiert.

### PatInvert {#PatInvert}
```
public static final int PatInvert
```


Die Farben des aktuell im Ziel‑Geräte‑Kontext ausgewählten Pinsels werden mit den Farben des Ziels mittels des booleschen `XOR`-Operators kombiniert.

### SourceInvert {#SourceInvert}
```
public static final int SourceInvert
```


Die Farben der Quell‑ und Zielbereiche werden mit dem booleschen `XOR`-Operator kombiniert.

### SourceAnd {#SourceAnd}
```
public static final int SourceAnd
```


Die Farben der Quell‑ und Zielbereiche werden mit dem booleschen `AND`-Operator kombiniert.

### MergePaint {#MergePaint}
```
public static final int MergePaint
```


Die Farben des invertierten Quellbereichs werden mit den Farben des Zielbereichs mittels des booleschen `OR`-Operators zusammengeführt.

### MergeCopy {#MergeCopy}
```
public static final int MergeCopy
```


Die Farben des Quellbereichs werden mit den Farben des im Ziel‑Geräte‑Kontext ausgewählten Pinsels mittels des booleschen `AND`-Operators zusammengeführt.

### SourceCopy {#SourceCopy}
```
public static final int SourceCopy
```


Der Quellbereich wird direkt in den Zielbereich kopiert.

### SourcePaint {#SourcePaint}
```
public static final int SourcePaint
```


Die Farben der Quell‑ und Zielbereiche werden mit dem booleschen `OR`-Operator kombiniert.

### PatCopy {#PatCopy}
```
public static final int PatCopy
```


Der im Ziel‑Geräte‑Kontext aktuell ausgewählte Pinsel wird in das Ziel‑Bitmap kopiert.

### PatPaint {#PatPaint}
```
public static final int PatPaint
```


Die Farben des aktuell im Zielgerätkontext ausgewählten Pinsels werden mit den Farben des invertierten Quellbereichs mittels des booleschen `OR`‑Operators kombiniert. Das Ergebnis dieser Operation wird mit den Farben des Zielbereichs mittels des booleschen `OR`‑Operators kombiniert.

### Whiteness {#Whiteness}
```
public static final int Whiteness
```


Der Zielbereich wird mit der Farbe gefüllt, die dem Index 1 in der physischen Palette zugeordnet ist. (Diese Farbe ist für die Standard‑physische Palette weiß.)

### CaptureBlt {#CaptureBlt}
```
public static final int CaptureBlt
```


Fenster, die über Ihrem Fenster geschichtet sind, werden in das resultierende Bild einbezogen. Standardmäßig enthält das Bild nur Ihr Fenster. Beachten Sie, dass dies im Allgemeinen nicht für das Drucken von Gerätekontexten verwendet werden kann.

