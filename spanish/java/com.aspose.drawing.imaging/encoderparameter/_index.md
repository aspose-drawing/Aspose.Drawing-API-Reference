---
title: EncoderParameter
second_title: Referencia de la API de Aspose.Drawing para Java
description: Se usa para pasar un valor o una matriz de valores a un codificador de imágenes.
type: docs
weight: 20
url: /es/java/com.aspose.drawing.imaging/encoderparameter/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class EncoderParameter implements System.IDisposable
```

Se utiliza para pasar un valor, o una matriz de valores, a un codificador de imagen.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EncoderParameter(Encoder encoder, byte value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte-) | Inicializa una nueva instancia de la clase [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) con el objeto `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) especificado y un entero sin signo de 8 bits. |
| [EncoderParameter(Encoder encoder, byte value, boolean undefined)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte-boolean-) | Inicializa una nueva instancia de la clase [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) con el objeto `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) especificado y un valor de 8 bits. |
| [EncoderParameter(Encoder encoder, short value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-short-) | Inicializa una nueva instancia de la clase [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) con el objeto `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) especificado y un entero de 16 bits. |
| [EncoderParameter(Encoder encoder, long value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-long-) | Inicializa una nueva instancia de la clase [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) con el objeto `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) especificado y un entero de 64 bits. |
| [EncoderParameter(Encoder encoder, int numerator, int denominator)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-) | Inicializa una nueva instancia de la clase [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) con el objeto \{@link \#\#System\} especificado y un par de enteros de 32 bits. |
| [EncoderParameter(Encoder encoder, long rangebegin, long rangeend)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-long-long-) | Inicializa una nueva instancia de la clase [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) con el objeto `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) especificado y un par de enteros de 64 bits. |
| [EncoderParameter(Encoder encoder, int numerator1, int demoninator1, int numerator2, int demoninator2)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-int-int-) | Inicializa una nueva instancia de la clase [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) con el objeto `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) especificado y cuatro enteros de 32 bits. |
| [EncoderParameter(Encoder encoder, String value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-java.lang.String-) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and a character string. |
| [EncoderParameter(Encoder encoder, byte[] value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of unsigned 8-bit integers. |
| [EncoderParameter(Encoder encoder, byte[] value, boolean undefined)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte---boolean-) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of bytes. |
| [EncoderParameter(Encoder encoder, short[] value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-short---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of 16-bit integers. |
| [EncoderParameter(Encoder encoder, long[] value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-long---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of 64-bit integers. |
| [EncoderParameter(Encoder encoder, int[] numerator, int[] denominator)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int---int---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and two arrays of 32-bit integers. |
| [EncoderParameter(Encoder encoder, long[] rangebegin, long[] rangeend)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-long---long---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and two arrays of 64-bit integers. |
| [EncoderParameter(Encoder encoder, int[] numerator1, int[] denominator1, int[] numerator2, int[] denominator2)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int---int---int---int---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and four arrays of 32-bit integers. |
| [EncoderParameter(Encoder encoder, int numberOfValues, int type, int value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-int-) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and three integers that specify the number of values, the data type of the values, and a pointer to the values stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getEncoder()](#getEncoder--) | Gets or sets the `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object associated with this [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |
| [setEncoder(Encoder value)](#setEncoder-com.aspose.drawing.imaging.Encoder-) | Gets or sets the `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object associated with this [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |
| [getNumberOfValues()](#getNumberOfValues--) | Gets the number of elements in the array of values stored in this [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |
| [dispose()](#dispose--) | Releases all resources used by this [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |
### EncoderParameter(Encoder encoder, byte value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte-}
```
public EncoderParameter(Encoder encoder, byte value)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and one unsigned 8-bit integer. Sets the `EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeByte`, and sets the `EncoderParameter.NumberOfValues` property to 1.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | byte | An 8-bit unsigned integer that specifies the value stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |

### EncoderParameter(Encoder encoder, byte value, boolean undefined) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte-boolean-}
```
public EncoderParameter(Encoder encoder, byte value, boolean undefined)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and one 8-bit value. Sets the `EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeUndefined` or `EncoderParameterValueType.ValueTypeByte`, and sets the `EncoderParameter.NumberOfValues` property to 1.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | byte | A byte that specifies the value stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |
| undefined | boolean | If true, the `EncoderParameter.ValueType` property is set to `EncoderParameterValueType.ValueTypeUndefined`; otherwise, the `EncoderParameter.ValueType` property is set to `EncoderParameterValueType.ValueTypeByte`. |

### EncoderParameter(Encoder encoder, short value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-short-}
```
public EncoderParameter(Encoder encoder, short value)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and one, 16-bit integer. Sets the `EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeShort`, and sets the `EncoderParameter.NumberOfValues` property to 1.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | short | A 16-bit integer that specifies the value stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. Must be nonnegative. |

### EncoderParameter(Encoder encoder, long value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-long-}
```
public EncoderParameter(Encoder encoder, long value)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and one 64-bit integer. Sets the `EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeLong` (32 bits), and sets the `EncoderParameter.NumberOfValues` property to 1.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | long | A 64-bit integer that specifies the value stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. Must be nonnegative. This parameter is converted to a 32-bit integer before it is stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |

### EncoderParameter(Encoder encoder, int numerator, int denominator) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-}
```
public EncoderParameter(Encoder encoder, int numerator, int denominator)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified \{@link \#\#System\} object and a pair of 32-bit integers. The pair of integers represents a fraction, the first integer being the numerator, and the second integer being the denominator. Sets the `EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeRational`, and sets the `EncoderParameter.NumberOfValues` property to 1.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| numerator | int | Un entero de 32 bits que representa el numerador de una fracción. Debe ser no negativo. |
| denominador | int | Un entero de 32 bits que representa el denominador de una fracción. Debe ser no negativo. |

### EncoderParameter(Encoder encoder, long rangebegin, long rangeend) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-long-long-}
```
public EncoderParameter(Encoder encoder, long rangebegin, long rangeend)
```


Inicializa una nueva instancia de la clase [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) con el objeto `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) especificado y un par de enteros de 64 bits. El par de enteros representa un rango de enteros, siendo el primer entero el número más pequeño del rango y el segundo entero el número más grande del rango. Establece la propiedad `EncoderParameter.ValueType` a `EncoderParameterValueType.ValueTypeLongRange` y establece la propiedad `P:EncoderParameter.NumberOfValues` a 1.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| rangebegin | long | Un entero de 64 bits que representa el número más pequeño en un rango de enteros. Debe ser no negativo. Este parámetro se convierte a un entero de 32 bits antes de almacenarse en el objeto [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). |
| rangeend | long | Un entero de 64 bits que representa el número más grande en un rango de enteros. Debe ser no negativo. Este parámetro se convierte a un entero de 32 bits antes de almacenarse en el objeto [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). |

### EncoderParameter(Encoder encoder, int numerator1, int demoninator1, int numerator2, int demoninator2) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-int-int-}
```
public EncoderParameter(Encoder encoder, int numerator1, int demoninator1, int numerator2, int demoninator2)
```


Inicializa una nueva instancia de la clase [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) con el objeto `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) especificado y cuatro enteros de 32 bits. Los cuatro enteros representan un rango de fracciones. Los dos primeros enteros representan la fracción más pequeña del rango, y los dos restantes representan la fracción más grande del rango. Establece la propiedad `P:EncoderParameter.ValueType` a `EncoderParameterValueType.ValueTypeRationalRange` y establece la propiedad `P:EncoderParameter.NumberOfValues` a 1.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| numerator1 | int | Un entero de 32 bits que representa el numerador de la fracción más pequeña del rango. Debe ser no negativo. |
| demoninator1 | int | Un entero de 32 bits que representa el denominador de la fracción más pequeña del rango. Debe ser no negativo. |
| numerator2 | int | Un entero de 32 bits que representa el numerador de la fracción más grande del rango. Debe ser no negativo. |
| demoninator2 | int | Un entero de 32 bits que representa el denominador de la fracción más grande del rango. Debe ser no negativo. |

### EncoderParameter(Encoder encoder, String value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-java.lang.String-}
```
public EncoderParameter(Encoder encoder, String value)
```


Inicializa una nueva instancia de la clase [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) con el objeto `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) especificado y una cadena de caracteres. La cadena se convierte en una cadena ASCII terminada en nulo antes de almacenarse en el objeto [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). Establece la propiedad `P:EncoderParameter.ValueType` a `EncoderParameterValueType.ValueTypeAscii` y establece la propiedad `P:EncoderParameter.NumberOfValues` a la longitud de la cadena ASCII incluyendo el terminador NULL.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | java.lang.String | Una cadena que especifica el valor almacenado en el objeto [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). |

### EncoderParameter(Encoder encoder, byte[] value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte---}
```
public EncoderParameter(Encoder encoder, byte[] value)
```


Inicializa una nueva instancia de la clase [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) con el objeto `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) especificado y una matriz de enteros sin signo de 8 bits. Establece la propiedad `P:EncoderParameter.ValueType` a `EncoderParameterValueType.ValueTypeByte` y establece la propiedad `P:EncoderParameter.NumberOfValues` al número de elementos de la matriz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | byte[] | Una matriz de enteros sin signo de 8 bits que especifica los valores almacenados en el objeto [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). |

### EncoderParameter(Encoder encoder, byte[] value, boolean undefined) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte---boolean-}
```
public EncoderParameter(Encoder encoder, byte[] value, boolean undefined)
```


Inicializa una nueva instancia de la clase [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) con el objeto `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) especificado y una matriz de bytes. Establece la propiedad `P:EncoderParameter.ValueType` a `EncoderParameterValueType.ValueTypeUndefined` o `EncoderParameterValueType.ValueTypeByte` y establece la propiedad `P:EncoderParameter.NumberOfValues` al número de elementos de la matriz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | byte[] | Una matriz de bytes que especifica los valores almacenados en el objeto [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). |
| undefined | boolean | Si es verdadero, la propiedad `P:EncoderParameter.ValueType` se establece en `EncoderParameterValueType.ValueTypeUndefined`; de lo contrario, la propiedad `P:EncoderParameter.ValueType` se establece en `EncoderParameterValueType.ValueTypeByte`. |

### EncoderParameter(Encoder encoder, short[] value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-short---}
```
public EncoderParameter(Encoder encoder, short[] value)
```


Inicializa una nueva instancia de la clase [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) con el objeto `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) especificado y una matriz de enteros de 16 bits. Establece la propiedad `P:EncoderParameter.ValueType` a `EncoderParameterValueType.ValueTypeShort` y establece la propiedad `P:EncoderParameter.NumberOfValues` al número de elementos de la matriz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | short[] | Una matriz de enteros de 16 bits que especifica los valores almacenados en el objeto [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). Los enteros de la matriz deben ser no negativos. |

### EncoderParameter(Encoder encoder, long[] value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-long---}
```
public EncoderParameter(Encoder encoder, long[] value)
```


Inicializa una nueva instancia de la clase [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) con el objeto `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) especificado y una matriz de enteros de 64 bits. Establece la propiedad `P:EncoderParameter.ValueType` a `EncoderParameterValueType.ValueTypeLong` (32 bits) y establece la propiedad `P:EncoderParameter.NumberOfValues` al número de elementos de la matriz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | long[] | Una matriz de enteros de 64 bits que especifica los valores almacenados en el objeto [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) . Los enteros en la matriz deben ser no negativos. Los enteros de 64 bits se convierten a enteros de 32 bits antes de almacenarse en el objeto [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) . |

