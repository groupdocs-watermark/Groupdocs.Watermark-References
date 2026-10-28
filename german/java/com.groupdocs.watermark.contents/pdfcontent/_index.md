---
title: "PdfContent"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt ein PDF-Dokument dar, in das ein Wasserzeichen eingefügt werden kann."
type: docs
weight: 60
url: /de/java/com.groupdocs.watermark.contents/pdfcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IEncryptable](../../com.groupdocs.watermark.internal/iencryptable)
```
public class PdfContent extends Content implements IEncryptable
```

Stellt ein PDF-Dokument dar, in das ein Wasserzeichen eingefügt werden kann.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)
* [Existing objects in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document)
* [Rasterize document or page](../https://docs.groupdocs.com/display/watermarkjava/Rasterize+document+or+page)
* [Watermarks in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Watermarks+in+PDF+document)

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PdfContent(StreamContainer stream, StrategyManager<Integer> strategyManager, PdfLoadOptions pdfLoadOptions, WatermarkerSettings watermarkerSettings)](#PdfContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.options.PdfLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPages()](#getPages--) | Liefert die Sammlung aller Seiten dieses `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`. |
|
|  | [getAttachments()](#getAttachments--) | Liefert die Sammlung aller Anhänge dieses `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`. |
|
|  | [getPageMarginType()](#getPageMarginType--) | Liefert die PDF‑Seitenränder, die beim Hinzufügen von Wasserzeichen verwendet werden. |
|
|  | [setPageMarginType(int value)](#setPageMarginType-int-) | Setzt die PDF‑Seitenränder, die beim Hinzufügen von Wasserzeichen verwendet werden. |
|
|  | [getAsposePdfDocument()](#getAsposePdfDocument--) | <br /> |

|
|  | [addArtifactWatermark(Watermark watermark)](#addArtifactWatermark-com.groupdocs.watermark.Watermark-) | <br /> |

|
|  | [addAnnotationWatermark(Watermark watermark, boolean isPrintOnly)](#addAnnotationWatermark-com.groupdocs.watermark.Watermark-boolean-) | <br /> |

|
|  | [getDocumentInfo()](#getDocumentInfo--) | <br /> |

|
|  | [getFileType()](#getFileType--) | <br /> |

|
|  | [encrypt(String password)](#encrypt-java.lang.String-) | Verschlüsselt das Dokument mit demselben Passwort wie Benutzer‑ und Eigentümerpasswort. |
|
|  | [encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm)](#encrypt-java.lang.String-java.lang.String-int-int-) | Verschlüsselt den Inhalt. |
|
|  | [decrypt()](#decrypt--) | Entschlüsselt den Inhalt. |
|
|  | [rasterize(int horizontalResolution, int verticalResolution, int imageFormat)](#rasterize-int-int-int-) | Konvertiert alle Inhaltsseiten in Bilder. |
|
|  | [performSave(String filePath)](#performSave-java.lang.String-) | <br /> |

|
|  | [performSave(String filePath, SaveOptions saveOptions)](#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | <br /> |

|
|  | [performSave(OutputStream stream)](#performSave-java.io.OutputStream-) | Speichert die Dokumentdaten in den angegebenen Stream. |
|
|  | [performSave(OutputStream stream, SaveOptions saveOptions)](#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | Speichert die Dokumentdaten in den angegebenen Stream. |
|
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | <br /> |

|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | <br /> |

|
### PdfContent(StreamContainer stream, StrategyManager<Integer> strategyManager, PdfLoadOptions pdfLoadOptions, WatermarkerSettings watermarkerSettings) {#PdfContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.options.PdfLoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public PdfContent(StreamContainer stream, StrategyManager<Integer> strategyManager, PdfLoadOptions pdfLoadOptions, WatermarkerSettings watermarkerSettings)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| pdfLoadOptions | [PdfLoadOptions](../../com.groupdocs.watermark.options/pdfloadoptions) |  |
| watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getPages() {#getPages--}
```
public final PdfPageCollection getPages()
```


Liefert die Sammlung aller Seiten dieses `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`.


**Returns:**
[PdfPageCollection](../../com.groupdocs.watermark.contents/pdfpagecollection) - The collection of all pages of this `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`.

### getAttachments() {#getAttachments--}
```
public final PdfAttachmentCollection getAttachments()
```


Liefert die Sammlung aller Anhänge dieses `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`.


**Returns:**
[PdfAttachmentCollection](../../com.groupdocs.watermark.contents/pdfattachmentcollection) - The collection of all attachments of this `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`.

### getPageMarginType() {#getPageMarginType--}
```
public final int getPageMarginType()
```


Liefert die PDF‑Seitenränder, die beim Hinzufügen von Wasserzeichen verwendet werden.

Diese Eigenschaft funktioniert nur, wenn `[Watermark.getConsiderParentMargins()](../../com.groupdocs.watermark/watermark#getConsiderParentMargins--)`
wahr ist. Wenn `[Watermark.getConsiderParentMargins()](../../com.groupdocs.watermark/watermark#getConsiderParentMargins--)` falsch ist,
wenn die PDF‑CropBox als Wasserzeichenbereich verwendet wird.

Der Standardwert ist `[PdfPageMarginType.TrimBox](../../com.groupdocs.watermark.contents/pdfpagemargintype#TrimBox)`.


**Returns:**
int
### setPageMarginType(int value) {#setPageMarginType-int-}
```
public final void setPageMarginType(int value)
```


Setzt die PDF‑Seitenränder, die beim Hinzufügen von Wasserzeichen verwendet werden.

Diese Eigenschaft funktioniert nur, wenn `[Watermark.getConsiderParentMargins()](../../com.groupdocs.watermark/watermark#getConsiderParentMargins--)`
ist auf wahr gesetzt. Wenn `[Watermark.getConsiderParentMargins()](../../com.groupdocs.watermark/watermark#getConsiderParentMargins--)` falsch ist,
wenn die PDF‑CropBox als Wasserzeichenbereich verwendet wird.

Der Standardwert ist `[PdfPageMarginType.TrimBox](../../com.groupdocs.watermark.contents/pdfpagemargintype#TrimBox)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getAsposePdfDocument() {#getAsposePdfDocument--}
```
public final Document getAsposePdfDocument()
```


<br />



**Returns:**
com.aspose.pdf.Document
### addArtifactWatermark(Watermark watermark) {#addArtifactWatermark-com.groupdocs.watermark.Watermark-}
```
public final void addArtifactWatermark(Watermark watermark)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### addAnnotationWatermark(Watermark watermark, boolean isPrintOnly) {#addAnnotationWatermark-com.groupdocs.watermark.Watermark-boolean-}
```
public final void addAnnotationWatermark(Watermark watermark, boolean isPrintOnly)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| isPrintOnly | boolean |  |

### getDocumentInfo() {#getDocumentInfo--}
```
public IDocumentInfo getDocumentInfo()
```


<br />



**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)
### getFileType() {#getFileType--}
```
public FileType getFileType()
```


<br />



**Returns:**
[FileType](../../com.groupdocs.watermark.common/filetype)
### encrypt(String password) {#encrypt-java.lang.String-}
```
public final void encrypt(String password)
```


Verschlüsselt das Dokument mit demselben Passwort wie Benutzer‑ und Eigentümerpasswort.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Passwort | java.lang.String | Benutzer- und Eigentümerpasswort. |
|

### encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm) {#encrypt-java.lang.String-java.lang.String-int-int-}
```
public final void encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm)
```


Verschlüsselt den Inhalt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | userPassword | java.lang.String | Benutzerpasswort. |
|
|  | ownerPassword | java.lang.String | Eigentümerpasswort. |
|
|  | permissions | int | Inhaltsberechtigungen. |
|
|  | cryptoAlgorithm | int | Kryptografischer Algorithmus. |
|

### decrypt() {#decrypt--}
```
public final void decrypt()
```


Entschlüsselt den Inhalt.


### rasterize(int horizontalResolution, int verticalResolution, int imageFormat) {#rasterize-int-int-int-}
```
public final void rasterize(int horizontalResolution, int verticalResolution, int imageFormat)
```


Konvertiert alle Inhaltsseiten in Bilder.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | horizontalResolution | int | Horizontale Bildauflösung. |
|
|  | verticalResolution | int | Vertikale Bildauflösung. |
|
|  | imageFormat | int | Bildformat. |
|

### performSave(String filePath) {#performSave-java.lang.String-}
```
public void performSave(String filePath)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


Speichert die Dokumentdaten in den angegebenen Stream.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | stream | java.io.OutputStream | Der Stream, in den die Inhaltsdaten gespeichert werden sollen. |
|

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


Speichert die Dokumentdaten in den angegebenen Stream.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | stream | java.io.OutputStream | Der Stream, in den die Inhaltsdaten gespeichert werden sollen. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | Die Optionen, die beim Speichern der Inhaltsdaten verwendet werden sollten. |
|

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public void add(Watermark watermark, WatermarkOptions options)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

