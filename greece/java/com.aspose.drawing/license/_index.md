---
title: Άδεια
second_title: Αναφορά API του Aspose.Drawing for Java
description: Provides methods to license the component.
type: docs
weight: 32
url: /el/java/com.aspose.drawing/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Provides methods to license the component.

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
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [License()](#License--) | Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Παρέχει άδεια στο στοιχείο. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Παρέχει άδεια στο στοιχείο. |
### License() {#License--}
```
public License()
```


Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης.

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


Παρέχει άδεια στο στοιχείο.

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | licenseName | java.lang.String | Μπορεί να είναι πλήρες ή σύντομο όνομα αρχείου` ή όνομα ενσωματωμένου πόρου`. Χρησιμοποιήστε μια κενή συμβολοσειρά για να μεταβείτε σε λειτουργία αξιολόγησης. |

--------------------

KKKCODEB

Προσπαθεί να βρει την άδεια στις ακόλουθες τοποθεσίες:

KKKCODEE KKKCODEB

1. Ρητή διαδρομή.

KKKCODEE KKKCODEB

2. Ο φάκελος που περιέχει το assembly του στοιχείου Aspose.

3. Ο φάκελος που περιέχει το assembly κλήσης του πελάτη.

4. Ο φάκελος που περιέχει το entry (startup) assembly.

5. Ένας ενσωματωμένος πόρος στο assembly κλήσης του πελάτη.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Ρητή διαδρομή.

2. Ένας ενσωματωμένος πόρος στο assembly κλήσης του πελάτη.

KKKCODEE KKKCODEB

2. Ο φάκελος που περιέχει το αρχείο JAR του στοιχείου Aspose.

3. Ο φάκελος που περιέχει το αρχείο JAR κλήσης του πελάτη.

KKKCODEE |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


Παρέχει άδεια στο στοιχείο.

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | stream | java.io.InputStream | Μια ροή που περιέχει την άδεια. |

--------------------

KKKCODEB

Χρησιμοποιήστε αυτή τη μέθοδο για να φορτώσετε μια άδεια από μια ροή.

KKKCODEE

`void setLicense(java.io.InputStream stream)` |

