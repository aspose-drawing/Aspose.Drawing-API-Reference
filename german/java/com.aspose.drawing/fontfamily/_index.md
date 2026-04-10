---
title: FontFamily
second_title: Aspose.Drawing für Java API-Referenz
description: Definiert eine Gruppe von Schriftarten, die ein ähnliches Grunddesign und bestimmte Stilvariationen aufweisen.
type: docs
weight: 24
url: /de/java/com.aspose.drawing/fontfamily/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class FontFamily implements System.IDisposable
```

Definiert eine Gruppe von Schriftarten, die ein ähnliches Grunddesign und gewisse Stilvariationen aufweisen. Diese Klasse kann nicht abgeleitet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FontFamily(String name)](#FontFamily-java.lang.String-) | Initialisiert eine neue Instanz der [FontFamily](../../com.aspose.drawing/fontfamily)-Klasse mit dem angegebenen Namen. |
| [FontFamily(String name, FontCollection fontCollection)](#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-) | Initialisiert eine neue Instanz der [FontFamily](../../com.aspose.drawing/fontfamily)-Klasse. |
| [FontFamily(String name, FontFamilyDefinition definition)](#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-) | Initialisiert eine neue Instanz der [FontFamily](../../com.aspose.drawing/fontfamily)-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFamilies()](#getFamilies--) | Gibt ein Array zurück, das alle mit dem aktuellen Grafik‑Kontext verknüpften [FontFamily](../../com.aspose.drawing/fontfamily)-Objekte enthält. |
| [getGenericSansSerif()](#getGenericSansSerif--) | Gibt ein generisches serifenloses [FontFamily](../../com.aspose.drawing/fontfamily)-Objekt zurück. |
| [getGenericSerif()](#getGenericSerif--) | Gibt ein generisches Serif-[FontFamily](../../com.aspose.drawing/fontfamily)-Objekt zurück. |
| [getGenericMonospace()](#getGenericMonospace--) | Gibt ein generisches Monospace-[FontFamily](../../com.aspose.drawing/fontfamily)-Objekt zurück. |
| [getName()](#getName--) | Gibt den Namen dieses [FontFamily](../../com.aspose.drawing/fontfamily)-Objekts zurück. |
| [dispose()](#dispose--) | Gibt alle von diesem [FontFamily](../../com.aspose.drawing/fontfamily)-Objekt verwendeten Ressourcen frei. |
| [getName(int language)](#getName-int-) | Gibt den Namen dieses [FontFamily](../../com.aspose.drawing/fontfamily)-Objekts in der angegebenen Sprache zurück. |
| [isStyleAvailable(int style)](#isStyleAvailable-int-) | Gibt an, ob die angegebene [FontStyle](../../com.aspose.drawing/fontstyle)-Aufzählung verfügbar ist. |
| [getEmHeight(int style)](#getEmHeight-int-) | Ermittelt die Höhe, in Schrift-Design-Einheiten, des EM-Quadrats für den angegebenen Stil. |
| [getCellAscent(int style)](#getCellAscent-int-) | Gibt den Zellaufstieg, in Design-Einheiten, der [FontFamily](../../com.aspose.drawing/fontfamily) des angegebenen Stils zurück. |
| [getCellDescent(int style)](#getCellDescent-int-) | Gibt den Zellabstieg, in Design-Einheiten, der [FontFamily](../../com.aspose.drawing/fontfamily) des angegebenen Stils zurück. |
| [hashCode()](#hashCode--) | Ermittelt einen Hashcode für diese [FontFamily](../../com.aspose.drawing/fontfamily). |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt an, ob das angegebene Objekt eine [FontFamily](../../com.aspose.drawing/fontfamily) ist und mit dieser [FontFamily](../../com.aspose.drawing/fontfamily) identisch ist. |
| [getLineSpacing(int style)](#getLineSpacing-int-) | Gibt den Zeilenabstand, in Design-Einheiten, der [FontFamily](../../com.aspose.drawing/fontfamily) des angegebenen Stils zurück. |
### FontFamily(String name) {#FontFamily-java.lang.String-}
```
public FontFamily(String name)
```


Initialisiert eine neue Instanz der [FontFamily](../../com.aspose.drawing/fontfamily)-Klasse mit dem angegebenen Namen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Der Name der neuen [FontFamily](../../com.aspose.drawing/fontfamily). |

### FontFamily(String name, FontCollection fontCollection) {#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-}
```
public FontFamily(String name, FontCollection fontCollection)
```


Initialisiert eine neue Instanz der [FontFamily](../../com.aspose.drawing/fontfamily)-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Der Name der Schriftfamilie. |
| fontCollection | [FontCollection](../../com.aspose.drawing/fontcollection) | Die Schriftartensammlung. |

### FontFamily(String name, FontFamilyDefinition definition) {#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-}
```
public FontFamily(String name, FontFamilyDefinition definition)
```


Initialisiert eine neue Instanz der [FontFamily](../../com.aspose.drawing/fontfamily)-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Der Name der Schriftfamilie. |
| definition | [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition) | Die Definition. |

### getFamilies() {#getFamilies--}
```
public static FontFamily[] getFamilies()
```


Gibt ein Array zurück, das alle mit dem aktuellen Grafik‑Kontext verknüpften [FontFamily](../../com.aspose.drawing/fontfamily)-Objekte enthält.

**Returns:**
com.aspose.drawing.FontFamily[] - Ein Array von [FontFamily](../../com.aspose.drawing/fontfamily)-Objekten, die mit dem aktuellen Grafik-Kontext verknüpft sind.
### getGenericSansSerif() {#getGenericSansSerif--}
```
public static FontFamily getGenericSansSerif()
```


Gibt ein generisches serifenloses [FontFamily](../../com.aspose.drawing/fontfamily)-Objekt zurück.

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) object that represents a generic sans serif font.
### getGenericSerif() {#getGenericSerif--}
```
public static FontFamily getGenericSerif()
```


Gibt ein generisches Serif-[FontFamily](../../com.aspose.drawing/fontfamily)-Objekt zurück.

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic serif font.
### getGenericMonospace() {#getGenericMonospace--}
```
public static FontFamily getGenericMonospace()
```


Gibt ein generisches Monospace-[FontFamily](../../com.aspose.drawing/fontfamily)-Objekt zurück.

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic monospace font.
### getName() {#getName--}
```
public String getName()
```


Gibt den Namen dieses [FontFamily](../../com.aspose.drawing/fontfamily)-Objekts zurück.

**Returns:**
java.lang.String - Ein String, der den Namen dieser [FontFamily](../../com.aspose.drawing/fontfamily) darstellt.
### dispose() {#dispose--}
```
public void dispose()
```


Gibt alle von diesem [FontFamily](../../com.aspose.drawing/fontfamily)-Objekt verwendeten Ressourcen frei.

### getName(int language) {#getName-int-}
```
public String getName(int language)
```


Gibt den Namen dieses [FontFamily](../../com.aspose.drawing/fontfamily)-Objekts in der angegebenen Sprache zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Sprache | int | Die Sprache, in der der Name zurückgegeben wird. |

**Returns:**
java.lang.String - Ein String, der den Namen dieser [FontFamily](../../com.aspose.drawing/fontfamily) in der angegebenen Sprache darstellt.
### isStyleAvailable(int style) {#isStyleAvailable-int-}
```
public boolean isStyleAvailable(int style)
```


Gibt an, ob die angegebene [FontStyle](../../com.aspose.drawing/fontstyle)-Aufzählung verfügbar ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| style | int | Der zu testende [FontStyle](../../com.aspose.drawing/fontstyle). |

**Returns:**
boolean - true, wenn der angegebene [FontStyle](../../com.aspose.drawing/fontstyle) verfügbar ist; andernfalls false.
### getEmHeight(int style) {#getEmHeight-int-}
```
public int getEmHeight(int style)
```


Ermittelt die Höhe, in Schrift-Design-Einheiten, des EM-Quadrats für den angegebenen Stil.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| style | int | Der [FontStyle](../../com.aspose.drawing/fontstyle), für den die EM-Höhe ermittelt werden soll. |

**Returns:**
int - Die Höhe des EM-Quadrats.
### getCellAscent(int style) {#getCellAscent-int-}
```
public int getCellAscent(int style)
```


Gibt den Zellaufstieg, in Design-Einheiten, der [FontFamily](../../com.aspose.drawing/fontfamily) des angegebenen Stils zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| style | int | Ein [FontStyle](../../com.aspose.drawing/fontstyle), der Stilinformationen für die Schrift enthält. |

**Returns:**
int - Der Zellaufstieg für diese [FontFamily](../../com.aspose.drawing/fontfamily), die den angegebenen [FontStyle](../../com.aspose.drawing/fontstyle) verwendet.
### getCellDescent(int style) {#getCellDescent-int-}
```
public int getCellDescent(int style)
```


Gibt den Zellabstieg, in Design-Einheiten, der [FontFamily](../../com.aspose.drawing/fontfamily) des angegebenen Stils zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| style | int | Ein [FontStyle](../../com.aspose.drawing/fontstyle), der Stilinformationen für die Schrift enthält. |

**Returns:**
int - Der Zellabstieg-Metrikwert für diese [FontFamily](../../com.aspose.drawing/fontfamily), die den angegebenen [FontStyle](../../com.aspose.drawing/fontstyle) verwendet.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Ermittelt einen Hashcode für diese [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
int - Der Hashcode für diese [FontFamily](../../com.aspose.drawing/fontfamily).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Gibt an, ob das angegebene Objekt eine [FontFamily](../../com.aspose.drawing/fontfamily) ist und mit dieser [FontFamily](../../com.aspose.drawing/fontfamily) identisch ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das zu testende Objekt. |

**Returns:**
boolean - `true`, wenn `obj` eine [FontFamily](../../com.aspose.drawing/fontfamily) ist und mit dieser [FontFamily](../../com.aspose.drawing/fontfamily) identisch ist; andernfalls `false`.
### getLineSpacing(int style) {#getLineSpacing-int-}
```
public int getLineSpacing(int style)
```


Gibt den Zeilenabstand in Designeinheiten der [FontFamily](../../com.aspose.drawing/fontfamily) des angegebenen Stils zurück. Der Zeilenabstand ist der vertikale Abstand zwischen den Grundlinien von zwei aufeinanderfolgenden Textzeilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| style | int | Der anzuwendende [FontStyle](../../com.aspose.drawing/fontstyle). |

**Returns:**
int - Der Abstand zwischen zwei aufeinanderfolgenden Textzeilen.