### EncoderParameter(Encoder encoder, int[] numerator, int[] denominator) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int---int---}
```
public EncoderParameter(Encoder encoder, int[] numerator, int[] denominator)
```


Inicializa una nueva instancia de la clase [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) con el objeto `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) especificado y dos matrices de enteros de 32 bits. Las dos matrices representan una matriz de fracciones. Establece la propiedad `P:EncoderParameter.ValueType` a `EncoderParameterValueType.ValueTypeRational`, y establece la propiedad `P:EncoderParameter.NumberOfValues` al número de elementos en la matriz `numerator`, que debe ser el mismo que el número de elementos en la matriz `denominator`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| numerator | int[] | Una matriz de enteros de 32 bits que especifica los numeradores de las fracciones. Los enteros en la matriz deben ser no negativos. |
| denominador | int[] | Una matriz de enteros de 32 bits que especifica los denominadores de las fracciones. Los enteros en la matriz deben ser no negativos. Un denominador de un índice dado se empareja con el numerador del mismo índice. |

### EncoderParameter(Encoder encoder, long[] rangebegin, long[] rangeend) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-long---long---}
```
public EncoderParameter(Encoder encoder, long[] rangebegin, long[] rangeend)
```


Inicializa una nueva instancia de la clase [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) con el objeto `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) especificado y dos matrices de enteros de 64 bits. Las dos matrices representan rangos de enteros. Establece la propiedad `P:EncoderParameter.ValueType` a `EncoderParameterValueType.ValueTypeLongRange`, y establece la propiedad `P:EncoderParameter.NumberOfValues` al número de elementos en la matriz `rangebegin`, que debe ser el mismo que el número de elementos en la matriz `rangeend`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| rangebegin | long[] | Una matriz de enteros de 64 bits que especifica los valores mínimos para los rangos de enteros. Los enteros en la matriz deben ser no negativos. Los enteros de 64 bits se convierten a enteros de 32 bits antes de almacenarse en el objeto [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) . |
| rangeend | long[] | Una matriz de enteros de 64 bits que especifica los valores máximos para los rangos de enteros. Los enteros en la matriz deben ser no negativos. Los enteros de 64 bits se convierten a enteros de 32 bits antes de almacenarse en el objeto [EncoderParameters](../../com.aspose.drawing.imaging/encoderparameters) . Un valor máximo de un índice dado se empareja con el valor mínimo del mismo índice. |

