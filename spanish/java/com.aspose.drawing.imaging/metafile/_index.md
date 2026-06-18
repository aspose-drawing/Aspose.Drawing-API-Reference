---
title: Metarchivo
second_title: Referencia de la API de Aspose.Drawing para Java
description: Define un metafile gráfico.
type: docs
weight: 30
url: /es/java/com.aspose.drawing.imaging/metafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public final class Metafile extends Image
```

Define un metarchivo gráfico. Un metarchivo contiene registros que describen una secuencia de operaciones gráficas que pueden ser registradas (construidas) y reproducidas (mostradas). Esta clase no es heredable.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Metafile(byte[] henhmetafile, boolean deleteEmf)](#Metafile-byte---boolean-) | Inicializa una nueva instancia de la clase [Metafile](../../com.aspose.drawing.imaging/metafile) a partir del identificador especificado. |
| [Metafile(byte[] referenceHdc, int emfType)](#Metafile-byte---int-) | Inicializa una nueva instancia de la clase [Metafile](../../com.aspose.drawing.imaging/metafile) a partir del identificador especificado a un contexto de dispositivo y una enumeración [EmfType](../../com.aspose.drawing.imaging/emftype) que especifica el formato del [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [Metafile(String filename)](#Metafile-java.lang.String-) | Inicializa una nueva instancia de la clase [Metafile](../../com.aspose.drawing.imaging/metafile) a partir del nombre de archivo especificado. |
| [Metafile(String filename, byte[] referenceHdc)](#Metafile-java.lang.String-byte---) | Inicializa una nueva instancia de la clase [Metafile](../../com.aspose.drawing.imaging/metafile) a partir del nombre de archivo especificado. |
| [Metafile(InputStream stream)](#Metafile-java.io.InputStream-) | Inicializa una nueva instancia de la clase [Metafile](../../com.aspose.drawing.imaging/metafile) a partir del flujo de datos especificado. |
| [Metafile(InputStream stream, byte[] referenceHdc)](#Metafile-java.io.InputStream-byte---) | Inicializa una nueva instancia de la clase [Metafile](../../com.aspose.drawing.imaging/metafile) a partir del flujo de datos especificado y un identificador de Windows a un contexto de dispositivo. |
| [Metafile(System.IO.Stream stream, int type)](#Metafile-com.aspose.ms.System.IO.Stream-int-) | Inicializa una nueva instancia de la clase [Metafile](../../com.aspose.drawing.imaging/metafile) a partir del flujo de datos especificado y un identificador de Windows a un contexto de dispositivo. |
| [Metafile(InputStream stream, byte[] referenceHdc, int type)](#Metafile-java.io.InputStream-byte---int-) | Inicializa una nueva instancia de la clase [Metafile](../../com.aspose.drawing.imaging/metafile) a partir del flujo de datos especificado, un identificador de Windows a un contexto de dispositivo y una enumeración [EmfType](../../com.aspose.drawing.imaging/emftype) que especifica el formato del [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)](#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-) | Inicializa una nueva instancia de la clase [Metafile](../../com.aspose.drawing.imaging/metafile) a partir del flujo de datos especificado, un identificador de Windows a un contexto de dispositivo y una enumeración [EmfType](../../com.aspose.drawing.imaging/emftype) que especifica el formato del [Metafile](../../com.aspose.drawing.imaging/metafile). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getWidth()](#getWidth--) | Obtiene el ancho, en píxeles, de este [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getHeight()](#getHeight--) | Obtiene la altura, en píxeles, de este [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getRawFormat()](#getRawFormat--) | Obtiene el formato de archivo de este [Image](../../com.aspose.drawing/image). |
| [getPixelFormat()](#getPixelFormat--) | Obtiene el formato de píxel de este [Image](../../com.aspose.drawing/image). |
| [getPalette()](#getPalette--) | Obtiene o establece la paleta de colores utilizada para este [Image](../../com.aspose.drawing/image). |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | Obtiene o establece la paleta de colores utilizada para este [Image](../../com.aspose.drawing/image). |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | Obtiene una matriz de GUID que representan las dimensiones de los fotogramas dentro de este [Image](../../com.aspose.drawing/image). |
| [getPropertyIdList()](#getPropertyIdList--) | Obtiene los ID de los elementos de propiedad almacenados en este [Image](../../com.aspose.drawing/image). |
| [getPropertyItems()](#getPropertyItems--) | Obtiene todos los elementos de propiedad (fragmentos de metadatos) almacenados en este [Image](../../com.aspose.drawing/image). |
| [getMetafileHeader(InputStream stream)](#getMetafileHeader-java.io.InputStream-) | Devuelve el [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) asociado con el [Metafile](../../com.aspose.drawing.imaging/metafile) especificado. |
| [getMetafileHeader(String fileName)](#getMetafileHeader-java.lang.String-) | Devuelve el [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) asociado con el [Metafile](../../com.aspose.drawing.imaging/metafile) especificado. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Este método rota, voltea o rota y voltea el [Image](../../com.aspose.drawing/image). |
| [getHenhmetafile()](#getHenhmetafile--) | Devuelve un identificador de Windows a un [Metafile](../../com.aspose.drawing.imaging/metafile) mejorado. |
| [playRecord(int recordType, int flags, int dataSize, byte[] dataArray)](#playRecord-int-int-int-byte---) | Reproduce un registro individual de metarchivo. |
| [getMetafileHeader()](#getMetafileHeader--) | Devuelve el [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) asociado con este [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | Obtiene el elemento de propiedad especificado de este [Image](../../com.aspose.drawing/image). |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | Elimina el elemento de propiedad especificado de este [Image](../../com.aspose.drawing/image). |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | Almacena un elemento de propiedad (fragmento de metadatos) en este [Image](../../com.aspose.drawing/image). |
### Metafile(byte[] henhmetafile, boolean deleteEmf) {#Metafile-byte---boolean-}
```
public Metafile(byte[] henhmetafile, boolean deleteEmf)
```


Inicializa una nueva instancia de la clase [Metafile](../../com.aspose.drawing.imaging/metafile) a partir del identificador especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| henhmetafile | byte[] | Un controlador a un metarchivo mejorado. |
| deleteEmf | boolean | true para eliminar el controlador del metarchivo mejorado cuando el [Metafile](../../com.aspose.drawing.imaging/metafile) se elimina; de lo contrario, false. |

### Metafile(byte[] referenceHdc, int emfType) {#Metafile-byte---int-}
```
public Metafile(byte[] referenceHdc, int emfType)
```


Inicializa una nueva instancia de la clase [Metafile](../../com.aspose.drawing.imaging/metafile) a partir del identificador especificado a un contexto de dispositivo y una enumeración [EmfType](../../com.aspose.drawing.imaging/emftype) que especifica el formato del [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| referenceHdc | byte[] | El controlador a un contexto de dispositivo. |
| emfType | int | Un [EmfType](../../com.aspose.drawing.imaging/emftype) que especifica el formato del [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(String filename) {#Metafile-java.lang.String-}
```
public Metafile(String filename)
```


Inicializa una nueva instancia de la clase [Metafile](../../com.aspose.drawing.imaging/metafile) a partir del nombre de archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | java.lang.String | Una cadena que representa el nombre de archivo desde el cual crear el nuevo [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(String filename, byte[] referenceHdc) {#Metafile-java.lang.String-byte---}
```
public Metafile(String filename, byte[] referenceHdc)
```


Inicializa una nueva instancia de la clase [Metafile](../../com.aspose.drawing.imaging/metafile) a partir del nombre de archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | java.lang.String | Una cadena que representa el nombre de archivo desde el cual crear el nuevo [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Un controlador de Windows a un contexto de dispositivo. |

### Metafile(InputStream stream) {#Metafile-java.io.InputStream-}
```
public Metafile(InputStream stream)
```


Inicializa una nueva instancia de la clase [Metafile](../../com.aspose.drawing.imaging/metafile) a partir del flujo de datos especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | El InputStream desde el cual crear el nuevo [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(InputStream stream, byte[] referenceHdc) {#Metafile-java.io.InputStream-byte---}
```
public Metafile(InputStream stream, byte[] referenceHdc)
```


Inicializa una nueva instancia de la clase [Metafile](../../com.aspose.drawing.imaging/metafile) a partir del flujo de datos especificado y un controlador de Windows a un contexto de dispositivo. />.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Un InputStream que contiene los datos de este [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Un controlador de Windows a un contexto de dispositivo del objeto [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(System.IO.Stream stream, int type) {#Metafile-com.aspose.ms.System.IO.Stream-int-}
```
public Metafile(System.IO.Stream stream, int type)
```


Inicializa una nueva instancia de la clase [Metafile](../../com.aspose.drawing.imaging/metafile) a partir del flujo de datos especificado y un controlador de Windows a un contexto de dispositivo. />.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Un InputStream que contiene los datos de este [Metafile](../../com.aspose.drawing.imaging/metafile). |
| type | int | debe ser int 1. |

### Metafile(InputStream stream, byte[] referenceHdc, int type) {#Metafile-java.io.InputStream-byte---int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, int type)
```


