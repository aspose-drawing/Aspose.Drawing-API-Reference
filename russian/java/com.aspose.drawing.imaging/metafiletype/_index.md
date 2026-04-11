---
title: MetafileType
second_title: Справочник API Aspose.Drawing для Java
description: Указывает типы метафайлов.
type: docs
weight: 33
url: /ru/java/com.aspose.drawing.imaging/metafiletype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MetafileType extends System.Enum
```

Указывает типы метафайлов.
## Поля

| Поле | Описание |
| --- | --- |
| [Invalid](#Invalid) | Указывает формат метафайла, не распознаваемый в GDI+. |
| [Wmf](#Wmf) | Указывает файл WMF (Windows Metafile). |
| [WmfPlaceable](#WmfPlaceable) | Указывает файл WMF (Windows Metafile), имеющий заголовок размещаемого метафайла в начале. |
| [Emf](#Emf) | Указывает файл Enhanced Metafile (EMF). |
| [EmfPlusOnly](#EmfPlusOnly) | Указывает файл EMF+. |
| [EmfPlusDual](#EmfPlusDual) | Указывает файл EMF+ Dual. |
### Invalid {#Invalid}
```
public static final int Invalid
```


Указывает формат метафайла, не распознаваемый в GDI+.

### Wmf {#Wmf}
```
public static final int Wmf
```


Указывает файл WMF (Windows Metafile). Такой файл содержит только записи GDI.

### WmfPlaceable {#WmfPlaceable}
```
public static final int WmfPlaceable
```


Указывает файл WMF (Windows Metafile), имеющий заголовок размещаемого метафайла в начале.

### Emf {#Emf}
```
public static final int Emf
```


Указывает файл Enhanced Metafile (EMF). Такой файл содержит только записи GDI.

### EmfPlusOnly {#EmfPlusOnly}
```
public static final int EmfPlusOnly
```


Указывает файл EMF+. Такой файл содержит только записи GDI+ и должен отображаться с использованием GDI+. Отображение записей с помощью GDI может привести к непредсказуемым результатам.

### EmfPlusDual {#EmfPlusDual}
```
public static final int EmfPlusDual
```


Указывает файл EMF+ Dual. Такой файл содержит записи GDI+ вместе с альтернативными записями GDI и может отображаться с использованием как GDI, так и GDI+. Отображение записей с помощью GDI может привести к некоторой потере качества.

