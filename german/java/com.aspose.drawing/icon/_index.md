---
title: Icon
second_title: Aspose.Drawing für Java API-Referenz
description: Stellt ein Windows‑Symbol dar, das ein kleines Bitmap‑Bild ist, das verwendet wird, um ein Objekt zu repräsentieren.
type: docs
weight: 29
url: /de/java/com.aspose.drawing/icon/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.ms.System.IDisposable
```
public final class Icon implements System.ICloneable, System.IDisposable
```

Stellt ein Windows‑Symbol dar, das ein kleines Bitmap‑Bild ist, das verwendet wird, um ein Objekt zu repräsentieren. Symbole können als transparente Bitmaps betrachtet werden, obwohl ihre Größe vom System bestimmt wird.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Icon(String fileName)](#Icon-java.lang.String-) | Initialisiert eine neue Instanz der [Icon](../../com.aspose.drawing/icon)-Klasse aus dem angegebenen Dateinamen. |
| [Icon(InputStream stream)](#Icon-java.io.InputStream-) | Initialisiert eine neue Instanz der [Icon](../../com.aspose.drawing/icon)-Klasse aus dem angegebenen Datenstrom. |
| [Icon(String fileName, Size size)](#Icon-java.lang.String-com.aspose.drawing.Size-) | Initialisiert eine neue Instanz der [Icon](../../com.aspose.drawing/icon)-Klasse mit der angegebenen Größe aus der angegebenen Datei. |
| [Icon(Icon original, Size size)](#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-) | Initialisiert eine neue Instanz der [Icon](../../com.aspose.drawing/icon)-Klasse und versucht, eine Version des Symbols zu finden, die der angeforderten Größe entspricht. |
| [Icon(Object type, String resource)](#Icon-java.lang.Object-java.lang.String-) | Initialisiert eine neue Instanz der [Icon](../../com.aspose.drawing/icon)-Klasse aus einer Ressource in der angegebenen Assembly. |
| [Icon(InputStream stream, Size size)](#Icon-java.io.InputStream-com.aspose.drawing.Size-) | Initialisiert eine neue Instanz der [Icon](../../com.aspose.drawing/icon)-Klasse mit der angegebenen Größe aus dem angegebenen Stream. |
| [Icon(String fileName, int width, int height)](#Icon-java.lang.String-int-int-) | Initialisiert eine neue Instanz der [Icon](../../com.aspose.drawing/icon)-Klasse mit der angegebenen Breite und Höhe aus der angegebenen Datei. |
| [Icon(Icon original, int width, int height)](#Icon-com.aspose.drawing.Icon-int-int-) | Initialisiert eine neue Instanz der [Icon](../../com.aspose.drawing/icon)-Klasse und versucht, eine Version des Icons zu finden, die der angeforderten Größe entspricht. |
| [Icon(InputStream stream, int width, int height)](#Icon-java.io.InputStream-int-int-) | Initialisiert eine neue Instanz der [Icon](../../com.aspose.drawing/icon)-Klasse aus dem angegebenen Datenstrom und mit der angegebenen Breite und Höhe. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHandle()](#getHandle--) | Liefert den Handle für dieses [Icon](../../com.aspose.drawing/icon). |
| [getHeight()](#getHeight--) | Liefert die Höhe dieses [Icon](../../com.aspose.drawing/icon). |
| [getSize()](#getSize--) | Liefert die Größe dieses [Icon](../../com.aspose.drawing/icon). |
| [getWidth()](#getWidth--) | Liefert die Breite dieses [Icon](../../com.aspose.drawing/icon). |
| [extractAssociatedIcon(String filePath)](#extractAssociatedIcon-java.lang.String-) | Gibt eine Icon-Darstellung eines Bildes zurück, das in der angegebenen Datei enthalten ist. |
| [fromHandle(byte[] handle)](#fromHandle-byte---) | Erstellt ein GDI+ [Icon](../../com.aspose.drawing/icon) aus dem angegebenen Windows-Handle für ein Icon (HICON). |
| [deepClone()](#deepClone--) | Klonen Sie das [Icon](../../com.aspose.drawing/icon), wodurch ein Duplikatbild entsteht. |
| [dispose()](#dispose--) | Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen von nicht verwalteten Ressourcen verbunden sind. |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | Speichert dieses [Icon](../../com.aspose.drawing/icon) in den angegebenen Ausgabe‑java.io.InputStream. |
| [toBitmap()](#toBitmap--) | Konvertiert dieses [Icon](../../com.aspose.drawing/icon) in ein GDI+ [Bitmap](../../com.aspose.drawing/bitmap). |
| [toString()](#toString--) | Liefert einen menschenlesbaren String, der das [Icon](../../com.aspose.drawing/icon) beschreibt. |
### Icon(String fileName) {#Icon-java.lang.String-}
```
public Icon(String fileName)
```


Initialisiert eine neue Instanz der [Icon](../../com.aspose.drawing/icon)-Klasse aus dem angegebenen Dateinamen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | java.lang.String | Die Datei, aus der das [Icon](../../com.aspose.drawing/icon) geladen werden soll. |

### Icon(InputStream stream) {#Icon-java.io.InputStream-}
```
public Icon(InputStream stream)
```


Initialisiert eine neue Instanz der [Icon](../../com.aspose.drawing/icon)-Klasse aus dem angegebenen Datenstrom.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Der Datenstrom, aus dem das [Icon](../../com.aspose.drawing/icon) geladen werden soll. |

### Icon(String fileName, Size size) {#Icon-java.lang.String-com.aspose.drawing.Size-}
```
public Icon(String fileName, Size size)
```


Initialisiert eine neue Instanz der [Icon](../../com.aspose.drawing/icon)-Klasse mit der angegebenen Größe aus der angegebenen Datei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | java.lang.String | Der Name und Pfad zu der Datei, die die Icon-Daten enthält. |
| size | [Size](../../com.aspose.drawing/size) | Die gewünschte Größe des Icons. |

### Icon(Icon original, Size size) {#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-}
```
public Icon(Icon original, Size size)
```


Initialisiert eine neue Instanz der [Icon](../../com.aspose.drawing/icon)-Klasse und versucht, eine Version des Symbols zu finden, die der angeforderten Größe entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | Das [Icon](../../com.aspose.drawing/icon), aus dem das neu skalierte Icon geladen werden soll. |
| size | [Size](../../com.aspose.drawing/size) | Eine `Size`([.getSize](../../null/\#getSize))-Struktur, die die Höhe und Breite des neuen [Icon](../../com.aspose.drawing/icon) angibt. |

### Icon(Object type, String resource) {#Icon-java.lang.Object-java.lang.String-}
```
public Icon(Object type, String resource)
```


Initialisiert eine neue Instanz der [Icon](../../com.aspose.drawing/icon)-Klasse aus einer Ressource in der angegebenen Assembly.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | java.lang.Object | Ein Typ, der die Assembly angibt, in der nach der Ressource gesucht werden soll. |
| Ressource | java.lang.String | Der Name der zu ladenden Ressource. |

### Icon(InputStream stream, Size size) {#Icon-java.io.InputStream-com.aspose.drawing.Size-}
```
public Icon(InputStream stream, Size size)
```


Initialisiert eine neue Instanz der [Icon](../../com.aspose.drawing/icon)-Klasse mit der angegebenen Größe aus dem angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream, der die Icon-Daten enthält. |
| size | [Size](../../com.aspose.drawing/size) | Die gewünschte Größe des Icons. |

### Icon(String fileName, int width, int height) {#Icon-java.lang.String-int-int-}
```
public Icon(String fileName, int width, int height)
```


Initialisiert eine neue Instanz der [Icon](../../com.aspose.drawing/icon)-Klasse mit der angegebenen Breite und Höhe aus der angegebenen Datei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | java.lang.String | Der Name und Pfad zu der Datei, die die [Icon](../../com.aspose.drawing/icon)-Daten enthält. |
| width | int | Die gewünschte Breite des [Icon](../../com.aspose.drawing/icon). |
| height | int | Die gewünschte Höhe des [Icon](../../com.aspose.drawing/icon). |

### Icon(Icon original, int width, int height) {#Icon-com.aspose.drawing.Icon-int-int-}
```
public Icon(Icon original, int width, int height)
```


Initialisiert eine neue Instanz der [Icon](../../com.aspose.drawing/icon)-Klasse und versucht, eine Version des Icons zu finden, die der angeforderten Größe entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | Das Icon, aus dem die andere Größe geladen werden soll. |
| Breite | int | Die Breite des neuen Icons. |
| Höhe | int | Die Höhe des neuen Icons. |

### Icon(InputStream stream, int width, int height) {#Icon-java.io.InputStream-int-int-}
```
public Icon(InputStream stream, int width, int height)
```


Initialisiert eine neue Instanz der [Icon](../../com.aspose.drawing/icon)-Klasse aus dem angegebenen Datenstrom und mit der angegebenen Breite und Höhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Datenstrom, aus dem das Icon geladen werden soll. |
| Breite | int | Die Breite des Icons in Pixeln. |
| Höhe | int | Die Höhe des Icons in Pixeln. |

### getHandle() {#getHandle--}
```
public System.IntPtr getHandle()
```


Liefert den Handle für dieses [Icon](../../com.aspose.drawing/icon). Dies ist keine Kopie des Handles; geben Sie ihn nicht frei.

Wert: Der Windows-Handle für das Icon.

**Returns:**
com.aspose.ms.System.IntPtr
### getHeight() {#getHeight--}
```
public int getHeight()
```


Liefert die Höhe dieses [Icon](../../com.aspose.drawing/icon).

Wert: Die Höhe dieses [Icon](../../com.aspose.drawing/icon).

**Returns:**
int
### getSize() {#getSize--}
```
public Size getSize()
```


Liefert die Größe dieses [Icon](../../com.aspose.drawing/icon).

Wert: Eine `Size`([.getSize](../../null/\#getSize))-Struktur, die die Breite und Höhe dieses [Icon](../../com.aspose.drawing/icon) angibt.

**Returns:**
[Size](../../com.aspose.drawing/size)
### getWidth() {#getWidth--}
```
public int getWidth()
```


Liefert die Breite dieses [Icon](../../com.aspose.drawing/icon).

Wert: Die Breite dieses [Icon](../../com.aspose.drawing/icon).

**Returns:**
int
### extractAssociatedIcon(String filePath) {#extractAssociatedIcon-java.lang.String-}
```
public static Icon extractAssociatedIcon(String filePath)
```


Gibt eine Icon-Darstellung eines Bildes zurück, das in der angegebenen Datei enthalten ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Pfad zu der Datei, die ein Bild enthält. |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) representation of the image that is contained in the specified file.
### fromHandle(byte[] handle) {#fromHandle-byte---}
```
public static Icon fromHandle(byte[] handle)
```


Erstellt ein GDI+ [Icon](../../com.aspose.drawing/icon) aus dem angegebenen Windows-Handle für ein Icon (HICON).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| handle | byte[] | Ein Windows-Handle zu einem Icon. |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) this method creates.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Klonen Sie das [Icon](../../com.aspose.drawing/icon), wodurch ein Duplikatbild entsteht.

**Returns:**
java.lang.Object - Ein Objekt, das in ein [Icon](../../com.aspose.drawing/icon) umgewandelt werden kann.
### dispose() {#dispose--}
```
public void dispose()
```


Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen von nicht verwalteten Ressourcen verbunden sind.

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


Speichert dieses [Icon](../../com.aspose.drawing/icon) in den angegebenen Ausgabe‑java.io.InputStream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Der java.io.InputStream, in den gespeichert werden soll. |

### toBitmap() {#toBitmap--}
```
public Bitmap toBitmap()
```


Konvertiert dieses [Icon](../../com.aspose.drawing/icon) in ein GDI+ [Bitmap](../../com.aspose.drawing/bitmap).

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - A [Bitmap](../../com.aspose.drawing/bitmap) that represents the converted [Icon](../../com.aspose.drawing/icon).
### toString() {#toString--}
```
public String toString()
```


Liefert einen menschenlesbaren String, der das [Icon](../../com.aspose.drawing/icon) beschreibt.

**Returns:**
java.lang.String - Ein String, der das [Icon](../../com.aspose.drawing/icon) beschreibt.
