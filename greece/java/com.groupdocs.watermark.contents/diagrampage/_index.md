---
title: "DiagramPage"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει μια σελίδα εγγράφου Visio."
type: docs
weight: 22
url: /el/java/com.groupdocs.watermark.contents/diagrampage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class DiagramPage extends ContentPart
```

Αντιπροσωπεύει μια σελίδα εγγράφου Visio.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getShapes()](#getShapes--) | Αποκτά τη συλλογή όλων των σχημάτων της σελίδας. |
|
|  | [isBackground()](#isBackground--) | Αποκτά μια τιμή που υποδεικνύει εάν η σελίδα είναι σελίδα φόντου. |
|
|  | [getBackgroundPage()](#getBackgroundPage--) | Αποκτά τη σελίδα φόντου για αυτό. |
|
|  | [getWidth()](#getWidth--) | Αποκτά το πλάτος αυτού σε πόντους. |
|
|  | [getHeight()](#getHeight--) | Αποκτά το ύψος αυτού σε πόντους. |
|
|  | [getTopMargin()](#getTopMargin--) | Λαμβάνει το μέγεθος του άνω περιθωρίου σε σημεία. |
|
|  | [getRightMargin()](#getRightMargin--) | Λαμβάνει το μέγεθος του δεξιού περιθωρίου σε σημεία. |
|
|  | [getBottomMargin()](#getBottomMargin--) | Λαμβάνει το μέγεθος του κάτω περιθωρίου σε σημεία. |
|
|  | [getLeftMargin()](#getLeftMargin--) | Λαμβάνει το μέγεθος του αριστερού περιθωρίου σε σημεία. |
|
|  | [isVisible()](#isVisible--) | Αποκτά μια τιμή που υποδεικνύει εάν η σελίδα είναι ορατή στη διεπαφή χρήστη. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν η σελίδα είναι ορατή στη διεπαφή χρήστη. |
|
|  | [getName()](#getName--) | Αποκτά το όνομα αυτού |
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


Αποκτά τη συλλογή όλων των σχημάτων της σελίδας.


**Returns:**
[DiagramShapeCollection](../../com.groupdocs.watermark.contents/diagramshapecollection) - The collection of all shapes of the page.

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


Αποκτά μια τιμή που υποδεικνύει εάν η σελίδα είναι σελίδα φόντου.


**Returns:**
boolean - True εάν η σελίδα είναι σελίδα φόντου· αλλιώς, false.

### getBackgroundPage() {#getBackgroundPage--}
```
public final DiagramPage getBackgroundPage()
```


Αποκτά τη σελίδα φόντου για αυτό.


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The background page for this .

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Αποκτά το πλάτος αυτού σε πόντους.


**Returns:**
double - Το πλάτος αυτού σε πόντους.

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Αποκτά το ύψος αυτού σε πόντους.


**Returns:**
double - Το ύψος αυτού σε πόντους.

### getTopMargin() {#getTopMargin--}
```
public final double getTopMargin()
```


Λαμβάνει το μέγεθος του άνω περιθωρίου σε σημεία.


**Returns:**
double - Το μέγεθος του άνω περιθωρίου σε σημεία.

### getRightMargin() {#getRightMargin--}
```
public final double getRightMargin()
```


Λαμβάνει το μέγεθος του δεξιού περιθωρίου σε σημεία.


**Returns:**
double - Το μέγεθος του δεξιού περιθωρίου σε σημεία.

### getBottomMargin() {#getBottomMargin--}
```
public final double getBottomMargin()
```


Λαμβάνει το μέγεθος του κάτω περιθωρίου σε σημεία.


**Returns:**
double - Το μέγεθος του κάτω περιθωρίου σε σημεία.

### getLeftMargin() {#getLeftMargin--}
```
public final double getLeftMargin()
```


Λαμβάνει το μέγεθος του αριστερού περιθωρίου σε σημεία.


**Returns:**
double - Το μέγεθος του αριστερού περιθωρίου σε σημεία.

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Αποκτά μια τιμή που υποδεικνύει εάν η σελίδα είναι ορατή στη διεπαφή χρήστη.


**Returns:**
boolean - Η τιμή που υποδεικνύει εάν η σελίδα είναι ορατή στη διεπαφή χρήστη. True εάν η σελίδα είναι ορατή· αλλιώς, false.

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν η σελίδα είναι ορατή στη διεπαφή χρήστη.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | Η τιμή που υποδεικνύει εάν η σελίδα είναι ορατή στη διεπαφή χρήστη. True εάν η σελίδα είναι ορατή· αλλιώς, false. |
|

### getName() {#getName--}
```
public final String getName()
```


Αποκτά το όνομα αυτού
DiagramPage
.


**Returns:**
java.lang.String - Το όνομα αυτού του  DiagramPage .

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [DiagramShapeSettings](../../com.groupdocs.watermark.internal/diagramshapesettings) |  |

### convertValueFromDrawingScaleToPageScale(DoubleValue value) {#convertValueFromDrawingScaleToPageScale-com.aspose.diagram.DoubleValue-}
```
public final double convertValueFromDrawingScaleToPageScale(DoubleValue value)
```


<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | com.aspose.diagram.DoubleValue |  |

**Returns:**
double
