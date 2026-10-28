---
title: "PdfArtifactWatermarkOptions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt opties voor het toevoegen van een watermerk voor bij het toevoegen van een artefactwatermerk aan een pdf-document."
type: docs
weight: 29
url: /nl/java/com.groupdocs.watermark.options/pdfartifactwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfArtifactWatermarkOptions extends PdfWatermarkOptions
```

Stelt opties voor het toevoegen van een watermerk voor bij het toevoegen van een artefactwatermerk aan een pdf-document.

**Leran more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

Het volgende voorbeeld toont hoe een afbeelding artefact watermerk toe te voegen aan een PDF-document.
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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PdfArtifactWatermarkOptions()](#PdfArtifactWatermarkOptions--) | Initialiseert een nieuw exemplaar van de klasse `[PdfArtifactWatermarkOptions](../../com.groupdocs.watermark.options/pdfartifactwatermarkoptions)`. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Haalt de pagina‑index op om het watermerk toe te voegen. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Stelt de pagina‑index in om het watermerk toe te voegen. |
|
### PdfArtifactWatermarkOptions() {#PdfArtifactWatermarkOptions--}
```
public PdfArtifactWatermarkOptions()
```


Initialiseert een nieuw exemplaar van de klasse `[PdfArtifactWatermarkOptions](../../com.groupdocs.watermark.options/pdfartifactwatermarkoptions)`.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


Haalt de pagina‑index op om het watermerk toe te voegen.


**Returns:**
int - De pagina‑index om het watermerk toe te voegen.

### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


Stelt de pagina‑index in om het watermerk toe te voegen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De pagina‑index om het watermerk toe te voegen. |
|

