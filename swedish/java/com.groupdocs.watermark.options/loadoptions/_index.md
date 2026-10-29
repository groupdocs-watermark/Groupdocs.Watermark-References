---
title: "LoadOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar alternativ för dokumentladdning när ett dokument laddas."
type: docs
weight: 24
url: /sv/java/com.groupdocs.watermark.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Representerar alternativ för dokumentladdning när ett dokument laddas.

**Learn more:**

* [Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents)
* [Load from local disk](../https://docs.groupdocs.com/display/watermarkjava/Load+from+local+disk)
* [Load from stream](../https://docs.groupdocs.com/display/watermarkjava/Load+from+stream)
* [Load document of specific format](../https://docs.groupdocs.com/display/watermarkjava/Load+document+of+specific+format)
* [Load password-protected document](../https://docs.groupdocs.com/display/watermarkjava/Load+password-protected+document)

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Initierar en ny instans av klassen `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)`. |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Initierar en ny instans av klassen `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` med ett specificerat lösenord. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPassword()](#getPassword--) | Hämtar lösenordet för att öppna ett krypterat dokument. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ställer in lösenordet för att öppna ett krypterat dokument. |
|
|  | [getFormatFamily()](#getFormatFamily--) | Hämta formatfamiljen för dokumentet, vilket anger dess typ (t.ex. Bild, Pdf, Kalkylblad, etc.). |
|
|  | [setFormatFamily(int formatFamily)](#setFormatFamily-int-) | Ställ in formatfamiljen för dokumentet, vilket anger dess typ (t.ex. Bild, Pdf, Kalkylblad, etc.). |
|
|  | [getFileType()](#getFileType--) | Hämta filens typ, vilket anger dess typ (t.ex. docx, pdf, xlsx, etc.). |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.watermark.common.FileType-) | Ställ in filens typ, vilket anger dess typ (t.ex. docx, pdf, xlsx, etc.). |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initierar en ny instans av klassen `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)`.


### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Initierar en ny instans av klassen `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` med ett specificerat lösenord.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | lösenord | java.lang.String | Lösenordet för att öppna krypterat innehåll. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Hämtar lösenordet för att öppna ett krypterat dokument.


**Returns:**
java.lang.String - Lösenordet för att öppna ett krypterat dokument.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ställer in lösenordet för att öppna ett krypterat dokument.

Lösenordet kan vara null eller en tom sträng. Standardvärdet är null.
Om innehållet inte är krypterat, sätt detta till null eller en tom sträng.

Följande exempel visar hur man laddar ett dokument som är skyddat med ett lösenord.
>
> ````
> ```
>
>    LoadOptions loadOptions = new LoadOptions();
>    loadOptions.setPassword("pwd123");
>  
>    Watermarker watermarker = new Watermarker("D:\\doc.vsdx", loadOptions);
>    // ...
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.String | Lösenordet för att öppna ett krypterat dokument. |
|

### getFormatFamily() {#getFormatFamily--}
```
public int getFormatFamily()
```


Hämta formatfamiljen för dokumentet, vilket anger dess typ (t.ex. Bild, Pdf, Kalkylblad, etc.).


**Returns:**
int - formatFamily Filtypen.

### setFormatFamily(int formatFamily) {#setFormatFamily-int-}
```
public void setFormatFamily(int formatFamily)
```


Ställ in formatfamiljen för dokumentet, vilket anger dess typ (t.ex. Bild, Pdf, Kalkylblad, etc.).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | formatFamily | int | Filtypen. |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Hämta filens typ, vilket anger dess typ (t.ex. docx, pdf, xlsx, etc.).


**Returns:**
[FileType](../../com.groupdocs.watermark.common/filetype) - fileType The file type.

### setFileType(FileType fileType) {#setFileType-com.groupdocs.watermark.common.FileType-}
```
public void setFileType(FileType fileType)
```


Ställ in filens typ, vilket anger dess typ (t.ex. docx, pdf, xlsx, etc.).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.watermark.common/filetype) | Filtypen. |
|

