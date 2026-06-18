---
title: License
second_title: Referencia de la API de Aspose.Drawing para Java
description: Proporciona métodos para licenciar el componente.
type: docs
weight: 32
url: /es/java/com.aspose.drawing/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Proporciona métodos para licenciar el componente.

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
## Constructores

| Constructor | Descripción |
| --- | --- |
| [License()](#License--) | Inicializa una nueva instancia de esta clase. |
## Métodos

| Método | Descripción |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licencia el componente. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licencia el componente. |
### License() {#License--}
```
public License()
```


Inicializa una nueva instancia de esta clase.

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


Licencia el componente.

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | licenseName | java.lang.String | Puede ser un nombre de archivo completo o corto` o nombre de un recurso incrustado`. Use una cadena vacía para cambiar al modo de evaluación. |

--------------------

KKKCODEB

Intenta encontrar la licencia en las siguientes ubicaciones:

KKKCODEE KKKCODEB

1. Ruta explícita.

KKKCODEE KKKCODEB

2. La carpeta que contiene el ensamblado del componente Aspose.

3. La carpeta que contiene el ensamblado que llama el cliente.

4. La carpeta que contiene el ensamblado de entrada (inicio).

5. Un recurso incrustado en el ensamblado que llama el cliente.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Ruta explícita.

2. Un recurso incrustado en el ensamblado que llama el cliente.

KKKCODEE KKKCODEB

2. La carpeta que contiene el archivo JAR del componente Aspose.

3. La carpeta que contiene el archivo JAR que llama el cliente.

KKKCODEE |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


Licencia el componente.

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | flujo | java.io.InputStream | Un flujo que contiene la licencia. |

--------------------

KKKCODEB

Use este método para cargar una licencia desde un flujo.

KKKCODEE

`void setLicense(java.io.InputStream stream)` |

