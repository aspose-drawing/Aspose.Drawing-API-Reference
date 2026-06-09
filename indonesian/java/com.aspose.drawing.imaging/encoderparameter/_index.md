---
title: EncoderParameter
second_title: Referensi API Aspose.Drawing for Java
description: Digunakan untuk mengirimkan nilai atau array nilai ke encoder gambar.
type: docs
weight: 20
url: /id/java/com.aspose.drawing.imaging/encoderparameter/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class EncoderParameter implements System.IDisposable
```

Digunakan untuk mengirimkan nilai, atau array nilai, ke encoder gambar.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [EncoderParameter(Encoder encoder, byte value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte-) | Menginisialisasi instance baru dari kelas [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) dengan objek `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) yang ditentukan dan satu bilangan bulat tak bertanda 8-bit. |
| [EncoderParameter(Encoder encoder, byte value, boolean undefined)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte-boolean-) | Menginisialisasi instance baru dari kelas [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) dengan objek `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) yang ditentukan dan satu nilai 8-bit. |
| [EncoderParameter(Encoder encoder, short value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-short-) | Menginisialisasi instance baru dari kelas [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) dengan objek `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) yang ditentukan dan satu bilangan bulat 16-bit. |
| [EncoderParameter(Encoder encoder, long value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-long-) | Menginisialisasi instance baru dari kelas [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) dengan objek `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) yang ditentukan dan satu bilangan bulat 64-bit. |
| [EncoderParameter(Encoder encoder, int numerator, int denominator)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-) | Menginisialisasi instance baru dari kelas [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) dengan objek \{@link \#\#System\} yang ditentukan dan sepasang bilangan bulat 32-bit. |
| [EncoderParameter(Encoder encoder, long rangebegin, long rangeend)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-long-long-) | Menginisialisasi instance baru dari kelas [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) dengan objek `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) yang ditentukan dan sepasang bilangan bulat 64-bit. |
| [EncoderParameter(Encoder encoder, int numerator1, int demoninator1, int numerator2, int demoninator2)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-int-int-) | Menginisialisasi instance baru dari kelas [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) dengan objek `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) yang ditentukan dan empat bilangan bulat 32-bit. |
| [EncoderParameter(Encoder encoder, String value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-java.lang.String-) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and a character string. |
| [EncoderParameter(Encoder encoder, byte[] value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of unsigned 8-bit integers. |
| [EncoderParameter(Encoder encoder, byte[] value, boolean undefined)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte---boolean-) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of bytes. |
| [EncoderParameter(Encoder encoder, short[] value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-short---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of 16-bit integers. |
| [EncoderParameter(Encoder encoder, long[] value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-long---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and an array of 64-bit integers. |
| [EncoderParameter(Encoder encoder, int[] numerator, int[] denominator)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int---int---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and two arrays of 32-bit integers. |
| [EncoderParameter(Encoder encoder, long[] rangebegin, long[] rangeend)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-long---long---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and two arrays of 64-bit integers. |
| [EncoderParameter(Encoder encoder, int[] numerator1, int[] denominator1, int[] numerator2, int[] denominator2)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int---int---int---int---) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and four arrays of 32-bit integers. |
| [EncoderParameter(Encoder encoder, int numberOfValues, int type, int value)](#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-int-) | Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and three integers that specify the number of values, the data type of the values, and a pointer to the values stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |
## Metode

| Metode | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | byte | An 8-bit unsigned integer that specifies the value stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |

### EncoderParameter(Encoder encoder, byte value, boolean undefined) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte-boolean-}
```
public EncoderParameter(Encoder encoder, byte value, boolean undefined)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and one 8-bit value. Sets the `EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeUndefined` or `EncoderParameterValueType.ValueTypeByte`, and sets the `EncoderParameter.NumberOfValues` property to 1.

**Parameters:**
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | short | A 16-bit integer that specifies the value stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. Must be nonnegative. |

