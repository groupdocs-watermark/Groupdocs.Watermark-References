---
title: "PdfXObject"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά ένα XObject σε ένα έγγραφο pdf."
type: docs
weight: 75
url: /el/java/com.groupdocs.watermark.contents/pdfxobject/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public abstract class PdfXObject extends PdfShape
```

Αναπαριστά ένα XObject σε ένα έγγραφο pdf.

**Learn more:**

* [Working with XObjects](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-WorkingwithXObjects)

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPage()](#getPage--) | Λαμβάνει τη γονική σελίδα αυτού του `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`. |
|
|  | [getX()](#getX--) | Λαμβάνει την οριζόντια μετατόπιση αυτού του `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` από το αριστερό άκρο της σελίδας σε σημεία. |
|
|  | [getY()](#getY--) | Λαμβάνει την κάθετη μετατόπιση αυτού του `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` από το κάτω άκρο της σελίδας σε σημεία. |
|
|  | [getWidth()](#getWidth--) | Λαμβάνει το πλάτος αυτού του `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` σε σημεία. |
|
|  | [getHeight()](#getHeight--) | Λαμβάνει το ύψος αυτού του `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` σε σημεία. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Λαμβάνει τη γωνία περιστροφής αυτού του `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` σε μοίρες. |
|
|  | [getMatrix()](#getMatrix--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


Λαμβάνει τη γονική σελίδα αυτού του `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getX() {#getX--}
```
public double getX()
```


Λαμβάνει την οριζόντια μετατόπιση αυτού του `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` από το αριστερό άκρο της σελίδας σε σημεία.


**Returns:**
double - Η συντεταγμένη x αυτού του `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getY() {#getY--}
```
public double getY()
```


Λαμβάνει την κάθετη μετατόπιση αυτού του `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` από το κάτω άκρο της σελίδας σε σημεία.


**Returns:**
double - Η συντεταγμένη y αυτού του `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Λαμβάνει το πλάτος αυτού του `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` σε σημεία.


**Returns:**
double - Το πλάτος αυτού του `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` σε σημεία.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Λαμβάνει το ύψος αυτού του `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` σε σημεία.


**Returns:**
double - Το ύψος αυτού του `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` σε σημεία.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Λαμβάνει τη γωνία περιστροφής αυτού του `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` σε μοίρες.


**Returns:**
double - Η γωνία περιστροφής αυτού του `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` σε μοίρες.

### getMatrix() {#getMatrix--}
```
public final Matrix getMatrix()
```


<br />



**Returns:**
com.aspose.pdf.Matrix
