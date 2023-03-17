---
title: Watermarker
second_title: GroupDocs.Watermark for .NET API リファレンス
description: の新しいインスタンスを初期化しますWatermarkergroupdocs.watermark/watermarker指定されたドキュメント パスを持つクラス.
type: docs
weight: 10
url: /ja/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

の新しいインスタンスを初期化します[`Watermarker`](../../watermarker)指定されたドキュメント パスを持つクラス.

```csharp
public Watermarker(string filePath)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | ドキュメントの読み込み元のファイル パス。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 指定されたドキュメント タイプはサポートされていません。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 指定されたパスワードが正しくありません。 |

### 備考

ドキュメントの読み込みの詳細: [ドキュメントの読み込み](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### 例

サポートされている形式のコンテンツを読み込んで保存します。

```csharp
// ファイルからコンテンツを読み込みます。
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Watermarker クラスのメソッドを使用して、透かしを追加、検索、または削除します。

    // ドキュメントを保存します。
    watermarker.Save("D:\\output.pdf");
}
```

### 関連項目

* class [Watermarker](../../watermarker)
* 名前空間 [GroupDocs.Watermark](../../watermarker)
* 組み立て [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

の新しいインスタンスを初期化します[`Watermarker`](../../watermarker)指定された ドキュメントパスとロードオプションを持つクラス.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | ドキュメントの読み込み元のファイル パス。 |
| options | LoadOptions | ドキュメントをロードするときに使用する追加オプション。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 指定されたドキュメント タイプはサポートされていません。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 指定されたパスワードが正しくありません。 |

### 備考

ドキュメントの読み込みの詳細: [ドキュメントの読み込み](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### 例

パスワードを使用して暗号化された PDF ドキュメントを読み込みます。

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    // ...
}
```

