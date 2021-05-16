---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/getting-started/page-builder/#people
widget: slider
headless: true  # This file represents a page section.
active: true
weight: 11

# ... Put Your Section Options Here (section position etc.) ...

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: 5000

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: ''


item:
  - title: 'Welcome to the Fang Liu group'
    content: 'Department of Chemistry, Stanford University'
    # Choose `center`, `left`, or `right` alignment.
    align: center
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    overlay_color: '#666'  # An HTML color value.
    overlay_img: 'lab-setup.png'  # Image path relative to your `assets/media/` folder
    overlay_filter: 0  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: 'Go to Stanford Chemistry'
    cta_url: 'https://chemistry.stanford.edu/'
    # cta_icon_pack: fas
    # cta_icon: graduation-cap
  - title: 'Material chemistry'
    content: 'We provide high quality cm size single crystal monolayer'
    align: left
    overlay_color: '#555'
    overlay_img: 'material-chemistry.png'
    overlay_filter: 0.5
  - title: 'Physical chemistry'
    content: 'Pump probe laser spectroscopy'
    align: right
    overlay_color: '#333'
    overlay_img: 'physical-chemistry.png'
    overlay_filter: 0
---