---
title: Password
second_title: GroupDocs.Watermark for .NET API Reference
description: Gets or sets the password for opening an encrypted document.
type: docs
weight: 30
url: /net/groupdocs.watermark.options/loadoptions/password/
---
## LoadOptions.Password property

Gets or sets the password for opening an encrypted document.

```csharp
public string Password { get; set; }
```

### Property Value

The password for opening an encrypted document.

### Remarks

The password be null or empty string. The default value is null. If the content is not encrypted, set this to null or empty string.

### Examples

Load a content protected with a password.

```csharp
LoadOptions loadOptions = new LoadOptions
{
    Password = "pwd123"
};
using (Watermarker watermarker = new Watermarker(@"D:\doc.vsdx", loadOptions))
{
    // ...
}
```

### See Also

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Watermark.Options](../../loadoptions)
* assembly [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
