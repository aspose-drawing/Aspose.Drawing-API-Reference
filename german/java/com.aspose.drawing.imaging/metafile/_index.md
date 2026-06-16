---
title: Metadatei
second_title: Aspose.Drawing für Java API-Referenz
description: Definiert eine grafische Metadatei.
type: docs
weight: 30
url: /de/java/com.aspose.drawing.imaging/metafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public final class Metafile extends Image
```

Definiert eine grafische Metadatei. Eine Metadatei enthält Datensätze, die eine Sequenz von Grafikoperationen beschreiben, die aufgezeichnet (erstellt) und wiedergegeben (angezeigt) werden können. Diese Klasse ist nicht vererbbar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Metafile(byte[] henhmetafile, boolean deleteEmf)](#Metafile-byte---boolean-) | Initialisiert eine neue Instanz der [Metafile](../../com.aspose.drawing.imaging/metafile) Klasse aus dem angegebenen Handle. |
| [Metafile(byte[] referenceHdc, int emfType)](#Metafile-byte---int-) | Initialisiert eine neue Instanz der [Metafile](../../com.aspose.drawing.imaging/metafile) Klasse aus dem angegebenen Handle zu einem Geräte-Kontext und einer [EmfType](../../com.aspose.drawing.imaging/emftype) Aufzählung, die das Format der [Metafile](../../com.aspose.drawing.imaging/metafile) angibt. |
| [Metafile(String filename)](#Metafile-java.lang.String-) | Initialisiert eine neue Instanz der [Metafile](../../com.aspose.drawing.imaging/metafile) Klasse aus dem angegebenen Dateinamen. |
| [Metafile(String filename, byte[] referenceHdc)](#Metafile-java.lang.String-byte---) | Initialisiert eine neue Instanz der [Metafile](../../com.aspose.drawing.imaging/metafile) Klasse aus dem angegebenen Dateinamen. |
| [Metafile(InputStream stream)](#Metafile-java.io.InputStream-) | Initialisiert eine neue Instanz der [Metafile](../../com.aspose.drawing.imaging/metafile) Klasse aus dem angegebenen Datenstrom. |
| [Metafile(InputStream stream, byte[] referenceHdc)](#Metafile-java.io.InputStream-byte---) | Initialisiert eine neue Instanz der [Metafile](../../com.aspose.drawing.imaging/metafile) Klasse aus dem angegebenen Datenstrom und einem Windows-Handle zu einem Geräte-Kontext. |
| [Metafile(System.IO.Stream stream, int type)](#Metafile-com.aspose.ms.System.IO.Stream-int-) | Initialisiert eine neue Instanz der [Metafile](../../com.aspose.drawing.imaging/metafile) Klasse aus dem angegebenen Datenstrom und einem Windows-Handle zu einem Geräte-Kontext. |
| [Metafile(InputStream stream, byte[] referenceHdc, int type)](#Metafile-java.io.InputStream-byte---int-) | Initialisiert eine neue Instanz der [Metafile](../../com.aspose.drawing.imaging/metafile) Klasse aus dem angegebenen Datenstrom, einem Windows-Handle zu einem Geräte-Kontext und einer [EmfType](../../com.aspose.drawing.imaging/emftype) Aufzählung, die das Format der [Metafile](../../com.aspose.drawing.imaging/metafile) angibt. |
| [Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)](#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-) | Initialisiert eine neue Instanz der [Metafile](../../com.aspose.drawing.imaging/metafile) Klasse aus dem angegebenen Datenstrom, einem Windows-Handle zu einem Geräte-Kontext und einer [EmfType](../../com.aspose.drawing.imaging/emftype) Aufzählung, die das Format der [Metafile](../../com.aspose.drawing.imaging/metafile) angibt. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getWidth()](#getWidth--) | Ermittelt die Breite in Pixeln dieser [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getHeight()](#getHeight--) | Ermittelt die Höhe in Pixeln dieser [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getRawFormat()](#getRawFormat--) | Ermittelt das Dateiformat dieses [Image](../../com.aspose.drawing/image). |
| [getPixelFormat()](#getPixelFormat--) | Ermittelt das Pixelformat dieses [Image](../../com.aspose.drawing/image). |
| [getPalette()](#getPalette--) | Liest oder legt die für dieses [Image](../../com.aspose.drawing/image) verwendete Farbpalette fest. |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | Liest oder legt die für dieses [Image](../../com.aspose.drawing/image) verwendete Farbpalette fest. |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | Ermittelt ein Array von GUIDs, das die Abmessungen der Frames innerhalb dieses [Image](../../com.aspose.drawing/image) darstellt. |
| [getPropertyIdList()](#getPropertyIdList--) | Ermittelt die IDs der in diesem [Image](../../com.aspose.drawing/image) gespeicherten Eigenschaftselemente. |
| [getPropertyItems()](#getPropertyItems--) | Ermittelt alle Eigenschaftselemente (Metadatenstücke), die in diesem [Image](../../com.aspose.drawing/image) gespeichert sind. |
| [getMetafileHeader(InputStream stream)](#getMetafileHeader-java.io.InputStream-) | Gibt den mit dem angegebenen [Metafile](../../com.aspose.drawing.imaging/metafile) verknüpften [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) zurück. |
| [getMetafileHeader(String fileName)](#getMetafileHeader-java.lang.String-) | Gibt den mit dem angegebenen [Metafile](../../com.aspose.drawing.imaging/metafile) verknüpften [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) zurück. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Diese Methode dreht, spiegelt oder dreht und spiegelt das [Image](../../com.aspose.drawing/image). |
| [getHenhmetafile()](#getHenhmetafile--) | Gibt ein Windows-Handle zu einer erweiterten [Metafile](../../com.aspose.drawing.imaging/metafile) zurück. |
| [playRecord(int recordType, int flags, int dataSize, byte[] dataArray)](#playRecord-int-int-int-byte---) | Spielt einen einzelnen Metadatei-Datensatz ab. |
| [getMetafileHeader()](#getMetafileHeader--) | Gibt den mit dieser [Metafile](../../com.aspose.drawing.imaging/metafile) verknüpften [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) zurück. |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | Ermittelt das angegebene Eigenschaftselement aus diesem [Image](../../com.aspose.drawing/image). |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | Entfernt das angegebene Eigenschaftselement aus diesem [Image](../../com.aspose.drawing/image). |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | Speichert ein Eigenschaftselement (Metadatenstück) in diesem [Image](../../com.aspose.drawing/image). |
### Metafile(byte[] henhmetafile, boolean deleteEmf) {#Metafile-byte---boolean-}
```
public Metafile(byte[] henhmetafile, boolean deleteEmf)
```


Initialisiert eine neue Instanz der [Metafile](../../com.aspose.drawing.imaging/metafile) Klasse aus dem angegebenen Handle.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| henhmetafile | byte[] | Ein Handle zu einer erweiterten Metadatei. |
| deleteEmf | boolean | true, um das Handle der erweiterten Metadatei zu löschen, wenn das [Metafile](../../com.aspose.drawing.imaging/metafile) gelöscht wird; andernfalls false. |

### Metafile(byte[] referenceHdc, int emfType) {#Metafile-byte---int-}
```
public Metafile(byte[] referenceHdc, int emfType)
```


Initialisiert eine neue Instanz der [Metafile](../../com.aspose.drawing.imaging/metafile) Klasse aus dem angegebenen Handle zu einem Geräte-Kontext und einer [EmfType](../../com.aspose.drawing.imaging/emftype) Aufzählung, die das Format der [Metafile](../../com.aspose.drawing.imaging/metafile) angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| referenceHdc | byte[] | Das Handle zu einem Geräte-Kontext. |
| emfType | int | Ein [EmfType](../../com.aspose.drawing.imaging/emftype) der das Format des [Metafile](../../com.aspose.drawing.imaging/metafile) angibt. |

### Metafile(String filename) {#Metafile-java.lang.String-}
```
public Metafile(String filename)
```


Initialisiert eine neue Instanz der [Metafile](../../com.aspose.drawing.imaging/metafile) Klasse aus dem angegebenen Dateinamen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | java.lang.String | Ein String, der den Dateinamen darstellt, aus dem das neue [Metafile](../../com.aspose.drawing.imaging/metafile) erstellt werden soll. |

### Metafile(String filename, byte[] referenceHdc) {#Metafile-java.lang.String-byte---}
```
public Metafile(String filename, byte[] referenceHdc)
```


Initialisiert eine neue Instanz der [Metafile](../../com.aspose.drawing.imaging/metafile) Klasse aus dem angegebenen Dateinamen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | java.lang.String | Ein String, der den Dateinamen darstellt, aus dem das neue [Metafile](../../com.aspose.drawing.imaging/metafile) erstellt werden soll. |
| referenceHdc | byte[] | Ein Windows-Handle zu einem Geräte-Kontext. |

### Metafile(InputStream stream) {#Metafile-java.io.InputStream-}
```
public Metafile(InputStream stream)
```


Initialisiert eine neue Instanz der [Metafile](../../com.aspose.drawing.imaging/metafile) Klasse aus dem angegebenen Datenstrom.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Der InputStream, aus dem das neue [Metafile](../../com.aspose.drawing.imaging/metafile) erstellt wird. |

### Metafile(InputStream stream, byte[] referenceHdc) {#Metafile-java.io.InputStream-byte---}
```
public Metafile(InputStream stream, byte[] referenceHdc)
```


Initialisiert eine neue Instanz der [Metafile](../../com.aspose.drawing.imaging/metafile) Klasse aus dem angegebenen Datenstrom und einem Windows-Handle zu einem Geräte-Kontext. />.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Ein InputStream, der die Daten für dieses [Metafile](../../com.aspose.drawing.imaging/metafile) enthält. |
| referenceHdc | byte[] | Ein Windows-Handle zu einem Geräte-Kontext des [Metafile](../../com.aspose.drawing.imaging/metafile) Objekts. |

### Metafile(System.IO.Stream stream, int type) {#Metafile-com.aspose.ms.System.IO.Stream-int-}
```
public Metafile(System.IO.Stream stream, int type)
```


Initialisiert eine neue Instanz der [Metafile](../../com.aspose.drawing.imaging/metafile) Klasse aus dem angegebenen Datenstrom und einem Windows-Handle zu einem Geräte-Kontext. />.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Ein InputStream, der die Daten für dieses [Metafile](../../com.aspose.drawing.imaging/metafile) enthält. |
| Typ | int | muss int 1 sein. |

### Metafile(InputStream stream, byte[] referenceHdc, int type) {#Metafile-java.io.InputStream-byte---int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, int type)
```


