---
title: MetafileType
second_title: Référence de l'API Aspose.Drawing pour Java
description: Spécifie les types de métafichiers.
type: docs
weight: 33
url: /fr/java/com.aspose.drawing.imaging/metafiletype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MetafileType extends System.Enum
```

Spécifie les types de métafichiers.
## Champs

| Champ | Description |
| --- | --- |
| [Invalid](#Invalid) | Spécifie un format de métafichier qui n'est pas reconnu dans GDI+. |
| [Wmf](#Wmf) | Spécifie un fichier WMF (Windows Metafile). |
| [WmfPlaceable](#WmfPlaceable) | Spécifie un fichier WMF (Windows Metafile) qui possède un en-tête de métafichier placable au début. |
| [Emf](#Emf) | Spécifie un fichier Enhanced Metafile (EMF). |
| [EmfPlusOnly](#EmfPlusOnly) | Spécifie un fichier EMF+. |
| [EmfPlusDual](#EmfPlusDual) | Spécifie un fichier EMF+ Dual. |
### Invalid {#Invalid}
```
public static final int Invalid
```


Spécifie un format de métafichier qui n'est pas reconnu dans GDI+.

### Wmf {#Wmf}
```
public static final int Wmf
```


Spécifie un fichier WMF (Windows Metafile). Un tel fichier ne contient que des enregistrements GDI.

### WmfPlaceable {#WmfPlaceable}
```
public static final int WmfPlaceable
```


Spécifie un fichier WMF (Windows Metafile) qui possède un en-tête de métafichier placable au début.

### Emf {#Emf}
```
public static final int Emf
```


Spécifie un fichier Enhanced Metafile (EMF). Un tel fichier ne contient que des enregistrements GDI.

### EmfPlusOnly {#EmfPlusOnly}
```
public static final int EmfPlusOnly
```


Spécifie un fichier EMF+. Un tel fichier ne contient que des enregistrements GDI+ et doit être affiché en utilisant GDI+. L'affichage des enregistrements avec GDI peut entraîner des résultats imprévisibles.

### EmfPlusDual {#EmfPlusDual}
```
public static final int EmfPlusDual
```


Spécifie un fichier EMF+ Dual. Un tel fichier contient des enregistrements GDI+ ainsi que des enregistrements GDI alternatifs et peut être affiché en utilisant soit GDI, soit GDI+. L'affichage des enregistrements avec GDI peut entraîner une certaine dégradation de la qualité.

