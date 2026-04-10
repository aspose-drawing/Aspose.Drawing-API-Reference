---
title: MeteredExt
second_title: Aspose.Drawing for Java API リファレンス
description: メーター付きキーを設定するメソッドを提供します。
type: docs
weight: 33
url: /ja/java/com.aspose.drawing/meteredext/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.dynabic.metered.Metered](../../com.aspose.drawing.dynabic.metered/metered)

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class MeteredExt extends Metered implements System.IDisposable
```

メーター付きキーを設定するメソッドを提供します。

--------------------

> ```
> In this example, an attempt will be made to set metered public and private key
>  
>  `
>  
>  [C#]
>  Metered matered = new Metered();
>  matered.SetMeteredKey("PublicKey", "PrivateKey");
>  [Visual Basic]
>  Dim matered As Metered = New Metered
>  matered.SetMeteredKey("PublicKey", "PrivateKey")
>  
>  `
>  
>  `
>  the component jar file:
>  
>  Metered matered = new Metered();
>  matered.setMeteredKey("PublicKey", "PrivateKey");
>  
>  `
> ```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MeteredExt()](#MeteredExt--) | Initializes a new instance of the [Metered](../../com.aspose.drawing.dynabic.metered/metered) class. |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Gets consumption file size. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Gets consumption credit. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Sets metered public and private key |
| [dispose()](#dispose--) | アンマネージド リソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
### MeteredExt() {#MeteredExt--}
```
public MeteredExt()
```


Initializes a new instance of the [Metered](../../com.aspose.drawing.dynabic.metered/metered) class.

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Gets consumption file size.

**Returns:**
java.math.BigDecimal - Returns consumption quantity
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Gets consumption credit.

**Returns:**
java.math.BigDecimal - Returns consumption quantity
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Sets metered public and private key

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| publicKey | java.lang.String | public key |
| privateKey | java.lang.String | private key |

### dispose() {#dispose--}
```
public void dispose()
```


アンマネージド リソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。

