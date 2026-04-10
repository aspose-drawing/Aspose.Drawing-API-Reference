---
title: CombineMode
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يحدد كيفية دمج مناطق القص المختلفة.
type: docs
weight: 13
url: /ar/java/com.aspose.drawing.drawing2d/combinemode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombineMode extends System.Enum
```

يحدد كيفية دمج مناطق القص المختلفة.
## الحقول

| حقل | الوصف |
| --- | --- |
| [Replace](#Replace) | يتم استبدال منطقة قص واحدة بأخرى. |
| [Intersect](#Intersect) | يتم دمج منطقتي قص بأخذ تقاطعهما. |
| [Union](#Union) | يتم دمج منطقتي قص بأخذ اتحادهما. |
| [Xor](#Xor) | يتم دمج منطقتي قص بأخذ المناطق المحصورة فقط في إحداهما أو الأخرى، ولكن ليس كليهما. |
| [Exclude](#Exclude) | يحدد أن المنطقة الحالية يتم استبدالها بنتيجة إزالة المنطقة الجديدة من المنطقة الحالية. |
| [Complement](#Complement) | يحدد أن المنطقة الحالية يتم استبدالها بنتيجة إزالة المنطقة الحالية من المنطقة الجديدة. |
### Replace {#Replace}
```
public static final int Replace
```


يتم استبدال منطقة قص واحدة بأخرى.

### Intersect {#Intersect}
```
public static final int Intersect
```


يتم دمج منطقتي قص بأخذ تقاطعهما.

### Union {#Union}
```
public static final int Union
```


يتم دمج منطقتي قص بأخذ اتحادهما.

### Xor {#Xor}
```
public static final int Xor
```


يتم دمج منطقتي قص بأخذ المناطق المحصورة فقط في إحداهما أو الأخرى، ولكن ليس كليهما.

### Exclude {#Exclude}
```
public static final int Exclude
```


يحدد أن المنطقة الحالية يتم استبدالها بنتيجة إزالة المنطقة الجديدة من المنطقة الحالية. بعبارة أخرى، يتم استبعاد المنطقة الجديدة من المنطقة الحالية.

### Complement {#Complement}
```
public static final int Complement
```


يحدد أن المنطقة الحالية يتم استبدالها بنتيجة إزالة المنطقة الحالية من المنطقة الجديدة. بعبارة أخرى، يتم استبعاد المنطقة الحالية من المنطقة الجديدة.

