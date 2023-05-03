---
title: FontFamily
second_title: Referencia de Aspose.Drawing para .NET API
description: Define un grupo de tipos de letra que tienen un diseño básico similar y ciertas variaciones en los estilos. Esta clase no se puede heredar.
type: docs
weight: 510
url: /es/net/system.drawing/fontfamily/
---
## FontFamily class

Define un grupo de tipos de letra que tienen un diseño básico similar y ciertas variaciones en los estilos. Esta clase no se puede heredar.

```csharp
public sealed class FontFamily : IDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FontFamily](fontfamily#constructor)(string) | Inicializa una nueva instancia del[`FontFamily`](../fontfamily) clase con el nombre especificado. |
| [FontFamily](fontfamily#constructor_1)(string, FontCollection) | Inicializa una nueva instancia del[`FontFamily`](../fontfamily) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [GenericMonospace](../../system.drawing/fontfamily/genericmonospace) { get; } | Obtiene un monoespacio genéricoFontFamily . |
| static [GenericSansSerif](../../system.drawing/fontfamily/genericsansserif) { get; } | Obtiene un sans serif genéricoFontFamily objeto. |
| static [GenericSerif](../../system.drawing/fontfamily/genericserif) { get; } | Obtiene una serifa genéricaFontFamily . |
| [Name](../../system.drawing/fontfamily/name) { get; } | Obtiene el nombre de esteFontFamily . |
| static [Families](../../system.drawing/fontfamily/families) { get; } | Obtiene una matriz que contiene todos losFontFamily objetos asociados con el contexto gráfico actual. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../system.drawing/fontfamily/dispose)() | Libera todos los recursos utilizados por esteFontFamily . |
| override [Equals](../../system.drawing/fontfamily/equals)(object) | Indica si el objeto especificado es unFontFamily y es identico a esteFontFamily . |
| [GetCellAscent](../../system.drawing/fontfamily/getcellascent)(FontStyle) | Devuelve el ascenso de celda, en unidades de diseño, delFontFamily del estilo especificado. |
| [GetCellDescent](../../system.drawing/fontfamily/getcelldescent)(FontStyle) | Devuelve la descendencia de celda, en unidades de diseño, delFontFamily del estilo especificado. |
| [GetEmHeight](../../system.drawing/fontfamily/getemheight)(FontStyle) | Obtiene la altura, en unidades de diseño de fuente, del cuadrado EM para el estilo especificado. |
| override [GetHashCode](../../system.drawing/fontfamily/gethashcode)() | Obtiene un código hash para estoFontFamily . |
| [GetLineSpacing](../../system.drawing/fontfamily/getlinespacing)(FontStyle) | Devuelve el interlineado, en unidades de diseño, delFontFamily del estilo especificado. El interlineado es la distancia vertical entre las líneas base de dos líneas consecutivas de texto. |
| [GetName](../../system.drawing/fontfamily/getname)(int) | Devuelve el nombre, en el idioma especificado, de esteFontFamily . |
| [IsStyleAvailable](../../system.drawing/fontfamily/isstyleavailable)(FontStyle) | Indica si el especificadoFontStyle la enumeración está disponible. |

### Ver también

* espacio de nombres [System.Drawing](../../system.drawing)
* asamblea [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->