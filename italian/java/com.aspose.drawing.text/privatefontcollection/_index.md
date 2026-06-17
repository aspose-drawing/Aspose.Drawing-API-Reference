---
title: PrivateFontCollection
second_title: Riferimento API di Aspose.Drawing per Java
description: Fornisce una raccolta di famiglie di caratteri costruite a partire da file di caratteri forniti dall'applicazione client.
type: docs
weight: 13
url: /it/java/com.aspose.drawing.text/privatefontcollection/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.FontCollection](../../com.aspose.drawing/fontcollection)
```
public final class PrivateFontCollection extends FontCollection
```

Fornisce una raccolta di famiglie di caratteri costruite a partire da file di caratteri forniti dall'applicazione client.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PrivateFontCollection()](#PrivateFontCollection--) | Inizializza una nuova istanza della classe [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addFontFile(String filename)](#addFontFile-java.lang.String-) | Aggiunge un carattere dal file specificato a questa [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection). |
| [addMemoryFont(byte[] memory, int length)](#addMemoryFont-byte---int-) | Aggiunge un carattere contenuto nella memoria di sistema a questa [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection). |
### PrivateFontCollection() {#PrivateFontCollection--}
```
public PrivateFontCollection()
```


Inizializza una nuova istanza della classe [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection).

### addFontFile(String filename) {#addFontFile-java.lang.String-}
```
public void addFontFile(String filename)
```


Aggiunge un carattere dal file specificato a questa [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nomefile | java.lang.String | Una stringa che contiene il nome file del carattere da aggiungere. |

### addMemoryFont(byte[] memory, int length) {#addMemoryFont-byte---int-}
```
public void addMemoryFont(byte[] memory, int length)
```


Aggiunge un carattere contenuto nella memoria di sistema a questa [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| memoria | byte[] | L'indirizzo di memoria del carattere da aggiungere. |
| lunghezza | int | La lunghezza di memoria del carattere da aggiungere. |

