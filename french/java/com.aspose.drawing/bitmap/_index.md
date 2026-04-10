---
title: Bitmap
second_title: Référence de l'API Aspose.Drawing pour Java
description: Encapsule un bitmap qui comprend les données de pixels d'une image graphique et ses attributs.
type: docs
weight: 10
url: /fr/java/com.aspose.drawing/bitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public class Bitmap extends Image
```

Encapsule un bitmap, qui comprend les données de pixels d'une image graphique et ses attributs. Un [Bitmap](../../com.aspose.drawing/bitmap) est un objet utilisé pour travailler avec des images définies par des données de pixels.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Bitmap(int width, int height)](#Bitmap-int-int-) | Initialise une nouvelle instance de la classe [Bitmap](../../com.aspose.drawing/bitmap) avec la taille spécifiée. |
| [Bitmap(String filename)](#Bitmap-java.lang.String-) | Initialise une nouvelle instance de la classe [Bitmap](../../com.aspose.drawing/bitmap) à partir du fichier spécifié. |
| [Bitmap(String filename, boolean useIcm)](#Bitmap-java.lang.String-boolean-) | Initialise une nouvelle instance de la classe [Bitmap](../../com.aspose.drawing/bitmap) à partir du fichier spécifié. |
| [Bitmap(InputStream stream)](#Bitmap-java.io.InputStream-) | Initialise une nouvelle instance de la classe [Bitmap](../../com.aspose.drawing/bitmap) à partir du flux de données spécifié. |
| [Bitmap(InputStream stream, boolean useIcm)](#Bitmap-java.io.InputStream-boolean-) | Initialise une nouvelle instance de la classe [Bitmap](../../com.aspose.drawing/bitmap) à partir du flux de données spécifié. |
| [Bitmap(int width, int height, int format)](#Bitmap-int-int-int-) | Initialise une nouvelle instance de la classe [Bitmap](../../com.aspose.drawing/bitmap) avec la taille et le format spécifiés. |
| [Bitmap(int width, int height, int stride, int format, int[] data)](#Bitmap-int-int-int-int-int---) | Initialise une nouvelle instance de la classe [Bitmap](../../com.aspose.drawing/bitmap) avec la taille et les données de pixels spécifiées. |
| [Bitmap(Image original)](#Bitmap-com.aspose.drawing.Image-) | Initialise une nouvelle instance de la classe [Bitmap](../../com.aspose.drawing/bitmap) à partir de l'image existante spécifiée. |
| [Bitmap(Image original, Size newSize)](#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-) | Initialise une nouvelle instance de la classe [Bitmap](../../com.aspose.drawing/bitmap) à partir de l'image existante spécifiée, mise à l'échelle à la taille indiquée. |
| [Bitmap(Image original, int width, int height)](#Bitmap-com.aspose.drawing.Image-int-int-) | Initialise une nouvelle instance de la classe [Bitmap](../../com.aspose.drawing/bitmap) à partir de l'image existante spécifiée, mise à l'échelle à la taille indiquée. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Obtient la largeur, en pixels, de ce Bitmap. |
| [getHeight()](#getHeight--) | Obtient la hauteur, en pixels, de ce Bitmap. |
| [getRawFormat()](#getRawFormat--) | Obtient le format de fichier de cette [Image](../../com.aspose.drawing/image). |
| [getPixelFormat()](#getPixelFormat--) | Obtient le format de pixel de cette [Image](../../com.aspose.drawing/image). |
| [getPalette()](#getPalette--) | Obtient ou définit la palette de couleurs utilisée pour cette [Image](../../com.aspose.drawing/image). |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | Obtient ou définit la palette de couleurs utilisée pour cette [Image](../../com.aspose.drawing/image). |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | Obtient un tableau de GUID qui représentent les dimensions des images dans cette [Image](../../com.aspose.drawing/image). |
| [getPropertyIdList()](#getPropertyIdList--) | Obtient les ID des éléments de propriété stockés dans cette [Image](../../com.aspose.drawing/image). |
| [getPropertyItems()](#getPropertyItems--) | Obtient tous les éléments de propriété (métadonnées) stockés dans cette [Image](../../com.aspose.drawing/image). |
| [deepClone(Rectangle rect, int format)](#deepClone-com.aspose.drawing.Rectangle-int-) | Crée une copie de la section de ce [Bitmap](../../com.aspose.drawing/bitmap) définie par la structure [Rectangle](../../com.aspose.drawing/rectangle) et avec une énumération `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) spécifiée. |
| [deepClone(RectangleF rect, int format)](#deepClone-com.aspose.drawing.RectangleF-int-) | Crée une copie de la section de ce [Bitmap](../../com.aspose.drawing/bitmap) définie avec une énumération [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) spécifiée. |
| [setResolution(float xDpi, float yDpi)](#setResolution-float-float-) | Définit la résolution de ce [Bitmap](../../com.aspose.drawing/bitmap). |
| [lockBits(Rectangle rect, int flags, int format)](#lockBits-com.aspose.drawing.Rectangle-int-int-) | Verrouille un [Bitmap](../../com.aspose.drawing/bitmap) en mémoire système. |
| [unlockBits(BitmapData bitmapData)](#unlockBits-com.aspose.drawing.imaging.BitmapData-) | Déverrouille ce [Bitmap](../../com.aspose.drawing/bitmap) de la mémoire système. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Obtient la couleur du pixel spécifié dans ce [Bitmap](../../com.aspose.drawing/bitmap). |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.drawing.Color-) | Définit la couleur du pixel spécifié dans ce [Bitmap](../../com.aspose.drawing/bitmap). |
| [readArgb32Pixels(int[] pixels)](#readArgb32Pixels-int---) | Lit les pixels du bitmap au format ARGB32 dans le tableau fourni. |
| [writeArgb32Pixels(int[] pixels)](#writeArgb32Pixels-int---) | Écrit les pixels dans le bitmap. |
| [makeTransparent()](#makeTransparent--) | Rend la couleur spécifiée transparente pour ce [Bitmap](../../com.aspose.drawing/bitmap). |
| [makeTransparent(Color transparentColor)](#makeTransparent-com.aspose.drawing.Color-) | Rend la couleur spécifiée transparente pour ce [Bitmap](../../com.aspose.drawing/bitmap). |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Cette méthode fait pivoter, retourner ou faire pivoter et retourner l'[Image](../../com.aspose.drawing/image). |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | Obtient l'élément de propriété spécifié de cette [Image](../../com.aspose.drawing/image). |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | Supprime l'élément de propriété spécifié de cette [Image](../../com.aspose.drawing/image). |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | Stocke un élément de propriété (métadonnée) dans cette [Image](../../com.aspose.drawing/image). |
### Bitmap(int width, int height) {#Bitmap-int-int-}
```
public Bitmap(int width, int height)
```


Initialise une nouvelle instance de la classe [Bitmap](../../com.aspose.drawing/bitmap) avec la taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur | int | La largeur, en pixels, du nouveau Bitmap. |
|  | hauteur | int | La hauteur, en pixels, du nouveau Bitmap. |

--------------------

Le seul format interne de bitmap pris en charge pour le moment est équivalent à `PixelFormat.Format32bppPArgb`. |

### Bitmap(String filename) {#Bitmap-java.lang.String-}
```
public Bitmap(String filename)
```


Initialise une nouvelle instance de la classe [Bitmap](../../com.aspose.drawing/bitmap) à partir du fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom de fichier | java.lang.String | Le nom du fichier bitmap. |

### Bitmap(String filename, boolean useIcm) {#Bitmap-java.lang.String-boolean-}
```
public Bitmap(String filename, boolean useIcm)
```


Initialise une nouvelle instance de la classe [Bitmap](../../com.aspose.drawing/bitmap) à partir du fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom de fichier | java.lang.String | Le nom du fichier bitmap. |
| useIcm | boolean | true pour utiliser la correction des couleurs pour ce [Bitmap](../../com.aspose.drawing/bitmap) ; sinon, false. |

### Bitmap(InputStream stream) {#Bitmap-java.io.InputStream-}
```
public Bitmap(InputStream stream)
```


Initialise une nouvelle instance de la classe [Bitmap](../../com.aspose.drawing/bitmap) à partir du flux de données spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux de données utilisé pour charger l'image. |

### Bitmap(InputStream stream, boolean useIcm) {#Bitmap-java.io.InputStream-boolean-}
```
public Bitmap(InputStream stream, boolean useIcm)
```


Initialise une nouvelle instance de la classe [Bitmap](../../com.aspose.drawing/bitmap) à partir du flux de données spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux de données utilisé pour charger l'image. |
| useIcm | boolean | `true` pour utiliser la correction des couleurs pour ce [Bitmap](../../com.aspose.drawing/bitmap) ; sinon, `false`. |

### Bitmap(int width, int height, int format) {#Bitmap-int-int-int-}
```
public Bitmap(int width, int height, int format)
```


Initialise une nouvelle instance de la classe [Bitmap](../../com.aspose.drawing/bitmap) avec la taille et le format spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur, en pixels, du nouveau [Bitmap](../../com.aspose.drawing/bitmap). |
| height | int | La hauteur, en pixels, du nouveau [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | L'énumération `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) pour le nouveau [Bitmap](../../com.aspose.drawing/bitmap). |

### Bitmap(int width, int height, int stride, int format, int[] data) {#Bitmap-int-int-int-int-int---}
```
public Bitmap(int width, int height, int stride, int format, int[] data)
```


Initialise une nouvelle instance de la classe [Bitmap](../../com.aspose.drawing/bitmap) avec la taille et les données de pixels spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur, en pixels, du nouveau [Bitmap](../../com.aspose.drawing/bitmap). |
| height | int | La hauteur, en pixels, du nouveau [Bitmap](../../com.aspose.drawing/bitmap). |
| pas | int | Le décalage en octets entre le début d'une ligne de balayage et la suivante doit être un multiple de quatre. |
| format | int | L'énumération `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) pour le nouveau [Bitmap](../../com.aspose.drawing/bitmap). |
| données | int[] | Les données du pixel. |

### Bitmap(Image original) {#Bitmap-com.aspose.drawing.Image-}
```
public Bitmap(Image original)
```


Initialise une nouvelle instance de la classe [Bitmap](../../com.aspose.drawing/bitmap) à partir de l'image existante spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | L'[Image](../../com.aspose.drawing/image) à partir de laquelle créer le nouveau [Bitmap](../../com.aspose.drawing/bitmap). |

### Bitmap(Image original, Size newSize) {#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-}
```
public Bitmap(Image original, Size newSize)
```


Initialise une nouvelle instance de la classe [Bitmap](../../com.aspose.drawing/bitmap) à partir de l'image existante spécifiée, mise à l'échelle à la taille indiquée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | L'[Image](../../com.aspose.drawing/image) à partir de laquelle créer le nouveau [Bitmap](../../com.aspose.drawing/bitmap) |
| newSize | [Size](../../com.aspose.drawing/size) | La structure `Size`([Image.getSize](../../com.aspose.drawing/image\#getSize)) qui représente la taille du nouveau [Bitmap](../../com.aspose.drawing/bitmap). |

### Bitmap(Image original, int width, int height) {#Bitmap-com.aspose.drawing.Image-int-int-}
```
public Bitmap(Image original, int width, int height)
```


Initialise une nouvelle instance de la classe [Bitmap](../../com.aspose.drawing/bitmap) à partir de l'image existante spécifiée, mise à l'échelle à la taille indiquée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | L'[Image](../../com.aspose.drawing/image) à partir de laquelle créer le nouveau [Bitmap](../../com.aspose.drawing/bitmap). |
| width | int | La largeur, en pixels, du nouveau [Bitmap](../../com.aspose.drawing/bitmap). |
| height | int | La hauteur, en pixels, du nouveau [Bitmap](../../com.aspose.drawing/bitmap). |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient la largeur, en pixels, de ce Bitmap.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtient la hauteur, en pixels, de ce Bitmap.

**Returns:**
int
### getRawFormat() {#getRawFormat--}
```
public ImageFormat getRawFormat()
```


Obtient le format de fichier de cette [Image](../../com.aspose.drawing/image).

**Returns:**
[ImageFormat](../../com.aspose.drawing.imaging/imageformat) - The [ImageFormat](../../com.aspose.drawing.imaging/imageformat) that represents the file format of this [Image](../../com.aspose.drawing/image).
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Obtient le format de pixel de cette [Image](../../com.aspose.drawing/image).

**Returns:**
int - Un `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) qui représente le format de pixel pour cette [Image](../../com.aspose.drawing/image).
### getPalette() {#getPalette--}
```
public ColorPalette getPalette()
```


Obtient ou définit la palette de couleurs utilisée pour cette [Image](../../com.aspose.drawing/image).

**Returns:**
[ColorPalette](../../com.aspose.drawing.imaging/colorpalette) - A [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) that represents the color palette used for this [Image](../../com.aspose.drawing/image).
### setPalette(ColorPalette value) {#setPalette-com.aspose.drawing.imaging.ColorPalette-}
```
public void setPalette(ColorPalette value)
```


Obtient ou définit la palette de couleurs utilisée pour cette [Image](../../com.aspose.drawing/image).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) |  |

### getFrameDimensionsList() {#getFrameDimensionsList--}
```
public UUID[] getFrameDimensionsList()
```


Obtient un tableau de GUID qui représentent les dimensions des images dans cette [Image](../../com.aspose.drawing/image).

**Returns:**
java.util.UUID[] - Un tableau de GUID qui spécifient les dimensions des images dans cette [Image](../../com.aspose.drawing/image) du plus significatif au moins significatif.
### getPropertyIdList() {#getPropertyIdList--}
```
public int[] getPropertyIdList()
```


Obtient les ID des éléments de propriété stockés dans cette [Image](../../com.aspose.drawing/image).

**Returns:**
int[] - Un tableau des identifiants de propriétés, un pour chaque élément de propriété stocké dans cette image.
### getPropertyItems() {#getPropertyItems--}
```
public PropertyItem[] getPropertyItems()
```


Obtient tous les éléments de propriété (métadonnées) stockés dans cette [Image](../../com.aspose.drawing/image).

**Returns:**
com.aspose.drawing.imaging.PropertyItem[] - Un tableau d'objets [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) , un pour chaque élément de propriété stocké dans l'image.
### deepClone(Rectangle rect, int format) {#deepClone-com.aspose.drawing.Rectangle-int-}
```
public final Bitmap deepClone(Rectangle rect, int format)
```


Crée une copie de la section de ce [Bitmap](../../com.aspose.drawing/bitmap) définie par la structure [Rectangle](../../com.aspose.drawing/rectangle) et avec une énumération `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Définit la partie de ce [Bitmap](../../com.aspose.drawing/bitmap) à copier. Les coordonnées sont relatives à ce [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | Spécifie l'énumération `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) pour le [Bitmap](../../com.aspose.drawing/bitmap) de destination. |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The new [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### deepClone(RectangleF rect, int format) {#deepClone-com.aspose.drawing.RectangleF-int-}
```
public final Bitmap deepClone(RectangleF rect, int format)
```


Crée une copie de la section de ce [Bitmap](../../com.aspose.drawing/bitmap) définie avec une énumération [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Définit la partie de ce [Bitmap](../../com.aspose.drawing/bitmap) à copier. |
| format | int | Spécifie l'énumération [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) pour le [Bitmap](../../com.aspose.drawing/bitmap) de destination. |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### setResolution(float xDpi, float yDpi) {#setResolution-float-float-}
```
public final void setResolution(float xDpi, float yDpi)
```


Définit la résolution de ce [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xDpi | float | La résolution horizontale, en points par pouce, du [Bitmap](../../com.aspose.drawing/bitmap). |
| yDpi | float | La résolution verticale, en points par pouce, du [Bitmap](../../com.aspose.drawing/bitmap). |

### lockBits(Rectangle rect, int flags, int format) {#lockBits-com.aspose.drawing.Rectangle-int-int-}
```
public final BitmapData lockBits(Rectangle rect, int flags, int format)
```


Verrouille un [Bitmap](../../com.aspose.drawing/bitmap) en mémoire système.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Une structure [Rectangle](../../com.aspose.drawing/rectangle) spécifiant la partie du [Bitmap](../../com.aspose.drawing/bitmap) à verrouiller. |
| flags | int | Une énumération [ImageLockMode](../../com.aspose.drawing.imaging/imagelockmode) spécifiant le niveau d'accès (lecture/écriture) pour le [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | Une énumération `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) spécifiant le format de données de ce [Bitmap](../../com.aspose.drawing/bitmap). |

**Returns:**
[BitmapData](../../com.aspose.drawing.imaging/bitmapdata) - A [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) containing information about this lock operation.
### unlockBits(BitmapData bitmapData) {#unlockBits-com.aspose.drawing.imaging.BitmapData-}
```
public final void unlockBits(BitmapData bitmapData)
```


Déverrouille ce [Bitmap](../../com.aspose.drawing/bitmap) de la mémoire système.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitmapData | [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) | Un [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) spécifiant les informations sur l'opération de verrouillage. |

### getPixel(int x, int y) {#getPixel-int-int-}
```
public final Color getPixel(int x, int y)
```


Obtient la couleur du pixel spécifié dans ce [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du pixel à récupérer. |
| y | int | La coordonnée y du pixel à récupérer. |

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) structure that represents the color of the specified pixel.
### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.drawing.Color-}
```
public final void setPixel(int x, int y, Color color)
```


Définit la couleur du pixel spécifié dans ce [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du pixel à définir. |
| y | int | La coordonnée y du pixel à définir. |
| color | [Color](../../com.aspose.drawing/color) | Une structure [Color](../../com.aspose.drawing/color) qui représente la couleur à attribuer au pixel spécifié. |

### readArgb32Pixels(int[] pixels) {#readArgb32Pixels-int---}
```
public final void readArgb32Pixels(int[] pixels)
```


Lit les pixels du bitmap au format ARGB32 dans le tableau fourni.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | int[] | Tableau pour placer les pixels du bitmap. Doit avoir une capacité suffisante. |

### writeArgb32Pixels(int[] pixels) {#writeArgb32Pixels-int---}
```
public final void writeArgb32Pixels(int[] pixels)
```


Écrit les pixels dans le bitmap.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | int[] | Tableau contenant les pixels source au format ARGB32. Doit avoir une longueur suffisante. |

### makeTransparent() {#makeTransparent--}
```
public final void makeTransparent()
```


Rend la couleur spécifiée transparente pour ce [Bitmap](../../com.aspose.drawing/bitmap).

### makeTransparent(Color transparentColor) {#makeTransparent-com.aspose.drawing.Color-}
```
public final void makeTransparent(Color transparentColor)
```


Rend la couleur spécifiée transparente pour ce [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| transparentColor | [Color](../../com.aspose.drawing/color) | La structure [Color](../../com.aspose.drawing/color) qui représente la couleur à rendre transparente. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Cette méthode fait pivoter, retourner ou faire pivoter et retourner l'[Image](../../com.aspose.drawing/image).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | Un membre [RotateFlipType](../../com.aspose.drawing/rotatefliptype) qui spécifie le type de rotation et de retournement à appliquer à l'image. |

### getPropertyItem(int propid) {#getPropertyItem-int-}
```
public PropertyItem getPropertyItem(int propid)
```


Obtient l'élément de propriété spécifié de cette [Image](../../com.aspose.drawing/image).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propid | int | L'ID de l'élément de propriété à obtenir. |

**Returns:**
[PropertyItem](../../com.aspose.drawing.imaging/propertyitem) - The [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) this method gets.
### removePropertyItem(int propid) {#removePropertyItem-int-}
```
public void removePropertyItem(int propid)
```


Supprime l'élément de propriété spécifié de cette [Image](../../com.aspose.drawing/image).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propid | int | L'ID de l'élément de propriété à supprimer. |

### setPropertyItem(PropertyItem propitem) {#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-}
```
public void setPropertyItem(PropertyItem propitem)
```


Stocke un élément de propriété (métadonnée) dans cette [Image](../../com.aspose.drawing/image).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propitem | [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) | Le [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) à stocker. |

