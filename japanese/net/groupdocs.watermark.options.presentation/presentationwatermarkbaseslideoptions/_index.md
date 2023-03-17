---
title: PresentationWatermarkBaseSlideOptions
second_title: GroupDocs.Watermark for .NET API リファレンス
description: プレゼンテーション ドキュメントにオプションを追加する透かしの基本クラス
type: docs
weight: 1990
url: /ja/net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/
---
## PresentationWatermarkBaseSlideOptions class

プレゼンテーション ドキュメントにオプションを追加する透かしの基本クラス。

```csharp
public abstract class PresentationWatermarkBaseSlideOptions : PresentationWatermarkOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternativetext) { get; set; } | 形状に関連付けられる説明 (代替) テキストを取得または設定します。 |
| [Effects](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects) { get; set; } | の値を取得または設定します[`PresentationImageEffects`](../presentationimageeffects)or [`PresentationTextEffects`](../presentationtexteffects)透かしに適用する必要がある効果用. |
| [IsLocked](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/islocked) { get; set; } | PowerPoint での図形の編集が禁止されているかどうかを示す値を取得または設定します. |
| [Name](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name) { get; set; } | シェイプの名前を取得または設定します。 |
| [ProtectWithUnreadableCharacters](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protectwithunreadablecharacters) { get; set; } | テキストの透かし文字が判読できない文字と混在しているかどうかを示す値を取得または設定します. |

### 備考

**もっと詳しく知る：**

* [プレゼンテーション ドキュメントに透かしを追加する](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)

### 例

パワー ポイント プレゼンテーションのさまざまなサービス スライドに透かしを追加します。

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pptx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 8));

    // すべてのマスター スライドに透かしを追加します
    PresentationWatermarkMasterSlideOptions masterSlideOptions = new PresentationWatermarkMasterSlideOptions();
    masterSlideOptions.MasterSlideIndex = -1; // デフォルト
    watermarker.Add(watermark, masterSlideOptions);

    // すべてのレイアウト スライドに透かしを追加します
    PresentationWatermarkLayoutSlideOptions layoutSlideOptions = new PresentationWatermarkLayoutSlideOptions();
    layoutSlideOptions.LayoutSlideIndex = -1; // デフォルト
    watermarker.Add(watermark, layoutSlideOptions);

    // すべてのノート スライドに透かしを追加します
    PresentationWatermarkNoteSlideOptions noteSlideOptions = new PresentationWatermarkNoteSlideOptions();
    noteSlideOptions.SlideIndex = -1; // デフォルト
    watermarker.Add(watermark, noteSlideOptions);

    // 配布資料マスターに透かしを追加
    PresentationWatermarkMasterHandoutSlideOptions masterHandoutSlideOptions = new PresentationWatermarkMasterHandoutSlideOptions();
    watermarker.Add(watermark, masterHandoutSlideOptions);

    // ノート マスターに透かしを追加
    PresentationWatermarkMasterNotesSlideOptions masterNotesSlideOptions = new PresentationWatermarkMasterNotesSlideOptions();
    watermarker.Add(watermark, masterNotesSlideOptions);

    watermarker.Save();
}
```

### 関連項目

* class [PresentationWatermarkOptions](../presentationwatermarkoptions)
* 名前空間 [GroupDocs.Watermark.Options.Presentation](../../groupdocs.watermark.options.presentation)
* 組み立て [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->