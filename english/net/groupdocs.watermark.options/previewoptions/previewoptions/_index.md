---
title: PreviewOptions
second_title: GroupDocs.Watermark for .NET API Reference
description: Initializes a new instance of the PreviewOptionsgroupdocs.watermark.options/previewoptions class causing the output stream to be closed.
type: docs
weight: 10
url: /net/groupdocs.watermark.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream) {#constructor}

Initializes a new instance of the [`PreviewOptions`](../../previewoptions) class causing the output stream to be closed.

```csharp
public PreviewOptions(CreatePageStream createPageStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | Creates a stream for a specific page preview. |

### See Also

* delegate [CreatePageStream](../../createpagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Watermark.Options](../../previewoptions)
* assembly [GroupDocs.Watermark](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initializes a new instance of [`PreviewOptions`](../../previewoptions) class causing the output stream to be returned to the client for further use.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | Creates a stream for a specific page preview. |
| releasePageStream | ReleasePageStream | Notifies that the page preview generation is done and gets the output stream. |

### See Also

* delegate [CreatePageStream](../../createpagestream)
* delegate [ReleasePageStream](../../releasepagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Watermark.Options](../../previewoptions)
* assembly [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