### EncoderParameter(Encoder encoder, long value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-long-}
```
public EncoderParameter(Encoder encoder, long value)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and one 64-bit integer. Sets the `EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeLong` (32 bits), and sets the `EncoderParameter.NumberOfValues` property to 1.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | long | A 64-bit integer that specifies the value stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. Must be nonnegative. This parameter is converted to a 32-bit integer before it is stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object. |

### EncoderParameter(Encoder encoder, int numerator, int denominator) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-}
```
public EncoderParameter(Encoder encoder, int numerator, int denominator)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified \{@link \#\#System\} object and a pair of 32-bit integers. The pair of integers represents a fraction, the first integer being the numerator, and the second integer being the denominator. Sets the `EncoderParameter.ValueType` property to `EncoderParameterValueType.ValueTypeRational`, and sets the `EncoderParameter.NumberOfValues` property to 1.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| numerator | int | Integer 32-bit yang mewakili pembilang sebuah pecahan. Harus tidak negatif. |
| penyebut | int | Integer 32-bit yang mewakili penyebut sebuah pecahan. Harus tidak negatif. |

### EncoderParameter(Encoder encoder, long rangebegin, long rangeend) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-long-long-}
```
public EncoderParameter(Encoder encoder, long rangebegin, long rangeend)
```


Menginisialisasi instance baru dari kelas [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) dengan objek `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) yang ditentukan dan sepasang integer 64-bit. Sepasang integer tersebut mewakili rentang integer, integer pertama adalah angka terkecil dalam rentang, dan integer kedua adalah angka terbesar dalam rentang. Mengatur properti `EncoderParameter.ValueType` menjadi `EncoderParameterValueType.ValueTypeLongRange`, dan mengatur properti `P:EncoderParameter.NumberOfValues` menjadi 1.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| rangebegin | long | Integer 64-bit yang mewakili angka terkecil dalam rentang integer. Harus tidak negatif. Parameter ini dikonversi menjadi integer 32-bit sebelum disimpan dalam objek [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). |
| rangeend | long | Integer 64-bit yang mewakili angka terbesar dalam rentang integer. Harus tidak negatif. Parameter ini dikonversi menjadi integer 32-bit sebelum disimpan dalam objek [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). |

### EncoderParameter(Encoder encoder, int numerator1, int demoninator1, int numerator2, int demoninator2) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-int-int-}
```
public EncoderParameter(Encoder encoder, int numerator1, int demoninator1, int numerator2, int demoninator2)
```


Menginisialisasi instance baru dari kelas [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) dengan objek `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) yang ditentukan dan empat integer 32-bit. Empat integer tersebut mewakili rentang pecahan. Dua integer pertama mewakili pecahan terkecil dalam rentang, dan dua integer berikutnya mewakili pecahan terbesar dalam rentang. Mengatur properti `P:EncoderParameter.ValueType` menjadi `EncoderParameterValueType.ValueTypeRationalRange`, dan mengatur properti `P:EncoderParameter.NumberOfValues` menjadi 1.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| numerator1 | int | Integer 32-bit yang mewakili pembilang pecahan terkecil dalam rentang. Harus tidak negatif. |
| demoninator1 | int | Integer 32-bit yang mewakili penyebut pecahan terkecil dalam rentang. Harus tidak negatif. |
| numerator2 | int | Integer 32-bit yang mewakili pembilang pecahan terbesar dalam rentang. Harus tidak negatif. |
| demoninator2 | int | Integer 32-bit yang mewakili penyebut pecahan terbesar dalam rentang. Harus tidak negatif. |

### EncoderParameter(Encoder encoder, String value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-java.lang.String-}
```
public EncoderParameter(Encoder encoder, String value)
```


Menginisialisasi instance baru dari kelas [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) dengan objek `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) yang ditentukan dan sebuah string karakter. String tersebut dikonversi menjadi string ASCII berakhiran null sebelum disimpan dalam objek [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). Mengatur properti `P:EncoderParameter.ValueType` menjadi `EncoderParameterValueType.ValueTypeAscii`, dan mengatur properti `P:EncoderParameter.NumberOfValues` menjadi panjang string ASCII termasuk terminator NULL.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | java.lang.String | String yang menentukan nilai yang disimpan dalam objek [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). |

### EncoderParameter(Encoder encoder, byte[] value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte---}
```
public EncoderParameter(Encoder encoder, byte[] value)
```


Menginisialisasi instance baru dari kelas [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) dengan objek `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) yang ditentukan dan sebuah array bilangan bulat tak bertanda 8-bit. Mengatur properti `P:EncoderParameter.ValueType` menjadi `EncoderParameterValueType.ValueTypeByte`, dan mengatur properti `P:EncoderParameter.NumberOfValues` menjadi jumlah elemen dalam array.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | byte[] | Array bilangan bulat tak bertanda 8-bit yang menentukan nilai yang disimpan dalam objek [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). |

