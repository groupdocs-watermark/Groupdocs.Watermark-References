---
title: "Metered クラス"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "メーター制（従量課金）ライセンスを管理します。"
type: docs
url: /ja/python-net/groupdocs.watermark/metered/
is_root: false
weight: 30
---


## Metered class

メーター制（従量課金）ライセンスを管理します。

Metered ライセンスは実際の使用量（通常はページや
処理されたドキュメント）。公開/非公開キーのペアは、一度だけ
アプリケーションの起動時に設定します；ラッパーは使用状況を GroupDocs に報告します
バックグラウンドでライセンスサーバーへ送信します。

Metered 型は次のメンバーを公開します:

### メソッド
| メソッド | 説明 |
| :- | :- |
| [get_consumption_credit](/watermark/python-net/groupdocs.watermark/metered/get_consumption_credit/) | これまでに消費されたクレジット数を返します。 |
| [get_consumption_quantity](/watermark/python-net/groupdocs.watermark/metered/get_consumption_quantity/) | これまでに処理されたデータ量を返します。 |
| [set_metered_key](/watermark/python-net/groupdocs.watermark/metered/set_metered_key/#public_key-private_key) | 指定された公開/秘密キーのペアで従量課金を有効にします。 |

### 関連項目
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
