---
title: Graphics.EnumerateMetafileProc
second_title: Aspose.Drawing för .NET API Referens
description: Tillhandahåller en återuppringningsmetod förEnumerateMetafile./graphics/enumeratemetafile metod.
type: docs
weight: 550
url: /sv/net/system.drawing/graphics.enumeratemetafileproc/
---
## Graphics.EnumerateMetafileProc delegate

Tillhandahåller en återuppringningsmetod för[`EnumerateMetafile`](../graphics/enumeratemetafile) metod.

```csharp
public delegate bool EnumerateMetafileProc(EmfPlusRecordType recordType, int flags, int dataSize, 
    IntPtr data, PlayRecordCallback callbackData);
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| recordType | EmfPlusRecordType | Medlem av[`EmfPlusRecordType`](../../system.drawing.imaging/emfplusrecordtype) uppräkning som anger typen av metafilpost. |
| flags | Int32 | Uppsättning flaggor som anger attribut för posten. |
| dataSize | Int32 | Antal byte i postdata. |
| data | IntPtr | Pekare till en buffert som innehåller postdata. |
| callbackData | PlayRecordCallback | Argumentet används inte. |

### Returvärde

Returnera sant om du vill fortsätta att räkna upp poster; annars falskt.

### Se även

* enum [EmfPlusRecordType](../../system.drawing.imaging/emfplusrecordtype)
* delegate [PlayRecordCallback](../../system.drawing.imaging/playrecordcallback)
* class [Graphics](../graphics)
* namnutrymme [System.Drawing](../../system.drawing)
* hopsättning [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
