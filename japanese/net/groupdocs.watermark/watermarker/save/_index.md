---
title: "保存"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "ドキュメントデータを基になるストリームに保存します。"
type: docs
weight: 100
url: /ja/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

ドキュメントデータを基になるストリームに保存します。

```csharp
public WatermarkResult Save()
```

### 備考

ドキュメントの保存について詳しくは [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### 例

メールメッセージの本文/件名から特定のテキストフラグメントを削除し、メールメッセージを保存します。

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // 注、検索は TextSearchCriteria インスタンスを Search メソッドに渡した場合にのみ実行されます。
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // 見つかったテキスト フラグメントを削除する
    watermarker.Remove(watermarks);
    // 変更を保存する
    watermarker.Save();
}
```

### 関連項目

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

ドキュメントを指定されたファイルの場所に保存します。

```csharp
public WatermarkResult Save(string filePath)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| filePath | String | ドキュメントデータを保存するファイルパスです。 |

### 備考

ドキュメントの保存について詳しくは [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### 例

透かしを追加し、ドキュメントを別のファイルに保存します。

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf");                                   
}                                                                                   
```

### 関連項目

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

ドキュメントを指定されたストリームに保存します。

```csharp
public WatermarkResult Save(Stream document)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| ドキュメント | Stream | ドキュメントデータを保存するストリームです。 |

### 備考

ドキュメントの保存について詳しくは [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### 例

透かしを追加し、ドキュメントをメモリストリームに保存します。

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    using (MemoryStream stream = new MemoryStream())
    {
        watermarker.Save(stream);
        // ...
    }
}
```

### 関連項目

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

保存オプションを使用して、ドキュメントデータを基になるストリームに保存します。

```csharp
public WatermarkResult Save(SaveOptions options)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| オプション | SaveOptions | ドキュメントを保存する際に使用する追加オプションです。 |

### 備考

ドキュメントの保存について詳しくは [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### 例

透かしを追加し、デフォルトの[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions)でドキュメントを保存します。

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### 関連項目

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

保存オプションを使用して、ドキュメントを指定されたファイルの場所に保存します。

```csharp
public WatermarkResult Save(string filePath, SaveOptions options)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| filePath | String | ドキュメントデータを保存するファイルパスです。 |
| オプション | SaveOptions | ドキュメントを保存する際に使用する追加オプションです。 |

### 備考

ドキュメントの保存について詳しくは [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### 例

透かしを追加し、デフォルトの[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions)でドキュメントを別のファイルに保存します。

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### 関連項目

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

保存オプションを使用して、ドキュメントを指定されたストリームに保存します。

```csharp
public WatermarkResult Save(Stream document, SaveOptions options)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| ドキュメント | Stream | ドキュメントデータを保存するストリームです。 |
| オプション | SaveOptions | ドキュメントを保存する際に使用する追加オプションです。 |

### 備考

ドキュメントの保存について詳しくは [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### 例

透かしを追加し、デフォルトの[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions)でドキュメントをメモリストリームに保存します。

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    using (MemoryStream stream = new MemoryStream())
    {
        watermarker.Save(stream, new SaveOptions());
        // ...
    }
}
```

### 関連項目

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
