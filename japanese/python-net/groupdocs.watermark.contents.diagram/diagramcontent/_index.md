---
title: "DiagramContent クラス"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "Visio ドキュメントを表します。"
type: docs
url: /ja/python-net/groupdocs.watermark.contents.diagram/diagramcontent/
is_root: false
weight: 10
---


## DiagramContent class

Visio ドキュメントを表します。

詳しくは:
- Add watermarks to diagram documents https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents
- Existing objects in diagram document https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+diagram+document

DiagramContent 型は次のメンバーを公開します：

### メソッド
| メソッド | 説明 |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | 現在のインスタンスを破棄します。（[`Content`](/watermark/python-net/groupdocs.watermark.contents/content/) から継承） |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | 指定された検索条件に従って画像を検索します。検索は[`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)で指定されたオブジェクト内で実行されます。（[`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)から継承） |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | （[`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)から継承） |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | 指定された検索条件に従って可能性のある透かしを検索します。検索は[`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)に列挙されたオブジェクト上で実行されます。（[`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)から継承） |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | （[`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)から継承） |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [header_footer](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramcontent/header_footer/) | このDiagramContentのヘッダーとフッターです。 |
| [pages](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramcontent/pages/) | この[`DiagramContent`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramcontent/)のすべてのページのコレクションです。 |

### 例

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

### 関連項目
* module [`groupdocs.watermark.contents.diagram`](/watermark/python-net/groupdocs.watermark.contents.diagram/)
