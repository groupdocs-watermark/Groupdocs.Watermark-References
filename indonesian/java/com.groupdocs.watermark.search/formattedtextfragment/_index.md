---
title: "FormattedTextFragment"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Menyediakan kelas dasar abstrak untuk fragmen teks terformat dalam konten."
type: docs
weight: 26
url: /id/java/com.groupdocs.watermark.search/formattedtextfragment/
---
**Inheritance:**
java.lang.Object
```
public abstract class FormattedTextFragment
```

Menyediakan kelas dasar abstrak untuk fragmen teks terformat dalam konten.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FormattedTextFragment()](#FormattedTextFragment--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getText()](#getText--) | Mendapatkan teks fragmen. |
|
|  | [getFont()](#getFont--) | Mendapatkan font teks. |
|
|  | [getForegroundColor()](#getForegroundColor--) | Mendapatkan warna latar depan teks. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Mendapatkan warna latar belakang teks. |
|
### FormattedTextFragment() {#FormattedTextFragment--}
```
public FormattedTextFragment()
```




### getText() {#getText--}
```
public abstract String getText()
```


Mendapatkan teks fragmen.


**Returns:**
java.lang.String - Teks fragmen.

### getFont() {#getFont--}
```
public abstract Font getFont()
```


Mendapatkan font teks.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public abstract Color getForegroundColor()
```


Mendapatkan warna latar depan teks.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public abstract Color getBackgroundColor()
```


Mendapatkan warna latar belakang teks.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

