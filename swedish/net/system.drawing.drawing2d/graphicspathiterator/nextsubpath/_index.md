---
title: NextSubpath
second_title: Aspose.Drawing för .NET API Referens
description: FlyttarGraphicsPathIteratorsystem.drawing.drawing2d/graphicspathiterator till nästa delväg i banan. Startindexet och slutindexet för nästa delsökväg finns i outparametrarna.
type: docs
weight: 100
url: /sv/net/system.drawing.drawing2d/graphicspathiterator/nextsubpath/
---
## NextSubpath(out int, out int, out bool) {#nextsubpath}

Flyttar[`GraphicsPathIterator`](../../graphicspathiterator) till nästa delväg i banan. Startindexet och slutindexet för nästa delsökväg finns i [out]-parametrarna.

```csharp
public int NextSubpath(out int startIndex, out int endIndex, out bool isClosed)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | Int32& | [ut] Tar emot startindexet för nästa undersökväg. |
| endIndex | Int32& | [out] Tar emot slutindexet för nästa undersökväg. |
| isClosed | Boolean& | [ut] Indikerar om undersökvägen är stängd. |

### Returvärde

Antalet datapunkter i den hämtade figuren (delväg). Om det inte finns fler siffror att hämta, returneras noll.

### Se även

* class [GraphicsPathIterator](../../graphicspathiterator)
* namnutrymme [System.Drawing.Drawing2D](../../graphicspathiterator)
* hopsättning [Aspose.Drawing](../../../)

---

## NextSubpath(GraphicsPath, out bool) {#nextsubpath_1}

Får nästa siffra (undersökväg) från den associerade sökvägen till denna[`GraphicsPathIterator`](../../graphicspathiterator) .

```csharp
public int NextSubpath(GraphicsPath path, out bool isClosed)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | GraphicsPath | A[`GraphicsPath`](../../graphicspath) det vill säga att ha sina datapunkter inställda för att matcha datapunkterna för den hämtade figuren (undersökvägen) för denna iterator. |
| isClosed | Boolean& | [ut] Indikerar om den aktuella undersökvägen är stängd. Det är sant om om siffran är stängd, annars är den falsk. |

### Returvärde

Antalet datapunkter i den hämtade figuren (delväg). Om det inte finns fler siffror att hämta, returneras noll.

### Se även

* class [GraphicsPath](../../graphicspath)
* class [GraphicsPathIterator](../../graphicspathiterator)
* namnutrymme [System.Drawing.Drawing2D](../../graphicspathiterator)
* hopsättning [Aspose.Drawing](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
