---
title: EmfType
second_title: Riferimento API di Aspose.Drawing per Java
description: Specifica la natura dei record inseriti in un file Enhanced Metafile EMF.
type: docs
weight: 18
url: /it/java/com.aspose.drawing.imaging/emftype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfType extends System.Enum
```

Specifica la natura dei record inseriti in un file Enhanced Metafile (EMF). Questa enumerazione è usata da diversi costruttori nella classe [Metafile](../../com.aspose.drawing.imaging/metafile).
## Campi

| Campo | Descrizione |
| --- | --- |
| [EmfOnly](#EmfOnly) | Specifica che tutti i record nel metafile sono record EMF, che possono essere visualizzati da GDI o GDI+. |
| [EmfPlusOnly](#EmfPlusOnly) | Specifica che tutti i record nel metafile sono record EMF+, che possono essere visualizzati da GDI+ ma non da GDI. |
| [EmfPlusDual](#EmfPlusDual) | Specifica che tutti i record EMF+ nel metafile sono associati a un record EMF alternativo. |
### EmfOnly {#EmfOnly}
```
public static final int EmfOnly
```


Specifica che tutti i record nel metafile sono record EMF, che possono essere visualizzati da GDI o GDI+.

### EmfPlusOnly {#EmfPlusOnly}
```
public static final int EmfPlusOnly
```


Specifica che tutti i record nel metafile sono record EMF+, che possono essere visualizzati da GDI+ ma non da GDI.

### EmfPlusDual {#EmfPlusDual}
```
public static final int EmfPlusDual
```


Specifica che tutti i record EMF+ nel metafile sono associati a un record EMF alternativo. I metafile di tipo `EmfType.EmfPlusDual` possono essere visualizzati da GDI o da GDI+.

