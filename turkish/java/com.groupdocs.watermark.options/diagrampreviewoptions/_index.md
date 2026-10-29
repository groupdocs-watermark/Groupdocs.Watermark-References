---
title: "DiagramPreviewOptions"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Diagram belgesi önizlemesi oluşturmak için gereksinimleri ayarlama ve akış delegeleri sağlamak için seçenekler sunar."
type: docs
weight: 12
url: /tr/java/com.groupdocs.watermark.options/diagrampreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class DiagramPreviewOptions extends PreviewOptions
```

Diagram belgesi önizlemesi oluşturmak için gereksinimleri ayarlama ve akış delegeleri sağlamak için seçenekler sunar.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [DiagramPreviewOptions(ICreatePageStream createPageStream)](#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Çıktı akışının kapanmasına neden olacak şekilde yeni bir `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` sınıfı örneği başlatır. |
|
|  | [DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | İstemciye daha sonraki kullanım için çıktı akışının döndürülmesini sağlayan `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` sınıfının yeni bir örneğini başlatır. |
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [DefaultResolution](#DefaultResolution) | Varsayılan çözünürlük inç başına nokta (dpi) cinsinden. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getResolution()](#getResolution--) | Oluşturulan görüntüler için çözünürlüğü, inç başına nokta (dpi) cinsinden alır. |
|
|  | [setResolution(float value)](#setResolution-float-) | Oluşturulan görüntüler için çözünürlüğü, inç başına nokta (dpi) cinsinden ayarlar. |
|
|  | [getHighQualityRendering()](#getHighQualityRendering--) | Yüksek kaliteli renderleme için bayrağı alır. |
|
|  | [setHighQualityRendering(boolean value)](#setHighQualityRendering-boolean-) | Yüksek kaliteli renderleme için bayrağı ayarlar. |
|
### DiagramPreviewOptions(ICreatePageStream createPageStream) {#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public DiagramPreviewOptions(ICreatePageStream createPageStream)
```


Çıktı akışının kapanmasına neden olacak şekilde yeni bir `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` sınıfı örneği başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Belirli bir sayfa önizlemesi için bir akış oluşturur. |
|

### DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


İstemciye daha sonraki kullanım için çıktı akışının döndürülmesini sağlayan `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Belirli bir sayfa önizlemesi için bir akış oluşturur. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Sayfa önizlemesi oluşturmanın tamamlandığını bildirir ve çıktı akışını alır. |
|

### DefaultResolution {#DefaultResolution}
```
public static final float DefaultResolution
```


Varsayılan çözünürlük inç başına nokta (dpi) cinsinden.


### getResolution() {#getResolution--}
```
public final float getResolution()
```


Oluşturulan görüntüler için çözünürlüğü, inç başına nokta (dpi) cinsinden alır.


**Returns:**
float - Oluşturulan görüntüler için çözünürlük, inç başına nokta (dpi) cinsinden.

<br />

*** ** * ** ***

Varsayılan değer 300'dür.

<br />


### setResolution(float value) {#setResolution-float-}
```
public final void setResolution(float value)
```


Oluşturulan görüntüler için çözünürlüğü, inç başına nokta (dpi) cinsinden ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | float | Oluşturulan görüntüler için çözünürlük, inç başına nokta (dpi) cinsinden. |

<br />

*** ** * ** ***

Varsayılan değer 300'dür.

<br />

|

### getHighQualityRendering() {#getHighQualityRendering--}
```
public final boolean getHighQualityRendering()
```


Yüksek kaliteli renderleme için bayrağı alır.


**Returns:**
boolean - Yüksek kaliteli renderleme için bayrak.

<br />

*** ** * ** ***

Yüksek kaliteli renderleme daha fazla kaynak kullanır. Varsayılan değer false.

<br />


### setHighQualityRendering(boolean value) {#setHighQualityRendering-boolean-}
```
public final void setHighQualityRendering(boolean value)
```


Yüksek kaliteli renderleme için bayrağı ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | Yüksek kaliteli renderleme için bayrak. |

<br />

*** ** * ** ***

Yüksek kaliteli renderleme daha fazla kaynak kullanır. Varsayılan değer false.

<br />

|

