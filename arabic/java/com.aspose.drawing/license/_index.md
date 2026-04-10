---
title: رخصة
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يوفر طرقًا لترخيص المكوّن.
type: docs
weight: 32
url: /ar/java/com.aspose.drawing/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

يوفر طرقًا لترخيص المكوّن.

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
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [License()](#License--) | ينشئ مثيلاً جديدًا من هذه الفئة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | يرخص المكوّن. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | يرخص المكوّن. |
### License() {#License--}
```
public License()
```


ينشئ مثيلاً جديدًا من هذه الفئة.

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


يرخص المكوّن.

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
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | licenseName | java.lang.String | يمكن أن يكون اسم ملف كامل أو قصير` أو اسم مورد مضمّن`. استخدم سلسلة فارغة للتبديل إلى وضع التقييم. |

--------------------

KKKCODEB

يحاول العثور على الترخيص في المواقع التالية:

KKKCODEE KKKCODEB

1. مسار صريح.

KKKCODEE KKKCODEB

2. المجلد الذي يحتوي على تجميع مكوّن Aspose.

3. المجلد الذي يحتوي على تجميع الاستدعاء الخاص بالعميل.

4. المجلد الذي يحتوي على تجميع الدخول (بدء التشغيل).

5. مورد مضمّن في تجميع الاستدعاء الخاص بالعميل.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. مسار صريح.

2. مورد مضمّن في تجميع الاستدعاء الخاص بالعميل.

KKKCODEE KKKCODEB

2. المجلد الذي يحتوي على ملف JAR لمكوّن Aspose.

3. المجلد الذي يحتوي على ملف JAR لاستدعاء العميل.

KKKCODEE |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


يرخص المكوّن.

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
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | دفق | java.io.InputStream | دفق يحتوي على الترخيص. |

--------------------

KKKCODEB

استخدم هذه الطريقة لتحميل الترخيص من تدفق.

KKKCODEE

`void setLicense(java.io.InputStream stream)` |

