## How to use this theme

This theme is used remotely via the `remote-theme: username/just-the-docs` statement in `_config.yml` of the website.

Below I highlight shortly the changes I've made:
### Navigation: custom colors
Now you can use `nav_color: ` statement in front matter to specify the color.
Available colors: 
- yellow 
- light-green
- green
- blue
- dark blue
- purple

(Corresponding code for reference below)
```
// Category heading colors
$color-nav-light-green: #46b4a5;
$color-nav-blue: #00aed9;
$color-nav-green: #00b45a;
$color-nav-yellow: #f5d503;
$color-nav-dark-blue: #226CC3;
$color-nav-purple: #5f5bb6;
```

In the front matter use it like this: ```nav_color: light-blue```.

## Original license

The theme is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
