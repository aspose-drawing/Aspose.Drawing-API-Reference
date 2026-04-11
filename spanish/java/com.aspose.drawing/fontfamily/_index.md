---
title: FontFamily
second_title: Referencia de la API de Aspose.Drawing para Java
description: Define un grupo de tipografías que tienen un diseño básico similar y ciertas variaciones en los estilos.
type: docs
weight: 24
url: /es/java/com.aspose.drawing/fontfamily/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class FontFamily implements System.IDisposable
```

Define un grupo de tipografías que tienen un diseño básico similar y ciertas variaciones en los estilos. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [FontFamily(String name)](#FontFamily-java.lang.String-) | Inicializa una nueva instancia de la clase [FontFamily](../../com.aspose.drawing/fontfamily) con el nombre especificado. |
| [FontFamily(String name, FontCollection fontCollection)](#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-) | Inicializa una nueva instancia de la clase [FontFamily](../../com.aspose.drawing/fontfamily). |
| [FontFamily(String name, FontFamilyDefinition definition)](#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-) | Inicializa una nueva instancia de la clase [FontFamily](../../com.aspose.drawing/fontfamily). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFamilies()](#getFamilies--) | Obtiene una matriz que contiene todos los objetos [FontFamily](../../com.aspose.drawing/fontfamily) asociados al contexto gráfico actual. |
| [getGenericSansSerif()](#getGenericSansSerif--) | Obtiene un objeto [FontFamily](../../com.aspose.drawing/fontfamily) genérico sans serif. |
| [getGenericSerif()](#getGenericSerif--) | Obtiene un [FontFamily](../../com.aspose.drawing/fontfamily) genérico serif. |
| [getGenericMonospace()](#getGenericMonospace--) | Obtiene un [FontFamily](../../com.aspose.drawing/fontfamily) genérico monoespaciado. |
| [getName()](#getName--) | Obtiene el nombre de este [FontFamily](../../com.aspose.drawing/fontfamily). |
| [dispose()](#dispose--) | Libera todos los recursos utilizados por este [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getName(int language)](#getName-int-) | Devuelve el nombre, en el idioma especificado, de este [FontFamily](../../com.aspose.drawing/fontfamily). |
| [isStyleAvailable(int style)](#isStyleAvailable-int-) | Indica si la enumeración [FontStyle](../../com.aspose.drawing/fontstyle) especificada está disponible. |
| [getEmHeight(int style)](#getEmHeight-int-) | Obtiene la altura, en unidades de diseño de fuente, del cuadrado EM para el estilo especificado. |
| [getCellAscent(int style)](#getCellAscent-int-) | Devuelve la ascensión de celda, en unidades de diseño, de la [FontFamily](../../com.aspose.drawing/fontfamily) del estilo especificado. |
| [getCellDescent(int style)](#getCellDescent-int-) | Devuelve el descenso de celda, en unidades de diseño, de la [FontFamily](../../com.aspose.drawing/fontfamily) del estilo especificado. |
| [hashCode()](#hashCode--) | Obtiene un código hash para esta [FontFamily](../../com.aspose.drawing/fontfamily). |
| [equals(Object obj)](#equals-java.lang.Object-) | Indica si el objeto especificado es una [FontFamily](../../com.aspose.drawing/fontfamily) y es idéntico a esta [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getLineSpacing(int style)](#getLineSpacing-int-) | Devuelve el interlineado, en unidades de diseño, de la [FontFamily](../../com.aspose.drawing/fontfamily) del estilo especificado. |
### FontFamily(String name) {#FontFamily-java.lang.String-}
```
public FontFamily(String name)
```


Inicializa una nueva instancia de la clase [FontFamily](../../com.aspose.drawing/fontfamily) con el nombre especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | El nombre de la nueva [FontFamily](../../com.aspose.drawing/fontfamily). |

### FontFamily(String name, FontCollection fontCollection) {#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-}
```
public FontFamily(String name, FontCollection fontCollection)
```


Inicializa una nueva instancia de la clase [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | El nombre de la familia de fuentes. |
| fontCollection | [FontCollection](../../com.aspose.drawing/fontcollection) | La colección de fuentes. |

### FontFamily(String name, FontFamilyDefinition definition) {#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-}
```
public FontFamily(String name, FontFamilyDefinition definition)
```


Inicializa una nueva instancia de la clase [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | El nombre de la familia de fuentes. |
| definition | [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition) | La definición. |

### getFamilies() {#getFamilies--}
```
public static FontFamily[] getFamilies()
```


Obtiene una matriz que contiene todos los objetos [FontFamily](../../com.aspose.drawing/fontfamily) asociados al contexto gráfico actual.

**Returns:**
com.aspose.drawing.FontFamily[] - Una matriz de objetos [FontFamily](../../com.aspose.drawing/fontfamily) asociados con el contexto gráfico actual.
### getGenericSansSerif() {#getGenericSansSerif--}
```
public static FontFamily getGenericSansSerif()
```


Obtiene un objeto [FontFamily](../../com.aspose.drawing/fontfamily) genérico sans serif.

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) object that represents a generic sans serif font.
### getGenericSerif() {#getGenericSerif--}
```
public static FontFamily getGenericSerif()
```


Obtiene un [FontFamily](../../com.aspose.drawing/fontfamily) genérico serif.

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic serif font.
### getGenericMonospace() {#getGenericMonospace--}
```
public static FontFamily getGenericMonospace()
```


Obtiene un [FontFamily](../../com.aspose.drawing/fontfamily) genérico monoespaciado.

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic monospace font.
### getName() {#getName--}
```
public String getName()
```


Obtiene el nombre de este [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
java.lang.String - Una cadena que representa el nombre de esta [FontFamily](../../com.aspose.drawing/fontfamily).
### dispose() {#dispose--}
```
public void dispose()
```


Libera todos los recursos utilizados por este [FontFamily](../../com.aspose.drawing/fontfamily).

### getName(int language) {#getName-int-}
```
public String getName(int language)
```


Devuelve el nombre, en el idioma especificado, de este [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| idioma | int | El idioma en el que se devuelve el nombre. |

**Returns:**
java.lang.String - Una cadena que representa el nombre, en el idioma especificado, de esta [FontFamily](../../com.aspose.drawing/fontfamily).
### isStyleAvailable(int style) {#isStyleAvailable-int-}
```
public boolean isStyleAvailable(int style)
```


Indica si la enumeración [FontStyle](../../com.aspose.drawing/fontstyle) especificada está disponible.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| style | int | El [FontStyle](../../com.aspose.drawing/fontstyle) a probar. |

**Returns:**
boolean - true si el [FontStyle](../../com.aspose.drawing/fontstyle) especificado está disponible; de lo contrario, false.
### getEmHeight(int style) {#getEmHeight-int-}
```
public int getEmHeight(int style)
```


Obtiene la altura, en unidades de diseño de fuente, del cuadrado EM para el estilo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| style | int | El [FontStyle](../../com.aspose.drawing/fontstyle) para el cual obtener la altura EM. |

**Returns:**
int - La altura del cuadrado EM.
### getCellAscent(int style) {#getCellAscent-int-}
```
public int getCellAscent(int style)
```


Devuelve la ascensión de celda, en unidades de diseño, de la [FontFamily](../../com.aspose.drawing/fontfamily) del estilo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| style | int | Un [FontStyle](../../com.aspose.drawing/fontstyle) que contiene información de estilo para la fuente. |

**Returns:**
int - La ascensión de celda para esta [FontFamily](../../com.aspose.drawing/fontfamily) que utiliza el [FontStyle](../../com.aspose.drawing/fontstyle) especificado.
### getCellDescent(int style) {#getCellDescent-int-}
```
public int getCellDescent(int style)
```


Devuelve el descenso de celda, en unidades de diseño, de la [FontFamily](../../com.aspose.drawing/fontfamily) del estilo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| style | int | Un [FontStyle](../../com.aspose.drawing/fontstyle) que contiene información de estilo para la fuente. |

**Returns:**
int - La métrica de descenso de celda para esta [FontFamily](../../com.aspose.drawing/fontfamily) que utiliza el [FontStyle](../../com.aspose.drawing/fontstyle) especificado.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtiene un código hash para esta [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
int - El código hash para esta [FontFamily](../../com.aspose.drawing/fontfamily).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Indica si el objeto especificado es una [FontFamily](../../com.aspose.drawing/fontfamily) y es idéntico a esta [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El objeto a probar. |

**Returns:**
boolean - `true` si `obj` es una [FontFamily](../../com.aspose.drawing/fontfamily) y es idéntica a esta [FontFamily](../../com.aspose.drawing/fontfamily); de lo contrario, `false`.
### getLineSpacing(int style) {#getLineSpacing-int-}
```
public int getLineSpacing(int style)
```


Devuelve el interlineado, en unidades de diseño, de la [FontFamily](../../com.aspose.drawing/fontfamily) del estilo especificado. El interlineado es la distancia vertical entre las líneas base de dos líneas consecutivas de texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| style | int | El [FontStyle](../../com.aspose.drawing/fontstyle) a aplicar. |

**Returns:**
int - La distancia entre dos líneas consecutivas de texto.
