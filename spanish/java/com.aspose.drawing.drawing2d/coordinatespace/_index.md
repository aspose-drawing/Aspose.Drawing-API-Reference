---
title: EspacioDeCoordenadas
second_title: Referencia de la API de Aspose.Drawing para Java
description: Especifica el sistema a usar al evaluar coordenadas.
type: docs
weight: 16
url: /es/java/com.aspose.drawing.drawing2d/coordinatespace/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CoordinateSpace extends System.Enum
```

Especifica el sistema a usar al evaluar coordenadas.
## Campos

| Campo | Descripción |
| --- | --- |
| [World](#World) | Especifica que las coordenadas están en el contexto de coordenadas del mundo. |
| [Page](#Page) | Especifica que las coordenadas están en el contexto de coordenadas de la página. |
| [Device](#Device) | Especifica que las coordenadas están en el contexto de coordenadas del dispositivo. |
### World {#World}
```
public static final int World
```


Especifica que las coordenadas están en el contexto de coordenadas del mundo. Las coordenadas del mundo se utilizan en un entorno no físico, como un entorno de modelado.

### Page {#Page}
```
public static final int Page
```


Especifica que las coordenadas están en el contexto de coordenadas de la página. Sus unidades están definidas por la propiedad Graphics.PageUnit y deben ser uno de los elementos de la enumeración GraphicsUnit.

### Device {#Device}
```
public static final int Device
```


Especifica que las coordenadas están en el contexto de coordenadas del dispositivo. En una pantalla de computadora, las coordenadas del dispositivo suelen medirse en píxeles.

