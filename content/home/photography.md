+++
# Photography Gallery section using the Blank widget and Gallery element (shortcode).
widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 67  # Order that this section will appear in (after projects)

title = "Photography"
subtitle = "A collection of my favorite shots"

# Gallery items - add your photos here with captions
[[gallery_item]]
album = "photography"
image = "IMG_2743-Enhanced-NR-HDR-Edit-Edit-Edit-Edit.jpg"
caption = "Golden hour at the mountains"

[[gallery_item]]
image = "IMG_3203-Enhanced-NR-HDR.jpg"
caption = "City lights reflection"

[[gallery_item]]
album = "photography"
image = "IMG_3671-Enhanced-NR.jpg"
caption = "Morning dew on autumn leaves"

# Add more photos by copying the [[gallery_item]] block above
# [[gallery_item]]
# album = "photography"
# image = "your-photo-name.jpg"
# caption = "Your photo description"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  # Uncomment (by removing `#`) an option to apply it.
  # Choose a light or dark text color by setting `text_color_light`.
  # Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DarkGreen"
  # gradient_end = "ForestGreen"
  
  # Background image.
  # image = "image.jpg"  # Name of image in `static/media/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = false

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]
+++

{{< gallery album="photography" >}}
