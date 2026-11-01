---
title: "EmailContent クラス"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "メールメッセージを表します。"
type: docs
url: /ja/python-net/groupdocs.watermark.contents.email/emailcontent/
is_root: false
weight: 70
---


## EmailContent class

メールメッセージを表します。

詳しくは:
- [Add watermarks to email attachments](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
- [Email attachments](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
- [Email messages](https://docs.groupdocs.com/display/watermarknet/Email+messages)

EmailContent 型は次のメンバーを公開します：

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
| [attachments](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/attachments/) | メールメッセージのすべての添付ファイルのコレクションです。 |
| [bcc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/bcc/) | メールメッセージの BCC（ブラインド カーボン コピー）受信者のコレクションです。 |
| [body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body/) | メッセージ本文のプレーンテキスト表現です。 |
| [body_type](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body_type/) | メールメッセージ本文のタイプです。 |
| [cc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/cc/) | メールメッセージの CC（カーボン コピー）受信者のコレクションです。 |
| [embedded_objects](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/embedded_objects/) | メールメッセージのすべての埋め込みオブジェクトのコレクションです。 |
| [from_](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/from_/) | メールメッセージの送信元アドレスです。 |
| [html_body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/html_body/) | メッセージ本文の HTML 表現です。 |
| [subject](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/subject/) | メールメッセージの件名です。 |
| [to](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/to/) | メールメッセージの受信者のコレクションです。 |

### 例

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.email import EmailLoadOptions
import groupdocs.watermark.contents.email as gwc_email

load_options = EmailLoadOptions()
with gw.Watermarker("message.msg", load_options) as watermarker:
    content = watermarker.get_content()
    # 添付ファイルを追加する
    with open("sample.msg", "rb") as f:
        content.attachments.add(f.read(), "sample.msg")
    watermarker.save("output.msg")
```

### 関連項目
* module [`groupdocs.watermark.contents.email`](/watermark/python-net/groupdocs.watermark.contents.email/)
