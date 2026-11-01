---
title: "Clase EmailContent"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa un mensaje de correo electrónico."
type: docs
url: /es/python-net/groupdocs.watermark.contents.email/emailcontent/
is_root: false
weight: 70
---


## EmailContent class

Representa un mensaje de correo electrónico.

Aprende más:
- [Add watermarks to email attachments](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
- [Email attachments](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
- [Email messages](https://docs.groupdocs.com/display/watermarknet/Email+messages)

El tipo EmailContent expone los siguientes miembros:

### Métodos
| Método | Descripción |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Libera la instancia actual. (heredado de [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Encuentra imágenes según los criterios de búsqueda especificados. La búsqueda se realiza en los objetos especificados en [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Encuentra posibles marcas de agua según los criterios de búsqueda especificados. La búsqueda se realiza en los objetos enumerados en [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [attachments](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/attachments/) | La colección de todos los archivos adjuntos del mensaje de correo electrónico. |
| [bcc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/bcc/) | La colección de destinatarios CCO (copia de carbón oculta) del mensaje de correo electrónico. |
| [body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body/) | La representación en texto plano del cuerpo del mensaje. |
| [body_type](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body_type/) | El tipo del cuerpo del mensaje de correo electrónico. |
| [cc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/cc/) | La colección de destinatarios CC (copia de carbón) del mensaje de correo electrónico. |
| [embedded_objects](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/embedded_objects/) | La colección de todos los objetos incrustados del mensaje de correo electrónico. |
| [from_](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/from_/) | La dirección del remitente del mensaje de correo electrónico. |
| [html_body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/html_body/) | La representación html del cuerpo del mensaje. |
| [subject](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/subject/) | El asunto del mensaje de correo electrónico. |
| [to](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/to/) | La colección de destinatarios del mensaje de correo electrónico. |

### Ejemplo

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.email import EmailLoadOptions
import groupdocs.watermark.contents.email as gwc_email

load_options = EmailLoadOptions()
with gw.Watermarker("message.msg", load_options) as watermarker:
    content = watermarker.get_content()
    # agregar un archivo adjunto
    with open("sample.msg", "rb") as f:
        content.attachments.add(f.read(), "sample.msg")
    watermarker.save("output.msg")
```

### Ver también
* module [`groupdocs.watermark.contents.email`](/watermark/python-net/groupdocs.watermark.contents.email/)
