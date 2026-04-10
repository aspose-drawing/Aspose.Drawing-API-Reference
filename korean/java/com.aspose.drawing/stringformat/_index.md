---
title: StringFormat
second_title: Aspose.Drawing for Java API 참조
description: 정렬 방향, 탭 정지, 생략 부호 삽입, 국가별 숫자 대체 및 OpenType 기능과 같은 텍스트 레이아웃 정보를 캡슐화합니다.
type: docs
weight: 47
url: /ko/java/com.aspose.drawing/stringformat/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class StringFormat implements System.IDisposable
```

텍스트 레이아웃 정보(정렬, 방향 및 탭 정지와 같은)와 표시 조작(생략 부호 삽입 및 국가별 숫자 대체와 같은) 및 OpenType 기능을 캡슐화합니다. 이 클래스는 상속될 수 없습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [StringFormat()](#StringFormat--) | 새로운 [StringFormat](../../com.aspose.drawing/stringformat) 클래스 인스턴스를 초기화합니다. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.drawing.StringFormat-) | 지정된 기존 [StringFormat](../../com.aspose.drawing/stringformat) 객체에서 새로운 [StringFormat](../../com.aspose.drawing/stringformat) 클래스 인스턴스를 초기화합니다. |
| [StringFormat(int options, int language)](#StringFormat-int-int-) | 지정된 [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 열거형 및 언어를 사용하여 새로운 [StringFormat](../../com.aspose.drawing/stringformat) 클래스 인스턴스를 초기화합니다. |
| [StringFormat(int options)](#StringFormat-int-) | 지정된 [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 열거형을 사용하여 새로운 [StringFormat](../../com.aspose.drawing/stringformat) 클래스 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) |  |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) |  |
| [getFirstTabOffset()](#getFirstTabOffset--) |  |
| [getGenericDefault()](#getGenericDefault--) | 일반적인 기본 [StringFormat](../../com.aspose.drawing/stringformat) 객체를 가져옵니다. |
| [getGenericTypographic()](#getGenericTypographic--) | 일반적인 타이포그래픽 [StringFormat](../../com.aspose.drawing/stringformat) 객체를 가져옵니다. |
| [getFormatFlags()](#getFormatFlags--) | [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 열거형을 가져오거나 설정합니다. 이 열거형은 서식 정보를 포함합니다. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 열거형을 가져오거나 설정합니다. 이 열거형은 서식 정보를 포함합니다. |
| [getAlignment()](#getAlignment--) | 수직 평면에서 텍스트 정렬 정보를 가져오거나 설정합니다. |
| [setAlignment(int value)](#setAlignment-int-) | 수직 평면에서 텍스트 정렬 정보를 가져오거나 설정합니다. |
| [getLineAlignment()](#getLineAlignment--) | 수평 평면에서 줄 정렬을 가져오거나 설정합니다. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | 수평 평면에서 줄 정렬을 가져오거나 설정합니다. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | 이 [StringFormat](../../com.aspose.drawing/stringformat) 객체에 대한 `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) 객체를 가져오거나 설정합니다. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | 이 [StringFormat](../../com.aspose.drawing/stringformat) 객체에 대한 `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) 객체를 가져오거나 설정합니다. |
| [getTrimming()](#getTrimming--) | 이 [StringFormat](../../com.aspose.drawing/stringformat) 객체에 대한 [StringTrimming](../../com.aspose.drawing/stringtrimming) 열거형을 가져오거나 설정합니다. |
| [setTrimming(int value)](#setTrimming-int-) | 이 [StringFormat](../../com.aspose.drawing/stringformat) 객체에 대한 [StringTrimming](../../com.aspose.drawing/stringtrimming) 열거형을 가져오거나 설정합니다. |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | 현지 숫자가 서양 숫자로 대체될 때 사용되는 언어를 가져옵니다. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | 숫자 대체에 사용할 방법을 가져옵니다. |
| [dispose()](#dispose--) | 이 [StringFormat](../../com.aspose.drawing/stringformat) 객체가 사용한 모든 리소스를 해제합니다. |
| [deepClone()](#deepClone--) | 이 [StringFormat](../../com.aspose.drawing/stringformat) 객체의 정확한 복사본을 생성합니다. |
| [getTabStops(float[] firstTabOffset)](#getTabStops-float---) | 이 [StringFormat](../../com.aspose.drawing/stringformat) 객체에 대한 탭 정지를 가져옵니다. |
| [getTabStops()](#getTabStops--) | `Aspose.Imaging.getGraphics().PageUnit` 속성으로 지정된 단위로 탭 정지 사이의 거리 배열을 가져옵니다. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | 이 [StringFormat](../../com.aspose.drawing/stringformat) 객체에 대한 탭 정지를 설정합니다. |
| [setDigitSubstitution(int language, int substitute)](#setDigitSubstitution-int-int-) | 현지 숫자가 서양 숫자로 대체될 때 사용할 언어와 방법을 지정합니다. |
| [setMeasurableCharacterRanges(CharacterRange[] ranges)](#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---) | `MeasureCharacterRanges` 메서드 호출로 측정된 문자 범위를 나타내는 [CharacterRange](../../com.aspose.drawing/characterrange) 구조체 배열을 지정합니다. |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


새로운 [StringFormat](../../com.aspose.drawing/stringformat) 클래스 인스턴스를 초기화합니다.

### StringFormat(StringFormat format) {#StringFormat-com.aspose.drawing.StringFormat-}
```
public StringFormat(StringFormat format)
```


지정된 기존 [StringFormat](../../com.aspose.drawing/stringformat) 객체에서 새로운 [StringFormat](../../com.aspose.drawing/stringformat) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.drawing/stringformat) | 새로운 [StringFormat](../../com.aspose.drawing/stringformat) 객체를 초기화할 [StringFormat](../../com.aspose.drawing/stringformat) 객체입니다. |

### StringFormat(int options, int language) {#StringFormat-int-int-}
```
public StringFormat(int options, int language)
```


지정된 [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 열거형 및 언어를 사용하여 새로운 [StringFormat](../../com.aspose.drawing/stringformat) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | int | 새로운 [StringFormat](../../com.aspose.drawing/stringformat) 객체에 대한 [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 열거형입니다. |
| 언어 | int | 텍스트의 언어를 나타내는 값입니다. |

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


지정된 [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 열거형을 사용하여 새로운 [StringFormat](../../com.aspose.drawing/stringformat) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | int | 새로운 [StringFormat](../../com.aspose.drawing/stringformat) 객체에 대한 [StringFormatFlags](../../com.aspose.drawing/stringformatflags) 열거형입니다. |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```




