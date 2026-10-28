---
title: "FormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά μια μεταβλητή συλλογή τμημάτων μορφοποιημένου κειμένου."
type: docs
weight: 27
url: /el/java/com.groupdocs.watermark.search/formattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class FormattedTextFragmentCollection extends RemoveOnlyListBase<FormattedTextFragment>
```

Αναπαριστά μια μεταβλητή συλλογή τμημάτων μορφοποιημένου κειμένου.

Αυτή η συλλογή περιέχει τα στοιχεία του βασικού τύπου `[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)`.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FormattedTextFragmentCollection(int collectionType)](#FormattedTextFragmentCollection-int-) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getCollectionType()](#getCollectionType--) | Λαμβάνει τον τύπο της μορφοποιημένης συλλογής τμημάτων. |
|
| [getDefaultFont()](#getDefaultFont--) |  |
| [getDefaultForegroundColor()](#getDefaultForegroundColor--) |  |
| [getDefaultBackgroundColor()](#getDefaultBackgroundColor--) |  |
| [getText()](#getText--) |  |
|  | [add(String text)](#add-java.lang.String-) | Προσθέτει ένα μορφοποιημένο τμήμα κειμένου στη συλλογή. |
|
|  | [add(String text, Font font)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Προσθέτει ένα μορφοποιημένο τμήμα κειμένου στη συλλογή. |
|
|  | [add(String text, Font font, Color foregroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | Προσθέτει ένα μορφοποιημένο τμήμα κειμένου στη συλλογή. |
|
|  | [add(String text, Font font, Color foregroundColor, Color backgroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | Προσθέτει ένα μορφοποιημένο τμήμα κειμένου στη συλλογή. |
|
|  | [insert(int index, String text)](#insert-int-java.lang.String-) | Εισάγει ένα μορφοποιημένο τμήμα κειμένου στη συλλογή σε συγκεκριμένο δείκτη. |
|
|  | [insert(int index, String text, Font font)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Εισάγει ένα μορφοποιημένο τμήμα κειμένου στη συλλογή σε συγκεκριμένο δείκτη. |
|
|  | [insert(int index, String text, Font font, Color foregroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | Εισάγει ένα μορφοποιημένο τμήμα κειμένου στη συλλογή σε συγκεκριμένο δείκτη. |
|
|  | [insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | Εισάγει ένα μορφοποιημένο τμήμα κειμένου στη συλλογή σε συγκεκριμένο δείκτη. |
|
| [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) |  |
| [setText(String text)](#setText-java.lang.String-) |  |
### FormattedTextFragmentCollection(int collectionType) {#FormattedTextFragmentCollection-int-}
```
public FormattedTextFragmentCollection(int collectionType)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| collectionType | int |  |

### getCollectionType() {#getCollectionType--}
```
public final int getCollectionType()
```


Λαμβάνει τον τύπο της μορφοποιημένης συλλογής τμημάτων.


**Returns:**
int - Ο τύπος της μορφοποιημένης συλλογής τμημάτων.

### getDefaultFont() {#getDefaultFont--}
```
public final Font getDefaultFont()
```




**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font)
### getDefaultForegroundColor() {#getDefaultForegroundColor--}
```
public final Color getDefaultForegroundColor()
```




**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
### getDefaultBackgroundColor() {#getDefaultBackgroundColor--}
```
public final Color getDefaultBackgroundColor()
```




**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
### getText() {#getText--}
```
public String getText()
```




**Returns:**
java.lang.String
### add(String text) {#add-java.lang.String-}
```
public final void add(String text)
```


Προσθέτει ένα μορφοποιημένο τμήμα κειμένου στη συλλογή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | κείμενο | java.lang.String | Το κείμενο του τμήματος. |
|

### add(String text, Font font) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void add(String text, Font font)
```


Προσθέτει ένα μορφοποιημένο τμήμα κειμένου στη συλλογή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | κείμενο | java.lang.String | Το κείμενο του τμήματος. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Η γραμματοσειρά του κειμένου. |
|

### add(String text, Font font, Color foregroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor)
```


Προσθέτει ένα μορφοποιημένο τμήμα κειμένου στη συλλογή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | κείμενο | java.lang.String | Το κείμενο του τμήματος. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Η γραμματοσειρά του κειμένου. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Το χρώμα προσκλήρου του κειμένου. |
|

### add(String text, Font font, Color foregroundColor, Color backgroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor, Color backgroundColor)
```


Προσθέτει ένα μορφοποιημένο τμήμα κειμένου στη συλλογή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | κείμενο | java.lang.String | Το κείμενο του τμήματος. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Η γραμματοσειρά του κειμένου. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Το χρώμα προσκλήρου του κειμένου. |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Το χρώμα φόντου του κειμένου. |
|

### insert(int index, String text) {#insert-int-java.lang.String-}
```
public final void insert(int index, String text)
```


Εισάγει ένα μορφοποιημένο τμήμα κειμένου στη συλλογή σε συγκεκριμένο δείκτη.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | δείκτης | int | Ο δείκτης μηδενικής βάσης στον οποίο πρέπει να εισαχθεί το μορφοποιημένο τμήμα κειμένου. |
|
|  | κείμενο | java.lang.String | Το κείμενο του τμήματος. |
|

### insert(int index, String text, Font font) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void insert(int index, String text, Font font)
```


Εισάγει ένα μορφοποιημένο τμήμα κειμένου στη συλλογή σε συγκεκριμένο δείκτη.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | δείκτης | int | Ο δείκτης μηδενικής βάσης στον οποίο πρέπει να εισαχθεί το μορφοποιημένο τμήμα κειμένου. |
|
|  | κείμενο | java.lang.String | Το κείμενο του τμήματος. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Η γραμματοσειρά του κειμένου. |
|

### insert(int index, String text, Font font, Color foregroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor)
```


Εισάγει ένα μορφοποιημένο τμήμα κειμένου στη συλλογή σε συγκεκριμένο δείκτη.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | δείκτης | int | Ο δείκτης μηδενικής βάσης στον οποίο πρέπει να εισαχθεί το μορφοποιημένο τμήμα κειμένου. |
|
|  | κείμενο | java.lang.String | Το κείμενο του τμήματος. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Η γραμματοσειρά του κειμένου. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Το χρώμα προσκλήρου του κειμένου. |
|

### insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```


Εισάγει ένα μορφοποιημένο τμήμα κειμένου στη συλλογή σε συγκεκριμένο δείκτη.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | δείκτης | int | Ο δείκτης μηδενικής βάσης στον οποίο πρέπει να εισαχθεί το μορφοποιημένο τμήμα κειμένου. |
|
|  | κείμενο | java.lang.String | Το κείμενο του τμήματος. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Η γραμματοσειρά του κειμένου. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Το χρώμα προσκλήρου του κειμένου. |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Το χρώμα φόντου του κειμένου. |
|

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int |  |
| κείμενο | java.lang.String |  |
| font | [Font](../../com.groupdocs.watermark.watermarks/font) |  |
| foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |
| backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |

**Returns:**
[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)
### setText(String text) {#setText-java.lang.String-}
```
public void setText(String text)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String |  |

