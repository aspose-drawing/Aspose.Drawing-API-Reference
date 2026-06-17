---
title: Metered
second_title: Aspose.Drawing for Java API 참조
description: 통합을 위한 계량 메서드를 제공합니다.
type: docs
weight: 10
url: /ko/java/com.aspose.drawing.dynabic.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

통합을 위한 계량 메서드를 제공합니다.

이 예제에서는 메터링된 공개 키와 개인 키를 설정하려고 시도합니다.

`// the component jar file: Metered matered = new Metered(); materd.setMeteredKey("PublicKey", "PrivateKey"); `
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Metered()](#Metered--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 소비 파일 크기를 가져옵니다 |
| [getConsumptionCredit()](#getConsumptionCredit--) | 소비 크레딧을 가져옵니다 |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | metered 공개 및 개인 키를 설정합니다 |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 Object가 이 인스턴스와 같은지 여부를 확인합니다. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


소비 파일 크기를 가져옵니다

**Returns:**
java.math.BigDecimal - 소비 파일 크기
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


소비 크레딧을 가져옵니다

**Returns:**
java.math.BigDecimal - 소비 수량
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

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된 Object가 이 인스턴스와 같은지 여부를 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할 Object. |

**Returns:**
boolean - 지정된 Object가 이 인스턴스와 동일하면 `true`, 그렇지 않으면 `false`.
