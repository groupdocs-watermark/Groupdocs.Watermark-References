---
title: ImageInpaintingPossibleWatermark class
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Represents a manually specified image region that should be inpainted (filled using surrounding pixels)."
type: docs
url: /python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/
is_root: false
weight: 110
---


## ImageInpaintingPossibleWatermark class

Represents a manually specified image region that should be inpainted (filled using surrounding pixels).

The ImageInpaintingPossibleWatermark type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/__init__/) | Initializes a new ImageInpaintingPossibleWatermark instance. |

### Properties
| Property | Description |
| :- | :- |
| [method](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/method/) | The inpainting algorithm. Default is `InpaintingMethod.patch_based`. |
| [parent](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/parent/) | The parent of this ImageInpaintingPossibleWatermark. Always returns None because the region is specified manually. |
| [patch_size](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/patch_size/) | The patch size used by the algorithm (odd, 5-11). Default is 7. For `InpaintingMethod.telea` this is used as HalfPatchSize. |
| [polygons](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/polygons/) | The polygonal regions to be inpainted, expressed as a list of polygons in image pixels. |
| [rectangles](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/rectangles/) | The rectangular areas to be inpainted, in image pixels. |
| [formatted_text_fragments](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/formatted_text_fragments/) | The collection of formatted text fragments of this [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (inherited from [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [height](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/height/) | The height of this [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (inherited from [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [image_data](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/image_data/) | The image of this [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/), or `None` if the watermark has no image. (inherited from [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [page_number](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/page_number/) | The page number where the watermark is placed. (inherited from [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [rotate_angle](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/rotate_angle/) | The rotate angle of this [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) in degrees. (inherited from [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [text](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/text/) | The text of this [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (inherited from [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [unit_of_measurement](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/unit_of_measurement/) | The unit of measurement of this [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (inherited from [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [width](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/width/) | The width of this PossibleWatermark. (inherited from [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [x](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/x/) | The x-coordinate of this PossibleWatermark. (inherited from [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [y](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/y/) | The y-coordinate of this [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (inherited from [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |

### See Also
* module [`groupdocs.watermark.search.watermarks`](/watermark/python-net/groupdocs.watermark.search.watermarks/)