**Returns:**
float
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


일반적인 기본 [StringFormat](../../com.aspose.drawing/stringformat) 객체를 가져옵니다.

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat)
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


일반적인 타이포그래픽 [StringFormat](../../com.aspose.drawing/stringformat) 객체를 가져옵니다.

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - A generic typographic [StringFormat](../../com.aspose.drawing/stringformat) object.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


[StringFormatFlags](../../com.aspose.drawing/stringformatflags) 열거형을 가져오거나 설정합니다. 이 열거형은 서식 정보를 포함합니다.

**Returns:**
int
### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


[StringFormatFlags](../../com.aspose.drawing/stringformatflags) 열거형을 가져오거나 설정합니다. 이 열거형은 서식 정보를 포함합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


수직 평면에서 텍스트 정렬 정보를 가져오거나 설정합니다.

**Returns:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


수직 평면에서 텍스트 정렬 정보를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


수평 평면에서 줄 정렬을 가져오거나 설정합니다.

**Returns:**
int
### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


수평 평면에서 줄 정렬을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


이 [StringFormat](../../com.aspose.drawing/stringformat) 객체에 대한 `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) 객체를 가져오거나 설정합니다.

**Returns:**
int
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


이 [StringFormat](../../com.aspose.drawing/stringformat) 객체에 대한 `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) 객체를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


이 [StringFormat](../../com.aspose.drawing/stringformat) 객체에 대한 [StringTrimming](../../com.aspose.drawing/stringtrimming) 열거형을 가져오거나 설정합니다.

**Returns:**
int
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


이 [StringFormat](../../com.aspose.drawing/stringformat) 객체에 대한 [StringTrimming](../../com.aspose.drawing/stringtrimming) 열거형을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


현지 숫자가 서양 숫자로 대체될 때 사용되는 언어를 가져옵니다.

