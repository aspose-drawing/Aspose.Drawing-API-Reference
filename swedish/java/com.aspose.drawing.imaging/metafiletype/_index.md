---
title: MetafileType
second_title: Aspose.Drawing för Java API‑referens
description: Anger typer av metafiler.
type: docs
weight: 33
url: /sv/java/com.aspose.drawing.imaging/metafiletype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MetafileType extends System.Enum
```

Anger typer av metafiler.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Invalid](#Invalid) | Specificerar ett metafilformat som inte känns igen i GDI+. |
| [Wmf](#Wmf) | Specificerar en WMF (Windows Metafile)-fil. |
| [WmfPlaceable](#WmfPlaceable) | Specificerar en WMF (Windows Metafile)-fil som har ett placerbart metafilhuvud framför sig. |
| [Emf](#Emf) | Specificerar en Enhanced Metafile (EMF)-fil. |
| [EmfPlusOnly](#EmfPlusOnly) | Specificerar en EMF+-fil. |
| [EmfPlusDual](#EmfPlusDual) | Specificerar en EMF+ Dual-fil. |
### Invalid {#Invalid}
```
public static final int Invalid
```


Specificerar ett metafilformat som inte känns igen i GDI+.

### Wmf {#Wmf}
```
public static final int Wmf
```


Specificerar en WMF (Windows Metafile)-fil. En sådan fil innehåller endast GDI-poster.

### WmfPlaceable {#WmfPlaceable}
```
public static final int WmfPlaceable
```


Specificerar en WMF (Windows Metafile)-fil som har ett placerbart metafilhuvud framför sig.

### Emf {#Emf}
```
public static final int Emf
```


Specificerar en Enhanced Metafile (EMF)-fil. En sådan fil innehåller endast GDI-poster.

### EmfPlusOnly {#EmfPlusOnly}
```
public static final int EmfPlusOnly
```


Specificerar en EMF+-fil. En sådan fil innehåller endast GDI+-poster och måste visas med GDI+. Att visa posterna med GDI kan leda till oförutsägbara resultat.

### EmfPlusDual {#EmfPlusDual}
```
public static final int EmfPlusDual
```


Specificerar en EMF+ Dual-fil. En sådan fil innehåller GDI+-poster tillsammans med alternativa GDI-poster och kan visas med antingen GDI eller GDI+. Att visa posterna med GDI kan orsaka viss kvalitetsförsämring.

