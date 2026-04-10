---
title: DrawingSettings
second_title: Aspose.Drawing for Java API 참조
description: 아직 완전히 구현되지 않은 일부 기능을 사용할 경우 그리기 라이브러리의 동작을 조정할 수 있도록 합니다.
type: docs
weight: 19
url: /ko/java/com.aspose.drawing/drawingsettings/
---
**Inheritance:**
java.lang.Object
```
public final class DrawingSettings
```

아직 완전히 구현되지 않은 일부 기능을 사용할 경우 그리기 라이브러리의 동작을 조정할 수 있도록 합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [DrawingSettings()](#DrawingSettings--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getStrictMode()](#getStrictMode--) | 구현되지 않은 기능에 대한 보다 엄격한 캐치가 활성화되어 있는지를 나타내는 값을 가져옵니다. |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | 구현되지 않은 기능에 대한 보다 엄격한 캐치가 활성화되어 있는지를 나타내는 값을 설정합니다. |
### DrawingSettings() {#DrawingSettings--}
```
public DrawingSettings()
```


### getStrictMode() {#getStrictMode--}
```
public static boolean getStrictMode()
```


구현되지 않은 기능에 대한 보다 엄격한 캐치가 활성화되어 있는지를 나타내는 값을 가져옵니다.

--------------------

true로 설정하면 현재 구현에서 올바르게 작동하지 않는 기능/매개변수를 사용할 경우 라이브러리가 NotImplementedException을 발생시킵니다. false로 설정하면 일부 매개변수가 무시되어 사용자 프로그램이 작동할 수 있도록 합니다. 이 경우 그리기 결과가 GDI+와 비교하여 다르게 보일 수 있습니다.

**Returns:**
boolean - 구현되지 않은 기능에 대한 보다 엄격한 캐치가 활성화되어 있는지를 나타내는 값.
### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public static void setStrictMode(boolean value)
```


구현되지 않은 기능에 대한 보다 엄격한 캐치가 활성화되어 있는지를 나타내는 값을 설정합니다.

--------------------

true로 설정하면 현재 구현에서 올바르게 작동하지 않는 기능/매개변수를 사용할 경우 라이브러리가 NotImplementedException을 발생시킵니다. false로 설정하면 일부 매개변수가 무시되어 사용자 프로그램이 작동할 수 있도록 합니다. 이 경우 그리기 결과가 GDI+와 비교하여 다르게 보일 수 있습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean | 구현되지 않은 기능에 대한 보다 엄격한 캐치가 활성화되어 있는지를 나타내는 값. |

