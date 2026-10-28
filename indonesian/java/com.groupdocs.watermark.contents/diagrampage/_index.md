---
title: "DiagramPage"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili halaman dokumen Visio."
type: docs
weight: 22
url: /id/java/com.groupdocs.watermark.contents/diagrampage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class DiagramPage extends ContentPart
```

Mewakili halaman dokumen Visio.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getShapes()](#getShapes--) | Mendapatkan koleksi semua bentuk pada halaman. |
|
|  | [isBackground()](#isBackground--) | Mendapatkan nilai yang menunjukkan apakah halaman tersebut adalah halaman latar belakang. |
|
|  | [getBackgroundPage()](#getBackgroundPage--) | Mendapatkan halaman latar belakang untuk ini . |
|
|  | [getWidth()](#getWidth--) | Mendapatkan lebar ini dalam poin. |
|
|  | [getHeight()](#getHeight--) | Mendapatkan tinggi ini dalam poin. |
|
|  | [getTopMargin()](#getTopMargin--) | Mendapatkan ukuran margin atas dalam poin. |
|
|  | [getRightMargin()](#getRightMargin--) | Mendapatkan ukuran margin kanan dalam poin. |
|
|  | [getBottomMargin()](#getBottomMargin--) | Mendapatkan ukuran margin bawah dalam poin. |
|
|  | [getLeftMargin()](#getLeftMargin--) | Mendapatkan ukuran margin kiri dalam poin. |
|
|  | [isVisible()](#isVisible--) | Mendapatkan nilai yang menunjukkan apakah halaman terlihat di UI. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | Mengatur nilai yang menunjukkan apakah halaman terlihat di UI. |
|
|  | [getName()](#getName--) | Mendapatkan nama dari ini |
DiagramPage
.
|
|  | [getAsposeDiagramPage()](#getAsposeDiagramPage--) | <br /> |

|
|  | [getContent()](#getContent--) | <br /> |

|
|  | [getPageToDrawingScale()](#getPageToDrawingScale--) | <br /> |

|
|  | [addWatermark(Watermark watermark, DiagramShapeSettings shapeSettings)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.internal.DiagramShapeSettings-) | <br /> |

|
|  | [convertValueFromDrawingScaleToPageScale(DoubleValue value)](#convertValueFromDrawingScaleToPageScale-com.aspose.diagram.DoubleValue-) | <br /> |

|
### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```




**Returns:**
java.lang.Integer
### getShapes() {#getShapes--}
```
public final DiagramShapeCollection getShapes()
```


Mendapatkan koleksi semua bentuk pada halaman.


**Returns:**
[DiagramShapeCollection](../../com.groupdocs.watermark.contents/diagramshapecollection) - The collection of all shapes of the page.

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


Mendapatkan nilai yang menunjukkan apakah halaman tersebut adalah halaman latar belakang.


**Returns:**
boolean - True jika halaman tersebut adalah halaman latar belakang; jika tidak, false.

### getBackgroundPage() {#getBackgroundPage--}
```
public final DiagramPage getBackgroundPage()
```


Mendapatkan halaman latar belakang untuk ini .


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The background page for this .

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Mendapatkan lebar ini dalam poin.


**Returns:**
double - Lebar ini dalam poin.

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Mendapatkan tinggi ini dalam poin.


**Returns:**
double - Tinggi ini dalam poin.

### getTopMargin() {#getTopMargin--}
```
public final double getTopMargin()
```


Mendapatkan ukuran margin atas dalam poin.


**Returns:**
double - Ukuran margin atas dalam poin.

### getRightMargin() {#getRightMargin--}
```
public final double getRightMargin()
```


Mendapatkan ukuran margin kanan dalam poin.


**Returns:**
double - Ukuran margin kanan dalam poin.

### getBottomMargin() {#getBottomMargin--}
```
public final double getBottomMargin()
```


Mendapatkan ukuran margin bawah dalam poin.


**Returns:**
double - Ukuran margin bawah dalam poin.

### getLeftMargin() {#getLeftMargin--}
```
public final double getLeftMargin()
```


Mendapatkan ukuran margin kiri dalam poin.


**Returns:**
double - Ukuran margin kiri dalam poin.

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Mendapatkan nilai yang menunjukkan apakah halaman terlihat di UI.


**Returns:**
boolean - Nilai yang menunjukkan apakah halaman terlihat di UI. True jika halaman terlihat; jika tidak, false.

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Mengatur nilai yang menunjukkan apakah halaman terlihat di UI.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | boolean | Nilai yang menunjukkan apakah halaman terlihat di UI. True jika halaman terlihat; jika tidak, false. |
|

### getName() {#getName--}
```
public final String getName()
```


Mendapatkan nama dari ini
DiagramPage
.


**Returns:**
java.lang.String - Nama dari ini  DiagramPage .

### getAsposeDiagramPage() {#getAsposeDiagramPage--}
```
public final Page getAsposeDiagramPage()
```


<br />



**Returns:**
com.aspose.diagram.Page
### getContent() {#getContent--}
```
public final DiagramContent getContent()
```


<br />



**Returns:**
[DiagramContent](../../com.groupdocs.watermark.contents/diagramcontent)
### getPageToDrawingScale() {#getPageToDrawingScale--}
```
public final double getPageToDrawingScale()
```


<br />



**Returns:**
double
### addWatermark(Watermark watermark, DiagramShapeSettings shapeSettings) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.internal.DiagramShapeSettings-}
```
public final void addWatermark(Watermark watermark, DiagramShapeSettings shapeSettings)
```


<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [DiagramShapeSettings](../../com.groupdocs.watermark.internal/diagramshapesettings) |  |

### convertValueFromDrawingScaleToPageScale(DoubleValue value) {#convertValueFromDrawingScaleToPageScale-com.aspose.diagram.DoubleValue-}
```
public final double convertValueFromDrawingScaleToPageScale(DoubleValue value)
```


<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | com.aspose.diagram.DoubleValue |  |

**Returns:**
double
