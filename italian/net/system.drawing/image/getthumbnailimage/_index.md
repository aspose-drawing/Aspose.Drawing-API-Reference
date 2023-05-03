---
title: GetThumbnailImage
second_title: Aspose.Drawing per .NET API Reference
description: Restituisce una miniatura per questoImage .
type: docs
weight: 230
url: /it/net/system.drawing/image/getthumbnailimage/
---
## Image.GetThumbnailImage method

Restituisce una miniatura per questoImage .

```csharp
public Image GetThumbnailImage(int thumbWidth, int thumbHeight, GetThumbnailImageAbort callback, 
    IntPtr callbackData)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| thumbWidth | Int32 | La larghezza, in pixel, dell'immagine in miniatura richiesta. |
| thumbHeight | Int32 | L'altezza, in pixel, dell'immagine in miniatura richiesta. |
| callback | GetThumbnailImageAbort | UN[`GetThumbnailImageAbort`](../../image.getthumbnailimageabort) delegare. Nota È necessario creare un delegato e passare un riferimento al delegato come*callback* parametro, ma il delegato non viene utilizzato. |
| callbackData | IntPtr | Deve essereZero . |

### Valore di ritorno

AnImage che rappresenta la miniatura.

### Guarda anche

* delegate [GetThumbnailImageAbort](../../image.getthumbnailimageabort)
* class [Image](../../image)
* spazio dei nomi [System.Drawing](../../image)
* assemblea [Aspose.Drawing](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->