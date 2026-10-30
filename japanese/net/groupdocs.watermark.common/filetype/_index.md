---
title: "FileType"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "ファイルタイプを表します。"
type: docs
weight: 40
url: /ja/net/groupdocs.watermark.common/filetype/
---
## FileType class

ファイルタイプを表します。

```csharp
public sealed class FileType : IEquatable<FileType>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | ファイル名のサフィックス（ピリオド \".\" を含む）を取得します。例: \".doc\"。 |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | ファイルタイプ名を取得します。例: \"Microsoft Word Document\"。 |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | フォーマットファミリを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | ファイル拡張子をファイルタイプにマッピングします。 |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | 現在の [`FileType`](../filetype) が指定された [`FileType`](../filetype) オブジェクトと同じかどうかを判断します。 |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | 現在の[`FileType`](../filetype) が指定されたオブジェクトと同じかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | 現在の[`FileType`](../filetype) オブジェクトのハッシュコードを返します。 |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | 現在のオブジェクトを表す文字列を返します。 |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | サポートされているファイルタイプを取得します。 |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | 2つの[`FileType`](../filetype) オブジェクトが同じかどうかを判断します。 |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | 2つの[`FileType`](../filetype) オブジェクトが異なるかどうかを判断します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | .BMP 拡張子を持つファイルは、ビットマップ画像ファイルを表し、ビットマップデジタル画像の保存に使用されます。これらの画像はグラフィックアダプタに依存せず、デバイス非依存ビットマップ (DIB) ファイル形式とも呼ばれます。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/bmp/)をご覧ください。 |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | .doc 拡張子のファイルは、Microsoft Word やその他のワードプロセッサで生成されたバイナリ形式の文書を表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/word-processing/doc/)をご覧ください。 |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | DOCM ファイルは、Microsoft Word 2007 以降で作成されたマクロ実行機能を持つ文書です。このファイル形式の詳細は[here](https://wiki.fileformat.com/word-processing/docm/)をご覧ください。 |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | DOCX は Microsoft Word 文書のよく知られた形式です。2007 年に Microsoft Office 2007 がリリースされた際に導入され、この新しい文書形式の構造は従来のバイナリから XML とバイナリの組み合わせに変更されました。このファイル形式の詳細は[here](https://wiki.fileformat.com/word-processing/docx/)をご覧ください。 |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | .DOT 拡張子のファイルは、Microsoft Word が作成したテンプレートファイルで、今後の DOC または DOCX ファイル生成のために事前に書式設定された設定を持ちます。このファイル形式の詳細は[here](https://wiki.fileformat.com/word-processing/dot/)をご覧ください。 |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | DOTM 拡張子のファイルは、Microsoft Word 2007 以降で作成されたテンプレートファイルを表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/word-processing/dotm/)をご覧ください。 |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | DOTX 拡張子のファイルは、Microsoft Word が作成したテンプレートファイルで、今後の DOCX ファイル生成のために事前に書式設定された設定を持ちます。このファイル形式の詳細は[here](https://wiki.fileformat.com/word-processing/dotx/)をご覧ください。 |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | EML ファイル形式は、Outlook やその他の関連アプリケーションで保存されたメールメッセージを表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/email/eml/)をご覧ください。 |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | EMLX ファイル形式は Apple によって実装・開発されました。Apple Mail アプリケーションはメールのエクスポートに EMLX ファイル形式を使用します。このファイル形式の詳細は[here](https://wiki.fileformat.com/email/emlx/)をご覧ください。 |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | Office Open XML WordprocessingML は、ZIP パッケージではなくフラットな XML ファイル（.xml）として保存されます。このファイル形式の詳細は[here](https://en.wikipedia.org/wiki/Office_Open_XML)をご覧ください。 |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | Office Open XML WordprocessingML マクロ有効ドキュメントは、ZIP パッケージではなくフラットな XML ファイル（.xml）として保存されます。このファイル形式の詳細は[here](https://en.wikipedia.org/wiki/Office_Open_XML)をご覧ください。 |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | Office Open XML WordprocessingML テンプレート（マクロなし）は、ZIP パッケージではなくフラットな XML ファイル（.xml）として保存されます。このファイル形式の詳細は[here](https://en.wikipedia.org/wiki/Office_Open_XML)をご覧ください。 |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | Office Open XML WordprocessingML マクロ有効テンプレートは、ZIP パッケージではなくフラットな XML ファイル（.xml）として保存されます。このファイル形式の詳細は[here](https://en.wikipedia.org/wiki/Office_Open_XML)をご覧ください。 |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | GIF（Graphics Interchange Format）は、高度に圧縮された画像形式の一種です。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/gif/)をご覧ください。 |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | JPEG は、非可逆圧縮方式で保存される画像形式の一種です。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/jpeg/)をご覧ください。 |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | JPEG 2000（JPF）は、画像符号化システムであり、最先端の画像圧縮規格です。ウェーブレット技術を使用して設計された JPEG 2000 は、任意の品質でロスレスコンテンツを一度に符号化できます。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/jp2/)をご覧ください。 |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | JPEG は、非可逆圧縮方式で保存される画像形式の一種です。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/jpeg/)をご覧ください。 |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | JPEG 2000（JPM）は、画像符号化システムであり、最先端の画像圧縮規格です。ウェーブレット技術を使用して設計された JPEG 2000 は、任意の品質でロスレスコンテンツを一度に符号化できます。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/jp2/)をご覧ください。 |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | JPEG 2000（JPX）は、画像符号化システムであり、最先端の画像圧縮規格です。ウェーブレット技術を使用して設計された JPEG 2000 は、任意の品質でロスレスコンテンツを一度に符号化できます。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/jp2/)をご覧ください。 |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | MSG は Microsoft Outlook と Exchange がメールメッセージ、連絡先、予定、またはその他のタスクを保存するために使用するファイル形式です。このファイル形式の詳細は [here](https://wiki.fileformat.com/email/msg/) で確認できます。 |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | ODT ファイルは OpenDocument テキストファイル形式に基づくワードプロセッサアプリケーションで作成される文書の一種です。これらは無料の OpenOffice Writer などのワードプロセッサアプリケーションで作成され、テキスト、画像、オブジェクト、スタイルなどのコンテンツを保持できます。このファイル形式の詳細は [here](https://wiki.fileformat.com/word-processing/odt/) で確認できます。 |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | .OFT 拡張子のファイルは Microsoft Outlook を使用して作成されるメッセージテンプレートファイルを表します。このファイル形式の詳細は [here](https://wiki.fileformat.com/email/oft/) で確認できます。 |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | Office Open XML ファイル (.ooxml)。 |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | Portable Document Format (PDF) は 1990 年代に Adobe が作成した文書の一種です。このファイル形式の目的は、アプリケーションソフトウェア、ハードウェア、オペレーティングシステムに依存しない形式で文書やその他の参照資料を表現する標準を導入することでした。このファイル形式の詳細は [here](https://wiki.fileformat.com/view/pdf/) で確認できます。 |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | PNG（Portable Network Graphics）は、ロスレス圧縮を使用するラスタ画像ファイル形式の一種です。このファイル形式の詳細は [here](https://wiki.fileformat.com/image/png/) で確認できます。 |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | POTM 拡張子のファイルはマクロに対応した Microsoft PowerPoint テンプレートファイルです。POTM ファイルは PowerPoint 2007 以降で作成され、今後のプレゼンテーションファイル作成に使用できる既定設定が含まれています。このファイル形式の詳細は [here](https://wiki.fileformat.com/presentation/potm/) で確認できます。 |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | .POTX 拡張子のファイルは Microsoft PowerPoint 2007 以降で作成された PowerPoint テンプレートプレゼンテーションを表します。このファイル形式の詳細は [here](https://wiki.fileformat.com/presentation/potx/) で確認できます。 |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | PPS（PowerPoint Slide Show）ファイルはスライドショー用に Microsoft PowerPoint を使用して作成されます。PPS ファイルの読み取りと作成は Microsoft PowerPoint 97-2003 でサポートされています。このファイル形式の詳細は [here](https://wiki.fileformat.com/presentation/pps/) で確認できます。 |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | PPSM 拡張子のファイルは Microsoft PowerPoint 2007 以降で作成されたマクロ対応スライドショーファイル形式を表します。このファイル形式の詳細は [here](https://wiki.fileformat.com/presentation/ppsm/) で確認できます。 |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | PPSX（PowerPoint Slide Show）ファイルはスライドショー目的で Microsoft PowerPoint 2007 以降を使用して作成されます。このファイル形式の詳細は [here](https://wiki.fileformat.com/presentation/ppsx/) で確認できます。 |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | PPT 拡張子のファイルはスライドショーとして表示されるスライドのコレクションで構成された PowerPoint ファイルを表します。これは Microsoft PowerPoint 97-2003 が使用するバイナリファイル形式です。このファイル形式の詳細は [here](https://wiki.fileformat.com/presentation/ppt/) で確認できます。 |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | PPTM 拡張子のファイルは Microsoft PowerPoint 2007 以降のバージョンで作成されたマクロ対応プレゼンテーションファイルです。このファイル形式の詳細は [here](https://wiki.fileformat.com/presentation/pptm/) で確認できます。 |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | PPTX 拡張子のファイルは一般的な Microsoft PowerPoint アプリケーションで作成されたプレゼンテーションファイルです。以前のバイナリ形式の PPT と異なり、PPTX 形式は Microsoft PowerPoint の Open XML プレゼンテーションファイル形式に基づいています。このファイル形式の詳細は [here](https://wiki.fileformat.com/presentation/pptx/) で確認できます。 |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | Microsoft が導入・文書化したリッチテキスト形式（RTF）は、アプリケーション内で使用するための書式付きテキストとグラフィックをエンコードする方法を表します。この形式は他の Microsoft 製品とのクロスプラットフォーム文書交換を容易にし、相互運用性の目的を果たします。このファイル形式の詳細は [here](https://wiki.fileformat.com/word-processing/rtf/) で確認できます。 |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | TIFF（または TIF）は Tagged Image File Format の略で、このファイル形式標準に準拠したさまざまなデバイスで使用されるラスタ画像を表します。このファイル形式の詳細は [here](https://wiki.fileformat.com/image/tiff/) で確認できます。 |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | TIFF（または TIF）は Tagged Image File Format の略で、このファイル形式標準に準拠したさまざまなデバイスで使用されるラスタ画像を表します。このファイル形式の詳細は [here](https://wiki.fileformat.com/image/tiff/) で確認できます。 |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | 不明なファイルタイプを表します。 |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | VDW は Web 図面のレンダリングに必要なストリームとストレージを指定する Visio Graphics Service ファイル形式です。このファイル形式の詳細は [here](https://wiki.fileformat.com/web/vdw/) で確認できます。 |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | Microsoft Visio で作成された図面やチャートを XML 形式で保存したものは .VDX 拡張子を持ちます。このファイル形式の詳細は [here](https://wiki.fileformat.com/image/vdx/) で確認できます。 |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | VSD ファイルは Microsoft Visio アプリケーションで作成された、さまざまなグラフィックオブジェクトとそれらの相互接続を表す図面です。このファイル形式の詳細は [here](https://wiki.fileformat.com/image/vsd/) で確認できます。 |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | VSDM 拡張子のファイルはマクロに対応した Microsoft Visio アプリケーションで作成された図面ファイルです。このファイル形式の詳細は [here](https://wiki.fileformat.com/image/vsdm/) で確認できます。 |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | .VSDX 拡張子のファイルは Microsoft Office 2013 以降で導入された Microsoft Visio ファイル形式を表します。このファイル形式の詳細は [here](https://wiki.fileformat.com/image/vsdx/) で確認できます。 |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | VSS は Microsoft Visio 2007 以前で作成されたステンシルファイルです。ステンシルファイルは .VSD Visio 図面に含めることができる描画オブジェクトを提供します。このファイル形式の詳細は [here](https://wiki.fileformat.com/image/vss/) で確認できます。 |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | .VSSM 拡張子のファイルはマクロに対応した Microsoft Visio ステンシルファイルです。このファイル形式の詳細は [here](https://wiki.fileformat.com/image/vssm/) で確認できます。 |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | .VSSX 拡張子のファイルは Microsoft Visio 2013 以降で作成された描画ステンシルです。このファイル形式の詳細は [here](https://wiki.fileformat.com/image/vssx/) で確認できます。 |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | VST 拡張子のファイルは、Microsoft Visio で作成されたベクター画像ファイルで、さらにファイルを作成するためのテンプレートとして機能します。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/vst/)でご覧ください。 |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | VSTM 拡張子のファイルは、Microsoft Visio で作成されたテンプレートファイルで、マクロをサポートします。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/vstm/)でご覧ください。 |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | VSTX 拡張子のファイルは、Microsoft Visio 2013 以降で作成された図面テンプレートファイルです。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/vstx/)でご覧ください。 |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | .VSX 拡張子のファイルは、Microsoft Visio で図やシェイプからなるステンシルを指し、ダイアグラム作成に使用されます。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/vsx/)でご覧ください。 |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | VTX 拡張子のファイルは、Microsoft Visio の図面テンプレートで、XML ファイル形式でディスクに保存されます。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/vtx/)でご覧ください。 |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | WebP は Google が導入した、ロスレスとロッシー圧縮に基づく最新のラスタ Web 画像ファイル形式です。画像品質を保ちつつ、画像サイズを大幅に削減します。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/webp/)でご覧ください。 |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | XLS 拡張子のファイルは Excel バイナリ ファイル形式を表します。このようなファイルは Microsoft Excel のほか、OpenOffice Calc や Apple Numbers などの類似スプレッドシートプログラムでも作成できます。このファイル形式の詳細は[here](https://wiki.fileformat.com/specification/spreadsheet/xls/)でご覧ください。 |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | XLSB ファイル形式は Excel バイナリ ファイル形式を指定し、Excel ブックの内容を示すレコードと構造のコレクションです。このファイル形式の詳細は[here](https://wiki.fileformat.com/specification/spreadsheet/xlsb/)でご覧ください。 |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | XLSM 拡張子のファイルはマクロをサポートするスプレッドシートファイルの一種です。このファイル形式の詳細は[here](https://wiki.fileformat.com/specification/spreadsheet/xlsm/)でご覧ください。 |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | XLSX は Microsoft Excel ドキュメントのよく知られた形式で、Microsoft Office 2007 のリリースとともに Microsoft によって導入されました。このファイル形式の詳細は[here](https://wiki.fileformat.com/specification/spreadsheet/xlsx/)でご覧ください。 |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | .XLT 拡張子のファイルは、Microsoft Office スイートの一部であるスプレッドシートアプリケーション Microsoft Excel で作成されたテンプレートファイルです。このファイル形式の詳細は[here](https://wiki.fileformat.com/specification/spreadsheet/xlt/)でご覧ください。 |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | XLTM 拡張子は、Microsoft Excel によってマクロ対応テンプレートファイルとして生成されるファイルを表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/specification/spreadsheet/xltm/)でご覧ください。 |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | XLTX 拡張子のファイルは、Office OpenXML ファイル形式仕様に基づく Microsoft Excel テンプレートファイルを表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/specification/spreadsheet/xltx/)でご覧ください。 |

### 備考

このクラスは **GroupDocs.Watermark** がサポートするすべてのファイルタイプの一覧を取得するメソッドを提供します。**詳細を見る**

* [Supported Document Formats](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [Get supported file formats](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### 関連項目

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
