---
title: HatchBrush
second_title: Aspose.Drawing für Java API-Referenz
description: Definiert einen rechteckigen Pinsel mit einem Schraffurstil, einer Vordergrundfarbe und einer Hintergrundfarbe.
type: docs
weight: 26
url: /de/java/com.aspose.drawing.drawing2d/hatchbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class HatchBrush extends Brush
```

Definiert einen rechteckigen Pinsel mit einem Schraffurstil, einer Vordergrundfarbe und einer Hintergrundfarbe. Diese Klasse kann nicht abgeleitet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [HatchBrush(int hatchstyle, Color foreColor)](#HatchBrush-int-com.aspose.drawing.Color-) | Initialisiert eine neue Instanz der [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush)-Klasse mit der angegebenen `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle))-Aufzählung und Vordergrundfarbe. |
| [HatchBrush(int hatchstyle, Color foreColor, Color backColor)](#HatchBrush-int-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Initialisiert eine neue Instanz der [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush)-Klasse mit der angegebenen `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle))-Aufzählung, Vordergrundfarbe und Hintergrundfarbe. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHatchStyle()](#getHatchStyle--) | Gibt den Schraffurstil dieses [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush)-Objekts zurück. |
| [getForegroundColor()](#getForegroundColor--) | Gibt die Farbe der von diesem [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) gezeichneten Schraffurlinien zurück. |
| [getBackgroundColor()](#getBackgroundColor--) | Gibt die Farbe der Zwischenräume zwischen den von diesem [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) gezeichneten Schraffurlinien zurück. |
| [deepClone()](#deepClone--) | Erstellt eine exakte Kopie dieses [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush)-Objekts. |
### HatchBrush(int hatchstyle, Color foreColor) {#HatchBrush-int-com.aspose.drawing.Color-}
```
public HatchBrush(int hatchstyle, Color foreColor)
```


Initialisiert eine neue Instanz der [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush)-Klasse mit der angegebenen `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle))-Aufzählung und Vordergrundfarbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hatchstyle | int | Einer der `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle))-Werte, der das von diesem [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) gezeichnete Muster darstellt. |
| foreColor | [Color](../../com.aspose.drawing/color) | Die [Color](../../com.aspose.drawing/color)-Struktur, die die Farbe der von diesem [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) gezeichneten Linien darstellt. |

### HatchBrush(int hatchstyle, Color foreColor, Color backColor) {#HatchBrush-int-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public HatchBrush(int hatchstyle, Color foreColor, Color backColor)
```


Initialisiert eine neue Instanz der [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush)-Klasse mit der angegebenen `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle))-Aufzählung, Vordergrundfarbe und Hintergrundfarbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hatchstyle | int | Einer der `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle))-Werte, der das von diesem [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) gezeichnete Muster darstellt. |
| foreColor | [Color](../../com.aspose.drawing/color) | Die [Color](../../com.aspose.drawing/color)-Struktur, die die Farbe der von diesem [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) gezeichneten Linien darstellt. |
| backColor | [Color](../../com.aspose.drawing/color) | Die [Color](../../com.aspose.drawing/color)-Struktur, die die Farbe der Zwischenräume zwischen den von diesem [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) gezeichneten Linien darstellt. |

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Gibt den Schraffurstil dieses [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush)-Objekts zurück.

**Returns:**
int – der Schraffurstil dieses [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush)-Objekts.
### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Gibt die Farbe der von diesem [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) gezeichneten Schraffurlinien zurück.

**Returns:**
[Color](../../com.aspose.drawing/color) - the color of hatch lines drawn by this [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gibt die Farbe der Zwischenräume zwischen den von diesem [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) gezeichneten Schraffurlinien zurück.

**Returns:**
[Color](../../com.aspose.drawing/color) - the color of spaces between the hatch lines drawn by this [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Erstellt eine exakte Kopie dieses [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush)-Objekts.

**Returns:**
java.lang.Object – Der [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush), den diese Methode erstellt, als Objekt umgewandelt.
