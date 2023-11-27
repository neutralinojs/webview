# webview

A modified version of [webview](https://github.com/webview/webview) for Neutralinojs.

## Modifications

- Window event handlers via `webview.setEventHandler(windowStateChange);`.
- Allow sending process exit code with the `terminate` class method.
- Prevent closing window by default, and let `windowStateChange` handler close the window explicitly. 
- Automatically start dev tools on Windows (Edge Chromium) if `debug == true`.
- Disable dev tools and inspect element context menu item on Windows if `debug == false`.
- Extend `set_size()` method to accept `minWidth`, `minHeight`, `maxWidth`, `maxHeight`, and `resizable`.
- Integrate [neutralinojs/tray](https://github.com/neutralinojs/tray)
- Apply dark/light themese from system preferences on Windows.
- Supports custom user agent strings via the `extend_user_agent` method.

