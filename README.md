Based on https://academicpages.github.io/ and customized.

Color themes are defined in `_sass/theme` (with dark and light variants). The choice is made in `_config.yml` (field `site_theme`). At the moment only one theme ("aurore") is defined.

Dark variant of the theme is currently default. To change this, modify `_layouts/default`:

```html
<html lang="{{ site.locale | slice: 0,2 }}" class="no-js">  # default is light theme
```

into

```html
<html lang="{{ site.locale | slice: 0,2 }}" class="no-js" data-theme="dark">  # default is dark theme
```



