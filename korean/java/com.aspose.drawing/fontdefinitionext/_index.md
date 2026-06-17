---
title: FontDefinitionExt
second_title: Aspose.Drawing for Java API 참조
description: 클래스는 글꼴 정의를 포함합니다
type: docs
weight: 23
url: /ko/java/com.aspose.drawing/fontdefinitionext/
---
**Inheritance:**
java.lang.Object
```
public class FontDefinitionExt
```

Class는 글꼴 정의를 포함합니다,
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset)](#FontDefinitionExt-java.lang.String-java.lang.String-java.util.List-java.lang.String--int-java.lang.String-long-) | [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | 글꼴 패밀리 이름을 가져옵니다. |
| [getStyle()](#getStyle--) | 글꼴 스타일을 가져옵니다. |
| [getFontName()](#getFontName--) | 글꼴 이름을 가져옵니다. |
| [getPostscriptName()](#getPostscriptName--) | 글꼴의 포스트스크립트 이름을 가져옵니다. |
| [getType()](#getType--) | 글꼴 유형을 가져옵니다. |
| [getFontFile()](#getFontFile--) | 글꼴 파일을 가져옵니다. |
| [getFileName()](#getFileName--) | 파일 이름을 가져옵니다. |
| [getFont()](#getFont--) | 글꼴을 가져옵니다. |
### FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset) {#FontDefinitionExt-java.lang.String-java.lang.String-java.util.List-java.lang.String--int-java.lang.String-long-}
```
public FontDefinitionExt(String fontName, String familyName, List<String> localizedFamilyNames, int type, String fileName, long offset)
```


[FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontName | java.lang.String | 글꼴 이름. |
| familyName | java.lang.String | 글꼴 패밀리. |
| localizedFamilyNames | java.util.List<java.lang.String> | 지역화된 글꼴 패밀리 이름. |
| type | int | 유형. |
| fileName | java.lang.String | 파일 이름. |
| offset | long | 오프셋입니다. |

### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


글꼴 패밀리 이름을 가져옵니다.

값: 글꼴 패밀리 이름.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public final String getStyle()
```


글꼴 스타일을 가져옵니다.

값: 글꼴 스타일.

**Returns:**
java.lang.String
### getFontName() {#getFontName--}
```
public final String getFontName()
```


글꼴 이름을 가져옵니다.

값: 글꼴 이름.

**Returns:**
java.lang.String
### getPostscriptName() {#getPostscriptName--}
```
public final String getPostscriptName()
```


글꼴의 포스트스크립트 이름을 가져옵니다.

값: 글꼴의 포스트스크립트 이름.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


글꼴 유형을 가져옵니다.

값: 글꼴 유형.

**Returns:**
int
### getFontFile() {#getFontFile--}
```
public final FontFileDefinition getFontFile()
```


글꼴 파일을 가져옵니다.

값: 글꼴 파일.

**Returns:**
com.aspose.fonts.sources.FontFileDefinition
### getFileName() {#getFileName--}
```
public final String getFileName()
```


파일 이름을 가져옵니다.

값: 파일 이름.

**Returns:**
java.lang.String
### getFont() {#getFont--}
```
public final IFont getFont()
```


글꼴을 가져옵니다.

**Returns:**
com.aspose.fonts.IFont - 현재 정의에 대한 글꼴을 반환합니다.
