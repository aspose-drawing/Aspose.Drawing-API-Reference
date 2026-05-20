---
title: License
second_title: Aspose.Drawing for Java API 参考
description: 提供对组件授权的方法。
type: docs
weight: 32
url: /zh/java/com.aspose.drawing/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

提供对组件授权的方法。

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
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [License()](#License--) | 初始化此类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | 为组件授权。 |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | 为组件授权。 |
### License() {#License--}
```
public License()
```


初始化此类的新实例。

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


为组件授权。

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | licenseName | java.lang.String | 可以是完整或短的文件名`或嵌入资源的名称`。使用空字符串切换到评估模式。 |

--------------------

KKKCODEB

尝试在以下位置查找许可证：

KKKCODEE KKKCODEB

1. 明确路径。

KKKCODEE KKKCODEB

2. 包含 Aspose 组件程序集的文件夹。

3. 包含客户端调用程序集的文件夹。

4. 包含入口（启动）程序集的文件夹。

5. 客户端调用程序集中的嵌入资源。

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. 明确路径。

2. 客户端调用程序集中的嵌入资源。

KKKCODEE KKKCODEB

2. 包含 Aspose 组件 JAR 文件的文件夹。

3. 包含客户端调用 JAR 文件的文件夹。

KKKCODEE |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


为组件授权。

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 流 | java.io.InputStream | 包含许可证的流。 |

--------------------

KKKCODEB

使用此方法从流中加载许可证。

KKKCODEE

`void setLicense(java.io.InputStream stream)` |

