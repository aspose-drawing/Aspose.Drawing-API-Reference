---
title: EmfType
second_title: Справочник API Aspose.Drawing для Java
description: Указывает тип записей, размещённых в файле Enhanced Metafile (EMF).
type: docs
weight: 18
url: /ru/java/com.aspose.drawing.imaging/emftype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfType extends System.Enum
```

Указывает тип записей, размещённых в файле Enhanced Metafile (EMF). Это перечисление используется несколькими конструкторами класса [Metafile](../../com.aspose.drawing.imaging/metafile).
## Поля

| Поле | Описание |
| --- | --- |
| [EmfOnly](#EmfOnly) | Указывает, что все записи в метафайле являются EMF‑записями, которые могут отображаться с помощью GDI или GDI+. |
| [EmfPlusOnly](#EmfPlusOnly) | Указывает, что все записи в метафайле являются EMF+‑записями, которые могут отображаться с помощью GDI+, но не GDI. |
| [EmfPlusDual](#EmfPlusDual) | Указывает, что все EMF+‑записи в метафайле связаны с альтернативной EMF‑записью. |
### EmfOnly {#EmfOnly}
```
public static final int EmfOnly
```


Указывает, что все записи в метафайле являются EMF‑записями, которые могут отображаться с помощью GDI или GDI+.

### EmfPlusOnly {#EmfPlusOnly}
```
public static final int EmfPlusOnly
```


Указывает, что все записи в метафайле являются EMF+‑записями, которые могут отображаться с помощью GDI+, но не GDI.

### EmfPlusDual {#EmfPlusDual}
```
public static final int EmfPlusDual
```


Указывает, что все EMF+‑записи в метафайле связаны с альтернативной EMF‑записью. Метафайлы типа `EmfType.EmfPlusDual` могут отображаться с помощью GDI или GDI+.

