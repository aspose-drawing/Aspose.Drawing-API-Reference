---
title: PrintPageEventArgs
second_title: Référence de l'API Aspose.Drawing pour Java
description: Fournit des données pour l'événement EPrintDocument.PrintPage.
type: docs
weight: 13
url: /fr/java/com.aspose.drawing.printing/printpageeventargs/
---
**Inheritance:**
java.lang.Object
```
public class PrintPageEventArgs
```

Fournit des données pour l'événement `E:PrintDocument.PrintPage`.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PrintPageEventArgs()](#PrintPageEventArgs--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getGraphics()](#getGraphics--) | Obtient le `Graphics`([.getGraphics](../../null/\#getGraphics)) utilisé pour peindre la page. |
| [hasMorePages()](#hasMorePages--) | Obtient une valeur indiquant si une page supplémentaire doit être imprimée. |
| [setMorePages(boolean value)](#setMorePages-boolean-) | Définit une valeur indiquant si une page supplémentaire doit être imprimée. |
| [getPageSettings()](#getPageSettings--) | Obtient les paramètres de page pour la page actuelle. |
### PrintPageEventArgs() {#PrintPageEventArgs--}
```
public PrintPageEventArgs()
```


### getGraphics() {#getGraphics--}
```
public final Graphics getGraphics()
```


Obtient le `Graphics`([.getGraphics](../../null/\#getGraphics)) utilisé pour peindre la page.

**Returns:**
[Graphics](../../com.aspose.drawing/graphics) - The `Graphics`([.getGraphics](../../null/\#getGraphics)) used to paint the page.
### hasMorePages() {#hasMorePages--}
```
public final boolean hasMorePages()
```


Obtient une valeur indiquant si une page supplémentaire doit être imprimée.

**Returns:**
booléen - `true` si une page supplémentaire doit être imprimée ; sinon, false. La valeur par défaut est `false`.
### setMorePages(boolean value) {#setMorePages-boolean-}
```
public final void setMorePages(boolean value)
```


Définit une valeur indiquant si une page supplémentaire doit être imprimée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean | une valeur indiquant si une page supplémentaire doit être imprimée. |

### getPageSettings() {#getPageSettings--}
```
public final PageSettings getPageSettings()
```


Obtient les paramètres de page pour la page actuelle.

**Returns:**
[PageSettings](../../com.aspose.drawing.printing/pagesettings) - The page settings for the current page.
