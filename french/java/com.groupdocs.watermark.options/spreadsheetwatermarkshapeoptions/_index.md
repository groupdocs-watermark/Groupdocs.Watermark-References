---
title: "SpreadsheetWatermarkShapeOptions"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les options lors de l'ajout d'un filigrane forme à une feuille de calcul Spreadsheet."
type: docs
weight: 60
url: /fr/java/com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkShapeOptions extends SpreadsheetWatermarkBaseOptions
```

Représente les options lors de l'ajout d'un filigrane forme à une feuille de calcul Spreadsheet.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

L'exemple suivant montre comment ajouter un filigrane à une feuille de calcul particulière d'un document Excel.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    SpreadsheetWatermarkShapeOptions options = new SpreadsheetWatermarkShapeOptions();
>    options.setWorksheetIndex(0);
>    
>    watermarker.save("D:\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [SpreadsheetWatermarkShapeOptions()](#SpreadsheetWatermarkShapeOptions--) | Initialise une nouvelle instance de la classe `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)`. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Obtient l'indice de la feuille de calcul à laquelle ajouter le filigrane. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Définit l'indice de la feuille de calcul à laquelle ajouter le filigrane. |
|
|  | [getEffects()](#getEffects--) | Obtient une valeur de `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` ou `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` pour les effets qui doivent être appliqués au filigrane. |
|
|  | [setEffects(ISpreadsheetWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-) | Obtient ou définit une valeur de `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` ou `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` pour les effets qui doivent être appliqués au filigrane. |
|
### SpreadsheetWatermarkShapeOptions() {#SpreadsheetWatermarkShapeOptions--}
```
public SpreadsheetWatermarkShapeOptions()
```


Initialise une nouvelle instance de la classe `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)`.


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Obtient l'indice de la feuille de calcul à laquelle ajouter le filigrane.


**Returns:**
int - L'indice de la feuille de calcul à laquelle ajouter le filigrane.

<br />

*** ** * ** ***

-1 means every worksheet.

<br />


### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Définit l'indice de la feuille de calcul à laquelle ajouter le filigrane.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | L'indice de la feuille de calcul à laquelle ajouter le filigrane. |

<br />

*** ** * ** ***

-1 means every worksheet.

<br />

|

### getEffects() {#getEffects--}
```
public final ISpreadsheetWatermarkEffects getEffects()
```


Obtient une valeur de `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` ou `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` pour les effets qui doivent être appliqués au filigrane.


**Returns:**
[ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) - The `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` or `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` for effects that should be applied to the watermark.

### setEffects(ISpreadsheetWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void setEffects(ISpreadsheetWatermarkEffects value)
```


Obtient ou définit une valeur de `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` ou `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` pour les effets qui doivent être appliqués au filigrane.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) | Le `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` ou `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` pour les effets qui doivent être appliqués au filigrane. |
|

