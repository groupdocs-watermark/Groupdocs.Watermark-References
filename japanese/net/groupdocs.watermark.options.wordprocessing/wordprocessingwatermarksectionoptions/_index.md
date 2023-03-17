---
title: WordProcessingWatermarkSectionOptions
second_title: GroupDocs.Watermark for .NET API リファレンス
description: Word 文書セクションに図形の透かしを追加するときのオプションを表します
type: docs
weight: 2380
url: /ja/net/groupdocs.watermark.options.wordprocessing/wordprocessingwatermarksectionoptions/
---
## WordProcessingWatermarkSectionOptions class

Word 文書セクションに図形の透かしを追加するときのオプションを表します。

```csharp
public sealed class WordProcessingWatermarkSectionOptions : WordProcessingWatermarkBaseOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [WordProcessingWatermarkSectionOptions](wordprocessingwatermarksectionoptions)() | の新しいインスタンスを初期化します[`WordProcessingWatermarkSectionOptions`](../wordprocessingwatermarksectionoptions)class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/alternativetext) { get; set; } | 形状に関連付けられる説明 (代替) テキストを取得または設定します。 |
| [Effects](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/effects) { get; set; } | の値を取得または設定します[`WordProcessingImageEffects`](../wordprocessingimageeffects)or [`WordProcessingTextEffects`](../wordprocessingtexteffects)透かしに適用する必要がある効果用. |
| [IsLocked](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/islocked) { get; set; } | Word での形状の編集が禁止されているかどうかを示す値を取得または設定します。 |
| [LockType](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/locktype) { get; set; } | ウォーターマーク ロック タイプを取得または設定します。 |
| [Name](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/name) { get; set; } | シェイプの名前を取得または設定します。 |
| [Password](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/password) { get; set; } | 透かしのロックに使用するパスワードを取得または設定します。 |
| [SectionIndex](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarksectionoptions/sectionindex) { get; set; } | 透かしを追加するセクションのインデックスを取得または設定します。 |

### 備考

**もっと詳しく知る：**

* [ワープロ ドキュメントに透かしを追加する](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents)

### 例

Word 文書の特定のセクションに透かしを追加します。

```csharp
WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.doc", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36, FontStyle.Bold | FontStyle.Italic));
    watermark.HorizontalAlignment = HorizontalAlignment.Center;
    watermark.VerticalAlignment = VerticalAlignment.Center;
    watermark.ForegroundColor = Color.Red;

    WordProcessingWatermarkSectionOptions options = new WordProcessingWatermarkSectionOptions();
    options.SectionIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### 関連項目

* class [WordProcessingWatermarkBaseOptions](../wordprocessingwatermarkbaseoptions)
* 名前空間 [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* 組み立て [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->