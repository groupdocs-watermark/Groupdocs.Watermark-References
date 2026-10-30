---
title: "저장"
second_title: "GroupDocs.Watermark for .NET API 레퍼런스"
description: "문서 데이터를 기본 스트림에 저장합니다."
type: docs
weight: 100
url: /ko/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

문서 데이터를 기본 스트림에 저장합니다.

```csharp
public WatermarkResult Save()
```

### 비고

문서 저장에 대해 자세히 알아보세요 [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### 예제

이메일 메시지 본문/제목에서 특정 텍스트 조각을 제거하고 이메일 메시지를 저장합니다.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // 참고: 검색은 TextSearchCriteria 인스턴스를 Search 메서드에 전달할 때만 수행됩니다.
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // 찾은 텍스트 조각을 제거합니다
    watermarker.Remove(watermarks);
    // 변경 사항을 저장합니다
    watermarker.Save();
}
```

### 또 보기

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

문서를 지정된 파일 위치에 저장합니다.

```csharp
public WatermarkResult Save(string filePath)
```

| 매개변수 | Type | 설명 |
| --- | --- | --- |
| filePath | String | 문서 데이터를 저장할 파일 경로입니다. |

### 비고

문서 저장에 대해 자세히 알아보세요 [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### 예제

워터마크를 추가하고 문서를 다른 파일에 저장합니다.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf");                                   
}                                                                                   
```

### 또 보기

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

문서를 지정된 스트림에 저장합니다.

```csharp
public WatermarkResult Save(Stream document)
```

| 매개변수 | Type | 설명 |
| --- | --- | --- |
| 문서 | Stream | 문서 데이터를 저장할 스트림입니다. |

### 비고

문서 저장에 대해 자세히 알아보세요 [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### 예제

워터마크를 추가하고 문서를 메모리 스트림에 저장합니다.

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

### 또 보기

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

저장 옵션을 사용하여 문서 데이터를 기본 스트림에 저장합니다.

```csharp
public WatermarkResult Save(SaveOptions options)
```

| 매개변수 | Type | 설명 |
| --- | --- | --- |
| 옵션 | SaveOptions | 문서를 저장할 때 사용할 추가 옵션입니다. |

### 비고

문서 저장에 대해 자세히 알아보세요 [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### 예제

워터마크를 추가하고 기본 [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions)으로 문서를 저장합니다.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### 또 보기

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

저장 옵션을 사용하여 문서를 지정된 파일 위치에 저장합니다.

```csharp
public WatermarkResult Save(string filePath, SaveOptions options)
```

| 매개변수 | Type | 설명 |
| --- | --- | --- |
| filePath | String | 문서 데이터를 저장할 파일 경로입니다. |
| 옵션 | SaveOptions | 문서를 저장할 때 사용할 추가 옵션입니다. |

### 비고

문서 저장에 대해 자세히 알아보세요 [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### 예제

워터마크를 추가하고 기본 [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions)으로 문서를 다른 파일에 저장합니다.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### 또 보기

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

저장 옵션을 사용하여 문서를 지정된 스트림에 저장합니다.

```csharp
public WatermarkResult Save(Stream document, SaveOptions options)
```

| 매개변수 | Type | 설명 |
| --- | --- | --- |
| 문서 | Stream | 문서 데이터를 저장할 스트림입니다. |
| 옵션 | SaveOptions | 문서를 저장할 때 사용할 추가 옵션입니다. |

### 비고

문서 저장에 대해 자세히 알아보세요 [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### 예제

워터마크를 추가하고 기본 [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions)으로 문서를 메모리 스트림에 저장합니다.

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

### 또 보기

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
