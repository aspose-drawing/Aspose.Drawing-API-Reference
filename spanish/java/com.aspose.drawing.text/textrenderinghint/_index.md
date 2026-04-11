---
title: TextRenderingHint
second_title: Referencia de la API de Aspose.Drawing para Java
description: Especifica la calidad del renderizado de texto.
type: docs
weight: 14
url: /es/java/com.aspose.drawing.text/textrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextRenderingHint extends System.Enum
```

Especifica la calidad del renderizado de texto.
## Campos

| Campo | Descripción |
| --- | --- |
| [SystemDefault](#SystemDefault) | Cada carácter se dibuja usando su mapa de bits de glifo, con la sugerencia de renderizado predeterminada del sistema. |
| [SingleBitPerPixelGridFit](#SingleBitPerPixelGridFit) | Cada carácter se dibuja usando su mapa de bits de glifo. |
| [SingleBitPerPixel](#SingleBitPerPixel) | Cada carácter se dibuja usando su mapa de bits de glifo. |
| [AntiAliasGridFit](#AntiAliasGridFit) | Cada carácter se dibuja usando su mapa de bits de glifo antialiasado con hinting. |
| [AntiAlias](#AntiAlias) | Cada carácter se dibuja usando su mapa de bits de glifo antialiasado sin hinting. |
| [ClearTypeGridFit](#ClearTypeGridFit) | Cada carácter se dibuja usando su mapa de bits de glifo ClearType con hinting. |
### SystemDefault {#SystemDefault}
```
public static final int SystemDefault
```


Cada carácter se dibuja usando su mapa de bits de glifo, con la sugerencia de renderizado predeterminada del sistema. El texto se dibujará usando cualquier configuración de suavizado de fuentes que el usuario haya seleccionado para el sistema.

### SingleBitPerPixelGridFit {#SingleBitPerPixelGridFit}
```
public static final int SingleBitPerPixelGridFit
```


Cada carácter se dibuja usando su mapa de bits de glifo. Se utiliza hinting para mejorar la apariencia de los caracteres en tallos y curvaturas.

### SingleBitPerPixel {#SingleBitPerPixel}
```
public static final int SingleBitPerPixel
```


Cada carácter se dibuja usando su mapa de bits de glifo. No se usa hinting.

### AntiAliasGridFit {#AntiAliasGridFit}
```
public static final int AntiAliasGridFit
```


Cada carácter se dibuja usando su mapa de bits de glifo antialiasado con hinting. Mucha mejor calidad debido al antialiasing, pero con un mayor costo de rendimiento.

### AntiAlias {#AntiAlias}
```
public static final int AntiAlias
```


Cada carácter se dibuja usando su mapa de bits de glifo antialiasado sin hinting. Mejor calidad debido al antialiasing. Las diferencias de ancho de los trazos pueden ser notables porque el hinting está desactivado.

### ClearTypeGridFit {#ClearTypeGridFit}
```
public static final int ClearTypeGridFit
```


Cada carácter se dibuja usando su mapa de bits de glifo ClearType con hinting. La configuración de mayor calidad. Se usa para aprovechar las características de fuente ClearType.

