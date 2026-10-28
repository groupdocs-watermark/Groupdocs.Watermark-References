---
title: "PresentationWatermarkBaseSlideOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Kelas dasar untuk opsi penambahan watermark ke dokumen Presentasi."
type: docs
weight: 39
url: /id/java/com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)
```
public abstract class PresentationWatermarkBaseSlideOptions extends PresentationWatermarkOptions
```

Kelas dasar untuk opsi penambahan watermark ke dokumen Presentasi.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

Contoh berikut menunjukkan cara menambahkan watermark ke slide layanan yang berbeda dari presentasi Power Point.
>
> ````
> ```
>
>    PresentationLoadOptions loadOptions = new PresentationLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pptx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 8));
>
>    // Add watermark to all master slides
>    PresentationWatermarkMasterSlideOptions masterSlideOptions = new PresentationWatermarkMasterSlideOptions();
>    masterSlideOptions.setMasterSlideIndex(-1); // default
>    watermarker.add(watermark, masterSlideOptions);
>    
>    // Add watermark to all layout slides
>    PresentationWatermarkLayoutSlideOptions layoutSlideOptions = new PresentationWatermarkLayoutSlideOptions();
>    layoutSlideOptions.setLayoutSlideIndex(-1); // default
>    watermarker.add(watermark, layoutSlideOptions);
>    
>    // Add watermark to all notes slides
>    PresentationWatermarkNoteSlideOptions noteSlideOptions = new PresentationWatermarkNoteSlideOptions();
>    noteSlideOptions.setSlideIndex(-1); // default
>    watermarker.add(watermark, noteSlideOptions);
>    
>    // Add watermark to handout master
>    PresentationWatermarkMasterHandoutSlideOptions masterHandoutSlideOptions = new PresentationWatermarkMasterHandoutSlideOptions();
>    watermarker.add(watermark, masterHandoutSlideOptions);
>    
>    // Add watermark to notes master
>    PresentationWatermarkMasterNotesSlideOptions masterNotesSlideOptions = new PresentationWatermarkMasterNotesSlideOptions();
>    watermarker.add(watermark, masterNotesSlideOptions);
>    
>    watermarker.save("D:\\watermarked_test.pptx");
>    watermarker.close();
>  
> ```
> ````


## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isLocked()](#isLocked--) | Mendapatkan nilai yang menunjukkan apakah penyuntingan bentuk di PowerPoint dilarang. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Menetapkan nilai yang menunjukkan apakah penyuntingan bentuk di PowerPoint dilarang. |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | Mendapatkan atau menetapkan nilai yang menunjukkan apakah karakter watermark teks dicampur dengan karakter yang tidak dapat dibaca. |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | Mendapatkan atau menetapkan nilai yang menunjukkan apakah karakter watermark teks dicampur dengan karakter yang tidak dapat dibaca. |
|
|  | [getName()](#getName--) | Mendapatkan nama shape. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Mengatur nama shape. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Mendapatkan teks deskriptif (alternatif) yang akan terkait dengan shape. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Mengatur teks deskriptif (alternatif) yang akan terkait dengan shape. |
|
|  | [getEffects()](#getEffects--) | Mendapatkan nilai dari `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` atau `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` untuk efek yang harus diterapkan pada watermark. |
|
|  | [setEffects(IPresentationWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-) | Menetapkan nilai dari `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` atau `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` untuk efek yang harus diterapkan pada watermark. |
|
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Mendapatkan nilai yang menunjukkan apakah penyuntingan bentuk di PowerPoint dilarang.


**Returns:**
boolean - Jika nilai true, penyuntingan bentuk akan dilarang. Secara default, nilai false, bentuk dapat disunting di PowerPoint.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Menetapkan nilai yang menunjukkan apakah penyuntingan bentuk di PowerPoint dilarang.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | boolean | Jika nilai true, penyuntingan bentuk akan dilarang. Secara default, nilai false, bentuk dapat disunting di PowerPoint. |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


Mendapatkan atau menetapkan nilai yang menunjukkan apakah karakter watermark teks dicampur dengan karakter yang tidak dapat dibaca.

Perlindungan ini berlaku hanya ketika `#isLocked().isLocked()` mengembalikan `true`.


**Returns:**
boolean - Nilai yang menunjukkan apakah karakter watermark teks dicampur dengan karakter yang tidak dapat dibaca.

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


Mendapatkan atau menetapkan nilai yang menunjukkan apakah karakter watermark teks dicampur dengan karakter yang tidak dapat dibaca.

Perlindungan ini berlaku hanya ketika `#isLocked().isLocked()` mengembalikan `true`.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | boolean | Nilai yang menunjukkan apakah karakter watermark teks dicampur dengan karakter yang tidak dapat dibaca. |
|

### getName() {#getName--}
```
public final String getName()
```


Mendapatkan nama shape.


**Returns:**
java.lang.String - Nama shape.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Mengatur nama shape.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | Nama shape. |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Mendapatkan teks deskriptif (alternatif) yang akan terkait dengan shape.


**Returns:**
java.lang.String - Teks deskriptif (alternatif) yang akan dikaitkan dengan sebuah bentuk.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Mengatur teks deskriptif (alternatif) yang akan terkait dengan shape.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | Teks deskriptif (alternatif) yang akan dikaitkan dengan sebuah bentuk. |
|

### getEffects() {#getEffects--}
```
public final IPresentationWatermarkEffects getEffects()
```


Mendapatkan nilai dari `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` atau `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` untuk efek yang harus diterapkan pada watermark.


**Returns:**
[IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) - The value of `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` or `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` for effects that should be applied to the watermark.

### setEffects(IPresentationWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-}
```
public final void setEffects(IPresentationWatermarkEffects value)
```


Menetapkan nilai dari `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` atau `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` untuk efek yang harus diterapkan pada watermark.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) | Nilai dari `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` atau `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` untuk efek yang harus diterapkan pada watermark. |
|

