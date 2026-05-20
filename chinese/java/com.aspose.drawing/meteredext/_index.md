---
title: MeteredExt
second_title: Aspose.Drawing for Java API 参考
description: 提供设置计量密钥的方法。
type: docs
weight: 33
url: /zh/java/com.aspose.drawing/meteredext/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.dynabic.metered.Metered](../../com.aspose.drawing.dynabic.metered/metered)

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class MeteredExt extends Metered implements System.IDisposable
```

提供设置计量密钥的方法。

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
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MeteredExt()](#MeteredExt--) | 初始化 [Metered](../../com.aspose.drawing.dynabic.metered/metered) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 获取消耗文件大小。 |
| [getConsumptionCredit()](#getConsumptionCredit--) | 获取消耗积分。 |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | 设置计量的公钥和私钥 |
| [dispose()](#dispose--) | 执行与释放、释放或重置非托管资源相关的应用程序定义任务。 |
### MeteredExt() {#MeteredExt--}
```
public MeteredExt()
```


初始化 [Metered](../../com.aspose.drawing.dynabic.metered/metered) 类的新实例。

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


获取消耗文件大小。

**Returns:**
java.math.BigDecimal - 返回消耗数量
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


获取消耗积分。

**Returns:**
java.math.BigDecimal - 返回消耗数量
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


设置计量的公钥和私钥

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| publicKey | java.lang.String | 公钥 |
| privateKey | java.lang.String | 私钥 |

### dispose() {#dispose--}
```
public void dispose()
```


执行与释放、释放或重置非托管资源相关的应用程序定义任务。