Initialisiert eine neue Instanz der [Metafile](../../com.aspose.drawing.imaging/metafile) Klasse aus dem angegebenen Datenstrom, einem Windows-Handle zu einem Geräte-Kontext und einer [EmfType](../../com.aspose.drawing.imaging/emftype) Aufzählung, die das Format der [Metafile](../../com.aspose.drawing.imaging/metafile) angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Ein InputStream, der die Daten für dieses [Metafile](../../com.aspose.drawing.imaging/metafile) enthält. |
| referenceHdc | byte[] | Ein Windows-Handle zu einem Geräte-Kontext. |
| type | int | Ein [EmfType](../../com.aspose.drawing.imaging/emftype) der das Format des [Metafile](../../com.aspose.drawing.imaging/metafile) angibt. |

### Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type) {#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)
```


Initialisiert eine neue Instanz der [Metafile](../../com.aspose.drawing.imaging/metafile) Klasse aus dem angegebenen Datenstrom, einem Windows-Handle zu einem Geräte-Kontext und einer [EmfType](../../com.aspose.drawing.imaging/emftype) Aufzählung, die das Format der [Metafile](../../com.aspose.drawing.imaging/metafile) angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Ein InputStream, der die Daten für dieses [Metafile](../../com.aspose.drawing.imaging/metafile) enthält. |
| referenceHdc | byte[] | Ein Windows-Handle zu einem Geräte-Kontext. |
| frameRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Ein [Rectangle](../../com.aspose.drawing/rectangle) der das Rechteck darstellt, das das neue [Metafile](../../com.aspose.drawing.imaging/metafile) begrenzt. |
| frameUnit | int | Ein [MetafileFrameUnit](../../com.aspose.drawing.imaging/metafileframeunit) der die Maßeinheit für frameRect angibt. |
| type | int | Ein [EmfType](../../com.aspose.drawing.imaging/emftype) der das Format des [Metafile](../../com.aspose.drawing.imaging/metafile) angibt. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Ermittelt die Breite in Pixeln dieser [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Ermittelt die Höhe in Pixeln dieser [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
int – die Höhe in Pixeln dieses [Metafile](../../com.aspose.drawing.imaging/metafile).
### getRawFormat() {#getRawFormat--}
```
public ImageFormat getRawFormat()
```


Ermittelt das Dateiformat dieses [Image](../../com.aspose.drawing/image).

**Returns:**
[ImageFormat](../../com.aspose.drawing.imaging/imageformat) - The [ImageFormat](../../com.aspose.drawing.imaging/imageformat) that represents the file format of this [Image](../../com.aspose.drawing/image).
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Ermittelt das Pixelformat dieses [Image](../../com.aspose.drawing/image).

**Returns:**
int – Ein `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) das das Pixel-Format für dieses [Image](../../com.aspose.drawing/image) darstellt.
### getPalette() {#getPalette--}
```
public ColorPalette getPalette()
```


