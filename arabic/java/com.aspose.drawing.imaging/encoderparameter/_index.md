---
title: EncoderParameter
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يُستخدم لتمرير قيمة أو مصفوفة من القيم إلى مشفر الصورة.
type: docs
weight: 20
url: /ar/java/com.aspose.drawing.imaging/encoderparameter/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class EncoderParameter implements System.IDisposable
```

يُستخدم لتمرير قيمة أو مصفوفة من القيم إلى مشفر الصورة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [EncoderParameter(Encoder encoder, byte value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte-) | ينشئ مثيلًا جديدًا من فئة [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) باستخدام كائن `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) المحدد وعدد صحيح غير موقع 8‑بت واحد. |
| [EncoderParameter(Encoder encoder, byte value, boolean undefined)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte-boolean-) | ينشئ مثيلًا جديدًا من فئة [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) باستخدام كائن `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) المحدد وقيمة 8‑بت واحدة. |
| [EncoderParameter(Encoder encoder, short value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-short-) | ينشئ مثيلًا جديدًا من فئة [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) باستخدام كائن `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) المحدد وعدد صحيح 16‑بت واحد. |
| [EncoderParameter(Encoder encoder, long value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-long-) | ينشئ مثيلًا جديدًا من فئة [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) باستخدام كائن `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) المحدد وعدد صحيح 64‑بت واحد. |
| [EncoderParameter(Encoder encoder, int numerator, int denominator)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-) | ينشئ مثيلًا جديدًا من فئة [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) باستخدام كائن \{@link \#\#System\} المحدد وزوج من الأعداد الصحيحة 32‑بت. |
| [EncoderParameter(Encoder encoder, long rangebegin, long rangeend)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-long-long-) | ينشئ مثيلًا جديدًا من فئة [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) باستخدام كائن `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) المحدد وزوج من الأعداد الصحيحة 64‑بت. |
| [EncoderParameter(Encoder encoder, int numerator1, int demoninator1, int numerator2, int demoninator2)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-int-int-) | ينشئ مثيلًا جديدًا من فئة [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) باستخدام كائن `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) المحدد وأربعة أعداد صحيحة 32‑بت. |
| [EncoderParameter(Encoder encoder, String value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-java.lang.String-) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and a character string. |
| [EncoderParameter(Encoder encoder, byte[] value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of unsigned 8-bit integers. |
| [EncoderParameter(Encoder encoder, byte[] value, boolean undefined)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte---boolean-) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of bytes. |
| [EncoderParameter(Encoder encoder, short[] value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-short---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of 16-bit integers. |
| [EncoderParameter(Encoder encoder, long[] value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-long---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of 64-bit integers. |
| [EncoderParameter(Encoder encoder, int[] numerator, int[] denominator)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int---int---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and two arrays of 32-bit integers. |
| [EncoderParameter(Encoder encoder, long[] rangebegin, long[] rangeend)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-long---long---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and two arrays of 64-bit integers. |
| [EncoderParameter(Encoder encoder, int[] numerator1, int[] denominator1, int[] numerator2, int[] denominator2)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int---int---int---int---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and four arrays of 32-bit integers. |
| [EncoderParameter(Encoder encoder, int numberOfValues, int type, int value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-int-) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and three integers that specify the number of values, the data type of the values, and a pointer to the values stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |
## الطرق

| طريقة | الوصف |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | byte | An 8-bit unsigned integer that specifies the value stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |

### EncoderParameter(Encoder encoder, byte value, boolean undefined) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte-boolean-}
```
public EncoderParameter(Encoder encoder, byte value, boolean undefined)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and one 8-bit value. Sets the `EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeUndefined` or `EncoderParameterValueType.ValueTypeByte`, and sets the `EncoderParameter.NumberOfValues` property to 1.

**Parameters:**
| معامل | نوع | الوصف |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | short | A 16-bit integer that specifies the value stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. Must be nonnegative. |

