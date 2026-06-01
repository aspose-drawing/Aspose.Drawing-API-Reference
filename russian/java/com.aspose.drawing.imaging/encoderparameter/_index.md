---
title: EncoderParameter
second_title: Справочник API Aspose.Drawing для Java
description: Используется для передачи значения или массива значений кодировщику изображения.
type: docs
weight: 20
url: /ru/java/com.aspose.drawing.imaging/encoderparameter/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class EncoderParameter implements System.IDisposable
```

Используется для передачи значения или массива значений кодировщику изображения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EncoderParameter(Encoder encoder, byte value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte-) | Инициализирует новый экземпляр класса [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) с указанным объектом `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) и одним беззнаковым 8‑битным целым числом. |
| [EncoderParameter(Encoder encoder, byte value, boolean undefined)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte-boolean-) | Инициализирует новый экземпляр класса [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) с указанным объектом `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) и одним 8‑битным значением. |
| [EncoderParameter(Encoder encoder, short value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-short-) | Инициализирует новый экземпляр класса [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) с указанным объектом `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) и одним 16‑битным целым числом. |
| [EncoderParameter(Encoder encoder, long value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-long-) | Инициализирует новый экземпляр класса [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) с указанным объектом `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) и одним 64‑битным целым числом. |
| [EncoderParameter(Encoder encoder, int numerator, int denominator)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-) | Инициализирует новый экземпляр класса [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) с указанным объектом \{@link \#\#System\} и парой 32‑битных целых чисел. |
| [EncoderParameter(Encoder encoder, long rangebegin, long rangeend)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-long-long-) | Инициализирует новый экземпляр класса [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) с указанным объектом `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) и парой 64‑битных целых чисел. |
| [EncoderParameter(Encoder encoder, int numerator1, int demoninator1, int numerator2, int demoninator2)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-int-int-) | Инициализирует новый экземпляр класса [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) с указанным объектом `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) и четырьмя 32‑битными целыми числами. |
| [EncoderParameter(Encoder encoder, String value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-java.lang.String-) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and a character string. |
| [EncoderParameter(Encoder encoder, byte[] value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of unsigned 8-bit integers. |
| [EncoderParameter(Encoder encoder, byte[] value, boolean undefined)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte---boolean-) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of bytes. |
| [EncoderParameter(Encoder encoder, short[] value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-short---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of 16-bit integers. |
| [EncoderParameter(Encoder encoder, long[] value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-long---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of 64-bit integers. |
| [EncoderParameter(Encoder encoder, int[] numerator, int[] denominator)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int---int---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and two arrays of 32-bit integers. |
| [EncoderParameter(Encoder encoder, long[] rangebegin, long[] rangeend)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-long---long---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and two arrays of 64-bit integers. |
| [EncoderParameter(Encoder encoder, int[] numerator1, int[] denominator1, int[] numerator2, int[] denominator2)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int---int---int---int---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and four arrays of 32-bit integers. |
| [EncoderParameter(Encoder encoder, int numberOfValues, int type, int value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-int-) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and three integers that specify the number of values, the data type of the values, and a pointer to the values stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |
## Методы

| Метод | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | byte | An 8-bit unsigned integer that specifies the value stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |

### EncoderParameter(Encoder encoder, byte value, boolean undefined) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte-boolean-}
```
public EncoderParameter(Encoder encoder, byte value, boolean undefined)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and one 8-bit value. Sets the `EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeUndefined` or `EncoderParameterValueType.ValueTypeByte`, and sets the `EncoderParameter.NumberOfValues` property to 1.

**Parameters:**
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | short | A 16-bit integer that specifies the value stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. Must be nonnegative. |

### EncoderParameter(Encoder encoder, long value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-long-}
```
public EncoderParameter(Encoder encoder, long value)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and one 64-bit integer. Sets the `EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeLong` (32 bits), and sets the `EncoderParameter.NumberOfValues` property to 1.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | long | A 64-bit integer that specifies the value stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. Must be nonnegative. This parameter is converted to a 32-bit integer before it is stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |

### EncoderParameter(Encoder encoder, int numerator, int denominator) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-}
```
public EncoderParameter(Encoder encoder, int numerator, int denominator)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified \{@link \#\#System\} object and a pair of 32-bit integers. The pair of integers represents a fraction, the first integer being the numerator, and the second integer being the denominator. Sets the `EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeRational`, and sets the `EncoderParameter.NumberOfValues` property to 1.

**Parameters:**
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | java.lang.String | A String that specifies the value stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |

### EncoderParameter(Encoder encoder, byte[] value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte---}
```
public EncoderParameter(Encoder encoder, byte[] value)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of unsigned 8-bit integers. Sets the `P:EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeByte`, and sets the `P:EncoderParameter.NumberOfValues` property to the number of elements in the array.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | byte[] | An array of 8-bit unsigned integers that specifies the values stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |

### EncoderParameter(Encoder encoder, byte[] value, boolean undefined) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte---boolean-}
```
public EncoderParameter(Encoder encoder, byte[] value, boolean undefined)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of bytes. Sets the `P:EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeUndefined` or `EncoderParameterValueType.ValueTypeByte`, and sets the `P:EncoderParameter.NumberOfValues` property to the number of elements in the array.

**Parameters:**
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | short[] | An array of 16-bit integers that specifies the values stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. The integers in the array must be nonnegative. |

### EncoderParameter(Encoder encoder, long[] value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-long---}
```
public EncoderParameter(Encoder encoder, long[] value)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of 64-bit integers. Sets the `P:EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeLong` (32-bit), and sets the `P:EncoderParameter.NumberOfValues` property to the number of elements in the array.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | long[] | Массив 64‑битных целых чисел, который задаёт значения, хранящиеся в объекте [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. Целые числа в массиве должны быть неотрицательными. 64‑битные целые числа преобразуются в 32‑битные перед тем, как они будут сохранены в объекте [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |

### EncoderParameter(Encoder encoder, int[] numerator, int[] denominator) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int---int---}
```
public EncoderParameter(Encoder encoder, int[] numerator, int[] denominator)
```


Инициализирует новый экземпляр класса [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) с указанным объектом `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) и двумя массивами 32‑битных целых чисел. Эти два массива представляют массив дробей. Устанавливает свойство `P:EncoderParameter.ValueType` в значение `EncoderParameterValueType.ValueTypeRational` и задаёт свойство `P:EncoderParameter.NumberOfValues` равным количеству элементов в массиве `numerator`, которое должно совпадать с количеством элементов в массиве `denominator`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| numerator | int[] | Массив 32‑битных целых чисел, задающий числители дробей. Числа в массиве должны быть неотрицательными. |
| denominator | int[] | Массив 32‑битных целых чисел, задающий знаменатели дробей. Числа в массиве должны быть неотрицательными. Знаменатель с определённым индексом сопоставляется с числителем того же индекса. |

