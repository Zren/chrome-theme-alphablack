Default theme but with a pure black titlebar without any tinting on inactive windows that makes it gray.

# Install

1. Download this repo as a zip.  
   https://github.com/Zren/chrome-theme-alphablack/archive/master.zip

2. Unzip the folder somewhere permanent (where you won't move/delete it).

3. Go to `chrome://extensions/` and toggle Developer Mode.

4. Click on the "Load unpacked" button and select the `chrome-theme-alphablack` folder.


# Configuration

To change the titlebar color, edit the `manifest.json` and modify the following lines. "Load" the theme to apply the changes.

* Black

      "frame": [ 0, 0, 0 ],
      "frame_inactive": [ 0, 0, 0 ],

* Dark Green

      "frame": [ 0, 32, 0 ],
      "frame_inactive": [ 0, 32, 0 ],

* Dark Red

      "frame": [ 32, 0, 0 ],
      "frame_inactive": [ 32, 0, 0 ],

* Dark Blue

      "frame": [ 0, 0, 32 ],
      "frame_inactive": [ 0, 0, 32 ],

* Dark Teal

      "frame": [ 0, 32, 32 ],
      "frame_inactive": [ 0, 32, 32 ],

* Dark Purple

      "frame": [ 32, 0, 32 ],
      "frame_inactive": [ 32, 0, 32 ],

# Chrome Theme Documentation

* https://developer.chrome.com/extensions/themes
* Colors: kColorTable in [browser_theme_pack.cc](https://src.chromium.org/viewvc/chrome/trunk/src/chrome/browser/themes/browser_theme_pack.cc#l288)
* Tints: kTintTable in [browser_theme_pack.cc](https://src.chromium.org/viewvc/chrome/trunk/src/chrome/browser/themes/browser_theme_pack.cc#l275)

