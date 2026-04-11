---
title: EncoderValue
second_title: Справочник API Aspose.Drawing для Java
description: Используется для указания значения параметра, передаваемого JPEG или TIFF кодировщику изображения при использовании методов MImage.SaveSystem.StringSystem.Drawing.Imaging.ImageCodecInfoSystem.Drawing.Imaging.EncoderParameters или MImage.SaveAddSystem.Drawing.Imaging.EncoderParameters.
type: docs
weight: 22
url: /ru/java/com.aspose.drawing.imaging/encodervalue/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EncoderValue extends System.Enum
```

Используется для указания значения параметра, передаваемого кодировщику JPEG или TIFF при использовании методов `M:Image.Save(System.String,System.Drawing.Imaging.ImageCodecInfo,System.Drawing.Imaging.EncoderParameters)` или `M:Image.SaveAdd(System.Drawing.Imaging.EncoderParameters)`. 
## Поля

| Поле | Описание |
| --- | --- |
| [ColorTypeCMYK](#ColorTypeCMYK) | Не используется в GDI+ версии 1.0. |
| [ColorTypeYCCK](#ColorTypeYCCK) | Не используется в GDI+ версии 1.0. |
| [CompressionLZW](#CompressionLZW) | Указывает схему сжатия LZW. |
| [CompressionCCITT3](#CompressionCCITT3) | Указывает схему сжатия CCITT3. |
| [CompressionCCITT4](#CompressionCCITT4) | Указывает схему сжатия CCITT4. |
| [CompressionRle](#CompressionRle) | Указывает схему сжатия RLE. |
| [CompressionNone](#CompressionNone) | Указывает отсутствие сжатия. |
| [ScanMethodInterlaced](#ScanMethodInterlaced) | Не используется в GDI+ версии 1.0. |
| [ScanMethodNonInterlaced](#ScanMethodNonInterlaced) | Не используется в GDI+ версии 1.0. |
| [VersionGif87](#VersionGif87) | Не используется в GDI+ версии 1.0. |
| [VersionGif89](#VersionGif89) | Не используется в GDI+ версии 1.0. |
| [RenderProgressive](#RenderProgressive) | Не используется в GDI+ версии 1.0. |
| [RenderNonProgressive](#RenderNonProgressive) | Не используется в GDI+ версии 1.0. |
| [TransformRotate90](#TransformRotate90) | Указывает, что изображение должно быть повернуто по часовой стрелке на 90 градусов относительно его центра. |
| [TransformRotate180](#TransformRotate180) | Указывает, что изображение должно быть повернуто на 180 градусов относительно его центра. |
| [TransformRotate270](#TransformRotate270) | Указывает, что изображение должно быть повернуто по часовой стрелке на 270 градусов вокруг своего центра. |
| [TransformFlipHorizontal](#TransformFlipHorizontal) | Указывает, что изображение должно быть отражено по горизонтали (относительно вертикальной оси). |
| [TransformFlipVertical](#TransformFlipVertical) | Указывает, что изображение должно быть отражено по вертикали (относительно горизонтальной оси). |
| [MultiFrame](#MultiFrame) | Указывает, что у изображения более одного кадра (страницы). |
| [LastFrame](#LastFrame) | Указывает последний кадр в многокадровом изображении. |
| [Flush](#Flush) | Указывает, что многокадровый файл или поток должны быть закрыты. |
| [FrameDimensionTime](#FrameDimensionTime) | Не используется в GDI+ версии 1.0. |
| [FrameDimensionResolution](#FrameDimensionResolution) | Не используется в GDI+ версии 1.0. |
| [FrameDimensionPage](#FrameDimensionPage) | Указывает, что кадр должен быть добавлен к размеру страницы изображения. |
### ColorTypeCMYK {#ColorTypeCMYK}
```
public static final int ColorTypeCMYK
```


Не используется в GDI+ версии 1.0.

### ColorTypeYCCK {#ColorTypeYCCK}
```
public static final int ColorTypeYCCK
```


Не используется в GDI+ версии 1.0.

### CompressionLZW {#CompressionLZW}
```
public static final int CompressionLZW
```


Указывает схему сжатия LZW. Может быть передан кодировщику TIFF в качестве параметра, относящегося к категории Сжатие.

### CompressionCCITT3 {#CompressionCCITT3}
```
public static final int CompressionCCITT3
```


Указывает схему сжатия CCITT3. Может быть передан кодировщику TIFF в качестве параметра, относящегося к категории сжатие.

### CompressionCCITT4 {#CompressionCCITT4}
```
public static final int CompressionCCITT4
```


Указывает схему сжатия CCITT4. Может быть передан кодировщику TIFF в качестве параметра, относящегося к категории сжатие.

### CompressionRle {#CompressionRle}
```
public static final int CompressionRle
```


Указывает схему сжатия RLE. Может быть передан кодировщику TIFF в качестве параметра, относящегося к категории сжатие.

### CompressionNone {#CompressionNone}
```
public static final int CompressionNone
```


Указывает отсутствие сжатия. Может быть передан кодировщику TIFF в качестве параметра, относящегося к категории сжатие.

### ScanMethodInterlaced {#ScanMethodInterlaced}
```
public static final int ScanMethodInterlaced
```


Не используется в GDI+ версии 1.0.

### ScanMethodNonInterlaced {#ScanMethodNonInterlaced}
```
public static final int ScanMethodNonInterlaced
```


Не используется в GDI+ версии 1.0.

### VersionGif87 {#VersionGif87}
```
public static final int VersionGif87
```


Не используется в GDI+ версии 1.0.

### VersionGif89 {#VersionGif89}
```
public static final int VersionGif89
```


Не используется в GDI+ версии 1.0.

### RenderProgressive {#RenderProgressive}
```
public static final int RenderProgressive
```


Не используется в GDI+ версии 1.0.

### RenderNonProgressive {#RenderNonProgressive}
```
public static final int RenderNonProgressive
```


Не используется в GDI+ версии 1.0.

### TransformRotate90 {#TransformRotate90}
```
public static final int TransformRotate90
```


Указывает, что изображение должно быть повернуто по часовой стрелке на 90 градусов вокруг своего центра. Может быть передан кодировщику JPEG в качестве параметра, относящегося к категории трансформация.

### TransformRotate180 {#TransformRotate180}
```
public static final int TransformRotate180
```


Указывает, что изображение должно быть повернуто на 180 градусов вокруг своего центра. Может быть передан кодировщику JPEG в качестве параметра, относящегося к категории трансформация.

### TransformRotate270 {#TransformRotate270}
```
public static final int TransformRotate270
```


Указывает, что изображение должно быть повернуто по часовой стрелке на 270 градусов вокруг своего центра. Может быть передан кодировщику JPEG в качестве параметра, относящегося к категории трансформация.

### TransformFlipHorizontal {#TransformFlipHorizontal}
```
public static final int TransformFlipHorizontal
```


Указывает, что изображение должно быть отражено по горизонтали (относительно вертикальной оси). Может быть передан кодировщику JPEG в качестве параметра, относящегося к категории трансформация.

### TransformFlipVertical {#TransformFlipVertical}
```
public static final int TransformFlipVertical
```


Указывает, что изображение должно быть отражено по вертикали (относительно горизонтальной оси). Может быть передан кодировщику JPEG в качестве параметра, относящегося к категории трансформация.

### MultiFrame {#MultiFrame}
```
public static final int MultiFrame
```


Указывает, что у изображения более одного кадра (страницы). Может быть передан кодировщику TIFF в качестве параметра, относящегося к категории флагов сохранения.

### LastFrame {#LastFrame}
```
public static final int LastFrame
```


Указывает последний кадр в многокадровом изображении. Может быть передан кодировщику TIFF в качестве параметра, относящегося к категории флагов сохранения.

### Flush {#Flush}
```
public static final int Flush
```


Указывает, что многокадровый файл или поток должны быть закрыты. Может быть передан кодировщику TIFF в качестве параметра, относящегося к категории флагов сохранения.

### FrameDimensionTime {#FrameDimensionTime}
```
public static final int FrameDimensionTime
```


Не используется в GDI+ версии 1.0.

### FrameDimensionResolution {#FrameDimensionResolution}
```
public static final int FrameDimensionResolution
```


Не используется в GDI+ версии 1.0.

### FrameDimensionPage {#FrameDimensionPage}
```
public static final int FrameDimensionPage
```


Указывает, что кадр должен быть добавлен к размеру страницы изображения. Может быть передан кодировщику TIFF в качестве параметра, относящегося к категории флагов сохранения.

