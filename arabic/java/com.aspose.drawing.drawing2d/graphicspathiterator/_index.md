---
title: GraphicsPathIterator
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يوفر القدرة على التكرار عبر المسارات الفرعية في  واختبار أنواع الأشكال الموجودة في كل مسار فرعي.
type: docs
weight: 24
url: /ar/java/com.aspose.drawing.drawing2d/graphicspathiterator/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class GraphicsPathIterator implements System.IDisposable
```

يوفر القدرة على التجول عبر المسارات الفرعية في [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) واختبار أنواع الأشكال الموجودة في كل مسار فرعي. لا يمكن وراثة هذه الفئة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [GraphicsPathIterator(GraphicsPath path)](#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-) | ينشئ مثيلاً جديدًا من الفئة [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCount()](#getCount--) | يحصل على عدد النقاط في المسار. |
| [getSubpathCount()](#getSubpathCount--) | يحصل على عدد المسارات الفرعية في المسار. |
| [dispose()](#dispose--) | ينفّذ مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة تعيين الموارد غير المُدارة. |
| [copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)](#copyData-com.aspose.drawing.PointF-----byte-----int-int-) | ينسخ مصفوفات الخاصيتين GraphicsPath.PathPoints و GraphicsPath.PathTypes للمسار المرتبط بـ [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) إلى المصفوفتين المحددتين. |
| [enumerate(PointF[][] points, byte[][] types)](#enumerate-com.aspose.drawing.PointF-----byte-----) | ينسخ مصفوفات الخاصيتين GraphicsPath.PathPoints و GraphicsPath.PathTypes للمسار المرتبط بـ [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) إلى المصفوفتين المحددتين. |
| [hasCurve()](#hasCurve--) | يشير إلى ما إذا كان المسار المرتبط بـ [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) يحتوي على منحنى. |
| [nextMarker(int[] startIndex, int[] endIndex)](#nextMarker-int---int---) | يزيد قيمة [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) إلى العلامة التالية في المسار ويعيد مؤشرات البداية والنهاية عبر معاملات [out]. |
| [nextMarker(GraphicsPath path)](#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-) | هذا الكائن [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) يحتوي على كائن [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) مرتبط به. |
| [nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)](#nextPathType-byte---int---int---) | يحصل على الفهرس الابتدائي والفهرس النهائي للمجموعة التالية من نقاط البيانات التي جميعها من نفس النوع. |
| [nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)](#nextSubpath-int---int---boolean---) | ينقل [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) إلى المسار الفرعي التالي في المسار. |
| [nextSubpath(GraphicsPath path, boolean[] isClosed)](#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---) | يحصل على الشكل التالي (المسار الفرعي) من المسار المرتبط بهذا [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator). |
| [rewind()](#rewind--) | يعيد هذا [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) إلى بداية المسار المرتبط به. |
### GraphicsPathIterator(GraphicsPath path) {#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public GraphicsPathIterator(GraphicsPath path)
```


