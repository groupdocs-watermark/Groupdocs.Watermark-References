---
title: "WordProcessingShape"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει ένα σχήμα σχεδίασης σε ένα έγγραφο Word."
type: docs
weight: 141
url: /el/java/com.groupdocs.watermark.contents/wordprocessingshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class WordProcessingShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

Αντιπροσωπεύει ένα σχήμα σχεδίασης σε ένα έγγραφο Word.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getSection()](#getSection--) | Λαμβάνει την γονική ενότητα αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getHeaderFooter()](#getHeaderFooter--) | Λαμβάνει την γονική κεφαλίδα/υποσέλιδο αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` (εάν υπάρχει). |
|
|  | [getShapeType()](#getShapeType--) | Λαμβάνει τον τύπο του σχήματος. |
|
|  | [isWordArt()](#isWordArt--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` είναι αντικείμενο WordArt. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Λαμβάνει το περιγραφικό (εναλλακτικό) κείμενο που σχετίζεται με αυτό το `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Ορίζει το περιγραφικό (εναλλακτικό) κείμενο που σχετίζεται με αυτό το `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getName()](#getName--) | Λαμβάνει το όνομα αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getBehindText()](#getBehindText--) | Λαμβάνει μια τιμή που υποδεικνύει εάν το σχήμα είναι πάνω ή πίσω από το κείμενο. |
|
|  | [setBehindText(boolean value)](#setBehindText-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν το σχήμα είναι πάνω ή πίσω από το κείμενο. |
|
|  | [getText()](#getText--) | Λαμβάνει το κείμενο αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Ορίζει το κείμενο αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Λαμβάνει τη συλλογή των μορφοποιημένων τμημάτων κειμένου αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getImage()](#getImage--) | Λαμβάνει την εικόνα αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setImage(WordProcessingWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-) | Ορίζει την εικόνα αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Λαμβάνει μια τιμή που καθορίζει πώς το σχήμα τοποθετείται οριζόντια. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Λαμβάνει μια τιμή που καθορίζει πώς το σχήμα τοποθετείται κάθετα. |
|
|  | [getRelativeHorizontalPosition()](#getRelativeHorizontalPosition--) | Λαμβάνει μια τιμή που καθορίζει προς τι το σχήμα τοποθετείται οριζόντια. |
|
|  | [getRelativeVerticalPosition()](#getRelativeVerticalPosition--) | Λαμβάνει μια τιμή που καθορίζει προς τι το σχήμα τοποθετείται κάθετα. |
|
| [getImageFillFormat()](#getImageFillFormat--) |  |
| [getAsposeWordsShape()](#getAsposeWordsShape--) |  |
|  | [getHyperlink()](#getHyperlink--) | Λαμβάνει τον υπερσύνδεσμο που σχετίζεται με αυτό το `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | Ορίζει τον υπερσύνδεσμο που σχετίζεται με αυτό το `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getWidth()](#getWidth--) | Λαμβάνει το πλάτος αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` σε σημεία. |
|
|  | [setWidth(double value)](#setWidth-double-) | Ορίζει το πλάτος αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` σε σημεία. |
|
|  | [getHeight()](#getHeight--) | Λαμβάνει το ύψος αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` σε μονάδες σημείου. |
|
|  | [setHeight(double value)](#setHeight-double-) | Ορίζει το ύψος αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` σε μονάδες σημείου. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Λαμβάνει τη γωνία περιστροφής αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` σε μοίρες. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Ορίζει τη γωνία περιστροφής αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` σε μοίρες. |
|
|  | [getX()](#getX--) | Λαμβάνει ή ορίζει την οριζόντια μετατόπιση αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` από το αριστερό άκρο της σελίδας σε μονάδες σημείου. |
|
|  | [setX(double value)](#setX-double-) | Λαμβάνει ή ορίζει την οριζόντια μετατόπιση αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` από το αριστερό άκρο της σελίδας σε μονάδες σημείου. |
|
|  | [getY()](#getY--) | Λαμβάνει την κατακόρυφη μετατόπιση αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` από το άνω άκρο της σελίδας σε μονάδες σημείου. |
|
|  | [setY(double value)](#setY-double-) | Ορίζει την κατακόρυφη μετατόπιση αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` από το άνω άκρο της σελίδας σε μονάδες σημείου. |
|
| [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) |  |
| [getTextForSearch()](#getTextForSearch--) |  |
| [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) |  |
| [getImageForSearch()](#getImageForSearch--) |  |
| [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) |  |
### getSection() {#getSection--}
```
public final WordProcessingSection getSection()
```


Λαμβάνει την γονική ενότητα αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection) - The parent section of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getHeaderFooter() {#getHeaderFooter--}
```
public final WordProcessingHeaderFooter getHeaderFooter()
```


Λαμβάνει την γονική κεφαλίδα/υποσέλιδο αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` (εάν υπάρχει).


**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The parent header/footer of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Λαμβάνει τον τύπο του σχήματος.


**Returns:**
int - Ο τύπος σχήματος.

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` είναι αντικείμενο WordArt.


**Returns:**
boolean - True εάν το σχήμα είναι αντικείμενο WordArt· διαφορετικά, false.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Λαμβάνει το περιγραφικό (εναλλακτικό) κείμενο που σχετίζεται με αυτό το `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - Το περιγραφικό (εναλλακτικό) κείμενο που σχετίζεται με αυτό το `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Ορίζει το περιγραφικό (εναλλακτικό) κείμενο που σχετίζεται με αυτό το `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Το περιγραφικό (εναλλακτικό) κείμενο που σχετίζεται με αυτό το `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getName() {#getName--}
```
public final String getName()
```


Λαμβάνει το όνομα αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - Το όνομα αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getBehindText() {#getBehindText--}
```
public final boolean getBehindText()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν το σχήμα είναι πάνω ή πίσω από το κείμενο.


**Returns:**
boolean - Η τιμή που υποδεικνύει εάν το σχήμα είναι πάνω ή πίσω από το κείμενο. Αληθές εάν το σχήμα είναι πίσω από το κείμενο· διαφορετικά, ψευδές.

### setBehindText(boolean value) {#setBehindText-boolean-}
```
public final void setBehindText(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν το σχήμα είναι πάνω ή πίσω από το κείμενο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | Η τιμή που υποδεικνύει εάν το σχήμα είναι πάνω ή πίσω από το κείμενο. Αληθές εάν το σχήμα είναι πίσω από το κείμενο· διαφορετικά, ψευδές. |
|

### getText() {#getText--}
```
public final String getText()
```


Λαμβάνει το κείμενο αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - Το κείμενο αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Ορίζει το κείμενο αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Το κείμενο αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Λαμβάνει τη συλλογή των μορφοποιημένων τμημάτων κειμένου αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getImage() {#getImage--}
```
public final WordProcessingWatermarkableImage getImage()
```


Λαμβάνει την εικόνα αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
[WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) - The image of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` or `null` if the shape has no image.

### setImage(WordProcessingWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-}
```
public final void setImage(WordProcessingWatermarkableImage value)
```


Ορίζει την εικόνα αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) | Η εικόνα αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ή `null` εάν η εικόνα πρέπει να αφαιρεθεί. |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Λαμβάνει μια τιμή που καθορίζει πώς το σχήμα τοποθετείται οριζόντια.


**Returns:**
int - Η τιμή οριζόντιας στοίχισης.

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Λαμβάνει μια τιμή που καθορίζει πώς το σχήμα τοποθετείται κάθετα.


**Returns:**
int - Η τιμή κατακόρυφης στοίχισης.

### getRelativeHorizontalPosition() {#getRelativeHorizontalPosition--}
```
public final int getRelativeHorizontalPosition()
```


Λαμβάνει μια τιμή που καθορίζει προς τι το σχήμα τοποθετείται οριζόντια.


**Returns:**
int - Η τιμή σχετικής οριζόντιας θέσης.

### getRelativeVerticalPosition() {#getRelativeVerticalPosition--}
```
public final int getRelativeVerticalPosition()
```


Λαμβάνει μια τιμή που καθορίζει προς τι το σχήμα τοποθετείται κάθετα.


**Returns:**
int - Η τιμή σχετικής κατακόρυφης θέσης.

### getImageFillFormat() {#getImageFillFormat--}
```
public final WordProcessingImageFillFormat getImageFillFormat()
```




**Returns:**
[WordProcessingImageFillFormat](../../com.groupdocs.watermark.internal/wordprocessingimagefillformat)
### getAsposeWordsShape() {#getAsposeWordsShape--}
```
public final Shape getAsposeWordsShape()
```




**Returns:**
com.aspose.words.Shape
### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


Λαμβάνει τον υπερσύνδεσμο που σχετίζεται με αυτό το `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - Ο υπερσύνδεσμος που σχετίζεται με αυτό το `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


Ορίζει τον υπερσύνδεσμο που σχετίζεται με αυτό το `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Ο υπερσύνδεσμος που σχετίζεται με αυτό το `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Λαμβάνει το πλάτος αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` σε σημεία.


**Returns:**
double - Το πλάτος αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` σε μονάδες σημείου.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Ορίζει το πλάτος αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` σε σημεία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Το πλάτος αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` σε μονάδες σημείου. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Λαμβάνει το ύψος αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` σε μονάδες σημείου.


**Returns:**
double - Το ύψος αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` σε πόντους.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Ορίζει το ύψος αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` σε μονάδες σημείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Το ύψος αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` σε πόντους. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Λαμβάνει τη γωνία περιστροφής αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` σε μοίρες.


**Returns:**
double - Η γωνία περιστροφής αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` σε μοίρες.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Ορίζει τη γωνία περιστροφής αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` σε μοίρες.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Η γωνία περιστροφής αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` σε μοίρες. |
|

### getX() {#getX--}
```
public final double getX()
```


Λαμβάνει ή ορίζει την οριζόντια μετατόπιση αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` από το αριστερό άκρο της σελίδας σε μονάδες σημείου.


**Returns:**
double - Η συντεταγμένη x αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Λαμβάνει ή ορίζει την οριζόντια μετατόπιση αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` από το αριστερό άκρο της σελίδας σε μονάδες σημείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Η συντεταγμένη x αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Λαμβάνει την κατακόρυφη μετατόπιση αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` από το άνω άκρο της σελίδας σε μονάδες σημείου.


**Returns:**
double - Η συντεταγμένη y αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Ορίζει την κατακόρυφη μετατόπιση αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` από το άνω άκρο της σελίδας σε μονάδες σημείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Η συντεταγμένη y αυτού του `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```




**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
### getTextForSearch() {#getTextForSearch--}
```
public String getTextForSearch()
```




**Returns:**
java.lang.String
### setFoundWatermarkText(String value) {#setFoundWatermarkText-java.lang.String-}
```
public void setFoundWatermarkText(String value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getImageForSearch() {#getImageForSearch--}
```
public WatermarkableImage getImageForSearch()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageData | byte[] |  |

