---
title: MeteredExt
second_title: Referencia de la API de Aspose.Drawing para Java
description: Proporciona métodos para establecer la clave medida.
type: docs
weight: 33
url: /es/java/com.aspose.drawing/meteredext/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.dynabic.metered.Metered](../../com.aspose.drawing.dynabic.metered/metered)

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class MeteredExt extends Metered implements System.IDisposable
```

Proporciona métodos para establecer la clave medida.

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
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MeteredExt()](#MeteredExt--) | Inicializa una nueva instancia de la clase [Metered](../../com.aspose.drawing.dynabic.metered/metered). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Obtiene el tamaño del archivo de consumo. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Obtiene el crédito de consumo. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Establece la clave pública y privada del medidor. |
| [dispose()](#dispose--) | Realiza tareas definidas por la aplicación asociadas con la liberación, el desalojo o el restablecimiento de recursos no administrados. |
### MeteredExt() {#MeteredExt--}
```
public MeteredExt()
```


Inicializa una nueva instancia de la clase [Metered](../../com.aspose.drawing.dynabic.metered/metered).

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Obtiene el tamaño del archivo de consumo.

**Returns:**
java.math.BigDecimal - Devuelve la cantidad de consumo
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Obtiene el crédito de consumo.

**Returns:**
java.math.BigDecimal - Devuelve la cantidad de consumo
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Establece la clave pública y privada del medidor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| publicKey | java.lang.String | clave pública |
| privateKey | java.lang.String | clave privada |

### dispose() {#dispose--}
```
public void dispose()
```


Realiza tareas definidas por la aplicación asociadas con la liberación, el desalojo o el restablecimiento de recursos no administrados.

