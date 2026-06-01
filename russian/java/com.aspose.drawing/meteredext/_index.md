---
title: MeteredExt
second_title: Справочник API Aspose.Drawing для Java
description: Предоставляет методы для установки измеряемого ключа.
type: docs
weight: 33
url: /ru/java/com.aspose.drawing/meteredext/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.dynabic.metered.Metered](../../com.aspose.drawing.dynabic.metered/metered)

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class MeteredExt extends Metered implements System.IDisposable
```

Предоставляет методы для установки измеряемого ключа.

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
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MeteredExt()](#MeteredExt--) | Инициализирует новый экземпляр класса [Metered](../../com.aspose.drawing.dynabic.metered/metered). |
## Методы

| Метод | Описание |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Получает размер файла потребления. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Получает кредит потребления. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Устанавливает измеряемый публичный и приватный ключ |
| [dispose()](#dispose--) | Выполняет задачи, определённые приложением, связанные с освобождением, выпуском или сбросом неуправляемых ресурсов. |
### MeteredExt() {#MeteredExt--}
```
public MeteredExt()
```


Инициализирует новый экземпляр класса [Metered](../../com.aspose.drawing.dynabic.metered/metered).

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Получает размер файла потребления.

**Returns:**
java.math.BigDecimal - Возвращает количество потребления
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Получает кредит потребления.

**Returns:**
java.math.BigDecimal - Возвращает количество потребления
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

### dispose() {#dispose--}
```
public void dispose()
```


Выполняет задачи, определённые приложением, связанные с освобождением, выпуском или сбросом неуправляемых ресурсов.

