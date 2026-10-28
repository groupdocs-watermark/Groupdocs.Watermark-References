---
title: "PresentationShape"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά ένα σχήμα σχεδίασης σε ένα έγγραφο PowerPoint."
type: docs
weight: 93
url: /el/java/com.groupdocs.watermark.contents/presentationshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class PresentationShape extends PresentationBaseShape implements IRotatableTwoDObject
```

Αναπαριστά ένα σχήμα σχεδίασης σε ένα έγγραφο PowerPoint.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | Λαμβάνει τη γωνία περιστροφής αυτού του `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` σε μοίρες. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Ορίζει τη γωνία περιστροφής αυτού του `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` σε μοίρες. |
|
|  | [getText()](#getText--) | Λαμβάνει το κείμενο αυτού του `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Ορίζει το κείμενο αυτού του `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Λαμβάνει τη συλλογή των μορφοποιημένων τμημάτων κειμένου αυτού του `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [getShapeType()](#getShapeType--) | Λαμβάνει τον προκαθορισμένο τύπο γεωμετρίας σχήματος. |
|
|  | [getImage()](#getImage--) | Λαμβάνει την εικόνα αυτού του `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [setImage(PresentationWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | Ορίζει την εικόνα αυτού του `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [getImageForSearch()](#getImageForSearch--) | <br /> |

|
|  | [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) | <br /> |

|
|  | [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) | <br /> |

|
|  | [getTextForSearch()](#getTextForSearch--) | <br /> |

|
|  | [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) | <br /> |

|
### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Λαμβάνει τη γωνία περιστροφής αυτού του `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` σε μοίρες.


**Returns:**
double - Η γωνία περιστροφής αυτού του `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` σε μοίρες.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Ορίζει τη γωνία περιστροφής αυτού του `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` σε μοίρες.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Η γωνία περιστροφής αυτού του `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` σε μοίρες. |
|

### getText() {#getText--}
```
public final String getText()
```


Λαμβάνει το κείμενο αυτού του `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Returns:**
java.lang.String - Το κείμενο αυτού του `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Ορίζει το κείμενο αυτού του `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Το κείμενο αυτού του `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Λαμβάνει τη συλλογή των μορφοποιημένων τμημάτων κειμένου αυτού του `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Λαμβάνει τον προκαθορισμένο τύπο γεωμετρίας σχήματος.


**Returns:**
int - Ο τύπος προκαθορισμένης γεωμετρίας.

### getImage() {#getImage--}
```
public final PresentationWatermarkableImage getImage()
```


Λαμβάνει την εικόνα αυτού του `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The image of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` or null if the shape has no image.

### setImage(PresentationWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public final void setImage(PresentationWatermarkableImage value)
```


Ορίζει την εικόνα αυτού του `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | Η εικόνα αυτού του `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` ή null εάν η εικόνα πρέπει να αφαιρεθεί. |
|

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

### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```


<br />



**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
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

