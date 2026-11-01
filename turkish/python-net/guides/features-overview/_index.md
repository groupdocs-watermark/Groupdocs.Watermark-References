---
title: "GroupDocs.Watermark for Python via .NET, tek bir format bağımsız API aracılığıyla metin ve görüntü filigranlarını ekler, arar ve kaldırır — format‑spesifik yerleştirme, içerik‑ağacı düzenleme, kilitleme ve rasterleştirme özellikleriyle."
linkTitle: "Features overview"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "GroupDocs.Watermark for Python via .NET, geniş bir [desteklenen belge formatları](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/) yelpazesinde filigran ekleme, arama ve kaldırma işlemleri sağlar. Her işlem aynı iş akışını izler: bir belgeyi [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) ile açın, `add()`, `search()` veya `remove()` metodunu çağırın, ardından sonucu orijinal formatına `save()` ile kaydedin. Aşağıdaki yetenekler tek bir geçişte serbestçe birleştirilebilir."
type: docs
url: /tr/python-net/guides/features-overview/
is_root: false
weight: 30
---


Yazı tipi, renk, opaklık, dönüş, hizalama ve boyutlandırma üzerinde tam kontrol sağlayarak stillendirilmiş metin veya görüntü filigranları ekleyin. Görüntü filigranları bir dosyadan veya akıştan yüklenebilir. Bakınız [Add text watermarks](/watermark/python-net/guides/add-text/) ve [Add image watermarks](/watermark/python-net/guides/add-image/).

## Text and image watermarks

Filigranı mutlak koordinatlarla veya ebeveyn‑göreli hizalama ve kenar boşluklarıyla konumlandırın, sayfaya göre ölçeklendirin, döndürün ve tekrar eden bir desenle tüm sayfa boyunca döşeyin. Bakınız [Customize watermarks](/watermark/python-net/guides/customize/), [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/), ve [Adding text watermarks](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/).

## Customization and tiling

Her format için uygun seçenekleri kullanarak filigranları yerleştirin — PDF artefaktları, ek açıklamalar ve yalnızca yazdırma ek açıklamaları; sunum slaytları, ana slaytlar, düzenler ve notlar; elektronik tablo çalışma sayfaları, arka planlar ve üstbilgi/altbilgi; Visio sayfaları; ve kilitli Word bölümleri ve sayfaları. Bakınız [Add watermarks to PDF documents](https://docs.groupdocs.com/watermark/python-net/add-watermarks-to-pdf-documents/) ve diğer format konularını [Developer Guide](https://docs.groupdocs.com/watermark/python-net/adding-watermarks/) içinde.

## Format-specific placement

Bir belgede zaten bulunan filigranları — üçüncü taraf araçlar tarafından eklenenler dahil — tam metin, düzenli ifade, görüntü benzerliği veya metin biçimlendirmesiyle bulun ve kriterleri `and_`/`or_`/`not_` ile birleştirin. Bulunduktan sonra metinlerini veya görüntülerini değiştirin ya da kaldırın. Bakınız [Searching watermarks](/watermark/python-net/guides/searching-watermarks/), [Modifying found watermark properties](https://docs.groupdocs.com/watermark/python-net/modifying-found-watermark-properties/), ve [Removing found watermarks](https://docs.groupdocs.com/watermark/python-net/removing-found-watermarks/).

## Searching, modifying, and removing

Bir belgede zaten mevcut olan filigranları — üçüncü taraf araçlar tarafından eklenenler dahil — kesin metin, düzenli ifade, görüntü benzerliği veya metin biçimlendirmesiyle bulun ve kriterleri `and_`/`or_`/`not_` ile birleştirin. Bulunduğunda, metinlerini veya görüntülerini değiştirin ya da kaldırın. Bakınız [Filigranları Arama](/watermark/python-net/guides/searching-watermarks/), [Bulunan filigran özelliklerini değiştirme](https://docs.groupdocs.com/watermark/python-net/modifying-found-watermark-properties/), ve [Bulunan filigranları kaldırma](https://docs.groupdocs.com/watermark/python-net/removing-found-watermarks/).

## Working with existing content

`Watermarker.get_content()` belirli bir formata özgü içerik ağacını ortaya çıkarır, böylece mevcut şekilleri, PDF XObject'leri/artefaktları/annotasyonları, ekleri, arka planları ve üstbilgi/altbilgileri inceleyebilir ve düzenleyebilirsiniz — ve bir belgenin içine gömülü görüntülere `get_images()` ile filigran ekleyebilirsiniz. Bakınız [Adding watermark to images inside a document](https://docs.groupdocs.com/watermark/python-net/adding-watermark-to-images-inside-a-document/).

## Tamper resistance

Filigranları kilitleyerek, Word belgelerini koruyarak, yalnızca yazdırma amaçlı PDF annotasyonları ekleyerek veya PDF sayfalarını rasterleştirerek filigranın kaldırılmasını zorlaştırın. Bakınız [Locking watermark in word processing document](https://docs.groupdocs.com/watermark/python-net/locking-watermark-in-word-processing-document/) ve [Rasterize document or page](https://docs.groupdocs.com/watermark/python-net/rasterize-document-or-page/).

## Document inspection

Bir belgenin dosya türünü, sayfa sayısını ve boyutunu değiştirmeden okuyun ve kütüphanenin desteklediği tüm dosya formatlarını listeleyin. Bakınız [Get document info](/watermark/python-net/guides/get-document-info/) ve [Get supported file formats](/watermark/python-net/guides/get-supported-file-formats/).

## On-premise

GroupDocs.Watermark for Python via .NET tamamen kendi altyapınızda çalışır — belgeleriniz ortamınızdan dışarı çıkmaz. Paket, ihtiyacı olan her şeyi içinde barındıran bağımsız bir wheel'dır, bu yüzden Microsoft Office, OpenOffice veya ayrı bir çalışma zamanı kurulumuna gerek yoktur. Desteklenen platformlar ve yerel bağımlılıklar için [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) sayfasına bakın.
