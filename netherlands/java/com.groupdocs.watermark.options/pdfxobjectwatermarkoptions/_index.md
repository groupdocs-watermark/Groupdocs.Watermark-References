---
title: "PdfXObjectWatermarkOptions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt opties voor het toevoegen van een watermerk voor bij het toevoegen van een XObject-watermerk aan een pdf-document."
type: docs
weight: 34
url: /nl/java/com.groupdocs.watermark.options/pdfxobjectwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfXObjectWatermarkOptions extends PdfWatermarkOptions
```

Stelt opties voor het toevoegen van een watermerk voor bij het toevoegen van een XObject-watermerk aan een pdf-document.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

Het volgende voorbeeld toont hoe een watermerk toe te voegen aan een specifieke pagina van een pdf-document.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\doc.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("C:\\watermark.png");
>
>    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
>    options.setPageIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("C:\\watermarked_doc.pdf");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PdfXObjectWatermarkOptions()](#PdfXObjectWatermarkOptions--) | Initialiseert een nieuw exemplaar van de klasse `[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)`. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Haalt de pagina‑index op om het watermerk toe te voegen. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Stelt de pagina‑index in om het watermerk toe te voegen. |
|
### PdfXObjectWatermarkOptions() {#PdfXObjectWatermarkOptions--}
```
public PdfXObjectWatermarkOptions()
```


Initialiseert een nieuw exemplaar van de klasse `[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)`.


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

