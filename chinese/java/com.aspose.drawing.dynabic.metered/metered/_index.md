---
title: 计量的
second_title: Aspose.Drawing for Java API 参考
description: 提供用于集成的计量方法。
type: docs
weight: 10
url: /zh/java/com.aspose.drawing.dynabic.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

提供用于集成的计量方法。

在此示例中，将尝试设置计量的公钥和私钥。

`// the component jar file: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey"); `
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Metered()](#Metered--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 获取消耗文件大小 |
| [getConsumptionCredit()](#getConsumptionCredit--) | 获取消耗信用 |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | 设置计量的公钥和私钥 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的对象是否等于此实例。 |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


获取消耗文件大小

**Returns:**
java.math.BigDecimal - 消耗文件大小
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


获取消耗信用

**Returns:**
java.math.BigDecimal - 消耗数量
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

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的对象是否等于此实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的 Object。 |

**Returns:**
boolean - 如果指定的 Object 等于此实例，则为 `true`；否则为 `false`。
