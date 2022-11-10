---
title: LoadOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Represents document loading options when loading a document.
type: docs
weight: 24
url: /java/com.groupdocs.watermark.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Represents document loading options when loading a document.

**Learn more:**

 *  [Loading documents][]
 *  [Load from local disk][]
 *  [Load from stream][]
 *  [Load document of specific format][]
 *  [Load password-protected document][]


[Loading documents]: https://docs.groupdocs.com/display/watermarkjava/Loading+documents
[Load from local disk]: https://docs.groupdocs.com/display/watermarkjava/Load+from+local+disk
[Load from stream]: https://docs.groupdocs.com/display/watermarkjava/Load+from+stream
[Load document of specific format]: https://docs.groupdocs.com/display/watermarkjava/Load+document+of+specific+format
[Load password-protected document]: https://docs.groupdocs.com/display/watermarkjava/Load+password-protected+document
## Constructors

| Constructor | Description |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Initializes a new instance of the `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` class. |
| [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Initializes a new instance of the `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` class with a specified password. |
## Methods

| Method | Description |
| --- | --- |
| [getPassword()](#getPassword--) | Gets the password for opening an encrypted document. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Sets the password for opening an encrypted document. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initializes a new instance of the `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` class.

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Initializes a new instance of the `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` class with a specified password.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | The password for opening an encrypted content. |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Gets the password for opening an encrypted document.

**Returns:**
java.lang.String - The password for opening an encrypted document.
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Sets the password for opening an encrypted document.

The password be null or empty string. The default value is null. If the content is not encrypted, set this to null or empty string.

The following example demonstrates how to load a document protected with a password.

> ```
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
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The password for opening an encrypted document. |