### EncoderParameter(Encoder encoder, int[] numerator1, int[] denominator1, int[] numerator2, int[] denominator2) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int---int---int---int---}
```
public EncoderParameter(Encoder encoder, int[] numerator1, int[] denominator1, int[] numerator2, int[] denominator2)
```


Inicializa una nueva instancia de la clase [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) con el objeto `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) especificado y cuatro matrices de enteros de 32 bits. Las cuatro matrices representan rangos racionales. Un rango racional es el conjunto de todas las fracciones desde un valor fraccionario mínimo hasta un valor fraccionario máximo. Establece la propiedad `P:EncoderParameter.ValueType` a `EncoderParameterValueType.ValueTypeRationalRange`, y establece la propiedad `P:EncoderParameter.NumberOfValues` al número de elementos en la matriz `numerator1`, que debe ser el mismo que el número de elementos en las otras tres matrices.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| numerator1 | int[] | Una matriz de enteros de 32 bits que especifica los numeradores de los valores mínimos para los rangos. Los enteros en la matriz deben ser no negativos. |
| denominator1 | int[] | Una matriz de enteros de 32 bits que especifica los denominadores de los valores mínimos para los rangos. Los enteros en la matriz deben ser no negativos. |
| numerator2 | int[] | Una matriz de enteros de 32 bits que especifica los numeradores de los valores máximos para los rangos. Los enteros en la matriz deben ser no negativos. |
| denominator2 | int[] | Una matriz de enteros de 32 bits que especifica los denominadores de los valores máximos para los rangos. Los enteros en la matriz deben ser no negativos. |

### EncoderParameter(Encoder encoder, int numberOfValues, int type, int value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-int-}
```
public EncoderParameter(Encoder encoder, int numberOfValues, int type, int value)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and three integers that specify the number of values, the data type of the values, and a pointer to the values stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| numberOfValues | int | Un entero que especifica el número de valores almacenados en el objeto [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) . La propiedad `P:EncoderParameter.NumberOfValues` se establece a este valor. |
| type | int | Un miembro de la enumeración `EncoderParameterValueType` que especifica el tipo de datos de los valores almacenados en el objeto [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) . Las propiedades Type y `P:EncoderParameter.ValueType` se establecen a este valor. |
| value | int | Un puntero a una matriz de valores del tipo especificado por el parámetro `type`. |

### getEncoder() {#getEncoder--}
```
public Encoder getEncoder()
```


Obtiene o establece el objeto `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) asociado a este objeto [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) . El objeto `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) encapsula el identificador único global (GUID) que especifica la categoría (por ejemplo `Encoder.Quality`, `Encoder.ColorDepth`, o `Encoder.Compression`) del parámetro almacenado en este objeto [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) .

**Returns:**
[Encoder](../../com.aspose.drawing.imaging/encoder)
### setEncoder(Encoder value) {#setEncoder-com.aspose.drawing.imaging.Encoder-}
```
public void setEncoder(Encoder value)
```


Obtiene o establece el objeto `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) asociado a este objeto [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) . El objeto `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) encapsula el identificador único global (GUID) que especifica la categoría (por ejemplo `Encoder.Quality`, `Encoder.ColorDepth`, o `Encoder.Compression`) del parámetro almacenado en este objeto [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Encoder](../../com.aspose.drawing.imaging/encoder) |  |

### getNumberOfValues() {#getNumberOfValues--}
```
public int getNumberOfValues()
```


Gets the number of elements in the array of values stored in this [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object.

**Returns:**
int
### dispose() {#dispose--}
```
public void dispose()
```


Releases all resources used by this [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object.

