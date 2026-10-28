---
title: "WordProcessingLockType"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Καθορίζει τον τύπο κλειδώματος του υδατογραφήματος σε έγγραφο Word."
type: docs
weight: 68
url: /el/java/com.groupdocs.watermark.options/wordprocessinglocktype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingLockType
```

Καθορίζει τον τύπο κλειδώματος του υδατογραφήματος σε έγγραφο Word.

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [AllowOnlyRevisions](#AllowOnlyRevisions) | Ο χρήστης μπορεί μόνο να προσθέσει σημάδια αναθεώρησης στο έγγραφο. |
|
|  | [AllowOnlyComments](#AllowOnlyComments) | Ο χρήστης μπορεί μόνο να τροποποιήσει σχόλια στο έγγραφο. |
|
|  | [AllowOnlyFormFields](#AllowOnlyFormFields) | Ο χρήστης μπορεί μόνο να εισάγει δεδομένα στα πεδία φόρμας του εγγράφου. |
|
|  | [ReadOnly](#ReadOnly) | Ολόκληρο το έγγραφο είναι μόνο για ανάγνωση. |
|
|  | [ReadOnlyWithEditableContent](#ReadOnlyWithEditableContent) | Το έγγραφο είναι μόνο για ανάγνωση, αλλά όλο το περιεχόμενο εκτός του υδατογραφήματος είναι σημειωμένο ως επεξεργάσιμο. |
|
|  | [NoLock](#NoLock) | Απενεργοποιήστε οποιοδήποτε κλείδωμα στο υδατογράφημα και στο έγγραφο. |
|
### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final int AllowOnlyRevisions
```


Ο χρήστης μπορεί μόνο να προσθέσει σημάδια αναθεώρησης στο έγγραφο.


### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


Ο χρήστης μπορεί μόνο να τροποποιήσει σχόλια στο έγγραφο.


### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


Ο χρήστης μπορεί μόνο να εισάγει δεδομένα στα πεδία φόρμας του εγγράφου.

<br />

*** ** * ** ***

Το έγγραφο χωρίζεται σε ενότητες μιας σελίδας και προστίθεται κλειδωμένη ενότητα με υδατογράφημα μεταξύ κάθε δύο διαδοχικών ενοτήτων περιεχομένου.

<br />



### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


Ολόκληρο το έγγραφο είναι μόνο για ανάγνωση.


### ReadOnlyWithEditableContent {#ReadOnlyWithEditableContent}
```
public static final int ReadOnlyWithEditableContent
```


Το έγγραφο είναι μόνο για ανάγνωση, αλλά όλο το περιεχόμενο εκτός του υδατογραφήματος είναι σημειωμένο ως επεξεργάσιμο.


### NoLock {#NoLock}
```
public static final int NoLock
```


Απενεργοποιήστε οποιοδήποτε κλείδωμα στο υδατογράφημα και στο έγγραφο.


