# WPC-Custom-Post-Type-Admin-Taxonomy-Filtering

A non-invasive, lightweight WordPress plugin adding custom post type admin taxonomy filtering support. [WPC-Custom-Post-Type-Admin-Taxonomy-Filtering](https://github.com/amarinediary/WPC-Custom-Post-Type-Admin-Taxonomy-Filtering) is a plug-and-play plugin with no required configuration.

||Version|
|- |- |
|Requires at least WordPress:|`4.8.0`|
|Requires PHP:|`4.0`|
|Tested up to WordPress:|`5.7.1`|

## Filter visibility behavior

Default behavior inherited from the [`register_taxonomy`](https://developer.wordpress.org/reference/functions/register_taxonomy/#parameters) function argument, `show_admin_column`.

## Filter labelling

Filter's labels are inherited from the associated taxonomy labels `filter_by_item` and `all_items`, usually defined from the [`register_taxonomy`](https://developer.wordpress.org/reference/functions/register_taxonomy/#parameters) function arguments.

## Hierarchical display

The main differences between [WPC-Custom-Post-Type-Admin-Taxonomy-Filtering](https://github.com/amarinediary/WPC-Custom-Post-Type-Admin-Taxonomy-Filtering) plugin and other pllugins are the way we handle terms display. Terms within a `<select>` tag are visually-hierarchically displayed for a better user experience.

<img src="https://user-images.githubusercontent.com/7512732/117062756-1fddf580-ad24-11eb-8617-54eea7dfc9f1.jpg" style="max-width:500px;">
