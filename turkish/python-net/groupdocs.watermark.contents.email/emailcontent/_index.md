---
title: "EmailContent sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Bir e-posta mesajını temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.contents.email/emailcontent/
is_root: false
weight: 70
---


## EmailContent class

Bir e-posta mesajını temsil eder.

Daha fazla bilgi edinin:
- [Add watermarks to email attachments](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
- [Email attachments](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
- [Email messages](https://docs.groupdocs.com/display/watermarknet/Email+messages)

EmailContent türü aşağıdaki üyeleri gösterir:

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Mevcut örneği yok eder. ([`Content`](/watermark/python-net/groupdocs.watermark.contents/content/) sınıfından miras alınmıştır) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Belirtilen arama kriterlerine göre görüntüleri bulur. Arama, [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) içinde belirtilen nesnelerde gerçekleştirilir. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır.) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Belirtilen arama kriterlerine göre olası filigranları bulur. Arama, [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) içinde listelenen nesnelerde gerçekleştirilir. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır.) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır) |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [attachments](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/attachments/) | E-posta mesajının tüm eklerinin koleksiyonu. |
| [bcc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/bcc/) | E-posta mesajının BCC (görünmez kopya) alıcılarının koleksiyonu. |
| [body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body/) | Mesaj gövdesinin düz metin temsili. |
| [body_type](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body_type/) | E-posta mesajı gövdesinin türü. |
| [cc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/cc/) | E-posta mesajının CC (kopya) alıcılarının koleksiyonu. |
| [embedded_objects](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/embedded_objects/) | E-posta mesajının tüm gömülü nesnelerinin koleksiyonu. |
| [from_](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/from_/) | E-posta mesajının gönderici adresi. |
| [html_body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/html_body/) | Mesaj gövdesinin html temsili. |
| [subject](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/subject/) | E-posta mesajının konusu. |
| [to](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/to/) | E-posta mesajının alıcılarının koleksiyonu. |

### Örnek

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.email import EmailLoadOptions
import groupdocs.watermark.contents.email as gwc_email

load_options = EmailLoadOptions()
with gw.Watermarker("message.msg", load_options) as watermarker:
    content = watermarker.get_content()
    # ek ekle
    with open("sample.msg", "rb") as f:
        content.attachments.add(f.read(), "sample.msg")
    watermarker.save("output.msg")
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.contents.email`](/watermark/python-net/groupdocs.watermark.contents.email/)
