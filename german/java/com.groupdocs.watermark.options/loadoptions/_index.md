---
title: "LoadOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Dokumentladeoptionen beim Laden eines Dokuments dar."
type: docs
weight: 24
url: /de/java/com.groupdocs.watermark.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Stellt Dokumentladeoptionen beim Laden eines Dokuments dar.

**Learn more:**

* [Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents)
* [Load from local disk](../https://docs.groupdocs.com/display/watermarkjava/Load+from+local+disk)
* [Load from stream](../https://docs.groupdocs.com/display/watermarkjava/Load+from+stream)
* [Load document of specific format](../https://docs.groupdocs.com/display/watermarkjava/Load+document+of+specific+format)
* [Load password-protected document](../https://docs.groupdocs.com/display/watermarkjava/Load+password-protected+document)

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Initialisiert eine neue Instanz der `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` Klasse. |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Initialisiert eine neue Instanz der `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` Klasse mit einem angegebenen Passwort. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPassword()](#getPassword--) | Liest das Passwort zum Öffnen eines verschlüsselten Dokuments. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Setzt das Passwort zum Öffnen eines verschlüsselten Dokuments. |
|
|  | [getFormatFamily()](#getFormatFamily--) | Ermittelt die Formatfamilie des Dokuments, die dessen Typ angibt (z. B. Image, Pdf, Spreadsheet usw.). |
|
|  | [setFormatFamily(int formatFamily)](#setFormatFamily-int-) | Setzt die Formatfamilie des Dokuments, die dessen Typ angibt (z. B. Image, Pdf, Spreadsheet usw.). |
|
|  | [getFileType()](#getFileType--) | Ermittelt den Dateityp, der dessen Typ angibt (z. B. docx, pdf, xlsx usw.). |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.watermark.common.FileType-) | Setzt den Dateityp, der dessen Typ angibt (z. B. docx, pdf, xlsx usw.). |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initialisiert eine neue Instanz der `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` Klasse.


### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Initialisiert eine neue Instanz der `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` Klasse mit einem angegebenen Passwort.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Passwort | java.lang.String | Das Passwort zum Öffnen eines verschlüsselten Inhalts. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Liest das Passwort zum Öffnen eines verschlüsselten Dokuments.


**Returns:**
java.lang.String - Das Passwort zum Öffnen eines verschlüsselten Dokuments.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Setzt das Passwort zum Öffnen eines verschlüsselten Dokuments.

Das Passwort kann null oder ein leerer String sein. Der Standardwert ist null.
Wenn der Inhalt nicht verschlüsselt ist, setzen Sie dies auf null oder einen leeren String.

Das folgende Beispiel zeigt, wie man ein mit einem Passwort geschütztes Dokument lädt.
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Das Passwort zum Öffnen eines verschlüsselten Dokuments. |
|

### getFormatFamily() {#getFormatFamily--}
```
public int getFormatFamily()
```


Ermittelt die Formatfamilie des Dokuments, die dessen Typ angibt (z. B. Image, Pdf, Spreadsheet usw.).


**Returns:**
int - formatFamily Der Dateityp.

### setFormatFamily(int formatFamily) {#setFormatFamily-int-}
```
public void setFormatFamily(int formatFamily)
```


Setzt die Formatfamilie des Dokuments, die dessen Typ angibt (z. B. Image, Pdf, Spreadsheet usw.).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | formatFamily | int | Der Dateityp. |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Ermittelt den Dateityp, der dessen Typ angibt (z. B. docx, pdf, xlsx usw.).


**Returns:**
[FileType](../../com.groupdocs.watermark.common/filetype) - fileType The file type.

### setFileType(FileType fileType) {#setFileType-com.groupdocs.watermark.common.FileType-}
```
public void setFileType(FileType fileType)
```


Setzt den Dateityp, der dessen Typ angibt (z. B. docx, pdf, xlsx usw.).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.watermark.common/filetype) | Der Dateityp. |
|

