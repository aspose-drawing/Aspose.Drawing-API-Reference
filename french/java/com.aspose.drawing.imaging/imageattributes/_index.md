---
title: ImageAttributes
second_title: Référence de l'API Aspose.Drawing pour Java
description: Contient des informations sur la façon dont les couleurs des bitmap et des métafichiers sont manipulées lors du rendu.
type: docs
weight: 24
url: /fr/java/com.aspose.drawing.imaging/imageattributes/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class ImageAttributes implements System.IDisposable
```

Contient des informations sur la façon dont les couleurs des bitmap et des métafichiers sont manipulées lors du rendu.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Initialise une nouvelle instance de la classe [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [dispose()](#dispose--) | Libère toutes les ressources utilisées par cet objet [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
| [deepClone()](#deepClone--) | Crée une copie exacte de cet objet [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | Définit la matrice d'ajustement des couleurs pour la catégorie par défaut. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | Définit la matrice d'ajustement des couleurs pour la catégorie par défaut. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | Définit la matrice d'ajustement des couleurs pour une catégorie spécifiée. |
| [clearColorMatrix()](#clearColorMatrix--) | Efface la matrice d'ajustement des couleurs pour la catégorie par défaut. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Efface la matrice d'ajustement des couleurs pour une catégorie spécifiée. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | Définit la matrice d'ajustement des couleurs et la matrice d'ajustement du niveau de gris pour la catégorie par défaut. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | Définit la matrice d'ajustement des couleurs et la matrice d'ajustement du niveau de gris pour la catégorie par défaut. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | Définit la matrice d'ajustement des couleurs et la matrice d'ajustement du niveau de gris pour une catégorie spécifiée. |
| [setThreshold(float threshold)](#setThreshold-float-) | Définit le seuil (plage de transparence) pour la catégorie par défaut. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Définit le seuil (plage de transparence) pour une catégorie spécifiée. |
| [clearThreshold()](#clearThreshold--) | Efface la valeur du seuil pour la catégorie par défaut. |
| [clearThreshold(int type)](#clearThreshold-int-) | Efface la valeur du seuil pour une catégorie spécifiée. |
| [setGamma(float gamma)](#setGamma-float-) | Définit la valeur gamma pour la catégorie par défaut. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Définit la valeur gamma pour une catégorie spécifiée. |
| [clearGamma()](#clearGamma--) | Désactive la correction gamma pour la catégorie par défaut. |
| [clearGamma(int type)](#clearGamma-int-) | Désactive la correction gamma pour une catégorie spécifiée. |
| [setNoOp()](#setNoOp--) | Désactive l'ajustement des couleurs pour la catégorie par défaut. |
| [setNoOp(int type)](#setNoOp-int-) | Désactive l'ajustement des couleurs pour une catégorie spécifiée. |
| [clearNoOp()](#clearNoOp--) | Efface le paramètre NoOp pour la catégorie par défaut. |
| [clearNoOp(int type)](#clearNoOp-int-) | Efface le paramètre NoOp pour une catégorie spécifiée. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Définit la clé de couleur pour la catégorie par défaut. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Définit la clé de couleur (plage de transparence) pour une catégorie spécifiée. |
| [clearColorKey()](#clearColorKey--) | Efface la clé de couleur (plage de transparence) pour la catégorie par défaut. |
| [clearColorKey(int type)](#clearColorKey-int-) | Efface la clé de couleur (plage de transparence) pour une catégorie spécifiée. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Définit le canal de sortie CMYK (cyan-magenta-yellow-black) pour la catégorie par défaut. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Définit le canal de sortie CMYK (cyan-magenta-yellow-black) pour une catégorie spécifiée. |
| [clearOutputChannel()](#clearOutputChannel--) | Efface le paramètre du canal de sortie CMYK (cyan-magenta-yellow-black) pour la catégorie par défaut. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Efface le paramètre du canal de sortie (cyan-magenta-yellow-black) pour une catégorie spécifiée. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Définit le fichier de profil couleur du canal de sortie pour la catégorie par défaut. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Définit le fichier de profil couleur du canal de sortie pour une catégorie spécifiée. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Efface le paramètre de profil couleur du canal de sortie pour la catégorie par défaut. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Efface le paramètre de profil couleur du canal de sortie pour une catégorie spécifiée. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---) | Définit la table de remappage des couleurs pour la catégorie par défaut. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-) | Définit la table de remappage des couleurs pour une catégorie spécifiée. |
| [clearRemapTable()](#clearRemapTable--) | Efface la table de remappage des couleurs pour la catégorie par défaut. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Efface la table de remappage des couleurs pour une catégorie spécifiée. |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---) | Définit la table de remappage des couleurs pour la catégorie de pinceau. |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Efface la table de remappage des couleurs du pinceau de cet objet [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
| [setWrapMode(int mode)](#setWrapMode-int-) | Définit le mode d'enveloppement utilisé pour déterminer comment répéter une texture sur une forme, ou aux limites de la forme. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.drawing.Color-) | Définit le mode d'enveloppement et la couleur utilisés pour déterminer comment répéter une texture sur une forme, ou aux limites de la forme. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.drawing.Color-boolean-) | Définit le mode d'enveloppement et la couleur utilisés pour déterminer comment répéter une texture sur une forme, ou aux limites de la forme. |
| [getAdjustedPalette(ColorPalette palette, int type)](#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-) | Ajuste les couleurs d'une palette selon les paramètres d'ajustement d'une catégorie spécifiée. |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Initialise une nouvelle instance de la classe [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

### dispose() {#dispose--}
```
public void dispose()
```


Libère toutes les ressources utilisées par cet objet [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crée une copie exacte de cet objet [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

**Returns:**
java.lang.Object - L'objet [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) créé par cette classe, converti en objet.
### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Définit la matrice d'ajustement des couleurs pour la catégorie par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matrice d'ajustement des couleurs. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Définit la matrice d'ajustement des couleurs pour la catégorie par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matrice d'ajustement des couleurs. |
| flags | int | Un élément de [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) qui spécifie le type d'image et de couleur qui seront affectés par la matrice d'ajustement des couleurs. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Définit la matrice d'ajustement des couleurs pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matrice d'ajustement des couleurs. |
| mode | int | Un élément de [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) qui spécifie le type d'image et de couleur qui seront affectés par la matrice d'ajustement des couleurs. |
| type | int | Un élément de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) qui spécifie la catégorie pour laquelle la matrice d'ajustement des couleurs est définie. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Efface la matrice d'ajustement des couleurs pour la catégorie par défaut.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Efface la matrice d'ajustement des couleurs pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Un élément de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) qui spécifie la catégorie pour laquelle la matrice d'ajustement des couleurs est effacée. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Définit la matrice d'ajustement des couleurs et la matrice d'ajustement du niveau de gris pour la catégorie par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matrice d'ajustement des couleurs. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matrice d'ajustement du niveau de gris. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Définit la matrice d'ajustement des couleurs et la matrice d'ajustement du niveau de gris pour la catégorie par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matrice d'ajustement des couleurs. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matrice d'ajustement du niveau de gris. |
| flags | int | Un élément de [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) qui spécifie le type d'image et de couleur qui seront affectés par les matrices d'ajustement des couleurs et du niveau de gris. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Définit la matrice d'ajustement des couleurs et la matrice d'ajustement du niveau de gris pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matrice d'ajustement des couleurs. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | La matrice d'ajustement du niveau de gris. |
| mode | int | Un élément de [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) qui spécifie le type d'image et de couleur qui seront affectés par les matrices d'ajustement des couleurs et du niveau de gris. |
| type | int | Un élément de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) qui spécifie la catégorie pour laquelle les matrices d'ajustement des couleurs et du niveau de gris sont définies. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Définit le seuil (plage de transparence) pour la catégorie par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| seuil | float | Un nombre réel qui spécifie la valeur du seuil. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Définit le seuil (plage de transparence) pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| seuil | float | Une valeur de seuil de 0.0 à 1.0 utilisée comme point de rupture pour trier les couleurs qui seront mappées à une valeur maximale ou minimale. |
| type | int | Un élément de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) qui spécifie la catégorie pour laquelle le seuil de couleur est défini. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Efface la valeur du seuil pour la catégorie par défaut.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Efface la valeur du seuil pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Un élément de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) qui spécifie la catégorie pour laquelle le seuil est effacé. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Définit la valeur gamma pour la catégorie par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gamma | float | La valeur de correction gamma. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Définit la valeur gamma pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gamma | float | La valeur de correction gamma. |
| type | int | Un élément de l'énumération [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) qui spécifie la catégorie pour laquelle la valeur gamma est définie. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Désactive la correction gamma pour la catégorie par défaut.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Désactive la correction gamma pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Un élément de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) qui spécifie la catégorie pour laquelle la correction gamma est désactivée. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Désactive l'ajustement des couleurs pour la catégorie par défaut. Vous pouvez appeler la méthode [.clearNoOp](../../null/\#clearNoOp) pour rétablir les paramètres d'ajustement des couleurs qui étaient en place avant l'appel de la méthode [.setNoOp](../../null/\#setNoOp).

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Désactive l'ajustement des couleurs pour une catégorie spécifiée. Vous pouvez appeler la méthode [.clearNoOp](../../null/\#clearNoOp) pour rétablir les paramètres d'ajustement des couleurs qui étaient en place avant l'appel de la méthode [.setNoOp](../../null/\#setNoOp).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Un élément de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) qui spécifie la catégorie pour laquelle la correction des couleurs est désactivée. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Efface le paramètre NoOp pour la catégorie par défaut.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Efface le paramètre NoOp pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Un élément de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) qui spécifie la catégorie pour laquelle le paramètre NoOp est réinitialisé. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Définit la clé de couleur pour la catégorie par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | La valeur basse de la clé de couleur. |
| colorHigh | [Color](../../com.aspose.drawing/color) | La valeur haute de la clé de couleur. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Définit la clé de couleur (plage de transparence) pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | La valeur basse de la clé de couleur. |
| colorHigh | [Color](../../com.aspose.drawing/color) | La valeur haute de la clé de couleur. |
| type | int | Un élément de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) qui spécifie la catégorie pour laquelle la clé de couleur est définie. |

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Efface la clé de couleur (plage de transparence) pour la catégorie par défaut.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Efface la clé de couleur (plage de transparence) pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Un élément de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) qui spécifie la catégorie pour laquelle la clé de couleur est réinitialisée. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Définit le canal de sortie CMYK (cyan-magenta-yellow-black) pour la catégorie par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flags | int | Un élément de [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag) qui spécifie le canal de sortie. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Définit le canal de sortie CMYK (cyan-magenta-yellow-black) pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flags | int | Un élément de [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag) qui spécifie le canal de sortie. |
| type | int | Un élément de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) qui spécifie la catégorie pour laquelle le canal de sortie est défini. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Efface le paramètre du canal de sortie CMYK (cyan-magenta-yellow-black) pour la catégorie par défaut.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Efface le paramètre du canal de sortie (cyan-magenta-yellow-black) pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Un élément de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) qui spécifie la catégorie pour laquelle le paramètre du canal de sortie est réinitialisé. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Définit le fichier de profil couleur du canal de sortie pour la catégorie par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Le chemin d'accès d'un fichier de profil couleur. Si le fichier de profil couleur se trouve dans le répertoire %SystemRoot%\\System32\\Spool\\Drivers\\Color, ce paramètre peut être le nom du fichier. Sinon, ce paramètre doit être le chemin d'accès complet. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Définit le fichier de profil couleur du canal de sortie pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Le chemin d'accès d'un fichier de profil couleur. Si le fichier de profil couleur se trouve dans le répertoire %SystemRoot%\\System32\\Spool\\Drivers\\Color, ce paramètre peut être le nom du fichier. Sinon, ce paramètre doit être le chemin d'accès complet. |
| type | int | Un élément de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) qui spécifie la catégorie pour laquelle le fichier de profil couleur du canal de sortie est défini. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Efface le paramètre de profil couleur du canal de sortie pour la catégorie par défaut.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Efface le paramètre de profil couleur du canal de sortie pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Un élément de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) qui spécifie la catégorie pour laquelle le paramètre de profil du canal de sortie est réinitialisé. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Définit la table de remappage des couleurs pour la catégorie par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | Un tableau de paires de couleurs du type [ColorMap](../../com.aspose.drawing.imaging/colormap). Chaque paire de couleurs contient une couleur existante (la première valeur) et la couleur vers laquelle elle sera mappée (la deuxième valeur). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Définit la table de remappage des couleurs pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | Un tableau de paires de couleurs du type [ColorMap](../../com.aspose.drawing.imaging/colormap). Chaque paire de couleurs contient une couleur existante (la première valeur) et la couleur vers laquelle elle sera mappée (la deuxième valeur). |
| type | int | Un élément de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) qui spécifie la catégorie pour laquelle la table de remappage des couleurs est définie. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Efface la table de remappage des couleurs pour la catégorie par défaut.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Efface la table de remappage des couleurs pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Un élément de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) qui spécifie la catégorie pour laquelle la table de remappage est réinitialisée. |

### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


Définit la table de remappage des couleurs pour la catégorie de pinceau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | Un tableau d'objets [ColorMap](../../com.aspose.drawing.imaging/colormap). |

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Efface la table de remappage des couleurs du pinceau de cet objet [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Définit le mode d'habillage utilisé pour déterminer comment répéter une texture sur une forme, ou aux limites de la forme. Une texture est répétée sur une forme pour la remplir lorsque la texture est plus petite que la forme à remplir.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mode | int | Un élément de [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) qui spécifie comment les copies répétées d'une image sont utilisées pour couvrir une zone. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.drawing.Color-}
```
public void setWrapMode(int mode, Color color)
```


Définit le mode d’enroulement et la couleur utilisés pour déterminer comment répéter une texture sur une forme, ou aux limites de la forme. Une texture est répétée sur une forme pour la remplir lorsque la texture est plus petite que la forme qu’elle remplit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mode | int | Un élément de [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) qui spécifie comment les copies répétées d'une image sont utilisées pour couvrir une zone. |
| color | [Color](../../com.aspose.drawing/color) | Un objet [Color](../../com.aspose.drawing/color) qui spécifie la couleur des pixels à l’extérieur d’une image rendue. Cette couleur est visible si le paramètre mode est défini sur `WrapMode.Clamp` et que le rectangle source passé à `Graphics.DrawImage` est plus grand que l’image elle‑même. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.drawing.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Définit le mode d’enroulement et la couleur utilisés pour déterminer comment répéter une texture sur une forme, ou aux limites de la forme. Une texture est répétée sur une forme pour la remplir lorsque la texture est plus petite que la forme qu’elle remplit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mode | int | Un élément de [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) qui spécifie comment les copies répétées d'une image sont utilisées pour couvrir une zone. |
| color | [Color](../../com.aspose.drawing/color) | Un objet couleur qui spécifie la couleur des pixels à l’extérieur d’une image rendue. Cette couleur est visible si le paramètre mode est défini sur `WrapMode.Clamp` et que le rectangle source passé à `Graphics.DrawImage` est plus grand que l’image elle‑même. |
| clamp | boolean | Ce paramètre n’a aucun effet. Réglez‑le sur false. |

### getAdjustedPalette(ColorPalette palette, int type) {#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-}
```
public void getAdjustedPalette(ColorPalette palette, int type)
```


Ajuste les couleurs d'une palette selon les paramètres d'ajustement d'une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| palette | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) | Une [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) qui, en entrée, contient la palette à ajuster, et en sortie, contient la palette ajustée. |
| type | int | Un élément de [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) qui spécifie la catégorie dont les paramètres d’ajustement seront appliqués à la palette. |

