---
title: "PdfArtifact"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά ένα artifact σε περιεχόμενο pdf."
type: docs
weight: 54
url: /el/java/com.groupdocs.watermark.contents/pdfartifact/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfArtifact extends PdfShape
```

Αναπαριστά ένα artifact σε περιεχόμενο pdf.

**Lean more**

* [Working with artifacts](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithartifacts)

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPage()](#getPage--) | Λαμβάνει τη γονική σελίδα αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getText()](#getText--) | Λαμβάνει το κείμενο αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Ορίζει το κείμενο αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getArtifactType()](#getArtifactType--) | Λαμβάνει τον τύπο αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getArtifactSubtype()](#getArtifactSubtype--) | Λαμβάνει τον υποτύπο αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getOpacity()](#getOpacity--) | Λαμβάνει την αδιαφάνεια αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getX()](#getX--) | Λαμβάνει την οριζόντια μετατόπιση αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` από το αριστερό άκρο της σελίδας σε σημεία. |
|
|  | [getY()](#getY--) | Λαμβάνει την κάθετη μετατόπιση αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` από το κάτω άκρο της σελίδας σε σημεία. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Λαμβάνει τη γωνία περιστροφής αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` σε μοίρες. |
|
|  | [getWidth()](#getWidth--) | Λαμβάνει το πλάτος αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` σε σημεία. |
|
|  | [getHeight()](#getHeight--) | Λαμβάνει το ύψος αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` σε σημεία. |
|
|  | [getAsposePdfArtifact()](#getAsposePdfArtifact--) | <br /> |

|
|  | [getOuterForm()](#getOuterForm--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


Λαμβάνει τη γονική σελίδα αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getText() {#getText--}
```
public String getText()
```


Λαμβάνει το κείμενο αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
java.lang.String - Το κείμενο αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Ορίζει το κείμενο αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Το κείμενο αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|

### getArtifactType() {#getArtifactType--}
```
public final int getArtifactType()
```


Λαμβάνει τον τύπο αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
int - Ο τύπος αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getArtifactSubtype() {#getArtifactSubtype--}
```
public final int getArtifactSubtype()
```


Λαμβάνει τον υποτύπο αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
int - Ο υποτύπος αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Λαμβάνει την αδιαφάνεια αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

Οι πιθανές τιμές είναι στο εύρος [0, 1].


**Returns:**
double - Η αδιαφάνεια αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getX() {#getX--}
```
public double getX()
```


Λαμβάνει την οριζόντια μετατόπιση αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` από το αριστερό άκρο της σελίδας σε σημεία.


**Returns:**
double - Η συντεταγμένη x αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getY() {#getY--}
```
public double getY()
```


Λαμβάνει την κάθετη μετατόπιση αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` από το κάτω άκρο της σελίδας σε σημεία.


**Returns:**
double - Η συντεταγμένη y αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Λαμβάνει τη γωνία περιστροφής αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` σε μοίρες.


**Returns:**
double - Η γωνία περιστροφής αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` σε μοίρες.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Λαμβάνει το πλάτος αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` σε σημεία.


**Returns:**
double - Το πλάτος αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` σε σημεία.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Λαμβάνει το ύψος αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` σε σημεία.


**Returns:**
double - Το ύψος αυτού του `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` σε σημεία.

### getAsposePdfArtifact() {#getAsposePdfArtifact--}
```
public final Artifact getAsposePdfArtifact()
```


<br />



**Returns:**
com.aspose.pdf.Artifact
### getOuterForm() {#getOuterForm--}
```
public XForm getOuterForm()
```


<br />



**Returns:**
com.aspose.pdf.XForm
