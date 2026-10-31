---
title: "إضافة علامات مائية متكررة"
linkTitle: "Repeated watermarks"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "أضف علامات مائية نصية أو صورة متكررة (مبلطة) مع الفواصل، والدوران، والأنماط باستخدام GroupDocs.Watermark للبايثون عبر .NET."
type: docs
url: /ar/python-net/guides/adding-repeated-watermarks/
is_root: false
weight: 70
---


تتيح لك العلامات المائية المتكررة (المبلطة) تغطية الصفحات بالكامل بنمط من النص أو الصور. يمكنك التحكم في الفواصل، والدوران، والإزاحات، واختيار قوالب تبليط مختلفة عن طريق ضبط `tile_options` على العلامة المائية.

## Add a repeated text watermark

المثال أدناه يبلط علامة مائية نصية مائلة عبر الصفحة بأكملها. يتم التعبير عن `line_spacing` و `watermark_spacing` كنسبة مئوية من الصفحة، ويختار `tile_type` قالب التبليط.

{{< tabs "code-example-adding-repeated-watermarks">}}
{{< tab "add_repeated_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import (
    TextWatermark, Font, Color, TextAlignment,
    TileOptions, TileType, MeasureValue, TileMeasureType,
)

def add_repeated_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
        watermark.foreground_color = Color.gray
        watermark.opacity = 0.3
        watermark.rotate_angle = -45.0
        watermark.text_alignment = TextAlignment.CENTER

        # الفواصل بين الأسطر وبين العلامات المائية المتكررة، كنسبة مئوية من الصفحة
        line_spacing = MeasureValue()
        line_spacing.measure_type = TileMeasureType.PERCENT
        line_spacing.value = 12.0
        watermark_spacing = MeasureValue()
        watermark_spacing.measure_type = TileMeasureType.PERCENT
        watermark_spacing.value = 10.0

        # بلط العلامة المائية عبر الصفحة بأكملها
        tile_options = TileOptions()
        tile_options.tile_type = TileType.ONE_THIRD_OFFSET
        tile_options.line_spacing = line_spacing
        tile_options.watermark_spacing = watermark_spacing
        watermark.tile_options = tile_options

        watermarker.add(watermark)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    add_repeated_watermark()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` هو الملف النموذجي المستخدم في هذا المثال. اضغط [هنا](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/adding-repeated-watermarks/sample.pdf) لتنزيله.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 379 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/adding-repeated-watermarks/add_repeated_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

يمكنك استبدال [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) بـ [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) لتبليط شعار أو ختم عبر الصفحة بنفس الطريقة — اضبط نفس `tile_options` على العلامة المائية للصورة.

**Use case:** Protect sensitive PDFs by overlaying a tiled "Confidential" text across every page, or reinforce branding by repeating a logo in the background.
