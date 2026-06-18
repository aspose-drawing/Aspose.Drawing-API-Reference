---
title: EmfType
second_title: Referencia de la API de Aspose.Drawing para Java
description: Especifica la naturaleza de los registros que se colocan en un archivo Enhanced Metafile EMF.
type: docs
weight: 18
url: /es/java/com.aspose.drawing.imaging/emftype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfType extends System.Enum
```

Especifica la naturaleza de los registros que se colocan en un archivo Enhanced Metafile (EMF). Esta enumeración es utilizada por varios constructores en la clase [Metafile](../../com.aspose.drawing.imaging/metafile).
## Campos

| Campo | Descripción |
| --- | --- |
| [EmfOnly](#EmfOnly) | Especifica que todos los registros en el metafile son registros EMF, que pueden ser mostrados por GDI o GDI+. |
| [EmfPlusOnly](#EmfPlusOnly) | Especifica que todos los registros en el metafile son registros EMF+, que pueden ser mostrados por GDI+ pero no por GDI. |
| [EmfPlusDual](#EmfPlusDual) | Especifica que todos los registros EMF+ en el metafile están asociados con un registro EMF alternativo. |
### EmfOnly {#EmfOnly}
```
public static final int EmfOnly
```


Especifica que todos los registros en el metafile son registros EMF, que pueden ser mostrados por GDI o GDI+.

### EmfPlusOnly {#EmfPlusOnly}
```
public static final int EmfPlusOnly
```


Especifica que todos los registros en el metafile son registros EMF+, que pueden ser mostrados por GDI+ pero no por GDI.

### EmfPlusDual {#EmfPlusDual}
```
public static final int EmfPlusDual
```


Especifica que todos los registros EMF+ en el metafile están asociados con un registro EMF alternativo. Los metafiles del tipo `EmfType.EmfPlusDual` pueden ser mostrados por GDI o por GDI+.

