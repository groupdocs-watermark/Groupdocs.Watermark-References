---
title: License
second_title: GroupDocs.Watermark for Java API Reference
description: Provides methods to license the component.
type: docs
weight: 10
url: /java/com.groupdocs.watermark.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

Provides methods to license the component.

**Lean more**

 *  More about licensing: [GroupDocs Licensing FAQ][]
 *  More about **GroupDocs.Watermark** licensing: [Evaluation Limitations and Licensing][]

The following example demonstrates demonstrates how to setup license from the local file.

> ```
> ```
> 
>    // Initialize License class.
>    License license = new License();
>  
>    // Set path to .lic file.
>    license.setLicense("C:\\GroupDocs.Watermark.lic");
>  
> ```
> ```


[GroupDocs Licensing FAQ]: https://purchase.groupdocs.com/faqs/licensing
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/watermarkjava/Evaluation+Limitations+and+Licensing
## Constructors

| Constructor | Description |
| --- | --- |
| [License()](#License--) | Initializes a new instance of the `[License](../../com.groupdocs.watermark.licensing/license)` class. |
## Methods

| Method | Description |
| --- | --- |
| [setLicense(String filePath)](#setLicense-java.lang.String-) | Licenses the component. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licenses the component. |
### License() {#License--}
```
public License()
```


Initializes a new instance of the `[License](../../com.groupdocs.watermark.licensing/license)` class.

### setLicense(String filePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String filePath)
```


Licenses the component.

Use this method to load a license from a file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Absolute path to license file. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


Licenses the component.

Use this method to load a license from a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | License stream. |

