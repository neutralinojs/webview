# webview

A modified version of [webview](https://github.com/webview/webview) for Neutralinojs.

## Modifications

- Event handlers support Eg: `webview.setonCloseHandler(onClose);`.
- Allow sending process exit code with the `terminate` class method.
- Prevent closing window by default, and let `onClose` handler close the window explicitly. 
- Automatically start dev tools on Windows (Edge Chromium) if `debug == true`.
- Disable dev tools and inspect element context menu item on Windows if `debug == false`.
- Extend `set_size()` method to accept `minWidth`, `minHeight`, `maxWidth`, `maxHeight`, and `resizable`.
- Integrate [zserge/tray](https://github.com/zserge/tray)

