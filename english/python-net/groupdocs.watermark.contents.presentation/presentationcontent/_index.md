---
title: PresentationContent class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.contents.presentation/presentationcontent/
is_root: false
weight: 60
---

## PresentationContent class

Represents a PowerPoint document where a watermark can be placed.



**Inheritance:** [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent) → 
[`Content`](/watermark/python-net/groupdocs.watermark.contents/content) → 
[`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart)



The PresentationContent type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [slide_width](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/slide_width) | Gets the width of a slide in points. |
| [slide_height](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/slide_height) | Gets the height of a slide in points. |
| [notes_slide_width](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/notes_slide_width) | Gets the width of a notes slide in points. |
| [notes_slide_height](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/notes_slide_height) | Gets the height of a notes slide in points. |
| [slides](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/slides) | Gets the collection of all slides of this [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent). |
| [master_slides](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/master_slides) | Gets the collection of all master slides of this [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent). |
| [layout_slides](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/layout_slides) | Gets the collection of all layout slides of this [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent). |
| [master_notes_slide](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/master_notes_slide) | Gets the master slide for all notes slides of this [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent). |
| [master_handout_slide](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/master_handout_slide) | Gets the master handout slide of this [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent). |


### Methods
| Method | Description |
| :- | :- |
| [find_images](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/find_images/#groupdocs.watermark.search.searchcriteria.ImageSearchCriteria) | Finds images according to the specified search criteria.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [find_images](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/find_images/#) | Finds all images in the content.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [search](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/search/#groupdocs.watermark.search.searchcriteria.SearchCriteria) | Finds possible watermarks according to specified search criteria.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [search](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/search/#) | Finds all possible watermarks in the content.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/encrypt/#str) | Encrypts the document. |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/decrypt/#) | Decrypts the document. |



### Remarks 


**Learn more:** |
|
 |
 |

### Example 


Load and save PowerPoint document of any supported type.

### See Also
* module [`groupdocs.watermark.contents.presentation`](..)
* class [`Content`](/watermark/python-net/groupdocs.watermark.contents/content)
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart)
* class [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent)
