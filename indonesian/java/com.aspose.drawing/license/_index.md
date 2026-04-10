---
title: License
second_title: Referensi API Aspose.Drawing for Java
description: Menyediakan metode untuk melisensikan komponen.
type: docs
weight: 32
url: /id/java/com.aspose.drawing/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Menyediakan metode untuk melisensikan komponen.

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
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [License()](#License--) | Menginisialisasi instance baru dari kelas ini. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Memberi lisensi pada komponen. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Memberi lisensi pada komponen. |
### License() {#License--}
```
public License()
```


Menginisialisasi instance baru dari kelas ini.

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


Memberi lisensi pada komponen.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | licenseName | java.lang.String | Dapat berupa nama file lengkap atau singkat` atau nama sumber daya yang disematkan`. Gunakan string kosong untuk beralih ke mode evaluasi. |

--------------------

KKKCODEB

Mencoba menemukan lisensi di lokasi berikut:

KKKCODEE KKKCODEB

1. Jalur eksplisit.

KKKCODEE KKKCODEB

2. Folder yang berisi assembly komponen Aspose.

3. Folder yang berisi assembly pemanggil klien.

4. Folder yang berisi assembly entri (startup).

5. Sumber daya yang disematkan dalam assembly pemanggil klien.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Jalur eksplisit.

2. Sumber daya yang disematkan dalam assembly pemanggil klien.

KKKCODEE KKKCODEB

2. Folder yang berisi file JAR komponen Aspose.

3. Folder yang berisi file JAR pemanggil klien.

KKKCODEE |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


Memberi lisensi pada komponen.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | aliran | java.io.InputStream | Aliran yang berisi lisensi. |

--------------------

KKKCODEB

Gunakan metode ini untuk memuat lisensi dari aliran.

KKKCODEE

`void setLicense(java.io.InputStream stream)` |

