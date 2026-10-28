---
title: "PresentationShapeSettings"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά ρυθμίσεις που μπορούν να εφαρμοστούν σε υδατογράφημα σχήματος για ένα έγγραφο PowerPoint."
type: docs
weight: 95
url: /el/java/com.groupdocs.watermark.contents/presentationshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class PresentationShapeSettings extends OfficeShapeSettings
```

Αναπαριστά ρυθμίσεις που μπορούν να εφαρμοστούν σε υδατογράφημα σχήματος για ένα έγγραφο PowerPoint.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PresentationShapeSettings()](#PresentationShapeSettings--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)`. |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [UnreadableCharacter](#UnreadableCharacter) | <br /> |

|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isLocked()](#isLocked--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η επεξεργασία του σχήματος στο PowerPoint είναι απαγορευμένη. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν η επεξεργασία του σχήματος στο PowerPoint είναι απαγορευμένη. |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | Λαμβάνει μια τιμή που υποδεικνύει εάν οι χαρακτήρες υδατογραφίας κειμένου είναι αναμεμιγμένοι με μη αναγνώσιμους χαρακτήρες. |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν οι χαρακτήρες υδατογραφίας κειμένου είναι αναμεμιγμένοι με μη αναγνώσιμους χαρακτήρες. |
|
### PresentationShapeSettings() {#PresentationShapeSettings--}
```
public PresentationShapeSettings()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)`.


### UnreadableCharacter {#UnreadableCharacter}
```
public static final char UnreadableCharacter
```


<br />



### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η επεξεργασία του σχήματος στο PowerPoint είναι απαγορευμένη.


**Returns:**
boolean - `true` εάν η επεξεργασία σχήματος απαγορεύεται, `false` εάν το σχήμα μπορεί να επεξεργαστεί στο PowerPoint.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν η επεξεργασία του σχήματος στο PowerPoint είναι απαγορευμένη.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | `true` εάν η επεξεργασία σχήματος πρέπει να απαγορευτεί, `false` εάν το σχήμα μπορεί να επεξεργαστεί στο PowerPoint. |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν οι χαρακτήρες υδατογραφίας κειμένου είναι αναμεμιγμένοι με μη αναγνώσιμους χαρακτήρες.

Αυτή η προστασία εφαρμόζεται μόνο όταν η `#isLocked().isLocked()` επιστρέφει `true`.


**Returns:**
boolean - Μια τιμή που υποδεικνύει εάν οι χαρακτήρες του κειμένου υδατογραφήματος αναμιγνύονται με μη αναγνώσιμους χαρακτήρες.

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν οι χαρακτήρες υδατογραφίας κειμένου είναι αναμεμιγμένοι με μη αναγνώσιμους χαρακτήρες.

Αυτή η προστασία εφαρμόζεται μόνο όταν η `#isLocked().isLocked()` επιστρέφει `true`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | Μια τιμή που υποδεικνύει εάν οι χαρακτήρες υδατογράφησης κειμένου είναι αναμεμιγμένοι με μη αναγνώσιμους χαρακτήρες. |
|

