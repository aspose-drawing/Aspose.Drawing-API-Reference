---
title: Bitmap
second_title: Referencia de la API de Aspose.Drawing para Java
description: Encapsula un bitmap que consiste en los datos de píxeles de una imagen gráfica y sus atributos.
type: docs
weight: 10
url: /es/java/com.aspose.drawing/bitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public class Bitmap extends Image
```

Encapsula un bitmap, que consiste en los datos de píxeles de una imagen gráfica y sus atributos. Un [Bitmap](../../com.aspose.drawing/bitmap) es un objeto utilizado para trabajar con imágenes definidas por datos de píxeles.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Bitmap(int width, int height)](#Bitmap-int-int-) | Inicializa una nueva instancia de la clase [Bitmap](../../com.aspose.drawing/bitmap) con el tamaño especificado. |
| [Bitmap(String filename)](#Bitmap-java.lang.String-) | Inicializa una nueva instancia de la clase [Bitmap](../../com.aspose.drawing/bitmap) a partir del archivo especificado. |
| [Bitmap(String filename, boolean useIcm)](#Bitmap-java.lang.String-boolean-) | Inicializa una nueva instancia de la clase [Bitmap](../../com.aspose.drawing/bitmap) a partir del archivo especificado. |
| [Bitmap(InputStream stream)](#Bitmap-java.io.InputStream-) | Inicializa una nueva instancia de la clase [Bitmap](../../com.aspose.drawing/bitmap) a partir del flujo de datos especificado. |
| [Bitmap(InputStream stream, boolean useIcm)](#Bitmap-java.io.InputStream-boolean-) | Inicializa una nueva instancia de la clase [Bitmap](../../com.aspose.drawing/bitmap) a partir del flujo de datos especificado. |
| [Bitmap(int width, int height, int format)](#Bitmap-int-int-int-) | Inicializa una nueva instancia de la clase [Bitmap](../../com.aspose.drawing/bitmap) con el tamaño y formato especificados. |
| [Bitmap(int width, int height, int stride, int format, int[] data)](#Bitmap-int-int-int-int-int---) | Inicializa una nueva instancia de la clase [Bitmap](../../com.aspose.drawing/bitmap) con el tamaño y los datos de píxeles especificados. |
| [Bitmap(Image original)](#Bitmap-com.aspose.drawing.Image-) | Inicializa una nueva instancia de la clase [Bitmap](../../com.aspose.drawing/bitmap) a partir de la imagen existente especificada. |
| [Bitmap(Image original, Size newSize)](#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-) | Inicializa una nueva instancia de la clase [Bitmap](../../com.aspose.drawing/bitmap) a partir de la imagen existente especificada, escalada al tamaño especificado. |
| [Bitmap(Image original, int width, int height)](#Bitmap-com.aspose.drawing.Image-int-int-) | Inicializa una nueva instancia de la clase [Bitmap](../../com.aspose.drawing/bitmap) a partir de la imagen existente especificada, escalada al tamaño especificado. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getWidth()](#getWidth--) | Obtiene el ancho, en píxeles, de este Bitmap. |
| [getHeight()](#getHeight--) | Obtiene la altura, en píxeles, de este Bitmap. |
| [getRawFormat()](#getRawFormat--) | Obtiene el formato de archivo de este [Image](../../com.aspose.drawing/image). |
| [getPixelFormat()](#getPixelFormat--) | Obtiene el formato de píxel de este [Image](../../com.aspose.drawing/image). |
| [getPalette()](#getPalette--) | Obtiene o establece la paleta de colores utilizada para este [Image](../../com.aspose.drawing/image). |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | Obtiene o establece la paleta de colores utilizada para este [Image](../../com.aspose.drawing/image). |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | Obtiene una matriz de GUID que representan las dimensiones de los fotogramas dentro de este [Image](../../com.aspose.drawing/image). |
| [getPropertyIdList()](#getPropertyIdList--) | Obtiene los ID de los elementos de propiedad almacenados en este [Image](../../com.aspose.drawing/image). |
| [getPropertyItems()](#getPropertyItems--) | Obtiene todos los elementos de propiedad (fragmentos de metadatos) almacenados en este [Image](../../com.aspose.drawing/image). |
| [deepClone(Rectangle rect, int format)](#deepClone-com.aspose.drawing.Rectangle-int-) | Crea una copia de la sección de este [Bitmap](../../com.aspose.drawing/bitmap) definida por la estructura [Rectangle](../../com.aspose.drawing/rectangle) y con una enumeración `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) especificada. |
| [deepClone(RectangleF rect, int format)](#deepClone-com.aspose.drawing.RectangleF-int-) | Crea una copia de la sección de este [Bitmap](../../com.aspose.drawing/bitmap) definida con una enumeración [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) especificada. |
| [setResolution(float xDpi, float yDpi)](#setResolution-float-float-) | Establece la resolución para este [Bitmap](../../com.aspose.drawing/bitmap). |
| [lockBits(Rectangle rect, int flags, int format)](#lockBits-com.aspose.drawing.Rectangle-int-int-) | Bloquea un [Bitmap](../../com.aspose.drawing/bitmap) en la memoria del sistema. |
| [unlockBits(BitmapData bitmapData)](#unlockBits-com.aspose.drawing.imaging.BitmapData-) | Desbloquea este [Bitmap](../../com.aspose.drawing/bitmap) de la memoria del sistema. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Obtiene el color del píxel especificado en este [Bitmap](../../com.aspose.drawing/bitmap). |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.drawing.Color-) | Establece el color del píxel especificado en este [Bitmap](../../com.aspose.drawing/bitmap). |
| [readArgb32Pixels(int[] pixels)](#readArgb32Pixels-int---) | Lee los píxeles del bitmap en formato ARGB32 en la matriz proporcionada. |
| [writeArgb32Pixels(int[] pixels)](#writeArgb32Pixels-int---) | Escribe píxeles en el bitmap. |
| [makeTransparent()](#makeTransparent--) | Hace que el color especificado sea transparente para este [Bitmap](../../com.aspose.drawing/bitmap). |
| [makeTransparent(Color transparentColor)](#makeTransparent-com.aspose.drawing.Color-) | Hace que el color especificado sea transparente para este [Bitmap](../../com.aspose.drawing/bitmap). |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Este método rota, voltea o rota y voltea el [Image](../../com.aspose.drawing/image). |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | Obtiene el elemento de propiedad especificado de este [Image](../../com.aspose.drawing/image). |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | Elimina el elemento de propiedad especificado de este [Image](../../com.aspose.drawing/image). |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | Almacena un elemento de propiedad (fragmento de metadatos) en este [Image](../../com.aspose.drawing/image). |
### Bitmap(int width, int height) {#Bitmap-int-int-}
```
public Bitmap(int width, int height)
```


Inicializa una nueva instancia de la clase [Bitmap](../../com.aspose.drawing/bitmap) con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho | int | El ancho, en píxeles, del nuevo Bitmap. |
|  | alto | int | La altura, en píxeles, del nuevo Bitmap. |

--------------------

El único formato interno de bitmap compatible en este momento es equivalente a `PixelFormat.Format32bppPArgb`. |

### Bitmap(String filename) {#Bitmap-java.lang.String-}
```
public Bitmap(String filename)
```


Inicializa una nueva instancia de la clase [Bitmap](../../com.aspose.drawing/bitmap) a partir del archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre de archivo | java.lang.String | El nombre del archivo bitmap. |

### Bitmap(String filename, boolean useIcm) {#Bitmap-java.lang.String-boolean-}
```
public Bitmap(String filename, boolean useIcm)
```


Inicializa una nueva instancia de la clase [Bitmap](../../com.aspose.drawing/bitmap) a partir del archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre de archivo | java.lang.String | El nombre del archivo bitmap. |
| useIcm | boolean | true para usar corrección de color para este [Bitmap](../../com.aspose.drawing/bitmap); de lo contrario, false. |

### Bitmap(InputStream stream) {#Bitmap-java.io.InputStream-}
```
public Bitmap(InputStream stream)
```


Inicializa una nueva instancia de la clase [Bitmap](../../com.aspose.drawing/bitmap) a partir del flujo de datos especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo de datos utilizado para cargar la imagen. |

### Bitmap(InputStream stream, boolean useIcm) {#Bitmap-java.io.InputStream-boolean-}
```
public Bitmap(InputStream stream, boolean useIcm)
```


Inicializa una nueva instancia de la clase [Bitmap](../../com.aspose.drawing/bitmap) a partir del flujo de datos especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo de datos utilizado para cargar la imagen. |
| useIcm | boolean | `true` para usar corrección de color para este [Bitmap](../../com.aspose.drawing/bitmap); de lo contrario, `false`. |

### Bitmap(int width, int height, int format) {#Bitmap-int-int-int-}
```
public Bitmap(int width, int height, int format)
```


Inicializa una nueva instancia de la clase [Bitmap](../../com.aspose.drawing/bitmap) con el tamaño y formato especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho, en píxeles, del nuevo [Bitmap](../../com.aspose.drawing/bitmap). |
| height | int | La altura, en píxeles, del nuevo [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | La enumeración `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) para el nuevo [Bitmap](../../com.aspose.drawing/bitmap). |

### Bitmap(int width, int height, int stride, int format, int[] data) {#Bitmap-int-int-int-int-int---}
```
public Bitmap(int width, int height, int stride, int format, int[] data)
```


Inicializa una nueva instancia de la clase [Bitmap](../../com.aspose.drawing/bitmap) con el tamaño y los datos de píxeles especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho, en píxeles, del nuevo [Bitmap](../../com.aspose.drawing/bitmap). |
| height | int | La altura, en píxeles, del nuevo [Bitmap](../../com.aspose.drawing/bitmap). |
| paso | int | El desplazamiento en bytes entre el comienzo de una línea de exploración y la siguiente, debe ser múltiplo de cuatro. |
| format | int | La enumeración `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) para el nuevo [Bitmap](../../com.aspose.drawing/bitmap). |
| datos | int[] | Los datos de píxeles. |

### Bitmap(Image original) {#Bitmap-com.aspose.drawing.Image-}
```
public Bitmap(Image original)
```


Inicializa una nueva instancia de la clase [Bitmap](../../com.aspose.drawing/bitmap) a partir de la imagen existente especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | La [Image](../../com.aspose.drawing/image) desde la cual crear el nuevo [Bitmap](../../com.aspose.drawing/bitmap). |

### Bitmap(Image original, Size newSize) {#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-}
```
public Bitmap(Image original, Size newSize)
```


Inicializa una nueva instancia de la clase [Bitmap](../../com.aspose.drawing/bitmap) a partir de la imagen existente especificada, escalada al tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | La [Image](../../com.aspose.drawing/image) desde la cual crear el nuevo [Bitmap](../../com.aspose.drawing/bitmap) |
| newSize | [Size](../../com.aspose.drawing/size) | La `Size`([Image.getSize](../../com.aspose.drawing/image\#getSize)) estructura que representa el tamaño del nuevo [Bitmap](../../com.aspose.drawing/bitmap). |

### Bitmap(Image original, int width, int height) {#Bitmap-com.aspose.drawing.Image-int-int-}
```
public Bitmap(Image original, int width, int height)
```


Inicializa una nueva instancia de la clase [Bitmap](../../com.aspose.drawing/bitmap) a partir de la imagen existente especificada, escalada al tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | La [Image](../../com.aspose.drawing/image) desde la cual crear el nuevo [Bitmap](../../com.aspose.drawing/bitmap). |
| width | int | El ancho, en píxeles, del nuevo [Bitmap](../../com.aspose.drawing/bitmap). |
| height | int | La altura, en píxeles, del nuevo [Bitmap](../../com.aspose.drawing/bitmap). |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene el ancho, en píxeles, de este Bitmap.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtiene la altura, en píxeles, de este Bitmap.

**Returns:**
int
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
### deepClone(Rectangle rect, int format) {#deepClone-com.aspose.drawing.Rectangle-int-}
```
public final Bitmap deepClone(Rectangle rect, int format)
```


Crea una copia de la sección de este [Bitmap](../../com.aspose.drawing/bitmap) definida por la estructura [Rectangle](../../com.aspose.drawing/rectangle) y con una enumeración `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Define la porción de este [Bitmap](../../com.aspose.drawing/bitmap) a copiar. Las coordenadas son relativas a este [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | Especifica la enumeración `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) para el [Bitmap](../../com.aspose.drawing/bitmap) de destino. |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The new [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### deepClone(RectangleF rect, int format) {#deepClone-com.aspose.drawing.RectangleF-int-}
```
public final Bitmap deepClone(RectangleF rect, int format)
```


Crea una copia de la sección de este [Bitmap](../../com.aspose.drawing/bitmap) definida con una enumeración [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Define la porción de este [Bitmap](../../com.aspose.drawing/bitmap) a copiar. |
| format | int | Especifica la enumeración [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) para el [Bitmap](../../com.aspose.drawing/bitmap) de destino. |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### setResolution(float xDpi, float yDpi) {#setResolution-float-float-}
```
public final void setResolution(float xDpi, float yDpi)
```


Establece la resolución para este [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xDpi | float | La resolución horizontal, en puntos por pulgada, del [Bitmap](../../com.aspose.drawing/bitmap). |
| yDpi | float | La resolución vertical, en puntos por pulgada, del [Bitmap](../../com.aspose.drawing/bitmap). |

### lockBits(Rectangle rect, int flags, int format) {#lockBits-com.aspose.drawing.Rectangle-int-int-}
```
public final BitmapData lockBits(Rectangle rect, int flags, int format)
```


Bloquea un [Bitmap](../../com.aspose.drawing/bitmap) en la memoria del sistema.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Una estructura [Rectangle](../../com.aspose.drawing/rectangle) que especifica la porción del [Bitmap](../../com.aspose.drawing/bitmap) a bloquear. |
| flags | int | Una enumeración [ImageLockMode](../../com.aspose.drawing.imaging/imagelockmode) que especifica el nivel de acceso (lectura/escritura) para el [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | Una enumeración `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) que especifica el formato de datos de este [Bitmap](../../com.aspose.drawing/bitmap). |

**Returns:**
[BitmapData](../../com.aspose.drawing.imaging/bitmapdata) - A [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) containing information about this lock operation.
### unlockBits(BitmapData bitmapData) {#unlockBits-com.aspose.drawing.imaging.BitmapData-}
```
public final void unlockBits(BitmapData bitmapData)
```


Desbloquea este [Bitmap](../../com.aspose.drawing/bitmap) de la memoria del sistema.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitmapData | [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) | Un [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) que especifica información sobre la operación de bloqueo. |

### getPixel(int x, int y) {#getPixel-int-int-}
```
public final Color getPixel(int x, int y)
```


Obtiene el color del píxel especificado en este [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del píxel a recuperar. |
| y | int | La coordenada y del píxel a recuperar. |

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) structure that represents the color of the specified pixel.
### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.drawing.Color-}
```
public final void setPixel(int x, int y, Color color)
```


Establece el color del píxel especificado en este [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del píxel a establecer. |
| y | int | La coordenada y del píxel a establecer. |
| color | [Color](../../com.aspose.drawing/color) | Una estructura [Color](../../com.aspose.drawing/color) que representa el color a asignar al píxel especificado. |

### readArgb32Pixels(int[] pixels) {#readArgb32Pixels-int---}
```
public final void readArgb32Pixels(int[] pixels)
```


Lee los píxeles del bitmap en formato ARGB32 en la matriz proporcionada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| píxeles | int[] | Arreglo para colocar píxeles de mapa de bits. Debe tener suficiente capacidad. |

### writeArgb32Pixels(int[] pixels) {#writeArgb32Pixels-int---}
```
public final void writeArgb32Pixels(int[] pixels)
```


Escribe píxeles en el bitmap.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| píxeles | int[] | Arreglo con píxeles de origen en formato ARGB32. Debe tener suficiente longitud. |

### makeTransparent() {#makeTransparent--}
```
public final void makeTransparent()
```


Hace que el color especificado sea transparente para este [Bitmap](../../com.aspose.drawing/bitmap).

### makeTransparent(Color transparentColor) {#makeTransparent-com.aspose.drawing.Color-}
```
public final void makeTransparent(Color transparentColor)
```


Hace que el color especificado sea transparente para este [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| transparentColor | [Color](../../com.aspose.drawing/color) | La estructura [Color](../../com.aspose.drawing/color) que representa el color a hacer transparente. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Este método rota, voltea o rota y voltea el [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rotateFlipType | int | Un miembro [RotateFlipType](../../com.aspose.drawing/rotatefliptype) que especifica el tipo de rotación y volteo a aplicar a la imagen. |

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

