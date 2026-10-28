---
title: "PresentationBaseShape"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Παρέχει την αφηρημένη βασική κλάση για σχήματα όλων των τύπων σε ένα έγγραφο PowerPoint."
type: docs
weight: 77
url: /el/java/com.groupdocs.watermark.contents/presentationbaseshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject), [com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public abstract class PresentationBaseShape extends ShapeSearchAdapter implements ITwoDObject, IPresentationHyperlinkContainer
```

Παρέχει την αφηρημένη βασική κλάση για σχήματα όλων των τύπων σε ένα έγγραφο PowerPoint.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPresentation()](#getPresentation--) | Λαμβάνει την γονική παρουσίαση αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | Λαμβάνει τις ρυθμίσεις μορφής γεμίσματος εικόνας αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getName()](#getName--) | Λαμβάνει το όνομα αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Λαμβάνει το περιγραφικό (εναλλακτικό) κείμενο που σχετίζεται με αυτό το `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Ορίζει το περιγραφικό (εναλλακτικό) κείμενο που σχετίζεται με αυτό το `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getId()](#getId--) | Λαμβάνει το αναγνωριστικό αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getZOrderPosition()](#getZOrderPosition--) | Λαμβάνει τη θέση αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` στη σειρά z. |
|
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | Λαμβάνει τον υπερσύνδεσμο που σχετίζεται με αυτό το `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | Ορίζει τον υπερσύνδεσμο που σχετίζεται με αυτό το `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getX()](#getX--) | Λαμβάνει την οριζόντια απόσταση αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` από το αριστερό όριο της παρουσίασης σε σημεία. |
|
|  | [setX(double value)](#setX-double-) | Ορίζει την οριζόντια απόσταση αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` από το αριστερό όριο της παρουσίασης σε σημεία. |
|
|  | [getY()](#getY--) | Λαμβάνει ή ορίζει την κάθετη απόσταση αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` από το άνω όριο της παρουσίασης σε σημεία. |
|
|  | [setY(double value)](#setY-double-) | Λαμβάνει ή ορίζει την κάθετη απόσταση αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` από το άνω όριο της παρουσίασης σε σημεία. |
|
|  | [getWidth()](#getWidth--) | Λαμβάνει το πλάτος αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` σε σημεία. |
|
|  | [setWidth(double value)](#setWidth-double-) | Ορίζει το πλάτος αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` σε σημεία. |
|
|  | [getHeight()](#getHeight--) | Λαμβάνει το ύψος αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` σε σημεία. |
|
|  | [setHeight(double value)](#setHeight-double-) | Ορίζει το ύψος αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` σε σημεία. |
|
### getPresentation() {#getPresentation--}
```
public final PresentationBaseSlide getPresentation()
```


Λαμβάνει την γονική παρουσίαση αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
[PresentationBaseSlide](../../com.groupdocs.watermark.contents/presentationbaseslide) - The parent presentation of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getImageFillFormat() {#getImageFillFormat--}
```
public final PresentationImageFillFormat getImageFillFormat()
```


Λαμβάνει τις ρυθμίσεις μορφής γεμίσματος εικόνας αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
[PresentationImageFillFormat](../../com.groupdocs.watermark.contents/presentationimagefillformat) - The image fill format settings of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getName() {#getName--}
```
public final String getName()
```


Λαμβάνει το όνομα αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
java.lang.String - Το όνομα αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Λαμβάνει το περιγραφικό (εναλλακτικό) κείμενο που σχετίζεται με αυτό το `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
java.lang.String - Το περιγραφικό (εναλλακτικό) κείμενο που σχετίζεται με αυτό το `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Ορίζει το περιγραφικό (εναλλακτικό) κείμενο που σχετίζεται με αυτό το `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Το περιγραφικό (εναλλακτικό) κείμενο που σχετίζεται με αυτό το `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|

### getId() {#getId--}
```
public final long getId()
```


Λαμβάνει το αναγνωριστικό αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
long - Το αναγνωριστικό αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getZOrderPosition() {#getZOrderPosition--}
```
public final int getZOrderPosition()
```


Λαμβάνει τη θέση αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` στη σειρά z.

Ένα σχήμα με μεγαλύτερη σειρά z είναι πάντα μπροστά από ένα σχήμα με χαμηλότερη σειρά z.


**Returns:**
int - Η θέση αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` στη σειρά z.

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


Λαμβάνει τον υπερσύνδεσμο που σχετίζεται με αυτό το `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | actionType | int | Η ενέργεια που ενεργοποιεί τον υπερσύνδεσμο. |
|

**Returns:**
java.lang.String - Η διεύθυνση URL του υπερσυνδέσμου που ενεργοποιείται με την καθορισμένη ενέργεια.

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


Ορίζει τον υπερσύνδεσμο που σχετίζεται με αυτό το `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | actionType | int | Η ενέργεια που ενεργοποιεί τον υπερσύνδεσμο. |
|
|  | διεύθυνση URL | java.lang.String | Η διεύθυνση URL του υπερσυνδέσμου. |
|

### getX() {#getX--}
```
public final double getX()
```


Λαμβάνει την οριζόντια απόσταση αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` από το αριστερό όριο της παρουσίασης σε σημεία.


**Returns:**
double - Η συντεταγμένη x αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Ορίζει την οριζόντια απόσταση αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` από το αριστερό όριο της παρουσίασης σε σημεία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Η συντεταγμένη x αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Λαμβάνει ή ορίζει την κάθετη απόσταση αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` από το άνω όριο της παρουσίασης σε σημεία.


**Returns:**
double - Η συντεταγμένη y αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Λαμβάνει ή ορίζει την κάθετη απόσταση αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` από το άνω όριο της παρουσίασης σε σημεία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Η συντεταγμένη y αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Λαμβάνει το πλάτος αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` σε σημεία.


**Returns:**
double - Το πλάτος αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` σε πόντους.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Ορίζει το πλάτος αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` σε σημεία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Το πλάτος αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` σε πόντους. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Λαμβάνει το ύψος αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` σε σημεία.


**Returns:**
double - Το ύψος αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` σε πόντους.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Ορίζει το ύψος αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` σε σημεία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Το ύψος αυτού του `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` σε πόντους. |
|

