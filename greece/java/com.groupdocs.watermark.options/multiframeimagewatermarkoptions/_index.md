---
title: "MultiframeImageWatermarkOptions"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει τις επιλογές προσθήκης υδατογράφηματος κατά την προσθήκη υδατογραφήματος σε μια εικόνα πολλαπλών πλαισίων."
type: docs
weight: 26
url: /el/java/com.groupdocs.watermark.options/multiframeimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions)
```
public class MultiframeImageWatermarkOptions extends WatermarkOptions
```

Αντιπροσωπεύει τις επιλογές προσθήκης υδατογράφηματος κατά την προσθήκη υδατογραφήματος σε μια εικόνα πολλαπλών πλαισίων.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε ένα υδατογράφημα σε ένα συγκεκριμένο πλαίσιο μιας εικόνας πολλαπλών πλαισίων.
>
> ````
> ```
>
>    ImageLoadOptions loadOptions = new ImageLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\test.gif", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));
>
>    MultiframeImageWatermarkOptions options = new MultiframeImageWatermarkOptions();
>    options.setFrameIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.gif");
>    watermarker.close();
>  
> ```
> ````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [MultiframeImageWatermarkOptions()](#MultiframeImageWatermarkOptions--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)`. |
|
|  | [MultiframeImageWatermarkOptions(int frameIndex)](#MultiframeImageWatermarkOptions-int-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` με καθορισμένο δείκτη του πλαισίου. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFrameIndex()](#getFrameIndex--) | Αποκτά τον δείκτη του πλαισίου για την προσθήκη υδατογραφήματος. |
|
|  | [setFrameIndex(int value)](#setFrameIndex-int-) | Ορίζει τον δείκτη του πλαισίου για την προσθήκη υδατογραφήματος. |
|
### MultiframeImageWatermarkOptions() {#MultiframeImageWatermarkOptions--}
```
public MultiframeImageWatermarkOptions()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)`.


### MultiframeImageWatermarkOptions(int frameIndex) {#MultiframeImageWatermarkOptions-int-}
```
public MultiframeImageWatermarkOptions(int frameIndex)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` με καθορισμένο δείκτη του πλαισίου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | frameIndex | int | Ο δείκτης του πλαισίου για την προσθήκη υδατογραφήματος. |
|

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```


Αποκτά τον δείκτη του πλαισίου για την προσθήκη υδατογραφήματος.


**Returns:**
int - Ο δείκτης του πλαισίου για την προσθήκη υδατογραφήματος.

<br />

*** ** * ** ***

-1 means all frames.

<br />


### setFrameIndex(int value) {#setFrameIndex-int-}
```
public final void setFrameIndex(int value)
```


Ορίζει τον δείκτη του πλαισίου για την προσθήκη υδατογραφήματος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Ο δείκτης του πλαισίου για την προσθήκη υδατογραφήματος. |

<br />

*** ** * ** ***

-1 means all frames.

<br />

|

