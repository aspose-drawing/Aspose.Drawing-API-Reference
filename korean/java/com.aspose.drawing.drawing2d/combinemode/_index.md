---
title: CombineMode
second_title: Aspose.Drawing for Java API 참조
description: 다양한 클리핑 영역을 결합하는 방법을 지정합니다.
type: docs
weight: 13
url: /ko/java/com.aspose.drawing.drawing2d/combinemode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombineMode extends System.Enum
```

다양한 클리핑 영역을 결합하는 방법을 지정합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [Replace](#Replace) | 하나의 클리핑 영역이 다른 영역으로 교체됩니다. |
| [Intersect](#Intersect) | 두 클리핑 영역은 교차점을 취해 결합됩니다. |
| [Union](#Union) | 두 클리핑 영역은 두 영역의 합집합을 취해 결합됩니다. |
| [Xor](#Xor) | 두 클리핑 영역은 하나 또는 다른 영역에만 포함된 영역을 취해 결합되며, 두 영역 모두에 포함된 영역은 제외됩니다. |
| [Exclude](#Exclude) | 기존 영역이 새 영역을 기존 영역에서 제거한 결과로 교체됨을 지정합니다. |
| [Complement](#Complement) | 기존 영역이 새 영역에서 기존 영역을 제거한 결과로 교체됨을 지정합니다. |
### Replace {#Replace}
```
public static final int Replace
```


하나의 클리핑 영역이 다른 영역으로 교체됩니다.

### Intersect {#Intersect}
```
public static final int Intersect
```


두 클리핑 영역은 교차점을 취해 결합됩니다.

### Union {#Union}
```
public static final int Union
```


두 클리핑 영역은 두 영역의 합집합을 취해 결합됩니다.

### Xor {#Xor}
```
public static final int Xor
```


두 클리핑 영역은 하나 또는 다른 영역에만 포함된 영역을 취해 결합되며, 두 영역 모두에 포함된 영역은 제외됩니다.

### Exclude {#Exclude}
```
public static final int Exclude
```


기존 영역이 새 영역을 기존 영역에서 제거한 결과로 교체됨을 지정합니다. 다시 말해, 새 영역이 기존 영역에서 제외됩니다.

### Complement {#Complement}
```
public static final int Complement
```


기존 영역이 새 영역에서 기존 영역을 제거한 결과로 교체됨을 지정합니다. 다시 말해, 기존 영역이 새 영역에서 제외됩니다.

