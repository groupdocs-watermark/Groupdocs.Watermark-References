---
title: "PdfArtifactWatermarkOptions"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane d'artefact à un document PDF."
type: docs
weight: 29
url: /fr/java/com.groupdocs.watermark.options/pdfartifactwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfArtifactWatermarkOptions extends PdfWatermarkOptions
```

Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane d'artefact à un document PDF.

**Leran more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

L'exemple suivant montre comment ajouter un filigrane d'image d'artefact à un document PDF.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("D:\\icon.png");
>
>    PdfArtifactWatermarkOptions options = new PdfArtifactWatermarkOptions();
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
|  | [PdfArtifactWatermarkOptions()](#PdfArtifactWatermarkOptions--) | Initialise une nouvelle instance de la classe `[PdfArtifactWatermarkOptions](../../com.groupdocs.watermark.options/pdfartifactwatermarkoptions)`. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Obtient l'index de page où ajouter le filigrane. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Définit l'index de page où ajouter le filigrane. |
|
### PdfArtifactWatermarkOptions() {#PdfArtifactWatermarkOptions--}
```
public PdfArtifactWatermarkOptions()
```


Initialise une nouvelle instance de la classe `[PdfArtifactWatermarkOptions](../../com.groupdocs.watermark.options/pdfartifactwatermarkoptions)`.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


Obtient l'index de page où ajouter le filigrane.


**Returns:**
int - L'index de page où ajouter le filigrane.

### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


Définit l'index de page où ajouter le filigrane.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | L'index de page où ajouter le filigrane. |
|

