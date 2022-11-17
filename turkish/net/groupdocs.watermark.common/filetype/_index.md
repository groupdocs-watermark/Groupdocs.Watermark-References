---
title: FileType
second_title: .NET API Başvurusu için GroupDocs.Watermark
description: Dosya türünü temsil eder.
type: docs
weight: 40
url: /tr/net/groupdocs.watermark.common/filetype/
---
## FileType class

Dosya türünü temsil eder.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | Dosya adı son ekini ("." noktası dahil) alır, örneğin, ".doc". |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | Dosya türü adını alır, örneğin, "Microsoft Word Belgesi". |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | Biçim ailesini alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | Dosya uzantısını dosya türüne eşler. |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | Mevcut olup olmadığını belirler.[`FileType`](../filetype) belirtilenle aynı[`FileType`](../filetype) nesne. |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | Mevcut olup olmadığını belirler.[`FileType`](../filetype) belirtilen nesne ile aynı. |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | Geçerli için bir karma kod döndürür[`FileType`](../filetype) nesne. |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | Geçerli nesneyi temsil eden bir dize döndürür. |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | Desteklenen dosya türlerini alır. |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | İki olup olmadığını belirler[`FileType`](../filetype) nesneler aynıdır. |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | İki olup olmadığını belirler[`FileType`](../filetype) nesneler aynı değil. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | .BMP uzantılı dosyalar, bitmap dijital görüntüleri depolamak için kullanılan Bitmap Görüntü dosyalarını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/bmp/) . |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | .doc uzantılı dosyalar, Microsoft Word tarafından oluşturulan belgeleri veya ikili dosya biçimindeki diğer sözcük işleme belgelerini temsil eder. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/word-processing/doc/) . |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | DOCM dosyaları, Microsoft Word 2007 veya daha yüksek sürümde oluşturulmuş ve makro çalıştırma özelliğine sahip belgelerdir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/docm/) . |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | DOCX, Microsoft Word belgeleri için iyi bilinen bir biçimdir. 2007'den itibaren Microsoft Office 2007'nin release sürümüyle tanıtılan bu yeni Belge biçiminin yapısı, düz ikili 'den XML ve ikili dosyaların birleşimine değiştirildi. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/word-processing/docx/) . |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | .DOT uzantılı dosyalar, daha fazla DOC veya DOCX dosyası oluşturmak için önceden biçimlendirilmiş ayarlar 'ye sahip olmak üzere Microsoft Word tarafından oluşturulan şablon dosyalarıdır. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/word-processing/dot/) . |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | DOTM uzantılı bir dosya, Microsoft Word 2007 veya üstü ile oluşturulan şablon dosyasını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/dotm/) . |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | DOTX uzantılı dosyalar, daha fazla DOCX dosyası oluşturmak için önceden biçimlendirilmiş ayarlara sahip olmak üzere Microsoft Word tarafından oluşturulan şablon dosyalarıdır. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/word-processing/dotx/) . |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | EML dosya biçimi, Outlook ve diğer ilgili uygulamalar kullanılarak kaydedilen e-posta mesajlarını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/email/eml/) . |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | EMLX dosya formatı Apple tarafından uygulanır ve geliştirilir. Apple Mail uygulaması, e-postaları dışa aktarmak için EMLX dosya biçimini kullanır. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/email/emlx/) . |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | ZIP paketi (.xml) yerine düz bir XML dosyasında saklanan Office Açık XML WordprocessingML. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | ZIP paketi (.xml) yerine düz bir XML dosyasında saklanan Office Açık XML WordprocessingML Makro Etkin Belge. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | ZIP paketi (.xml) yerine düz bir XML dosyasında saklanan Office Açık XML WordprocessingML Şablonu (makrosuz). Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | ZIP paketi (.xml) yerine düz bir XML dosyasında saklanan Office Açık XML WordprocessingML Makro Etkin Şablon. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | GIF veya Grafik Değişim Biçimi, yüksek oranda sıkıştırılmış bir görüntü türüdür. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/gif/) . |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | JPEG, kayıplı sıkıştırma yöntemi kullanılarak kaydedilen bir görüntü biçimi türüdür. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/jpeg/) . |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | JPEG 2000 (JPF), bir görüntü kodlama sistemi ve en gelişmiş görüntü sıkıştırma standardıdır. Wavelet teknolojisi kullanılarak olarak tasarlanan JPEG 2000, herhangi bir kalitedeki kayıpsız içeriği aynı anda kodlayabilir. Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | JPEG, kayıplı sıkıştırma yöntemi kullanılarak kaydedilen bir görüntü biçimi türüdür. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/jpeg/) . |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | JPEG 2000 (JPM), bir görüntü kodlama sistemi ve en gelişmiş görüntü sıkıştırma standardıdır. Wavelet teknolojisi kullanılarak olarak tasarlanan JPEG 2000, herhangi bir kalitedeki kayıpsız içeriği aynı anda kodlayabilir. Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | JPEG 2000 (JPX), bir görüntü kodlama sistemi ve en gelişmiş görüntü sıkıştırma standardıdır. Wavelet teknolojisi kullanılarak olarak tasarlanan JPEG 2000, herhangi bir kalitedeki kayıpsız içeriği aynı anda kodlayabilir. Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | MSG, Microsoft Outlook ve Exchange tarafından e-posta mesajlarını, kişileri, randevularını veya diğer görevleri depolamak için kullanılan bir dosya biçimidir. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/email/msg/) . |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | ODT dosyaları, OpenDocument Metin Dosyası biçimini temel alan kelime işlem uygulamalarıyla oluşturulan belge türüdür. Bunlar ücretsiz OpenOffice Writer gibi kelime işlemci uygulamalarıyla oluşturulur ve metin, resim, nesne ve stil gibi içerikleri tutabilir. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/word-processing/odt/) . |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | .OFT uzantılı dosyalar, Microsoft Outlook kullanılarak oluşturulan mesaj şablonu dosyalarını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/email/oft/) . |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | Office açık xml dosyası (.ooxml). |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | Taşınabilir Belge Biçimi (PDF), Adobe tarafından 1990'larda oluşturulmuş bir belge türüdür. this dosya formatının amacı, uygulama yazılımı, donanım ve İşletim Sisteminden bağımsız bir format olan 'de belgelerin ve diğer referans materyallerinin temsili için bir standart getirmekti. Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/view/pdf/) . |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | PNG, Portable Network Graphics, kayıpsız sıkıştırma kullanan bir tür raster görüntü dosyası formatını ifade eder. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/png/) . |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | POTM uzantılı dosyalar, Makroları destekleyen Microsoft PowerPoint şablon dosyalarıdır. POTM files , PowerPoint 2007 veya üzeri ile oluşturulur ve başka sunum dosyaları oluşturmak için kullanılabilecek varsayılan ayarları içerir. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/presentation/potm/) . |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | .POTX uzantılı dosyalar, Microsoft PowerPoint 2007 ve üzeri ile oluşturulan Microsoft PowerPoint şablon sunumlarını temsil eder. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/presentation/potx/) . |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | PPS, PowerPoint Slayt Gösterisi, dosyalar Slayt Gösterisi amacıyla Microsoft PowerPoint kullanılarak oluşturulur. PPS dosyası okuma ve oluşturma, Microsoft PowerPoint 97-2003 tarafından desteklenir. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/presentation/pps/) . |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | PPSM uzantılı dosyalar, Microsoft PowerPoint 2007 veya üstü ile oluşturulan Makro özellikli Slayt Gösterisi dosya formatını temsil eder. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/presentation/ppsm/) . |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | PPSX, Power Point Slayt Gösterisi, dosya Slayt Gösterisi amacıyla Microsoft PowerPoint 2007 ve üstü kullanılarak oluşturulmuştur. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/presentation/ppsx/) . |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | PPT uzantılı bir dosya, SlideShow olarak görüntülenen için bir slayt koleksiyonundan oluşan PowerPoint dosyasını temsil eder. Microsoft PowerPoint 97-2003 tarafından kullanılan İkili Dosya Biçimini belirtir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation/ppt/) . |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | PPTM uzantılı dosyalar, Microsoft PowerPoint 2007 veya daha yüksek sürümlerle oluşturulan Makro özellikli Sunum dosyalarıdır. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/presentation/pptm/) . |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | PPTX uzantılı dosyalar, popüler Microsoft PowerPoint uygulamasıyla oluşturulan sunum dosyalarıdır. İkili olan sunum dosyası biçimi PPT'nin önceki sürümünden farklı olarak, PPTX biçimi, Microsoft PowerPoint açık XML sunum dosyası biçimini temel alır. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/presentation/pptx/) . |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | Microsoft tarafından tanıtılan ve belgelenen Zengin Metin Biçimi (RTF), uygulamalarda kullanım için biçimli metin ve grafikleri kodlama yöntemini temsil eder. Biçim, diğer Microsoft Ürünleri ile platformlar arası belge alışverişini kolaylaştırır, böylece birlikte çalışabilirlik amacına hizmet eder. Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/word-processing/rtf/) . |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | TIFF veya TIF, Etiketli Görüntü Dosyası Biçimi, bu dosya biçimi standardına uyan çeşitli aygıtlarda kullanım amaçlı raster görüntüleri temsil eder. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/image/tiff/) . |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | TIFF veya TIF, Etiketli Görüntü Dosyası Biçimi, bu dosya biçimi standardına uyan çeşitli aygıtlarda kullanım amaçlı raster görüntüleri temsil eder. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/image/tiff/) . |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | Bilinmeyen dosya türünü temsil eder. |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | VDW, bir Web çizimini oluşturmak için gereken akışları ve depoları belirten Visio Graphics Service dosya biçimidir. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/web/vdw/) . |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | Microsoft Visio'da oluşturulan ancak XML biçiminde kaydedilen herhangi bir çizim veya grafik .VDX uzantısına sahiptir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/vdx/) . |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | VSD dosyaları, çeşitli grafik nesneleri ve bunlar arasındaki ara bağlantıyı temsil etmek için Microsoft Visio uygulamasıyla oluşturulan çizimlerdir. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/image/vsd/) . |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | VSDM uzantılı dosyalar, makroları destekleyen Microsoft Visio uygulamasıyla oluşturulmuş çizim dosyalarıdır. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/image/vsdm/) . |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | .VSDX uzantılı dosyalar, Microsoft Office 2013'ten itibaren kullanıma sunulan Microsoft Visio dosya biçimini temsil eder. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/image/vsdx/) . |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | VSS, Microsoft Visio 2007 ve önceki sürümleriyle oluşturulan kalıp dosyalarıdır. Kalıp dosyaları, bir .VSD Visio çizimine dahil edilebilecek drawing nesneleri sağlar. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/image/vss/) . |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | .VSSM uzantılı dosyalar, makrolar için destek sağlamayı destekleyen Microsoft Visio Stencil dosyalarıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/vssm/) . |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | .VSSX uzantılı dosyalar, Microsoft Visio 2013 ve üstü ile oluşturulan çizim kalıplarıdır. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/image/vssx/) . |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | VST uzantılı dosyalar, Microsoft Visio ile oluşturulan vektör görüntü dosyalarıdır ve başka dosyalar oluşturmak için şablonu görevi görür. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/image/vst/) . |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | VSTM uzantılı dosyalar, makroları destekleyen Microsoft Visio ile oluşturulan şablon dosyalarıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/vstm/) . |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | VSTX uzantılı dosyalar, Microsoft Visio 2013 ve üstü ile oluşturulan çizim şablon dosyalarıdır. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/image/vstx/) . |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | .VSX uzantılı dosyalar, Microsoft Visio'da diyagramlar oluşturmak için kullanılan çizimlerden ve şekillerden oluşan kalıpları ifade eder. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/image/vsx/) . |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | VTX uzantılı bir dosya, XML dosya biçiminde diske kaydedilen bir Microsoft Visio çizim şablonudur. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/vtx/) . |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | WebP, Google tarafından tanıtılan, kayıpsız ve kayıplı sıkıştırmaya dayalı modern bir raster web resim dosyası biçimidir. Görüntü boyutunu önemli ölçüde azaltırken aynı görüntü kalitesini sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/webp/) . |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | XLS uzantılı dosyalar, Excel İkili Dosya Biçimini temsil eder. Bu tür dosyalar, Microsoft Excel ve OpenOffice Calc veya Apple Numbers gibi diğer benzer elektronik tablo programları tarafından oluşturulabilir. Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/specification/spreadsheet/xls/) . |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | XLSB dosya biçimi, Excel çalışma kitabı içeriğini belirten bir kayıt ve yapıları koleksiyonu olan Excel İkili Dosya Biçimini belirtir. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/specification/spreadsheet/xlsb/) . |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | XLSM uzantılı dosyalar, Makroları destekleyen bir Elektronik Tablo dosyası türüdür. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/specification/spreadsheet/xlsm/) . |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | XLSX, Microsoft tarafından Microsoft Office 2007'nin sürümüyle tanıtılan Microsoft Excel belgeleri için iyi bilinen bir biçimdir. Bu dosya hakkında daha fazla bilgi edinin: format [burada](https://wiki.fileformat.com/specification/spreadsheet/xlsx/) . |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | .XLT uzantılı dosyalar, Microsoft Office paketinin bir parçası olarak gelen bir elektronik tablo uygulaması olan Microsoft Excel ile oluşturulan şablon dosyalarıdır. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/specification/spreadsheet/xlt/) . |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | XLTM dosya uzantısı, Microsoft Excel tarafından Macro-enabled şablon dosyaları olarak oluşturulan dosyaları temsil eder. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/specification/spreadsheet/xltm/) . |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | XLTX uzantılı dosyalar, Office OpenXML dosya biçimi belirtimlerini temel alan Microsoft Excel Şablon dosyalarını temsil eder. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/specification/spreadsheet/xltx/) . |

### Notlar

Bu sınıf, tarafından desteklenen tüm dosya türlerinin listesini elde etmek için yöntemler sağlar.**GroupDocs.Filigran**.**Daha fazla bilgi edin**

* [Desteklenen Belge Biçimleri](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [Desteklenen dosya biçimlerini edinin](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [Belge bilgilerini al](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### Ayrıca bakınız

* ad alanı [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* toplantı [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
