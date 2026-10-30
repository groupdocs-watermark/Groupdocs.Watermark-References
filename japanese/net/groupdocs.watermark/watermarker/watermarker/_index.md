---
title: "ウォーターマーカー"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "指定されたドキュメントパスで Watermarkergroupdocs.watermark/watermarker クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

指定されたドキュメントパスで [`Watermarker`](../../watermarker) クラスの新しいインスタンスを初期化します。

```csharp
public Watermarker(string filePath)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| filePath | String | ドキュメントを読み込むファイルパスです。 |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 指定されたドキュメントタイプはサポートされていません。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 指定されたパスワードが正しくありません。 |

### 備考

ドキュメントの読み込みについて詳しくは、[Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents) をご覧ください。

### 例

任意のサポートされている形式のコンテンツを読み込み、保存します。

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
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

指定されたドキュメントパスと読み込みオプションで [`Watermarker`](../../watermarker) クラスの新しいインスタンスを初期化します。

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| filePath | String | ドキュメントを読み込むファイルパスです。 |
| オプション | LoadOptions | ドキュメントを読み込む際に使用する追加オプションです。 |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 指定されたドキュメントタイプはサポートされていません。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 指定されたパスワードが正しくありません。 |

### 備考

ドキュメントの読み込みについて詳しくは、[Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents) をご覧ください。

### 例

パスワードを使用して暗号化された PDF ドキュメントを読み込む。

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
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

指定されたドキュメント パスと設定で [`Watermarker`](../../watermarker) クラスの新しいインスタンスを初期化します。

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| filePath | String | ドキュメントを読み込むファイルパスです。 |
| 設定 | WatermarkerSettings | ロードされたドキュメントを操作する際に使用する追加設定。 |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 指定されたドキュメントタイプはサポートされていません。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 指定されたパスワードが正しくありません。 |

### 備考

ドキュメントの読み込みについて詳しくは、[Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents) をご覧ください。

### 例

検索可能オブジェクトをグローバルに設定します（それ以降に読み込まれるすべてのドキュメントに適用）。

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

        // 見つかった透かしを操作するコードはここに記述します。
    }
}
```

### 関連項目

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

指定されたドキュメント パス、ロード オプション、および設定で [`Watermarker`](../../watermarker) クラスの新しいインスタンスを初期化します。

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| filePath | String | ドキュメントを読み込むファイルパスです。 |
| オプション | LoadOptions | ドキュメントを読み込む際に使用する追加オプションです。 |
| 設定 | WatermarkerSettings | ロードされたドキュメントを操作する際に使用する追加設定。 |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 指定されたドキュメントタイプはサポートされていません。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 指定されたパスワードが正しくありません。 |

### 備考

ドキュメントの読み込みについて詳しくは、[Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents) をご覧ください。

### 例

メール メッセージの本文/件名から特定のテキスト フラグメントを検索します。

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
    // 注、検索は TextSearchCriteria インスタンスを Search メソッドに渡した場合にのみ実行されます。
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // 見つかったテキスト フラグメントを削除する
    watermarks.Clear();
    // 変更を保存する
    watermarker.Save();
}
```

### 関連項目

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

指定されたストリームで [`Watermarker`](../../watermarker) クラスの新しいインスタンスを初期化します。

```csharp
public Watermarker(Stream document)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| ドキュメント | Stream | ドキュメントを読み込むストリームです。 |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 指定されたドキュメントタイプはサポートされていません。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 指定されたパスワードが正しくありません。 |

### 備考

ドキュメントの読み込みについて詳しくは [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents) をご覧ください。

### 例

サポートされている任意の形式のドキュメントを読み込み、保存します。

```csharp
// ストリームからコンテンツを読み込みます。
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // Watermarker クラスのメソッドを使用して、透かしを追加、検索、または削除します。

    // 変更を保存します。
    watermarker.Save(outputStream);
}
```

### 関連項目

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

指定されたストリームとロード オプションで [`Watermarker`](../../watermarker) クラスの新しいインスタンスを初期化します。

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| ドキュメント | Stream | ドキュメントを読み込むストリームです。 |
| オプション | LoadOptions | ドキュメントを読み込む際に使用する追加オプションです。 |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 指定されたドキュメントタイプはサポートされていません。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 指定されたパスワードが正しくありません。 |

### 備考

ドキュメントの読み込みについて詳しくは [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents) をご覧ください。

### 例

パスワードを使用して暗号化された PDF ドキュメントを読み込む

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
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

指定されたストリームと設定で [`Watermarker`](../../watermarker) クラスの新しいインスタンスを初期化します。

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| ドキュメント | Stream | ドキュメントを読み込むストリームです。 |
| 設定 | WatermarkerSettings | ロードされたドキュメントを操作する際に使用する追加設定。 |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 指定されたドキュメントタイプはサポートされていません。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 指定されたパスワードが正しくありません。 |

### 備考

ドキュメントの読み込みについて詳しくは [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents) をご覧ください。

### 例

検索可能オブジェクトをグローバルに設定します（それ以降に読み込まれるすべてのドキュメントに適用）。

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

        // 見つかった透かしを操作するコードはここに記述します。
    }
}
```

### 関連項目

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

指定されたストリーム、ロード オプション、および設定で [`Watermarker`](../../watermarker) クラスの新しいインスタンスを初期化します。

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| ドキュメント | Stream | ドキュメントを読み込むストリームです。 |
| オプション | LoadOptions | ドキュメントを読み込む際に使用する追加オプションです。 |
| 設定 | WatermarkerSettings | ロードされたドキュメントを操作する際に使用する追加設定。 |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 指定されたドキュメントタイプはサポートされていません。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 指定されたパスワードが正しくありません。 |

### 備考

ドキュメントの読み込みについて詳しくは [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents) をご覧ください。

### 例

メール メッセージの本文/件名から特定のテキスト フラグメントを検索します。

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
    // 注、検索は TextSearchCriteria インスタンスを Search メソッドに渡した場合にのみ実行されます。
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // 見つかったテキスト フラグメントを削除する
    watermarks.Clear();
    // 変更を保存する
    watermarker.Save();
}
```

### 関連項目

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
