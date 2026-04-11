---
title: License
second_title: Справочник API Aspose.Drawing для Java
description: Предоставляет методы для лицензирования компонента.
type: docs
weight: 32
url: /ru/java/com.aspose.drawing/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Предоставляет методы для лицензирования компонента.

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
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [License()](#License--) | Инициализирует новый экземпляр этого класса. |
## Методы

| Метод | Описание |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Лицензирует компонент. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Лицензирует компонент. |
### License() {#License--}
```
public License()
```


Инициализирует новый экземпляр этого класса.

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


Лицензирует компонент.

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
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | licenseName | java.lang.String | Может быть полным или коротким именем файла` или именем встроенного ресурса`. Используйте пустую строку, чтобы переключиться в режим оценки. |

--------------------

KKKCODEB

Пытается найти лицензию в следующих местах:

KKKCODEE KKKCODEB

1. Явный путь.

KKKCODEE KKKCODEB

2. Папка, содержащая сборку компонента Aspose.

3. Папка, содержащая вызывающую сборку клиента.

4. Папка, содержащая входную (запускную) сборку.

5. Встроенный ресурс в вызывающей сборке клиента.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Явный путь.

2. Встроенный ресурс в вызывающей сборке клиента.

KKKCODEE KKKCODEB

2. Папка, содержащая JAR‑файл компонента Aspose.

3. Папка, содержащая JAR‑файл вызывающего клиента.

KKKCODEE |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


Лицензирует компонент.

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
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | stream | java.io.InputStream | Поток, содержащий лицензию. |

--------------------

KKKCODEB

Используйте этот метод для загрузки лицензии из потока.

KKKCODEE

`void setLicense(java.io.InputStream stream)` |

