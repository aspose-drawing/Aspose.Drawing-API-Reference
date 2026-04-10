---
title: MetafileType
second_title: Aspose.Drawing for Java API 참조
description: 메타파일 유형을 지정합니다.
type: docs
weight: 33
url: /ko/java/com.aspose.drawing.imaging/metafiletype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MetafileType extends System.Enum
```

메타파일 유형을 지정합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [Invalid](#Invalid) | GDI+에서 인식되지 않는 메타파일 형식을 지정합니다. |
| [Wmf](#Wmf) | WMF(Windows Metafile) 파일을 지정합니다. |
| [WmfPlaceable](#WmfPlaceable) | 앞에 배치 가능한 메타파일 헤더가 있는 WMF(Windows Metafile) 파일을 지정합니다. |
| [Emf](#Emf) | Enhanced Metafile(EMF) 파일을 지정합니다. |
| [EmfPlusOnly](#EmfPlusOnly) | EMF+ 파일을 지정합니다. |
| [EmfPlusDual](#EmfPlusDual) | EMF+ Dual 파일을 지정합니다. |
### Invalid {#Invalid}
```
public static final int Invalid
```


GDI+에서 인식되지 않는 메타파일 형식을 지정합니다.

### Wmf {#Wmf}
```
public static final int Wmf
```


WMF(Windows Metafile) 파일을 지정합니다. 이러한 파일은 GDI 레코드만 포함합니다.

### WmfPlaceable {#WmfPlaceable}
```
public static final int WmfPlaceable
```


앞에 배치 가능한 메타파일 헤더가 있는 WMF(Windows Metafile) 파일을 지정합니다.

### Emf {#Emf}
```
public static final int Emf
```


Enhanced Metafile(EMF) 파일을 지정합니다. 이러한 파일은 GDI 레코드만 포함합니다.

### EmfPlusOnly {#EmfPlusOnly}
```
public static final int EmfPlusOnly
```


EMF+ 파일을 지정합니다. 이러한 파일은 GDI+ 레코드만 포함하며 GDI+를 사용하여 표시해야 합니다. GDI를 사용하여 레코드를 표시하면 예측할 수 없는 결과가 발생할 수 있습니다.

### EmfPlusDual {#EmfPlusDual}
```
public static final int EmfPlusDual
```


EMF+ Dual 파일을 지정합니다. 이러한 파일은 대체 GDI 레코드와 함께 GDI+ 레코드를 포함하며 GDI 또는 GDI+ 중 하나를 사용하여 표시할 수 있습니다. GDI를 사용하여 레코드를 표시하면 일부 품질 저하가 발생할 수 있습니다.

