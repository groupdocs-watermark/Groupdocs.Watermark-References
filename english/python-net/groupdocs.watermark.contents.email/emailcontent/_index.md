---
title: EmailContent class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.contents.email/emailcontent/
is_root: false
weight: 60
---

## EmailContent class

Represents an email message.



**Inheritance:** [`EmailContent`](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent) → 
[`Content`](/watermark/python-net/groupdocs.watermark.contents/content) → 
[`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart)



The EmailContent type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [attachments](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/attachments) | Gets the collection of all attachments of the email message. |
| [embedded_objects](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/embedded_objects) | Gets the collection of all embedded objects of the email message. |
| [from_address](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/from_address) | Gets the from address of the email message. |
| [to](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/to) | Gets the collection of recipients of the email message. |
| [cc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/cc) | Gets the collection of CC (carbon copy) recipients of the email message. |
| [bcc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/bcc) | Gets the collection of BCC (blind carbon copy) recipients of the email message. |
| [subject](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/subject) | Gets or sets the subject of the email message. |
| [body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body) | Gets or sets the plain text representation of the message body. |
| [html_body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/html_body) | Gets or sets the html representation of the message body. |
| [body_type](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body_type) | Gets the type of the email message body. |


### Methods
| Method | Description |
| :- | :- |
| [find_images](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/find_images/#groupdocs.watermark.search.searchcriteria.ImageSearchCriteria) | Finds images according to the specified search criteria.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [find_images](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/find_images/#) | Finds all images in the content.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [search](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/search/#groupdocs.watermark.search.searchcriteria.SearchCriteria) | Finds possible watermarks according to specified search criteria.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |
| [search](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/search/#) | Finds all possible watermarks in the content.<br/>The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects). |



### Remarks 


**Learn more:** |
|
 |
 |
 |

### See Also
* module [`groupdocs.watermark.contents.email`](..)
* class [`Content`](/watermark/python-net/groupdocs.watermark.contents/content)
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart)
* class [`EmailContent`](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent)
