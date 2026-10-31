---
title: "classe EmailContent"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta un messaggio email."
type: docs
url: /it/python-net/groupdocs.watermark.contents.email/emailcontent/
is_root: false
weight: 70
---


## EmailContent class

Rappresenta un messaggio email.

Per saperne di più:
- [Add watermarks to email attachments](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
- [Email attachments](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
- [Email messages](https://docs.groupdocs.com/display/watermarknet/Email+messages)

Il tipo EmailContent espone i seguenti membri:

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Elimina l'istanza corrente. (eredita da [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Trova le immagini in base ai criteri di ricerca specificati. La ricerca viene eseguita negli oggetti specificati in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (eredita da [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (eredita da [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Trova i possibili watermark in base ai criteri di ricerca specificati. La ricerca viene eseguita sugli oggetti elencati in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (eredita da [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (eredita da [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [attachments](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/attachments/) | La raccolta di tutti gli allegati del messaggio email. |
| [bcc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/bcc/) | La raccolta dei destinatari BCC (copia carbone nascosta) del messaggio email. |
| [body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body/) | La rappresentazione in testo semplice del corpo del messaggio. |
| [body_type](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body_type/) | Il tipo del corpo del messaggio email. |
| [cc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/cc/) | La raccolta dei destinatari CC (copia carbone) del messaggio email. |
| [embedded_objects](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/embedded_objects/) | La raccolta di tutti gli oggetti incorporati del messaggio email. |
| [from_](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/from_/) | L'indirizzo mittente del messaggio email. |
| [html_body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/html_body/) | La rappresentazione HTML del corpo del messaggio. |
| [subject](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/subject/) | L'oggetto del messaggio email. |
| [to](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/to/) | La raccolta dei destinatari del messaggio email. |

### Esempio

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.email import EmailLoadOptions
import groupdocs.watermark.contents.email as gwc_email

load_options = EmailLoadOptions()
with gw.Watermarker("message.msg", load_options) as watermarker:
    content = watermarker.get_content()
    # aggiungi un allegato
    with open("sample.msg", "rb") as f:
        content.attachments.add(f.read(), "sample.msg")
    watermarker.save("output.msg")
```

### Vedi anche
* module [`groupdocs.watermark.contents.email`](/watermark/python-net/groupdocs.watermark.contents.email/)
