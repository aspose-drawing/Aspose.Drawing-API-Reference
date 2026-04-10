---
title: DrawingSettings
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يسمح بضبط سلوك مكتبة الرسم في حال استخدام بعض الميزات التي لم تُنفّذ بالكامل بعد.
type: docs
weight: 19
url: /ar/java/com.aspose.drawing/drawingsettings/
---
**Inheritance:**
java.lang.Object
```
public final class DrawingSettings
```

يسمح بضبط سلوك مكتبة الرسم في حال استخدام بعض الميزات التي لم تُنفّذ بالكامل بعد.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [DrawingSettings()](#DrawingSettings--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getStrictMode()](#getStrictMode--) | يحصل على قيمة تشير إلى ما إذا كان تمكين التقاط أكثر صرامة للميزات غير المنفذة. |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | يضبط قيمة تشير إلى ما إذا كان تمكين التقاط أكثر صرامة للميزات غير المنفذة. |
### DrawingSettings() {#DrawingSettings--}
```
public DrawingSettings()
```


### getStrictMode() {#getStrictMode--}
```
public static boolean getStrictMode()
```


يحصل على قيمة تشير إلى ما إذا كان تمكين التقاط أكثر صرامة للميزات غير المنفذة.

--------------------

إذا تم تعيينه إلى true، في حالة استخدام ميزات/معلمات لا تعمل بشكل صحيح في التنفيذ الحالي، ستقوم المكتبة برمي استثناء NotImplementedException. إذا تم تعيينه إلى false، قد يتم تجاهل بعض المعلمات لإعطاء برنامج المستخدم فرصة للعمل. في هذه الحالة قد تبدو نتائج الرسم مختلفة مقارنةً بـ GDI+.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان تمكين التقاط أكثر صرامة للميزات غير المنفذة.
### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public static void setStrictMode(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان تمكين التقاط أكثر صرامة للميزات غير المنفذة.

--------------------

إذا تم تعيينه إلى true، في حالة استخدام ميزات/معلمات لا تعمل بشكل صحيح في التنفيذ الحالي، ستقوم المكتبة برمي استثناء NotImplementedException. إذا تم تعيينه إلى false، قد يتم تجاهل بعض المعلمات لإعطاء برنامج المستخدم فرصة للعمل. في هذه الحالة قد تبدو نتائج الرسم مختلفة مقارنةً بـ GDI+.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | قيمة تشير إلى ما إذا كان تمكين التقاط أكثر صرامة للميزات غير المنفذة. |

