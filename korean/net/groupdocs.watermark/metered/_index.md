---
title: Metered
second_title: .NET API 참조용 GroupDocs.Watermark
description: 요금제 라이센스로 구성 요소에 라이센스를 부여하는 방법을 제공합니다.
type: docs
weight: 1620
url: /ko/net/groupdocs.watermark/metered/
---
## Metered class

요금제 라이센스로 구성 요소에 라이센스를 부여하는 방법을 제공합니다.

```csharp
public class Metered
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Metered](metered)() | 의 새 인스턴스를 초기화합니다.[`Metered`](../metered) 클래스. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [SetMeteredKey](../../groupdocs.watermark/metered/setmeteredkey)(string, string) | 측정된 키로 제품을 활성화합니다. |
| static [GetConsumptionCredit](../../groupdocs.watermark/metered/getconsumptioncredit)() | 소비된 크레딧 수를 검색합니다. |
| static [GetConsumptionQuantity](../../groupdocs.watermark/metered/getconsumptionquantity)() | 처리된 MB 양을 검색합니다. |

### 비고

**더 알아보기**

* 요금제 라이선스에 대한 추가 정보: [요금제 라이선스 FAQ](https://purchase.groupdocs.com/faqs/licensing/metered)
* 추가 정보**GroupDocs.워터마크** 라이센스: [평가 제한 및 라이선스](https://docs.groupdocs.com/display/watermarknet/Evaluation+Limitations+and+Licensing)

### 예

다음 예는 측정된 키로 제품을 활성화하는 방법을 보여줍니다.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### 또한보십시오

* 네임스페이스 [GroupDocs.Watermark](../../groupdocs.watermark)
* 집회 [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->