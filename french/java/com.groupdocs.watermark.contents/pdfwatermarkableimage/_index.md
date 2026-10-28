---
title: "PdfWatermarkableImage"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente une image à l'intérieur d'un document PDF."
type: docs
weight: 72
url: /fr/java/com.groupdocs.watermark.contents/pdfwatermarkableimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
```
public class PdfWatermarkableImage extends WatermarkableImage
```

Représente une image à l'intérieur d'un document PDF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PdfWatermarkableImage(byte[] imageData)](#PdfWatermarkableImage-byte---) | Initialise une nouvelle instance de la classe `[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage)` en utilisant les données d'image spécifiées. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [fetchOrCreate(XImageCollection imageCollection, String nameInCollection, PdfContent content)](#fetchOrCreate-com.aspose.pdf.XImageCollection-java.lang.String-com.groupdocs.watermark.contents.PdfContent-) | <br /> |

|
### PdfWatermarkableImage(byte[] imageData) {#PdfWatermarkableImage-byte---}
```
public PdfWatermarkableImage(byte[] imageData)
```


Initialise une nouvelle instance de la classe `[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage)` en utilisant les données d'image spécifiées.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | imageData | byte[] | Le tableau d'octets non signés à partir duquel créer le `[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage)`. |
|

### fetchOrCreate(XImageCollection imageCollection, String nameInCollection, PdfContent content) {#fetchOrCreate-com.aspose.pdf.XImageCollection-java.lang.String-com.groupdocs.watermark.contents.PdfContent-}
```
public static PdfWatermarkableImage fetchOrCreate(XImageCollection imageCollection, String nameInCollection, PdfContent content)
```


<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageCollection | com.aspose.pdf.XImageCollection |  |
| nameInCollection | java.lang.String |  |
| content | [PdfContent](../../com.groupdocs.watermark.contents/pdfcontent) |  |

**Returns:**
[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage)
