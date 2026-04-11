---
title: License
second_title: Aspose.Drawing voor Java API-referentie
description: Biedt methoden om het component te licentiëren.
type: docs
weight: 32
url: /nl/java/com.aspose.drawing/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Biedt methoden om het component te licentiëren.

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
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [License()](#License--) | Initialiseert een nieuw exemplaar van deze klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licentieert het component. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licentieert het component. |
### License() {#License--}
```
public License()
```


Initialiseert een nieuw exemplaar van deze klasse.

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


Licentieert het component.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | licenseName | java.lang.String | Kan een volledige of korte bestandsnaam` of naam van een ingebedde resource` zijn. Gebruik een lege tekenreeks om over te schakelen naar evaluatiemodus. |

--------------------

KKKCODEB

Probeert de licentie te vinden op de volgende locaties:

KKKCODEE KKKCODEB

1. Expliciet pad.

KKKCODEE KKKCODEB

2. De map die de Aspose componentassembly bevat.

3. De map die de aanroepende assembly van de client bevat.

4. De map die de entry (startup) assembly bevat.

5. Een ingebedde resource in de aanroepende assembly van de client.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Expliciet pad.

2. Een ingebedde resource in de aanroepende assembly van de client.

KKKCODEE KKKCODEB

2. De map die het Aspose component JAR‑bestand bevat.

3. De map die het JAR‑bestand van de aanroepende client bevat.

KKKCODEE |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


Licentieert het component.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | stroom | java.io.InputStream | Een stream die de licentie bevat. |

--------------------

KKKCODEB

Gebruik deze methode om een licentie uit een stream te laden.

KKKCODEE

`void setLicense(java.io.InputStream stream)` |

