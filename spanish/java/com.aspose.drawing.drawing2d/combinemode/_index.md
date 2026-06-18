---
title: CombineMode
second_title: Referencia de la API de Aspose.Drawing para Java
description: Especifica cómo se pueden combinar diferentes regiones de recorte.
type: docs
weight: 13
url: /es/java/com.aspose.drawing.drawing2d/combinemode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombineMode extends System.Enum
```

Especifica cómo se pueden combinar diferentes regiones de recorte.
## Campos

| Campo | Descripción |
| --- | --- |
| [Replace](#Replace) | Una región de recorte se reemplaza por otra. |
| [Intersect](#Intersect) | Dos regiones de recorte se combinan tomando su intersección. |
| [Union](#Union) | Dos regiones de recorte se combinan tomando la unión de ambas. |
| [Xor](#Xor) | Dos regiones de recorte se combinan tomando solo las áreas encerradas por una u otra región, pero no ambas. |
| [Exclude](#Exclude) | Especifica que la región existente se reemplaza por el resultado de que la nueva región sea eliminada de la región existente. |
| [Complement](#Complement) | Especifica que la región existente se reemplaza por el resultado de que la región existente sea eliminada de la nueva región. |
### Replace {#Replace}
```
public static final int Replace
```


Una región de recorte se reemplaza por otra.

### Intersect {#Intersect}
```
public static final int Intersect
```


Dos regiones de recorte se combinan tomando su intersección.

### Union {#Union}
```
public static final int Union
```


Dos regiones de recorte se combinan tomando la unión de ambas.

### Xor {#Xor}
```
public static final int Xor
```


Dos regiones de recorte se combinan tomando solo las áreas encerradas por una u otra región, pero no ambas.

### Exclude {#Exclude}
```
public static final int Exclude
```


Especifica que la región existente se reemplaza por el resultado de que la nueva región sea eliminada de la región existente. Dicho de otro modo, la nueva región se excluye de la región existente.

### Complement {#Complement}
```
public static final int Complement
```


Especifica que la región existente se reemplaza por el resultado de que la región existente sea eliminada de la nueva región. Dicho de otro modo, la región existente se excluye de la nueva región.

