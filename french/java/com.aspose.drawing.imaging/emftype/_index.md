---
title: EmfType
second_title: Référence de l'API Aspose.Drawing pour Java
description: Spécifie la nature des enregistrements placés dans un fichier Enhanced Metafile EMF.
type: docs
weight: 18
url: /fr/java/com.aspose.drawing.imaging/emftype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfType extends System.Enum
```

Spécifie la nature des enregistrements placés dans un fichier Enhanced Metafile (EMF). Cette énumération est utilisée par plusieurs constructeurs de la classe [Metafile](../../com.aspose.drawing.imaging/metafile).
## Champs

| Champ | Description |
| --- | --- |
| [EmfOnly](#EmfOnly) | Spécifie que tous les enregistrements du métafichier sont des enregistrements EMF, qui peuvent être affichés par GDI ou GDI+. |
| [EmfPlusOnly](#EmfPlusOnly) | Spécifie que tous les enregistrements du métafichier sont des enregistrements EMF+, qui peuvent être affichés par GDI+ mais pas par GDI. |
| [EmfPlusDual](#EmfPlusDual) | Spécifie que tous les enregistrements EMF+ du métafichier sont associés à un enregistrement EMF alternatif. |
### EmfOnly {#EmfOnly}
```
public static final int EmfOnly
```


Spécifie que tous les enregistrements du métafichier sont des enregistrements EMF, qui peuvent être affichés par GDI ou GDI+.

### EmfPlusOnly {#EmfPlusOnly}
```
public static final int EmfPlusOnly
```


Spécifie que tous les enregistrements du métafichier sont des enregistrements EMF+, qui peuvent être affichés par GDI+ mais pas par GDI.

### EmfPlusDual {#EmfPlusDual}
```
public static final int EmfPlusDual
```


Spécifie que tous les enregistrements EMF+ du métafichier sont associés à un enregistrement EMF alternatif. Les métafichiers de type `EmfType.EmfPlusDual` peuvent être affichés par GDI ou par GDI+.

