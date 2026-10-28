---
title: "WatermarkerSettings"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Ορίζει ρυθμίσεις για την προσαρμογή της συμπεριφοράς του Watermarker."
type: docs
weight: 15
url: /el/java/com.groupdocs.watermark/watermarkersettings/
---
**Inheritance:**
java.lang.Object
```
public final class WatermarkerSettings
```

Ορίζει ρυθμίσεις για την προσαρμογή της συμπεριφοράς του Watermarker.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [WatermarkerSettings()](#WatermarkerSettings--) | Αρχικοποιεί νέα παρουσία του |
WatermarkerSettings
της κλάσης.
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | Λαμβάνει |
SearchableObjects
που πρέπει να συμπεριληφθούν σε αναζήτηση υδατογραφήματος.
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | Ορίζει |
SearchableObjects
που πρέπει να συμπεριληφθούν σε αναζήτηση υδατογραφήματος.
|
|  | [getLogger()](#getLogger--) | Λαμβάνει τον καταγραφέα που χρησιμοποιείται για την καταγραφή συμβάντων και σφαλμάτων κατά τη δημιουργία υδατογραφήματος. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.watermark.options.ILogger-) | Ορίζει τον καταγραφέα που χρησιμοποιείται για την καταγραφή συμβάντων και σφαλμάτων κατά τη δημιουργία υδατογραφήματος. |
|
| [logError(WatermarkException exception, String format, Object[] args)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-) |  |
| [logError(WatermarkException exception)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-) |  |
| [logWarning(String format, Object[] args)](#logWarning-java.lang.String-java.lang.Object...-) |  |
| [logTrace(String format, Object[] args)](#logTrace-java.lang.String-java.lang.Object...-) |  |
### WatermarkerSettings() {#WatermarkerSettings--}
```
public WatermarkerSettings()
```


Αρχικοποιεί νέα παρουσία του
WatermarkerSettings
της κλάσης.


### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


Λαμβάνει
SearchableObjects
που πρέπει να συμπεριληφθούν σε αναζήτηση υδατογραφήματος.


**Returns:**
[SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) - The  SearchableObjects  that are to be included in a watermark search.

### setSearchableObjects(SearchableObjects value) {#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-}
```
public final void setSearchableObjects(SearchableObjects value)
```


Ορίζει
SearchableObjects
που πρέπει να συμπεριληφθούν σε αναζήτηση υδατογραφήματος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | Τα  SearchableObjects  που πρέπει να συμπεριληφθούν σε αναζήτηση υδατογραφήματος. |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Λαμβάνει τον καταγραφέα που χρησιμοποιείται για την καταγραφή συμβάντων και σφαλμάτων κατά τη δημιουργία υδατογραφήματος.


**Returns:**
[ILogger](../../com.groupdocs.watermark.options/ilogger) - An instance of class that implements `[ILogger](../../com.groupdocs.watermark.options/ilogger)` interface.

### setLogger(ILogger value) {#setLogger-com.groupdocs.watermark.options.ILogger-}
```
public final void setLogger(ILogger value)
```


Ορίζει τον καταγραφέα που χρησιμοποιείται για την καταγραφή συμβάντων και σφαλμάτων κατά τη δημιουργία υδατογραφήματος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [ILogger](../../com.groupdocs.watermark.options/ilogger) | Ένα στιγμιότυπο κλάσης που υλοποιεί τη διεπαφή `[ILogger](../../com.groupdocs.watermark.options/ilogger)`. |
|

### logError(WatermarkException exception, String format, Object[] args) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-}
```
public final void logError(WatermarkException exception, String format, Object[] args)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |
| μορφή | java.lang.String |  |
| ορίσματα | java.lang.Object[] |  |

### logError(WatermarkException exception) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-}
```
public final void logError(WatermarkException exception)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |

### logWarning(String format, Object[] args) {#logWarning-java.lang.String-java.lang.Object...-}
```
public final void logWarning(String format, Object[] args)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μορφή | java.lang.String |  |
| ορίσματα | java.lang.Object[] |  |

### logTrace(String format, Object[] args) {#logTrace-java.lang.String-java.lang.Object...-}
```
public final void logTrace(String format, Object[] args)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μορφή | java.lang.String |  |
| ορίσματα | java.lang.Object[] |  |

