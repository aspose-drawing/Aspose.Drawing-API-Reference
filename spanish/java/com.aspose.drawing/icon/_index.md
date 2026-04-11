---
title: Icon
second_title: Referencia de la API de Aspose.Drawing para Java
description: Representa un icono de Windows que es una pequeña imagen bitmap utilizada para representar un objeto.
type: docs
weight: 29
url: /es/java/com.aspose.drawing/icon/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.ms.System.IDisposable
```
public final class Icon implements System.ICloneable, System.IDisposable
```

Representa un icono de Windows, que es una pequeña imagen bitmap utilizada para representar un objeto. Los iconos pueden considerarse como bitmaps transparentes, aunque su tamaño lo determina el sistema.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Icon(String fileName)](#Icon-java.lang.String-) | Inicializa una nueva instancia de la clase [Icon](../../com.aspose.drawing/icon) a partir del nombre de archivo especificado. |
| [Icon(InputStream stream)](#Icon-java.io.InputStream-) | Inicializa una nueva instancia de la clase [Icon](../../com.aspose.drawing/icon) a partir del flujo de datos especificado. |
| [Icon(String fileName, Size size)](#Icon-java.lang.String-com.aspose.drawing.Size-) | Inicializa una nueva instancia de la clase [Icon](../../com.aspose.drawing/icon) del tamaño especificado a partir del archivo especificado. |
| [Icon(Icon original, Size size)](#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-) | Inicializa una nueva instancia de la clase [Icon](../../com.aspose.drawing/icon) e intenta encontrar una versión del icono que coincida con el tamaño solicitado. |
| [Icon(Object type, String resource)](#Icon-java.lang.Object-java.lang.String-) | Inicializa una nueva instancia de la clase [Icon](../../com.aspose.drawing/icon) a partir de un recurso en el ensamblado especificado. |
| [Icon(InputStream stream, Size size)](#Icon-java.io.InputStream-com.aspose.drawing.Size-) | Inicializa una nueva instancia de la clase [Icon](../../com.aspose.drawing/icon) del tamaño especificado a partir del flujo especificado. |
| [Icon(String fileName, int width, int height)](#Icon-java.lang.String-int-int-) | Inicializa una nueva instancia de la clase [Icon](../../com.aspose.drawing/icon) con el ancho y la altura especificados del archivo especificado. |
| [Icon(Icon original, int width, int height)](#Icon-com.aspose.drawing.Icon-int-int-) | Inicializa una nueva instancia de la clase [Icon](../../com.aspose.drawing/icon) y intenta encontrar una versión del ícono que coincida con el tamaño solicitado.. |
| [Icon(InputStream stream, int width, int height)](#Icon-java.io.InputStream-int-int-) | Inicializa una nueva instancia de la clase [Icon](../../com.aspose.drawing/icon) a partir del flujo de datos especificado y con el ancho y la altura especificados. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getHandle()](#getHandle--) | Obtiene el identificador de este [Icon](../../com.aspose.drawing/icon). |
| [getHeight()](#getHeight--) | Obtiene la altura de este [Icon](../../com.aspose.drawing/icon). |
| [getSize()](#getSize--) | Obtiene el tamaño de este [Icon](../../com.aspose.drawing/icon). |
| [getWidth()](#getWidth--) | Obtiene el ancho de este [Icon](../../com.aspose.drawing/icon). |
| [extractAssociatedIcon(String filePath)](#extractAssociatedIcon-java.lang.String-) | Devuelve una representación de ícono de una imagen que está contenida en el archivo especificado. |
| [fromHandle(byte[] handle)](#fromHandle-byte---) | Crea un [Icon](../../com.aspose.drawing/icon) GDI+ a partir del identificador de Windows especificado para un ícono (HICON). |
| [deepClone()](#deepClone--) | Clona el [Icon](../../com.aspose.drawing/icon), creando una imagen duplicada. |
| [dispose()](#dispose--) | Realiza tareas definidas por la aplicación asociadas con la liberación, el desalojo o el restablecimiento de recursos no administrados. |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | Guarda este [Icon](../../com.aspose.drawing/icon) en el java.io.InputStream de salida especificado. |
| [toBitmap()](#toBitmap--) | Convierte este [Icon](../../com.aspose.drawing/icon) a un [Bitmap](../../com.aspose.drawing/bitmap) GDI+. |
| [toString()](#toString--) | Obtiene una cadena legible por humanos que describe el [Icon](../../com.aspose.drawing/icon). |
### Icon(String fileName) {#Icon-java.lang.String-}
```
public Icon(String fileName)
```


Inicializa una nueva instancia de la clase [Icon](../../com.aspose.drawing/icon) a partir del nombre de archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | El archivo del cual cargar el [Icon](../../com.aspose.drawing/icon). |

### Icon(InputStream stream) {#Icon-java.io.InputStream-}
```
public Icon(InputStream stream)
```


Inicializa una nueva instancia de la clase [Icon](../../com.aspose.drawing/icon) a partir del flujo de datos especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | El flujo de datos desde el cual cargar el [Icon](../../com.aspose.drawing/icon). |

### Icon(String fileName, Size size) {#Icon-java.lang.String-com.aspose.drawing.Size-}
```
public Icon(String fileName, Size size)
```


Inicializa una nueva instancia de la clase [Icon](../../com.aspose.drawing/icon) del tamaño especificado a partir del archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | El nombre y la ruta al archivo que contiene los datos del ícono. |
| size | [Size](../../com.aspose.drawing/size) | El tamaño deseado del ícono. |

### Icon(Icon original, Size size) {#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-}
```
public Icon(Icon original, Size size)
```


Inicializa una nueva instancia de la clase [Icon](../../com.aspose.drawing/icon) e intenta encontrar una versión del icono que coincida con el tamaño solicitado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | El [Icon](../../com.aspose.drawing/icon) desde el cual cargar el ícono recién dimensionado. |
| size | [Size](../../com.aspose.drawing/size) | Una estructura `Size`([.getSize](../../null/\#getSize)) que especifica la altura y el ancho del nuevo [Icon](../../com.aspose.drawing/icon). |

### Icon(Object type, String resource) {#Icon-java.lang.Object-java.lang.String-}
```
public Icon(Object type, String resource)
```


Inicializa una nueva instancia de la clase [Icon](../../com.aspose.drawing/icon) a partir de un recurso en el ensamblado especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | java.lang.Object | Un Type que especifica el ensamblado en el que buscar el recurso. |
| recurso | java.lang.String | El nombre del recurso a cargar. |

### Icon(InputStream stream, Size size) {#Icon-java.io.InputStream-com.aspose.drawing.Size-}
```
public Icon(InputStream stream, Size size)
```


Inicializa una nueva instancia de la clase [Icon](../../com.aspose.drawing/icon) del tamaño especificado a partir del flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo que contiene los datos del ícono. |
| size | [Size](../../com.aspose.drawing/size) | El tamaño deseado del ícono. |

### Icon(String fileName, int width, int height) {#Icon-java.lang.String-int-int-}
```
public Icon(String fileName, int width, int height)
```


Inicializa una nueva instancia de la clase [Icon](../../com.aspose.drawing/icon) con el ancho y la altura especificados del archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | El nombre y la ruta al archivo que contiene los datos del [Icon](../../com.aspose.drawing/icon). |
| width | int | El ancho deseado del [Icon](../../com.aspose.drawing/icon). |
| height | int | La altura deseada del [Icon](../../com.aspose.drawing/icon). |

### Icon(Icon original, int width, int height) {#Icon-com.aspose.drawing.Icon-int-int-}
```
public Icon(Icon original, int width, int height)
```


Inicializa una nueva instancia de la clase [Icon](../../com.aspose.drawing/icon) y intenta encontrar una versión del ícono que coincida con el tamaño solicitado..

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | El icono del que cargar el tamaño diferente. |
| ancho | int | El ancho del nuevo icono. |
| alto | int | La altura del nuevo icono. |

### Icon(InputStream stream, int width, int height) {#Icon-java.io.InputStream-int-int-}
```
public Icon(InputStream stream, int width, int height)
```


Inicializa una nueva instancia de la clase [Icon](../../com.aspose.drawing/icon) a partir del flujo de datos especificado y con el ancho y la altura especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo de datos desde el cual cargar el icono. |
| ancho | int | El ancho, en píxeles, del icono. |
| alto | int | La altura, en píxeles, del icono. |

### getHandle() {#getHandle--}
```
public System.IntPtr getHandle()
```


Obtiene el identificador para este [Icon](../../com.aspose.drawing/icon). Esto no es una copia del identificador; no lo libere.

Valor: El identificador de Windows para el icono.

**Returns:**
com.aspose.ms.System.IntPtr
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtiene la altura de este [Icon](../../com.aspose.drawing/icon).

Valor: La altura de este [Icon](../../com.aspose.drawing/icon).

**Returns:**
int
### getSize() {#getSize--}
```
public Size getSize()
```


Obtiene el tamaño de este [Icon](../../com.aspose.drawing/icon).

Valor: Una estructura `Size`([.getSize](../../null/\#getSize)) que especifica el ancho y la altura de este [Icon](../../com.aspose.drawing/icon).

**Returns:**
[Size](../../com.aspose.drawing/size)
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene el ancho de este [Icon](../../com.aspose.drawing/icon).

Valor: El ancho de este [Icon](../../com.aspose.drawing/icon).

**Returns:**
int
### extractAssociatedIcon(String filePath) {#extractAssociatedIcon-java.lang.String-}
```
public static Icon extractAssociatedIcon(String filePath)
```


Devuelve una representación de ícono de una imagen que está contenida en el archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta al archivo que contiene una imagen. |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) representation of the image that is contained in the specified file.
### fromHandle(byte[] handle) {#fromHandle-byte---}
```
public static Icon fromHandle(byte[] handle)
```


Crea un [Icon](../../com.aspose.drawing/icon) GDI+ a partir del identificador de Windows especificado para un ícono (HICON).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| handle | byte[] | Un identificador de Windows para un icono. |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) this method creates.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clona el [Icon](../../com.aspose.drawing/icon), creando una imagen duplicada.

**Returns:**
java.lang.Object - Un objeto que puede convertirse a un [Icon](../../com.aspose.drawing/icon).
### dispose() {#dispose--}
```
public void dispose()
```


Realiza tareas definidas por la aplicación asociadas con la liberación, el desalojo o el restablecimiento de recursos no administrados.

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


Guarda este [Icon](../../com.aspose.drawing/icon) en el java.io.InputStream de salida especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | java.io.OutputStream | El java.io.InputStream al que guardar. |

### toBitmap() {#toBitmap--}
```
public Bitmap toBitmap()
```


Convierte este [Icon](../../com.aspose.drawing/icon) a un [Bitmap](../../com.aspose.drawing/bitmap) GDI+.

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - A [Bitmap](../../com.aspose.drawing/bitmap) that represents the converted [Icon](../../com.aspose.drawing/icon).
### toString() {#toString--}
```
public String toString()
```


Obtiene una cadena legible por humanos que describe el [Icon](../../com.aspose.drawing/icon).

**Returns:**
java.lang.String - Una cadena que describe el [Icon](../../com.aspose.drawing/icon).