Liest oder legt die für dieses [Image](../../com.aspose.drawing/image) verwendete Farbpalette fest.

**Returns:**
[ColorPalette](../../com.aspose.drawing.imaging/colorpalette) - A [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) that represents the color palette used for this [Image](../../com.aspose.drawing/image).
### setPalette(ColorPalette value) {#setPalette-com.aspose.drawing.imaging.ColorPalette-}
```
public void setPalette(ColorPalette value)
```


Liest oder legt die für dieses [Image](../../com.aspose.drawing/image) verwendete Farbpalette fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) |  |

### getFrameDimensionsList() {#getFrameDimensionsList--}
```
public UUID[] getFrameDimensionsList()
```


Ermittelt ein Array von GUIDs, das die Abmessungen der Frames innerhalb dieses [Image](../../com.aspose.drawing/image) darstellt.

**Returns:**
java.util.UUID[] – Ein Array von GUIDs, das die Abmessungen der Frames innerhalb dieses [Image](../../com.aspose.drawing/image) von höchstwertig zu niederwertig angibt.
### getPropertyIdList() {#getPropertyIdList--}
```
public int[] getPropertyIdList()
```


Ermittelt die IDs der in diesem [Image](../../com.aspose.drawing/image) gespeicherten Eigenschaftselemente.

