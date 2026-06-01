---
title: Измеряемый
second_title: Справочник API Aspose.Drawing для Java
description: Предоставляет измеряемые методы для интеграции.
type: docs
weight: 10
url: /ru/java/com.aspose.drawing.dynabic.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Предоставляет измеряемые методы для интеграции.

В этом примере будет предпринята попытка установить измеряемый публичный и приватный ключ.

`// файл jar компонента: Metered materd = new Metered(); materd.setMeteredKey("PublicKey", "PrivateKey"); `
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Metered()](#Metered--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Получает размер файла потребления |
| [getConsumptionCredit()](#getConsumptionCredit--) | Получает кредит потребления |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Устанавливает измеряемый публичный и приватный ключ |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный объект этому экземпляру. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Получает размер файла потребления

**Returns:**
java.math.BigDecimal - размер файла потребления
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Получает кредит потребления

**Returns:**
java.math.BigDecimal - количество потребления
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Устанавливает измеряемый публичный и приватный ключ

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| publicKey | java.lang.String | публичный ключ |
| privateKey | java.lang.String | приватный ключ |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный объект этому экземпляру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для сравнения с этим экземпляром. |

**Returns:**
boolean — `true`, если указанный объект равен этому экземпляру; в противном случае `false`.
