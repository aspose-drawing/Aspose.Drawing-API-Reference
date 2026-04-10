---
title: صورة نقطية
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يحتوي على صورة نقطية تتكون من بيانات البكسل لصورة رسومية وخصائصها.
type: docs
weight: 10
url: /ar/java/com.aspose.drawing/bitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public class Bitmap extends Image
```

يحتوي على صورة نقطية، التي تتكون من بيانات البكسل لصورة رسومية وخصائصها. الـ[Bitmap](../../com.aspose.drawing/bitmap) هو كائن يُستخدم للعمل مع الصور المعرفة ببيانات البكسل.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Bitmap(int width, int height)](#Bitmap-int-int-) | ينشئ نسخة جديدة من فئة الـ[Bitmap](../../com.aspose.drawing/bitmap) بالحجم المحدد. |
| [Bitmap(String filename)](#Bitmap-java.lang.String-) | ينشئ نسخة جديدة من فئة الـ[Bitmap](../../com.aspose.drawing/bitmap) من الملف المحدد. |
| [Bitmap(String filename, boolean useIcm)](#Bitmap-java.lang.String-boolean-) | ينشئ نسخة جديدة من فئة الـ[Bitmap](../../com.aspose.drawing/bitmap) من الملف المحدد. |
| [Bitmap(InputStream stream)](#Bitmap-java.io.InputStream-) | ينشئ نسخة جديدة من فئة الـ[Bitmap](../../com.aspose.drawing/bitmap) من تدفق البيانات المحدد. |
| [Bitmap(InputStream stream, boolean useIcm)](#Bitmap-java.io.InputStream-boolean-) | ينشئ نسخة جديدة من فئة الـ[Bitmap](../../com.aspose.drawing/bitmap) من تدفق البيانات المحدد. |
| [Bitmap(int width, int height, int format)](#Bitmap-int-int-int-) | ينشئ نسخة جديدة من فئة الـ[Bitmap](../../com.aspose.drawing/bitmap) بالحجم والتنسيق المحددين. |
| [Bitmap(int width, int height, int stride, int format, int[] data)](#Bitmap-int-int-int-int-int---) | ينشئ نسخة جديدة من فئة الـ[Bitmap](../../com.aspose.drawing/bitmap) بالحجم وبيانات البكسل المحددة. |
| [Bitmap(Image original)](#Bitmap-com.aspose.drawing.Image-) | ينشئ نسخة جديدة من فئة الـ[Bitmap](../../com.aspose.drawing/bitmap) من الصورة الموجودة المحددة. |
| [Bitmap(Image original, Size newSize)](#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-) | ينشئ نسخة جديدة من فئة الـ[Bitmap](../../com.aspose.drawing/bitmap) من الصورة الموجودة المحددة، مُقاسة إلى الحجم المحدد. |
| [Bitmap(Image original, int width, int height)](#Bitmap-com.aspose.drawing.Image-int-int-) | ينشئ نسخة جديدة من فئة الـ[Bitmap](../../com.aspose.drawing/bitmap) من الصورة الموجودة المحددة، مُقاسة إلى الحجم المحدد. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getWidth()](#getWidth--) | يحصل على عرض هذه الـBitmap بوحدة البكسل. |
| [getHeight()](#getHeight--) | يحصل على ارتفاع هذه الـBitmap بوحدة البكسل. |
| [getRawFormat()](#getRawFormat--) | يعيد تنسيق الملف لهذا الـ [Image](../../com.aspose.drawing/image). |
| [getPixelFormat()](#getPixelFormat--) | يعيد تنسيق البكسل لهذا الـ [Image](../../com.aspose.drawing/image). |
| [getPalette()](#getPalette--) | يحصل أو يضبط لوحة الألوان المستخدمة لهذا الـ [Image](../../com.aspose.drawing/image). |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | يحصل أو يضبط لوحة الألوان المستخدمة لهذا الـ [Image](../../com.aspose.drawing/image). |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | يعيد مصفوفة من GUIDs التي تمثل أبعاد الإطارات داخل هذا الـ [Image](../../com.aspose.drawing/image). |
| [getPropertyIdList()](#getPropertyIdList--) | يعيد معرفات عناصر الخاصية المخزنة في هذا الـ [Image](../../com.aspose.drawing/image). |
| [getPropertyItems()](#getPropertyItems--) | يعيد جميع عناصر الخاصية (قطع من البيانات الوصفية) المخزنة في هذا الـ [Image](../../com.aspose.drawing/image). |
| [deepClone(Rectangle rect, int format)](#deepClone-com.aspose.drawing.Rectangle-int-) | ينشئ نسخة من الجزء من هذه الـ[Bitmap](../../com.aspose.drawing/bitmap) المحدد بواسطة بنية الـ[Rectangle](../../com.aspose.drawing/rectangle) وباستخدام تعداد `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) المحدد. |
| [deepClone(RectangleF rect, int format)](#deepClone-com.aspose.drawing.RectangleF-int-) | ينشئ نسخة من الجزء من هذه الـ[Bitmap](../../com.aspose.drawing/bitmap) المحدد باستخدام تعداد الـ[PixelFormat](../../com.aspose.drawing.imaging/pixelformat) المحدد. |
| [setResolution(float xDpi, float yDpi)](#setResolution-float-float-) | يضبط الدقة لهذه الـ[Bitmap](../../com.aspose.drawing/bitmap). |
| [lockBits(Rectangle rect, int flags, int format)](#lockBits-com.aspose.drawing.Rectangle-int-int-) | يقفل [Bitmap](../../com.aspose.drawing/bitmap) في ذاكرة النظام. |
| [unlockBits(BitmapData bitmapData)](#unlockBits-com.aspose.drawing.imaging.BitmapData-) | يفك قفل هذا [Bitmap](../../com.aspose.drawing/bitmap) من ذاكرة النظام. |
| [getPixel(int x, int y)](#getPixel-int-int-) | يحصل على لون البكسل المحدد في هذا [Bitmap](../../com.aspose.drawing/bitmap). |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.drawing.Color-) | يضبط لون البكسل المحدد في هذا [Bitmap](../../com.aspose.drawing/bitmap). |
| [readArgb32Pixels(int[] pixels)](#readArgb32Pixels-int---) | يقرأ بكسلات bitmap بتنسيق ARGB32 إلى المصفوفة المعطاة. |
| [writeArgb32Pixels(int[] pixels)](#writeArgb32Pixels-int---) | يكتب البكسلات إلى الـ bitmap. |
| [makeTransparent()](#makeTransparent--) | يجعل اللون المحدد شفافًا لهذا [Bitmap](../../com.aspose.drawing/bitmap). |
| [makeTransparent(Color transparentColor)](#makeTransparent-com.aspose.drawing.Color-) | يجعل اللون المحدد شفافًا لهذا [Bitmap](../../com.aspose.drawing/bitmap). |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | تقوم هذه الطريقة بتدوير، أو قلب، أو تدوير وقلب الـ [Image](../../com.aspose.drawing/image). |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | يعيد عنصر الخاصية المحدد من هذا الـ [Image](../../com.aspose.drawing/image). |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | يزيل عنصر الخاصية المحدد من هذا الـ [Image](../../com.aspose.drawing/image). |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | يخزن عنصر خاصية (قطعة من البيانات الوصفية) في هذا الـ [Image](../../com.aspose.drawing/image). |
### Bitmap(int width, int height) {#Bitmap-int-int-}
```
public Bitmap(int width, int height)
```


ينشئ نسخة جديدة من فئة الـ[Bitmap](../../com.aspose.drawing/bitmap) بالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int | العرض، بوحدات البكسل، للـ Bitmap الجديد. |
|  | الارتفاع | int | الارتفاع، بوحدات البكسل، للـ Bitmap الجديد. |

--------------------

الصيغة الداخلية الوحيدة المدعومة للـ bitmap في الوقت الحالي تعادل `PixelFormat.Format32bppPArgb`. |

### Bitmap(String filename) {#Bitmap-java.lang.String-}
```
public Bitmap(String filename)
```


ينشئ نسخة جديدة من فئة الـ[Bitmap](../../com.aspose.drawing/bitmap) من الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| اسم الملف | java.lang.String | اسم ملف الـ bitmap. |

### Bitmap(String filename, boolean useIcm) {#Bitmap-java.lang.String-boolean-}
```
public Bitmap(String filename, boolean useIcm)
```


ينشئ نسخة جديدة من فئة الـ[Bitmap](../../com.aspose.drawing/bitmap) من الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| اسم الملف | java.lang.String | اسم ملف الـ bitmap. |
| useIcm | boolean | true لاستخدام تصحيح اللون لهذا [Bitmap](../../com.aspose.drawing/bitmap)؛ وإلا false. |

### Bitmap(InputStream stream) {#Bitmap-java.io.InputStream-}
```
public Bitmap(InputStream stream)
```


ينشئ نسخة جديدة من فئة الـ[Bitmap](../../com.aspose.drawing/bitmap) من تدفق البيانات المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | java.io.InputStream | دفق البيانات المستخدم لتحميل الصورة. |

### Bitmap(InputStream stream, boolean useIcm) {#Bitmap-java.io.InputStream-boolean-}
```
public Bitmap(InputStream stream, boolean useIcm)
```


ينشئ نسخة جديدة من فئة الـ[Bitmap](../../com.aspose.drawing/bitmap) من تدفق البيانات المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | java.io.InputStream | دفق البيانات المستخدم لتحميل الصورة. |
| useIcm | boolean | `true` لاستخدام تصحيح اللون لهذا [Bitmap](../../com.aspose.drawing/bitmap)؛ وإلا `false`. |

### Bitmap(int width, int height, int format) {#Bitmap-int-int-int-}
```
public Bitmap(int width, int height, int format)
```


ينشئ نسخة جديدة من فئة الـ[Bitmap](../../com.aspose.drawing/bitmap) بالحجم والتنسيق المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| width | int | العرض، بوحدات البكسل، للـ [Bitmap](../../com.aspose.drawing/bitmap) الجديد. |
| height | int | الارتفاع، بوحدات البكسل، للـ [Bitmap](../../com.aspose.drawing/bitmap) الجديد. |
| format | int | تعداد `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) للـ [Bitmap](../../com.aspose.drawing/bitmap) الجديد. |

### Bitmap(int width, int height, int stride, int format, int[] data) {#Bitmap-int-int-int-int-int---}
```
public Bitmap(int width, int height, int stride, int format, int[] data)
```


ينشئ نسخة جديدة من فئة الـ[Bitmap](../../com.aspose.drawing/bitmap) بالحجم وبيانات البكسل المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| width | int | العرض، بوحدات البكسل، للـ [Bitmap](../../com.aspose.drawing/bitmap) الجديد. |
| height | int | الارتفاع، بوحدات البكسل، للـ [Bitmap](../../com.aspose.drawing/bitmap) الجديد. |
| خطوة | int | الإزاحة بالبايت بين بداية سطر المسح وآخر، يجب أن تكون مضاعفًا للعدد أربعة. |
| format | int | تعداد `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) للـ [Bitmap](../../com.aspose.drawing/bitmap) الجديد. |
| بيانات | int[] | بيانات البكسل. |

### Bitmap(Image original) {#Bitmap-com.aspose.drawing.Image-}
```
public Bitmap(Image original)
```


ينشئ نسخة جديدة من فئة الـ[Bitmap](../../com.aspose.drawing/bitmap) من الصورة الموجودة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | الـ [Image](../../com.aspose.drawing/image) الذي يُنشأ منه الـ [Bitmap](../../com.aspose.drawing/bitmap) الجديد. |

### Bitmap(Image original, Size newSize) {#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-}
```
public Bitmap(Image original, Size newSize)
```


ينشئ نسخة جديدة من فئة الـ[Bitmap](../../com.aspose.drawing/bitmap) من الصورة الموجودة المحددة، مُقاسة إلى الحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | الـ [Image](../../com.aspose.drawing/image) الذي يُنشأ منه الـ [Bitmap](../../com.aspose.drawing/bitmap) الجديد |
| newSize | [Size](../../com.aspose.drawing/size) | البنية `Size`([Image.getSize](../../com.aspose.drawing/image\#getSize)) التي تمثل حجم الـ [Bitmap](../../com.aspose.drawing/bitmap) الجديد. |

### Bitmap(Image original, int width, int height) {#Bitmap-com.aspose.drawing.Image-int-int-}
```
public Bitmap(Image original, int width, int height)
```


ينشئ نسخة جديدة من فئة الـ[Bitmap](../../com.aspose.drawing/bitmap) من الصورة الموجودة المحددة، مُقاسة إلى الحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | الـ [Image](../../com.aspose.drawing/image) الذي يُنشأ منه الـ [Bitmap](../../com.aspose.drawing/bitmap) الجديد. |
| width | int | العرض، بوحدات البكسل، للـ [Bitmap](../../com.aspose.drawing/bitmap) الجديد. |
| height | int | الارتفاع، بوحدات البكسل، للـ [Bitmap](../../com.aspose.drawing/bitmap) الجديد. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


يحصل على عرض هذه الـBitmap بوحدة البكسل.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


يحصل على ارتفاع هذه الـBitmap بوحدة البكسل.

**Returns:**
int
### getRawFormat() {#getRawFormat--}
```
public ImageFormat getRawFormat()
```


يعيد تنسيق الملف لهذا الـ [Image](../../com.aspose.drawing/image).

**Returns:**
[ImageFormat](../../com.aspose.drawing.imaging/imageformat) - The [ImageFormat](../../com.aspose.drawing.imaging/imageformat) that represents the file format of this [Image](../../com.aspose.drawing/image).
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


يعيد تنسيق البكسل لهذا الـ [Image](../../com.aspose.drawing/image).

**Returns:**
int - `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) الذي يمثل تنسيق البكسل لهذا الـ [Image](../../com.aspose.drawing/image).
### getPalette() {#getPalette--}
```
public ColorPalette getPalette()
```


يحصل أو يضبط لوحة الألوان المستخدمة لهذا الـ [Image](../../com.aspose.drawing/image).

**Returns:**
[ColorPalette](../../com.aspose.drawing.imaging/colorpalette) - A [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) that represents the color palette used for this [Image](../../com.aspose.drawing/image).
### setPalette(ColorPalette value) {#setPalette-com.aspose.drawing.imaging.ColorPalette-}
```
public void setPalette(ColorPalette value)
```


يحصل أو يضبط لوحة الألوان المستخدمة لهذا الـ [Image](../../com.aspose.drawing/image).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) |  |

### getFrameDimensionsList() {#getFrameDimensionsList--}
```
public UUID[] getFrameDimensionsList()
```


يعيد مصفوفة من GUIDs التي تمثل أبعاد الإطارات داخل هذا الـ [Image](../../com.aspose.drawing/image).

**Returns:**
java.util.UUID[] - مصفوفة من GUIDs التي تحدد أبعاد الإطارات داخل هذا الـ [Image](../../com.aspose.drawing/image) من الأكثر أهمية إلى الأقل.
### getPropertyIdList() {#getPropertyIdList--}
```
public int[] getPropertyIdList()
```


يعيد معرفات عناصر الخاصية المخزنة في هذا الـ [Image](../../com.aspose.drawing/image).

**Returns:**
int[] - مصفوفة من معرفات الخصائص، واحدة لكل عنصر خاصية مخزن في هذه الصورة.
### getPropertyItems() {#getPropertyItems--}
```
public PropertyItem[] getPropertyItems()
```


يعيد جميع عناصر الخاصية (قطع من البيانات الوصفية) المخزنة في هذا الـ [Image](../../com.aspose.drawing/image).

**Returns:**
com.aspose.drawing.imaging.PropertyItem[] - مصفوفة من كائنات [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) ، واحدة لكل عنصر خاصية مخزن في الصورة.
### deepClone(Rectangle rect, int format) {#deepClone-com.aspose.drawing.Rectangle-int-}
```
public final Bitmap deepClone(Rectangle rect, int format)
```


ينشئ نسخة من الجزء من هذه الـ[Bitmap](../../com.aspose.drawing/bitmap) المحدد بواسطة بنية الـ[Rectangle](../../com.aspose.drawing/rectangle) وباستخدام تعداد `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | يحدد الجزء من هذا [Bitmap](../../com.aspose.drawing/bitmap) الذي سيُنسخ. الإحداثيات نسبية لهذا [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | يحدد تعداد `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) للـ [Bitmap](../../com.aspose.drawing/bitmap) الوجهة. |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The new [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### deepClone(RectangleF rect, int format) {#deepClone-com.aspose.drawing.RectangleF-int-}
```
public final Bitmap deepClone(RectangleF rect, int format)
```


ينشئ نسخة من الجزء من هذه الـ[Bitmap](../../com.aspose.drawing/bitmap) المحدد باستخدام تعداد الـ[PixelFormat](../../com.aspose.drawing.imaging/pixelformat) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | يحدد الجزء من هذا [Bitmap](../../com.aspose.drawing/bitmap) الذي سيُنسخ. |
| format | int | يحدد تعداد [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) للـ [Bitmap](../../com.aspose.drawing/bitmap) الوجهة. |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### setResolution(float xDpi, float yDpi) {#setResolution-float-float-}
```
public final void setResolution(float xDpi, float yDpi)
```


يضبط الدقة لهذه الـ[Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| xDpi | float | الدقة الأفقية، بوحدة النقاط لكل بوصة، للـ [Bitmap](../../com.aspose.drawing/bitmap). |
| yDpi | float | الدقة العمودية، بوحدة النقاط لكل بوصة، للـ [Bitmap](../../com.aspose.drawing/bitmap). |

### lockBits(Rectangle rect, int flags, int format) {#lockBits-com.aspose.drawing.Rectangle-int-int-}
```
public final BitmapData lockBits(Rectangle rect, int flags, int format)
```


يقفل [Bitmap](../../com.aspose.drawing/bitmap) في ذاكرة النظام.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | بنية [Rectangle](../../com.aspose.drawing/rectangle) التي تحدد الجزء من الـ [Bitmap](../../com.aspose.drawing/bitmap) لتقفيله. |
| flags | int | تعداد [ImageLockMode](../../com.aspose.drawing.imaging/imagelockmode) الذي يحدد مستوى الوصول (قراءة/كتابة) للـ [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | تعداد `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) الذي يحدد تنسيق البيانات لهذا الـ [Bitmap](../../com.aspose.drawing/bitmap). |

**Returns:**
[BitmapData](../../com.aspose.drawing.imaging/bitmapdata) - A [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) containing information about this lock operation.
### unlockBits(BitmapData bitmapData) {#unlockBits-com.aspose.drawing.imaging.BitmapData-}
```
public final void unlockBits(BitmapData bitmapData)
```


يفك قفل هذا [Bitmap](../../com.aspose.drawing/bitmap) من ذاكرة النظام.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitmapData | [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) | كائن [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) الذي يحدد معلومات حول عملية القفل. |

### getPixel(int x, int y) {#getPixel-int-int-}
```
public final Color getPixel(int x, int y)
```


يحصل على لون البكسل المحدد في هذا [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | int | الإحداثي السيني للبكسل المراد استرجاعه. |
| y | int | الإحداثي الصادي للبكسل المراد استرجاعه. |

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) structure that represents the color of the specified pixel.
### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.drawing.Color-}
```
public final void setPixel(int x, int y, Color color)
```


يضبط لون البكسل المحدد في هذا [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | int | الإحداثي السيني للبكسل المراد تعيينه. |
| y | int | الإحداثي الصادي للبكسل المراد تعيينه. |
| color | [Color](../../com.aspose.drawing/color) | بنية [Color](../../com.aspose.drawing/color) التي تمثل اللون الذي سيُعيّن للبكسل المحدد. |

### readArgb32Pixels(int[] pixels) {#readArgb32Pixels-int---}
```
public final void readArgb32Pixels(int[] pixels)
```


يقرأ بكسلات bitmap بتنسيق ARGB32 إلى المصفوفة المعطاة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بكسلات | int[] | مصفوفة لوضع بكسلات الـ bitmap. يجب أن تكون ذات سعة كافية. |

### writeArgb32Pixels(int[] pixels) {#writeArgb32Pixels-int---}
```
public final void writeArgb32Pixels(int[] pixels)
```


يكتب البكسلات إلى الـ bitmap.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بكسلات | int[] | مصفوفة تحتوي على بكسلات المصدر بصيغة ARGB32. يجب أن يكون طولها كافياً. |

### makeTransparent() {#makeTransparent--}
```
public final void makeTransparent()
```


يجعل اللون المحدد شفافًا لهذا [Bitmap](../../com.aspose.drawing/bitmap).

### makeTransparent(Color transparentColor) {#makeTransparent-com.aspose.drawing.Color-}
```
public final void makeTransparent(Color transparentColor)
```


يجعل اللون المحدد شفافًا لهذا [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| transparentColor | [Color](../../com.aspose.drawing/color) | بنية [Color](../../com.aspose.drawing/color) التي تمثل اللون الذي سيُجعل شفافًا. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


تقوم هذه الطريقة بتدوير، أو قلب، أو تدوير وقلب الـ [Image](../../com.aspose.drawing/image).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateFlipType | int | عضو [RotateFlipType](../../com.aspose.drawing/rotatefliptype) يحدد نوع الدوران والقلب لتطبيقه على الصورة. |

### getPropertyItem(int propid) {#getPropertyItem-int-}
```
public PropertyItem getPropertyItem(int propid)
```


يعيد عنصر الخاصية المحدد من هذا الـ [Image](../../com.aspose.drawing/image).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| propid | int | معرف عنصر الخاصية للحصول عليه. |

**Returns:**
[PropertyItem](../../com.aspose.drawing.imaging/propertyitem) - The [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) this method gets.
### removePropertyItem(int propid) {#removePropertyItem-int-}
```
public void removePropertyItem(int propid)
```


يزيل عنصر الخاصية المحدد من هذا الـ [Image](../../com.aspose.drawing/image).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| propid | int | معرف عنصر الخاصية لإزالته. |

### setPropertyItem(PropertyItem propitem) {#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-}
```
public void setPropertyItem(PropertyItem propitem)
```


يخزن عنصر خاصية (قطعة من البيانات الوصفية) في هذا الـ [Image](../../com.aspose.drawing/image).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| propitem | [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) | عنصر [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) الذي سيتم تخزينه. |

