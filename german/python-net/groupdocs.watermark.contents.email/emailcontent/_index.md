---
title: "EmailContent-Klasse"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Stellt eine E-Mail-Nachricht dar."
type: docs
url: /de/python-net/groupdocs.watermark.contents.email/emailcontent/
is_root: false
weight: 70
---


## EmailContent class

Stellt eine E-Mail-Nachricht dar.

Mehr erfahren:
- [Add watermarks to email attachments](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
- [Email attachments](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
- [Email messages](https://docs.groupdocs.com/display/watermarknet/Email+messages)

Der EmailContent-Typ stellt die folgenden Mitglieder bereit:

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Gibt die aktuelle Instanz frei. (geerbt von [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Findet Bilder gemäß den angegebenen Suchkriterien. Die Suche wird in den in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) angegebenen Objekten durchgeführt. (geerbt von [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (geerbt von [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Findet mögliche Wasserzeichen gemäß den angegebenen Suchkriterien. Die Suche wird an den in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) aufgeführten Objekten durchgeführt. (geerbt von [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (geerbt von [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [attachments](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/attachments/) | Die Sammlung aller Anhänge der E-Mail-Nachricht. |
| [bcc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/bcc/) | Die Sammlung der BCC-Empfänger (Blind Carbon Copy) der E-Mail-Nachricht. |
| [body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body/) | Die Nur-Text-Darstellung des Nachrichtenkörpers. |
| [body_type](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body_type/) | Der Typ des E-Mail-Nachrichtenkörpers. |
| [cc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/cc/) | Die Sammlung der CC-Empfänger (Carbon Copy) der E-Mail-Nachricht. |
| [embedded_objects](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/embedded_objects/) | Die Sammlung aller eingebetteten Objekte der E-Mail-Nachricht. |
| [from_](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/from_/) | Die Absenderadresse der E-Mail-Nachricht. |
| [html_body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/html_body/) | Die HTML-Darstellung des Nachrichtenkörpers. |
| [subject](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/subject/) | Der Betreff der E-Mail-Nachricht. |
| [to](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/to/) | Die Sammlung der Empfänger der E-Mail-Nachricht. |

### Beispiel

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.email import EmailLoadOptions
import groupdocs.watermark.contents.email as gwc_email

load_options = EmailLoadOptions()
with gw.Watermarker("message.msg", load_options) as watermarker:
    content = watermarker.get_content()
    # einen Anhang hinzufügen
    with open("sample.msg", "rb") as f:
        content.attachments.add(f.read(), "sample.msg")
    watermarker.save("output.msg")
```

### Siehe auch
* module [`groupdocs.watermark.contents.email`](/watermark/python-net/groupdocs.watermark.contents.email/)
