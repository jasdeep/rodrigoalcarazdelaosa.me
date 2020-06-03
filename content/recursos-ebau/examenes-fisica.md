+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 2  # Order that this section will appear.

title = "📝 Exámenes de Física resueltos"
subtitle = "Cantabria, desde el 2009 hasta el 2019, cortesía del **Profesor Enrique Ortega González** del IES José del Campo de Ampuero"

[content]
  # Page type to display. E.g. project.
  page_type = "examenes-EBAU-fisica"
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0
  
  [[content.filter_button]]
    name = "Todos"
    tag = "*"	
	
  [[content.filter_button]]
    name = "2009"
    tag = "2009"
	
  [[content.filter_button]]
    name = "2010"
    tag = "2010"
	
  [[content.filter_button]]
    name = "2011"
    tag = "2011"
	
  [[content.filter_button]]
    name = "2012"
    tag = "2012"
	
  [[content.filter_button]]
    name = "2013"
    tag = "2013"
	
  [[content.filter_button]]
    name = "2014"
    tag = "2014"
	
  [[content.filter_button]]
    name = "2015"
    tag = "2015"
	
  [[content.filter_button]]
    name = "2016"
    tag = "2016"
	
  [[content.filter_button]]
    name = "2017"
    tag = "2017"
	
  [[content.filter_button]]
    name = "2018"
    tag = "2018"
	
  [[content.filter_button]]
    name = "2019"
    tag = "2019"									

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 2

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "#ffffff"
  # gradient_end = "#dddddd"
  
  # Background image.
  image = "ebau.png"  # Name of image in `static/img/`.
  # image_darken = 0.5  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  image_position = "center"  # Options include `left`, `center` (default), or `right`.
  image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = false
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

{{% alert gdrive %}}
Accede [aquí](https://drive.google.com/drive/u/0/folders/0B6t6-aLmKtoLaEZ1Q2UzVXpxUlk) a todos los enunciados de Cantabria desde 1995 hasta 2019, cortesía de [**EL FÍSICO LOCO**](http://elfisicoloco.blogspot.com/p/pau-cantabria-new.html).
{{% /alert %}}