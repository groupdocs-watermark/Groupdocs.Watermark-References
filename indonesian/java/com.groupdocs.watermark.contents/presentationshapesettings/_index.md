---
title: "PresentationShapeSettings"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili pengaturan yang dapat diterapkan pada watermark bentuk untuk dokumen PowerPoint."
type: docs
weight: 95
url: /id/java/com.groupdocs.watermark.contents/presentationshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class PresentationShapeSettings extends OfficeShapeSettings
```

Mewakili pengaturan yang dapat diterapkan pada watermark bentuk untuk dokumen PowerPoint.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PresentationShapeSettings()](#PresentationShapeSettings--) | Menginisialisasi instance baru dari kelas `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)`. |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [UnreadableCharacter](#UnreadableCharacter) | <br /> |

|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isLocked()](#isLocked--) | Mendapatkan nilai yang menunjukkan apakah penyuntingan bentuk di PowerPoint dilarang. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Menetapkan nilai yang menunjukkan apakah penyuntingan bentuk di PowerPoint dilarang. |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | Mendapatkan nilai yang menunjukkan apakah karakter watermark teks dicampur dengan karakter yang tidak dapat dibaca. |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | Mengatur nilai yang menunjukkan apakah karakter watermark teks dicampur dengan karakter yang tidak dapat dibaca. |
|
### PresentationShapeSettings() {#PresentationShapeSettings--}
```
public PresentationShapeSettings()
```


Menginisialisasi instance baru dari kelas `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)`.


### UnreadableCharacter {#UnreadableCharacter}
```
public static final char UnreadableCharacter
```


<br />



### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Mendapatkan nilai yang menunjukkan apakah penyuntingan bentuk di PowerPoint dilarang.


**Returns:**
boolean - `true` jika penyuntingan bentuk dilarang, `false` jika bentuk dapat disunting di PowerPoint.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Menetapkan nilai yang menunjukkan apakah penyuntingan bentuk di PowerPoint dilarang.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | boolean | `true` jika penyuntingan bentuk harus dilarang, `false` jika bentuk dapat disunting di PowerPoint. |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


Mendapatkan nilai yang menunjukkan apakah karakter watermark teks dicampur dengan karakter yang tidak dapat dibaca.

Perlindungan ini berlaku hanya ketika `#isLocked().isLocked()` mengembalikan `true`.


**Returns:**
boolean - Nilai yang menunjukkan apakah karakter watermark teks dicampur dengan karakter yang tidak dapat dibaca.

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


Mengatur nilai yang menunjukkan apakah karakter watermark teks dicampur dengan karakter yang tidak dapat dibaca.

Perlindungan ini berlaku hanya ketika `#isLocked().isLocked()` mengembalikan `true`.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | boolean | Nilai yang menunjukkan apakah karakter watermark teks dicampur dengan karakter yang tidak dapat dibaca. |
|

