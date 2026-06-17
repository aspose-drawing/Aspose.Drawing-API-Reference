---
title: CoordinateSpace
second_title: Riferimento API di Aspose.Drawing per Java
description: Specifica il sistema da utilizzare durante la valutazione delle coordinate.
type: docs
weight: 16
url: /it/java/com.aspose.drawing.drawing2d/coordinatespace/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CoordinateSpace extends System.Enum
```

Specifica il sistema da utilizzare durante la valutazione delle coordinate.
## Campi

| Campo | Descrizione |
| --- | --- |
| [World](#World) | Specifica che le coordinate sono nel contesto di coordinate del mondo. |
| [Page](#Page) | Specifica che le coordinate sono nel contesto di coordinate della pagina. |
| [Device](#Device) | Specifica che le coordinate sono nel contesto di coordinate del dispositivo. |
### World {#World}
```
public static final int World
```


Specifica che le coordinate sono nel contesto di coordinate del mondo. Le coordinate del mondo sono usate in un ambiente non fisico, come un ambiente di modellazione.

### Page {#Page}
```
public static final int Page
```


Specifica che le coordinate sono nel contesto di coordinate della pagina. Le loro unità sono definite dalla proprietà Graphics.PageUnit e devono essere uno degli elementi dell'enumerazione GraphicsUnit.

### Device {#Device}
```
public static final int Device
```


Specifica che le coordinate sono nel contesto di coordinate del dispositivo. Su uno schermo del computer le coordinate del dispositivo sono solitamente misurate in pixel.

