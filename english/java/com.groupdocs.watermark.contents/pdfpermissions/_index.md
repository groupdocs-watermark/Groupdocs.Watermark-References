---
title: PdfPermissions
second_title: GroupDocs.Watermark for Java API Reference
description: Represents users permissions for a pdf document.
type: docs
weight: 68
url: /java/com.groupdocs.watermark.contents/pdfpermissions/
---
**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

Represents user's permissions for a pdf document.
## Fields

| Field | Description |
| --- | --- |
| [PrintDocument](#PrintDocument) | Print the content. |
| [ModifyContent](#ModifyContent) | Modify the content. |
| [ExtractContent](#ExtractContent) | Copy or otherwise extract text and graphics from the document. |
| [ModifyTextAnnotations](#ModifyTextAnnotations) | Add or modify text annotations. |
| [FillForm](#FillForm) | Fill in existing interactive form fields. |
| [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | Extract text and graphics. |
| [AssembleDocument](#AssembleDocument) | Assemble the content. |
| [PrintingQuality](#PrintingQuality) | Print the content to a representation from which a faithful digital copy of the PDF document could be generated. |
### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```


Print the content.

Security handlers of revision 2: Print the content.

Security handlers of revision 3 or greater: Print the content (possibly not at the highest quality level, depending on whether `#PrintingQuality.PrintingQuality` is also set).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```


Modify the content.

Modify the contents of the document by operations other than those controlled by `#ModifyTextAnnotations.ModifyTextAnnotations`, `#FillForm.FillForm`.

### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```


Copy or otherwise extract text and graphics from the document.

Security handlers of revision 2: Copy or otherwise extract text and graphics from the content, including extracting text and graphics (in support of accessibility to users with disabilities or for other purposes).

Security handlers of revision 3 or greater: Copy or otherwise extract text and graphics from the content by operations other than that controlled by `#ExtractContentWithDisabilities.ExtractContentWithDisabilities`.

### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```


Add or modify text annotations.

Add or modify text annotations, fill in interactive form fields, and, if `#ModifyContent.ModifyContent` is also set, create or modify interactive form fields (including signature fields).

### FillForm {#FillForm}
```
public static final int FillForm
```


Fill in existing interactive form fields.

Security handlers of revision 3 or greater: Fill in existing interactive form fields (including signature fields), even if `#ModifyTextAnnotations.ModifyTextAnnotations` is clear.

### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```


Extract text and graphics.

Security handlers of revision 3 or greater: Extract text and graphics (in support of accessibility to users with disabilities or for other purposes).

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```


Assemble the content.

Security handlers of revision 3 or greater: Assemble the content (insert, rotate, or delete pages and create bookmarks or thumbnail images), even if `#ModifyContent.ModifyContent` is clear.

### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```


Print the content to a representation from which a faithful digital copy of the PDF document could be generated.

Security handlers of revision 3 or greater: Print the content to a representation from which a faithful digital copy of the PDF document could be generated. When this bit is clear (and `#PrintDocument.PrintDocument` is set), printing is limited to a low-level representation of the appearance, possibly of degraded quality.

