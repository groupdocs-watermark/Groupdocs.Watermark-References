---
title: "PdfWatermarkableImage"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa una imagen dentro de un documento Pdf."
type: docs
weight: 72
url: /es/java/com.groupdocs.watermark.contents/pdfwatermarkableimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
```
public class PdfWatermarkableImage extends WatermarkableImage
```

Representa una imagen dentro de un documento Pdf.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PdfWatermarkableImage(byte[] imageData)](#PdfWatermarkableImage-byte---) | Inicializa una nueva instancia de la clase `[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage)` usando los datos de imagen especificados. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [fetchOrCreate(XImageCollection imageCollection, String nameInCollection, PdfContent content)](#fetchOrCreate-com.aspose.pdf.XImageCollection-java.lang.String-com.groupdocs.watermark.contents.PdfContent-) | <br /> |

|
### PdfWatermarkableImage(byte[] imageData) {#PdfWatermarkableImage-byte---}
```
public PdfWatermarkableImage(byte[] imageData)
```


Inicializa una nueva instancia de la clase `[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage)` usando los datos de imagen especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | imageData | byte[] | La matriz de bytes sin signo a partir de la cual crear el `[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage)`. |
|

### fetchOrCreate(XImageCollection imageCollection, String nameInCollection, PdfContent content) {#fetchOrCreate-com.aspose.pdf.XImageCollection-java.lang.String-com.groupdocs.watermark.contents.PdfContent-}
```
public static PdfWatermarkableImage fetchOrCreate(XImageCollection imageCollection, String nameInCollection, PdfContent content)
```


<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageCollection | com.aspose.pdf.XImageCollection |  |
| nameInCollection | java.lang.String |  |
| content | [PdfContent](../../com.groupdocs.watermark.contents/pdfcontent) |  |

**Returns:**
[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage)
