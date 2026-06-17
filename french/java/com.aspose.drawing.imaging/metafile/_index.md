---
title: Metafile
second_title: Référence de l'API Aspose.Drawing pour Java
description: Définit un métafichier graphique.
type: docs
weight: 30
url: /fr/java/com.aspose.drawing.imaging/metafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public final class Metafile extends Image
```

Définit un fichier méta graphique. Un fichier méta contient des enregistrements qui décrivent une séquence d'opérations graphiques pouvant être enregistrées (construites) et rejouées (affichées). Cette classe n'est pas héritable.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Metafile(byte[] henhmetafile, boolean deleteEmf)](#Metafile-byte---boolean-) | Initialise une nouvelle instance de la classe [Metafile](../../com.aspose.drawing.imaging/metafile) à partir du handle spécifié. |
| [Metafile(byte[] referenceHdc, int emfType)](#Metafile-byte---int-) | Initialise une nouvelle instance de la classe [Metafile](../../com.aspose.drawing.imaging/metafile) à partir du handle spécifié vers un contexte de périphérique et d'une énumération [EmfType](../../com.aspose.drawing.imaging/emftype) qui spécifie le format du [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [Metafile(String filename)](#Metafile-java.lang.String-) | Initialise une nouvelle instance de la classe [Metafile](../../com.aspose.drawing.imaging/metafile) à partir du nom de fichier spécifié. |
| [Metafile(String filename, byte[] referenceHdc)](#Metafile-java.lang.String-byte---) | Initialise une nouvelle instance de la classe [Metafile](../../com.aspose.drawing.imaging/metafile) à partir du nom de fichier spécifié. |
| [Metafile(InputStream stream)](#Metafile-java.io.InputStream-) | Initialise une nouvelle instance de la classe [Metafile](../../com.aspose.drawing.imaging/metafile) à partir du flux de données spécifié. |
| [Metafile(InputStream stream, byte[] referenceHdc)](#Metafile-java.io.InputStream-byte---) | Initialise une nouvelle instance de la classe [Metafile](../../com.aspose.drawing.imaging/metafile) à partir du flux de données spécifié et d'un handle Windows vers un contexte de périphérique. |
| [Metafile(System.IO.Stream stream, int type)](#Metafile-com.aspose.ms.System.IO.Stream-int-) | Initialise une nouvelle instance de la classe [Metafile](../../com.aspose.drawing.imaging/metafile) à partir du flux de données spécifié et d'un handle Windows vers un contexte de périphérique. |
| [Metafile(InputStream stream, byte[] referenceHdc, int type)](#Metafile-java.io.InputStream-byte---int-) | Initialise une nouvelle instance de la classe [Metafile](../../com.aspose.drawing.imaging/metafile) à partir du flux de données spécifié, d'un handle Windows vers un contexte de périphérique et d'une énumération [EmfType](../../com.aspose.drawing.imaging/emftype) qui spécifie le format du [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)](#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-) | Initialise une nouvelle instance de la classe [Metafile](../../com.aspose.drawing.imaging/metafile) à partir du flux de données spécifié, d'un handle Windows vers un contexte de périphérique et d'une énumération [EmfType](../../com.aspose.drawing.imaging/emftype) qui spécifie le format du [Metafile](../../com.aspose.drawing.imaging/metafile). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Obtient la largeur, en pixels, de ce [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getHeight()](#getHeight--) | Obtient la hauteur, en pixels, de ce [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getRawFormat()](#getRawFormat--) | Obtient le format de fichier de cette [Image](../../com.aspose.drawing/image). |
| [getPixelFormat()](#getPixelFormat--) | Obtient le format de pixel de cette [Image](../../com.aspose.drawing/image). |
| [getPalette()](#getPalette--) | Obtient ou définit la palette de couleurs utilisée pour cette [Image](../../com.aspose.drawing/image). |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | Obtient ou définit la palette de couleurs utilisée pour cette [Image](../../com.aspose.drawing/image). |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | Obtient un tableau de GUID qui représentent les dimensions des images dans cette [Image](../../com.aspose.drawing/image). |
| [getPropertyIdList()](#getPropertyIdList--) | Obtient les ID des éléments de propriété stockés dans cette [Image](../../com.aspose.drawing/image). |
| [getPropertyItems()](#getPropertyItems--) | Obtient tous les éléments de propriété (métadonnées) stockés dans cette [Image](../../com.aspose.drawing/image). |
| [getMetafileHeader(InputStream stream)](#getMetafileHeader-java.io.InputStream-) | Renvoie le [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associé au [Metafile](../../com.aspose.drawing.imaging/metafile) spécifié. |
| [getMetafileHeader(String fileName)](#getMetafileHeader-java.lang.String-) | Renvoie le [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associé au [Metafile](../../com.aspose.drawing.imaging/metafile) spécifié. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Cette méthode fait pivoter, retourner ou faire pivoter et retourner l'[Image](../../com.aspose.drawing/image). |
| [getHenhmetafile()](#getHenhmetafile--) | Renvoie un handle Windows vers un [Metafile](../../com.aspose.drawing.imaging/metafile) amélioré. |
| [playRecord(int recordType, int flags, int dataSize, byte[] dataArray)](#playRecord-int-int-int-byte---) | Exécute un enregistrement de fichier méta individuel. |
| [getMetafileHeader()](#getMetafileHeader--) | Renvoie le [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associé à ce [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | Obtient l'élément de propriété spécifié de cette [Image](../../com.aspose.drawing/image). |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | Supprime l'élément de propriété spécifié de cette [Image](../../com.aspose.drawing/image). |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | Stocke un élément de propriété (métadonnée) dans cette [Image](../../com.aspose.drawing/image). |
### Metafile(byte[] henhmetafile, boolean deleteEmf) {#Metafile-byte---boolean-}
```
public Metafile(byte[] henhmetafile, boolean deleteEmf)
```


Initialise une nouvelle instance de la classe [Metafile](../../com.aspose.drawing.imaging/metafile) à partir du handle spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| henhmetafile | byte[] | Une poignée d'un métafichier amélioré. |
| deleteEmf | boolean | true pour supprimer la poignée du métafichier amélioré lorsque le [Metafile](../../com.aspose.drawing.imaging/metafile) est supprimé ; sinon, false. |

### Metafile(byte[] referenceHdc, int emfType) {#Metafile-byte---int-}
```
public Metafile(byte[] referenceHdc, int emfType)
```


Initialise une nouvelle instance de la classe [Metafile](../../com.aspose.drawing.imaging/metafile) à partir du handle spécifié vers un contexte de périphérique et d'une énumération [EmfType](../../com.aspose.drawing.imaging/emftype) qui spécifie le format du [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| referenceHdc | byte[] | La poignée d'un contexte de périphérique. |
| emfType | int | Un [EmfType](../../com.aspose.drawing.imaging/emftype) qui spécifie le format du [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(String filename) {#Metafile-java.lang.String-}
```
public Metafile(String filename)
```


Initialise une nouvelle instance de la classe [Metafile](../../com.aspose.drawing.imaging/metafile) à partir du nom de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | Une chaîne qui représente le nom de fichier à partir duquel créer le nouveau [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(String filename, byte[] referenceHdc) {#Metafile-java.lang.String-byte---}
```
public Metafile(String filename, byte[] referenceHdc)
```


Initialise une nouvelle instance de la classe [Metafile](../../com.aspose.drawing.imaging/metafile) à partir du nom de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | Une chaîne qui représente le nom de fichier à partir duquel créer le nouveau [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Une poignée Windows vers un contexte de périphérique. |

### Metafile(InputStream stream) {#Metafile-java.io.InputStream-}
```
public Metafile(InputStream stream)
```


Initialise une nouvelle instance de la classe [Metafile](../../com.aspose.drawing.imaging/metafile) à partir du flux de données spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Le InputStream à partir duquel créer le nouveau [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(InputStream stream, byte[] referenceHdc) {#Metafile-java.io.InputStream-byte---}
```
public Metafile(InputStream stream, byte[] referenceHdc)
```


Initialise une nouvelle instance de la classe [Metafile](../../com.aspose.drawing.imaging/metafile) à partir du flux de données spécifié et d'une poignée Windows vers un contexte de périphérique. />.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Un InputStream qui contient les données de ce [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Une poignée Windows vers un contexte de périphérique de l'objet [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(System.IO.Stream stream, int type) {#Metafile-com.aspose.ms.System.IO.Stream-int-}
```
public Metafile(System.IO.Stream stream, int type)
```


Initialise une nouvelle instance de la classe [Metafile](../../com.aspose.drawing.imaging/metafile) à partir du flux de données spécifié et d'une poignée Windows vers un contexte de périphérique. />.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Un InputStream qui contient les données de ce [Metafile](../../com.aspose.drawing.imaging/metafile). |
| type | int | doit être int 1. |

### Metafile(InputStream stream, byte[] referenceHdc, int type) {#Metafile-java.io.InputStream-byte---int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, int type)
```


