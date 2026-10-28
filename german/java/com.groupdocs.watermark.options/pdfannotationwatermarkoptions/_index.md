---
title: "PdfAnnotationWatermarkOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Optionen zum Hinzufügen von Wasserzeichen beim Hinzufügen eines Annotationswasserzeichens zu einem PDF‑Dokument dar."
type: docs
weight: 28
url: /de/java/com.groupdocs.watermark.options/pdfannotationwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfAnnotationWatermarkOptions extends PdfWatermarkOptions
```

Stellt Optionen zum Hinzufügen von Wasserzeichen beim Hinzufügen eines Annotationswasserzeichens zu einem PDF‑Dokument dar.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

Das folgende Beispiel demonstriert, wie ein Bild-Anmerkungs-Wasserzeichen zu einem PDF-Dokument hinzugefügt wird.
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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PdfAnnotationWatermarkOptions()](#PdfAnnotationWatermarkOptions--) | Initialisiert eine neue Instanz der `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)` Klasse. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Ermittelt den Seitenindex, zu dem das Wasserzeichen hinzugefügt werden soll. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Setzt den Seitenindex, zu dem das Wasserzeichen hinzugefügt werden soll. |
|
|  | [getPrintOnly()](#getPrintOnly--) | Liest den Wert, der angibt, ob die Anmerkung gedruckt, aber nicht in der PDF-Anzeigeanwendung angezeigt wird. |
|
|  | [setPrintOnly(boolean value)](#setPrintOnly-boolean-) | Setzt den Wert, der angibt, ob die Anmerkung gedruckt, aber nicht in der PDF-Anzeigeanwendung angezeigt wird. |
|
### PdfAnnotationWatermarkOptions() {#PdfAnnotationWatermarkOptions--}
```
public PdfAnnotationWatermarkOptions()
```


Initialisiert eine neue Instanz der `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)` Klasse.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


Ermittelt den Seitenindex, zu dem das Wasserzeichen hinzugefügt werden soll.


**Returns:**
int - Der Seitenindex, zu dem das Wasserzeichen hinzugefügt werden soll.

<br />

*** ** * ** ***

-1 means all pages.

<br />


### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


Setzt den Seitenindex, zu dem das Wasserzeichen hinzugefügt werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Der Seitenindex, zu dem das Wasserzeichen hinzugefügt werden soll. |

<br />

*** ** * ** ***

-1 means all pages.

<br />

|

### getPrintOnly() {#getPrintOnly--}
```
public final boolean getPrintOnly()
```


Liest den Wert, der angibt, ob die Anmerkung gedruckt, aber nicht in der PDF-Anzeigeanwendung angezeigt wird.


**Returns:**
boolean - Der Wert, der angibt, ob die Anmerkung gedruckt, aber nicht in der PDF-Anzeigeanwendung angezeigt wird.

### setPrintOnly(boolean value) {#setPrintOnly-boolean-}
```
public final void setPrintOnly(boolean value)
```


Setzt den Wert, der angibt, ob die Anmerkung gedruckt, aber nicht in der PDF-Anzeigeanwendung angezeigt wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | Der Wert, der angibt, ob die Anmerkung gedruckt, aber nicht in der PDF-Anzeigeanwendung angezeigt wird. |
|

