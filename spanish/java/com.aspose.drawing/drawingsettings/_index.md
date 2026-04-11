---
title: DrawingSettings
second_title: Referencia de la API de Aspose.Drawing para Java
description: Permite ajustar el comportamiento de la biblioteca de dibujo en caso de usar algunas funciones que aún no están implementadas completamente.
type: docs
weight: 19
url: /es/java/com.aspose.drawing/drawingsettings/
---
**Inheritance:**
java.lang.Object
```
public final class DrawingSettings
```

Permite ajustar el comportamiento de la biblioteca de dibujo en caso de usar algunas funciones que aún no están implementadas completamente.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [DrawingSettings()](#DrawingSettings--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getStrictMode()](#getStrictMode--) | Obtiene un valor que indica si la captura más estricta de características no implementadas está habilitada. |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | Establece un valor que indica si la captura más estricta de características no implementadas está habilitada. |
### DrawingSettings() {#DrawingSettings--}
```
public DrawingSettings()
```


### getStrictMode() {#getStrictMode--}
```
public static boolean getStrictMode()
```


Obtiene un valor que indica si la captura más estricta de características no implementadas está habilitada.

--------------------

Si se establece en true, en caso de usar características/parámetros que no funcionan correctamente en la implementación actual, la biblioteca lanzará NotImplementedException. Si se establece en false, algunos parámetros pueden ser ignorados para dar al programa del usuario la oportunidad de funcionar. En ese caso, los resultados del dibujo pueden verse diferentes en comparación con GDI+.

**Returns:**
boolean - un valor que indica si la captura más estricta de características no implementadas está habilitada.
### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public static void setStrictMode(boolean value)
```


Establece un valor que indica si la captura más estricta de características no implementadas está habilitada.

--------------------

Si se establece en true, en caso de usar características/parámetros que no funcionan correctamente en la implementación actual, la biblioteca lanzará NotImplementedException. Si se establece en false, algunos parámetros pueden ser ignorados para dar al programa del usuario la oportunidad de funcionar. En ese caso, los resultados del dibujo pueden verse diferentes en comparación con GDI+.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean | un valor que indica si la captura más estricta de características no implementadas está habilitada. |

