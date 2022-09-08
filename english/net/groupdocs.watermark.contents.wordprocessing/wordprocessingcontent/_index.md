---
title: WordProcessingContent
second_title: GroupDocs.Watermark for .NET API Reference
description: Class representing Word document doc docx etc where watermark should be placed.
type: docs
weight: 1280
url: /net/groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/
---
## WordProcessingContent class

Class representing Word document (doc, docx etc) where watermark should be placed.

```csharp
public class WordProcessingContent : Content
```

## Properties

| Name | Description |
| --- | --- |
| [PageCount](../../groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/pagecount) { get; } | Gets the number of pages in the document. |
| [Sections](../../groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/sections) { get; } | Gets the collection of all sections of this [`WordProcessingContent`](../wordprocessingcontent). |

## Methods

| Name | Description |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/decrypt)() | Decrypts the document. |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Disposes the current instance. |
| [Encrypt](../../groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/encrypt)(string) | Encrypts the document. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Finds all images in the content. The search is conducted in the objects specified in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Finds images according to the specified search criteria. The search is conducted in the objects specified in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Protect](../../groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/protect)(WordProcessingProtectionType, string) | Protects the document from changes and sets a protection password. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Finds all possible watermarks in the content. The search is conducted in the objects specified in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Finds possible watermarks according to specified search criteria. The search is conducted in the objects specified in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Unprotect](../../groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/unprotect)() | Removes protection from the document regardless of the password. |

### Remarks

**Learn more:**

* [Add watermarks to word processing documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents)
* [Existing objects in word processing document](https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+word+processing+document)
* [Locking watermark in word processing document](https://docs.groupdocs.com/display/watermarknet/Locking+watermark+in+word+processing+document)
* [Protecting word processing documents](https://docs.groupdocs.com/display/watermarknet/Protecting+word+processing+documents)
* [Watermarks in word processing document](https://docs.groupdocs.com/display/watermarknet/Watermarks+in+word+processing+document)

### Examples

Load and save Word document of any supported type.

```csharp
WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\input.doc", loadOptions))
{
    // Use Add method to add watermark to a particular or all sections.

    // Save changes.
    watermarker.Save(@"D:\output.doc");
}
```

### See Also

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.WordProcessing](../../groupdocs.watermark.contents.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->