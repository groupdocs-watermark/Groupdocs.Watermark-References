---
title: "PresentationFormattedTextFragment"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά ένα τμήμα μορφοποιημένου κειμένου σε ένα έγγραφο PowerPoint."
type: docs
weight: 82
url: /el/java/com.groupdocs.watermark.contents/presentationformattedtextfragment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public class PresentationFormattedTextFragment extends FormattedTextFragment implements IPresentationHyperlinkContainer
```

Αναπαριστά ένα τμήμα μορφοποιημένου κειμένου σε ένα έγγραφο PowerPoint.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getText()](#getText--) | Λαμβάνει το κείμενο του τμήματος. |
|
|  | [getFont()](#getFont--) | Λαμβάνει τη γραμματοσειρά του κειμένου. |
|
|  | [getForegroundColor()](#getForegroundColor--) | Λαμβάνει το χρώμα προσκλήρου του κειμένου. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Λαμβάνει το χρώμα φόντου του κειμένου. |
|
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | Λαμβάνει τον υπερσύνδεσμο που σχετίζεται με το κείμενο. |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | Ορίζει τον υπερσύνδεσμο που σχετίζεται με το κείμενο. |
|
### getText() {#getText--}
```
public String getText()
```


Λαμβάνει το κείμενο του τμήματος.


**Returns:**
java.lang.String - Το κείμενο του τμήματος.

### getFont() {#getFont--}
```
public Font getFont()
```


Λαμβάνει τη γραμματοσειρά του κειμένου.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Λαμβάνει το χρώμα προσκλήρου του κειμένου.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Λαμβάνει το χρώμα φόντου του κειμένου.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


Λαμβάνει τον υπερσύνδεσμο που σχετίζεται με το κείμενο.


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


Ορίζει τον υπερσύνδεσμο που σχετίζεται με το κείμενο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | actionType | int | Η ενέργεια που ενεργοποιεί τον υπερσύνδεσμο. |
|
|  | διεύθυνση URL | java.lang.String | Η διεύθυνση URL του υπερσυνδέσμου. |
|

