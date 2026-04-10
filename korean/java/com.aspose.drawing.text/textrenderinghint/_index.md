---
title: TextRenderingHint
second_title: Aspose.Drawing for Java API 참조
description: 텍스트 렌더링 품질을 지정합니다.
type: docs
weight: 14
url: /ko/java/com.aspose.drawing.text/textrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextRenderingHint extends System.Enum
```

텍스트 렌더링 품질을 지정합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [SystemDefault](#SystemDefault) | 각 문자는 해당 글리프 비트맵을 사용하여 시스템 기본 렌더링 힌트와 함께 그려집니다. |
| [SingleBitPerPixelGridFit](#SingleBitPerPixelGridFit) | 각 문자는 해당 글리프 비트맵을 사용하여 그려집니다. |
| [SingleBitPerPixel](#SingleBitPerPixel) | 각 문자는 해당 글리프 비트맵을 사용하여 그려집니다. |
| [AntiAliasGridFit](#AntiAliasGridFit) | 각 문자는 힌팅이 적용된 안티앨리어싱 글리프 비트맵을 사용하여 그려집니다. |
| [AntiAlias](#AntiAlias) | 각 문자는 힌팅 없이 안티앨리어싱 글리프 비트맵을 사용하여 그려집니다. |
| [ClearTypeGridFit](#ClearTypeGridFit) | 각 문자는 힌팅이 적용된 ClearType 글리프 비트맵을 사용하여 그려집니다. |
### SystemDefault {#SystemDefault}
```
public static final int SystemDefault
```


각 문자는 해당 글리프 비트맵을 사용하여 시스템 기본 렌더링 힌트와 함께 그려집니다. 텍스트는 사용자가 시스템에 대해 선택한 폰트 스무딩 설정에 따라 그려집니다.

### SingleBitPerPixelGridFit {#SingleBitPerPixelGridFit}
```
public static final int SingleBitPerPixelGridFit
```


각 문자는 해당 글리프 비트맵을 사용하여 그려집니다. 힌팅은 줄기와 곡선에서 문자 모양을 개선하는 데 사용됩니다.

### SingleBitPerPixel {#SingleBitPerPixel}
```
public static final int SingleBitPerPixel
```


각 문자는 해당 글리프 비트맵을 사용하여 그려집니다. 힌팅이 사용되지 않습니다.

### AntiAliasGridFit {#AntiAliasGridFit}
```
public static final int AntiAliasGridFit
```


각 문자는 힌팅이 적용된 안티앨리어싱 글리프 비트맵을 사용하여 그려집니다. 안티앨리어싱으로 인해 품질이 크게 향상되지만, 성능 비용이 더 높습니다.

### AntiAlias {#AntiAlias}
```
public static final int AntiAlias
```


각 문자는 힌팅 없이 안티앨리어싱 글리프 비트맵을 사용하여 그려집니다. 안티앨리어싱으로 인해 품질이 향상됩니다. 힌팅이 꺼져 있기 때문에 줄기 너비 차이가 눈에 띌 수 있습니다.

### ClearTypeGridFit {#ClearTypeGridFit}
```
public static final int ClearTypeGridFit
```


각 문자는 힌팅이 적용된 글리프 ClearType 비트맵을 사용하여 그려집니다. 최고 품질 설정입니다. ClearType 글꼴 기능을 활용하기 위해 사용됩니다.

