---
title: "PdfAnnotationWatermarkOptions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt opties voor het toevoegen van een watermerk voor bij het toevoegen van een annotatiewatermerk aan een pdf-document."
type: docs
weight: 28
url: /nl/java/com.groupdocs.watermark.options/pdfannotationwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfAnnotationWatermarkOptions extends PdfWatermarkOptions
```

Stelt opties voor het toevoegen van een watermerk voor bij het toevoegen van een annotatiewatermerk aan een pdf-document.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

Het volgende voorbeeld toont hoe u een afbeeldingannotatie-watermerk aan een PDF-document kunt toevoegen.
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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PdfAnnotationWatermarkOptions()](#PdfAnnotationWatermarkOptions--) | Initialiseert een nieuw exemplaar van de `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)` klasse. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Haalt de pagina‑index op om het watermerk toe te voegen. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Stelt de pagina‑index in om het watermerk toe te voegen. |
|
|  | [getPrintOnly()](#getPrintOnly--) | Haal de waarde op die aangeeft of annotatie wordt afgedrukt, maar niet wordt weergegeven in een pdf-viewer. |
|
|  | [setPrintOnly(boolean value)](#setPrintOnly-boolean-) | Stelt de waarde in die aangeeft of annotatie wordt afgedrukt, maar niet wordt weergegeven in een pdf-viewer. |
|
### PdfAnnotationWatermarkOptions() {#PdfAnnotationWatermarkOptions--}
```
public PdfAnnotationWatermarkOptions()
```


Initialiseert een nieuw exemplaar van de `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)` klasse.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


Haalt de pagina‑index op om het watermerk toe te voegen.


**Returns:**
int - De pagina‑index om het watermerk toe te voegen.

<br />

*** ** * ** ***

-1 means all pages.

<br />


### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


Stelt de pagina‑index in om het watermerk toe te voegen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De pagina‑index om het watermerk toe te voegen. |

<br />

*** ** * ** ***

-1 means all pages.

<br />

|

### getPrintOnly() {#getPrintOnly--}
```
public final boolean getPrintOnly()
```


Haal de waarde op die aangeeft of annotatie wordt afgedrukt, maar niet wordt weergegeven in een pdf-viewer.


**Returns:**
boolean - De waarde die aangeeft of annotatie wordt afgedrukt, maar niet wordt weergegeven in een pdf-viewer.

### setPrintOnly(boolean value) {#setPrintOnly-boolean-}
```
public final void setPrintOnly(boolean value)
```


Stelt de waarde in die aangeeft of annotatie wordt afgedrukt, maar niet wordt weergegeven in een pdf-viewer.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | De waarde die aangeeft of annotatie wordt afgedrukt, maar niet wordt weergegeven in een pdf-viewer. |
|

