---
title: "PdfAnnotation"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά μια σημείωση σε ένα pdf έγγραφο."
type: docs
weight: 51
url: /el/java/com.groupdocs.watermark.contents/pdfannotation/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfAnnotation extends PdfShape
```

Αναπαριστά μια σημείωση σε ένα pdf έγγραφο.

**Learn more:**

* [Working with annotations](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithannotations)

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [NormalAppearanceKey](#NormalAppearanceKey) | <br /> |

|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPage()](#getPage--) | Λαμβάνει τη γονική σελίδα αυτού του `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`. |
|
|  | [getAnnotationType()](#getAnnotationType--) | Λαμβάνει τον τύπο αυτού του `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`. |
|
|  | [getX()](#getX--) | Λαμβάνει την οριζόντια απόσταση αυτού του `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` από το αριστερό άκρο της σελίδας σε πόντους. |
|
|  | [getY()](#getY--) | Λαμβάνει την κάθετη απόσταση αυτού του `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` από το κάτω άκρο του φύλλου εργασίας σε πόντους. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Λαμβάνει τη γωνία περιστροφής αυτού του `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` σε μοίρες. |
|
|  | [getWidth()](#getWidth--) | Λαμβάνει το πλάτος αυτού του `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` σε πόντους. |
|
|  | [getHeight()](#getHeight--) | Λαμβάνει το ύψος αυτού του `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` σε πόντους. |
|
|  | [getAsposePdfAnnotation()](#getAsposePdfAnnotation--) | <br /> |

|
|  | [getOuterForm()](#getOuterForm--) | <br /> |

|
### NormalAppearanceKey {#NormalAppearanceKey}
```
public static final String NormalAppearanceKey
```


<br />



### getPage() {#getPage--}
```
public final PdfPage getPage()
```


Λαμβάνει τη γονική σελίδα αυτού του `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.

### getAnnotationType() {#getAnnotationType--}
```
public final int getAnnotationType()
```


Λαμβάνει τον τύπο αυτού του `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.


**Returns:**
int - Ο τύπος αυτού του `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.

### getX() {#getX--}
```
public double getX()
```


Λαμβάνει την οριζόντια απόσταση αυτού του `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` από το αριστερό άκρο της σελίδας σε πόντους.


**Returns:**
double - Η οριζόντια απόσταση αυτού του `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` από το αριστερό άκρο της σελίδας σε πόντους.

### getY() {#getY--}
```
public double getY()
```


Λαμβάνει την κάθετη απόσταση αυτού του `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` από το κάτω άκρο του φύλλου εργασίας σε πόντους.


**Returns:**
double - Η κάθετη απόσταση αυτού του `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` από το κάτω άκρο του φύλλου εργασίας σε πόντους.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Λαμβάνει τη γωνία περιστροφής αυτού του `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` σε μοίρες.


**Returns:**
double - Η γωνία περιστροφής αυτού του `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` σε μοίρες.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Λαμβάνει το πλάτος αυτού του `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` σε πόντους.


**Returns:**
double - Το πλάτος αυτού του `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` σε πόντους.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Λαμβάνει το ύψος αυτού του `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` σε πόντους.


**Returns:**
double - Το ύψος αυτού του `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` σε πόντους.

### getAsposePdfAnnotation() {#getAsposePdfAnnotation--}
```
public final Annotation getAsposePdfAnnotation()
```


<br />



**Returns:**
com.aspose.pdf.Annotation
### getOuterForm() {#getOuterForm--}
```
public XForm getOuterForm()
```


<br />



**Returns:**
com.aspose.pdf.XForm
