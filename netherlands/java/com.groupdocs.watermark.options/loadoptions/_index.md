---
title: "LoadOptions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt opties voor het laden van een document voor bij het laden van een document."
type: docs
weight: 24
url: /nl/java/com.groupdocs.watermark.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Stelt opties voor het laden van een document voor bij het laden van een document.

**Learn more:**

* [Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents)
* [Load from local disk](../https://docs.groupdocs.com/display/watermarkjava/Load+from+local+disk)
* [Load from stream](../https://docs.groupdocs.com/display/watermarkjava/Load+from+stream)
* [Load document of specific format](../https://docs.groupdocs.com/display/watermarkjava/Load+document+of+specific+format)
* [Load password-protected document](../https://docs.groupdocs.com/display/watermarkjava/Load+password-protected+document)

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Initialiseert een nieuw exemplaar van de `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` klasse. |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Initialiseert een nieuw exemplaar van de `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` klasse met een opgegeven wachtwoord. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPassword()](#getPassword--) | Haalt het wachtwoord op voor het openen van een versleuteld document. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Stelt het wachtwoord in voor het openen van een versleuteld document. |
|
|  | [getFormatFamily()](#getFormatFamily--) | Haal de formaatfamilie van het document op, die het type aangeeft (bijv. Image, Pdf, Spreadsheet, enz.). |
|
|  | [setFormatFamily(int formatFamily)](#setFormatFamily-int-) | Stel de formaatfamilie van het document in, die het type aangeeft (bijv. Image, Pdf, Spreadsheet, enz.). |
|
|  | [getFileType()](#getFileType--) | Haal het type van het bestand op, dat het type aangeeft (bijv. docx, pdf, xlsx, enz.). |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.watermark.common.FileType-) | Stel het type van het bestand in, dat het type aangeeft (bijv. docx, pdf, xlsx, enz.). |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initialiseert een nieuw exemplaar van de `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` klasse.


### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Initialiseert een nieuw exemplaar van de `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` klasse met een opgegeven wachtwoord.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | wachtwoord | java.lang.String | Het wachtwoord om versleutelde inhoud te openen. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Haalt het wachtwoord op voor het openen van een versleuteld document.


**Returns:**
java.lang.String - Het wachtwoord voor het openen van een versleuteld document.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Stelt het wachtwoord in voor het openen van een versleuteld document.

Het wachtwoord mag null of een lege string zijn. De standaardwaarde is null.
Als de inhoud niet versleuteld is, stel dit in op null of een lege string.

Het volgende voorbeeld laat zien hoe je een document laadt dat met een wachtwoord is beveiligd.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | Het wachtwoord voor het openen van een versleuteld document. |
|

### getFormatFamily() {#getFormatFamily--}
```
public int getFormatFamily()
```


Haal de formaatfamilie van het document op, die het type aangeeft (bijv. Image, Pdf, Spreadsheet, enz.).


**Returns:**
int - formatFamily Het bestandstype.

### setFormatFamily(int formatFamily) {#setFormatFamily-int-}
```
public void setFormatFamily(int formatFamily)
```


Stel de formaatfamilie van het document in, die het type aangeeft (bijv. Image, Pdf, Spreadsheet, enz.).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | formatFamily | int | Het bestandstype. |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Haal het type van het bestand op, dat het type aangeeft (bijv. docx, pdf, xlsx, enz.).


**Returns:**
[FileType](../../com.groupdocs.watermark.common/filetype) - fileType The file type.

### setFileType(FileType fileType) {#setFileType-com.groupdocs.watermark.common.FileType-}
```
public void setFileType(FileType fileType)
```


Stel het type van het bestand in, dat het type aangeeft (bijv. docx, pdf, xlsx, enz.).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.watermark.common/filetype) | Het bestandstype. |
|

