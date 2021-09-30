---
widget: slider
active: true
headless: true  # This file represents a page section.
weight: 10
# ... Put Your Section Options Here (section position etc.) ...

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: false

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: 400px

item:
  - title: Hello!
    content: 'This is Fudan GST Group<br/>这是我们小组的自我介绍,左上角可以查看具体分块
    <br />
    <br />
    <br />'
    # Choose `center`, `left`, or `right` alignment.

    align: center
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    overlay_color: '#666'  # An HTML color value.
    overlay_img: coders.jpg  # Image path relative to your `assets/media/` folder
    overlay_filter: 1  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: Official Website
    cta_url: 'https://www.fudan.edu.cn/'
    cta_icon_pack: fas
    cta_icon: graduation-cap

  - title: Left
    content: '放一些其他的东西😄'
    align: left
    overlay_color: '#555'
    overlay_img: ''
    overlay_filter: 0.5
  - title: Right
    content: 'I am right aligned 😄'
    align: right
    overlay_color: '#333'
    overlay_img: ''
    overlay_filter: 0.5
---
