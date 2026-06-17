---
title: License
second_title: Riferimento API di Aspose.Drawing per Java
description: Fornisce metodi per licenziare il componente.
type: docs
weight: 32
url: /it/java/com.aspose.drawing/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Fornisce metodi per licenziare il componente.

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
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [License()](#License--) | Inizializza una nuova istanza di questa classe. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Concede licenza al componente. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Concede licenza al componente. |
### License() {#License--}
```
public License()
```


Inizializza una nuova istanza di questa classe.

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


Concede licenza al componente.

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | licenseName | java.lang.String | Può essere un nome file completo o breve` o il nome di una risorsa incorporata`. Usa una stringa vuota per passare alla modalità di valutazione. |

--------------------

KKKCODEB

Cerca di trovare la licenza nei seguenti percorsi:

KKKCODEE KKKCODEB

1. Percorso esplicito.

KKKCODEE KKKCODEB

2. La cartella che contiene l'assembly del componente Aspose.

3. La cartella che contiene l'assembly chiamante del client.

4. La cartella che contiene l'assembly di ingresso (avvio).

5. Una risorsa incorporata nell'assembly chiamante del client.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Percorso esplicito.

2. Una risorsa incorporata nell'assembly chiamante del client.

KKKCODEE KKKCODEB

2. La cartella che contiene il file JAR del componente Aspose.

3. La cartella che contiene il file JAR chiamante del client.

KKKCODEE |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


Concede licenza al componente.

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | flusso | java.io.InputStream | Uno stream che contiene la licenza. |

--------------------

KKKCODEB

Usa questo metodo per caricare una licenza da uno stream.

KKKCODEE

`void setLicense(java.io.InputStream stream)` |

