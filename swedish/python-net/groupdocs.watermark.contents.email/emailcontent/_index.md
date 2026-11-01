---
title: "EmailContent-klass"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Representerar ett e-postmeddelande."
type: docs
url: /sv/python-net/groupdocs.watermark.contents.email/emailcontent/
is_root: false
weight: 70
---


## EmailContent class

Representerar ett e-postmeddelande.

Läs mer:
- [Add watermarks to email attachments](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
- [Email attachments](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
- [Email messages](https://docs.groupdocs.com/display/watermarknet/Email+messages)

EmailContent-typen exponerar följande medlemmar:

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Avslutar den aktuella instansen. (ärvd från [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Hittar bilder enligt de angivna sökkriterierna. Söket utförs i de objekt som anges i [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (ärvd från [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (ärvd från [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Hittar möjliga vattenmärken enligt de angivna sökkriterierna. Söket utförs på de objekt som listas i [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (ärvd från [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (ärvd från [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [attachments](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/attachments/) | Samlingen av alla bilagor i e‑postmeddelandet. |
| [bcc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/bcc/) | Samlingen av BCC‑mottagare (blind carbon copy) i e‑postmeddelandet. |
| [body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body/) | Den rena textrepresentationen av meddelandekroppen. |
| [body_type](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body_type/) | Typen av e‑postmeddelandekroppen. |
| [cc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/cc/) | Samlingen av CC‑mottagare (carbon copy) av e‑postmeddelandet. |
| [embedded_objects](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/embedded_objects/) | Samlingen av alla inbäddade objekt i e‑postmeddelandet. |
| [from_](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/from_/) | Avsändaradressen för e‑postmeddelandet. |
| [html_body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/html_body/) | HTML‑representationen av meddelandekroppen. |
| [subject](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/subject/) | Ämnet för e‑postmeddelandet. |
| [to](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/to/) | Samlingen av mottagare av e‑postmeddelandet. |

### Exempel

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.email import EmailLoadOptions
import groupdocs.watermark.contents.email as gwc_email

load_options = EmailLoadOptions()
with gw.Watermarker("message.msg", load_options) as watermarker:
    content = watermarker.get_content()
    # lägg till en bilaga
    with open("sample.msg", "rb") as f:
        content.attachments.add(f.read(), "sample.msg")
    watermarker.save("output.msg")
```

### Se även
* module [`groupdocs.watermark.contents.email`](/watermark/python-net/groupdocs.watermark.contents.email/)
