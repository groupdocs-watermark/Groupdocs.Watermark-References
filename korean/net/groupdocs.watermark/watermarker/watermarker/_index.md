---
title: Watermarker
second_title: .NET API 참조용 GroupDocs.Watermark
description: 의 새 인스턴스를 초기화합니다.Watermarkergroupdocs.watermark/watermarker 지정된 문서 경로가 있는 클래스.
type: docs
weight: 10
url: /ko/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

의 새 인스턴스를 초기화합니다.[`Watermarker`](../../watermarker) 지정된 문서 경로가 있는 클래스.

```csharp
public Watermarker(string filePath)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 문서를 로드할 파일 경로입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 제공된 문서 유형이 지원되지 않습니다. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 제공된 비밀번호가 올바르지 않습니다. |

### 비고

문서 로드에 대해 자세히 알아보기: [문서 로드 중](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### 예

지원되는 형식의 콘텐츠를 로드하고 저장합니다.

```csharp
// 파일에서 콘텐츠를 로드합니다.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Watermarker 클래스의 메서드를 사용하여 워터마크를 추가, 검색 또는 제거합니다.

    // 문서를 저장합니다.
    watermarker.Save("D:\\output.pdf");
}
```

### 또한보십시오

* class [Watermarker](../../watermarker)
* 네임스페이스 [GroupDocs.Watermark](../../watermarker)
* 집회 [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

의 새 인스턴스를 초기화합니다.[`Watermarker`](../../watermarker)지정된 문서 경로 및 로드 옵션이 있는 클래스.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 문서를 로드할 파일 경로입니다. |
| options | LoadOptions | 문서를 로드할 때 사용할 추가 옵션입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 제공된 문서 유형이 지원되지 않습니다. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 제공된 비밀번호가 올바르지 않습니다. |

### 비고

문서 로드에 대해 자세히 알아보기: [문서 로드 중](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### 예

암호를 사용하여 암호화된 PDF 문서를 로드합니다.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    // ...
}
```

### 또한보십시오

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* 네임스페이스 [GroupDocs.Watermark](../../watermarker)
* 집회 [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

의 새 인스턴스를 초기화합니다.[`Watermarker`](../../watermarker) 지정된 문서 경로 및 설정이 있는 클래스.

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 문서를 로드할 파일 경로입니다. |
| settings | WatermarkerSettings | 로드된 문서로 작업할 때 사용할 추가 설정입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 제공된 문서 유형이 지원되지 않습니다. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 제공된 비밀번호가 올바르지 않습니다. |

### 비고

문서 로드에 대해 자세히 알아보기: [문서 로드 중](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### 예

검색 가능한 개체를 전체적으로 설정합니다(그 이후에 로드될 모든 문서에 대해).

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

        // 발견된 워터마크 작업을 위한 코드는 여기에 있습니다.
    }
}
```

### 또한보십시오

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* 네임스페이스 [GroupDocs.Watermark](../../watermarker)
* 집회 [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

의 새 인스턴스를 초기화합니다.[`Watermarker`](../../watermarker) 지정된 문서 경로, 로드 옵션 및 설정이 있는 클래스.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 문서를 로드할 파일 경로입니다. |
| options | LoadOptions | 문서를 로드할 때 사용할 추가 옵션입니다. |
| settings | WatermarkerSettings | 로드된 문서로 작업할 때 사용할 추가 설정입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 제공된 문서 유형이 지원되지 않습니다. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 제공된 비밀번호가 올바르지 않습니다. |

### 비고

문서 로드에 대해 자세히 알아보기: [문서 로드 중](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### 예

이메일 메시지 본문/제목에서 특정 텍스트 조각을 찾습니다.

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
    // 참고, Search 메서드에 TextSearchCriteria 인스턴스를 전달한 경우에만 검색이 수행됩니다.
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // 찾은 텍스트 조각 제거
    watermarks.Clear();
    // 변경 사항을 저장하다
    watermarker.Save();
}
```

### 또한보십시오

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* 네임스페이스 [GroupDocs.Watermark](../../watermarker)
* 집회 [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

의 새 인스턴스를 초기화합니다.[`Watermarker`](../../watermarker) 지정된 stream. 클래스

```csharp
public Watermarker(Stream document)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Stream | 문서를 로드할 스트림입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 제공된 문서 유형이 지원되지 않습니다. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 제공된 비밀번호가 올바르지 않습니다. |

### 비고

문서 로드에 대해 자세히 알아보기 [문서 로드 중](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### 예

지원되는 형식의 문서를 로드하고 저장합니다.

```csharp
// 스트림에서 콘텐츠를 로드합니다.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // Watermarker 클래스의 메서드를 사용하여 워터마크를 추가, 검색 또는 제거합니다.

    // 변경 사항을 저장하다.
    watermarker.Save(outputStream);
}
```

### 또한보십시오

* class [Watermarker](../../watermarker)
* 네임스페이스 [GroupDocs.Watermark](../../watermarker)
* 집회 [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

의 새 인스턴스를 초기화합니다.[`Watermarker`](../../watermarker) 지정된 stream 및 로드 옵션이 있는 클래스.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Stream | 문서를 로드할 스트림입니다. |
| options | LoadOptions | 문서를 로드할 때 사용할 추가 옵션입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 제공된 문서 유형이 지원되지 않습니다. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 제공된 비밀번호가 올바르지 않습니다. |

### 비고

문서 로드에 대해 자세히 알아보기 [문서 로드 중](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### 예

password 를 사용하여 암호화된 PDF 문서 로드

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    // ...
}
```

### 또한보십시오

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* 네임스페이스 [GroupDocs.Watermark](../../watermarker)
* 집회 [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

의 새 인스턴스를 초기화합니다.[`Watermarker`](../../watermarker) stream 및 settings. 가 지정된 클래스

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Stream | 문서를 로드할 스트림입니다. |
| settings | WatermarkerSettings | 로드된 문서로 작업할 때 사용할 추가 설정입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 제공된 문서 유형이 지원되지 않습니다. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 제공된 비밀번호가 올바르지 않습니다. |

### 비고

문서 로드에 대해 자세히 알아보기 [문서 로드 중](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### 예

검색 가능한 개체를 전체적으로 설정합니다(그 이후에 로드될 모든 문서에 대해).

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

        // 발견된 워터마크 작업을 위한 코드는 여기에 있습니다.
    }
}
```

### 또한보십시오

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* 네임스페이스 [GroupDocs.Watermark](../../watermarker)
* 집회 [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

의 새 인스턴스를 초기화합니다.[`Watermarker`](../../watermarker) 지정된 스트림이 있는 클래스, 로드 옵션 및 설정.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Stream | 문서를 로드할 스트림입니다. |
| options | LoadOptions | 문서를 로드할 때 사용할 추가 옵션입니다. |
| settings | WatermarkerSettings | 로드된 문서로 작업할 때 사용할 추가 설정입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 제공된 문서 유형이 지원되지 않습니다. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 제공된 비밀번호가 올바르지 않습니다. |

### 비고

문서 로드에 대해 자세히 알아보기 [문서 로드 중](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### 예

이메일 메시지 본문/제목에서 특정 텍스트 조각을 찾습니다.

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
    // 참고, Search 메서드에 TextSearchCriteria 인스턴스를 전달한 경우에만 검색이 수행됩니다.
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // 찾은 텍스트 조각 제거
    watermarks.Clear();
    // 변경 사항을 저장하다
    watermarker.Save();
}
```

### 또한보십시오

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* 네임스페이스 [GroupDocs.Watermark](../../watermarker)
* 집회 [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
