---
title: Icon
second_title: Référence de l'API Aspose.Drawing pour Java
description: Représente une icône Windows qui est une petite image bitmap utilisée pour représenter un objet.
type: docs
weight: 29
url: /fr/java/com.aspose.drawing/icon/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.ms.System.IDisposable
```
public final class Icon implements System.ICloneable, System.IDisposable
```

Représente une icône Windows, qui est une petite image bitmap utilisée pour représenter un objet. Les icônes peuvent être considérées comme des bitmaps transparents, bien que leur taille soit déterminée par le système.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Icon(String fileName)](#Icon-java.lang.String-) | Initialise une nouvelle instance de la classe [Icon](../../com.aspose.drawing/icon) à partir du nom de fichier spécifié. |
| [Icon(InputStream stream)](#Icon-java.io.InputStream-) | Initialise une nouvelle instance de la classe [Icon](../../com.aspose.drawing/icon) à partir du flux de données spécifié. |
| [Icon(String fileName, Size size)](#Icon-java.lang.String-com.aspose.drawing.Size-) | Initialise une nouvelle instance de la classe [Icon](../../com.aspose.drawing/icon) de la taille spécifiée à partir du fichier spécifié. |
| [Icon(Icon original, Size size)](#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-) | Initialise une nouvelle instance de la classe [Icon](../../com.aspose.drawing/icon) et tente de trouver une version de l'icône correspondant à la taille demandée. |
| [Icon(Object type, String resource)](#Icon-java.lang.Object-java.lang.String-) | Initialise une nouvelle instance de la classe [Icon](../../com.aspose.drawing/icon) à partir d'une ressource dans l'assembly spécifié. |
| [Icon(InputStream stream, Size size)](#Icon-java.io.InputStream-com.aspose.drawing.Size-) | Initialise une nouvelle instance de la classe [Icon](../../com.aspose.drawing/icon) de la taille spécifiée à partir du flux spécifié. |
| [Icon(String fileName, int width, int height)](#Icon-java.lang.String-int-int-) | Initialise une nouvelle instance de la classe [Icon](../../com.aspose.drawing/icon) avec la largeur et la hauteur spécifiées à partir du fichier spécifié. |
| [Icon(Icon original, int width, int height)](#Icon-com.aspose.drawing.Icon-int-int-) | Initialise une nouvelle instance de la classe [Icon](../../com.aspose.drawing/icon) et tente de trouver une version de l’icône correspondant à la taille demandée.. |
| [Icon(InputStream stream, int width, int height)](#Icon-java.io.InputStream-int-int-) | Initialise une nouvelle instance de la classe [Icon](../../com.aspose.drawing/icon) à partir du flux de données spécifié et avec la largeur et la hauteur spécifiées. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHandle()](#getHandle--) | Obtient le handle de cet [Icon](../../com.aspose.drawing/icon). |
| [getHeight()](#getHeight--) | Obtient la hauteur de cet [Icon](../../com.aspose.drawing/icon). |
| [getSize()](#getSize--) | Obtient la taille de cet [Icon](../../com.aspose.drawing/icon). |
| [getWidth()](#getWidth--) | Obtient la largeur de cet [Icon](../../com.aspose.drawing/icon). |
| [extractAssociatedIcon(String filePath)](#extractAssociatedIcon-java.lang.String-) | Renvoie une représentation icône d’une image contenue dans le fichier spécifié. |
| [fromHandle(byte[] handle)](#fromHandle-byte---) | Crée un [Icon](../../com.aspose.drawing/icon) GDI+ à partir du handle Windows spécifié vers une icône (HICON). |
| [deepClone()](#deepClone--) | Clone le [Icon](../../com.aspose.drawing/icon), créant une image dupliquée. |
| [dispose()](#dispose--) | Effectue les tâches définies par l'application associées à la libération, la remise ou la réinitialisation des ressources non gérées. |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | Enregistre cet [Icon](../../com.aspose.drawing/icon) dans le java.io.InputStream de sortie spécifié. |
| [toBitmap()](#toBitmap--) | Convertit cet [Icon](../../com.aspose.drawing/icon) en un [Bitmap](../../com.aspose.drawing/bitmap) GDI+. |
| [toString()](#toString--) | Obtient une chaîne lisible par l’homme qui décrit le [Icon](../../com.aspose.drawing/icon). |
### Icon(String fileName) {#Icon-java.lang.String-}
```
public Icon(String fileName)
```


Initialise une nouvelle instance de la classe [Icon](../../com.aspose.drawing/icon) à partir du nom de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Le fichier à partir duquel charger le [Icon](../../com.aspose.drawing/icon). |

### Icon(InputStream stream) {#Icon-java.io.InputStream-}
```
public Icon(InputStream stream)
```


Initialise une nouvelle instance de la classe [Icon](../../com.aspose.drawing/icon) à partir du flux de données spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Le flux de données à partir duquel charger le [Icon](../../com.aspose.drawing/icon). |

### Icon(String fileName, Size size) {#Icon-java.lang.String-com.aspose.drawing.Size-}
```
public Icon(String fileName, Size size)
```


Initialise une nouvelle instance de la classe [Icon](../../com.aspose.drawing/icon) de la taille spécifiée à partir du fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Le nom et le chemin du fichier contenant les données de l’icône. |
| size | [Size](../../com.aspose.drawing/size) | La taille souhaitée de l’icône. |

### Icon(Icon original, Size size) {#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-}
```
public Icon(Icon original, Size size)
```


Initialise une nouvelle instance de la classe [Icon](../../com.aspose.drawing/icon) et tente de trouver une version de l'icône correspondant à la taille demandée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | Le [Icon](../../com.aspose.drawing/icon) à partir duquel charger l’icône nouvellement redimensionnée. |
| size | [Size](../../com.aspose.drawing/size) | Une structure `Size`([.getSize](../../null/\#getSize)) qui spécifie la hauteur et la largeur du nouveau [Icon](../../com.aspose.drawing/icon). |

### Icon(Object type, String resource) {#Icon-java.lang.Object-java.lang.String-}
```
public Icon(Object type, String resource)
```


Initialise une nouvelle instance de la classe [Icon](../../com.aspose.drawing/icon) à partir d'une ressource dans l'assembly spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | java.lang.Object | Un Type qui spécifie l’assembly dans lequel rechercher la ressource. |
| ressource | java.lang.String | Le nom de la ressource à charger. |

### Icon(InputStream stream, Size size) {#Icon-java.io.InputStream-com.aspose.drawing.Size-}
```
public Icon(InputStream stream, Size size)
```


Initialise une nouvelle instance de la classe [Icon](../../com.aspose.drawing/icon) de la taille spécifiée à partir du flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux qui contient les données de l’icône. |
| size | [Size](../../com.aspose.drawing/size) | La taille souhaitée de l’icône. |

### Icon(String fileName, int width, int height) {#Icon-java.lang.String-int-int-}
```
public Icon(String fileName, int width, int height)
```


Initialise une nouvelle instance de la classe [Icon](../../com.aspose.drawing/icon) avec la largeur et la hauteur spécifiées à partir du fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Le nom et le chemin du fichier contenant les données du [Icon](../../com.aspose.drawing/icon). |
| width | int | La largeur souhaitée du [Icon](../../com.aspose.drawing/icon). |
| height | int | La hauteur souhaitée de l'[Icon](../../com.aspose.drawing/icon). |

### Icon(Icon original, int width, int height) {#Icon-com.aspose.drawing.Icon-int-int-}
```
public Icon(Icon original, int width, int height)
```


Initialise une nouvelle instance de la classe [Icon](../../com.aspose.drawing/icon) et tente de trouver une version de l’icône correspondant à la taille demandée..

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | L'icône à partir de laquelle charger la taille différente. |
| largeur | int | La largeur de la nouvelle icône. |
| hauteur | int | La hauteur de la nouvelle icône. |

### Icon(InputStream stream, int width, int height) {#Icon-java.io.InputStream-int-int-}
```
public Icon(InputStream stream, int width, int height)
```


Initialise une nouvelle instance de la classe [Icon](../../com.aspose.drawing/icon) à partir du flux de données spécifié et avec la largeur et la hauteur spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux de données à partir duquel charger l'icône. |
| largeur | int | La largeur, en pixels, de l'icône. |
| hauteur | int | La hauteur, en pixels, de l'icône. |

### getHandle() {#getHandle--}
```
public System.IntPtr getHandle()
```


Obtient le handle pour cet [Icon](../../com.aspose.drawing/icon). Ce n'est pas une copie du handle ; ne le libérez pas.

Valeur : le handle Windows pour l'icône.

**Returns:**
com.aspose.ms.System.IntPtr
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtient la hauteur de cet [Icon](../../com.aspose.drawing/icon).

Valeur : la hauteur de cet [Icon](../../com.aspose.drawing/icon).

**Returns:**
int
### getSize() {#getSize--}
```
public Size getSize()
```


Obtient la taille de cet [Icon](../../com.aspose.drawing/icon).

Valeur : une structure `Size`([.getSize](../../null/\\#getSize)) qui spécifie la largeur et la hauteur de cet [Icon](../../com.aspose.drawing/icon).

**Returns:**
[Size](../../com.aspose.drawing/size)
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient la largeur de cet [Icon](../../com.aspose.drawing/icon).

Valeur : la largeur de cet [Icon](../../com.aspose.drawing/icon).

**Returns:**
int
### extractAssociatedIcon(String filePath) {#extractAssociatedIcon-java.lang.String-}
```
public static Icon extractAssociatedIcon(String filePath)
```


Renvoie une représentation icône d’une image contenue dans le fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin vers le fichier qui contient une image. |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) representation of the image that is contained in the specified file.
### fromHandle(byte[] handle) {#fromHandle-byte---}
```
public static Icon fromHandle(byte[] handle)
```


Crée un [Icon](../../com.aspose.drawing/icon) GDI+ à partir du handle Windows spécifié vers une icône (HICON).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| handle | byte[] | Un handle Windows vers une icône. |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) this method creates.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clone le [Icon](../../com.aspose.drawing/icon), créant une image dupliquée.

**Returns:**
java.lang.Object - Un objet qui peut être converti en un [Icon](../../com.aspose.drawing/icon).
### dispose() {#dispose--}
```
public void dispose()
```


Effectue les tâches définies par l'application associées à la libération, la remise ou la réinitialisation des ressources non gérées.

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


Enregistre cet [Icon](../../com.aspose.drawing/icon) dans le java.io.InputStream de sortie spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Le java.io.InputStream dans lequel enregistrer. |

### toBitmap() {#toBitmap--}
```
public Bitmap toBitmap()
```


Convertit cet [Icon](../../com.aspose.drawing/icon) en un [Bitmap](../../com.aspose.drawing/bitmap) GDI+.

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - A [Bitmap](../../com.aspose.drawing/bitmap) that represents the converted [Icon](../../com.aspose.drawing/icon).
### toString() {#toString--}
```
public String toString()
```


Obtient une chaîne lisible par l’homme qui décrit le [Icon](../../com.aspose.drawing/icon).

**Returns:**
java.lang.String - Une chaîne qui décrit le [Icon](../../com.aspose.drawing/icon).