**Returns:**
int[] – Ein Array der Eigenschafts-IDs, jeweils eine für jedes in diesem Bild gespeicherte Eigenschaftselement.
### getPropertyItems() {#getPropertyItems--}
```
public PropertyItem[] getPropertyItems()
```


Ermittelt alle Eigenschaftselemente (Metadatenstücke), die in diesem [Image](../../com.aspose.drawing/image) gespeichert sind.

**Returns:**
com.aspose.drawing.imaging.PropertyItem[] – Ein Array von [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) Objekten, jeweils eines für jedes in dem Bild gespeicherte Eigenschaftselement.
### getMetafileHeader(InputStream stream) {#getMetafileHeader-java.io.InputStream-}
```
public static MetafileHeader getMetafileHeader(InputStream stream)
```


Gibt den mit dem angegebenen [Metafile](../../com.aspose.drawing.imaging/metafile) verknüpften [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Ein InputStream, der das [Metafile](../../com.aspose.drawing.imaging/metafile) enthält, für das ein Header abgerufen wird. |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### getMetafileHeader(String fileName) {#getMetafileHeader-java.lang.String-}
```
public static MetafileHeader getMetafileHeader(String fileName)
```


Gibt den mit dem angegebenen [Metafile](../../com.aspose.drawing.imaging/metafile) verknüpften [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | java.lang.String | Ein String, der den Namen des [Metafile](../../com.aspose.drawing.imaging/metafile) enthält, für das ein Header abgerufen wird. |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Diese Methode dreht, spiegelt oder dreht und spiegelt das [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotateFlipType | int | Ein [RotateFlipType](../../com.aspose.drawing/rotatefliptype) Mitglied, das den Typ der Rotation und Spiegelung angibt, die auf das Bild angewendet werden soll. |

### getHenhmetafile() {#getHenhmetafile--}
```
public System.IntPtr getHenhmetafile()
```


Gibt ein Windows-Handle zu einer erweiterten [Metafile](../../com.aspose.drawing.imaging/metafile) zurück.

**Returns:**
com.aspose.ms.System.IntPtr – Ein Windows-Handle zu diesem erweiterten [Metafile](../../com.aspose.drawing.imaging/metafile).
### playRecord(int recordType, int flags, int dataSize, byte[] dataArray) {#playRecord-int-int-int-byte---}
```
public void playRecord(int recordType, int flags, int dataSize, byte[] dataArray)
```


Spielt einen einzelnen Metadatei-Datensatz ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| recordType | int | Element des [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype), das den Typ des abgespielten Metadatei‑Eintrags angibt. |
| flags | int | Eine Menge von Flags, die Attribute des Eintrags festlegen. |
| dataSize | int | Die Anzahl der Bytes in den Eintragsdaten. |
| dataArray | byte[] | Ein Array von Bytes, das die Eintragsdaten enthält. |

### getMetafileHeader() {#getMetafileHeader--}
```
public MetafileHeader getMetafileHeader()
```


Gibt den mit dieser [Metafile](../../com.aspose.drawing.imaging/metafile) verknüpften [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) zurück.

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with this [Metafile](../../com.aspose.drawing.imaging/metafile).
### getPropertyItem(int propid) {#getPropertyItem-int-}
```
public PropertyItem getPropertyItem(int propid)
```


Ermittelt das angegebene Eigenschaftselement aus diesem [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| propid | int | Die ID des abzurufenden Property‑Elements. |

**Returns:**
[PropertyItem](../../com.aspose.drawing.imaging/propertyitem) - The [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) this method gets.
### removePropertyItem(int propid) {#removePropertyItem-int-}
```
public void removePropertyItem(int propid)
```


Entfernt das angegebene Eigenschaftselement aus diesem [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| propid | int | Die ID des zu entfernenden Property‑Elements. |

### setPropertyItem(PropertyItem propitem) {#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-}
```
public void setPropertyItem(PropertyItem propitem)
```


Speichert ein Eigenschaftselement (Metadatenstück) in diesem [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| propitem | [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) | Das [PropertyItem](../../com.aspose.drawing.imaging/propertyitem), das gespeichert werden soll. |

