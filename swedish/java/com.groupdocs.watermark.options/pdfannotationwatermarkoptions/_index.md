---
title: "PdfAnnotationWatermarkOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar alternativ för att lägga till vattenstämpel när en annoteringsvattenstämpel läggs till ett PDF-dokument."
type: docs
weight: 28
url: /sv/java/com.groupdocs.watermark.options/pdfannotationwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfAnnotationWatermarkOptions extends PdfWatermarkOptions
```

Representerar alternativ för att lägga till vattenstämpel när en annoteringsvattenstämpel läggs till ett PDF-dokument.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

Följande exempel visar hur man lägger till en bildannoteringsvattenstämpel i ett PDF-dokument.
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


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [PdfAnnotationWatermarkOptions()](#PdfAnnotationWatermarkOptions--) | Initierar en ny instans av klassen `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)`. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Hämtar sidindexet som vattenstämpeln ska läggas till på. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Ställer in sidindexet som vattenstämpeln ska läggas till på. |
|
|  | [getPrintOnly()](#getPrintOnly--) | Hämta värdet som indikerar om annoteringen kommer att skrivas ut, men inte visas i pdf‑visningsprogrammet. |
|
|  | [setPrintOnly(boolean value)](#setPrintOnly-boolean-) | Ställer in värdet som indikerar om annoteringen kommer att skrivas ut, men inte visas i pdf‑visningsprogrammet. |
|
### PdfAnnotationWatermarkOptions() {#PdfAnnotationWatermarkOptions--}
```
public PdfAnnotationWatermarkOptions()
```


Initierar en ny instans av klassen `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)`.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


Hämtar sidindexet som vattenstämpeln ska läggas till på.


**Returns:**
int - Sidindexet som vattenstämpeln ska läggas till på.

<br />

*** ** * ** ***

-1 means all pages.

<br />


### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


Ställer in sidindexet som vattenstämpeln ska läggas till på.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Sidindexet som vattenstämpeln ska läggas till på. |

<br />

*** ** * ** ***

-1 means all pages.

<br />

|

### getPrintOnly() {#getPrintOnly--}
```
public final boolean getPrintOnly()
```


Hämta värdet som indikerar om annoteringen kommer att skrivas ut, men inte visas i pdf‑visningsprogrammet.


**Returns:**
boolean - Värdet som indikerar om annoteringen kommer att skrivas ut, men inte visas i pdf‑visningsprogrammet.

### setPrintOnly(boolean value) {#setPrintOnly-boolean-}
```
public final void setPrintOnly(boolean value)
```


Ställer in värdet som indikerar om annoteringen kommer att skrivas ut, men inte visas i pdf‑visningsprogrammet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | Värdet som indikerar om annoteringen kommer att skrivas ut, men inte visas i pdf‑visningsprogrammet. |
|

