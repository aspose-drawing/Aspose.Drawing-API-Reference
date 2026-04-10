---
title: ColorMatrix
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يعرف مصفوفة 5 × 5 تحتوي على إحداثيات مساحة RGBA.
type: docs
weight: 14
url: /ar/java/com.aspose.drawing.imaging/colormatrix/
---
**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

يعرّف مصفوفة 5 × 5 تحتوي على إحداثيات مساحة RGBA. عدة طرق في فئة [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) تعدّل ألوان الصورة باستخدام مصفوفة ألوان. لا يمكن وراثة هذه الفئة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | ينشئ مثيلًا جديدًا من فئة [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | ينشئ مثيلًا جديدًا من فئة [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) باستخدام العناصر في المصفوفة المحددة `newColorMatrix`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getMatrix00()](#getMatrix00--) | يحصل على العنصر في الصف 0 (صفر) والعمود 0 من هذه [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix00(float value)](#setMatrix00-float-) | يضبط العنصر في الصف 0 (صفر) والعمود 0 من هذه [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix01()](#getMatrix01--) | يحصل على العنصر في الصف 0 (صفر) والعمود الأول من هذه [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix01(float value)](#setMatrix01-float-) | يضبط العنصر في الصف 0 (صفر) والعمود الأول من هذه [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix02()](#getMatrix02--) | يحصل على العنصر في الصف 0 (صفر) والعمود الثاني من هذه [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix02(float value)](#setMatrix02-float-) | يضبط العنصر في الصف 0 (صفر) والعمود الثاني من هذه [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix03()](#getMatrix03--) | يحصل على العنصر في الصف 0 (صفر) والعمود الثالث من هذه [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix03(float value)](#setMatrix03-float-) | يضبط العنصر في الصف 0 (صفر) والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix04()](#getMatrix04--) | يحصل على العنصر في الصف 0 (صفر) والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix04(float value)](#setMatrix04-float-) | يضبط العنصر في الصف 0 (صفر) والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix10()](#getMatrix10--) | يحصل على العنصر في الصف الأول والعمود 0 (صفر) من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix10(float value)](#setMatrix10-float-) | يضبط العنصر في الصف الأول والعمود 0 (صفر) من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix11()](#getMatrix11--) | يحصل على العنصر في الصف الأول والعمود الأول من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix11(float value)](#setMatrix11-float-) | يضبط العنصر في الصف الأول والعمود الأول من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix12()](#getMatrix12--) | يحصل على العنصر في الصف الأول والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix12(float value)](#setMatrix12-float-) | يضبط العنصر في الصف الأول والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix13()](#getMatrix13--) | يحصل على العنصر في الصف الأول والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix13(float value)](#setMatrix13-float-) | يضبط العنصر في الصف الأول والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix14()](#getMatrix14--) | يحصل على العنصر في الصف الأول والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix14(float value)](#setMatrix14-float-) | يضبط العنصر في الصف الأول والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix20()](#getMatrix20--) | يحصل على العنصر في الصف الثاني والعمود 0 (صفر) من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix20(float value)](#setMatrix20-float-) | يضبط العنصر في الصف الثاني والعمود 0 (صفر) من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix21()](#getMatrix21--) | يحصل على العنصر في الصف الثاني والعمود الأول من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix21(float value)](#setMatrix21-float-) | يضبط العنصر في الصف الثاني والعمود الأول من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix22()](#getMatrix22--) | يحصل على العنصر في الصف الثاني والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix22(float value)](#setMatrix22-float-) | يضبط العنصر في الصف الثاني والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix23()](#getMatrix23--) | يحصل على العنصر في الصف الثاني والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix23(float value)](#setMatrix23-float-) | يضبط العنصر في الصف الثاني والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix24()](#getMatrix24--) | يحصل على العنصر في الصف الثاني والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix24(float value)](#setMatrix24-float-) | يضبط العنصر في الصف الثاني والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix30()](#getMatrix30--) | يحصل على العنصر في الصف الثالث والعمود 0 (صفر) من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix30(float value)](#setMatrix30-float-) | يضبط العنصر في الصف الثالث والعمود 0 (صفر) من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix31()](#getMatrix31--) | يحصل على العنصر في الصف الثالث والعمود الأول من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix31(float value)](#setMatrix31-float-) | يضبط العنصر في الصف الثالث والعمود الأول من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix32()](#getMatrix32--) | يحصل على العنصر في الصف الثالث والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix32(float value)](#setMatrix32-float-) | يضبط العنصر في الصف الثالث والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix33()](#getMatrix33--) | يحصل على العنصر في الصف الثالث والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix33(float value)](#setMatrix33-float-) | يضبط العنصر في الصف الثالث والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix34()](#getMatrix34--) | يحصل على العنصر في الصف الثالث والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix34(float value)](#setMatrix34-float-) | يضبط العنصر في الصف الثالث والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix40()](#getMatrix40--) | يحصل على العنصر في الصف الرابع والعمود 0 (صفر) من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix40(float value)](#setMatrix40-float-) | يضبط العنصر في الصف الرابع والعمود 0 (صفر) من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix41()](#getMatrix41--) | يحصل على العنصر في الصف الرابع والعمود الأول من هذا `.ColorMatrix`. |
| [setMatrix41(float value)](#setMatrix41-float-) | يضبط العنصر في الصف الرابع والعمود الأول من هذا `.ColorMatrix`. |
| [getMatrix42()](#getMatrix42--) | يحصل على العنصر في الصف الرابع والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix42(float value)](#setMatrix42-float-) | يضبط العنصر في الصف الرابع والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix43()](#getMatrix43--) | يحصل على العنصر في الصف الرابع والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix43(float value)](#setMatrix43-float-) | يضبط العنصر في الصف الرابع والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix44()](#getMatrix44--) | يحصل على العنصر في الصف الرابع والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix44(float value)](#setMatrix44-float-) | يضبط العنصر في الصف الرابع والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [get_Item(int row, int column)](#get-Item-int-int-) | يحصل على العنصر في الصف والعمود المحددين في [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | يضبط العنصر في الصف والعمود المحددين في [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


ينشئ مثيلًا جديدًا من فئة [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


ينشئ مثيلًا جديدًا من فئة [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) باستخدام العناصر في المصفوفة المحددة `newColorMatrix`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorMatrix | float[][] | قِيَم العناصر للمصفوفة [ColorMatrix] الجديدة. |

### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


يحصل على العنصر في الصف 0 (صفر) والعمود 0 من هذه [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - العنصر في الصف 0 (صفر) والعمود 0 من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix00(float value) {#setMatrix00-float-}
```
public void setMatrix00(float value)
```


يضبط العنصر في الصف 0 (صفر) والعمود 0 من هذه [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف 0 (صفر) والعمود 0 من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


يحصل على العنصر في الصف 0 (صفر) والعمود الأول من هذه [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - العنصر في الصف 0 (صفر) والعمود الأول من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


يضبط العنصر في الصف 0 (صفر) والعمود الأول من هذه [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف 0 (صفر) والعمود الأول من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


يحصل على العنصر في الصف 0 (صفر) والعمود الثاني من هذه [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - العنصر في الصف 0 (صفر) والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


يضبط العنصر في الصف 0 (صفر) والعمود الثاني من هذه [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف 0 (صفر) والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


يحصل على العنصر في الصف 0 (صفر) والعمود الثالث من هذه [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - العنصر في الصف 0 (صفر) والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


يضبط العنصر في الصف 0 (صفر) والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف 0 (صفر) والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


يحصل على العنصر في الصف 0 (صفر) والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - العنصر في الصف 0 (صفر) والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


يضبط العنصر في الصف 0 (صفر) والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف 0 (صفر) والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


يحصل على العنصر في الصف الأول والعمود 0 (صفر) من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - العنصر في الصف الأول والعمود 0 (صفر) من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


يضبط العنصر في الصف الأول والعمود 0 (صفر) من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف الأول والعمود 0 (صفر) من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


يحصل على العنصر في الصف الأول والعمود الأول من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - العنصر في الصف الأول والعمود الأول من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


يضبط العنصر في الصف الأول والعمود الأول من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف الأول والعمود الأول من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


يحصل على العنصر في الصف الأول والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - العنصر في الصف الأول والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


يضبط العنصر في الصف الأول والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف الأول والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


يحصل على العنصر في الصف الأول والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - العنصر في الصف الأول والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


يضبط العنصر في الصف الأول والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف الأول والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


يحصل على العنصر في الصف الأول والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - العنصر في الصف الأول والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


يضبط العنصر في الصف الأول والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف الأول والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


يحصل على العنصر في الصف الثاني والعمود 0 (صفر) من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - العنصر في الصف الثاني والعمود 0 (صفر) من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


يضبط العنصر في الصف الثاني والعمود 0 (صفر) من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف الثاني والعمود 0 (صفر) من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


يحصل على العنصر في الصف الثاني والعمود الأول من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - العنصر في الصف الثاني والعمود الأول من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


يضبط العنصر في الصف الثاني والعمود الأول من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف الثاني والعمود الأول من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


يحصل على العنصر في الصف الثاني والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - العنصر في الصف الثاني والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


يضبط العنصر في الصف الثاني والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف الثاني والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


يحصل على العنصر في الصف الثاني والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - العنصر في الصف الثاني والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


يضبط العنصر في الصف الثاني والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف الثاني والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


يحصل على العنصر في الصف الثاني والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - العنصر في الصف الثاني والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


يضبط العنصر في الصف الثاني والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف الثاني والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


يحصل على العنصر في الصف الثالث والعمود 0 (صفر) من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - العنصر في الصف الثالث والعمود 0 (صفر) من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


يضبط العنصر في الصف الثالث والعمود 0 (صفر) من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف الثالث والعمود 0 (صفر) من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


يحصل على العنصر في الصف الثالث والعمود الأول من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - العنصر في الصف الثالث والعمود الأول من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


يضبط العنصر في الصف الثالث والعمود الأول من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف الثالث والعمود الأول من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


يحصل على العنصر في الصف الثالث والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - العنصر في الصف الثالث والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


يضبط العنصر في الصف الثالث والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف الثالث والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


يحصل على العنصر في الصف الثالث والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - العنصر في الصف الثالث والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


يضبط العنصر في الصف الثالث والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف الثالث والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


يحصل على العنصر في الصف الثالث والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - العنصر في الصف الثالث والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


يضبط العنصر في الصف الثالث والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف الثالث والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


يحصل على العنصر في الصف الرابع والعمود 0 (صفر) من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - العنصر في الصف الرابع والعمود 0 (صفر) من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


يضبط العنصر في الصف الرابع والعمود 0 (صفر) من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف الرابع والعمود 0 (صفر) من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


يحصل على العنصر في الصف الرابع والعمود الأول من هذا `.ColorMatrix`.

**Returns:**
float - العنصر في الصف الرابع والعمود الأول من هذا `.ColorMatrix`.
### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


يضبط العنصر في الصف الرابع والعمود الأول من هذا `.ColorMatrix`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف الرابع والعمود الأول من هذا `.ColorMatrix`. |

### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


يحصل على العنصر في الصف الرابع والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - العنصر في الصف الرابع والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


يضبط العنصر في الصف الرابع والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف الرابع والعمود الثاني من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


يحصل على العنصر في الصف الرابع والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - العنصر في الصف الرابع والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


يضبط العنصر في الصف الرابع والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف الرابع والعمود الثالث من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


يحصل على العنصر في الصف الرابع والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - العنصر في الصف الرابع والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


يضبط العنصر في الصف الرابع والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | العنصر في الصف الرابع والعمود الرابع من هذا [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


يحصل على العنصر في الصف والعمود المحددين في [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| صف | int | صف العنصر. |
| عمود | int | عمود العنصر. |

**Returns:**
float - العنصر في الصف والعمود المحددين.
### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


يضبط العنصر في الصف والعمود المحددين في [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| صف | int | صف العنصر. |
| عمود | int | عمود العنصر. |
| value | float | العنصر في الصف والعمود المحددين في [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

