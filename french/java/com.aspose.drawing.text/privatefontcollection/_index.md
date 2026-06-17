---
title: PrivateFontCollection
second_title: Référence de l'API Aspose.Drawing pour Java
description: Fournit une collection de familles de polices construites à partir de fichiers de polices fournis par l'application cliente.
type: docs
weight: 13
url: /fr/java/com.aspose.drawing.text/privatefontcollection/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.FontCollection](../../com.aspose.drawing/fontcollection)
```
public final class PrivateFontCollection extends FontCollection
```

Fournit une collection de familles de polices construites à partir de fichiers de polices fournis par l'application cliente.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PrivateFontCollection()](#PrivateFontCollection--) | Initialise une nouvelle instance de la classe [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addFontFile(String filename)](#addFontFile-java.lang.String-) | Ajoute une police depuis le fichier spécifié à cette [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection). |
| [addMemoryFont(byte[] memory, int length)](#addMemoryFont-byte---int-) | Ajoute une police contenue dans la mémoire du système à cette [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection). |
### PrivateFontCollection() {#PrivateFontCollection--}
```
public PrivateFontCollection()
```


Initialise une nouvelle instance de la classe [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection).

### addFontFile(String filename) {#addFontFile-java.lang.String-}
```
public void addFontFile(String filename)
```


Ajoute une police depuis le fichier spécifié à cette [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom de fichier | java.lang.String | Une chaîne qui contient le nom de fichier de la police à ajouter. |

### addMemoryFont(byte[] memory, int length) {#addMemoryFont-byte---int-}
```
public void addMemoryFont(byte[] memory, int length)
```


Ajoute une police contenue dans la mémoire du système à cette [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mémoire | byte[] | L'adresse mémoire de la police à ajouter. |
| longueur | int | La longueur mémoire de la police à ajouter. |

