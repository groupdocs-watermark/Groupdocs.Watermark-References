---
title: "PdfAnnotationWatermarkOptions"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane d'annotation à un document PDF."
type: docs
weight: 28
url: /fr/java/com.groupdocs.watermark.options/pdfannotationwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfAnnotationWatermarkOptions extends PdfWatermarkOptions
```

Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane d'annotation à un document PDF.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

L'exemple suivant montre comment ajouter un filigrane d'annotation d'image à un document PDF.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("D:\\icon.png");
>
>    PdfAnnotationWatermarkOptions options = new PdfAnnotationWatermarkOptions();
>    options.setPageIndex(-1); // default - all pages
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.pdf");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PdfAnnotationWatermarkOptions()](#PdfAnnotationWatermarkOptions--) | Initialise une nouvelle instance de la classe `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)`. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Obtient l'index de page où ajouter le filigrane. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Définit l'index de page où ajouter le filigrane. |
|
|  | [getPrintOnly()](#getPrintOnly--) | Obtient la valeur indiquant si l'annotation sera imprimée, mais non affichée dans l'application de visualisation PDF. |
|
|  | [setPrintOnly(boolean value)](#setPrintOnly-boolean-) | Définit la valeur indiquant si l'annotation sera imprimée, mais non affichée dans l'application de visualisation PDF. |
|
### PdfAnnotationWatermarkOptions() {#PdfAnnotationWatermarkOptions--}
```
public PdfAnnotationWatermarkOptions()
```


Initialise une nouvelle instance de la classe `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)`.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


Obtient l'index de page où ajouter le filigrane.


**Returns:**
int - L'index de page où ajouter le filigrane.

<br />

*** ** * ** ***

-1 means all pages.

<br />


### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


Définit l'index de page où ajouter le filigrane.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | L'index de page où ajouter le filigrane. |

<br />

*** ** * ** ***

-1 means all pages.

<br />

|

### getPrintOnly() {#getPrintOnly--}
```
public final boolean getPrintOnly()
```


Obtient la valeur indiquant si l'annotation sera imprimée, mais non affichée dans l'application de visualisation PDF.


**Returns:**
booléen - La valeur indiquant si l'annotation sera imprimée, mais non affichée dans l'application de visualisation PDF.

### setPrintOnly(boolean value) {#setPrintOnly-boolean-}
```
public final void setPrintOnly(boolean value)
```


Définit la valeur indiquant si l'annotation sera imprimée, mais non affichée dans l'application de visualisation PDF.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | La valeur indiquant si l'annotation sera imprimée, mais non affichée dans l'application de visualisation PDF. |
|

