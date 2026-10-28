---
title: "PresentationWatermarkMasterSlideOptions"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει τις επιλογές κατά την προσθήκη υδατογραφήματος σε κύρια διαφάνεια εγγράφου Παρουσίασης."
type: docs
weight: 43
url: /el/java/com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkMasterSlideOptions extends PresentationWatermarkBaseSlideOptions
```

Αντιπροσωπεύει τις επιλογές κατά την προσθήκη υδατογραφήματος σε κύρια διαφάνεια εγγράφου Παρουσίασης.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

Δείτε τα παραδείγματα χρήσης στο `[PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)`.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PresentationWatermarkMasterSlideOptions()](#PresentationWatermarkMasterSlideOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)`. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getMasterSlideIndex()](#getMasterSlideIndex--) | Λαμβάνει το δείκτη της κύριας διαφάνειας στην οποία θα προστεθεί το υδατογράφημα. |
|
|  | [setMasterSlideIndex(int value)](#setMasterSlideIndex-int-) | Ορίζει το δείκτη της κύριας διαφάνειας στην οποία θα προστεθεί το υδατογράφημα. |
|
### PresentationWatermarkMasterSlideOptions() {#PresentationWatermarkMasterSlideOptions--}
```
public PresentationWatermarkMasterSlideOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)`.


### getMasterSlideIndex() {#getMasterSlideIndex--}
```
public final int getMasterSlideIndex()
```


Λαμβάνει το δείκτη της κύριας διαφάνειας στην οποία θα προστεθεί το υδατογράφημα.


**Returns:**
int - Ο δείκτης της κύριας διαφάνειας στην οποία θα προστεθεί το υδατογράφημα.

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setMasterSlideIndex(int value) {#setMasterSlideIndex-int-}
```
public final void setMasterSlideIndex(int value)
```


Ορίζει το δείκτη της κύριας διαφάνειας στην οποία θα προστεθεί το υδατογράφημα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Ο δείκτης της κύριας διαφάνειας στην οποία θα προστεθεί το υδατογράφημα. |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