### 関連項目

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* 名前空間 [GroupDocs.Watermark](../../watermarker)
* 組み立て [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

の新しいインスタンスを初期化します[`Watermarker`](../../watermarker)指定された ドキュメント パスと設定を持つクラス.

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | ドキュメントの読み込み元のファイル パス。 |
| settings | WatermarkerSettings | 読み込まれたドキュメントを操作するときに使用する追加の設定。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 指定されたドキュメント タイプはサポートされていません。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 指定されたパスワードが正しくありません。 |

### 備考

ドキュメントの読み込みの詳細: [ドキュメントの読み込み](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### 例

検索可能なオブジェクトをグローバルに設定します (その後ロードされるすべてのドキュメント用).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    WordProcessingSearchableObjects = WordProcessingSearchableObjects.Hyperlinks
                                    | WordProcessingSearchableObjects.Text,
    SpreadsheetSearchableObjects = SpreadsheetSearchableObjects.HeadersFooters,
    PresentationSearchableObjects = PresentationSearchableObjects.SlidesBackgrounds
                                  | PresentationSearchableObjects.Shapes,
    DiagramSearchableObjects = DiagramSearchableObjects.None,
    PdfSearchableObjects = PdfSearchableObjects.All
};

foreach (string file in Directory.GetFiles(@"D:\files"))
{
    using (Watermarker watermarker = new Watermarker(file, settings))
    {
        PossibleWatermarkCollection watermarks = watermarker.Search();

        // 見つかった透かしを操作するためのコードはここに記述します。
    }
}
```

### 関連項目

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* 名前空間 [GroupDocs.Watermark](../../watermarker)
* 組み立て [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

の新しいインスタンスを初期化します[`Watermarker`](../../watermarker)指定された ドキュメント パス、ロード オプションおよび設定を持つクラス.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | ドキュメントの読み込み元のファイル パス。 |
| options | LoadOptions | ドキュメントをロードするときに使用する追加オプション。 |
| settings | WatermarkerSettings | 読み込まれたドキュメントを操作するときに使用する追加の設定。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 指定されたドキュメント タイプはサポートされていません。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 指定されたパスワードが正しくありません。 |

### 備考

ドキュメントの読み込みの詳細: [ドキュメントの読み込み](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### 例

電子メール メッセージの本文/件名で特定のテキスト フラグメントを検索します。

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    EmailSearchableObjects = EmailSearchableObjects.Subject
                           | EmailSearchableObjects.HtmlBody
                           | EmailSearchableObjects.PlainTextBody
};
EmailLoadOptions loadOptions = new EmailLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.msg", loadOptions, settings))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // 注: TextSearchCriteria インスタンスを Search メソッドに渡した場合にのみ、検索が実行されます。
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // 見つかったテキスト フラグメントを削除します
    watermarks.Clear();
    // 変更内容を保存
    watermarker.Save();
}
```

### 関連項目

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* 名前空間 [GroupDocs.Watermark](../../watermarker)
* 組み立て [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

の新しいインスタンスを初期化します[`Watermarker`](../../watermarker)指定されたストリームを持つクラス.

```csharp
public Watermarker(Stream document)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Stream | ドキュメントをロードするストリーム。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 指定されたドキュメント タイプはサポートされていません。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 指定されたパスワードが正しくありません。 |

### 備考

ドキュメントのロードについて詳しく知る [ドキュメントの読み込み](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### 例

サポートされている形式のドキュメントを読み込んで保存します。

```csharp
// ストリームからコンテンツをロードします。
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // Watermarker クラスのメソッドを使用して、透かしを追加、検索、または削除します。

    // 変更内容を保存。
    watermarker.Save(outputStream);
}
```

### 関連項目

* class [Watermarker](../../watermarker)
* 名前空間 [GroupDocs.Watermark](../../watermarker)
* 組み立て [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

の新しいインスタンスを初期化します[`Watermarker`](../../watermarker)指定された stream およびロード オプションを持つクラス.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Stream | ドキュメントをロードするストリーム。 |
| options | LoadOptions | ドキュメントをロードするときに使用する追加オプション。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 指定されたドキュメント タイプはサポートされていません。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 指定されたパスワードが正しくありません。 |

### 備考

ドキュメントのロードについて詳しく知る [ドキュメントの読み込み](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### 例

password を使用して暗号化された PDF ドキュメントを読み込みます

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    // ...
}
```

### 関連項目

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* 名前空間 [GroupDocs.Watermark](../../watermarker)
* 組み立て [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

の新しいインスタンスを初期化します[`Watermarker`](../../watermarker)指定された stream と settings. を持つクラス

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Stream | ドキュメントをロードするストリーム。 |
| settings | WatermarkerSettings | 読み込まれたドキュメントを操作するときに使用する追加の設定。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 指定されたドキュメント タイプはサポートされていません。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 指定されたパスワードが正しくありません。 |

### 備考

ドキュメントのロードについて詳しく知る [ドキュメントの読み込み](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### 例

検索可能なオブジェクトをグローバルに設定します (その後ロードされるすべてのドキュメント用).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    WordProcessingSearchableObjects = WordProcessingSearchableObjects.Hyperlinks
                                    | WordProcessingSearchableObjects.Text,
    SpreadsheetSearchableObjects = SpreadsheetSearchableObjects.HeadersFooters,
    PresentationSearchableObjects = PresentationSearchableObjects.SlidesBackgrounds
                                  | PresentationSearchableObjects.Shapes,
    DiagramSearchableObjects = DiagramSearchableObjects.None,
    PdfSearchableObjects = PdfSearchableObjects.All
};

foreach (string file in Directory.GetFiles(@"D:\files"))
{
    using (FileStream fileStream = File.Open(file, FileMode.Open))
    using (Watermarker watermarker = new Watermarker(fileStream, settings))
    {
        PossibleWatermarkCollection watermarks = watermarker.Search();

        // 見つかった透かしを操作するためのコードはここに記述します。
    }
}
```

### 関連項目

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* 名前空間 [GroupDocs.Watermark](../../watermarker)
* 組み立て [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

の新しいインスタンスを初期化します[`Watermarker`](../../watermarker)指定されたストリームを持つクラス, ロード オプションと設定.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Stream | ドキュメントをロードするストリーム。 |
| options | LoadOptions | ドキュメントをロードするときに使用する追加オプション。 |
| settings | WatermarkerSettings | 読み込まれたドキュメントを操作するときに使用する追加の設定。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 指定されたドキュメント タイプはサポートされていません。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 指定されたパスワードが正しくありません。 |

### 備考

ドキュメントのロードについて詳しく知る [ドキュメントの読み込み](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### 例

電子メール メッセージの本文/件名で特定のテキスト フラグメントを検索します。

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    EmailSearchableObjects = EmailSearchableObjects.Subject
                           | EmailSearchableObjects.HtmlBody
                           | EmailSearchableObjects.PlainTextBody
};
EmailLoadOptions loadOptions = new EmailLoadOptions();
using (FileStream fileStream = File.Open(@"D:\test.msg", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions, settings))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // 注: TextSearchCriteria インスタンスを Search メソッドに渡した場合にのみ、検索が実行されます。
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // 見つかったテキスト フラグメントを削除します
    watermarks.Clear();
    // 変更内容を保存
    watermarker.Save();
}
```

### 関連項目

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* 名前空間 [GroupDocs.Watermark](../../watermarker)
* 組み立て [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
