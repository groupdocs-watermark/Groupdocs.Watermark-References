---
title: "PdfTextPossibleWatermark"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "PDF belge metninde olası filigranı temsil eder."
type: docs
weight: 43
url: /tr/java/com.groupdocs.watermark.search/pdftextpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public class PdfTextPossibleWatermark extends PossibleWatermark
```

PDF belge metninde olası filigranı temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfTextPossibleWatermark(PdfPage parent, TextFragment fragment)](#PdfTextPossibleWatermark-com.groupdocs.watermark.contents.PdfPage-com.aspose.pdf.TextFragment-) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getParent()](#getParent--) | Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin üst öğesini alır. |
|
|  | [getWidth()](#getWidth--) | Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin genişliğini puan cinsinden alır. |
|
|  | [getHeight()](#getHeight--) | Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin yüksekliğini puan cinsinden alır. |
|
|  | [getX()](#getX--) | Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin sayfa sol kenarından yatay ofsetini puan cinsinden alır. |
|
|  | [getY()](#getY--) | Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin sayfa alt kenarından dikey ofsetini puan cinsinden alır. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin döndürme açısını derece cinsinden alır. |
|
|  | [getText()](#getText--) | Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin metnini alır. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin metnini ayarlar. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin biçimlendirilmiş metin parçacıkları koleksiyonunu alır. |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` değerini alır. |
|
| [remove()](#remove--) |  |
### PdfTextPossibleWatermark(PdfPage parent, TextFragment fragment) {#PdfTextPossibleWatermark-com.groupdocs.watermark.contents.PdfPage-com.aspose.pdf.TextFragment-}
```
public PdfTextPossibleWatermark(PdfPage parent, TextFragment fragment)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parent | [PdfPage](../../com.groupdocs.watermark.contents/pdfpage) |  |
| parçacık | com.aspose.pdf.TextFragment |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin üst öğesini alır.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin genişliğini puan cinsinden alır.


**Returns:**
double - Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin genişliğini puan cinsinden.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin yüksekliğini puan cinsinden alır.


**Returns:**
double - Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin yüksekliğini puan cinsinden.

### getX() {#getX--}
```
public double getX()
```


Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin sayfa sol kenarından yatay ofsetini puan cinsinden alır.


**Returns:**
double - Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin x koordinatı.

### getY() {#getY--}
```
public double getY()
```


Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin sayfa alt kenarından dikey ofsetini puan cinsinden alır.


**Returns:**
double - Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin y koordinatı.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin döndürme açısını derece cinsinden alır.


**Returns:**
double - Bu olası filigran türü için değer her zaman 0'dır.

### getText() {#getText--}
```
public String getText()
```


Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin metnini alır.


**Returns:**
java.lang.String - Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin metni.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin metnini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.lang.String | Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin metni. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin biçimlendirilmiş metin parçacıkları koleksiyonunu alır.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` değerini alır.


**Returns:**
int - Bu `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` öğesinin `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` değeri.

### remove() {#remove--}
```
public void remove()
```




