---
title: MetafileType
second_title: Riferimento API di Aspose.Drawing per Java
description: Specifica i tipi di metafile.
type: docs
weight: 33
url: /it/java/com.aspose.drawing.imaging/metafiletype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MetafileType extends System.Enum
```

Specifica i tipi di metafile.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Invalid](#Invalid) | Specifica un formato metafile non riconosciuto in GDI+. |
| [Wmf](#Wmf) | Specifica un file WMF (Windows Metafile). |
| [WmfPlaceable](#WmfPlaceable) | Specifica un file WMF (Windows Metafile) che presenta un'intestazione metafile posizionabile all'inizio. |
| [Emf](#Emf) | Specifica un file Enhanced Metafile (EMF). |
| [EmfPlusOnly](#EmfPlusOnly) | Specifica un file EMF+. |
| [EmfPlusDual](#EmfPlusDual) | Specifica un file EMF+ Dual. |
### Invalid {#Invalid}
```
public static final int Invalid
```


Specifica un formato metafile non riconosciuto in GDI+.

### Wmf {#Wmf}
```
public static final int Wmf
```


Specifica un file WMF (Windows Metafile). Un file di questo tipo contiene solo record GDI.

### WmfPlaceable {#WmfPlaceable}
```
public static final int WmfPlaceable
```


Specifica un file WMF (Windows Metafile) che presenta un'intestazione metafile posizionabile all'inizio.

### Emf {#Emf}
```
public static final int Emf
```


Specifica un file Enhanced Metafile (EMF). Un file di questo tipo contiene solo record GDI.

### EmfPlusOnly {#EmfPlusOnly}
```
public static final int EmfPlusOnly
```


Specifica un file EMF+. Un file di questo tipo contiene solo record GDI+ e deve essere visualizzato utilizzando GDI+. Visualizzare i record con GDI può causare risultati imprevedibili.

### EmfPlusDual {#EmfPlusDual}
```
public static final int EmfPlusDual
```


Specifica un file EMF+ Dual. Un file di questo tipo contiene record GDI+ insieme a record GDI alternativi e può essere visualizzato utilizzando GDI o GDI+. Visualizzare i record con GDI può provocare una certa degradazione della qualità.

