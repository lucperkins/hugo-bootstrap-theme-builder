# Bootstrap Theme Builder for Hugo

This repo houses a theme builder for [Bootstrap](https://getbootstrap.com)

## Running the theme builder

To run this theme builder, make sure that you have [Hugo](https://gohugo.io) installed (version 0.43 or later). Then:

```bash
git clone https://github.com/lucperkins/hugo-bootstrap-theme-builder
cd hugo-bootstrap-theme-builder
hugo server
open http://localhost:1313
```

This will open your browser (you may need to refresh) to the theme builder. Now you can [customize](#customization) the theme however you wish.

## Customization

To build your theme, you can customize the color palette in [`config.yaml`](./config.yaml). You can also modify the Sass file at `assets/sass/theme.sass` to apply any logic you'd like.

## Modules

You can enable and disable Bootstrap modules (`breadcrumb`, `button-group`, etc.) by modifying the list of modules in `config.yaml`.