Initialise une nouvelle instance de la classe [Metafile](../../com.aspose.drawing.imaging/metafile) à partir du flux de données spécifié, d'un handle Windows vers un contexte de périphérique et d'une énumération [EmfType](../../com.aspose.drawing.imaging/emftype) qui spécifie le format du [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Un InputStream qui contient les données de ce [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Une poignée Windows vers un contexte de périphérique. |
| type | int | Un [EmfType](../../com.aspose.drawing.imaging/emftype) qui spécifie le format du [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type) {#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)
```


Initialise une nouvelle instance de la classe [Metafile](../../com.aspose.drawing.imaging/metafile) à partir du flux de données spécifié, d'un handle Windows vers un contexte de périphérique et d'une énumération [EmfType](../../com.aspose.drawing.imaging/emftype) qui spécifie le format du [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Un InputStream qui contient les données de ce [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Une poignée Windows vers un contexte de périphérique. |
| frameRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Un [Rectangle](../../com.aspose.drawing/rectangle) qui représente le rectangle qui délimite le nouveau [Metafile](../../com.aspose.drawing.imaging/metafile). |
| frameUnit | int | Un [MetafileFrameUnit](../../com.aspose.drawing.imaging/metafileframeunit) qui spécifie l'unité de mesure pour frameRect. |
| type | int | Un [EmfType](../../com.aspose.drawing.imaging/emftype) qui spécifie le format du [Metafile](../../com.aspose.drawing.imaging/metafile). |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient la largeur, en pixels, de ce [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtient la hauteur, en pixels, de ce [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
int - la hauteur, en pixels, de ce [Metafile](../../com.aspose.drawing.imaging/metafile).
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
### getMetafileHeader(InputStream stream) {#getMetafileHeader-java.io.InputStream-}
```
public static MetafileHeader getMetafileHeader(InputStream stream)
```


Renvoie le [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associé au [Metafile](../../com.aspose.drawing.imaging/metafile) spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Un InputStream contenant le [Metafile](../../com.aspose.drawing.imaging/metafile) pour lequel un en-tête est récupéré. |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### getMetafileHeader(String fileName) {#getMetafileHeader-java.lang.String-}
```
public static MetafileHeader getMetafileHeader(String fileName)
```


Renvoie le [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associé au [Metafile](../../com.aspose.drawing.imaging/metafile) spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Une chaîne contenant le nom du [Metafile](../../com.aspose.drawing.imaging/metafile) pour lequel un en-tête est récupéré. |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Cette méthode fait pivoter, retourner ou faire pivoter et retourner l'[Image](../../com.aspose.drawing/image).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | Un membre [RotateFlipType](../../com.aspose.drawing/rotatefliptype) qui spécifie le type de rotation et de retournement à appliquer à l'image. |

### getHenhmetafile() {#getHenhmetafile--}
```
public System.IntPtr getHenhmetafile()
```


Renvoie un handle Windows vers un [Metafile](../../com.aspose.drawing.imaging/metafile) amélioré.

**Returns:**
com.aspose.ms.System.IntPtr - Une poignée Windows vers ce [Metafile](../../com.aspose.drawing.imaging/metafile) amélioré.
### playRecord(int recordType, int flags, int dataSize, byte[] dataArray) {#playRecord-int-int-int-byte---}
```
public void playRecord(int recordType, int flags, int dataSize, byte[] dataArray)
```


Exécute un enregistrement de fichier méta individuel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recordType | int | Élément du [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype) qui spécifie le type d'enregistrement de métafichier en cours de lecture. |
| flags | int | Ensemble de drapeaux qui spécifient les attributs de l'enregistrement. |
| dataSize | int | Le nombre d'octets dans les données de l'enregistrement. |
| dataArray | byte[] | Un tableau d'octets qui contient les données de l'enregistrement. |

### getMetafileHeader() {#getMetafileHeader--}
```
public MetafileHeader getMetafileHeader()
```


Renvoie le [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associé à ce [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with this [Metafile](../../com.aspose.drawing.imaging/metafile).
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

