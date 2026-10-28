---
title: "Font"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Κλάση που αναπαριστά μια γραμματοσειρά."
type: docs
weight: 11
url: /el/java/com.groupdocs.watermark.watermarks/font/
---
**Inheritance:**
java.lang.Object
```
public final class Font
```

Κλάση που αναπαριστά μια γραμματοσειρά.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `[Font](../../com.groupdocs.watermark.watermarks/font)` με καθορισμένο όνομα οικογένειας γραμματοσειράς και μέγεθος. |
|
|  | [Font(String fontFamilyName, float size, int style)](#Font-java.lang.String-float-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `[Font](../../com.groupdocs.watermark.watermarks/font)` με καθορισμένο όνομα οικογένειας γραμματοσειράς, μέγεθος και στυλ. |
|
| [Font(String fontFamilyName, String folderPath, float size)](#Font-java.lang.String-java.lang.String-float-) |  |
| [Font(String fontFamilyName, String folderPath, float size, FontStyle style)](#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFolderPath()](#getFolderPath--) |  |
| [setFolderPath(String folderPath)](#setFolderPath-java.lang.String-) |  |
|  | [getFamilyName()](#getFamilyName--) | Επιστρέφει το όνομα οικογένειας αυτής της `[Font](../../com.groupdocs.watermark.watermarks/font)`. |
|
|  | [getSize()](#getSize--) | Επιστρέφει το μέγεθος αυτής της `[Font](../../com.groupdocs.watermark.watermarks/font)`. |
|
|  | [getStyle()](#getStyle--) | Επιστρέφει το `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` για αυτήν τη `[Font](../../com.groupdocs.watermark.watermarks/font)`. |
|
|  | [getBold()](#getBold--) | Επιστρέφει μια τιμή που υποδεικνύει αν η γραμματοσειρά είναι έντονη. |
|
|  | [getItalic()](#getItalic--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η γραμματοσειρά είναι πλάγια. |
|
|  | [getStrikeout()](#getStrikeout--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η γραμματοσειρά καθορίζει μια οριζόντια γραμμή μέσα στη γραμματοσειρά. |
|
|  | [getUnderline()](#getUnderline--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η γραμματοσειρά είναι υπογραμμισμένη. |
|
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `[Font](../../com.groupdocs.watermark.watermarks/font)` με καθορισμένο όνομα οικογένειας γραμματοσειράς και μέγεθος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | Το όνομα οικογένειας γραμματοσειράς. |
|
|  | size | float | Το μέγεθος της νέας γραμματοσειράς. |
|

### Font(String fontFamilyName, float size, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontFamilyName, float size, int style)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `[Font](../../com.groupdocs.watermark.watermarks/font)` με καθορισμένο όνομα οικογένειας γραμματοσειράς, μέγεθος και στυλ.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | Το όνομα οικογένειας γραμματοσειράς. |
|
|  | size | float | Το μέγεθος της νέας γραμματοσειράς. |
|
|  | style | int | Το `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` της νέας γραμματοσειράς. |
|

### Font(String fontFamilyName, String folderPath, float size) {#Font-java.lang.String-java.lang.String-float-}
```
public Font(String fontFamilyName, String folderPath, float size)
```


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontFamilyName | java.lang.String |  |
| folderPath | java.lang.String |  |
| size | float |  |

### Font(String fontFamilyName, String folderPath, float size, FontStyle style) {#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-}
```
public Font(String fontFamilyName, String folderPath, float size, FontStyle style)
```


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontFamilyName | java.lang.String |  |
| folderPath | java.lang.String |  |
| size | float |  |
| style | [FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle) |  |

### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```




**Returns:**
java.lang.String
### setFolderPath(String folderPath) {#setFolderPath-java.lang.String-}
```
public void setFolderPath(String folderPath)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| folderPath | java.lang.String |  |

### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Επιστρέφει το όνομα οικογένειας αυτής της `[Font](../../com.groupdocs.watermark.watermarks/font)`.


**Returns:**
java.lang.String - Το όνομα οικογένειας αυτού του `[Font](../../com.groupdocs.watermark.watermarks/font)`.

### getSize() {#getSize--}
```
public final float getSize()
```


Επιστρέφει το μέγεθος αυτής της `[Font](../../com.groupdocs.watermark.watermarks/font)`.


**Returns:**
float - Το μέγεθος αυτού του `[Font](../../com.groupdocs.watermark.watermarks/font)`.

### getStyle() {#getStyle--}
```
public final int getStyle()
```


Επιστρέφει το `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` για αυτήν τη `[Font](../../com.groupdocs.watermark.watermarks/font)`.

Η προεπιλεγμένη τιμή είναι `[FontStyle.Regular](../../com.groupdocs.watermark.watermarks/fontstyle#Regular)` (κανονικό κείμενο).


**Returns:**
int - Το `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` αυτού του `[Font](../../com.groupdocs.watermark.watermarks/font)`.

### getBold() {#getBold--}
```
public final boolean getBold()
```


Επιστρέφει μια τιμή που υποδεικνύει αν η γραμματοσειρά είναι έντονη.


**Returns:**
boolean - Αληθές εάν αυτή η γραμματοσειρά είναι έντονη· διαφορετικά, ψευδές.

### getItalic() {#getItalic--}
```
public final boolean getItalic()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η γραμματοσειρά είναι πλάγια.


**Returns:**
boolean - Αληθές εάν αυτή η γραμματοσειρά είναι πλάγια· διαφορετικά, ψευδές.

### getStrikeout() {#getStrikeout--}
```
public final boolean getStrikeout()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η γραμματοσειρά καθορίζει μια οριζόντια γραμμή μέσα στη γραμματοσειρά.


**Returns:**
boolean - Αληθές εάν αυτή η γραμματοσειρά καθορίζει μια οριζόντια γραμμή μέσα στη γραμματοσειρά· διαφορετικά, ψευδές.

### getUnderline() {#getUnderline--}
```
public final boolean getUnderline()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η γραμματοσειρά είναι υπογραμμισμένη.


**Returns:**
boolean - Αληθές εάν αυτή η γραμματοσειρά είναι υπογραμμισμένη· διαφορετικά, ψευδές.

