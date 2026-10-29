---
title: "DiagramShapeWatermarkOptions"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Visio belgesine şekil filigranı eklerken filigran ekleme seçeneklerini temsil eder."
type: docs
weight: 14
url: /tr/java/com.groupdocs.watermark.options/diagramshapewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.DiagramWatermarkOptions](../../com.groupdocs.watermark.options/diagramwatermarkoptions)
```
public final class DiagramShapeWatermarkOptions extends DiagramWatermarkOptions
```

Visio belgesine şekil filigranı eklerken filigran ekleme seçeneklerini temsil eder.

**Learn more:**

* [Add watermarks to diagram documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents)

Aşağıdaki örnek, Visio belgesinin tüm sayfalarına korumalı bir filigran eklemenin nasıl yapılacağını gösterir.
>
> ````
> ```
>
>    DiagramLoadOptions loadOptions = new DiagramLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.vsdx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));
>
>    DiagramShapeWatermarkOptions options = new DiagramShapeWatermarkOptions();
>    options.setLocked(true);
>    options.setPlacementType(DiagramWatermarkPlacementType.AllPages);
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.vsdx");
>    watermarker.close();
>  
> ```
> ````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [DiagramShapeWatermarkOptions()](#DiagramShapeWatermarkOptions--) | Yeni bir `[DiagramShapeWatermarkOptions](../../com.groupdocs.watermark.options/diagramshapewatermarkoptions)` sınıfı örneği başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPlacementType()](#getPlacementType--) | Filigranın ekleneceği sayfaları belirten bir değeri alır. |
|
|  | [setPlacementType(int value)](#setPlacementType-int-) | Filigranın ekleneceği sayfaları belirten bir değeri alır veya ayarlar. |
|
### DiagramShapeWatermarkOptions() {#DiagramShapeWatermarkOptions--}
```
public DiagramShapeWatermarkOptions()
```


Yeni bir `[DiagramShapeWatermarkOptions](../../com.groupdocs.watermark.options/diagramshapewatermarkoptions)` sınıfı örneği başlatır.


### getPlacementType() {#getPlacementType--}
```
public final int getPlacementType()
```


Filigranın ekleneceği sayfaları belirten bir değeri alır.


**Returns:**
int - Filigranın ekleneceği sayfaları belirten `[DiagramWatermarkPlacementType](../../com.groupdocs.watermark.contents/diagramwatermarkplacementtype)`.

### setPlacementType(int value) {#setPlacementType-int-}
```
public final void setPlacementType(int value)
```


Filigranın ekleneceği sayfaları belirten bir değeri alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | int | `[DiagramWatermarkPlacementType](../../com.groupdocs.watermark.contents/diagramwatermarkplacementtype)`, filigranın ekleneceği sayfaları belirten. |
|

