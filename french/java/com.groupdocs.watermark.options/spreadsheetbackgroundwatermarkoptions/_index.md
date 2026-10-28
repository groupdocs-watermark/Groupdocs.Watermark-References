---
title: "SpreadsheetBackgroundWatermarkOptions"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les options lors de l'ajout du filigrane en tant qu'arrière-plan à une feuille de calcul Spreadsheet."
type: docs
weight: 49
url: /fr/java/com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public final class SpreadsheetBackgroundWatermarkOptions extends SpreadsheetWatermarkOptions
```

Représente les options lors de l'ajout du filigrane en tant qu'arrière-plan à une feuille de calcul Spreadsheet.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

L'exemple suivant montre comment ajouter un filigrane texte à une feuille de calcul Excel en tant qu'arrière-plan.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\Documents\\test.xlsx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36));
>
>    SpreadsheetBackgroundWatermarkOptions options = new SpreadsheetBackgroundWatermarkOptions();
>    options.setWorksheetIndex(-1); // default
>    options.setBackgroundWidth(800);
>    options.setBackgroundHeight(600);
>    
>    watermarker.save("C:\\Documents\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [SpreadsheetBackgroundWatermarkOptions()](#SpreadsheetBackgroundWatermarkOptions--) | Initialise une nouvelle instance de la classe `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)`. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Obtenez l'index de la feuille de calcul où ajouter le filigrane. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Définit l'indice de la feuille de calcul à laquelle ajouter le filigrane. |
|
|  | [getBackgroundWidth()](#getBackgroundWidth--) | Obtenez la largeur souhaitée de l'image d'arrière-plan en pixels. |
|
|  | [setBackgroundWidth(int value)](#setBackgroundWidth-int-) | Définit la largeur souhaitée de l'image d'arrière-plan en pixels. |
|
|  | [getBackgroundHeight()](#getBackgroundHeight--) | Obtient ou définit la hauteur souhaitée de l'image d'arrière-plan en pixels. |
|
|  | [setBackgroundHeight(int value)](#setBackgroundHeight-int-) | Obtient ou définit la hauteur souhaitée de l'image d'arrière-plan en pixels. |
|
### SpreadsheetBackgroundWatermarkOptions() {#SpreadsheetBackgroundWatermarkOptions--}
```
public SpreadsheetBackgroundWatermarkOptions()
```


Initialise une nouvelle instance de la classe `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)`.


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Obtenez l'index de la feuille de calcul où ajouter le filigrane.

-1 means every worksheet.


**Returns:**
int - L'indice de la feuille de calcul à laquelle ajouter le filigrane.

### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Définit l'indice de la feuille de calcul à laquelle ajouter le filigrane.

-1 means every worksheet.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | L'indice de la feuille de calcul à laquelle ajouter le filigrane. |
|

### getBackgroundWidth() {#getBackgroundWidth--}
```
public final int getBackgroundWidth()
```


Obtenez la largeur souhaitée de l'image d'arrière-plan en pixels.


**Returns:**
int - La largeur souhaitée de l'image d'arrière-plan en pixels.

### setBackgroundWidth(int value) {#setBackgroundWidth-int-}
```
public final void setBackgroundWidth(int value)
```


Définit la largeur souhaitée de l'image d'arrière-plan en pixels.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | La largeur souhaitée de l'image d'arrière-plan en pixels. |
|

### getBackgroundHeight() {#getBackgroundHeight--}
```
public final int getBackgroundHeight()
```


Obtient ou définit la hauteur souhaitée de l'image d'arrière-plan en pixels.


**Returns:**
int - La hauteur souhaitée de l'image d'arrière-plan en pixels.

### setBackgroundHeight(int value) {#setBackgroundHeight-int-}
```
public final void setBackgroundHeight(int value)
```


Obtient ou définit la hauteur souhaitée de l'image d'arrière-plan en pixels.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | La hauteur souhaitée de l'image d'arrière-plan en pixels. |
|