### EncoderParameter(Encoder encoder, long[] rangebegin, long[] rangeend) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-long---long---}
```
public EncoderParameter(Encoder encoder, long[] rangebegin, long[] rangeend)
```


Инициализирует новый экземпляр класса [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) с указанным объектом `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) и двумя массивами 64‑битных целых чисел. Эти два массива представляют диапазоны целых чисел. Устанавливает свойство `P:EncoderParameter.ValueType` в значение `EncoderParameterValueType.ValueTypeLongRange` и задаёт свойство `P:EncoderParameter.NumberOfValues` равным количеству элементов в массиве `rangebegin`, которое должно совпадать с количеством элементов в массиве `rangeend`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| rangebegin | long[] | Массив 64‑битных целых чисел, задающий минимальные значения диапазонов целых чисел. Числа в массиве должны быть неотрицательными. 64‑битные целые числа преобразуются в 32‑битные перед сохранением в объекте [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |
| rangeend | long[] | Массив 64‑битных целых чисел, задающий максимальные значения диапазонов целых чисел. Числа в массиве должны быть неотрицательными. 64‑битные целые числа преобразуются в 32‑битные перед сохранением в объекте [EncoderParameters](../../com.aspose.drawing.imaging/encoderparameters) object. Максимальное значение с определённым индексом сопоставляется с минимальным значением того же индекса. |

### EncoderParameter(Encoder encoder, int[] numerator1, int[] denominator1, int[] numerator2, int[] denominator2) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int---int---int---int---}
```
public EncoderParameter(Encoder encoder, int[] numerator1, int[] denominator1, int[] numerator2, int[] denominator2)
```


Инициализирует новый экземпляр класса [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) с указанным объектом `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) и четырьмя массивами 32‑битных целых чисел. Эти четыре массива представляют диапазоны рациональных чисел. Рациональный диапазон — это набор всех дробей от минимального дробного значения до максимального дробного значения. Устанавливает свойство `P:EncoderParameter.ValueType` в значение `EncoderParameterValueType.ValueTypeRationalRange` и задаёт свойство `P:EncoderParameter.NumberOfValues` равным количеству элементов в массиве `numerator1`, которое должно совпадать с количеством элементов в остальных трёх массивах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| numerator1 | int[] | Массив 32‑битных целых чисел, задающий числители минимальных значений диапазонов. Числа в массиве должны быть неотрицательными. |
| denominator1 | int[] | Массив 32‑битных целых чисел, задающий знаменатели минимальных значений диапазонов. Числа в массиве должны быть неотрицательными. |
| numerator2 | int[] | Массив 32‑битных целых чисел, задающий числители максимальных значений диапазонов. Числа в массиве должны быть неотрицательными. |
| denominator2 | int[] | Массив 32‑битных целых чисел, задающий знаменатели максимальных значений диапазонов. Числа в массиве должны быть неотрицательными. |

### EncoderParameter(Encoder encoder, int numberOfValues, int type, int value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-int-}
```
public EncoderParameter(Encoder encoder, int numberOfValues, int type, int value)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and three integers that specify the number of values, the data type of the values, and a pointer to the values stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| numberOfValues | int | Целое число, указывающее количество значений, хранящихся в объекте [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. Свойство `P:EncoderParameter.NumberOfValues` устанавливается в это значение. |
| type | int | Элемент перечисления `EncoderParameterValueType`, определяющий тип данных значений, хранящихся в объекте [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. Свойства Type и `P:EncoderParameter.ValueType` устанавливаются в это значение. |
| value | int | Указатель на массив значений типа, указанного параметром `type`. |

### getEncoder() {#getEncoder--}
```
public Encoder getEncoder()
```


Получает или задаёт объект `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) , связанный с этим объектом [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. Объект `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) инкапсулирует глобальный уникальный идентификатор (GUID), определяющий категорию (например `Encoder.Quality`, `Encoder.ColorDepth` или `Encoder.Compression`) параметра, хранящегося в этом объекте [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object.

**Returns:**
[Encoder](../../com.aspose.drawing.imaging/encoder)
### setEncoder(Encoder value) {#setEncoder-com.aspose.drawing.imaging.Encoder-}
```
public void setEncoder(Encoder value)
```


Получает или задаёт объект `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) , связанный с этим объектом [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. Объект `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) инкапсулирует глобальный уникальный идентификатор (GUID), определяющий категорию (например `Encoder.Quality`, `Encoder.ColorDepth` или `Encoder.Compression`) параметра, хранящегося в этом объекте [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object.

**Parameters:**
| Параметр | Тип | Описание |
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

