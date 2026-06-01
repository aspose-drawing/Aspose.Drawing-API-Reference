---
title: BitmapData
second_title: Справочник API Aspose.Drawing для Java
description: Указывает атрибуты растрового изображения.
type: docs
weight: 10
url: /ru/java/com.aspose.drawing.imaging/bitmapdata/
---
**Inheritance:**
java.lang.Object
```
public final class BitmapData
```

Указывает атрибуты растрового изображения. Класс [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) используется методами `E:Bitmap.LockBits` и `M:Bitmap.UnlockBits(BitmapData)` класса [Bitmap](../../com.aspose.drawing/bitmap). Не наследуемый.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BitmapData()](#BitmapData--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getWidth()](#getWidth--) | Получает ширину в пикселях объекта [Bitmap](../../com.aspose.drawing/bitmap). |
| [setWidth(int value)](#setWidth-int-) | Задает ширину в пикселях объекта [Bitmap](../../com.aspose.drawing/bitmap). |
| [getHeight()](#getHeight--) | Получает высоту в пикселях объекта [Bitmap](../../com.aspose.drawing/bitmap). |
| [setHeight(int value)](#setHeight-int-) | Задает высоту в пикселях объекта [Bitmap](../../com.aspose.drawing/bitmap). |
| [getStride()](#getStride--) | Получает ширину шага (также называемую шириной сканирования) объекта [Bitmap](../../com.aspose.drawing/bitmap). |
| [setStride(int value)](#setStride-int-) | Задает ширину шага (также называемую шириной сканирования) объекта [Bitmap](../../com.aspose.drawing/bitmap). |
| [getPixelFormat()](#getPixelFormat--) | Получает формат пиксельной информации в объекте [Bitmap](../../com.aspose.drawing/bitmap), который вернул этот объект [BitmapData](../../com.aspose.drawing.imaging/bitmapdata). |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Задает формат пиксельной информации в объекте [Bitmap](../../com.aspose.drawing/bitmap), который вернул этот объект [BitmapData](../../com.aspose.drawing.imaging/bitmapdata). |
| [getScan0()](#getScan0--) | Получает адрес первых данных пикселя в растровом изображении. |
| [setScan0(int[] value)](#setScan0-int---) | Задает адрес первых данных пикселя в растровом изображении. |
### BitmapData() {#BitmapData--}
```
public BitmapData()
```


### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает ширину в пикселях объекта [Bitmap](../../com.aspose.drawing/bitmap). Это также можно рассматривать как количество пикселей в одной строке сканирования.

**Returns:**
int - Ширина в пикселях объекта [Bitmap](../../com.aspose.drawing/bitmap).
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Устанавливает ширину в пикселях объекта [Bitmap](../../com.aspose.drawing/bitmap). Это также можно рассматривать как количество пикселей в одной строке сканирования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | ширина в пикселях объекта [Bitmap](../../com.aspose.drawing/bitmap). |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Получает высоту в пикселях объекта [Bitmap](../../com.aspose.drawing/bitmap). Также иногда называется количеством строк сканирования.

**Returns:**
int - Высота в пикселях объекта [Bitmap](../../com.aspose.drawing/bitmap).
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Устанавливает высоту в пикселях объекта [Bitmap](../../com.aspose.drawing/bitmap). Также иногда называется количеством строк сканирования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | высота в пикселях объекта [Bitmap](../../com.aspose.drawing/bitmap). |

### getStride() {#getStride--}
```
public int getStride()
```


Получает ширину шага (также называемую шириной сканирования) объекта [Bitmap](../../com.aspose.drawing/bitmap).

**Returns:**
int - Ширина шага, в байтах, объекта [Bitmap](../../com.aspose.drawing/bitmap).
### setStride(int value) {#setStride-int-}
```
public void setStride(int value)
```


Задает ширину шага (также называемую шириной сканирования) объекта [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | ширина шага (также называется шириной сканирования) объекта [Bitmap](../../com.aspose.drawing/bitmap). |

### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Получает формат пиксельной информации в объекте [Bitmap](../../com.aspose.drawing/bitmap), который вернул этот объект [BitmapData](../../com.aspose.drawing.imaging/bitmapdata).

**Returns:**
int - `PixelFormat`([.getPixelFormat](../../null/\#getPixelFormat)/[.setPixelFormat(int)](../../null/\#setPixelFormat-int-)), который задает формат информации о пикселях в связанном объекте [Bitmap](../../com.aspose.drawing/bitmap).
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public void setPixelFormat(int value)
```


Задает формат пиксельной информации в объекте [Bitmap](../../com.aspose.drawing/bitmap), который вернул этот объект [BitmapData](../../com.aspose.drawing.imaging/bitmapdata).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | формат информации о пикселях в объекте [Bitmap](../../com.aspose.drawing/bitmap), который вернул этот объект [BitmapData](../../com.aspose.drawing.imaging/bitmapdata). |

### getScan0() {#getScan0--}
```
public int[] getScan0()
```


Получает адрес первых данных пикселя в битмапе. Это также можно рассматривать как первую строку сканирования в битмапе.

**Returns:**
int[] - Адрес первых данных пикселя в битмапе.
### setScan0(int[] value) {#setScan0-int---}
```
public void setScan0(int[] value)
```


Устанавливает адрес первых данных пикселя в битмапе. Это также можно рассматривать как первую строку сканирования в битмапе.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] | адрес первых данных пикселя в битмапе. |

