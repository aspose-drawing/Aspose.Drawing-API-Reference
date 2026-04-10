---
title: Metered
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يوفر طرقًا مقنَّعة للتكامل.
type: docs
weight: 10
url: /ar/java/com.aspose.drawing.dynabic.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

يوفر طرقًا مقنَّعة للتكامل.

في هذا المثال، سيتم محاولة تعيين المفتاح العام والخاص للـ metered

`// the component jar file: Metered materd = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey"); `
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Metered()](#Metered--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | يحصل على حجم ملف الاستهلاك |
| [getConsumptionCredit()](#getConsumptionCredit--) | يحصل على رصيد الاستهلاك |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | يضبط المفتاح العام والخاص للعداد. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان الكائن المحدد يساوي هذه الحالة. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


يحصل على حجم ملف الاستهلاك

**Returns:**
java.math.BigDecimal - حجم ملف الاستهلاك
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


يحصل على رصيد الاستهلاك

**Returns:**
java.math.BigDecimal - كمية الاستهلاك
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

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان الكائن المحدد يساوي هذه الحالة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للمقارنة مع هذه الحالة. |

**Returns:**
منطقي - `true` إذا كان الكائن المحدد يساوي هذه الحالة؛ وإلا `false`.
