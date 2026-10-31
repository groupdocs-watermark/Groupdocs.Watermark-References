---
title: "Classe EmailContent"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Représente un message électronique."
type: docs
url: /fr/python-net/groupdocs.watermark.contents.email/emailcontent/
is_root: false
weight: 70
---


## EmailContent class

Représente un message électronique.

En savoir plus :
- [Add watermarks to email attachments](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
- [Email attachments](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
- [Email messages](https://docs.groupdocs.com/display/watermarknet/Email+messages)

Le type EmailContent expose les membres suivants :

### Méthodes
| Méthode | Description |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Libère l’instance actuelle. (hérité de [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Recherche des images selon les critères de recherche spécifiés. La recherche est effectuée dans les objets spécifiés dans [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (hérité de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (hérité de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Recherche les filigranes possibles selon les critères de recherche spécifiés. La recherche est effectuée sur les objets répertoriés dans [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (hérité de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (hérité de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Propriétés
| Propriété | Description |
| :- | :- |
| [attachments](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/attachments/) | La collection de toutes les pièces jointes du message électronique. |
| [bcc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/bcc/) | La collection des destinataires BCC (copie carbone invisible) du message électronique. |
| [body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body/) | La représentation en texte brut du corps du message. |
| [body_type](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body_type/) | Le type du corps du message électronique. |
| [cc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/cc/) | La collection des destinataires CC (copie carbone) du message électronique. |
| [embedded_objects](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/embedded_objects/) | La collection de tous les objets incorporés du message électronique. |
| [from_](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/from_/) | L'adresse d'expéditeur du message électronique. |
| [html_body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/html_body/) | La représentation HTML du corps du message. |
| [subject](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/subject/) | L'objet du message électronique. |
| [to](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/to/) | La collection des destinataires du message électronique. |

### Exemple

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.email import EmailLoadOptions
import groupdocs.watermark.contents.email as gwc_email

load_options = EmailLoadOptions()
with gw.Watermarker("message.msg", load_options) as watermarker:
    content = watermarker.get_content()
    # ajouter une pièce jointe
    with open("sample.msg", "rb") as f:
        content.attachments.add(f.read(), "sample.msg")
    watermarker.save("output.msg")
```

### Voir aussi
* module [`groupdocs.watermark.contents.email`](/watermark/python-net/groupdocs.watermark.contents.email/)
