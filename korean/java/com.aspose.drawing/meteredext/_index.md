---
title: MeteredExt
second_title: Aspose.Drawing for Java API 참조
description: 계량 키를 설정하는 메서드를 제공합니다.
type: docs
weight: 33
url: /ko/java/com.aspose.drawing/meteredext/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.dynabic.metered.Metered](../../com.aspose.drawing.dynabic.metered/metered)

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class MeteredExt extends Metered implements System.IDisposable
```

계량 키를 설정하는 메서드를 제공합니다.

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
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MeteredExt()](#MeteredExt--) | [Metered](../../com.aspose.drawing.dynabic.metered/metered) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 소비 파일 크기를 가져옵니다. |
| [getConsumptionCredit()](#getConsumptionCredit--) | 소비 크레딧을 가져옵니다. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | metered 공개 및 개인 키를 설정합니다 |
| [dispose()](#dispose--) | 관리되지 않는 리소스를 해제, 릴리스 또는 재설정과 관련된 애플리케이션 정의 작업을 수행합니다. |
### MeteredExt() {#MeteredExt--}
```
public MeteredExt()
```


[Metered](../../com.aspose.drawing.dynabic.metered/metered) 클래스의 새 인스턴스를 초기화합니다.

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


소비 파일 크기를 가져옵니다.

**Returns:**
java.math.BigDecimal - 소비 수량을 반환합니다
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


소비 크레딧을 가져옵니다.

**Returns:**
java.math.BigDecimal - 소비 수량을 반환합니다
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


metered 공개 및 개인 키를 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| publicKey | java.lang.String | 공개 키 |
| privateKey | java.lang.String | 개인 키 |

### dispose() {#dispose--}
```
public void dispose()
```


관리되지 않는 리소스를 해제, 릴리스 또는 재설정과 관련된 애플리케이션 정의 작업을 수행합니다.

