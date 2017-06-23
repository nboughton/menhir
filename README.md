# Menhir
A minimalist Hugo theme built using the Bulma css framework.

A simple theme to use. Sections are defined directly below content/ and navigation is meant to be intuitive.
By default the theme assumes you are posting content under content/blog but you can change which sections are
listed on the front page and recent articles widget by editing the list post_sections in the config.toml.

The theme is also highly themable. Just set the bulma_theme variable in your config.toml to an existing theme
from [Bulma Swatch](https://jenil.github.io/bulmaswatch/).

You can add custom css or js by placing your files in /static/css or /static/js in your project folder and
listing them in the custom\_css/custom\_js lists in your config.toml. Just list each file by its name 
(excluding /js or /css) and it will be sourced in the template after the theme's core files. 

You can also load custom css or js on a per page basis by putting custom\_css or custom\_js lists in the headmatter 
of an individual page.
