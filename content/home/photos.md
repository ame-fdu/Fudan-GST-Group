---
widget: slider
active: true
headless: true  # This file represents a page section.
weight: 70
# ... Put Your Section Options Here (section position etc.) ...

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: false

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: 400px

item:
  - title: 测试1
    content: ''
    # Choose `center`, `left`, or `right` alignment.

    align: center
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    overlay_color: '#666'  # An HTML color value.
    overlay_img: albums/photos/coders.jpg  # Image path relative to your `assets/media/` folder
    overlay_filter: 1  # Darken the image. Value in range 0-1.


  - title: 测试2
    content: '放一些其他的东西😄'
    align: center
    overlay_color: '#555'
    overlay_img: albums/photos/coders.jpg
    overlay_filter: 0.5

  - title: 测试3
    content: 'I am right aligned 😄'
    align: center
    overlay_color: '#333'
    overlay_img: albums/photos/coders.jpg
    overlay_filter: 0.5
---
