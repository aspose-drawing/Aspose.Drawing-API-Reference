---
title: PageSettings
second_title: Référence de l'API Aspose.Drawing pour Java
description: Spécifie les paramètres qui s'appliquent à une seule page imprimée.
type: docs
weight: 10
url: /fr/java/com.aspose.drawing.printing/pagesettings/
---
**Inheritance:**
java.lang.Object
```
public class PageSettings
```

Spécifie les paramètres qui s'appliquent à une seule page imprimée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PageSettings()](#PageSettings--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Obtient la taille de la page, en tenant compte de l'orientation de la page spécifiée par la propriété [PageSettings](../../com.aspose.drawing.printing/pagesettings). |
| [getHardMarginX()](#getHardMarginX--) | Obtient la coordonnée x, en centièmes de pouce, de la marge fixe à gauche de la page. |
| [getHardMarginY()](#getHardMarginY--) | Obtient la coordonnée y, en centièmes de pouce, de la marge fixe en haut de la page. |
| [getPrinterResolution()](#getPrinterResolution--) | Obtient la résolution de l'imprimante pour la page. |
### PageSettings() {#PageSettings--}
```
public PageSettings()
```


### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Obtient la taille de la page, en tenant compte de l'orientation de la page spécifiée par la propriété [PageSettings](../../com.aspose.drawing.printing/pagesettings).

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the length and width, in hundredths of an inch, of the page.
### getHardMarginX() {#getHardMarginX--}
```
public final float getHardMarginX()
```


Obtient la coordonnée x, en centièmes de pouce, de la marge fixe à gauche de la page.

**Returns:**
float - La coordonnée x, en centièmes de pouce, de la marge fixe à gauche.
### getHardMarginY() {#getHardMarginY--}
```
public final float getHardMarginY()
```


Obtient la coordonnée y, en centièmes de pouce, de la marge fixe en haut de la page.

**Returns:**
float - La coordonnée y, en centièmes de pouce, de la marge fixe en haut de la page.
### getPrinterResolution() {#getPrinterResolution--}
```
public final PrinterResolution getPrinterResolution()
```


Obtient la résolution de l'imprimante pour la page.

**Returns:**
[PrinterResolution](../../com.aspose.drawing.printing/printerresolution) - A `PrinterResolution`([.getPrinterResolution](../../null/\#getPrinterResolution)) that specifies the printer resolution for the page. The default is the printer's default resolution.
