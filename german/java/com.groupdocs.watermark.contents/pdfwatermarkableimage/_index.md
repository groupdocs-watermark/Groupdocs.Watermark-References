---
title: "PdfWatermarkableImage"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt ein Bild innerhalb eines PDF-Dokuments dar."
type: docs
weight: 72
url: /de/java/com.groupdocs.watermark.contents/pdfwatermarkableimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
```
public class PdfWatermarkableImage extends WatermarkableImage
```

Stellt ein Bild innerhalb eines PDF-Dokuments dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PdfWatermarkableImage(byte[] imageData)](#PdfWatermarkableImage-byte---) | Initialisiert eine neue Instanz der Klasse `[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage)` mit den angegebenen Bilddaten. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [fetchOrCreate(XImageCollection imageCollection, String nameInCollection, PdfContent content)](#fetchOrCreate-com.aspose.pdf.XImageCollection-java.lang.String-com.groupdocs.watermark.contents.PdfContent-) | <br /> |

|
### PdfWatermarkableImage(byte[] imageData) {#PdfWatermarkableImage-byte---}
```
public PdfWatermarkableImage(byte[] imageData)
```


Initialisiert eine neue Instanz der Klasse `[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage)` mit den angegebenen Bilddaten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | imageData | byte[] | Das Array aus vorzeichenlosen Bytes, aus dem das `[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage)` erstellt wird. |
|

### fetchOrCreate(XImageCollection imageCollection, String nameInCollection, PdfContent content) {#fetchOrCreate-com.aspose.pdf.XImageCollection-java.lang.String-com.groupdocs.watermark.contents.PdfContent-}
```
public static PdfWatermarkableImage fetchOrCreate(XImageCollection imageCollection, String nameInCollection, PdfContent content)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageCollection | com.aspose.pdf.XImageCollection |  |
| nameInCollection | java.lang.String |  |
| content | [PdfContent](../../com.groupdocs.watermark.contents/pdfcontent) |  |

**Returns:**
[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage)
