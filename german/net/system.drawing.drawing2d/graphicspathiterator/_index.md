---
title: GraphicsPathIterator
second_title: Aspose.Drawing für .NET-API-Referenz
description: Bietet die Möglichkeit Unterpfade in a zu durchlaufenGraphicsPath und testen Sie die Formentypen die in jedem Unterpfad enthalten sind. Diese Klasse kann nicht vererbt werden.
type: docs
weight: 270
url: /de/net/system.drawing.drawing2d/graphicspathiterator/
---
## GraphicsPathIterator class

Bietet die Möglichkeit, Unterpfade in a zu durchlaufenGraphicsPath und testen Sie die Formentypen, die in jedem Unterpfad enthalten sind. Diese Klasse kann nicht vererbt werden.

```csharp
public sealed class GraphicsPathIterator : IDisposable
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [GraphicsPathIterator](graphicspathiterator)(GraphicsPath) | Initialisiert eine neue Instanz von[`GraphicsPathIterator`](../graphicspathiterator) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../system.drawing.drawing2d/graphicspathiterator/count) { get; } | Ruft die Anzahl der Punkte im Pfad ab. |
| [SubpathCount](../../system.drawing.drawing2d/graphicspathiterator/subpathcount) { get; } | Ruft die Anzahl der Unterpfade im Pfad ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CopyData](../../system.drawing.drawing2d/graphicspathiterator/copydata)(ref PointF[], ref byte[], int, int) | Kopiert die GraphicsPath.PathPoints-Eigenschaft und die GraphicsPath.PathTypes-Eigenschaft arrays der zugehörigen[`GraphicsPath`](../graphicspath) in die beiden angegebenen Arrays. |
| [Dispose](../../system.drawing.drawing2d/graphicspathiterator/dispose)() | Führt anwendungsdefinierte Aufgaben aus, die mit dem Freigeben, Freigeben oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| [Enumerate](../../system.drawing.drawing2d/graphicspathiterator/enumerate)(ref PointF[], ref byte[]) | Kopiert die GraphicsPath.PathPoints-Eigenschaft und die GraphicsPath.PathTypes-Eigenschaft arrays der zugehörigen[`GraphicsPath`](../graphicspath) in die beiden angegebenen Arrays. |
| [HasCurve](../../system.drawing.drawing2d/graphicspathiterator/hascurve)() | Gibt an, ob der Pfad damit verbunden ist[`GraphicsPathIterator`](../graphicspathiterator) enthält eine Kurve. |
| [NextMarker](../../system.drawing.drawing2d/graphicspathiterator/nextmarker#nextmarker_1)(GraphicsPath) | Dies[`GraphicsPathIterator`](../graphicspathiterator) Objekt hat a[`GraphicsPath`](../graphicspath) ihm zugeordnetes Objekt. Diese Methode inkrementiert das zugeordnete[`GraphicsPath`](../graphicspath) zur nächsten Markierung in seinem Pfad und kopiert alle Punkte, die zwischen der aktuellen Markierung und der nächsten Markierung (oder dem Ende des Pfads) enthalten sind, auf eine Sekunde[`GraphicsPath`](../graphicspath) Objekt, das an den Parameter übergeben wird. |
| [NextMarker](../../system.drawing.drawing2d/graphicspathiterator/nextmarker#nextmarker)(out int, out int) | Erhöht die[`GraphicsPathIterator`](../graphicspathiterator)zum nächsten Marker im Pfad und gibt die Start- und Stopp-Indizes über die [out]-Parameter zurück. |
| [NextPathType](../../system.drawing.drawing2d/graphicspathiterator/nextpathtype)(out byte, out int, out int) | Ruft den Startindex und den Endindex der nächsten Gruppe von Datenpunkten ab, die alle denselben Typ haben. |
| [NextSubpath](../../system.drawing.drawing2d/graphicspathiterator/nextsubpath#nextsubpath_1)(GraphicsPath, out bool) | Holt die nächste Ziffer (Unterpfad) aus dem zugehörigen Pfad von this[`GraphicsPathIterator`](../graphicspathiterator) . |
| [NextSubpath](../../system.drawing.drawing2d/graphicspathiterator/nextsubpath#nextsubpath)(out int, out int, out bool) | Verschiebt die[`GraphicsPathIterator`](../graphicspathiterator) zum nächsten Unterpfad im Pfad. Der Startindex und der Endindex des nächsten Teilpfads sind in den [out]-Parametern enthalten. |
| [Rewind](../../system.drawing.drawing2d/graphicspathiterator/rewind)() | Spult das zurück[`GraphicsPathIterator`](../graphicspathiterator) bis zum Anfang des zugehörigen Pfads. |

### Siehe auch

* namensraum [System.Drawing.Drawing2D](../../system.drawing.drawing2d)
* Montage [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
