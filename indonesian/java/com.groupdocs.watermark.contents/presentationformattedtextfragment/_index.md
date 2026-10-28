---
title: "PresentationFormattedTextFragment"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili fragmen teks terformat dalam dokumen PowerPoint."
type: docs
weight: 82
url: /id/java/com.groupdocs.watermark.contents/presentationformattedtextfragment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public class PresentationFormattedTextFragment extends FormattedTextFragment implements IPresentationHyperlinkContainer
```

Mewakili fragmen teks terformat dalam dokumen PowerPoint.

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
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | Mendapatkan hyperlink yang terkait dengan teks. |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | Mengatur hyperlink yang terkait dengan teks. |
|
### getText() {#getText--}
```
public String getText()
```


Mendapatkan teks fragmen.


**Returns:**
java.lang.String - Teks fragmen.

### getFont() {#getFont--}
```
public Font getFont()
```


Mendapatkan font teks.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Mendapatkan warna latar depan teks.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Mendapatkan warna latar belakang teks.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


Mendapatkan hyperlink yang terkait dengan teks.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | actionType | int | Aksi yang mengaktifkan hyperlink. |
|

**Returns:**
java.lang.String - url dari hyperlink yang diaktifkan pada aksi yang ditentukan.

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


Mengatur hyperlink yang terkait dengan teks.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | actionType | int | Aksi yang mengaktifkan hyperlink. |
|
|  | url | java.lang.String | URL hyperlink. |
|

