---
title: "EmailContent klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt een e-mailbericht voor."
type: docs
url: /nl/python-net/groupdocs.watermark.contents.email/emailcontent/
is_root: false
weight: 70
---


## EmailContent class

Stelt een e-mailbericht voor.

Meer informatie:
- [Add watermarks to email attachments](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
- [Email attachments](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
- [Email messages](https://docs.groupdocs.com/display/watermarknet/Email+messages)

Het type EmailContent bevat de volgende leden:

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Verwijdert de huidige instantie. (geërfd van [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Zoekt afbeeldingen volgens de opgegeven zoekcriteria. De zoekopdracht wordt uitgevoerd in de objecten die zijn gespecificeerd in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (geërfd van [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (geërfd van [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Zoekt mogelijke watermerken volgens de opgegeven zoekcriteria. De zoekopdracht wordt uitgevoerd op de objecten die zijn vermeld in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (geërfd van [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (geërfd van [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [attachments](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/attachments/) | De verzameling van alle bijlagen van het e‑mailbericht. |
| [bcc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/bcc/) | De verzameling van BCC (blind carbon copy) ontvangers van het e‑mailbericht. |
| [body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body/) | De platte-tekstrepresentatie van de berichtinhoud. |
| [body_type](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body_type/) | Het type van de e‑mailberichtinhoud. |
| [cc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/cc/) | De verzameling van CC (carbon copy) ontvangers van het e‑mailbericht. |
| [embedded_objects](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/embedded_objects/) | De verzameling van alle ingesloten objecten van het e‑mailbericht. |
| [from_](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/from_/) | Het afzenderadres van het e‑mailbericht. |
| [html_body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/html_body/) | De html-weergave van de berichtinhoud. |
| [subject](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/subject/) | Het onderwerp van het e‑mailbericht. |
| [to](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/to/) | De verzameling van ontvangers van het e‑mailbericht. |

### Voorbeeld

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.email import EmailLoadOptions
import groupdocs.watermark.contents.email as gwc_email

load_options = EmailLoadOptions()
with gw.Watermarker("message.msg", load_options) as watermarker:
    content = watermarker.get_content()
    # voeg een bijlage toe
    with open("sample.msg", "rb") as f:
        content.attachments.add(f.read(), "sample.msg")
    watermarker.save("output.msg")
```

### Zie ook
* module [`groupdocs.watermark.contents.email`](/watermark/python-net/groupdocs.watermark.contents.email/)
