---
title: PrivateFontCollection
second_title: Aspose.Drawing for Java API 참조
description: 클라이언트 애플리케이션에서 제공하는 글꼴 파일로 만든 글꼴 패밀리 컬렉션을 제공합니다.
type: docs
weight: 13
url: /ko/java/com.aspose.drawing.text/privatefontcollection/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.FontCollection](../../com.aspose.drawing/fontcollection)
```
public final class PrivateFontCollection extends FontCollection
```

클라이언트 애플리케이션에서 제공하는 글꼴 파일로 만든 글꼴 패밀리 컬렉션을 제공합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PrivateFontCollection()](#PrivateFontCollection--) | [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addFontFile(String filename)](#addFontFile-java.lang.String-) | 지정된 파일에서 폰트를 추가하여 이 [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection)에 추가합니다. |
| [addMemoryFont(byte[] memory, int length)](#addMemoryFont-byte---int-) | 시스템 메모리에 포함된 폰트를 이 [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection)에 추가합니다. |
### PrivateFontCollection() {#PrivateFontCollection--}
```
public PrivateFontCollection()
```


[PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection) 클래스의 새 인스턴스를 초기화합니다.

### addFontFile(String filename) {#addFontFile-java.lang.String-}
```
public void addFontFile(String filename)
```


지정된 파일에서 폰트를 추가하여 이 [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection)에 추가합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filename | java.lang.String | 추가할 폰트의 파일 이름을 포함하는 문자열입니다. |

### addMemoryFont(byte[] memory, int length) {#addMemoryFont-byte---int-}
```
public void addMemoryFont(byte[] memory, int length)
```


시스템 메모리에 포함된 폰트를 이 [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection)에 추가합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 메모리 | byte[] | 추가할 폰트의 메모리 주소입니다. |
| length | int | 추가할 폰트의 메모리 길이입니다. |

