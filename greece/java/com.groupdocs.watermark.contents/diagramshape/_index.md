---
title: "DiagramShape"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει ένα σχήμα σχεδίασης σε ένα έγγραφο Visio."
type: docs
weight: 24
url: /el/java/com.groupdocs.watermark.contents/diagramshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class DiagramShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

Αντιπροσωπεύει ένα σχήμα σχεδίασης σε ένα έγγραφο Visio.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getPage()](#getPage--) | Λαμβάνει τη γονική σελίδα αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getWidth()](#getWidth--) | Λαμβάνει το πλάτος αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` σε σημεία. |
|
|  | [setWidth(double value)](#setWidth-double-) | Ορίζει το πλάτος αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` σε σημεία. |
|
|  | [getHeight()](#getHeight--) | Λαμβάνει το ύψος αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` σε σημεία. |
|
|  | [setHeight(double value)](#setHeight-double-) | Ορίζει το ύψος αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` σε σημεία. |
|
|  | [getX()](#getX--) | Λαμβάνει την οριζόντια μετατόπιση αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` από το αριστερό άκρο της σελίδας σε σημεία. |
|
|  | [setX(double value)](#setX-double-) | Ορίζει την οριζόντια μετατόπιση αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` από το αριστερό άκρο της σελίδας σε σημεία. |
|
|  | [getY()](#getY--) | Λαμβάνει την κάθετη μετατόπιση αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` από το κάτω άκρο της σελίδας σε σημεία. |
|
|  | [setY(double value)](#setY-double-) | Ορίζει την κάθετη μετατόπιση αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` από το κάτω άκρο της σελίδας σε σημεία. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Λαμβάνει ή ορίζει τη γωνία περιστροφής αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` σε μοίρες. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Λαμβάνει ή ορίζει τη γωνία περιστροφής αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` σε μοίρες. |
|
|  | [getText()](#getText--) | Λαμβάνει ή ορίζει το κείμενο αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Λαμβάνει ή ορίζει το κείμενο αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Λαμβάνει τη συλλογή των μορφοποιημένων τμημάτων κειμένου αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getImage()](#getImage--) | Λαμβάνει την εικόνα αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [setImage(DiagramWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-) | Ορίζει την εικόνα αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getId()](#getId--) | Λαμβάνει το αναγνωριστικό αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getName()](#getName--) | Λαμβάνει το όνομα αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getHyperlinks()](#getHyperlinks--) | Λαμβάνει τη συλλογή των υπερσυνδέσμων που είναι συνημμένοι σε αυτό το `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getAsposeShape()](#getAsposeShape--) | <br /> |

|
|  | [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) | <br /> |

|
|  | [getImageForSearch()](#getImageForSearch--) | <br /> |

|
|  | [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) | <br /> |

|
|  | [getTextForSearch()](#getTextForSearch--) | <br /> |

|
|  | [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) | <br /> |

|
### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```




**Returns:**
java.lang.Integer
### getPage() {#getPage--}
```
public final DiagramPage getPage()
```


Λαμβάνει τη γονική σελίδα αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The parent page of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Λαμβάνει το πλάτος αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` σε σημεία.


**Returns:**
double - Το πλάτος αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` σε σημεία.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Ορίζει το πλάτος αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` σε σημεία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Το πλάτος αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` σε σημεία. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Λαμβάνει το ύψος αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` σε σημεία.


**Returns:**
double - Το ύψος αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` σε σημεία.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Ορίζει το ύψος αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` σε σημεία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Το ύψος αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` σε σημεία. |
|

### getX() {#getX--}
```
public final double getX()
```


Λαμβάνει την οριζόντια μετατόπιση αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` από το αριστερό άκρο της σελίδας σε σημεία.


**Returns:**
double - Η οριζόντια μετατόπιση αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` από το αριστερό άκρο της σελίδας σε σημεία.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Ορίζει την οριζόντια μετατόπιση αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` από το αριστερό άκρο της σελίδας σε σημεία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Η οριζόντια μετατόπιση αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` από το αριστερό άκρο της σελίδας σε σημεία. |
|

### getY() {#getY--}
```
public final double getY()
```


Λαμβάνει την κάθετη μετατόπιση αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` από το κάτω άκρο της σελίδας σε σημεία.


**Returns:**
double - Η κάθετη μετατόπιση αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` από το κάτω άκρο της σελίδας σε σημεία.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Ορίζει την κάθετη μετατόπιση αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` από το κάτω άκρο της σελίδας σε σημεία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Η κάθετη μετατόπιση αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` από το κάτω άκρο της σελίδας σε σημεία. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Λαμβάνει ή ορίζει τη γωνία περιστροφής αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` σε μοίρες.


**Returns:**
double - Η γωνία περιστροφής αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` σε μοίρες.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Λαμβάνει ή ορίζει τη γωνία περιστροφής αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` σε μοίρες.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Η γωνία περιστροφής αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` σε μοίρες. |
|

### getText() {#getText--}
```
public final String getText()
```


Λαμβάνει ή ορίζει το κείμενο αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
java.lang.String - Το κείμενο αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Λαμβάνει ή ορίζει το κείμενο αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Το κείμενο αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Λαμβάνει τη συλλογή των μορφοποιημένων τμημάτων κειμένου αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getImage() {#getImage--}
```
public final DiagramWatermarkableImage getImage()
```


Λαμβάνει την εικόνα αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
[DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) - The image of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### setImage(DiagramWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-}
```
public final void setImage(DiagramWatermarkableImage value)
```


Ορίζει την εικόνα αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) | Η εικόνα αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|

### getId() {#getId--}
```
public final long getId()
```


Λαμβάνει το αναγνωριστικό αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
long - Το αναγνωριστικό αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getName() {#getName--}
```
public final String getName()
```


Λαμβάνει το όνομα αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
java.lang.String - Το όνομα αυτού του `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getHyperlinks() {#getHyperlinks--}
```
public final DiagramHyperlinkCollection getHyperlinks()
```


Λαμβάνει τη συλλογή των υπερσυνδέσμων που είναι συνημμένοι σε αυτό το `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
[DiagramHyperlinkCollection](../../com.groupdocs.watermark.contents/diagramhyperlinkcollection) - The collection of hyperlinks attached to this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getAsposeShape() {#getAsposeShape--}
```
public final Shape getAsposeShape()
```


<br />



**Returns:**
com.aspose.diagram.Shape
### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```


<br />



**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
### getImageForSearch() {#getImageForSearch--}
```
public WatermarkableImage getImageForSearch()
```


<br />



**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```


<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageData | byte[] |  |

### getTextForSearch() {#getTextForSearch--}
```
public String getTextForSearch()
```


<br />



**Returns:**
java.lang.String
### setFoundWatermarkText(String value) {#setFoundWatermarkText-java.lang.String-}
```
public void setFoundWatermarkText(String value)
```


<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

