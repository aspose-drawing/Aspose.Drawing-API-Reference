---
title: FontFamily
second_title: Référence de l'API Aspose.Drawing pour Java
description: Définit un groupe de polices ayant un design de base similaire et certaines variations de style.
type: docs
weight: 24
url: /fr/java/com.aspose.drawing/fontfamily/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class FontFamily implements System.IDisposable
```

Définit un groupe de polices ayant un design de base similaire et certaines variations de styles. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FontFamily(String name)](#FontFamily-java.lang.String-) | Initialise une nouvelle instance de la classe [FontFamily](../../com.aspose.drawing/fontfamily) avec le nom spécifié. |
| [FontFamily(String name, FontCollection fontCollection)](#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-) | Initialise une nouvelle instance de la classe [FontFamily](../../com.aspose.drawing/fontfamily). |
| [FontFamily(String name, FontFamilyDefinition definition)](#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-) | Initialise une nouvelle instance de la classe [FontFamily](../../com.aspose.drawing/fontfamily). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFamilies()](#getFamilies--) | Obtient un tableau contenant tous les objets [FontFamily](../../com.aspose.drawing/fontfamily) associés au contexte graphique actuel. |
| [getGenericSansSerif()](#getGenericSansSerif--) | Obtient un objet générique sans empattement [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getGenericSerif()](#getGenericSerif--) | Obtient un objet générique avec empattement [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getGenericMonospace()](#getGenericMonospace--) | Obtient un objet générique à chasse fixe [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getName()](#getName--) | Obtient le nom de ce [FontFamily](../../com.aspose.drawing/fontfamily). |
| [dispose()](#dispose--) | Libère toutes les ressources utilisées par ce [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getName(int language)](#getName-int-) | Renvoie le nom, dans la langue spécifiée, de ce [FontFamily](../../com.aspose.drawing/fontfamily). |
| [isStyleAvailable(int style)](#isStyleAvailable-int-) | Indique si l'énumération [FontStyle](../../com.aspose.drawing/fontstyle) spécifiée est disponible. |
| [getEmHeight(int style)](#getEmHeight-int-) | Obtient la hauteur, en unités de conception de police, du carré EM pour le style spécifié. |
| [getCellAscent(int style)](#getCellAscent-int-) | Renvoie l'ascension de la cellule, en unités de conception, de la [FontFamily](../../com.aspose.drawing/fontfamily) du style spécifié. |
| [getCellDescent(int style)](#getCellDescent-int-) | Renvoie la descente de la cellule, en unités de conception, de la [FontFamily](../../com.aspose.drawing/fontfamily) du style spécifié. |
| [hashCode()](#hashCode--) | Obtient un code de hachage pour cette [FontFamily](../../com.aspose.drawing/fontfamily). |
| [equals(Object obj)](#equals-java.lang.Object-) | Indique si l'objet spécifié est une [FontFamily](../../com.aspose.drawing/fontfamily) et est identique à cette [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getLineSpacing(int style)](#getLineSpacing-int-) | Renvoie l'espacement des lignes, en unités de conception, de la [FontFamily](../../com.aspose.drawing/fontfamily) du style spécifié. |
### FontFamily(String name) {#FontFamily-java.lang.String-}
```
public FontFamily(String name)
```


Initialise une nouvelle instance de la classe [FontFamily](../../com.aspose.drawing/fontfamily) avec le nom spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Le nom de la nouvelle [FontFamily](../../com.aspose.drawing/fontfamily). |

### FontFamily(String name, FontCollection fontCollection) {#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-}
```
public FontFamily(String name, FontCollection fontCollection)
```


Initialise une nouvelle instance de la classe [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Le nom de la famille de polices. |
| fontCollection | [FontCollection](../../com.aspose.drawing/fontcollection) | La collection de polices. |

### FontFamily(String name, FontFamilyDefinition definition) {#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-}
```
public FontFamily(String name, FontFamilyDefinition definition)
```


Initialise une nouvelle instance de la classe [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Le nom de la famille de polices. |
| definition | [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition) | La définition. |

### getFamilies() {#getFamilies--}
```
public static FontFamily[] getFamilies()
```


Obtient un tableau contenant tous les objets [FontFamily](../../com.aspose.drawing/fontfamily) associés au contexte graphique actuel.

**Returns:**
com.aspose.drawing.FontFamily[] - Un tableau d'objets [FontFamily](../../com.aspose.drawing/fontfamily) associés au contexte graphique actuel.
### getGenericSansSerif() {#getGenericSansSerif--}
```
public static FontFamily getGenericSansSerif()
```


Obtient un objet générique sans empattement [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) object that represents a generic sans serif font.
### getGenericSerif() {#getGenericSerif--}
```
public static FontFamily getGenericSerif()
```


Obtient un objet générique avec empattement [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic serif font.
### getGenericMonospace() {#getGenericMonospace--}
```
public static FontFamily getGenericMonospace()
```


Obtient un objet générique à chasse fixe [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic monospace font.
### getName() {#getName--}
```
public String getName()
```


Obtient le nom de ce [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
java.lang.String - Une chaîne qui représente le nom de cette [FontFamily](../../com.aspose.drawing/fontfamily).
### dispose() {#dispose--}
```
public void dispose()
```


Libère toutes les ressources utilisées par ce [FontFamily](../../com.aspose.drawing/fontfamily).

### getName(int language) {#getName-int-}
```
public String getName(int language)
```


Renvoie le nom, dans la langue spécifiée, de ce [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| langue | int | La langue dans laquelle le nom est renvoyé. |

**Returns:**
java.lang.String - Une chaîne qui représente le nom, dans la langue spécifiée, de cette [FontFamily](../../com.aspose.drawing/fontfamily).
### isStyleAvailable(int style) {#isStyleAvailable-int-}
```
public boolean isStyleAvailable(int style)
```


Indique si l'énumération [FontStyle](../../com.aspose.drawing/fontstyle) spécifiée est disponible.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| style | int | Le [FontStyle](../../com.aspose.drawing/fontstyle) à tester. |

**Returns:**
boolean - true si le [FontStyle](../../com.aspose.drawing/fontstyle) spécifié est disponible ; sinon, false.
### getEmHeight(int style) {#getEmHeight-int-}
```
public int getEmHeight(int style)
```


Obtient la hauteur, en unités de conception de police, du carré EM pour le style spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| style | int | Le [FontStyle](../../com.aspose.drawing/fontstyle) pour lequel obtenir la hauteur EM. |

**Returns:**
int - La hauteur du carré EM.
### getCellAscent(int style) {#getCellAscent-int-}
```
public int getCellAscent(int style)
```


Renvoie l'ascension de la cellule, en unités de conception, de la [FontFamily](../../com.aspose.drawing/fontfamily) du style spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| style | int | Un [FontStyle](../../com.aspose.drawing/fontstyle) qui contient les informations de style pour la police. |

**Returns:**
int - L'ascension de la cellule pour cette [FontFamily](../../com.aspose.drawing/fontfamily) qui utilise le [FontStyle](../../com.aspose.drawing/fontstyle) spécifié.
### getCellDescent(int style) {#getCellDescent-int-}
```
public int getCellDescent(int style)
```


Renvoie la descente de la cellule, en unités de conception, de la [FontFamily](../../com.aspose.drawing/fontfamily) du style spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| style | int | Un [FontStyle](../../com.aspose.drawing/fontstyle) qui contient les informations de style pour la police. |

**Returns:**
int - La métrique de descente de la cellule pour cette [FontFamily](../../com.aspose.drawing/fontfamily) qui utilise le [FontStyle](../../com.aspose.drawing/fontstyle) spécifié.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtient un code de hachage pour cette [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
int - Le code de hachage pour cette [FontFamily](../../com.aspose.drawing/fontfamily).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Indique si l'objet spécifié est une [FontFamily](../../com.aspose.drawing/fontfamily) et est identique à cette [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'objet à tester. |

**Returns:**
boolean - `true` si `obj` est une [FontFamily](../../com.aspose.drawing/fontfamily) et est identique à cette [FontFamily](../../com.aspose.drawing/fontfamily) ; sinon, `false`.
### getLineSpacing(int style) {#getLineSpacing-int-}
```
public int getLineSpacing(int style)
```


Renvoie l’interligne, en unités de conception, de la [FontFamily](../../com.aspose.drawing/fontfamily) du style spécifié. L’interligne est la distance verticale entre les lignes de base de deux lignes de texte consécutives.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| style | int | Le [FontStyle](../../com.aspose.drawing/fontstyle) à appliquer. |

**Returns:**
int - La distance entre deux lignes de texte consécutives.
