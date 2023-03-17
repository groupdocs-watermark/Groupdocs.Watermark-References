---
title: Save
second_title: GroupDocs.Watermark for .NET API リファレンス
description: ドキュメント データを基になるストリームに保存します
type: docs
weight: 100
url: /ja/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

ドキュメント データを基になるストリームに保存します。

```csharp
public void Save()
```

### 備考

ドキュメントの保存についての詳細をご覧ください [ドキュメントの保存](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### 例

電子メール メッセージの本文/件名から特定のテキスト フラグメントを削除し、電子メール メッセージを保存します。

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // 注: TextSearchCriteria インスタンスを Search メソッドに渡した場合にのみ、検索が実行されます。
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // 見つかったテキスト フラグメントを削除します
    watermarker.Remove(watermarks);
    // 変更内容を保存
    watermarker.Save();
}
```

### 関連項目

* class [Watermarker](../../watermarker)
* 名前空間 [GroupDocs.Watermark](../../watermarker)
* 組み立て [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

指定したファイルの場所にドキュメントを保存します。

```csharp
public void Save(string filePath)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | ドキュメント データを保存するファイル パス。 |

### 備考

ドキュメントの保存についての詳細をご覧ください [ドキュメントの保存](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

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

* class [Watermarker](../../watermarker)
* 名前空間 [GroupDocs.Watermark](../../watermarker)
* 組み立て [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

ドキュメントを指定されたストリームに保存します。

```csharp
public void Save(Stream document)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Stream | ドキュメント データを保存するストリーム。 |

### 備考

ドキュメントの保存についての詳細をご覧ください [ドキュメントの保存](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### 例

透かしを追加し、ドキュメントをメモリ ストリームに保存します。

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

* class [Watermarker](../../watermarker)
* 名前空間 [GroupDocs.Watermark](../../watermarker)
* 組み立て [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

保存オプションを使用して、基になるストリームにドキュメント データを保存します。

```csharp
public void Save(SaveOptions options)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| options | SaveOptions | ドキュメントを保存するときに使用する追加オプション。 |

### 備考

ドキュメントの保存についての詳細をご覧ください [ドキュメントの保存](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### 例

透かしを追加し、ドキュメントをデフォルトで保存します[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### 関連項目

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* 名前空間 [GroupDocs.Watermark](../../watermarker)
* 組み立て [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

保存オプションを使用して、指定されたファイルの場所にドキュメントを保存します。

```csharp
public void Save(string filePath, SaveOptions options)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | ドキュメント データを保存するファイル パス。 |
| options | SaveOptions | ドキュメントを保存するときに使用する追加オプション。 |

### 備考

ドキュメントの保存についての詳細をご覧ください [ドキュメントの保存](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### 例

透かしを追加し、ドキュメントをデフォルトで別のファイルに保存します[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### 関連項目

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* 名前空間 [GroupDocs.Watermark](../../watermarker)
* 組み立て [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

保存オプションを使用して、指定されたストリームにドキュメントを保存します。

```csharp
public void Save(Stream document, SaveOptions options)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Stream | ドキュメント データを保存するストリーム。 |
| options | SaveOptions | ドキュメントを保存するときに使用する追加オプション。 |

### 備考

ドキュメントの保存についての詳細をご覧ください [ドキュメントの保存](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### 例

透かしを追加し、デフォルトでドキュメントをメモリ ストリームに保存します[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

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

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* 名前空間 [GroupDocs.Watermark](../../watermarker)
* 組み立て [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
