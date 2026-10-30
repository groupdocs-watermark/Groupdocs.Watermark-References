---
title: "PresentationWatermarkSlideOptions"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "Presentation ドキュメントのスライドに透かしを追加する際のオプションを表します。"
type: docs
weight: 2130
url: /ja/net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/
---
## PresentationWatermarkSlideOptions class

Presentation ドキュメントのスライドに透かしを追加する際のオプションを表します。

```csharp
public sealed class PresentationWatermarkSlideOptions : PresentationWatermarkBaseSlideOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PresentationWatermarkSlideOptions](presentationwatermarkslideoptions)() | 新しいインスタンスの[`PresentationWatermarkSlideOptions`](../presentationwatermarkslideoptions)クラスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternativetext) { get; set; } | 形状に関連付けられる説明（代替）テキストを取得または設定します。 |
| [Effects](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects) { get; set; } | 透かしに適用すべき効果のために、[`PresentationImageEffects`](../presentationimageeffects) または [`PresentationTextEffects`](../presentationtexteffects) の値を取得または設定します。 |
| [IsLocked](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/islocked) { get; set; } | PowerPoint でシェイプの編集が禁止されているかどうかを示す値を取得または設定します。 |
| [Name](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name) { get; set; } | 形状の名前を取得または設定します。 |
| [ProtectWithUnreadableCharacters](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protectwithunreadablecharacters) { get; set; } | テキスト透かし文字が読めない文字と混在しているかどうかを示す値を取得または設定します。 |
| [SlideIndex](../../groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/slideindex) { get; set; } | 透かしを追加するスライドのインデックスを取得または設定します。 |

### 備考

**Learn more:**

* [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)

### 例

PowerPoint プレゼンテーションの特定のスライドに透かしを追加します。

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.ppt", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36, FontStyle.Bold | FontStyle.Italic));
    watermark.HorizontalAlignment = HorizontalAlignment.Center;
    watermark.VerticalAlignment = VerticalAlignment.Center;

    PresentationWatermarkSlideOptions options = new PresentationWatermarkSlideOptions();
    options.SlideIndex = 0;
    options.IsLocked = false; // default
    options.ProtectWithUnreadableCharacters = false; // default
    options.Name = null; // default
    options.AlternativeText = null; // default

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### 関連項目

* class [PresentationWatermarkBaseSlideOptions](../presentationwatermarkbaseslideoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