### EncoderParameter(Encoder encoder, long value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-long-}
```
public EncoderParameter(Encoder encoder, long value)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and one 64-bit integer. Sets the `EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeLong` (32 bits), and sets the `EncoderParameter.NumberOfValues` property to 1.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | long | A 64-bit integer that specifies the value stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. Must be nonnegative. This parameter is converted to a 32-bit integer before it is stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |

### EncoderParameter(Encoder encoder, int numerator, int denominator) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-}
```
public EncoderParameter(Encoder encoder, int numerator, int denominator)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified \{@link \#\#System\} object and a pair of 32-bit integers. The pair of integers represents a fraction, the first integer being the numerator, and the second integer being the denominator. Sets the `EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeRational`, and sets the `EncoderParameter.NumberOfValues` property to 1.

**Parameters:**
| معامل | نوع | الوصف |
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
| معامل | نوع | الوصف |
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
| معامل | نوع | الوصف |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | java.lang.String | A String that specifies the value stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |

### EncoderParameter(Encoder encoder, byte[] value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte---}
```
public EncoderParameter(Encoder encoder, byte[] value)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of unsigned 8-bit integers. Sets the `P:EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeByte`, and sets the `P:EncoderParameter.NumberOfValues` property to the number of elements in the array.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | byte[] | An array of 8-bit unsigned integers that specifies the values stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |

### EncoderParameter(Encoder encoder, byte[] value, boolean undefined) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte---boolean-}
```
public EncoderParameter(Encoder encoder, byte[] value, boolean undefined)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of bytes. Sets the `P:EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeUndefined` or `EncoderParameterValueType.ValueTypeByte`, and sets the `P:EncoderParameter.NumberOfValues` property to the number of elements in the array.

**Parameters:**
| معامل | نوع | الوصف |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | short[] | An array of 16-bit integers that specifies the values stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. The integers in the array must be nonnegative. |

### EncoderParameter(Encoder encoder, long[] value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-long---}
```
public EncoderParameter(Encoder encoder, long[] value)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of 64-bit integers. Sets the `P:EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeLong` (32-bit), and sets the `P:EncoderParameter.NumberOfValues` property to the number of elements in the array.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | long[] | مصفوفة من أعداد صحيحة 64‑بت تحدد القيم المخزنة في كائن [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). يجب أن تكون الأعداد الصحيحة في المصفوفة غير سالبة. يتم تحويل أعداد 64‑بت إلى أعداد 32‑بت قبل تخزينها في كائن [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). |

### EncoderParameter(Encoder encoder, int[] numerator, int[] denominator) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int---int---}
```
public EncoderParameter(Encoder encoder, int[] numerator, int[] denominator)
```


يُنشئ مثيلاً جديداً من فئة [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) باستخدام كائن `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) المحدد ومصفوفتين من أعداد 32‑بت. تمثل المصفوفتان مجموعة من الكسور. يضبط الخاصية `P:EncoderParameter.ValueType` إلى `EncoderParameterValueType.ValueTypeRational`، ويضبط الخاصية `P:EncoderParameter.NumberOfValues` إلى عدد العناصر في مصفوفة `numerator`، والتي يجب أن تكون مساوية لعدد العناصر في مصفوفة `denominator`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| numerator | int[] | مصفوفة من أعداد صحيحة 32‑بت تحدد البسط للكسور. يجب أن تكون الأعداد الصحيحة في المصفوفة غير سالبة. |
| denominator | int[] | مصفوفة من أعداد صحيحة 32‑بت تحدد المقام للكسور. يجب أن تكون الأعداد الصحيحة في المصفوفة غير سالبة. يتم إقران المقام في الفهرس المحدد مع البسط في نفس الفهرس. |

### EncoderParameter(Encoder encoder, long[] rangebegin, long[] rangeend) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-long---long---}
```
public EncoderParameter(Encoder encoder, long[] rangebegin, long[] rangeend)
```


