---
title: EncoderParameter
second_title: Aspose.Drawing för Java API‑referens
description: Används för att skicka ett värde eller en array av värden till en bildkodare.
type: docs
weight: 20
url: /sv/java/com.aspose.drawing.imaging/encoderparameter/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class EncoderParameter implements System.IDisposable
```

Används för att skicka ett värde, eller en array av värden, till en bildkodare.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EncoderParameter(Encoder encoder, byte value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte-) | Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objektet och ett osignerat 8-bitars heltal. |
| [EncoderParameter(Encoder encoder, byte value, boolean undefined)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte-boolean-) | Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objektet och ett 8-bitars värde. |
| [EncoderParameter(Encoder encoder, short value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-short-) | Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objektet och ett 16-bitars heltal. |
| [EncoderParameter(Encoder encoder, long value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-long-) | Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objektet och ett 64-bitars heltal. |
| [EncoderParameter(Encoder encoder, int numerator, int denominator)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-) | Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna \{@link \#\#System\}-objektet och ett par 32-bitars heltal. |
| [EncoderParameter(Encoder encoder, long rangebegin, long rangeend)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-long-long-) | Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objektet och ett par 64-bitars heltal. |
| [EncoderParameter(Encoder encoder, int numerator1, int demoninator1, int numerator2, int demoninator2)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-int-int-) | Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objektet och fyra 32-bitars heltal. |
| [EncoderParameter(Encoder encoder, String value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-java.lang.String-) | Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objektet och en teckensträng. |
| [EncoderParameter(Encoder encoder, byte[] value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte---) | Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objektet och en array av osignerade 8‑bitars heltal. |
| [EncoderParameter(Encoder encoder, byte[] value, boolean undefined)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte---boolean-) | Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objektet och en array av byte. |
| [EncoderParameter(Encoder encoder, short[] value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-short---) | Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objektet och en array av 16‑bitars heltal. |
| [EncoderParameter(Encoder encoder, long[] value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-long---) | Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objektet och en array av 64‑bitars heltal. |
| [EncoderParameter(Encoder encoder, int[] numerator, int[] denominator)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int---int---) | Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objektet och två arrayer av 32‑bitars heltal. |
| [EncoderParameter(Encoder encoder, long[] rangebegin, long[] rangeend)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-long---long---) | Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objektet och två arrayer av 64‑bitars heltal. |
| [EncoderParameter(Encoder encoder, int[] numerator1, int[] denominator1, int[] numerator2, int[] denominator2)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int---int---int---int---) | Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objektet och fyra arrayer av 32‑bitars heltal. |
| [EncoderParameter(Encoder encoder, int numberOfValues, int type, int value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-int-) | Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objektet och tre heltal som specificerar antalet värden, datatypen för värdena och en pekare till värdena som lagras i objektet [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEncoder()](#getEncoder--) | Hämtar eller anger `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objektet som är associerat med detta [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter)-objekt. |
| [setEncoder(Encoder value)](#setEncoder-com.aspose.drawing.imaging.Encoder-) | Hämtar eller anger `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objektet som är associerat med detta [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter)-objekt. |
| [getNumberOfValues()](#getNumberOfValues--) | Hämtar antalet element i arrayen av värden som lagras i detta [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter)-objekt. |
| [dispose()](#dispose--) | Frigör alla resurser som används av detta [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter)-objekt. |
### EncoderParameter(Encoder encoder, byte value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte-}
```
public EncoderParameter(Encoder encoder, byte value)
```


Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objektet och ett osignerat 8‑bitars heltal. Sätter egenskapen `EncoderParameter.ValueType` till `EncoderParameterValueType.ValueTypeByte` och sätter egenskapen `EncoderParameter.NumberOfValues` till 1.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | Ett `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objekt som kapslar in den globalt unika identifieraren för parameterkategorin. |
| value | byte | Ett 8‑bitars osignerat heltal som specificerar värdet som lagras i objektet [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). |

### EncoderParameter(Encoder encoder, byte value, boolean undefined) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte-boolean-}
```
public EncoderParameter(Encoder encoder, byte value, boolean undefined)
```


Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objektet och ett 8‑bitars värde. Sätter egenskapen `EncoderParameter.ValueType` till `EncoderParameterValueType.ValueTypeUndefined` eller `EncoderParameterValueType.ValueTypeByte` och sätter egenskapen `EncoderParameter.NumberOfValues` till 1.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | Ett `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objekt som kapslar in den globalt unika identifieraren för parameterkategorin. |
| value | byte | En byte som specificerar värdet som lagras i objektet [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). |
| undefined | boolean | Om true sätts egenskapen `EncoderParameter.ValueType` till `EncoderParameterValueType.ValueTypeUndefined`; annars sätts egenskapen `EncoderParameter.ValueType` till `EncoderParameterValueType.ValueTypeByte`. |

### EncoderParameter(Encoder encoder, short value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-short-}
```
public EncoderParameter(Encoder encoder, short value)
```


Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objektet och ett 16‑bitars heltal. Sätter egenskapen `EncoderParameter.ValueType` till `EncoderParameterValueType.ValueTypeShort` och sätter egenskapen `EncoderParameter.NumberOfValues` till 1.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | Ett `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objekt som kapslar in den globalt unika identifieraren för parameterkategorin. |
| value | short | Ett 16‑bitars heltal som specificerar värdet som lagras i objektet [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). Måste vara icke‑negativt. |

### EncoderParameter(Encoder encoder, long value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-long-}
```
public EncoderParameter(Encoder encoder, long value)
```


Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objektet och ett 64‑bitars heltal. Sätter egenskapen `EncoderParameter.ValueType` till `EncoderParameterValueType.ValueTypeLong` (32 bitar) och sätter egenskapen `EncoderParameter.NumberOfValues` till 1.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | Ett `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objekt som kapslar in den globalt unika identifieraren för parameterkategorin. |
| value | long | Ett 64‑bitars heltal som specificerar värdet som lagras i objektet [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). Måste vara icke‑negativt. Denna parameter konverteras till ett 32‑bitars heltal innan den lagras i objektet [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). |

### EncoderParameter(Encoder encoder, int numerator, int denominator) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-}
```
public EncoderParameter(Encoder encoder, int numerator, int denominator)
```


Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna \{@link \#\#System\}-objektet och ett par 32‑bitars heltal. Parets heltal representerar en bråkdel, där det första heltalet är täljaren och det andra heltalet är nämnaren. Sätter egenskapen `EncoderParameter.ValueType` till `EncoderParameterValueType.ValueTypeRational` och sätter egenskapen `EncoderParameter.NumberOfValues` till 1.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | Ett `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objekt som kapslar in den globalt unika identifieraren för parameterkategorin. |
| täljare | int | A 32-bit integer that represents the numerator of a fraction. Must be nonnegative. |
| denominator | int | A 32-bit integer that represents the denominator of a fraction. Must be nonnegative. |

### EncoderParameter(Encoder encoder, long rangebegin, long rangeend) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-long-long-}
```
public EncoderParameter(Encoder encoder, long rangebegin, long rangeend)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and a pair of 64-bit integers. The pair of integers represents a range of integers, the first integer being the smallest number in the range, and the second integer being the largest number in the range. Sets the `EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeLongRange`, and sets the `P:EncoderParameter.NumberOfValues` property to 1.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | Ett `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objekt som kapslar in den globalt unika identifieraren för parameterkategorin. |
| rangebegin | long | A 64-bit integer that represents the smallest number in a range of integers. Must be nonnegative. This parameter is converted to a 32-bit integer before it is stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |
| rangeend | long | A 64-bit integer that represents the largest number in a range of integers. Must be nonnegative. This parameter is converted to a 32-bit integer before it is stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |

### EncoderParameter(Encoder encoder, int numerator1, int demoninator1, int numerator2, int demoninator2) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-int-int-}
```
public EncoderParameter(Encoder encoder, int numerator1, int demoninator1, int numerator2, int demoninator2)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and four, 32-bit integers. The four integers represent a range of fractions. The first two integers represent the smallest fraction in the range, and the remaining two integers represent the largest fraction in the range. Sets the `P:EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeRationalRange`, and sets the `P:EncoderParameter.NumberOfValues` property to 1.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | Ett `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objekt som kapslar in den globalt unika identifieraren för parameterkategorin. |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | Ett `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objekt som kapslar in den globalt unika identifieraren för parameterkategorin. |
| value | java.lang.String | A String that specifies the value stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |

### EncoderParameter(Encoder encoder, byte[] value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte---}
```
public EncoderParameter(Encoder encoder, byte[] value)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of unsigned 8-bit integers. Sets the `P:EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeByte`, and sets the `P:EncoderParameter.NumberOfValues` property to the number of elements in the array.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | Ett `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objekt som kapslar in den globalt unika identifieraren för parameterkategorin. |
| value | byte[] | An array of 8-bit unsigned integers that specifies the values stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |

### EncoderParameter(Encoder encoder, byte[] value, boolean undefined) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte---boolean-}
```
public EncoderParameter(Encoder encoder, byte[] value, boolean undefined)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of bytes. Sets the `P:EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeUndefined` or `EncoderParameterValueType.ValueTypeByte`, and sets the `P:EncoderParameter.NumberOfValues` property to the number of elements in the array.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | Ett `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objekt som kapslar in den globalt unika identifieraren för parameterkategorin. |
| value | byte[] | An array of bytes that specifies the values stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |
| undefined | boolean | If true, the `P:EncoderParameter.ValueType` property is set to `EncoderParameterValueType.ValueTypeUndefined`; otherwise, the `P:EncoderParameter.ValueType` property is set to `EncoderParameterValueType.ValueTypeByte`. |

### EncoderParameter(Encoder encoder, short[] value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-short---}
```
public EncoderParameter(Encoder encoder, short[] value)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of 16-bit integers. Sets the `P:EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeShort`, and sets the `P:EncoderParameter.NumberOfValues` property to the number of elements in the array.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | Ett `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objekt som kapslar in den globalt unika identifieraren för parameterkategorin. |
| value | short[] | An array of 16-bit integers that specifies the values stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. The integers in the array must be nonnegative. |

### EncoderParameter(Encoder encoder, long[] value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-long---}
```
public EncoderParameter(Encoder encoder, long[] value)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of 64-bit integers. Sets the `P:EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeLong` (32-bit), and sets the `P:EncoderParameter.NumberOfValues` property to the number of elements in the array.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | Ett `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objekt som kapslar in den globalt unika identifieraren för parameterkategorin. |
| value | long[] | En array av 64-bitars heltal som specificerar värdena som lagras i [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter)‑objektet. Heltalen i arrayen måste vara icke‑negativa. De 64-bitars heltalen konverteras till 32-bitars heltal innan de lagras i [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter)‑objektet. |

### EncoderParameter(Encoder encoder, int[] numerator, int[] denominator) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int---int---}
```
public EncoderParameter(Encoder encoder, int[] numerator, int[] denominator)
```


Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))‑objektet och två arrayer av 32-bitars heltal. De två arrayerna representerar en array av bråktal. Sätter egenskapen `P:EncoderParameter.ValueType` till `EncoderParameterValueType.ValueTypeRational` och sätter egenskapen `P:EncoderParameter.NumberOfValues` till antalet element i `numerator`‑arrayen, vilket måste vara samma som antalet element i `denominator`‑arrayen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | Ett `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objekt som kapslar in den globalt unika identifieraren för parameterkategorin. |
| täljare | int[] | En array av 32-bitars heltal som specificerar täljarna i bråktalen. Heltalen i arrayen måste vara icke‑negativa. |
| denominator | int[] | En array av 32-bitars heltal som specificerar nämnarna i bråktalen. Heltalen i arrayen måste vara icke‑negativa. En nämnare på ett givet index paras ihop med täljaren på samma index. |

### EncoderParameter(Encoder encoder, long[] rangebegin, long[] rangeend) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-long---long---}
```
public EncoderParameter(Encoder encoder, long[] rangebegin, long[] rangeend)
```


Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))‑objektet och två arrayer av 64-bitars heltal. De två arrayerna representerar ett intervall av heltal. Sätter egenskapen `P:EncoderParameter.ValueType` till `EncoderParameterValueType.ValueTypeLongRange` och sätter egenskapen `P:EncoderParameter.NumberOfValues` till antalet element i `rangebegin`‑arrayen, vilket måste vara samma som antalet element i `rangeend`‑arrayen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | Ett `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objekt som kapslar in den globalt unika identifieraren för parameterkategorin. |
| rangebegin | long[] | En array av 64-bitars heltal som specificerar minimivärdena för heltalsintervallen. Heltalen i arrayen måste vara icke‑negativa. De 64-bitars heltalen konverteras till 32-bitars heltal innan de lagras i [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter)‑objektet. |
| rangeend | long[] | En array av 64-bitars heltal som specificerar maxvärdena för heltalsintervallen. Heltalen i arrayen måste vara icke‑negativa. De 64-bitars heltalen konverteras till 32-bitars heltal innan de lagras i [EncoderParameters](../../com.aspose.drawing.imaging/encoderparameters)‑objektet. Ett maxvärde på ett givet index paras ihop med minimivärdet på samma index. |

### EncoderParameter(Encoder encoder, int[] numerator1, int[] denominator1, int[] numerator2, int[] denominator2) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int---int---int---int---}
```
public EncoderParameter(Encoder encoder, int[] numerator1, int[] denominator1, int[] numerator2, int[] denominator2)
```


Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))‑objektet och fyra arrayer av 32-bitars heltal. De fyra arrayerna representerar ett intervall av rationella tal. Ett rationellt intervall är mängden av alla bråktal från ett minimalt bråkvärde till ett maximalt bråkvärde. Sätter egenskapen `P:EncoderParameter.ValueType` till `EncoderParameterValueType.ValueTypeRationalRange` och sätter egenskapen `P:EncoderParameter.NumberOfValues` till antalet element i `numerator1`‑arrayen, vilket måste vara samma som antalet element i de andra tre arrayerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | Ett `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objekt som kapslar in den globalt unika identifieraren för parameterkategorin. |
| numerator1 | int[] | En array av 32-bitars heltal som specificerar täljarna för minimivärdena i intervallen. Heltalen i arrayen måste vara icke‑negativa. |
| denominator1 | int[] | En array av 32-bitars heltal som specificerar nämnarna för minimivärdena i intervallen. Heltalen i arrayen måste vara icke‑negativa. |
| numerator2 | int[] | En array av 32-bitars heltal som specificerar täljarna för maxvärdena i intervallen. Heltalen i arrayen måste vara icke‑negativa. |
| denominator2 | int[] | En array av 32-bitars heltal som specificerar nämnarna för maxvärdena i intervallen. Heltalen i arrayen måste vara icke‑negativa. |

### EncoderParameter(Encoder encoder, int numberOfValues, int type, int value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-int-}
```
public EncoderParameter(Encoder encoder, int numberOfValues, int type, int value)
```


Initierar en ny instans av klassen [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) med det angivna `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objektet och tre heltal som specificerar antalet värden, datatypen för värdena och en pekare till värdena som lagras i objektet [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | Ett `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))-objekt som kapslar in den globalt unika identifieraren för parameterkategorin. |
| numberOfValues | int | Ett heltal som specificerar antalet värden som lagras i [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter)‑objektet. Egenskapen `P:EncoderParameter.NumberOfValues` sätts till detta värde. |
| type | int | En medlem av uppräkningen `EncoderParameterValueType` som specificerar datatypen för värdena som lagras i [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter)‑objektet. Typ‑ och `P:EncoderParameter.ValueType`‑egenskaperna sätts till detta värde. |
| value | int | En pekare till en array av värden av den typ som anges av parametern `type`. |

