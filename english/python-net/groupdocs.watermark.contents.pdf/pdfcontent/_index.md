---
title: PdfContent class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.contents.pdf/pdfcontent/
is_root: false
weight: 70
---

## PdfContent class

Represents a pdf document where a watermark can be placed.



**Inheritance:** [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent) → 
[`Content`](/watermark/python-net/groupdocs.watermark.contents/content) → 
[`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart)



The PdfContent type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [pages](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/pages) | Gets the collection of all pages of this [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent). |
| [attachments](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/attachments) | Gets the collection of all attachments of this [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent). |
| [page_margin_type](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type) | Gets or sets pdf page margins to be used during watermark adding. |


### Methods
| Method | Description |
| :- | :- |
| [find_images](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/find_images/#groupdocs.watermark.search.searchcriteria.ImageSearchCriteria) | Finds images according to the specified search criteria.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [find_images](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/find_images/#) | Finds all images in the content.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [search](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/search/#groupdocs.watermark.search.searchcriteria.SearchCriteria) | Finds possible watermarks according to specified search criteria.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [search](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/search/#) | Finds all possible watermarks in the content.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/#str) | Encrypts the document using the same password as user password and owner password. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/#str-str-groupdocs.watermark.contents.pdf.PdfPermissions-groupdocs.watermark.contents.pdf.PdfCryptoAlgorithm) | Encrypts the content. |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/decrypt/#) | Decrypts the content. |
| [rasterize](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/#int-int-groupdocs.watermark.contents.pdf.PdfImageConversionFormat) | Converts all content pages into images. |



### Remarks 


**Learn more:** |
|
 |
 |
 |
 |

### See Also
* module [`groupdocs.watermark.contents.pdf`](..)
* class [`Content`](/watermark/python-net/groupdocs.watermark.contents/content)
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart)
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent)
