---
title: FontFamily
second_title: Aspose.Drawing voor Java API-referentie
description: Definieert een groep lettertypen met een vergelijkbaar basisonwerp en bepaalde variaties in stijlen.
type: docs
weight: 24
url: /nl/java/com.aspose.drawing/fontfamily/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class FontFamily implements System.IDisposable
```

Definieert een groep lettertypen met een vergelijkbaar basisonwerp en bepaalde variaties in stijlen. Deze klasse kan niet worden geërfd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FontFamily(String name)](#FontFamily-java.lang.String-) | Initialiseert een nieuw exemplaar van de [FontFamily](../../com.aspose.drawing/fontfamily)-klasse met de opgegeven naam. |
| [FontFamily(String name, FontCollection fontCollection)](#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-) | Initialiseert een nieuw exemplaar van de [FontFamily](../../com.aspose.drawing/fontfamily)-klasse. |
| [FontFamily(String name, FontFamilyDefinition definition)](#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-) | Initialiseert een nieuw exemplaar van de [FontFamily](../../com.aspose.drawing/fontfamily)-klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFamilies()](#getFamilies--) | Haalt een array op die alle [FontFamily](../../com.aspose.drawing/fontfamily)-objecten bevat die geassocieerd zijn met de huidige grafische context. |
| [getGenericSansSerif()](#getGenericSansSerif--) | Haalt een generiek sans-serif [FontFamily](../../com.aspose.drawing/fontfamily)-object op. |
| [getGenericSerif()](#getGenericSerif--) | Haalt een generiek serif [FontFamily](../../com.aspose.drawing/fontfamily) op. |
| [getGenericMonospace()](#getGenericMonospace--) | Haalt een generiek monospace [FontFamily](../../com.aspose.drawing/fontfamily) op. |
| [getName()](#getName--) | Haalt de naam op van deze [FontFamily](../../com.aspose.drawing/fontfamily). |
| [dispose()](#dispose--) | Vrijgeeft alle bronnen die door deze [FontFamily](../../com.aspose.drawing/fontfamily) worden gebruikt. |
| [getName(int language)](#getName-int-) | Retourneert de naam, in de opgegeven taal, van deze [FontFamily](../../com.aspose.drawing/fontfamily). |
| [isStyleAvailable(int style)](#isStyleAvailable-int-) | Geeft aan of de opgegeven [FontStyle](../../com.aspose.drawing/fontstyle) enumeratie beschikbaar is. |
| [getEmHeight(int style)](#getEmHeight-int-) | Haalt de hoogte, in lettertype-ontwerpeenheden, van het EM-kwadraat op voor de opgegeven stijl. |
| [getCellAscent(int style)](#getCellAscent-int-) | Retourneert de celstijging, in ontwerpeenheden, van de [FontFamily](../../com.aspose.drawing/fontfamily) van de opgegeven stijl. |
| [getCellDescent(int style)](#getCellDescent-int-) | Retourneert de celafdaling, in ontwerpeenheden, van de [FontFamily](../../com.aspose.drawing/fontfamily) van de opgegeven stijl. |
| [hashCode()](#hashCode--) | Haalt een hashcode op voor deze [FontFamily](../../com.aspose.drawing/fontfamily). |
| [equals(Object obj)](#equals-java.lang.Object-) | Geeft aan of het opgegeven object een [FontFamily](../../com.aspose.drawing/fontfamily) is en identiek is aan deze [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getLineSpacing(int style)](#getLineSpacing-int-) | Retourneert de regelafstand, in ontwerpeenheden, van de [FontFamily](../../com.aspose.drawing/fontfamily) van de opgegeven stijl. |
### FontFamily(String name) {#FontFamily-java.lang.String-}
```
public FontFamily(String name)
```


Initialiseert een nieuw exemplaar van de [FontFamily](../../com.aspose.drawing/fontfamily)-klasse met de opgegeven naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | De naam van de nieuwe [FontFamily](../../com.aspose.drawing/fontfamily). |

### FontFamily(String name, FontCollection fontCollection) {#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-}
```
public FontFamily(String name, FontCollection fontCollection)
```


Initialiseert een nieuw exemplaar van de [FontFamily](../../com.aspose.drawing/fontfamily)-klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | De naam van de lettertypefamilie. |
| fontCollection | [FontCollection](../../com.aspose.drawing/fontcollection) | De lettertypecollectie. |

### FontFamily(String name, FontFamilyDefinition definition) {#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-}
```
public FontFamily(String name, FontFamilyDefinition definition)
```


Initialiseert een nieuw exemplaar van de [FontFamily](../../com.aspose.drawing/fontfamily)-klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | De naam van de lettertypefamilie. |
| definition | [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition) | De definitie. |

### getFamilies() {#getFamilies--}
```
public static FontFamily[] getFamilies()
```


Haalt een array op die alle [FontFamily](../../com.aspose.drawing/fontfamily)-objecten bevat die geassocieerd zijn met de huidige grafische context.

**Returns:**
com.aspose.drawing.FontFamily[] - Een array van [FontFamily](../../com.aspose.drawing/fontfamily) objecten die gekoppeld zijn aan de huidige grafische context.
### getGenericSansSerif() {#getGenericSansSerif--}
```
public static FontFamily getGenericSansSerif()
```


Haalt een generiek sans-serif [FontFamily](../../com.aspose.drawing/fontfamily)-object op.

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) object that represents a generic sans serif font.
### getGenericSerif() {#getGenericSerif--}
```
public static FontFamily getGenericSerif()
```


Haalt een generiek serif [FontFamily](../../com.aspose.drawing/fontfamily) op.

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic serif font.
### getGenericMonospace() {#getGenericMonospace--}
```
public static FontFamily getGenericMonospace()
```


Haalt een generiek monospace [FontFamily](../../com.aspose.drawing/fontfamily) op.

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic monospace font.
### getName() {#getName--}
```
public String getName()
```


Haalt de naam op van deze [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
java.lang.String - Een String die de naam van deze [FontFamily](../../com.aspose.drawing/fontfamily) weergeeft.
### dispose() {#dispose--}
```
public void dispose()
```


Vrijgeeft alle bronnen die door deze [FontFamily](../../com.aspose.drawing/fontfamily) worden gebruikt.

### getName(int language) {#getName-int-}
```
public String getName(int language)
```


Retourneert de naam, in de opgegeven taal, van deze [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| taal | int | De taal waarin de naam wordt geretourneerd. |

**Returns:**
java.lang.String - Een String die de naam, in de opgegeven taal, van deze [FontFamily](../../com.aspose.drawing/fontfamily) weergeeft.
### isStyleAvailable(int style) {#isStyleAvailable-int-}
```
public boolean isStyleAvailable(int style)
```


Geeft aan of de opgegeven [FontStyle](../../com.aspose.drawing/fontstyle) enumeratie beschikbaar is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| style | int | De [FontStyle](../../com.aspose.drawing/fontstyle) om te testen. |

**Returns:**
boolean - true als de opgegeven [FontStyle](../../com.aspose.drawing/fontstyle) beschikbaar is; anders false.
### getEmHeight(int style) {#getEmHeight-int-}
```
public int getEmHeight(int style)
```


Haalt de hoogte, in lettertype-ontwerpeenheden, van het EM-kwadraat op voor de opgegeven stijl.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| style | int | De [FontStyle](../../com.aspose.drawing/fontstyle) waarvoor de EM-hoogte moet worden opgehaald. |

**Returns:**
int - De hoogte van het EM-kwadraat.
### getCellAscent(int style) {#getCellAscent-int-}
```
public int getCellAscent(int style)
```


Retourneert de celstijging, in ontwerpeenheden, van de [FontFamily](../../com.aspose.drawing/fontfamily) van de opgegeven stijl.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| style | int | Een [FontStyle](../../com.aspose.drawing/fontstyle) die stijlinformatie voor het lettertype bevat. |

**Returns:**
int - De celstijging voor deze [FontFamily](../../com.aspose.drawing/fontfamily) die de opgegeven [FontStyle](../../com.aspose.drawing/fontstyle) gebruikt.
### getCellDescent(int style) {#getCellDescent-int-}
```
public int getCellDescent(int style)
```


Retourneert de celafdaling, in ontwerpeenheden, van de [FontFamily](../../com.aspose.drawing/fontfamily) van de opgegeven stijl.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| style | int | Een [FontStyle](../../com.aspose.drawing/fontstyle) die stijlinformatie voor het lettertype bevat. |

**Returns:**
int - De celafdalingmetriek voor deze [FontFamily](../../com.aspose.drawing/fontfamily) die de opgegeven [FontStyle](../../com.aspose.drawing/fontstyle) gebruikt.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Haalt een hashcode op voor deze [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
int - De hashcode voor deze [FontFamily](../../com.aspose.drawing/fontfamily).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Geeft aan of het opgegeven object een [FontFamily](../../com.aspose.drawing/fontfamily) is en identiek is aan deze [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het object om te testen. |

**Returns:**
boolean - `true` als `obj` een [FontFamily](../../com.aspose.drawing/fontfamily) is en identiek is aan deze [FontFamily](../../com.aspose.drawing/fontfamily); anders `false`.
### getLineSpacing(int style) {#getLineSpacing-int-}
```
public int getLineSpacing(int style)
```


Geeft de regelafstand, in ontwerpeenheden, van de [FontFamily](../../com.aspose.drawing/fontfamily) van de opgegeven stijl terug. De regelafstand is de verticale afstand tussen de basislijnen van twee opeenvolgende tekstregels.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| style | int | De [FontStyle](../../com.aspose.drawing/fontstyle) om toe te passen. |

**Returns:**
int - De afstand tussen twee opeenvolgende tekstregels.
