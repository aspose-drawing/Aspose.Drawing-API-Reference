---
title: MetafileType
second_title: Référence de l'API Aspose.Drawing pour .NET
description: Spécifie les types de métafichiers.
type: docs
weight: 830
url: /fr/net/system.drawing.imaging/metafiletype/
---
## MetafileType enumeration

Spécifie les types de métafichiers.

```csharp
public enum MetafileType
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| Invalid | `0` | Spécifie un format de métafichier qui n'est pas reconnu dans GDI+. |
| Wmf | `1` | Spécifie un fichier WMF (Windows Metafile). Un tel fichier ne contient que des enregistrements GDI. |
| WmfPlaceable | `2` | Spécifie un fichier WMF (Windows Metafile) qui a un en-tête de métafichier placeable devant lui. |
| Emf | `3` | Spécifie un fichier de métafichier amélioré (EMF). Un tel fichier ne contient que des enregistrements GDI. |
| EmfPlusOnly | `4` | Spécifie un fichier EMF+. Un tel fichier contient uniquement des enregistrements GDI+ et doit être affiché à l'aide de GDI+. L'affichage des enregistrements à l'aide de GDI peut entraîner des résultats imprévisibles. |
| EmfPlusDual | `5` | Spécifie un fichier double EMF+. Un tel fichier contient des enregistrements GDI+ ainsi que d'autres enregistrements GDI et peut être affiché à l'aide de GDI ou de GDI+. L'affichage des enregistrements à l'aide de GDI peut entraîner une certaine dégradation de la qualité. |

### Voir également

* espace de noms [System.Drawing.Imaging](../../system.drawing.imaging)
* Assemblée [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->