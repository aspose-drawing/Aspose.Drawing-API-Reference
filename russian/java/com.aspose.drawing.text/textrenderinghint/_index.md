---
title: TextRenderingHint
second_title: Справочник API Aspose.Drawing для Java
description: Указывает качество рендеринга текста.
type: docs
weight: 14
url: /ru/java/com.aspose.drawing.text/textrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextRenderingHint extends System.Enum
```

Указывает качество рендеринга текста.
## Поля

| Поле | Описание |
| --- | --- |
| [SystemDefault](#SystemDefault) | Каждый символ отрисовывается с использованием его растрового образа глифа, с системным режимом рендеринга по умолчанию. |
| [SingleBitPerPixelGridFit](#SingleBitPerPixelGridFit) | Каждый символ отрисовывается с использованием его растрового образа глифа. |
| [SingleBitPerPixel](#SingleBitPerPixel) | Каждый символ отрисовывается с использованием его растрового образа глифа. |
| [AntiAliasGridFit](#AntiAliasGridFit) | Каждый символ отрисовывается с использованием его сглаженного растрового образа глифа с хинтингом. |
| [AntiAlias](#AntiAlias) | Каждый символ отрисовывается с использованием его сглаженного растрового образа глифа без хинтинга. |
| [ClearTypeGridFit](#ClearTypeGridFit) | Каждый символ отрисовывается с использованием его растрового образа глифа ClearType с хинтингом. |
### SystemDefault {#SystemDefault}
```
public static final int SystemDefault
```


Каждый символ отрисовывается с использованием его растрового образа глифа, с системным режимом рендеринга по умолчанию. Текст будет отрисован с учётом любых настроек сглаживания шрифтов, выбранных пользователем для системы.

### SingleBitPerPixelGridFit {#SingleBitPerPixelGridFit}
```
public static final int SingleBitPerPixelGridFit
```


Каждый символ отрисовывается с использованием его растрового образа глифа. Хинтинг используется для улучшения внешнего вида символов на штрихах и кривизне.

### SingleBitPerPixel {#SingleBitPerPixel}
```
public static final int SingleBitPerPixel
```


Каждый символ отрисовывается с использованием его растрового изображения глифа. Хинтинг не используется.

### AntiAliasGridFit {#AntiAliasGridFit}
```
public static final int AntiAliasGridFit
```


Каждый символ отрисовывается с использованием его сглаженного растрового изображения глифа с хинтингом. Качество значительно лучше благодаря сглаживанию, но за счёт более высокой нагрузки на производительность.

### AntiAlias {#AntiAlias}
```
public static final int AntiAlias
```


Каждый символ отрисовывается с использованием его сглаженного растрового изображения глифа без хинтинга. Качество лучше благодаря сглаживанию. Различия в ширине штрихов могут быть заметны, поскольку хинтинг отключён.

### ClearTypeGridFit {#ClearTypeGridFit}
```
public static final int ClearTypeGridFit
```


Каждый символ отрисовывается с использованием его растрового изображения глифа ClearType с хинтингом. Наивысшая настройка качества. Используется для получения преимуществ функций шрифтов ClearType.

