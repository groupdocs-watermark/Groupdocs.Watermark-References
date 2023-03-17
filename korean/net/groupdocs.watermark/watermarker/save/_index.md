---
title: Save
second_title: .NET API 참조용 GroupDocs.Watermark
description: 문서 데이터를 기본 스트림에 저장합니다.
type: docs
weight: 100
url: /ko/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

문서 데이터를 기본 스트림에 저장합니다.

```csharp
public void Save()
```

### 비고

문서 저장에 대해 자세히 알아보기 [문서 저장](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### 예

이메일 메시지 본문/제목에서 특정 텍스트 조각을 제거하고 이메일 메시지를 저장합니다.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // 참고, Search 메서드에 TextSearchCriteria 인스턴스를 전달한 경우에만 검색이 수행됩니다.
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // 찾은 텍스트 조각 제거
    watermarker.Remove(watermarks);
    // 변경 사항을 저장하다
    watermarker.Save();
}
```

### 또한보십시오

* class [Watermarker](../../watermarker)
* 네임스페이스 [GroupDocs.Watermark](../../watermarker)
* 집회 [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

지정된 파일 위치에 문서를 저장합니다.

```csharp
public void Save(string filePath)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 문서 데이터를 저장할 파일 경로입니다. |

### 비고

문서 저장에 대해 자세히 알아보기 [문서 저장](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### 예

워터마크를 추가하고 문서를 다른 파일에 저장합니다.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf");                                   
}                                                                                   
```

### 또한보십시오

* class [Watermarker](../../watermarker)
* 네임스페이스 [GroupDocs.Watermark](../../watermarker)
* 집회 [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

지정된 스트림에 문서를 저장합니다.

```csharp
public void Save(Stream document)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Stream | 문서 데이터를 저장할 스트림입니다. |

### 비고

문서 저장에 대해 자세히 알아보기 [문서 저장](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### 예

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

### 또한보십시오

* class [Watermarker](../../watermarker)
* 네임스페이스 [GroupDocs.Watermark](../../watermarker)
* 집회 [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

저장 옵션을 사용하여 기본 스트림에 문서 데이터를 저장합니다.

```csharp
public void Save(SaveOptions options)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| options | SaveOptions | 문서를 저장할 때 사용할 추가 옵션입니다. |

### 비고

문서 저장에 대해 자세히 알아보기 [문서 저장](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### 예

워터마크를 추가하고 문서를 기본값으로 저장[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### 또한보십시오

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* 네임스페이스 [GroupDocs.Watermark](../../watermarker)
* 집회 [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

저장 옵션을 사용하여 지정된 파일 위치에 문서를 저장합니다.

```csharp
public void Save(string filePath, SaveOptions options)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 문서 데이터를 저장할 파일 경로입니다. |
| options | SaveOptions | 문서를 저장할 때 사용할 추가 옵션입니다. |

### 비고

문서 저장에 대해 자세히 알아보기 [문서 저장](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### 예

워터마크를 추가하고 문서를 기본값으로 다른 파일에 저장합니다.[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### 또한보십시오

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* 네임스페이스 [GroupDocs.Watermark](../../watermarker)
* 집회 [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

저장 옵션을 사용하여 지정된 스트림에 문서를 저장합니다.

```csharp
public void Save(Stream document, SaveOptions options)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Stream | 문서 데이터를 저장할 스트림입니다. |
| options | SaveOptions | 문서를 저장할 때 사용할 추가 옵션입니다. |

### 비고

문서 저장에 대해 자세히 알아보기 [문서 저장](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### 예

워터마크를 추가하고 문서를 기본 메모리 스트림에 저장합니다.[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

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

### 또한보십시오

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* 네임스페이스 [GroupDocs.Watermark](../../watermarker)
* 집회 [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
