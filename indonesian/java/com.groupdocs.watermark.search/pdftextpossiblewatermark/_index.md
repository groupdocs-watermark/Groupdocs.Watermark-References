---
title: "PdfTextPossibleWatermark"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili watermark yang mungkin ada dalam teks dokumen pdf."
type: docs
weight: 43
url: /id/java/com.groupdocs.watermark.search/pdftextpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public class PdfTextPossibleWatermark extends PossibleWatermark
```

Mewakili watermark yang mungkin ada dalam teks dokumen pdf.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfTextPossibleWatermark(PdfPage parent, TextFragment fragment)](#PdfTextPossibleWatermark-com.groupdocs.watermark.contents.PdfPage-com.aspose.pdf.TextFragment-) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getParent()](#getParent--) | Mendapatkan induk dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`. |
|
|  | [getWidth()](#getWidth--) | Mendapatkan lebar dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` dalam poin. |
|
|  | [getHeight()](#getHeight--) | Mendapatkan tinggi dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` dalam poin. |
|
|  | [getX()](#getX--) | Mendapatkan offset horizontal dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` dari batas kiri halaman dalam poin. |
|
|  | [getY()](#getY--) | Mendapatkan offset vertikal dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` dari batas bawah halaman dalam poin. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Mendapatkan sudut rotasi dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` dalam derajat. |
|
|  | [getText()](#getText--) | Mendapatkan teks dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Mengatur teks dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Mendapatkan koleksi fragmen teks terformat dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`. |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Mendapatkan `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`. |
|
| [remove()](#remove--) |  |
### PdfTextPossibleWatermark(PdfPage parent, TextFragment fragment) {#PdfTextPossibleWatermark-com.groupdocs.watermark.contents.PdfPage-com.aspose.pdf.TextFragment-}
```
public PdfTextPossibleWatermark(PdfPage parent, TextFragment fragment)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| parent | [PdfPage](../../com.groupdocs.watermark.contents/pdfpage) |  |
| fragmen | com.aspose.pdf.TextFragment |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


Mendapatkan induk dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Mendapatkan lebar dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` dalam poin.


**Returns:**
double - Lebar dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` dalam poin.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Mendapatkan tinggi dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` dalam poin.


**Returns:**
double - Tinggi dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` dalam poin.

### getX() {#getX--}
```
public double getX()
```


Mendapatkan offset horizontal dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` dari batas kiri halaman dalam poin.


**Returns:**
double - Koordinat x dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getY() {#getY--}
```
public double getY()
```


Mendapatkan offset vertikal dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` dari batas bawah halaman dalam poin.


**Returns:**
double - Koordinat y dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Mendapatkan sudut rotasi dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` dalam derajat.


**Returns:**
double - Nilai selalu 0 untuk tipe watermark yang mungkin ini.

### getText() {#getText--}
```
public String getText()
```


Mendapatkan teks dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.


**Returns:**
java.lang.String - Teks dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Mengatur teks dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | Teks dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Mendapatkan koleksi fragmen teks terformat dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Mendapatkan `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.


**Returns:**
int - `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` dari `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### remove() {#remove--}
```
public void remove()
```