Inicializa una nueva instancia de la clase [Metafile](../../com.aspose.drawing.imaging/metafile) a partir del flujo de datos especificado, un identificador de Windows a un contexto de dispositivo y una enumeración [EmfType](../../com.aspose.drawing.imaging/emftype) que especifica el formato del [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Un InputStream que contiene los datos de este [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Un controlador de Windows a un contexto de dispositivo. |
| type | int | Un [EmfType](../../com.aspose.drawing.imaging/emftype) que especifica el formato del [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type) {#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)
```


Inicializa una nueva instancia de la clase [Metafile](../../com.aspose.drawing.imaging/metafile) a partir del flujo de datos especificado, un identificador de Windows a un contexto de dispositivo y una enumeración [EmfType](../../com.aspose.drawing.imaging/emftype) que especifica el formato del [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Un InputStream que contiene los datos de este [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Un controlador de Windows a un contexto de dispositivo. |
| frameRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Un [Rectangle](../../com.aspose.drawing/rectangle) que representa el rectángulo que delimita el nuevo [Metafile](../../com.aspose.drawing.imaging/metafile). |
| frameUnit | int | Un [MetafileFrameUnit](../../com.aspose.drawing.imaging/metafileframeunit) que especifica la unidad de medida para frameRect. |
| type | int | Un [EmfType](../../com.aspose.drawing.imaging/emftype) que especifica el formato del [Metafile](../../com.aspose.drawing.imaging/metafile). |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene el ancho, en píxeles, de este [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtiene la altura, en píxeles, de este [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
int - la altura, en píxeles, de este [Metafile](../../com.aspose.drawing.imaging/metafile).
### getRawFormat() {#getRawFormat--}
```
public ImageFormat getRawFormat()
```


Obtiene el formato de archivo de este [Image](../../com.aspose.drawing/image).

**Returns:**
[ImageFormat](../../com.aspose.drawing.imaging/imageformat) - The [ImageFormat](../../com.aspose.drawing.imaging/imageformat) that represents the file format of this [Image](../../com.aspose.drawing/image).
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Obtiene el formato de píxel de este [Image](../../com.aspose.drawing/image).

**Returns:**
int - Un `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) que representa el formato de píxel para este [Image](../../com.aspose.drawing/image).
### getPalette() {#getPalette--}
```
public ColorPalette getPalette()
```


Obtiene o establece la paleta de colores utilizada para este [Image](../../com.aspose.drawing/image).

**Returns:**
[ColorPalette](../../com.aspose.drawing.imaging/colorpalette) - A [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) that represents the color palette used for this [Image](../../com.aspose.drawing/image).
### setPalette(ColorPalette value) {#setPalette-com.aspose.drawing.imaging.ColorPalette-}
```
public void setPalette(ColorPalette value)
```


Obtiene o establece la paleta de colores utilizada para este [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) |  |

### getFrameDimensionsList() {#getFrameDimensionsList--}
```
public UUID[] getFrameDimensionsList()
```


Obtiene una matriz de GUID que representan las dimensiones de los fotogramas dentro de este [Image](../../com.aspose.drawing/image).

**Returns:**
java.util.UUID[] - Una matriz de GUID que especifica las dimensiones de los fotogramas dentro de este [Image](../../com.aspose.drawing/image) de más significativo a menos significativo.
### getPropertyIdList() {#getPropertyIdList--}
```
public int[] getPropertyIdList()
```


Obtiene los ID de los elementos de propiedad almacenados en este [Image](../../com.aspose.drawing/image).

**Returns:**
int[] - Una matriz de los IDs de propiedad, uno para cada elemento de propiedad almacenado en esta imagen.
### getPropertyItems() {#getPropertyItems--}
```
public PropertyItem[] getPropertyItems()
```


Obtiene todos los elementos de propiedad (fragmentos de metadatos) almacenados en este [Image](../../com.aspose.drawing/image).

**Returns:**
com.aspose.drawing.imaging.PropertyItem[] - Una matriz de objetos [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) , uno para cada elemento de propiedad almacenado en la imagen.
### getMetafileHeader(InputStream stream) {#getMetafileHeader-java.io.InputStream-}
```
public static MetafileHeader getMetafileHeader(InputStream stream)
```


Devuelve el [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) asociado con el [Metafile](../../com.aspose.drawing.imaging/metafile) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Un InputStream que contiene el [Metafile](../../com.aspose.drawing.imaging/metafile) del cual se recupera un encabezado. |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### getMetafileHeader(String fileName) {#getMetafileHeader-java.lang.String-}
```
public static MetafileHeader getMetafileHeader(String fileName)
```


Devuelve el [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) asociado con el [Metafile](../../com.aspose.drawing.imaging/metafile) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Una cadena que contiene el nombre del [Metafile](../../com.aspose.drawing.imaging/metafile) del cual se recupera un encabezado. |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Este método rota, voltea o rota y voltea el [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rotateFlipType | int | Un miembro [RotateFlipType](../../com.aspose.drawing/rotatefliptype) que especifica el tipo de rotación y volteo a aplicar a la imagen. |

### getHenhmetafile() {#getHenhmetafile--}
```
public System.IntPtr getHenhmetafile()
```


Devuelve un identificador de Windows a un [Metafile](../../com.aspose.drawing.imaging/metafile) mejorado.

**Returns:**
com.aspose.ms.System.IntPtr - Un controlador de Windows a este [Metafile](../../com.aspose.drawing.imaging/metafile).
### playRecord(int recordType, int flags, int dataSize, byte[] dataArray) {#playRecord-int-int-int-byte---}
```
public void playRecord(int recordType, int flags, int dataSize, byte[] dataArray)
```


Reproduce un registro individual de metarchivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| recordType | int | Elemento de la [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype) que especifica el tipo de registro de metafile que se está reproduciendo. |
| flags | int | Conjunto de indicadores que especifican los atributos del registro. |
| dataSize | int | El número de bytes en los datos del registro. |
| dataArray | byte[] | Una matriz de bytes que contiene los datos del registro. |

### getMetafileHeader() {#getMetafileHeader--}
```
public MetafileHeader getMetafileHeader()
```


Devuelve el [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) asociado con este [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with this [Metafile](../../com.aspose.drawing.imaging/metafile).
### getPropertyItem(int propid) {#getPropertyItem-int-}
```
public PropertyItem getPropertyItem(int propid)
```


Obtiene el elemento de propiedad especificado de este [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propid | int | El ID del elemento de propiedad a obtener. |

**Returns:**
[PropertyItem](../../com.aspose.drawing.imaging/propertyitem) - The [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) this method gets.
### removePropertyItem(int propid) {#removePropertyItem-int-}
```
public void removePropertyItem(int propid)
```


Elimina el elemento de propiedad especificado de este [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propid | int | El ID del elemento de propiedad a eliminar. |

### setPropertyItem(PropertyItem propitem) {#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-}
```
public void setPropertyItem(PropertyItem propitem)
```


Almacena un elemento de propiedad (fragmento de metadatos) en este [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propitem | [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) | El [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) que se almacenará. |

