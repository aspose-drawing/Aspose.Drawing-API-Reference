---
title: MetafileType
second_title: Aspose.Drawing für Java API-Referenz
description: Gibt die Typen von Metadateien an.
type: docs
weight: 33
url: /de/java/com.aspose.drawing.imaging/metafiletype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MetafileType extends System.Enum
```

Gibt die Typen von Metadateien an.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Invalid](#Invalid) | Gibt ein Metadateiformat an, das in GDI+ nicht erkannt wird. |
| [Wmf](#Wmf) | Gibt eine WMF (Windows Metafile)-Datei an. |
| [WmfPlaceable](#WmfPlaceable) | Gibt eine WMF (Windows Metafile)-Datei an, die einen platzierbaren Metadatei‑Header vorn hat. |
| [Emf](#Emf) | Gibt eine Enhanced Metafile (EMF)-Datei an. |
| [EmfPlusOnly](#EmfPlusOnly) | Gibt eine EMF+-Datei an. |
| [EmfPlusDual](#EmfPlusDual) | Gibt eine EMF+ Dual‑Datei an. |
### Invalid {#Invalid}
```
public static final int Invalid
```


Gibt ein Metadateiformat an, das in GDI+ nicht erkannt wird.

### Wmf {#Wmf}
```
public static final int Wmf
```


Gibt eine WMF (Windows Metafile)-Datei an. Eine solche Datei enthält nur GDI‑Einträge.

### WmfPlaceable {#WmfPlaceable}
```
public static final int WmfPlaceable
```


Gibt eine WMF (Windows Metafile)-Datei an, die einen platzierbaren Metadatei‑Header vorn hat.

### Emf {#Emf}
```
public static final int Emf
```


Gibt eine Enhanced Metafile (EMF)-Datei an. Eine solche Datei enthält nur GDI‑Einträge.

### EmfPlusOnly {#EmfPlusOnly}
```
public static final int EmfPlusOnly
```


Gibt eine EMF+-Datei an. Eine solche Datei enthält nur GDI+-Einträge und muss mit GDI+ angezeigt werden. Die Anzeige der Einträge mit GDI kann zu unvorhersehbaren Ergebnissen führen.

### EmfPlusDual {#EmfPlusDual}
```
public static final int EmfPlusDual
```


Gibt eine EMF+ Dual‑Datei an. Eine solche Datei enthält GDI+-Einträge zusammen mit alternativen GDI‑Einträgen und kann entweder mit GDI oder GDI+ angezeigt werden. Die Anzeige der Einträge mit GDI kann zu einer leichten Qualitätsverschlechterung führen.

