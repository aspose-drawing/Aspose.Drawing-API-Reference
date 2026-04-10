---
title: License
second_title: Aspose.Drawing for Java API 참조
description: 구성 요소에 라이선스를 부여하는 메서드를 제공합니다.
type: docs
weight: 32
url: /ko/java/com.aspose.drawing/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

구성 요소에 라이선스를 부여하는 메서드를 제공합니다.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains
>  `
>  the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  [C#]
>  License license = new License();
>  license.SetLicense("MyLicense.lic");
>  
>  `
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [License()](#License--) | 이 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | 구성 요소에 라이선스를 적용합니다. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | 구성 요소에 라이선스를 적용합니다. |
### License() {#License--}
```
public License()
```


이 클래스의 새 인스턴스를 초기화합니다.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains
>  `
>  the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  [C#]
>  License license = new License();
>  license.SetLicense("MyLicense.lic");
>  [Visual Basic]
>  Dim license As license = New license
>  License.SetLicense("MyLicense.lic")
>  
>  `
>  `
>  the component jar file:
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
>  
>  `
> ```

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public final void setLicense(String licenseName)
```


구성 요소에 라이선스를 적용합니다.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains
>  `
>  the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  [C#]
>  License license = new License();
>  license.SetLicense("MyLicense.lic");
>  [Visual Basic]
>  Dim license As License = New License
>  license.SetLicense("MyLicense.lic")
>  
>  `
>  `
>  the component jar file:
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
>  
>  `
> ```

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | licenseName | java.lang.String | 전체 또는 짧은 파일 이름` 또는 포함된 리소스 이름`이 될 수 있습니다. 빈 문자열을 사용하면 평가 모드로 전환됩니다. |

--------------------

KKKCODEB

다음 위치에서 라이선스를 찾으려고 시도합니다:

KKKCODEE KKKCODEB

1. 명시적 경로.

KKKCODEE KKKCODEB

2. Aspose 구성 요소 어셈블리를 포함하는 폴더.

3. 클라이언트의 호출 어셈블리를 포함하는 폴더.

4. 엔트리(시작) 어셈블리를 포함하는 폴더.

5. 클라이언트의 호출 어셈블리 내에 포함된 리소스.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. 명시적 경로.

2. 클라이언트의 호출 어셈블리 내에 포함된 리소스.

KKKCODEE KKKCODEB

2. Aspose 구성 요소 JAR 파일을 포함하는 폴더.

3. 클라이언트의 호출 JAR 파일을 포함하는 폴더.

KKKCODEE |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


구성 요소에 라이선스를 적용합니다.

--------------------

> ```
> `
>  [C#]
>  License license = new License();
>  license.SetLicense(myStream);
>  [Visual Basic]
>  Dim license as License = new License
>  license.SetLicense(myStream)
>  `
>  `
>  License license = new License();
>  license.setLicense(myStream);
>  `
> ```

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | stream | java.io.InputStream | 라이선스를 포함하는 스트림. |

--------------------

KKKCODEB

이 메서드를 사용하여 스트림에서 라이선스를 로드합니다.

KKKCODEE

`void setLicense(java.io.InputStream stream)` |

