---
title: MetafileType
second_title: Referencia de la API de Aspose.Drawing para Java
description: Especifica tipos de metafiles.
type: docs
weight: 33
url: /es/java/com.aspose.drawing.imaging/metafiletype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MetafileType extends System.Enum
```

Especifica tipos de metafiles.
## Campos

| Campo | Descripción |
| --- | --- |
| [Invalid](#Invalid) | Especifica un formato de metafile que no es reconocido en GDI+. |
| [Wmf](#Wmf) | Especifica un archivo WMF (Windows Metafile). |
| [WmfPlaceable](#WmfPlaceable) | Especifica un archivo WMF (Windows Metafile) que tiene un encabezado de metafile colocable al frente. |
| [Emf](#Emf) | Especifica un archivo Enhanced Metafile (EMF). |
| [EmfPlusOnly](#EmfPlusOnly) | Especifica un archivo EMF+. |
| [EmfPlusDual](#EmfPlusDual) | Especifica un archivo EMF+ Dual. |
### Invalid {#Invalid}
```
public static final int Invalid
```


Especifica un formato de metafile que no es reconocido en GDI+.

### Wmf {#Wmf}
```
public static final int Wmf
```


Especifica un archivo WMF (Windows Metafile). Un archivo de este tipo contiene solo registros GDI.

### WmfPlaceable {#WmfPlaceable}
```
public static final int WmfPlaceable
```


Especifica un archivo WMF (Windows Metafile) que tiene un encabezado de metafile colocable al frente.

### Emf {#Emf}
```
public static final int Emf
```


Especifica un archivo Enhanced Metafile (EMF). Un archivo de este tipo contiene solo registros GDI.

### EmfPlusOnly {#EmfPlusOnly}
```
public static final int EmfPlusOnly
```


Especifica un archivo EMF+. Un archivo de este tipo contiene solo registros GDI+ y debe mostrarse usando GDI+. Mostrar los registros usando GDI puede causar resultados impredecibles.

### EmfPlusDual {#EmfPlusDual}
```
public static final int EmfPlusDual
```


Especifica un archivo EMF+ Dual. Un archivo de este tipo contiene registros GDI+ junto con registros GDI alternativos y puede mostrarse usando GDI o GDI+. Mostrar los registros usando GDI puede causar cierta degradación de calidad.

