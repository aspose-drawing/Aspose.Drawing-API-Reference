---
title: PrivateFontCollection
second_title: Referencia de la API de Aspose.Drawing para Java
description: Proporciona una colección de familias de fuentes construidas a partir de archivos de fuentes que son suministrados por la aplicación cliente.
type: docs
weight: 13
url: /es/java/com.aspose.drawing.text/privatefontcollection/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.FontCollection](../../com.aspose.drawing/fontcollection)
```
public final class PrivateFontCollection extends FontCollection
```

Proporciona una colección de familias de fuentes construidas a partir de archivos de fuentes que son suministrados por la aplicación cliente.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PrivateFontCollection()](#PrivateFontCollection--) | Inicializa una nueva instancia de la clase [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection). |
## Métodos

| Método | Descripción |
| --- | --- |
| [addFontFile(String filename)](#addFontFile-java.lang.String-) | Agrega una fuente del archivo especificado a esta [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection). |
| [addMemoryFont(byte[] memory, int length)](#addMemoryFont-byte---int-) | Agrega una fuente contenida en la memoria del sistema a esta [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection). |
### PrivateFontCollection() {#PrivateFontCollection--}
```
public PrivateFontCollection()
```


Inicializa una nueva instancia de la clase [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection).

### addFontFile(String filename) {#addFontFile-java.lang.String-}
```
public void addFontFile(String filename)
```


Agrega una fuente del archivo especificado a esta [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre de archivo | java.lang.String | Una cadena que contiene el nombre de archivo de la fuente a agregar. |

### addMemoryFont(byte[] memory, int length) {#addMemoryFont-byte---int-}
```
public void addMemoryFont(byte[] memory, int length)
```


Agrega una fuente contenida en la memoria del sistema a esta [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| memoria | byte[] | La dirección de memoria de la fuente a agregar. |
| length | int | La longitud de memoria de la fuente a agregar. |

