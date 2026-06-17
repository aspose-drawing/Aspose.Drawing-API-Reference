---
title: EncoderParameter
second_title: Référence de l'API Aspose.Drawing pour Java
description: Utilisé pour transmettre une valeur ou un tableau de valeurs à un encodeur d’image.
type: docs
weight: 20
url: /fr/java/com.aspose.drawing.imaging/encoderparameter/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class EncoderParameter implements System.IDisposable
```

Utilisé pour transmettre une valeur, ou un tableau de valeurs, à un encodeur d'image.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EncoderParameter(Encoder encoder, byte value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte-) | Initialise une nouvelle instance de la classe [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) avec l’objet `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) spécifié et un entier non signé de 8 bits. |
| [EncoderParameter(Encoder encoder, byte value, boolean undefined)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte-boolean-) | Initialise une nouvelle instance de la classe [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) avec l’objet `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) spécifié et une valeur de 8 bits. |
| [EncoderParameter(Encoder encoder, short value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-short-) | Initialise une nouvelle instance de la classe [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) avec l’objet `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) spécifié et un entier de 16 bits. |
| [EncoderParameter(Encoder encoder, long value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-long-) | Initialise une nouvelle instance de la classe [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) avec l’objet `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) spécifié et un entier de 64 bits. |
| [EncoderParameter(Encoder encoder, int numerator, int denominator)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-) | Initialise une nouvelle instance de la classe [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) avec l’objet \{@link \#\#System\} spécifié et une paire d’entiers de 32 bits. |
| [EncoderParameter(Encoder encoder, long rangebegin, long rangeend)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-long-long-) | Initialise une nouvelle instance de la classe [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) avec l’objet `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) spécifié et une paire d’entiers de 64 bits. |
| [EncoderParameter(Encoder encoder, int numerator1, int demoninator1, int numerator2, int demoninator2)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-int-int-) | Initialise une nouvelle instance de la classe [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) avec l’objet `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) spécifié et quatre entiers de 32 bits. |
| [EncoderParameter(Encoder encoder, String value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-java.lang.String-) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and a character string. |
| [EncoderParameter(Encoder encoder, byte[] value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of unsigned 8-bit integers. |
| [EncoderParameter(Encoder encoder, byte[] value, boolean undefined)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte---boolean-) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of bytes. |
| [EncoderParameter(Encoder encoder, short[] value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-short---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of 16-bit integers. |
| [EncoderParameter(Encoder encoder, long[] value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-long---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of 64-bit integers. |
| [EncoderParameter(Encoder encoder, int[] numerator, int[] denominator)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int---int---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and two arrays of 32-bit integers. |
| [EncoderParameter(Encoder encoder, long[] rangebegin, long[] rangeend)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-long---long---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and two arrays of 64-bit integers. |
| [EncoderParameter(Encoder encoder, int[] numerator1, int[] denominator1, int[] numerator2, int[] denominator2)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int---int---int---int---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and four arrays of 32-bit integers. |
| [EncoderParameter(Encoder encoder, int numberOfValues, int type, int value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-int-) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and three integers that specify the number of values, the data type of the values, and a pointer to the values stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |
## Méthodes

| Méthode | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | byte | An 8-bit unsigned integer that specifies the value stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |

### EncoderParameter(Encoder encoder, byte value, boolean undefined) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte-boolean-}
```
public EncoderParameter(Encoder encoder, byte value, boolean undefined)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and one 8-bit value. Sets the `EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeUndefined` or `EncoderParameterValueType.ValueTypeByte`, and sets the `EncoderParameter.NumberOfValues` property to 1.

**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | short | A 16-bit integer that specifies the value stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. Must be nonnegative. |

