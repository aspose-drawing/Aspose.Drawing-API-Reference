---
title: Point
second_title: Referencia de Aspose.Drawing para .NET API
description: Representa un par ordenado de coordenadas x e y enteras que define un punto en un plano bidimensional.
type: docs
weight: 930
url: /es/net/system.drawing/point/
---
## Point structure

Representa un par ordenado de coordenadas x e y enteras que define un punto en un plano bidimensional.

```csharp
public struct Point : IEquatable<Point>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Point](point#constructor)(int) | Inicializa una nueva instancia del[`Point`](../point) estructura usando coordenadas especificadas por un valor entero. |
| [Point](point#constructor_2)(Size) | Inicializa una nueva instancia del[`Point`](../point) estructura de un[`Size`](../size) . |
| [Point](point#constructor_1)(int, int) | Inicializa una nueva instancia del[`Point`](../point) estructura con las coordenadas especificadas. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsEmpty](../../system.drawing/point/isempty) { get; } | Obtiene un valor que indica si estePoint está vacío. |
| [X](../../system.drawing/point/x) { get; set; } | Obtiene o establece la coordenada x de este Punto. |
| [Y](../../system.drawing/point/y) { get; set; } | Obtiene o establece la coordenada y de este Punto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Add](../../system.drawing/point/add)(Point, Size) | Agrega el especificadoSize a lo especificadoPoint . |
| static [Ceiling](../../system.drawing/point/ceiling)(PointF) | Convierte un[`PointF`](../pointf) a un[`Point`](../point) realizando una operación de techo en todas las coordenadas. |
| static [Round](../../system.drawing/point/round)(PointF) | Convierte el especificadoPointF a un objeto Punto redondeando elPoint valores al entero más próximo. |
| static [Subtract](../../system.drawing/point/subtract)(Point, Size) | Traduce un[`Point`](../point) por el negativo de un dado[`Size`](../size) . |
| static [Truncate](../../system.drawing/point/truncate)(PointF) | Convierte un PuntoF en un Punto realizando una operación de truncado en todas las coordenadas. |
| override [Equals](../../system.drawing/point/equals#equals_1)(object) | Especifica si estePoint contiene las mismas coordenadas que el especificadoObject . |
| [Equals](../../system.drawing/point/equals#equals)(Point) | Comprueba si otros[`Point`](../point) estructura tiene la misma ubicación de este[`Point`](../point) estructura. |
| override [GetHashCode](../../system.drawing/point/gethashcode)() | Devuelve un código hash para estePoint . |
| [Offset](../../system.drawing/point/offset#offset_1)(Point) | Traduce estoPoint por el especificadoPoint . |
| [Offset](../../system.drawing/point/offset#offset)(int, int) | Traduce estoPoint por la cantidad especificada. |
| override [ToString](../../system.drawing/point/tostring)() | Convierte los atributos de este[`Point`](../point) a una cadena legible por humanos. |
| [operator +](../../system.drawing/point/op_addition) | Traduce un[`Point`](../point) por un dado[`Size`](../size) . |
| [operator ==](../../system.drawing/point/op_equality) | Compara dosPoint objects. El resultado especifica si los valores de losX yY properties de los dosPoint los objetos son iguales. |
| [explicit operator](../../system.drawing/point/op_explicit) | Crea un[`Size`](../size) con las coordenadas del especificado[`Point`](../point) . |
| [implicit operator](../../system.drawing/point/op_implicit) | Convierte el especificadoPoint estructura a unPointF estructura. |
| [operator !=](../../system.drawing/point/op_inequality) | Compara dosPoint objects. El resultado especifica si los valores de losX oY properties de los dosPoint los objetos son desiguales. |
| [operator -](../../system.drawing/point/op_subtraction) | Traduce un[`Point`](../point) por el negativo de un dado[`Size`](../size) . |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Empty](../../system.drawing/point/empty) | Representa unPoint que tieneX yY valores establecidos en cero. |

### Ver también

* espacio de nombres [System.Drawing](../../system.drawing)
* asamblea [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->