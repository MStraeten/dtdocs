---
title: scale pixels
id: scale-pixels
weight: 10
applicable-version: 3.2.1
tags:
working-color-space: RGB
view: darkroom
masking: false
---

Some cameras (such as the Nikon D1X) have rectangular instead of the usual square sensor cells. Without correction this would lead to distorted images. This module applies the required scaling.

darktable detects images that need correction using their Exif data and automatically activates this module where required.

For other images, the module can also be used to de-squeeze the image when using anamorphic lenses.

---

# module controls

pixel aspect ratio
: Aspect ratio of the pixels. Values greater than 1 stretch the image horizontally, values less than 1 stretch the image vertically.
