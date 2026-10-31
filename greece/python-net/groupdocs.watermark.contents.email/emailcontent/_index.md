---
title: "EmailContent κλάση"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά ένα μήνυμα email."
type: docs
url: /el/python-net/groupdocs.watermark.contents.email/emailcontent/
is_root: false
weight: 70
---


## EmailContent class

Αναπαριστά ένα μήνυμα email.

Μάθετε περισσότερα:
- [Add watermarks to email attachments](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
- [Email attachments](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
- [Email messages](https://docs.groupdocs.com/display/watermarknet/Email+messages)

Ο τύπος EmailContent εκθέτει τα ακόλουθα μέλη:

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Αποδεσμεύει την τρέχουσα παρουσία. (κληρονομείται από το [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Βρίσκει εικόνες σύμφωνα με τα καθορισμένα κριτήρια αναζήτησης. Η αναζήτηση πραγματοποιείται στα αντικείμενα που ορίζονται στο [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (κληρονομείται από το [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (κληρονομείται από το [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Βρίσκει πιθανά υδατογραφήματα σύμφωνα με τα καθορισμένα κριτήρια αναζήτησης. Η αναζήτηση εκτελείται στα αντικείμενα που αναφέρονται στο [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (κληρονομείται από το [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (κληρονομείται από το [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [attachments](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/attachments/) | Η συλλογή όλων των συνημμένων του μηνύματος ηλεκτρονικού ταχυδρομείου. |
| [bcc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/bcc/) | Η συλλογή των παραληπτών BCC (τυφλό αντίγραφο) του μηνύματος ηλεκτρονικού ταχυδρομείου. |
| [body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body/) | Η αναπαράσταση απλού κειμένου του σώματος του μηνύματος. |
| [body_type](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body_type/) | Ο τύπος του σώματος του μηνύματος ηλεκτρονικού ταχυδρομείου. |
| [cc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/cc/) | Η συλλογή των παραληπτών CC (αντίγραφο) του μηνύματος ηλεκτρονικού ταχυδρομείου. |
| [embedded_objects](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/embedded_objects/) | Η συλλογή όλων των ενσωματωμένων αντικειμένων του μηνύματος ηλεκτρονικού ταχυδρομείου. |
| [from_](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/from_/) | Η διεύθυνση αποστολέα του μηνύματος ηλεκτρονικού ταχυδρομείου. |
| [html_body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/html_body/) | Η αναπαράσταση html του σώματος του μηνύματος. |
| [subject](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/subject/) | Το θέμα του μηνύματος ηλεκτρονικού ταχυδρομείου. |
| [to](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/to/) | Η συλλογή των παραληπτών του μηνύματος ηλεκτρονικού ταχυδρομείου. |

### Παράδειγμα

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.email import EmailLoadOptions
import groupdocs.watermark.contents.email as gwc_email

load_options = EmailLoadOptions()
with gw.Watermarker("message.msg", load_options) as watermarker:
    content = watermarker.get_content()
    # προσθέστε ένα συνημμένο
    with open("sample.msg", "rb") as f:
        content.attachments.add(f.read(), "sample.msg")
    watermarker.save("output.msg")
```

### Δείτε επίσης
* module [`groupdocs.watermark.contents.email`](/watermark/python-net/groupdocs.watermark.contents.email/)
