---
title: "DiagramPage"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir Visio belge sayfasını temsil eder."
type: docs
weight: 22
url: /tr/java/com.groupdocs.watermark.contents/diagrampage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class DiagramPage extends ContentPart
```

Bir Visio belge sayfasını temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getShapes()](#getShapes--) | Sayfanın tüm şekillerinin koleksiyonunu alır. |
|
|  | [isBackground()](#isBackground--) | Sayfanın arka plan sayfası olup olmadığını gösteren bir değeri alır. |
|
|  | [getBackgroundPage()](#getBackgroundPage--) | Bu öğe için arka plan sayfasını alır. |
|
|  | [getWidth()](#getWidth--) | Bunun genişliğini puan cinsinden alır. |
|
|  | [getHeight()](#getHeight--) | Bunun yüksekliğini puan cinsinden alır. |
|
|  | [getTopMargin()](#getTopMargin--) | Üst kenar boşluğunun boyutunu puan cinsinden alır. |
|
|  | [getRightMargin()](#getRightMargin--) | Sağ kenar boşluğunun boyutunu puan cinsinden alır. |
|
|  | [getBottomMargin()](#getBottomMargin--) | Alt kenar boşluğunun boyutunu puan cinsinden alır. |
|
|  | [getLeftMargin()](#getLeftMargin--) | Sol kenar boşluğunun boyutunu puan cinsinden alır. |
|
|  | [isVisible()](#isVisible--) | Sayfanın UI'de görünür olup olmadığını gösteren bir değeri alır. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | Sayfanın UI'de görünür olup olmadığını gösteren bir değeri ayarlar. |
|
|  | [getName()](#getName--) | Bunun adını alır |
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


Sayfanın tüm şekillerinin koleksiyonunu alır.


**Returns:**
[DiagramShapeCollection](../../com.groupdocs.watermark.contents/diagramshapecollection) - The collection of all shapes of the page.

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


Sayfanın arka plan sayfası olup olmadığını gösteren bir değeri alır.


**Returns:**
boolean - Sayfa bir arka plan sayfası ise True; aksi takdirde false.

### getBackgroundPage() {#getBackgroundPage--}
```
public final DiagramPage getBackgroundPage()
```


Bu öğe için arka plan sayfasını alır.


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The background page for this .

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Bunun genişliğini puan cinsinden alır.


**Returns:**
double - Bunun puan cinsinden genişliği.

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Bunun yüksekliğini puan cinsinden alır.


**Returns:**
double - Bunun puan cinsinden yüksekliği.

### getTopMargin() {#getTopMargin--}
```
public final double getTopMargin()
```


Üst kenar boşluğunun boyutunu puan cinsinden alır.


**Returns:**
double - Üst kenar boşluğunun boyutu puan cinsinden.

### getRightMargin() {#getRightMargin--}
```
public final double getRightMargin()
```


Sağ kenar boşluğunun boyutunu puan cinsinden alır.


**Returns:**
double - Sağ kenar boşluğunun boyutu puan cinsinden.

### getBottomMargin() {#getBottomMargin--}
```
public final double getBottomMargin()
```


Alt kenar boşluğunun boyutunu puan cinsinden alır.


**Returns:**
double - Alt kenar boşluğunun nokta cinsinden boyutu.

### getLeftMargin() {#getLeftMargin--}
```
public final double getLeftMargin()
```


Sol kenar boşluğunun boyutunu puan cinsinden alır.


**Returns:**
double - Sol kenar boşluğunun boyutu puan cinsinden.

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Sayfanın UI'de görünür olup olmadığını gösteren bir değeri alır.


**Returns:**
boolean - Sayfanın UI'de görünür olup olmadığını gösteren değer. Sayfa görünür ise True; aksi takdirde false.

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Sayfanın UI'de görünür olup olmadığını gösteren bir değeri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | Sayfanın UI'de görünür olup olmadığını gösteren değer. Sayfa görünür ise True; aksi takdirde false. |
|

### getName() {#getName--}
```
public final String getName()
```


Bunun adını alır
DiagramPage
.


**Returns:**
java.lang.String - Bu DiagramPage'in adı.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [DiagramShapeSettings](../../com.groupdocs.watermark.internal/diagramshapesettings) |  |

### convertValueFromDrawingScaleToPageScale(DoubleValue value) {#convertValueFromDrawingScaleToPageScale-com.aspose.diagram.DoubleValue-}
```
public final double convertValueFromDrawingScaleToPageScale(DoubleValue value)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.diagram.DoubleValue |  |

**Returns:**
double