### getEncoder() {#getEncoder--}
```
public Encoder getEncoder()
```


Hämtar eller anger `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))‑objektet som är associerat med detta [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter)‑objekt. `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))‑objektet kapslar in den globalt unika identifieraren (GUID) som specificerar kategorin (till exempel `Encoder.Quality`, `Encoder.ColorDepth` eller `Encoder.Compression`) för parametern som lagras i detta [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter)‑objekt.

**Returns:**
[Encoder](../../com.aspose.drawing.imaging/encoder)
### setEncoder(Encoder value) {#setEncoder-com.aspose.drawing.imaging.Encoder-}
```
public void setEncoder(Encoder value)
```


Hämtar eller anger `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))‑objektet som är associerat med detta [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter)‑objekt. `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-))‑objektet kapslar in den globalt unika identifieraren (GUID) som specificerar kategorin (till exempel `Encoder.Quality`, `Encoder.ColorDepth` eller `Encoder.Compression`) för parametern som lagras i detta [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter)‑objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Encoder](../../com.aspose.drawing.imaging/encoder) |  |

### getNumberOfValues() {#getNumberOfValues--}
```
public int getNumberOfValues()
```


Hämtar antalet element i arrayen av värden som lagras i detta [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter)-objekt.

**Returns:**
int
### dispose() {#dispose--}
```
public void dispose()
```


Frigör alla resurser som används av detta [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter)-objekt.