### EncoderParameter(Encoder encoder, byte[] value, boolean undefined) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-byte---boolean-}
```
public EncoderParameter(Encoder encoder, byte[] value, boolean undefined)
```


Menginisialisasi instance baru dari kelas [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) dengan objek `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) yang ditentukan dan sebuah array byte. Mengatur properti `P:EncoderParameter.ValueType` menjadi `EncoderParameterValueType.ValueTypeUndefined` atau `EncoderParameterValueType.ValueTypeByte`, dan mengatur properti `P:EncoderParameter.NumberOfValues` menjadi jumlah elemen dalam array.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | byte[] | Array byte yang menentukan nilai yang disimpan dalam objek [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). |
| undefined | boolean | Jika true, properti `P:EncoderParameter.ValueType` diatur menjadi `EncoderParameterValueType.ValueTypeUndefined`; jika tidak, properti `P:EncoderParameter.ValueType` diatur menjadi `EncoderParameterValueType.ValueTypeByte`. |

### EncoderParameter(Encoder encoder, short[] value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-short---}
```
public EncoderParameter(Encoder encoder, short[] value)
```


Menginisialisasi instance baru dari kelas [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) dengan objek `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) yang ditentukan dan sebuah array integer 16-bit. Mengatur properti `P:EncoderParameter.ValueType` menjadi `EncoderParameterValueType.ValueTypeShort`, dan mengatur properti `P:EncoderParameter.NumberOfValues` menjadi jumlah elemen dalam array.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | short[] | Array integer 16-bit yang menentukan nilai yang disimpan dalam objek [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter). Integer dalam array harus tidak negatif. |

### EncoderParameter(Encoder encoder, long[] value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-long---}
```
public EncoderParameter(Encoder encoder, long[] value)
```


Menginisialisasi instance baru dari kelas [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) dengan objek `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) yang ditentukan dan sebuah array integer 64-bit. Mengatur properti `P:EncoderParameter.ValueType` menjadi `EncoderParameterValueType.ValueTypeLong` (32-bit), dan mengatur properti `P:EncoderParameter.NumberOfValues` menjadi jumlah elemen dalam array.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| value | long[] | Sebuah array berisi integer 64-bit yang menentukan nilai yang disimpan dalam objek [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) . Integer dalam array harus nonnegatif. Integer 64-bit dikonversi menjadi integer 32-bit sebelum disimpan dalam objek [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) . |

### EncoderParameter(Encoder encoder, int[] numerator, int[] denominator) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int---int---}
```
public EncoderParameter(Encoder encoder, int[] numerator, int[] denominator)
```


Menginisialisasi instance baru dari kelas [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) dengan objek `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) yang ditentukan dan dua array integer 32-bit. Kedua array mewakili array pecahan. Mengatur properti `P:EncoderParameter.ValueType` menjadi `EncoderParameterValueType.ValueTypeRational`, dan mengatur properti `P:EncoderParameter.NumberOfValues` menjadi jumlah elemen dalam array `numerator`, yang harus sama dengan jumlah elemen dalam array `denominator`.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| numerator | int[] | Sebuah array integer 32-bit yang menentukan pembilang pecahan. Integer dalam array harus nonnegatif. |
| penyebut | int[] | Sebuah array integer 32-bit yang menentukan penyebut pecahan. Integer dalam array harus nonnegatif. Penyebut pada indeks tertentu dipasangkan dengan pembilang pada indeks yang sama. |

### EncoderParameter(Encoder encoder, long[] rangebegin, long[] rangeend) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-long---long---}
```
public EncoderParameter(Encoder encoder, long[] rangebegin, long[] rangeend)
```


