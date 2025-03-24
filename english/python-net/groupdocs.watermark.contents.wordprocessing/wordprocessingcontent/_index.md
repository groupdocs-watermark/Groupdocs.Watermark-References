---
title: WordProcessingContent class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/
is_root: false
weight: 10
---

## WordProcessingContent class

Class representing Word document (doc, docx etc) where watermark should be placed.



**Inheritance:** [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingcontent) → 
[`Content`](/watermark/python-net/groupdocs.watermark.contents/content) → 
[`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart)



The WordProcessingContent type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [sections](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/sections) | Gets the collection of all sections of this [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingcontent). |
| [page_count](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/page_count) | Gets the number of pages in the document. |


### Methods
| Method | Description |
| :- | :- |
| [find_images](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/find_images/#groupdocs.watermark.search.searchcriteria.ImageSearchCriteria) | Finds images according to the specified search criteria.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [find_images](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/find_images/#) | Finds all images in the content.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [search](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/search/#groupdocs.watermark.search.searchcriteria.SearchCriteria) | Finds possible watermarks according to specified search criteria.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [search](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/search/#) | Finds all possible watermarks in the content.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/encrypt/#str) | Encrypts the document. |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/decrypt/#) | Decrypts the document. |
| [protect](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/protect/#groupdocs.watermark.contents.wordprocessing.WordProcessingProtectionType-str) | Protects the document from changes and sets a protection password. |
| [unprotect](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/unprotect/#) | Removes protection from the document regardless of the password. |



### Remarks 


**Learn more:** |
|
 |
 |
 |
 |
 |

### Example 


Load and save Word document of any supported type.

### See Also
* module [`groupdocs.watermark.contents.wordprocessing`](..)
* class [`Content`](/watermark/python-net/groupdocs.watermark.contents/content)
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart)
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.wordprocessing/wordprocessingcontent)
