---
title: Graphics.EnumerateMetafileProc
second_title: Aspose.Drawing per .NET API Reference
description: Fornisce un metodo di callback per ilEnumerateMetafile./graphics/enumeratemetafile metodo.
type: docs
weight: 550
url: /it/net/system.drawing/graphics.enumeratemetafileproc/
---
## Graphics.EnumerateMetafileProc delegate

Fornisce un metodo di callback per il[`EnumerateMetafile`](../graphics/enumeratemetafile) metodo.

```csharp
public delegate bool EnumerateMetafileProc(EmfPlusRecordType recordType, int flags, int dataSize, 
    IntPtr data, PlayRecordCallback callbackData);
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| recordType | EmfPlusRecordType | Membro del[`EmfPlusRecordType`](../../system.drawing.imaging/emfplusrecordtype) enumerazione che specifica il tipo di record di metafile. |
| flags | Int32 | Insieme di flag che specificano gli attributi del record. |
| dataSize | Int32 | Numero di byte nei dati del record. |
| data | IntPtr | Puntatore a un buffer che contiene i dati del record. |
| callbackData | PlayRecordCallback | L'argomento non viene utilizzato. |

### Valore di ritorno

Restituisce true se si desidera continuare a enumerare i record; altrimenti falso.

### Guarda anche

* enum [EmfPlusRecordType](../../system.drawing.imaging/emfplusrecordtype)
* delegate [PlayRecordCallback](../../system.drawing.imaging/playrecordcallback)
* class [Graphics](../graphics)
* spazio dei nomi [System.Drawing](../../system.drawing)
* assemblea [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