### EncoderParameter(Encoder encoder, long value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-long-}
```
public EncoderParameter(Encoder encoder, long value)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and one 64-bit integer. Sets the `EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeLong` (32 bits), and sets the `EncoderParameter.NumberOfValues` property to 1.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | long | A 64-bit integer that specifies the value stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. Must be nonnegative. This parameter is converted to a 32-bit integer before it is stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |

### EncoderParameter(Encoder encoder, int numerator, int denominator) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-}
```
public EncoderParameter(Encoder encoder, int numerator, int denominator)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified \{@link \#\#System\} object and a pair of 32-bit integers. The pair of integers represents a fraction, the first integer being the numerator, and the second integer being the denominator. Sets the `EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeRational`, and sets the `EncoderParameter.NumberOfValues` property to 1.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| numerator | int | A 32-bit integer that represents the numerator of a fraction. Must be nonnegative. |
| denominator | int | A 32-bit integer that represents the denominator of a fraction. Must be nonnegative. |

### EncoderParameter(Encoder encoder, long rangebegin, long rangeend) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-long-long-}
```
public EncoderParameter(Encoder encoder, long rangebegin, long rangeend)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and a pair of 64-bit integers. The pair of integers represents a range of integers, the first integer being the smallest number in the range, and the second integer being the largest number in the range. Sets the `EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeLongRange`, and sets the `P:EncoderParameter.NumberOfValues` property to 1.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| rangebegin | long | A 64-bit integer that represents the smallest number in a range of integers. Must be nonnegative. This parameter is converted to a 32-bit integer before it is stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |
| rangeend | long | A 64-bit integer that represents the largest number in a range of integers. Must be nonnegative. This parameter is converted to a 32-bit integer before it is stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |

### EncoderParameter(Encoder encoder, int numerator1, int demoninator1, int numerator2, int demoninator2) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-int-int-}
```
public EncoderParameter(Encoder encoder, int numerator1, int demoninator1, int numerator2, int demoninator2)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and four, 32-bit integers. The four integers represent a range of fractions. The first two integers represent the smallest fraction in the range, and the remaining two integers represent the largest fraction in the range. Sets the `P:EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeRationalRange`, and sets the `P:EncoderParameter.NumberOfValues` property to 1.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| numerator1 | int | A 32-bit integer that represents the numerator of the smallest fraction in the range. Must be nonnegative. |
| demoninator1 | int | A 32-bit integer that represents the denominator of the smallest fraction in the range. Must be nonnegative. |
| numerator2 | int | A 32-bit integer that represents the numerator of the largest fraction in the range. Must be nonnegative. |
| demoninator2 | int | A 32-bit integer that represents the denominator of the largest fraction in the range. Must be nonnegative. |

### EncoderParameter(Encoder encoder, String value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-java.lang.String-}
```
public EncoderParameter(Encoder encoder, String value)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and a character string. The string is converted to a null-terminated ASCII string before it is stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. Sets the `P:EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeAscii`, and sets the `P:EncoderParameter.NumberOfValues` property to the length of the ASCII string including the NULL terminator.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | java.lang.String | A String that specifies the value stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |

### EncoderParameter(Encoder encoder, byte[] value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte---}
```
public EncoderParameter(Encoder encoder, byte[] value)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of unsigned 8-bit integers. Sets the `P:EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeByte`, and sets the `P:EncoderParameter.NumberOfValues` property to the number of elements in the array.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | byte[] | An array of 8-bit unsigned integers that specifies the values stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |

### EncoderParameter(Encoder encoder, byte[] value, boolean undefined) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte---boolean-}
```
public EncoderParameter(Encoder encoder, byte[] value, boolean undefined)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of bytes. Sets the `P:EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeUndefined` or `EncoderParameterValueType.ValueTypeByte`, and sets the `P:EncoderParameter.NumberOfValues` property to the number of elements in the array.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | byte[] | An array of bytes that specifies the values stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |
| undefined | boolean | If true, the `P:EncoderParameter.ValueType` property is set to `EncoderParameterValueType.ValueTypeUndefined`; otherwise, the `P:EncoderParameter.ValueType` property is set to `EncoderParameterValueType.ValueTypeByte`. |

### EncoderParameter(Encoder encoder, short[] value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-short---}
```
public EncoderParameter(Encoder encoder, short[] value)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of 16-bit integers. Sets the `P:EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeShort`, and sets the `P:EncoderParameter.NumberOfValues` property to the number of elements in the array.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | short[] | An array of 16-bit integers that specifies the values stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. The integers in the array must be nonnegative. |

### EncoderParameter(Encoder encoder, long[] value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-long---}
```
public EncoderParameter(Encoder encoder, long[] value)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of 64-bit integers. Sets the `P:EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeLong` (32-bit), and sets the `P:EncoderParameter.NumberOfValues` property to the number of elements in the array.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | long[] | Un tableau d'entiers 64 bits qui spécifie les valeurs stockées dans l'objet [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). Les entiers du tableau doivent être non négatifs. Les entiers 64 bits sont convertis en entiers 32 bits avant d'être stockés dans l'objet [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). |

### EncoderParameter(Encoder encoder, int[] numerator, int[] denominator) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int---int---}
```
public EncoderParameter(Encoder encoder, int[] numerator, int[] denominator)
```


Initialise une nouvelle instance de la classe [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) avec l'objet `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) spécifié et deux tableaux d'entiers 32 bits. Les deux tableaux représentent un tableau de fractions. Définit la propriété `P:EncoderParameter.ValueType` sur `EncoderParameterValueType.ValueTypeRational` et définit la propriété `P:EncoderParameter.NumberOfValues` sur le nombre d'éléments du tableau `numerator`, qui doit être identique au nombre d'éléments du tableau `denominator`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| numerator | int[] | Un tableau d'entiers 32 bits qui spécifie les numérateurs des fractions. Les entiers du tableau doivent être non négatifs. |
| denominator | int[] | Un tableau d'entiers 32 bits qui spécifie les dénominateurs des fractions. Les entiers du tableau doivent être non négatifs. Un dénominateur à un indice donné est associé au numérateur du même indice. |

