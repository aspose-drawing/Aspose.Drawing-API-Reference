---
title: Icon
second_title: Aspose.Drawing voor Java API-referentie
description: Stelt een Windows-pictogram voor dat een kleine bitmapafbeelding is die wordt gebruikt om een object weer te geven.
type: docs
weight: 29
url: /nl/java/com.aspose.drawing/icon/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.ms.System.IDisposable
```
public final class Icon implements System.ICloneable, System.IDisposable
```

Stelt een Windows-pictogram voor, dat een kleine bitmapafbeelding is die wordt gebruikt om een object weer te geven. Pictogrammen kunnen worden beschouwd als transparante bitmaps, hoewel hun grootte door het systeem wordt bepaald.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Icon(String fileName)](#Icon-java.lang.String-) | Initialiseert een nieuw exemplaar van de [Icon](../../com.aspose.drawing/icon) klasse vanuit de opgegeven bestandsnaam. |
| [Icon(InputStream stream)](#Icon-java.io.InputStream-) | Initialiseert een nieuw exemplaar van de [Icon](../../com.aspose.drawing/icon) klasse vanuit de opgegeven datastroom. |
| [Icon(String fileName, Size size)](#Icon-java.lang.String-com.aspose.drawing.Size-) | Initialiseert een nieuw exemplaar van de [Icon](../../com.aspose.drawing/icon) klasse van de opgegeven grootte vanuit het opgegeven bestand. |
| [Icon(Icon original, Size size)](#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-) | Initialiseert een nieuw exemplaar van de [Icon](../../com.aspose.drawing/icon) klasse en probeert een versie van het pictogram te vinden die overeenkomt met de gevraagde grootte. |
| [Icon(Object type, String resource)](#Icon-java.lang.Object-java.lang.String-) | Initialiseert een nieuw exemplaar van de [Icon](../../com.aspose.drawing/icon) klasse vanuit een resource in de opgegeven assembly. |
| [Icon(InputStream stream, Size size)](#Icon-java.io.InputStream-com.aspose.drawing.Size-) | Initialiseert een nieuw exemplaar van de [Icon](../../com.aspose.drawing/icon) klasse van de opgegeven grootte vanuit de opgegeven stream. |
| [Icon(String fileName, int width, int height)](#Icon-java.lang.String-int-int-) | Initialiseert een nieuw exemplaar van de [Icon](../../com.aspose.drawing/icon) klasse met de opgegeven breedte en hoogte uit het opgegeven bestand. |
| [Icon(Icon original, int width, int height)](#Icon-com.aspose.drawing.Icon-int-int-) | Initialiseert een nieuw exemplaar van de [Icon](../../com.aspose.drawing/icon) klasse en probeert een versie van het pictogram te vinden die overeenkomt met de gevraagde grootte.. |
| [Icon(InputStream stream, int width, int height)](#Icon-java.io.InputStream-int-int-) | Initialiseert een nieuw exemplaar van de [Icon](../../com.aspose.drawing/icon) klasse vanuit de opgegeven gegevensstroom en met de opgegeven breedte en hoogte. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getHandle()](#getHandle--) | Haalt de handle op voor dit [Icon](../../com.aspose.drawing/icon). |
| [getHeight()](#getHeight--) | Haalt de hoogte op van dit [Icon](../../com.aspose.drawing/icon). |
| [getSize()](#getSize--) | Haalt de grootte op van dit [Icon](../../com.aspose.drawing/icon). |
| [getWidth()](#getWidth--) | Haalt de breedte op van dit [Icon](../../com.aspose.drawing/icon). |
| [extractAssociatedIcon(String filePath)](#extractAssociatedIcon-java.lang.String-) | Retourneert een pictogramrepresentatie van een afbeelding die zich bevindt in het opgegeven bestand. |
| [fromHandle(byte[] handle)](#fromHandle-byte---) | Maakt een GDI+ [Icon](../../com.aspose.drawing/icon) aan vanuit de opgegeven Windows-handle naar een pictogram (HICON). |
| [deepClone()](#deepClone--) | Kloont het [Icon](../../com.aspose.drawing/icon) en maakt een duplicaatafbeelding. |
| [dispose()](#dispose--) | Voert door de toepassing gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet-beheerde bronnen. |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | Slaat dit [Icon](../../com.aspose.drawing/icon) op naar de opgegeven uitvoer java.io.InputStream. |
| [toBitmap()](#toBitmap--) | Converteert dit [Icon](../../com.aspose.drawing/icon) naar een GDI+ [Bitmap](../../com.aspose.drawing/bitmap). |
| [toString()](#toString--) | Haalt een menselijk leesbare tekenreeks op die het [Icon](../../com.aspose.drawing/icon) beschrijft. |
### Icon(String fileName) {#Icon-java.lang.String-}
```
public Icon(String fileName)
```


Initialiseert een nieuw exemplaar van de [Icon](../../com.aspose.drawing/icon) klasse vanuit de opgegeven bestandsnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | Het bestand waaruit het [Icon](../../com.aspose.drawing/icon) geladen moet worden. |

### Icon(InputStream stream) {#Icon-java.io.InputStream-}
```
public Icon(InputStream stream)
```


Initialiseert een nieuw exemplaar van de [Icon](../../com.aspose.drawing/icon) klasse vanuit de opgegeven datastroom.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De gegevensstroom waaruit het [Icon](../../com.aspose.drawing/icon) geladen moet worden. |

### Icon(String fileName, Size size) {#Icon-java.lang.String-com.aspose.drawing.Size-}
```
public Icon(String fileName, Size size)
```


Initialiseert een nieuw exemplaar van de [Icon](../../com.aspose.drawing/icon) klasse van de opgegeven grootte vanuit het opgegeven bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | De naam en het pad naar het bestand dat de pictogramgegevens bevat. |
| size | [Size](../../com.aspose.drawing/size) | De gewenste grootte van het pictogram. |

### Icon(Icon original, Size size) {#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-}
```
public Icon(Icon original, Size size)
```


Initialiseert een nieuw exemplaar van de [Icon](../../com.aspose.drawing/icon) klasse en probeert een versie van het pictogram te vinden die overeenkomt met de gevraagde grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | Het [Icon](../../com.aspose.drawing/icon) waaruit het nieuw formaat pictogram geladen moet worden. |
| size | [Size](../../com.aspose.drawing/size) | Een `Size`([.getSize](../../null/\#getSize)) structuur die de hoogte en breedte van het nieuwe [Icon](../../com.aspose.drawing/icon) specificeert. |

### Icon(Object type, String resource) {#Icon-java.lang.Object-java.lang.String-}
```
public Icon(Object type, String resource)
```


Initialiseert een nieuw exemplaar van de [Icon](../../com.aspose.drawing/icon) klasse vanuit een resource in de opgegeven assembly.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | java.lang.Object | Een Type dat de assembly specificeert waarin naar de resource gezocht moet worden. |
| resource | java.lang.String | De resource‑naam om te laden. |

### Icon(InputStream stream, Size size) {#Icon-java.io.InputStream-com.aspose.drawing.Size-}
```
public Icon(InputStream stream, Size size)
```


Initialiseert een nieuw exemplaar van de [Icon](../../com.aspose.drawing/icon) klasse van de opgegeven grootte vanuit de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | java.io.InputStream | De stroom die de pictogramgegevens bevat. |
| size | [Size](../../com.aspose.drawing/size) | De gewenste grootte van het pictogram. |

### Icon(String fileName, int width, int height) {#Icon-java.lang.String-int-int-}
```
public Icon(String fileName, int width, int height)
```


Initialiseert een nieuw exemplaar van de [Icon](../../com.aspose.drawing/icon) klasse met de opgegeven breedte en hoogte uit het opgegeven bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | De naam en het pad naar het bestand dat de [Icon](../../com.aspose.drawing/icon) gegevens bevat. |
| width | int | De gewenste breedte van het [Icon](../../com.aspose.drawing/icon). |
| height | int | De gewenste hoogte van de [Icon](../../com.aspose.drawing/icon). |

### Icon(Icon original, int width, int height) {#Icon-com.aspose.drawing.Icon-int-int-}
```
public Icon(Icon original, int width, int height)
```


Initialiseert een nieuw exemplaar van de [Icon](../../com.aspose.drawing/icon) klasse en probeert een versie van het pictogram te vinden die overeenkomt met de gevraagde grootte..

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | Het pictogram om de verschillende grootte van te laden. |
| breedte | int | De breedte van het nieuwe pictogram. |
| hoogte | int | De hoogte van het nieuwe pictogram. |

### Icon(InputStream stream, int width, int height) {#Icon-java.io.InputStream-int-int-}
```
public Icon(InputStream stream, int width, int height)
```


Initialiseert een nieuw exemplaar van de [Icon](../../com.aspose.drawing/icon) klasse vanuit de opgegeven gegevensstroom en met de opgegeven breedte en hoogte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | java.io.InputStream | De gegevensstroom waaruit het pictogram moet worden geladen. |
| breedte | int | De breedte, in pixels, van het pictogram. |
| hoogte | int | De hoogte, in pixels, van het pictogram. |

### getHandle() {#getHandle--}
```
public System.IntPtr getHandle()
```


Haalt de handle voor dit [Icon](../../com.aspose.drawing/icon). Dit is geen kopie van de handle; vrijgeven is niet toegestaan.

Waarde: De Windows-handle voor het pictogram.

**Returns:**
com.aspose.ms.System.IntPtr
### getHeight() {#getHeight--}
```
public int getHeight()
```


Haalt de hoogte op van dit [Icon](../../com.aspose.drawing/icon).

Waarde: De hoogte van dit [Icon](../../com.aspose.drawing/icon).

**Returns:**
int
### getSize() {#getSize--}
```
public Size getSize()
```


Haalt de grootte op van dit [Icon](../../com.aspose.drawing/icon).

Waarde: Een `Size`([.getSize](../../null/\#getSize)) structuur die de breedte en hoogte van dit [Icon](../../com.aspose.drawing/icon) specificeert.

**Returns:**
[Size](../../com.aspose.drawing/size)
### getWidth() {#getWidth--}
```
public int getWidth()
```


Haalt de breedte op van dit [Icon](../../com.aspose.drawing/icon).

Waarde: De breedte van dit [Icon](../../com.aspose.drawing/icon).

**Returns:**
int
### extractAssociatedIcon(String filePath) {#extractAssociatedIcon-java.lang.String-}
```
public static Icon extractAssociatedIcon(String filePath)
```


Retourneert een pictogramrepresentatie van een afbeelding die zich bevindt in het opgegeven bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het pad naar het bestand dat een afbeelding bevat. |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) representation of the image that is contained in the specified file.
### fromHandle(byte[] handle) {#fromHandle-byte---}
```
public static Icon fromHandle(byte[] handle)
```


Maakt een GDI+ [Icon](../../com.aspose.drawing/icon) aan vanuit de opgegeven Windows-handle naar een pictogram (HICON).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| handle | byte[] | Een Windows-handle naar een pictogram. |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) this method creates.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Kloont het [Icon](../../com.aspose.drawing/icon) en maakt een duplicaatafbeelding.

**Returns:**
java.lang.Object - Een object dat kan worden gecast naar een [Icon](../../com.aspose.drawing/icon).
### dispose() {#dispose--}
```
public void dispose()
```


Voert door de toepassing gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet-beheerde bronnen.

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


Slaat dit [Icon](../../com.aspose.drawing/icon) op naar de opgegeven uitvoer java.io.InputStream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| outputStream | java.io.OutputStream | De java.io.InputStream om naar op te slaan. |

### toBitmap() {#toBitmap--}
```
public Bitmap toBitmap()
```


Converteert dit [Icon](../../com.aspose.drawing/icon) naar een GDI+ [Bitmap](../../com.aspose.drawing/bitmap).

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - A [Bitmap](../../com.aspose.drawing/bitmap) that represents the converted [Icon](../../com.aspose.drawing/icon).
### toString() {#toString--}
```
public String toString()
```


Haalt een menselijk leesbare tekenreeks op die het [Icon](../../com.aspose.drawing/icon) beschrijft.

**Returns:**
java.lang.String - Een string die het [Icon](../../com.aspose.drawing/icon) beschrijft.
