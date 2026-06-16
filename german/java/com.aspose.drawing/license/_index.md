---
title: License
second_title: Aspose.Drawing für Java API-Referenz
description: Stellt Methoden bereit, um die Komponente zu lizenzieren.
type: docs
weight: 32
url: /de/java/com.aspose.drawing/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Stellt Methoden bereit, um die Komponente zu lizenzieren.

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
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [License()](#License--) | Initialisiert eine neue Instanz dieser Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Lizenziert die Komponente. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Lizenziert die Komponente. |
### License() {#License--}
```
public License()
```


Initialisiert eine neue Instanz dieser Klasse.

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


Lizenziert die Komponente.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | licenseName | java.lang.String | Kann ein voller oder kurzer Dateiname` oder der Name einer eingebetteten Ressource` sein. Verwenden Sie eine leere Zeichenfolge, um in den Evaluierungsmodus zu wechseln. |

--------------------

KKKCODEB

Versucht, die Lizenz an den folgenden Orten zu finden:

KKKCODEE KKKCODEB

1. Expliziter Pfad.

KKKCODEE KKKCODEB

2. Der Ordner, der die Aspose‑Komponenten‑Assembly enthält.

3. Der Ordner, der die aufrufende Assembly des Clients enthält.

4. Der Ordner, der die Einstiegs‑(Start‑)Assembly enthält.

5. Eine eingebettete Ressource in der aufrufenden Assembly des Clients.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Expliziter Pfad.

2. Eine eingebettete Ressource in der aufrufenden Assembly des Clients.

KKKCODEE KKKCODEB

2. Der Ordner, der die Aspose‑Komponenten‑JAR‑Datei enthält.

3. Der Ordner, der die aufrufende JAR‑Datei des Clients enthält.

KKKCODEE |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


Lizenziert die Komponente.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Stream | java.io.InputStream | Ein Stream, der die Lizenz enthält. |

--------------------

KKKCODEB

Verwenden Sie diese Methode, um eine Lizenz aus einem Stream zu laden.

KKKCODEE

`void setLicense(java.io.InputStream stream)` |

