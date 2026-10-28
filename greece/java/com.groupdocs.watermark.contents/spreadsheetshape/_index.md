---
title: "SpreadsheetShape"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει ένα σχήμα σχεδίασης σε ένα έγγραφο Excel."
type: docs
weight: 117
url: /el/java/com.groupdocs.watermark.contents/spreadsheetshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class SpreadsheetShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

Αντιπροσωπεύει ένα σχήμα σχεδίασης σε ένα έγγραφο Excel.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getWorksheet()](#getWorksheet--) | Λαμβάνει το γονικό φύλλο εργασίας αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getAutoShapeType()](#getAutoShapeType--) | Λαμβάνει τον τύπο αυτόματου σχήματος. |
|
|  | [getMsoDrawingType()](#getMsoDrawingType--) | Λαμβάνει τον τύπο σχεδίασης mso. |
|
|  | [getText()](#getText--) | Λαμβάνει το κείμενο αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Ορίζει το κείμενο αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Λαμβάνει τη συλλογή των μορφοποιημένων τμημάτων κειμένου αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getImage()](#getImage--) | Λαμβάνει την εικόνα αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setImage(SpreadsheetWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Ορίζει την εικόνα αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | Λαμβάνει τις ρυθμίσεις μορφής γεμίσματος εικόνας αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getId()](#getId--) | Λαμβάνει το αναγνωριστικό αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Λαμβάνει το περιγραφικό (εναλλακτικό) κείμενο που σχετίζεται με αυτό το `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Ορίζει το περιγραφικό (εναλλακτικό) κείμενο που σχετίζεται με αυτό το `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [isWordArt()](#isWordArt--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` είναι αντικείμενο WordArt. |
|
|  | [getName()](#getName--) | Λαμβάνει το όνομα αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getAsposeCellsShape()](#getAsposeCellsShape--) | <br /> |

|
|  | [getHyperlink()](#getHyperlink--) | Λαμβάνει τον υπερσύνδεσμο που σχετίζεται με αυτό το `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | Ορίζει τον υπερσύνδεσμο που σχετίζεται με αυτό το `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getX()](#getX--) | Λαμβάνει την οριζόντια απόσταση αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` από το αριστερό όριο του φύλλου εργασίας σε σημεία. |
|
|  | [setX(double value)](#setX-double-) | Ορίζει την οριζόντια απόσταση αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` από το αριστερό όριο του φύλλου εργασίας σε σημεία. |
|
|  | [getY()](#getY--) | Λαμβάνει την κάθετη απόσταση αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` από το άνω όριο του φύλλου εργασίας σε σημεία. |
|
|  | [setY(double value)](#setY-double-) | Ορίζει την κάθετη απόσταση αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` από το άνω όριο του φύλλου εργασίας σε σημεία. |
|
|  | [getWidth()](#getWidth--) | Λαμβάνει το πλάτος αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` σε σημεία. |
|
|  | [setWidth(double value)](#setWidth-double-) | Ορίζει το πλάτος αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` σε σημεία. |
|
|  | [getHeight()](#getHeight--) | Λαμβάνει το ύψος αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` σε σημεία. |
|
|  | [setHeight(double value)](#setHeight-double-) | Ορίζει το ύψος αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` σε σημεία. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Λαμβάνει ή ορίζει τη γωνία περιστροφής αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` σε μοίρες. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Λαμβάνει ή ορίζει τη γωνία περιστροφής αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` σε μοίρες. |
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
### getWorksheet() {#getWorksheet--}
```
public final SpreadsheetWorksheet getWorksheet()
```


Λαμβάνει το γονικό φύλλο εργασίας αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) - The parent worksheet of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAutoShapeType() {#getAutoShapeType--}
```
public final int getAutoShapeType()
```


Λαμβάνει τον τύπο αυτόματου σχήματος.


**Returns:**
int - Ο τύπος αυτόματου σχήματος.

### getMsoDrawingType() {#getMsoDrawingType--}
```
public final int getMsoDrawingType()
```


Λαμβάνει τον τύπο σχεδίασης mso.


**Returns:**
int - Ο τύπος σχεδίασης mso.

### getText() {#getText--}
```
public final String getText()
```


Λαμβάνει το κείμενο αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - Το κείμενο αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Ορίζει το κείμενο αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Το κείμενο αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Λαμβάνει τη συλλογή των μορφοποιημένων τμημάτων κειμένου αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getImage() {#getImage--}
```
public final SpreadsheetWatermarkableImage getImage()
```


Λαμβάνει την εικόνα αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The image of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` or null if the shape has no image.

### setImage(SpreadsheetWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setImage(SpreadsheetWatermarkableImage value)
```


Ορίζει την εικόνα αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | Η εικόνα αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ή null εάν η εικόνα πρέπει να αφαιρεθεί. |
|

### getImageFillFormat() {#getImageFillFormat--}
```
public final SpreadsheetImageFillFormat getImageFillFormat()
```


Λαμβάνει τις ρυθμίσεις μορφής γεμίσματος εικόνας αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[SpreadsheetImageFillFormat](../../com.groupdocs.watermark.contents/spreadsheetimagefillformat) - The image fill format settings of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getId() {#getId--}
```
public final int getId()
```


Λαμβάνει το αναγνωριστικό αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
int - Το αναγνωριστικό αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Λαμβάνει το περιγραφικό (εναλλακτικό) κείμενο που σχετίζεται με αυτό το `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - Το περιγραφικό (εναλλακτικό) κείμενο που σχετίζεται με αυτό το `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Ορίζει το περιγραφικό (εναλλακτικό) κείμενο που σχετίζεται με αυτό το `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Το περιγραφικό (εναλλακτικό) κείμενο που σχετίζεται με αυτό το `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` είναι αντικείμενο WordArt.


**Returns:**
boolean - True εάν το σχήμα είναι αντικείμενο WordArt· διαφορετικά, false.

### getName() {#getName--}
```
public final String getName()
```


Λαμβάνει το όνομα αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - Το όνομα αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAsposeCellsShape() {#getAsposeCellsShape--}
```
public final Shape getAsposeCellsShape()
```


<br />



**Returns:**
com.aspose.cells.Shape
### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


Λαμβάνει τον υπερσύνδεσμο που σχετίζεται με αυτό το `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - Ο υπερσύνδεσμος που σχετίζεται με αυτό το `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


Ορίζει τον υπερσύνδεσμο που σχετίζεται με αυτό το `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Ο υπερσύνδεσμος που σχετίζεται με αυτό το `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getX() {#getX--}
```
public final double getX()
```


Λαμβάνει την οριζόντια απόσταση αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` από το αριστερό όριο του φύλλου εργασίας σε σημεία.


**Returns:**
double - Η συντεταγμένη x αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Ορίζει την οριζόντια απόσταση αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` από το αριστερό όριο του φύλλου εργασίας σε σημεία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Η συντεταγμένη x αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Λαμβάνει την κάθετη απόσταση αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` από το άνω όριο του φύλλου εργασίας σε σημεία.


**Returns:**
double - Η συντεταγμένη y αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Ορίζει την κάθετη απόσταση αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` από το άνω όριο του φύλλου εργασίας σε σημεία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Η συντεταγμένη y αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Λαμβάνει το πλάτος αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` σε σημεία.


**Returns:**
double - Το πλάτος αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` σε σημεία.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Ορίζει το πλάτος αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` σε σημεία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Το πλάτος αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` σε σημεία. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Λαμβάνει το ύψος αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` σε σημεία.


**Returns:**
double - Το ύψος αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` σε σημεία.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Ορίζει το ύψος αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` σε σημεία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Το ύψος αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` σε σημεία. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Λαμβάνει ή ορίζει τη γωνία περιστροφής αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` σε μοίρες.


**Returns:**
double - Η γωνία περιστροφής αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` σε μοίρες.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Λαμβάνει ή ορίζει τη γωνία περιστροφής αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` σε μοίρες.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Η γωνία περιστροφής αυτού του `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` σε μοίρες. |
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

