---
title: "Classe DiagramContent"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Représente un document Visio."
type: docs
url: /fr/python-net/groupdocs.watermark.contents.diagram/diagramcontent/
is_root: false
weight: 10
---


## DiagramContent class

Représente un document Visio.

En savoir plus :
- Add watermarks to diagram documents https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents
- Existing objects in diagram document https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+diagram+document

Le type DiagramContent expose les membres suivants:

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
| [header_footer](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramcontent/header_footer/) | L'en-tête et le pied de page de ce DiagramContent. |
| [pages](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramcontent/pages/) | La collection de toutes les pages de ce [`DiagramContent`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramcontent/). |

### Exemple

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.diagram import DiagramLoadOptions
import groupdocs.watermark.contents.diagram as gwc_vsdx

load_options = DiagramLoadOptions()
with gw.Watermarker("diagram.vsdx", load_options) as watermarker:
    content = watermarker.get_content()
    for shape in content.pages[0].shapes:
        if shape.text and "© Aspose 2016" in shape.text:
            shape.text = "© GroupDocs 2017"
    watermarker.save("output.vsdx")
```

### Voir aussi
* module [`groupdocs.watermark.contents.diagram`](/watermark/python-net/groupdocs.watermark.contents.diagram/)