ينشئ مثيلاً جديدًا من الفئة [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | كائن [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) الذي سيتم تهيئته لهذه الفئة المساعدة. |

### getCount() {#getCount--}
```
public int getCount()
```


يحصل على عدد النقاط في المسار.

**Returns:**
int - عدد النقاط في المسار.
### getSubpathCount() {#getSubpathCount--}
```
public int getSubpathCount()
```


يحصل على عدد المسارات الفرعية في المسار.

**Returns:**
int - عدد المسارات الفرعية في المسار.
### dispose() {#dispose--}
```
public void dispose()
```


ينفّذ مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة تعيين الموارد غير المُدارة.

### copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex) {#copyData-com.aspose.drawing.PointF-----byte-----int-int-}
```
public int copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)
```


ينسخ مصفوفات الخاصيتين GraphicsPath.PathPoints و GraphicsPath.PathTypes للمسار المرتبط بـ [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) إلى المصفوفتين المحددتين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | عند الإرجاع، يحتوي على مصفوفة من هياكل System.Drawing.PointF التي تمثل النقاط في المسار. |
| الأنواع | byte[][] | عند الإرجاع، يحتوي على مصفوفة من البايتات التي تمثل أنواع النقاط في المسار. |
| startIndex | int | يحدد الفهرس الابتدائي للمصفوفات. |
| endIndex | int | يحدد الفهرس النهائي للمصفوفات. |

**Returns:**
int - عدد النقاط المنقولة.
### enumerate(PointF[][] points, byte[][] types) {#enumerate-com.aspose.drawing.PointF-----byte-----}
```
public int enumerate(PointF[][] points, byte[][] types)
```


ينسخ مصفوفات الخاصيتين GraphicsPath.PathPoints و GraphicsPath.PathTypes للمسار المرتبط بـ [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) إلى المصفوفتين المحددتين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | عند الإرجاع، يحتوي على مصفوفة من هياكل System.Drawing.PointF التي تمثل النقاط في المسار. |
| الأنواع | byte[][] | عند الإرجاع، يحتوي على مصفوفة من البايتات التي تمثل أنواع النقاط في المسار. |

**Returns:**
int - عدد النقاط المنقولة.
### hasCurve() {#hasCurve--}
```
public boolean hasCurve()
```


يشير إلى ما إذا كان المسار المرتبط بـ [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) يحتوي على منحنى.

**Returns:**
boolean - تُرجِع هذه الطريقة true إذا كان المسار الفرعي الحالي يحتوي على منحنى؛ وإلا، false.
### nextMarker(int[] startIndex, int[] endIndex) {#nextMarker-int---int---}
```
public int nextMarker(int[] startIndex, int[] endIndex)
```


يزيد قيمة [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) إلى العلامة التالية في المسار ويعيد مؤشرات البداية والنهاية عبر معاملات [out].

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| startIndex | int[] | [out] المرجع الصحيح المقدم لهذا المعامل يستقبل فهرس النقطة التي تبدأ مسارًا فرعيًا. |
| endIndex | int[] | [out] المرجع الصحيح المقدم لهذا المعامل يستقبل فهرس النقطة التي تنهي المسار الفرعي الذي تشير إليه startIndex. |

**Returns:**
int - عدد النقاط بين هذه العلامة واللاحقة.
### nextMarker(GraphicsPath path) {#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public int nextMarker(GraphicsPath path)
```


هذا الكائن [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) يحتوي على كائن [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) مرتبط به. تقوم هذه الطريقة بزيادة الـ [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) المرتبط إلى العلامة التالية في مساره وتنسخ جميع النقاط الموجودة بين العلامة الحالية والعلامة التالية (أو نهاية المسار) إلى كائن [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) ثاني يتم تمريره كمعامل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | كائن [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) الذي ستُنسخ إليه النقاط. |

**Returns:**
int - عدد النقاط بين هذه العلامة واللاحقة.
### nextPathType(byte[] pathType, int[] startIndex, int[] endIndex) {#nextPathType-byte---int---int---}
```
public int nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)
```


يحصل على الفهرس الابتدائي والفهرس النهائي للمجموعة التالية من نقاط البيانات التي جميعها من نفس النوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pathType | byte[] | [out] يستقبل نوع النقطة المشترك لجميع النقاط في المجموعة. يمكن استرجاع الأنواع الممكنة من تعداد [PathPointType](../../com.aspose.drawing.drawing2d/pathpointtype). |
| startIndex | int[] | [out] يستقبل الفهرس الابتدائي لمجموعة النقاط. |
| endIndex | int[] | [out] يستقبل الفهرس النهائي لمجموعة النقاط. |

**Returns:**
int - تُرجِع هذه الطريقة عدد نقاط البيانات في المجموعة. إذا لم تعد هناك مجموعات أخرى في المسار، تُرجِع هذه الطريقة 0.
### nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed) {#nextSubpath-int---int---boolean---}
```
public int nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)
```


ينقل الـ [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) إلى المسار الفرعي التالي في المسار. الفهرس الابتدائي والفهرس النهائي للمسار الفرعي التالي موجودان في المعاملات [out].

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| startIndex | int[] | [out] يستقبل الفهرس الابتدائي للمسار الفرعي التالي. |
| endIndex | int[] | [out] يستقبل الفهرس النهائي للمسار الفرعي التالي. |
| isClosed | boolean[] | [out] يوضح ما إذا كان المسار الفرعي مغلقًا. |

**Returns:**
int - عدد نقاط البيانات في الشكل المسترجع (المسار الفرعي). إذا لم يعد هناك أشكال أخرى لاسترجاعها، يتم إرجاع الصفر.
### nextSubpath(GraphicsPath path, boolean[] isClosed) {#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---}
```
public int nextSubpath(GraphicsPath path, boolean[] isClosed)
```


يحصل على الشكل التالي (المسار الفرعي) من المسار المرتبط بهذا [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | كائن [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) يُضبط نقاط بياناته لتطابق نقاط بيانات الشكل المسترجع (المسار الفرعي) لهذا المتكرر. |
| isClosed | boolean[] | [out] يوضح ما إذا كان المسار الفرعي الحالي مغلقًا. تكون القيمة true إذا كان الشكل مغلقًا، وإلا تكون false. |

**Returns:**
int - عدد نقاط البيانات في الشكل المسترجع (المسار الفرعي). إذا لم يعد هناك أشكال أخرى لاسترجاعها، يتم إرجاع الصفر.
### rewind() {#rewind--}
```
public void rewind()
```


يعيد هذا [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) إلى بداية المسار المرتبط به.

