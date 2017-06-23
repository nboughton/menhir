# Menhir
A minimalist Hugo theme built using the Bulma css framework.

A simple theme to use. Sections are defined directly below content/ and navigation is meant to be intuitive.
The theme is also highly themable. Just set the bulma_theme variable in your config.toml to an existing theme
from [Bulma Swatch](https://jenil.github.io/bulmaswatch/).

You can add custom css or js by placing your files in /static/css or /static/js in your project folder and
listing them in the custom\_css/custom\_js lists in your config.toml. Just list each file by its name and it will
be sourced in the template after the theme's core files. 

You can also load custom css or js on a per page basis by putting custom\_css or custom\_js lists in the headmatter 
of an individual page.
