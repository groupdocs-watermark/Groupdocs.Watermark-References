---
title: "WordProcessingPreviewOptions"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "WordProcessing belgesi için ön izleme oluşturma gereksinimlerini ve akış delegelerini ayarlama seçenekleri sağlar."
type: docs
weight: 69
url: /tr/java/com.groupdocs.watermark.options/wordprocessingpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class WordProcessingPreviewOptions extends PreviewOptions
```

WordProcessing belgesi için ön izleme oluşturma gereksinimlerini ve akış delegelerini ayarlama seçenekleri sağlar.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [WordProcessingPreviewOptions(ICreatePageStream createPageStream)](#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` sınıfının yeni bir örneğini başlatır ve çıktı akışının kapatılmasına neden olur. |
|
|  | [WordProcessingPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` sınıfının yeni bir örneğini başlatır ve çıktı akışının daha sonraki kullanım için istemciye geri döndürülmesine neden olur. |
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
### WordProcessingPreviewOptions(ICreatePageStream createPageStream) {#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public WordProcessingPreviewOptions(ICreatePageStream createPageStream)
```


`[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` sınıfının yeni bir örneğini başlatır ve çıktı akışının kapatılmasına neden olur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Belirli bir sayfa önizlemesi için bir akış oluşturur. |
|

### WordProcessingPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public WordProcessingPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


`[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` sınıfının yeni bir örneğini başlatır ve çıktı akışının daha sonraki kullanım için istemciye geri döndürülmesine neden olur.


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

Varsayılan değer 96'dır.

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

Varsayılan değer 96'dır.

<br />

|

