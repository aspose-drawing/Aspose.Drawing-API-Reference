---
title: FontFamilyDefinition
second_title: Aspose.Drawing for Java API 참조
description: 폰트 패밀리 정의입니다.
type: docs
weight: 25
url: /ko/java/com.aspose.drawing/fontfamilydefinition/
---
**Inheritance:**
java.lang.Object
```
public class FontFamilyDefinition
```

폰트 패밀리 정의입니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FontFamilyDefinition()](#FontFamilyDefinition--) | 새 인스턴스의 [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition) 클래스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addFontDefinition(int style, FontDefinitionExt fontDef)](#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-) | 폰트 정의를 폰트 패밀리에 추가합니다. |
| [getFontDefinition(int style)](#getFontDefinition-int-) | 특정 스타일에 대한 패밀리에서 폰트 정의를 가져옵니다. |
| [matchesLocalizedFamilyName(String localizedFamilyName)](#matchesLocalizedFamilyName-java.lang.String-) | 이 패밀리에서 로컬라이즈된 패밀리 이름을 일치시킵니다. |
| [getFamilyName()](#getFamilyName--) | 이 패밀리의 패밀리 이름을 가져옵니다. |
### FontFamilyDefinition() {#FontFamilyDefinition--}
```
public FontFamilyDefinition()
```


새 인스턴스의 [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition) 클래스를 초기화합니다.

### addFontDefinition(int style, FontDefinitionExt fontDef) {#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-}
```
public final void addFontDefinition(int style, FontDefinitionExt fontDef)
```


폰트 정의를 폰트 패밀리에 추가합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스타일 | int | 스타일입니다. |
| fontDef | [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) | 폰트 정의입니다. |

### getFontDefinition(int style) {#getFontDefinition-int-}
```
public final FontDefinitionExt getFontDefinition(int style)
```


특정 스타일에 대한 패밀리에서 폰트 정의를 가져옵니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스타일 | int | 스타일입니다. |

**Returns:**
[FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) - Returns font definition if exist for specified style, null otherwise.
### matchesLocalizedFamilyName(String localizedFamilyName) {#matchesLocalizedFamilyName-java.lang.String-}
```
public final boolean matchesLocalizedFamilyName(String localizedFamilyName)
```


이 패밀리에서 로컬라이즈된 패밀리 이름을 일치시킵니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| localizedFamilyName | java.lang.String | 로컬라이즈된 패밀리 이름입니다. |

**Returns:**
boolean - 이 패밀리에 로컬라이즈된 패밀리 이름이 포함된 경우 true.
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


이 패밀리의 패밀리 이름을 가져옵니다.

**Returns:**
java.lang.String - 패밀리 이름, 또는 빈 패밀리의 경우 null.
