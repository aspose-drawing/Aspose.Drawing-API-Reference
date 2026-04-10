---
title: BitmapData
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يحدد سمات صورة نقطية.
type: docs
weight: 10
url: /ar/java/com.aspose.drawing.imaging/bitmapdata/
---
**Inheritance:**
java.lang.Object
```
public final class BitmapData
```

يحدد سمات صورة bitmap. الفئة [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) تُستخدم بواسطة الطريقتين `E:Bitmap.LockBits` و `M:Bitmap.UnlockBits(BitmapData)` في فئة [Bitmap](../../com.aspose.drawing/bitmap). غير قابلة للوراثة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [BitmapData()](#BitmapData--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getWidth()](#getWidth--) | يحصل على عرض البكسل لكائن [Bitmap](../../com.aspose.drawing/bitmap). |
| [setWidth(int value)](#setWidth-int-) | يضبط عرض البكسل لكائن [Bitmap](../../com.aspose.drawing/bitmap). |
| [getHeight()](#getHeight--) | يحصل على ارتفاع البكسل لكائن [Bitmap](../../com.aspose.drawing/bitmap). |
| [setHeight(int value)](#setHeight-int-) | يضبط ارتفاع البكسل لكائن [Bitmap](../../com.aspose.drawing/bitmap). |
| [getStride()](#getStride--) | يحصل على عرض الخطوة (المعروف أيضًا باسم عرض الفحص) لكائن [Bitmap](../../com.aspose.drawing/bitmap). |
| [setStride(int value)](#setStride-int-) | يضبط عرض الخطوة (المعروف أيضًا باسم عرض الفحص) لكائن [Bitmap](../../com.aspose.drawing/bitmap). |
| [getPixelFormat()](#getPixelFormat--) | يحصل على تنسيق معلومات البكسل في كائن [Bitmap](../../com.aspose.drawing/bitmap) الذي أرجع هذا الكائن [BitmapData](../../com.aspose.drawing.imaging/bitmapdata). |
| [setPixelFormat(int value)](#setPixelFormat-int-) | يضبط تنسيق معلومات البكسل في كائن [Bitmap](../../com.aspose.drawing/bitmap) الذي أرجع هذا الكائن [BitmapData](../../com.aspose.drawing.imaging/bitmapdata). |
| [getScan0()](#getScan0--) | يحصل على عنوان أول بيانات البكسل في الـ bitmap. |
| [setScan0(int[] value)](#setScan0-int---) | يضبط عنوان أول بيانات البكسل في الـ bitmap. |
### BitmapData() {#BitmapData--}
```
public BitmapData()
```


### getWidth() {#getWidth--}
```
public int getWidth()
```


يحصل على عرض البكسل لكائن [Bitmap](../../com.aspose.drawing/bitmap). يمكن أيضًا اعتبار ذلك عدد البكسلات في سطر فحص واحد.

**Returns:**
int - العرض بالبكسل لكائن [Bitmap](../../com.aspose.drawing/bitmap).
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


يضبط العرض بالبكسل لكائن [Bitmap](../../com.aspose.drawing/bitmap). يمكن التفكير في ذلك أيضًا على أنه عدد البكسلات في سطر مسح واحد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | العرض بالبكسل لكائن [Bitmap](../../com.aspose.drawing/bitmap). |

### getHeight() {#getHeight--}
```
public int getHeight()
```


يحصل على الارتفاع بالبكسل لكائن [Bitmap](../../com.aspose.drawing/bitmap). يُشار إليه أحيانًا أيضًا على أنه عدد خطوط المسح.

**Returns:**
int - الارتفاع بالبكسل لكائن [Bitmap](../../com.aspose.drawing/bitmap).
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


يضبط الارتفاع بالبكسل لكائن [Bitmap](../../com.aspose.drawing/bitmap). يُشار إليه أحيانًا أيضًا على أنه عدد خطوط المسح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | الارتفاع بالبكسل لكائن [Bitmap](../../com.aspose.drawing/bitmap). |

### getStride() {#getStride--}
```
public int getStride()
```


يحصل على عرض الخطوة (المعروف أيضًا باسم عرض الفحص) لكائن [Bitmap](../../com.aspose.drawing/bitmap).

**Returns:**
int - عرض الخطوة (stride) بالبايتات لكائن [Bitmap](../../com.aspose.drawing/bitmap).
### setStride(int value) {#setStride-int-}
```
public void setStride(int value)
```


يضبط عرض الخطوة (المعروف أيضًا باسم عرض الفحص) لكائن [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | عرض الخطوة (المعروف أيضًا باسم عرض المسح) لكائن [Bitmap](../../com.aspose.drawing/bitmap). |

### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


يحصل على تنسيق معلومات البكسل في كائن [Bitmap](../../com.aspose.drawing/bitmap) الذي أرجع هذا الكائن [BitmapData](../../com.aspose.drawing.imaging/bitmapdata).

**Returns:**
int - `PixelFormat`([.getPixelFormat](../../null/\#getPixelFormat)/[.setPixelFormat(int)](../../null/\#setPixelFormat-int-)) الذي يحدد تنسيق معلومات البكسل في كائن [Bitmap](../../com.aspose.drawing/bitmap) المرتبط.
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public void setPixelFormat(int value)
```


يضبط تنسيق معلومات البكسل في كائن [Bitmap](../../com.aspose.drawing/bitmap) الذي أرجع هذا الكائن [BitmapData](../../com.aspose.drawing.imaging/bitmapdata).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | تنسيق معلومات البكسل في كائن [Bitmap](../../com.aspose.drawing/bitmap) الذي أعاد كائن [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) هذا. |

### getScan0() {#getScan0--}
```
public int[] getScan0()
```


يحصل على عنوان أول بيانات بكسل في الصورة النقطية. يمكن التفكير في ذلك أيضًا على أنه أول سطر مسح في الصورة النقطية.

**Returns:**
int[] - عنوان أول بيانات بكسل في الصورة النقطية.
### setScan0(int[] value) {#setScan0-int---}
```
public void setScan0(int[] value)
```


يضبط عنوان أول بيانات بكسل في الصورة النقطية. يمكن التفكير في ذلك أيضًا على أنه أول سطر مسح في الصورة النقطية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int[] | عنوان أول بيانات بكسل في الصورة النقطية. |

