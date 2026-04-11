---
title: Koordinatrymd
second_title: Aspose.Drawing för Java API‑referens
description: Anger vilket system som ska användas vid utvärdering av koordinater.
type: docs
weight: 16
url: /sv/java/com.aspose.drawing.drawing2d/coordinatespace/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CoordinateSpace extends System.Enum
```

Anger vilket system som ska användas vid utvärdering av koordinater.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [World](#World) | Anger att koordinaterna är i världens koordinatkontext. |
| [Page](#Page) | Anger att koordinaterna är i sidans koordinatkontext. |
| [Device](#Device) | Anger att koordinaterna är i enhetens koordinatkontext. |
### World {#World}
```
public static final int World
```


Anger att koordinaterna är i världens koordinatkontext. Världskoordinater används i en icke-fysisk miljö, såsom en modelleringsmiljö.

### Page {#Page}
```
public static final int Page
```


Anger att koordinaterna är i sidans koordinatkontext. Deras enheter definieras av egenskapen Graphics.PageUnit och måste vara ett av elementen i uppräkningen GraphicsUnit.

### Device {#Device}
```
public static final int Device
```


Anger att koordinaterna är i enhetens koordinatkontext. På en datorskärm mäts enhetskoordinaterna vanligtvis i pixlar.

