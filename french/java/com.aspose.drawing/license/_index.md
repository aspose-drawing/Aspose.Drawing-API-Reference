---
title: License
second_title: Référence de l'API Aspose.Drawing pour Java
description: Fournit des méthodes pour licencier le composant.
type: docs
weight: 32
url: /fr/java/com.aspose.drawing/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Fournit des méthodes pour licencier le composant.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains
>  `
>  the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  [C#]
>  License license = new License();
>  license.SetLicense("MyLicense.lic");
>  
>  `
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [License()](#License--) | Initialise une nouvelle instance de cette classe. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licence le composant. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licence le composant. |
### License() {#License--}
```
public License()
```


Initialise une nouvelle instance de cette classe.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains
>  `
>  the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  [C#]
>  License license = new License();
>  license.SetLicense("MyLicense.lic");
>  [Visual Basic]
>  Dim license As license = New license
>  License.SetLicense("MyLicense.lic")
>  
>  `
>  `
>  the component jar file:
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
>  
>  `
> ```

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public final void setLicense(String licenseName)
```


Licence le composant.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains
>  `
>  the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  [C#]
>  License license = new License();
>  license.SetLicense("MyLicense.lic");
>  [Visual Basic]
>  Dim license As License = New License
>  license.SetLicense("MyLicense.lic")
>  
>  `
>  `
>  the component jar file:
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
>  
>  `
> ```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | licenseName | java.lang.String | Peut être un nom de fichier complet ou court` ou le nom d'une ressource incorporée`. Utilisez une chaîne vide pour passer en mode évaluation. |

--------------------

KKKCODEB

Essaie de trouver la licence aux emplacements suivants :

KKKCODEE KKKCODEB

1. Chemin explicite.

KKKCODEE KKKCODEB

2. Le dossier qui contient l'assembly du composant Aspose.

3. Le dossier qui contient l'assembly appelant du client.

4. Le dossier qui contient l'assembly d'entrée (démarrage).

5. Une ressource incorporée dans l'assembly appelant du client.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Chemin explicite.

2. Une ressource incorporée dans l'assembly appelant du client.

KKKCODEE KKKCODEB

2. Le dossier qui contient le fichier JAR du composant Aspose.

3. Le dossier qui contient le fichier JAR appelant du client.

KKKCODEE |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


Licence le composant.

--------------------

> ```
> `
>  [C#]
>  License license = new License();
>  license.SetLicense(myStream);
>  [Visual Basic]
>  Dim license as License = new License
>  license.SetLicense(myStream)
>  `
>  `
>  License license = new License();
>  license.setLicense(myStream);
>  `
> ```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | flux | java.io.InputStream | Un flux qui contient la licence. |

--------------------

KKKCODEB

Utilisez cette méthode pour charger une licence à partir d'un flux.

KKKCODEE

`void setLicense(java.io.InputStream stream)` |

