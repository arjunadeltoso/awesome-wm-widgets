# Ram widget

This widget shows the RAM usage. When clicked another widget appears with more detailed information:

![screenshot](./out.gif)

## Customization

It is possible to customize widget by providing a table with all or some of the following config parameters:

| Name | Default | Description |
|---|---|---|
| `color_used` | `beautiful.bg_urgent` | Color for used RAM |
| `color_free` | `beautiful.fg_normal` | Color for free RAM |
| `color_buf`  | `beautiful.border_color_active` | Color for buffers/cache |
| `widget_show_buf`  | `false` | Whether to display buffers/cache separately in the tray widget. If `false`, buffers/cache are considered free RAM. |
| `timeout`    | 1 | How often (in seconds) the widget refreshes |

## Installation

Please refer to the [installation](https://github.com/streetturtle/awesome-wm-widgets#installation) section of the repo.