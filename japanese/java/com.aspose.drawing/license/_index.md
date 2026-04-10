---
title: License
second_title: Aspose.Drawing for Java API リファレンス
description: コンポーネントのライセンス認証用メソッドを提供します。
type: docs
weight: 32
url: /ja/java/com.aspose.drawing/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

コンポーネントのライセンス認証用メソッドを提供します。

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
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [License()](#License--) | Initializes a new instance of this class. |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licenses the component. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licenses the component. |
### License() {#License--}
```
public License()
```


Initializes a new instance of this class.

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


Licenses the component.

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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | licenseName | java.lang.String | 完全なファイル名または短いファイル名` または埋め込みリソースの名前` を指定できます。空文字列を使用すると評価モードに切り替わります。 |

--------------------

KKKCODEB

次の場所でライセンスを検索しようとします:

KKKCODEE KKKCODEB

1. 明示的なパス。

KKKCODEE KKKCODEB

2. Aspose コンポーネント アセンブリが含まれるフォルダー。

3. クライアントの呼び出しアセンブリが含まれるフォルダー。

4. エントリ（スタートアップ）アセンブリが含まれるフォルダー。

5. クライアントの呼び出しアセンブリ内の埋め込みリソース。

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. 明示的なパス。

2. クライアントの呼び出しアセンブリ内の埋め込みリソース。

KKKCODEE KKKCODEB

2. Aspose コンポーネント JAR ファイルが含まれるフォルダー。

3. クライアントの呼び出し JAR ファイルが含まれるフォルダー。

KKKCODEE |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


Licenses the component.

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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ストリーム | java.io.InputStream | ライセンスを含むストリーム。 |

--------------------

KKKCODEB

このメソッドを使用してストリームからライセンスをロードします。

KKKCODEE

`void setLicense(java.io.InputStream stream)` |

