# webview

A modified version of [webview](https://github.com/webview/webview) for Neutralinojs.

## Modifications

- Exit process with the window close event.
- Automatically start dev tools on Windows if `debug == true`.
- Disable dev tools and inspect element context menu item on Windows if `debug == false`.
- Extend `set_size()` method to accept `minWidth`, `minHeight`, `maxWidth`, `maxHeight`, and `resizable`.
- Integrate [zserge/tray](https://github.com/zserge/tray)

