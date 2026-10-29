---
title: "PresentationPreviewOptions"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Sunum belgesi önizlemesi oluşturmak için gereksinimleri ayarlama ve akış delegeleri sağlamak için seçenekler sunar."
type: docs
weight: 12
url: /tr/java/com.groupdocs.watermark/presentationpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PresentationPreviewOptions extends PreviewOptions
```

Sunum belgesi önizlemesi oluşturmak için gereksinimleri ayarlama ve akış delegeleri sağlamak için seçenekler sunar.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` sınıfının yeni bir örneğini başlatır ve çıktı akışını kapatır. |
|
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` sınıfının yeni bir örneğini başlatır ve çıktı akışını daha sonraki kullanım için istemciye geri döndürür. |
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
|  | [setResolution(long value)](#setResolution-long-) | Oluşturulan görüntüler için çözünürlüğü, inç başına nokta (dpi) cinsinden ayarlar. |
|
### PresentationPreviewOptions(ICreatePageStream createPageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream)
```


`[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` sınıfının yeni bir örneğini başlatır ve çıktı akışını kapatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Belirli bir sayfa önizlemesi için bir akış oluşturur. |
|

### PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


`[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` sınıfının yeni bir örneğini başlatır ve çıktı akışını daha sonraki kullanım için istemciye geri döndürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Belirli bir sayfa önizlemesi için bir akış oluşturur. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Sayfa önizlemesi oluşturmanın tamamlandığını bildirir ve çıktı akışını alır. |
|

### DefaultResolution {#DefaultResolution}
```
public static final long DefaultResolution
```


Varsayılan çözünürlük inç başına nokta (dpi) cinsinden.


### getResolution() {#getResolution--}
```
public final long getResolution()
```


Oluşturulan görüntüler için çözünürlüğü, inç başına nokta (dpi) cinsinden alır.


**Returns:**
long - Oluşturulan görüntüler için çözünürlük, inç başına nokta (dpi) cinsinden.

### setResolution(long value) {#setResolution-long-}
```
public final void setResolution(long value)
```


Oluşturulan görüntüler için çözünürlüğü, inç başına nokta (dpi) cinsinden ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | long | Oluşturulan görüntüler için çözünürlük, inç başına nokta (dpi) cinsinden. |
|