**Returns:**
int - 현지 숫자가 서양 숫자로 대체될 때 사용될 언어를 식별하는 국가 언어 지원(NLS) 언어 식별자입니다. `System.Globalization.CultureInfo.LCID` 속성을 java.util.Locale 객체의 NLS 언어 식별자로 전달할 수 있습니다. 예를 들어, 문자열 "ar-EG"를 java.util.Locale 생성자에 전달하여 java.util.Locale 객체를 만든다고 가정합니다. 해당 java.util.Locale 객체의 `System.Globalization.CultureInfo.LCID` 속성을 `StringDigitSubstitute.Traditional`와 함께 [.setDigitSubstitution(int,int)](../../null/\#setDigitSubstitution-int-int-) 메서드에 전달하면, 표시 시 아라비아-인도 숫자가 서양 숫자로 대체됩니다.
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


숫자 대체에 사용할 방법을 가져옵니다.

**Returns:**
int - 현재 글꼴에서 지원되지 않아 표시할 수 없는 문자열의 문자를 어떻게 대체할지 지정하는 [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute) 열거형 값입니다.
### dispose() {#dispose--}
```
public void dispose()
```


이 [StringFormat](../../com.aspose.drawing/stringformat) 객체가 사용한 모든 리소스를 해제합니다.

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


이 [StringFormat](../../com.aspose.drawing/stringformat) 객체의 정확한 복사본을 생성합니다.

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - The [StringFormat](../../com.aspose.drawing/stringformat) object this method creates.
### getTabStops(float[] firstTabOffset) {#getTabStops-float---}
```
public float[] getTabStops(float[] firstTabOffset)
```


이 [StringFormat](../../com.aspose.drawing/stringformat) 객체에 대한 탭 정지를 가져옵니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| firstTabOffset | float[] | 텍스트 줄의 시작과 첫 번째 탭 정지점 사이의 공백 수입니다. |

**Returns:**
float[] - 탭 정지점 사이의 거리(공백 수) 배열입니다.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


`Aspose.Imaging.getGraphics().PageUnit` 속성으로 지정된 단위로 탭 정지 사이의 거리 배열을 가져옵니다.

**Returns:**
float[] - 탭 정지점들입니다.

이 속성은 제거된 메서드 GetTabStops에 대해 도입되었습니다.
### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


이 [StringFormat](../../com.aspose.drawing/stringformat) 객체에 대한 탭 정지를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| firstTabOffset | float | 텍스트 줄의 시작과 첫 번째 탭 정지점 사이의 공백 수입니다. |
| tabStops | float[] | Graphics.PageUnit 속성에서 지정한 단위로 탭 정지점 사이의 거리 배열입니다. |

### setDigitSubstitution(int language, int substitute) {#setDigitSubstitution-int-int-}
```
public void setDigitSubstitution(int language, int substitute)
```


현지 숫자가 서양 숫자로 대체될 때 사용할 언어와 방법을 지정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 언어 | int | 국가 언어 지원(NLS) 언어 식별자는 현지 숫자가 서양 숫자로 대체될 때 사용될 언어를 식별합니다. `System.Globalization.CultureInfo.LCID` 속성을 java.util.Locale 객체의 NLS 언어 식별자로 전달할 수 있습니다. 예를 들어, 문자열 `"ar-EG"`를 java.util.Locale 생성자에 전달하여 java.util.Locale 객체를 만든다고 가정합니다. 해당 java.util.Locale 객체의 `System.Globalization.CultureInfo.LCID` 속성을 `StringDigitSubstitute.Traditional`와 함께 `M:StringFormat.SetDigitSubstitution(System.Int32,StringDigitSubstitute)` 메서드에 전달하면, 표시 시 아라비아-인도 숫자가 서양 숫자로 대체됩니다. |
| substitute | int | [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute) 열거형의 요소로, 숫자가 어떻게 표시되는지를 지정합니다. |

### setMeasurableCharacterRanges(CharacterRange[] ranges) {#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---}
```
public void setMeasurableCharacterRanges(CharacterRange[] ranges)
```


`MeasureCharacterRanges` 메서드 호출로 측정된 문자 범위를 나타내는 [CharacterRange](../../com.aspose.drawing/characterrange) 구조체 배열을 지정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| ranges | [CharacterRange\[\]](../../com.aspose.drawing/characterrange) | `MeasureCharacterRanges` 메서드 호출로 측정되는 문자 범위를 지정하는 [CharacterRange](../../com.aspose.drawing/characterrange) 구조체 배열입니다. |