### EncoderParameter(Encoder encoder, long[] rangebegin, long[] rangeend) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-long---long---}
```
public EncoderParameter(Encoder encoder, long[] rangebegin, long[] rangeend)
```


Initialise une nouvelle instance de la classe [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) avec l'objet `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) spécifié et deux tableaux d'entiers 64 bits. Les deux tableaux représentent un tableau de plages d'entiers. Définit la propriété `P:EncoderParameter.ValueType` sur `EncoderParameterValueType.ValueTypeLongRange` et définit la propriété `P:EncoderParameter.NumberOfValues` sur le nombre d'éléments du tableau `rangebegin`, qui doit être identique au nombre d'éléments du tableau `rangeend`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| rangebegin | long[] | Un tableau d'entiers 64 bits qui spécifie les valeurs minimales pour les plages d'entiers. Les entiers du tableau doivent être non négatifs. Les entiers 64 bits sont convertis en entiers 32 bits avant d'être stockés dans l'objet [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). |
| rangeend | long[] | Un tableau d'entiers 64 bits qui spécifie les valeurs maximales pour les plages d'entiers. Les entiers du tableau doivent être non négatifs. Les entiers 64 bits sont convertis en entiers 32 bits avant d'être stockés dans l'objet [EncoderParameters](../../com.aspose.drawing.imaging/encoderparameters). Une valeur maximale à un indice donné est associée à la valeur minimale du même indice. |

### EncoderParameter(Encoder encoder, int[] numerator1, int[] denominator1, int[] numerator2, int[] denominator2) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int---int---int---int---}
```
public EncoderParameter(Encoder encoder, int[] numerator1, int[] denominator1, int[] numerator2, int[] denominator2)
```


Initialise une nouvelle instance de la classe [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) avec l'objet `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) spécifié et quatre tableaux d'entiers 32 bits. Les quatre tableaux représentent un tableau de plages rationnelles. Une plage rationnelle est l'ensemble de toutes les fractions d'une valeur fractionnaire minimale à une valeur fractionnaire maximale. Définit la propriété `P:EncoderParameter.ValueType` sur `EncoderParameterValueType.ValueTypeRationalRange` et définit la propriété `P:EncoderParameter.NumberOfValues` sur le nombre d'éléments du tableau `numerator1`, qui doit être identique au nombre d'éléments des trois autres tableaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| numerator1 | int[] | Un tableau d'entiers 32 bits qui spécifie les numérateurs des valeurs minimales pour les plages. Les entiers du tableau doivent être non négatifs. |
| denominator1 | int[] | Un tableau d'entiers 32 bits qui spécifie les dénominateurs des valeurs minimales pour les plages. Les entiers du tableau doivent être non négatifs. |
| numerator2 | int[] | Un tableau d'entiers 32 bits qui spécifie les numérateurs des valeurs maximales pour les plages. Les entiers du tableau doivent être non négatifs. |
| denominator2 | int[] | Un tableau d'entiers 32 bits qui spécifie les dénominateurs des valeurs maximales pour les plages. Les entiers du tableau doivent être non négatifs. |

### EncoderParameter(Encoder encoder, int numberOfValues, int type, int value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-int-}
```
public EncoderParameter(Encoder encoder, int numberOfValues, int type, int value)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and three integers that specify the number of values, the data type of the values, and a pointer to the values stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| numberOfValues | int | Un entier qui spécifie le nombre de valeurs stockées dans l'objet [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). La propriété `P:EncoderParameter.NumberOfValues` est définie à cette valeur. |
| type | int | Un membre de l'énumération `EncoderParameterValueType` qui spécifie le type de données des valeurs stockées dans l'objet [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). Les propriétés Type et `P:EncoderParameter.ValueType` sont définies à cette valeur. |
| value | int | Un pointeur vers un tableau de valeurs du type spécifié par le paramètre `type`. |

### getEncoder() {#getEncoder--}
```
public Encoder getEncoder()
```


Obtient ou définit l'objet `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) associé à cet objet [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). L'objet `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) encapsule l'identifiant unique global (GUID) qui spécifie la catégorie (par exemple `Encoder.Quality`, `Encoder.ColorDepth` ou `Encoder.Compression`) du paramètre stocké dans cet objet [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter).

**Returns:**
[Encoder](../../com.aspose.drawing.imaging/encoder)
### setEncoder(Encoder value) {#setEncoder-com.aspose.drawing.imaging.Encoder-}
```
public void setEncoder(Encoder value)
```


Obtient ou définit l'objet `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) associé à cet objet [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). L'objet `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) encapsule l'identifiant unique global (GUID) qui spécifie la catégorie (par exemple `Encoder.Quality`, `Encoder.ColorDepth` ou `Encoder.Compression`) du paramètre stocké dans cet objet [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter).

**Parameters:**
| Paramètre | Type | Description |
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

