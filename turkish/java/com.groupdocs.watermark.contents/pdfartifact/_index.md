---
title: "PdfArtifact"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "PDF içeriğindeki bir artefakti temsil eder."
type: docs
weight: 54
url: /tr/java/com.groupdocs.watermark.contents/pdfartifact/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfArtifact extends PdfShape
```

PDF içeriğindeki bir artefakti temsil eder.

**Lean more**

* [Working with artifacts](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithartifacts)

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPage()](#getPage--) | Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin üst sayfasını alır. |
|
|  | [getText()](#getText--) | Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin metnini alır. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin metnini ayarlar. |
|
|  | [getArtifactType()](#getArtifactType--) | Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin tipini alır. |
|
|  | [getArtifactSubtype()](#getArtifactSubtype--) | Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin alt tipini alır. |
|
|  | [getOpacity()](#getOpacity--) | Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin opaklığını alır. |
|
|  | [getX()](#getX--) | Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin sayfa sol kenarından yatay ofsetini puan olarak alır. |
|
|  | [getY()](#getY--) | Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin sayfa alt kenarından dikey ofsetini puan olarak alır. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin döndürme açısını derece cinsinden alır. |
|
|  | [getWidth()](#getWidth--) | Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin genişliğini puan cinsinden alır. |
|
|  | [getHeight()](#getHeight--) | Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin yüksekliğini puan cinsinden alır. |
|
|  | [getAsposePdfArtifact()](#getAsposePdfArtifact--) | <br /> |

|
|  | [getOuterForm()](#getOuterForm--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin üst sayfasını alır.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getText() {#getText--}
```
public String getText()
```


Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin metnini alır.


**Returns:**
java.lang.String - Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin metni.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin metnini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.lang.String | Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin metni. |
|

### getArtifactType() {#getArtifactType--}
```
public final int getArtifactType()
```


Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin tipini alır.


**Returns:**
int - Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin tipi.

### getArtifactSubtype() {#getArtifactSubtype--}
```
public final int getArtifactSubtype()
```


Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin alt tipini alır.


**Returns:**
int - Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin alt tipi.

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin opaklığını alır.

Olası değerler [0, 1] aralığındadır.


**Returns:**
double - Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin opaklığı.

### getX() {#getX--}
```
public double getX()
```


Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin sayfa sol kenarından yatay ofsetini puan olarak alır.


**Returns:**
double - Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin x-koordinatı.

### getY() {#getY--}
```
public double getY()
```


Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin sayfa alt kenarından dikey ofsetini puan olarak alır.


**Returns:**
double - Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin y-koordinatı.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin döndürme açısını derece cinsinden alır.


**Returns:**
double - Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin derece cinsinden döndürme açısı.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin genişliğini puan cinsinden alır.


**Returns:**
double - Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin puan cinsinden genişliği.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin yüksekliğini puan cinsinden alır.


**Returns:**
double - Bu `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` öğesinin nokta cinsinden yüksekliği.

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
