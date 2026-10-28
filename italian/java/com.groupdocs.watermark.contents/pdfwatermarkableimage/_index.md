---
title: "PdfWatermarkableImage"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta un'immagine all'interno di un documento PDF."
type: docs
weight: 72
url: /it/java/com.groupdocs.watermark.contents/pdfwatermarkableimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
```
public class PdfWatermarkableImage extends WatermarkableImage
```

Rappresenta un'immagine all'interno di un documento PDF.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PdfWatermarkableImage(byte[] imageData)](#PdfWatermarkableImage-byte---) | Inizializza una nuova istanza della classe `[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage)` utilizzando i dati immagine specificati. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [fetchOrCreate(XImageCollection imageCollection, String nameInCollection, PdfContent content)](#fetchOrCreate-com.aspose.pdf.XImageCollection-java.lang.String-com.groupdocs.watermark.contents.PdfContent-) | <br /> |

|
### PdfWatermarkableImage(byte[] imageData) {#PdfWatermarkableImage-byte---}
```
public PdfWatermarkableImage(byte[] imageData)
```


Inizializza una nuova istanza della classe `[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage)` utilizzando i dati immagine specificati.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | imageData | byte[] | L'array di byte senza segno da cui creare il `[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage)`. |
|

### fetchOrCreate(XImageCollection imageCollection, String nameInCollection, PdfContent content) {#fetchOrCreate-com.aspose.pdf.XImageCollection-java.lang.String-com.groupdocs.watermark.contents.PdfContent-}
```
public static PdfWatermarkableImage fetchOrCreate(XImageCollection imageCollection, String nameInCollection, PdfContent content)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageCollection | com.aspose.pdf.XImageCollection |  |
| nameInCollection | java.lang.String |  |
| content | [PdfContent](../../com.groupdocs.watermark.contents/pdfcontent) |  |

**Returns:**
[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage)