يُنشئ مثيلاً جديداً من فئة [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) باستخدام كائن `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) المحدد ومصفوفتين من أعداد 64‑بت. تمثل المصفوفتان نطاقات أعداد صحيحة. يضبط الخاصية `P:EncoderParameter.ValueType` إلى `EncoderParameterValueType.ValueTypeLongRange`، ويضبط الخاصية `P:EncoderParameter.NumberOfValues` إلى عدد العناصر في مصفوفة `rangebegin`، والتي يجب أن تكون مساوية لعدد العناصر في مصفوفة `rangeend`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| rangebegin | long[] | مصفوفة من أعداد صحيحة 64‑بت تحدد القيم الدنيا لنطاقات الأعداد الصحيحة. يجب أن تكون الأعداد الصحيحة في المصفوفة غير سالبة. يتم تحويل أعداد 64‑بت إلى أعداد 32‑بت قبل تخزينها في كائن [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). |
| rangeend | long[] | مصفوفة من أعداد صحيحة 64‑بت تحدد القيم العظمى لنطاقات الأعداد الصحيحة. يجب أن تكون الأعداد الصحيحة في المصفوفة غير سالبة. يتم تحويل أعداد 64‑بت إلى أعداد 32‑بت قبل تخزينها في كائن [EncoderParameters](../../com.aspose.drawing.imaging/encoderparameters). يتم إقران القيمة العظمى في الفهرس المحدد مع القيمة الدنيا في نفس الفهرس. |

### EncoderParameter(Encoder encoder, int[] numerator1, int[] denominator1, int[] numerator2, int[] denominator2) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int---int---int---int---}
```
public EncoderParameter(Encoder encoder, int[] numerator1, int[] denominator1, int[] numerator2, int[] denominator2)
```


يُنشئ مثيلاً جديداً من فئة [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) باستخدام كائن `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) المحدد وأربع مصفوفات من أعداد 32‑بت. تمثل الأربع مصفوفات نطاقات كسرية. النطاق الكسرى هو مجموعة جميع الكسور من قيمة كسرية دنيا إلى قيمة كسرية عظمى. يضبط الخاصية `P:EncoderParameter.ValueType` إلى `EncoderParameterValueType.ValueTypeRationalRange`، ويضبط الخاصية `P:EncoderParameter.NumberOfValues` إلى عدد العناصر في مصفوفة `numerator1`، والتي يجب أن تكون مساوية لعدد العناصر في المصفوفات الثلاثة الأخرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| numerator1 | int[] | مصفوفة من أعداد صحيحة 32‑بت تحدد بسط القيم الدنيا للنطاقات. يجب أن تكون الأعداد الصحيحة في المصفوفة غير سالبة. |
| denominator1 | int[] | مصفوفة من أعداد صحيحة 32‑بت تحدد مقام القيم الدنيا للنطاقات. يجب أن تكون الأعداد الصحيحة في المصفوفة غير سالبة. |
| numerator2 | int[] | مصفوفة من أعداد صحيحة 32‑بت تحدد بسط القيم العظمى للنطاقات. يجب أن تكون الأعداد الصحيحة في المصفوفة غير سالبة. |
| denominator2 | int[] | مصفوفة من أعداد صحيحة 32‑بت تحدد مقام القيم العظمى للنطاقات. يجب أن تكون الأعداد الصحيحة في المصفوفة غير سالبة. |

### EncoderParameter(Encoder encoder, int numberOfValues, int type, int value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-int-}
```
public EncoderParameter(Encoder encoder, int numberOfValues, int type, int value)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and three integers that specify the number of values, the data type of the values, and a pointer to the values stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| numberOfValues | int | عدد صحيح يحدد عدد القيم المخزنة في كائن [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). يتم تعيين الخاصية `P:EncoderParameter.NumberOfValues` إلى هذه القيمة. |
| type | int | عضو من تعداد `EncoderParameterValueType` يحدد نوع البيانات للقيم المخزنة في كائن [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). يتم تعيين الخاصيتين Type و `P:EncoderParameter.ValueType` إلى هذه القيمة. |
| value | int | مؤشر إلى مصفوفة من القيم من النوع المحدد بواسطة المعامل `type`. |

### getEncoder() {#getEncoder--}
```
public Encoder getEncoder()
```


يحصل أو يضبط كائن `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) المرتبط بهذا كائن [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). كائن `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) يحتوي على المعرف الفريد عالمياً (GUID) الذي يحدد الفئة (على سبيل المثال `Encoder.Quality`، `Encoder.ColorDepth`، أو `Encoder.Compression`) للمعامل المخزن في هذا كائن [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter).

**Returns:**
[Encoder](../../com.aspose.drawing.imaging/encoder)
### setEncoder(Encoder value) {#setEncoder-com.aspose.drawing.imaging.Encoder-}
```
public void setEncoder(Encoder value)
```


يحصل أو يضبط كائن `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) المرتبط بهذا كائن [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). كائن `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) يحتوي على المعرف الفريد عالمياً (GUID) الذي يحدد الفئة (على سبيل المثال `Encoder.Quality`، `Encoder.ColorDepth`، أو `Encoder.Compression`) للمعامل المخزن في هذا كائن [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter).

**Parameters:**
| معامل | نوع | الوصف |
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

