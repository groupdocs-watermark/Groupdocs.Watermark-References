---
title: "PagesSelector"
second_title: "GroupDocs.Watermark για Java API Reference"
description: 
type: docs
weight: 10
url: /el/java/com.groupdocs.watermark/pagesselector/
---
**Inheritance:**
java.lang.Object
```
public class PagesSelector
```

<br />


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PagesSelector()](#PagesSelector--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--) | Λαμβάνει μια λίστα σελίδων βάσει της καθορισμένης ρύθμισης. |
|
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-) | Λαμβάνει μια λίστα επιλεγμένων σελίδων βάσει των καθορισμένων κριτηρίων. |
|
### PagesSelector() {#PagesSelector--}
```
public PagesSelector()
```


### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)
```


Λαμβάνει μια λίστα σελίδων βάσει της καθορισμένης ρύθμισης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | allPages | boolean | Εάν θα συμπεριληφθούν όλες οι σελίδες. |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | Η διαμόρφωση ρύθμισης σελίδων. |
|
|  | totalPages | int | Ο συνολικός αριθμός σελίδων. |
|
|  | pageIndex | com.aspose.ms.System.Nullable<java.lang.Integer> | Ο συγκεκριμένος δείκτης σελίδας (αρχίζοντας από 0). |
|

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Μια λίστα σελίδων βάσει της καθορισμένης ρύθμισης.

### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)
```


Λαμβάνει μια λίστα επιλεγμένων σελίδων βάσει των καθορισμένων κριτηρίων.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | allPages | boolean | Μία σημαία που υποδεικνύει αν θα συμπεριληφθούν όλες οι σελίδες. |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | Η διαμόρφωση ρύθμισης για τις σελίδες. |
|
|  | totalPages | int | Ο συνολικός αριθμός σελίδων στο έγγραφο. |
|
|  | pageNumbers | int[] | Ένας πίνακας συγκεκριμένων αριθμών σελίδων προς συμπερίληψη. |
|
| fromOne | boolean |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Μια ταξινομημένη και διακριτή λίστα επιλεγμένων αριθμών σελίδων.