Menginisialisasi instance baru dari kelas [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) dengan objek `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) yang ditentukan dan dua array integer 64-bit. Kedua array mewakili rentang integer. Mengatur properti `P:EncoderParameter.ValueType` menjadi `EncoderParameterValueType.ValueTypeLongRange`, dan mengatur properti `P:EncoderParameter.NumberOfValues` menjadi jumlah elemen dalam array `rangebegin`, yang harus sama dengan jumlah elemen dalam array `rangeend`.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| rangebegin | long[] | Sebuah array integer 64-bit yang menentukan nilai minimum untuk rentang integer. Integer dalam array harus nonnegatif. Integer 64-bit dikonversi menjadi integer 32-bit sebelum disimpan dalam objek [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) . |
| rangeend | long[] | Sebuah array integer 64-bit yang menentukan nilai maksimum untuk rentang integer. Integer dalam array harus nonnegatif. Integer 64-bit dikonversi menjadi integer 32-bit sebelum disimpan dalam objek [EncoderParameters](../../com.aspose.drawing.imaging/encoderparameters) . Nilai maksimum pada indeks tertentu dipasangkan dengan nilai minimum pada indeks yang sama. |

### EncoderParameter(Encoder encoder, int[] numerator1, int[] denominator1, int[] numerator2, int[] denominator2) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int---int---int---int---}
```
public EncoderParameter(Encoder encoder, int[] numerator1, int[] denominator1, int[] numerator2, int[] denominator2)
```


Menginisialisasi instance baru dari kelas [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) dengan objek `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) yang ditentukan dan empat array integer 32-bit. Keempat array mewakili rentang rasional. Rentang rasional adalah kumpulan semua pecahan dari nilai pecahan minimum hingga nilai pecahan maksimum. Mengatur properti `P:EncoderParameter.ValueType` menjadi `EncoderParameterValueType.ValueTypeRationalRange`, dan mengatur properti `P:EncoderParameter.NumberOfValues` menjadi jumlah elemen dalam array `numerator1`, yang harus sama dengan jumlah elemen dalam tiga array lainnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| numerator1 | int[] | Sebuah array integer 32-bit yang menentukan pembilang nilai minimum untuk rentang. Integer dalam array harus nonnegatif. |
| denominator1 | int[] | Sebuah array integer 32-bit yang menentukan penyebut nilai minimum untuk rentang. Integer dalam array harus nonnegatif. |
| numerator2 | int[] | Sebuah array integer 32-bit yang menentukan pembilang nilai maksimum untuk rentang. Integer dalam array harus nonnegatif. |
| denominator2 | int[] | Sebuah array integer 32-bit yang menentukan penyebut nilai maksimum untuk rentang. Integer dalam array harus nonnegatif. |

### EncoderParameter(Encoder encoder, int numberOfValues, int type, int value) {#EncoderParameter-com.aspose.drawing.imaging.Encoder-int-int-int-}
```
public EncoderParameter(Encoder encoder, int numberOfValues, int type, int value)
```


Initializes a new instance of the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) class with the specified `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object and three integers that specify the number of values, the data type of the values, and a pointer to the values stored in the [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) object.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| encoder | [Encoder](../../com.aspose.drawing.imaging/encoder) | An `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) object that encapsulates the globally unique identifier of the parameter category. |
| numberOfValues | int | Sebuah integer yang menentukan jumlah nilai yang disimpan dalam objek [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) . Properti `P:EncoderParameter.NumberOfValues` diatur ke nilai ini. |
| type | int | Anggota enumerasi `EncoderParameterValueType` yang menentukan tipe data nilai yang disimpan dalam objek [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) . Properti Type dan `P:EncoderParameter.ValueType` diatur ke nilai ini. |
| value | int | Pointer ke sebuah array nilai dengan tipe yang ditentukan oleh parameter `type`. |

### getEncoder() {#getEncoder--}
```
public Encoder getEncoder()
```


Mendapatkan atau mengatur objek `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) yang terkait dengan objek [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) ini. Objek `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) menyimpan identifier unik global (GUID) yang menentukan kategori (misalnya `Encoder.Quality`, `Encoder.ColorDepth`, atau `Encoder.Compression`) dari parameter yang disimpan dalam objek [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) ini.

**Returns:**
[Encoder](../../com.aspose.drawing.imaging/encoder)
### setEncoder(Encoder value) {#setEncoder-com.aspose.drawing.imaging.Encoder-}
```
public void setEncoder(Encoder value)
```


Mendapatkan atau mengatur objek `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) yang terkait dengan objek [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) ini. Objek `Encoder`([.getEncoder](../../null/\#getEncoder)/[.setEncoder(Encoder)](../../null/\#setEncoder-Encoder-)) menyimpan identifier unik global (GUID) yang menentukan kategori (misalnya `Encoder.Quality`, `Encoder.ColorDepth`, atau `Encoder.Compression`) dari parameter yang disimpan dalam objek [EncoderParameter](../../com.aspose.drawing.imaging/encoderparameter) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
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

