+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 65  # Order that this section will appear.

title = "Projects"
subtitle = ""

[content]
  # Page type to display. E.g. project.
  page_type = "project"

  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.

  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0

  [[content.filter_button]]
    name = "All"
    tag = "*"

  [[content.filter_button]]
    name = "Industry"
    tag = "Industry"

  [[content.filter_button]]
    name = "PhD Research"
    tag = "PhD Research"

  [[content.filter_button]]
    name = "Course Projects"
    tag = "Course Projects"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2" # 1 column looks weird since projects title doesn't align with publications

  # Toggle between the various page layout types.
  #   1 = List. doesn't even show the images. very boring!
  #   2 = Compact. summaries make sense here.
  #   3 = Card. small pictures. maybe not my favorite. getting kinda cramped. summaries would be a lot here.
  #   5 = Showcase. kinda too big for me. flip rows if so though.
  view = 2 # not 3, 2, 1.

  # For Showcase view, flip alternate rows?
  flip_alt_rows = true

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"

  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"

  # Background image.
  # image = "background.jpg"  # Name of image in `static/media/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true

[advanced]
 # Custom CSS.
 css_style = ""

 # CSS class.
 css_class = ""
+++
