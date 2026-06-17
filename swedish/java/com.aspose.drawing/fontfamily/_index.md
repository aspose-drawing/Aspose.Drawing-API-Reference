---
title: FontFamily
second_title: Aspose.Drawing för Java API‑referens
description: Definierar en grupp av typsnitt med en liknande grunddesign och vissa variationer i stilar.
type: docs
weight: 24
url: /sv/java/com.aspose.drawing/fontfamily/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class FontFamily implements System.IDisposable
```

Definierar en grupp av typsnitt med en liknande grunddesign och vissa variationer i stilar. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FontFamily(String name)](#FontFamily-java.lang.String-) | Initierar en ny instans av klassen [FontFamily](../../com.aspose.drawing/fontfamily) med det angivna namnet. |
| [FontFamily(String name, FontCollection fontCollection)](#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-) | Initierar en ny instans av klassen [FontFamily](../../com.aspose.drawing/fontfamily). |
| [FontFamily(String name, FontFamilyDefinition definition)](#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-) | Initierar en ny instans av klassen [FontFamily](../../com.aspose.drawing/fontfamily). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFamilies()](#getFamilies--) | Hämtar en array som innehåller alla [FontFamily](../../com.aspose.drawing/fontfamily)‑objekt som är associerade med det aktuella grafik‑sammanhanget. |
| [getGenericSansSerif()](#getGenericSansSerif--) | Hämtar ett generiskt sans‑serif [FontFamily](../../com.aspose.drawing/fontfamily)‑objekt. |
| [getGenericSerif()](#getGenericSerif--) | Hämtar ett generiskt serif‑[FontFamily](../../com.aspose.drawing/fontfamily). |
| [getGenericMonospace()](#getGenericMonospace--) | Hämtar ett generiskt monospace‑[FontFamily](../../com.aspose.drawing/fontfamily). |
| [getName()](#getName--) | Hämtar namnet på detta [FontFamily](../../com.aspose.drawing/fontfamily). |
| [dispose()](#dispose--) | Frigör alla resurser som används av detta [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getName(int language)](#getName-int-) | Returnerar namnet, på det angivna språket, för detta [FontFamily](../../com.aspose.drawing/fontfamily). |
| [isStyleAvailable(int style)](#isStyleAvailable-int-) | Indikerar om den angivna [FontStyle](../../com.aspose.drawing/fontstyle)-enumerationen är tillgänglig. |
| [getEmHeight(int style)](#getEmHeight-int-) | Hämtar höjden, i teckensnittets designenheter, för EM-kvadraten för den angivna stilen. |
| [getCellAscent(int style)](#getCellAscent-int-) | Returnerar cellens uppstigning, i designenheter, för [FontFamily](../../com.aspose.drawing/fontfamily) för den angivna stilen. |
| [getCellDescent(int style)](#getCellDescent-int-) | Returnerar cellens nedstigning, i designenheter, för [FontFamily](../../com.aspose.drawing/fontfamily) för den angivna stilen. |
| [hashCode()](#hashCode--) | Hämtar en hashkod för denna [FontFamily](../../com.aspose.drawing/fontfamily). |
| [equals(Object obj)](#equals-java.lang.Object-) | Indikerar om det angivna objektet är en [FontFamily](../../com.aspose.drawing/fontfamily) och är identisk med denna [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getLineSpacing(int style)](#getLineSpacing-int-) | Returnerar radavståndet, i designenheter, för [FontFamily](../../com.aspose.drawing/fontfamily) för den angivna stilen. |
### FontFamily(String name) {#FontFamily-java.lang.String-}
```
public FontFamily(String name)
```


Initierar en ny instans av klassen [FontFamily](../../com.aspose.drawing/fontfamily) med det angivna namnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den nya [FontFamily](../../com.aspose.drawing/fontfamily). |

### FontFamily(String name, FontCollection fontCollection) {#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-}
```
public FontFamily(String name, FontCollection fontCollection)
```


Initierar en ny instans av klassen [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Namnet på teckensnittsfamiljen. |
| fontCollection | [FontCollection](../../com.aspose.drawing/fontcollection) | Teckensnittssamlingen. |

### FontFamily(String name, FontFamilyDefinition definition) {#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-}
```
public FontFamily(String name, FontFamilyDefinition definition)
```


Initierar en ny instans av klassen [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Namnet på teckensnittsfamiljen. |
| definition | [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition) | Definitionen. |

### getFamilies() {#getFamilies--}
```
public static FontFamily[] getFamilies()
```


Hämtar en array som innehåller alla [FontFamily](../../com.aspose.drawing/fontfamily)‑objekt som är associerade med det aktuella grafik‑sammanhanget.

**Returns:**
com.aspose.drawing.FontFamily[] - En array av [FontFamily](../../com.aspose.drawing/fontfamily)-objekt som är associerade med det aktuella grafik‑kontextet.
### getGenericSansSerif() {#getGenericSansSerif--}
```
public static FontFamily getGenericSansSerif()
```


Hämtar ett generiskt sans‑serif [FontFamily](../../com.aspose.drawing/fontfamily)‑objekt.

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) object that represents a generic sans serif font.
### getGenericSerif() {#getGenericSerif--}
```
public static FontFamily getGenericSerif()
```


Hämtar ett generiskt serif‑[FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic serif font.
### getGenericMonospace() {#getGenericMonospace--}
```
public static FontFamily getGenericMonospace()
```


Hämtar ett generiskt monospace‑[FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic monospace font.
### getName() {#getName--}
```
public String getName()
```


Hämtar namnet på detta [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
java.lang.String - En sträng som representerar namnet på denna [FontFamily](../../com.aspose.drawing/fontfamily).
### dispose() {#dispose--}
```
public void dispose()
```


Frigör alla resurser som används av detta [FontFamily](../../com.aspose.drawing/fontfamily).

### getName(int language) {#getName-int-}
```
public String getName(int language)
```


Returnerar namnet, på det angivna språket, för detta [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| språk | int | Språket som namnet returneras på. |

**Returns:**
java.lang.String - En sträng som representerar namnet, på det angivna språket, för denna [FontFamily](../../com.aspose.drawing/fontfamily).
### isStyleAvailable(int style) {#isStyleAvailable-int-}
```
public boolean isStyleAvailable(int style)
```


Indikerar om den angivna [FontStyle](../../com.aspose.drawing/fontstyle)-enumerationen är tillgänglig.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| style | int | Den [FontStyle](../../com.aspose.drawing/fontstyle) som ska testas. |

**Returns:**
boolean - true om den angivna [FontStyle](../../com.aspose.drawing/fontstyle) är tillgänglig; annars false.
### getEmHeight(int style) {#getEmHeight-int-}
```
public int getEmHeight(int style)
```


Hämtar höjden, i teckensnittets designenheter, för EM-kvadraten för den angivna stilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| style | int | Den [FontStyle](../../com.aspose.drawing/fontstyle) för vilken EM‑höjden ska hämtas. |

**Returns:**
int - Höjden på EM‑kvadraten.
### getCellAscent(int style) {#getCellAscent-int-}
```
public int getCellAscent(int style)
```


Returnerar cellens uppstigning, i designenheter, för [FontFamily](../../com.aspose.drawing/fontfamily) för den angivna stilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| style | int | En [FontStyle](../../com.aspose.drawing/fontstyle) som innehåller stilinformation för teckensnittet. |

**Returns:**
int - Cellens uppstigning för denna [FontFamily](../../com.aspose.drawing/fontfamily) som använder den angivna [FontStyle](../../com.aspose.drawing/fontstyle).
### getCellDescent(int style) {#getCellDescent-int-}
```
public int getCellDescent(int style)
```


Returnerar cellens nedstigning, i designenheter, för [FontFamily](../../com.aspose.drawing/fontfamily) för den angivna stilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| style | int | En [FontStyle](../../com.aspose.drawing/fontstyle) som innehåller stilinformation för teckensnittet. |

**Returns:**
int - Cellens nedstigningsmått för denna [FontFamily](../../com.aspose.drawing/fontfamily) som använder den angivna [FontStyle](../../com.aspose.drawing/fontstyle).
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämtar en hashkod för denna [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
int - Hashkoden för denna [FontFamily](../../com.aspose.drawing/fontfamily).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Indikerar om det angivna objektet är en [FontFamily](../../com.aspose.drawing/fontfamily) och är identisk med denna [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att testa. |

**Returns:**
boolean - `true` om `obj` är en [FontFamily](../../com.aspose.drawing/fontfamily) och är identisk med denna [FontFamily](../../com.aspose.drawing/fontfamily); annars `false`.
### getLineSpacing(int style) {#getLineSpacing-int-}
```
public int getLineSpacing(int style)
```


Returnerar radavståndet, i designenheter, för [FontFamily](../../com.aspose.drawing/fontfamily) för den angivna stilen. Radavståndet är det vertikala avståndet mellan baslinjerna för två på varandra följande textrader.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| style | int | Den [FontStyle](../../com.aspose.drawing/fontstyle) som ska tillämpas. |

**Returns:**
int - Avståndet mellan två på varandra följande textrader.
