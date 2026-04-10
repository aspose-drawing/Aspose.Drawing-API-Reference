---
title: MeteredExt
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يوفر طرقًا لتعيين المفتاح المقيس.
type: docs
weight: 33
url: /ar/java/com.aspose.drawing/meteredext/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.dynabic.metered.Metered](../../com.aspose.drawing.dynabic.metered/metered)

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class MeteredExt extends Metered implements System.IDisposable
```

يوفر طرقًا لتعيين المفتاح المقيس.

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
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [MeteredExt()](#MeteredExt--) | ينشئ مثيلاً جديدًا من الفئة [Metered](../../com.aspose.drawing.dynabic.metered/metered). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | يحصل على حجم ملف الاستهلاك. |
| [getConsumptionCredit()](#getConsumptionCredit--) | يحصل على رصيد الاستهلاك. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | يضبط المفتاح العام والخاص للعداد. |
| [dispose()](#dispose--) | ينفّذ مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة تعيين الموارد غير المُدارة. |
### MeteredExt() {#MeteredExt--}
```
public MeteredExt()
```


ينشئ مثيلاً جديدًا من الفئة [Metered](../../com.aspose.drawing.dynabic.metered/metered).

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


يحصل على حجم ملف الاستهلاك.

**Returns:**
java.math.BigDecimal - يرجع كمية الاستهلاك
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


يحصل على رصيد الاستهلاك.

**Returns:**
java.math.BigDecimal - يرجع كمية الاستهلاك
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


يضبط المفتاح العام والخاص للعداد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| publicKey | java.lang.String | المفتاح العام |
| privateKey | java.lang.String | المفتاح الخاص |

### dispose() {#dispose--}
```
public void dispose()
```


ينفّذ مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة تعيين الموارد غير المُدارة.

