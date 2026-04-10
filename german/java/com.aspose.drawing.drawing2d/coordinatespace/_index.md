---
title: Koordinatenraum
second_title: Aspose.Drawing für Java API-Referenz
description: Gibt das System an, das bei der Auswertung von Koordinaten verwendet werden soll.
type: docs
weight: 16
url: /de/java/com.aspose.drawing.drawing2d/coordinatespace/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CoordinateSpace extends System.Enum
```

Gibt das System an, das bei der Auswertung von Koordinaten verwendet werden soll.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [World](#World) | Gibt an, dass Koordinaten im Weltkoordinaten-Kontext liegen. |
| [Page](#Page) | Gibt an, dass Koordinaten im Seitenkoordinaten-Kontext liegen. |
| [Device](#Device) | Gibt an, dass Koordinaten im Gerätekoordinaten-Kontext liegen. |
### World {#World}
```
public static final int World
```


Gibt an, dass Koordinaten im Weltkoordinaten-Kontext liegen. Weltkoordinaten werden in einer nicht‑physischen Umgebung verwendet, z. B. in einer Modellierungsumgebung.

### Page {#Page}
```
public static final int Page
```


Gibt an, dass Koordinaten im Seitenkoordinaten-Kontext liegen. Ihre Einheiten werden durch die Eigenschaft Graphics.PageUnit definiert und müssen eines der Elemente der Aufzählung GraphicsUnit sein.

### Device {#Device}
```
public static final int Device
```


Gibt an, dass Koordinaten im Gerätekoordinaten-Kontext liegen. Auf einem Computerbildschirm werden die Gerätekoordinaten üblicherweise in Pixeln gemessen.

