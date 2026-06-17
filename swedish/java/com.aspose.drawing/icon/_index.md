---
title: Ikon
second_title: Aspose.Drawing för Java API‑referens
description: Representerar en Windows‑ikon som är en liten bitmap‑bild som används för att representera ett objekt.
type: docs
weight: 29
url: /sv/java/com.aspose.drawing/icon/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.ms.System.IDisposable
```
public final class Icon implements System.ICloneable, System.IDisposable
```

Representerar en Windows‑ikon, som är en liten bitmap‑bild som används för att representera ett objekt. Ikoner kan betraktas som transparenta bitmaps, även om deras storlek bestäms av systemet.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Icon(String fileName)](#Icon-java.lang.String-) | Initierar en ny instans av klassen [Icon](../../com.aspose.drawing/icon) från det angivna filnamnet. |
| [Icon(InputStream stream)](#Icon-java.io.InputStream-) | Initierar en ny instans av klassen [Icon](../../com.aspose.drawing/icon) från den angivna datastreamen. |
| [Icon(String fileName, Size size)](#Icon-java.lang.String-com.aspose.drawing.Size-) | Initierar en ny instans av klassen [Icon](../../com.aspose.drawing/icon) med den angivna storleken från den angivna filen. |
| [Icon(Icon original, Size size)](#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-) | Initierar en ny instans av klassen [Icon](../../com.aspose.drawing/icon) och försöker hitta en version av ikonen som matchar den begärda storleken. |
| [Icon(Object type, String resource)](#Icon-java.lang.Object-java.lang.String-) | Initierar en ny instans av klassen [Icon](../../com.aspose.drawing/icon) från en resurs i den angivna sammansättningen. |
| [Icon(InputStream stream, Size size)](#Icon-java.io.InputStream-com.aspose.drawing.Size-) | Initierar en ny instans av klassen [Icon](../../com.aspose.drawing/icon) med den angivna storleken från den angivna strömmen. |
| [Icon(String fileName, int width, int height)](#Icon-java.lang.String-int-int-) | Initierar en ny instans av klassen [Icon](../../com.aspose.drawing/icon) med den angivna bredden och höjden från den angivna filen. |
| [Icon(Icon original, int width, int height)](#Icon-com.aspose.drawing.Icon-int-int-) | Initierar en ny instans av klassen [Icon](../../com.aspose.drawing/icon) och försöker hitta en version av ikonen som matchar den begärda storleken. |
| [Icon(InputStream stream, int width, int height)](#Icon-java.io.InputStream-int-int-) | Initierar en ny instans av klassen [Icon](../../com.aspose.drawing/icon) från den angivna datastreamen och med den angivna bredden och höjden. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHandle()](#getHandle--) | Hämtar handtaget för denna [Icon](../../com.aspose.drawing/icon). |
| [getHeight()](#getHeight--) | Hämtar höjden på denna [Icon](../../com.aspose.drawing/icon). |
| [getSize()](#getSize--) | Hämtar storleken på denna [Icon](../../com.aspose.drawing/icon). |
| [getWidth()](#getWidth--) | Hämtar bredden på denna [Icon](../../com.aspose.drawing/icon). |
| [extractAssociatedIcon(String filePath)](#extractAssociatedIcon-java.lang.String-) | Returnerar en ikonrepresentation av en bild som finns i den angivna filen. |
| [fromHandle(byte[] handle)](#fromHandle-byte---) | Skapar en GDI+ [Icon](../../com.aspose.drawing/icon) från den angivna Windows-handtaget till en ikon (HICON). |
| [deepClone()](#deepClone--) | Klonar [Icon](../../com.aspose.drawing/icon) och skapar en duplicerad bild. |
| [dispose()](#dispose--) | Utför applikationsdefinierade uppgifter som är relaterade till att frigöra, släppa eller återställa ohanterade resurser. |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | Sparar denna [Icon](../../com.aspose.drawing/icon) till den angivna utdata‑strömmen java.io.InputStream. |
| [toBitmap()](#toBitmap--) | Konverterar denna [Icon](../../com.aspose.drawing/icon) till en GDI+ [Bitmap](../../com.aspose.drawing/bitmap). |
| [toString()](#toString--) | Hämtar en människoläsbar sträng som beskriver [Icon](../../com.aspose.drawing/icon). |
### Icon(String fileName) {#Icon-java.lang.String-}
```
public Icon(String fileName)
```


Initierar en ny instans av klassen [Icon](../../com.aspose.drawing/icon) från det angivna filnamnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filen att läsa in [Icon](../../com.aspose.drawing/icon) från. |

### Icon(InputStream stream) {#Icon-java.io.InputStream-}
```
public Icon(InputStream stream)
```


Initierar en ny instans av klassen [Icon](../../com.aspose.drawing/icon) från den angivna datastreamen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Datastreamen som [Icon](../../com.aspose.drawing/icon) ska läsas in från. |

### Icon(String fileName, Size size) {#Icon-java.lang.String-com.aspose.drawing.Size-}
```
public Icon(String fileName, Size size)
```


Initierar en ny instans av klassen [Icon](../../com.aspose.drawing/icon) med den angivna storleken från den angivna filen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Namnet och sökvägen till filen som innehåller ikon‑data. |
| size | [Size](../../com.aspose.drawing/size) | Den önskade storleken på ikonen. |

### Icon(Icon original, Size size) {#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-}
```
public Icon(Icon original, Size size)
```


Initierar en ny instans av klassen [Icon](../../com.aspose.drawing/icon) och försöker hitta en version av ikonen som matchar den begärda storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | Den [Icon](../../com.aspose.drawing/icon) som den nystorleksändrade ikonen ska laddas från. |
| size | [Size](../../com.aspose.drawing/size) | En `Size`([.getSize](../../null/\#getSize))-struktur som specificerar höjden och bredden på den nya [Icon](../../com.aspose.drawing/icon). |

### Icon(Object type, String resource) {#Icon-java.lang.Object-java.lang.String-}
```
public Icon(Object type, String resource)
```


Initierar en ny instans av klassen [Icon](../../com.aspose.drawing/icon) från en resurs i den angivna sammansättningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | java.lang.Object | En Type som specificerar den samling där resursen ska sökas. |
| resurs | java.lang.String | Resursnamnet att läsa in. |

### Icon(InputStream stream, Size size) {#Icon-java.io.InputStream-com.aspose.drawing.Size-}
```
public Icon(InputStream stream, Size size)
```


Initierar en ny instans av klassen [Icon](../../com.aspose.drawing/icon) med den angivna storleken från den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen som innehåller ikon‑data. |
| size | [Size](../../com.aspose.drawing/size) | Den önskade storleken på ikonen. |

### Icon(String fileName, int width, int height) {#Icon-java.lang.String-int-int-}
```
public Icon(String fileName, int width, int height)
```


Initierar en ny instans av klassen [Icon](../../com.aspose.drawing/icon) med den angivna bredden och höjden från den angivna filen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Namnet och sökvägen till filen som innehåller [Icon](../../com.aspose.drawing/icon)-data. |
| width | int | Den önskade bredden på [Icon](../../com.aspose.drawing/icon). |
| height | int | Den önskade höjden på [Icon](../../com.aspose.drawing/icon). |

### Icon(Icon original, int width, int height) {#Icon-com.aspose.drawing.Icon-int-int-}
```
public Icon(Icon original, int width, int height)
```


Initierar en ny instans av klassen [Icon](../../com.aspose.drawing/icon) och försöker hitta en version av ikonen som matchar den begärda storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | Ikonen att ladda den olika storleken från. |
| bredd | int | Bredden på den nya ikonen. |
| höjd | int | Höjden på den nya ikonen. |

### Icon(InputStream stream, int width, int height) {#Icon-java.io.InputStream-int-int-}
```
public Icon(InputStream stream, int width, int height)
```


Initierar en ny instans av klassen [Icon](../../com.aspose.drawing/icon) från den angivna datastreamen och med den angivna bredden och höjden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Datastreamen från vilken ikonen ska laddas. |
| bredd | int | Bredden, i pixlar, på ikonen. |
| höjd | int | Höjden, i pixlar, på ikonen. |

### getHandle() {#getHandle--}
```
public System.IntPtr getHandle()
```


Hämtar handtaget för denna [Icon](../../com.aspose.drawing/icon). Detta är inte en kopia av handtaget; frigör det inte.

Värde: Windows-handtaget för ikonen.

**Returns:**
com.aspose.ms.System.IntPtr
### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar höjden på denna [Icon](../../com.aspose.drawing/icon).

Värde: Höjden på denna [Icon](../../com.aspose.drawing/icon).

**Returns:**
int
### getSize() {#getSize--}
```
public Size getSize()
```


Hämtar storleken på denna [Icon](../../com.aspose.drawing/icon).

Värde: En `Size`([.getSize](../../null/\#getSize)) struktur som specificerar bredden och höjden på denna [Icon](../../com.aspose.drawing/icon).

**Returns:**
[Size](../../com.aspose.drawing/size)
### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar bredden på denna [Icon](../../com.aspose.drawing/icon).

Värde: Bredden på denna [Icon](../../com.aspose.drawing/icon).

**Returns:**
int
### extractAssociatedIcon(String filePath) {#extractAssociatedIcon-java.lang.String-}
```
public static Icon extractAssociatedIcon(String filePath)
```


Returnerar en ikonrepresentation av en bild som finns i den angivna filen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Sökvägen till filen som innehåller en bild. |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) representation of the image that is contained in the specified file.
### fromHandle(byte[] handle) {#fromHandle-byte---}
```
public static Icon fromHandle(byte[] handle)
```


Skapar en GDI+ [Icon](../../com.aspose.drawing/icon) från den angivna Windows-handtaget till en ikon (HICON).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| handle | byte[] | Ett Windows-handtag till en ikon. |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) this method creates.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Klonar [Icon](../../com.aspose.drawing/icon) och skapar en duplicerad bild.

**Returns:**
java.lang.Object - Ett objekt som kan kastas till en [Icon](../../com.aspose.drawing/icon).
### dispose() {#dispose--}
```
public void dispose()
```


Utför applikationsdefinierade uppgifter som är relaterade till att frigöra, släppa eller återställa ohanterade resurser.

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


Sparar denna [Icon](../../com.aspose.drawing/icon) till den angivna utdata‑strömmen java.io.InputStream.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Den java.io.InputStream att spara till. |

### toBitmap() {#toBitmap--}
```
public Bitmap toBitmap()
```


Konverterar denna [Icon](../../com.aspose.drawing/icon) till en GDI+ [Bitmap](../../com.aspose.drawing/bitmap).

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - A [Bitmap](../../com.aspose.drawing/bitmap) that represents the converted [Icon](../../com.aspose.drawing/icon).
### toString() {#toString--}
```
public String toString()
```


Hämtar en människoläsbar sträng som beskriver [Icon](../../com.aspose.drawing/icon).

**Returns:**
java.lang.String - En sträng som beskriver [Icon](../../com.aspose.drawing/icon).
