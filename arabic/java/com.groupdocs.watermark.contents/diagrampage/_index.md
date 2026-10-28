---
title: "DiagramPage"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل صفحة مستند Visio."
type: docs
weight: 22
url: /ar/java/com.groupdocs.watermark.contents/diagrampage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class DiagramPage extends ContentPart
```

يمثل صفحة مستند Visio.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getShapes()](#getShapes--) | يحصل على مجموعة جميع أشكال الصفحة. |
|
|  | [isBackground()](#isBackground--) | يحصل على قيمة تشير إلى ما إذا كانت الصفحة صفحة خلفية. |
|
|  | [getBackgroundPage()](#getBackgroundPage--) | يحصل على صفحة الخلفية لهذا. |
|
|  | [getWidth()](#getWidth--) | يحصل على عرض هذا بالنقاط. |
|
|  | [getHeight()](#getHeight--) | يحصل على ارتفاع هذا بالنقاط. |
|
|  | [getTopMargin()](#getTopMargin--) | يحصل على حجم الهامش العلوي بالنقاط. |
|
|  | [getRightMargin()](#getRightMargin--) | يحصل على حجم الهامش الأيمن بالنقاط. |
|
|  | [getBottomMargin()](#getBottomMargin--) | يحصل على حجم الهامش السفلي بالنقاط. |
|
|  | [getLeftMargin()](#getLeftMargin--) | يحصل على حجم الهامش الأيسر بالنقاط. |
|
|  | [isVisible()](#isVisible--) | يحصل على قيمة تشير إلى ما إذا كانت الصفحة مرئية في واجهة المستخدم. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | يضبط قيمة تشير إلى ما إذا كانت الصفحة مرئية في واجهة المستخدم. |
|
|  | [getName()](#getName--) | يحصل على اسم هذا |
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


يحصل على مجموعة جميع أشكال الصفحة.


**Returns:**
[DiagramShapeCollection](../../com.groupdocs.watermark.contents/diagramshapecollection) - The collection of all shapes of the page.

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


يحصل على قيمة تشير إلى ما إذا كانت الصفحة صفحة خلفية.


**Returns:**
منطقي - صحيح إذا كانت الصفحة صفحة خلفية؛ وإلا، خطأ.

### getBackgroundPage() {#getBackgroundPage--}
```
public final DiagramPage getBackgroundPage()
```


يحصل على صفحة الخلفية لهذا.


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The background page for this .

### getWidth() {#getWidth--}
```
public final double getWidth()
```


يحصل على عرض هذا بالنقاط.


**Returns:**
مزدوج - عرض هذا بالنقاط.

### getHeight() {#getHeight--}
```
public final double getHeight()
```


يحصل على ارتفاع هذا بالنقاط.


**Returns:**
مزدوج - ارتفاع هذا بالنقاط.

### getTopMargin() {#getTopMargin--}
```
public final double getTopMargin()
```


يحصل على حجم الهامش العلوي بالنقاط.


**Returns:**
double - حجم الهامش العلوي بالنقاط.

### getRightMargin() {#getRightMargin--}
```
public final double getRightMargin()
```


يحصل على حجم الهامش الأيمن بالنقاط.


**Returns:**
double - حجم الهامش الأيمن بالنقاط.

### getBottomMargin() {#getBottomMargin--}
```
public final double getBottomMargin()
```


يحصل على حجم الهامش السفلي بالنقاط.


**Returns:**
double - حجم الهامش السفلي بالنقاط.

### getLeftMargin() {#getLeftMargin--}
```
public final double getLeftMargin()
```


يحصل على حجم الهامش الأيسر بالنقاط.


**Returns:**
double - حجم الهامش الأيسر بالنقاط.

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


يحصل على قيمة تشير إلى ما إذا كانت الصفحة مرئية في واجهة المستخدم.


**Returns:**
منطقي - القيمة التي تشير إلى ما إذا كانت الصفحة مرئية في واجهة المستخدم. صحيح إذا كانت الصفحة مرئية؛ وإلا، خطأ.

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


يضبط قيمة تشير إلى ما إذا كانت الصفحة مرئية في واجهة المستخدم.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | boolean | القيمة التي تشير إلى ما إذا كانت الصفحة مرئية في واجهة المستخدم. صحيح إذا كانت الصفحة مرئية؛ وإلا، خطأ. |
|

### getName() {#getName--}
```
public final String getName()
```


يحصل على اسم هذا
DiagramPage
.


**Returns:**
java.lang.String - اسم هذه DiagramPage .

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [DiagramShapeSettings](../../com.groupdocs.watermark.internal/diagramshapesettings) |  |

### convertValueFromDrawingScaleToPageScale(DoubleValue value) {#convertValueFromDrawingScaleToPageScale-com.aspose.diagram.DoubleValue-}
```
public final double convertValueFromDrawingScaleToPageScale(DoubleValue value)
```


<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | com.aspose.diagram.DoubleValue |  |

**Returns:**
double
