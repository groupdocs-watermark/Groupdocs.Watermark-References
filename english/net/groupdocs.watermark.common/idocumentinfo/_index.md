---
title: IDocumentInfo
second_title: GroupDocs.Watermark for .NET API Reference
description: Defines the methods that are required for getting the basic document information.
type: docs
weight: 70
url: /net/groupdocs.watermark.common/idocumentinfo/
---
## IDocumentInfo interface

Defines the methods that are required for getting the basic document information.

```csharp
public interface IDocumentInfo
```

## Properties

| Name | Description |
| --- | --- |
| [FileType](../../groupdocs.watermark.common/idocumentinfo/filetype) { get; } | Gets the file format description. |
| [IsEncrypted](../../groupdocs.watermark.common/idocumentinfo/isencrypted) { get; } | Gets a value indicating whether the document is encrypted and requires a password to open. |
| [PageCount](../../groupdocs.watermark.common/idocumentinfo/pagecount) { get; } | Gets the total page count. |
| [Pages](../../groupdocs.watermark.common/idocumentinfo/pages) { get; } | Gets the collection of document pages descriptions. |
| [Size](../../groupdocs.watermark.common/idocumentinfo/size) { get; } | Gets the document size in bytes. |

### Remarks

**Learn more**

* [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### Examples

The following example demonstrates how to retrieve the general document information using [`IDocumentInfo`](../idocumentinfo).

```csharp
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    IDocumentInfo docInfo = watermarker.GetDocumentInfo();
    Console.WriteLine("Document size: {0}", docInfo.Size);
    Console.WriteLine("Document format: {0}", docInfo.FileType.FileFormat);
    Console.WriteLine("Document contains {0} pages", docInfo.PageCount);
}
```

### See Also

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
