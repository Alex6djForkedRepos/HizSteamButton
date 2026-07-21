# ![HizSearch icon](https://hizsearch.pages.dev/favicon-32x32.png) HizSearch Steam Button

Search for any Steam game on HizSearch ([a game search engine](http://hizsearch.pages.dev/)) with just one click. It works on both the Steam Store and SteamDB.

## Installation methods

### Steam Client Browser
Since Steam runs on Chromium, you can install Chrome extensions directly inside it.

1) [Download the latest extension zip](https://github.com/hiz0147/HizSteamButton/releases/latest/download/hizsteambutton.zip) and extract it.
2) While browsing Steam, middle-click any game to open a new tab.
3) In the address bar, enter `chrome://extensions` and press Enter.
4) Turn on **Developer mode** (top-right toggle).
5) Drag and drop the extracted folder onto the extensions page.
6) Click **Details** → **Extension options** to configure position, icon and more.
7) The button will appear on Steam Store and SteamDB app pages.

> [!IMPORTANT]  
> If you're having trouble dragging and dropping the folder in step 5, you can follow these steps provided by [@thesaguaro](https://github.com/hiz0147/HizSteamButton/issues/4#issuecomment-5028797121) to fix the issue:
> 
> After middle clicking random game and opening the _chrome://extensions_ tab in _steam_ browser, click the _Chrome Web Store_ button (its on the left under the _Keyboard Shortcuts_). Then download and install (_Add to Chrome_ button) any extension (i recommend installing _uBlock Origin Lite_). Click save in the file manager pop-up (if it asks you to). You might now notice that a new window (tab) opened that looks exactly like the default new chromium tab, where it will say that the extension you just downloaded has been added to chromium. Now, in that new tab, go to _chrome://extensions_ and you should be able to drag and drop the zip or crx file that will install the plugin.

> [!NOTE]
> If you're having issues with the Cloudflare Challenge that aren't resolved by refreshing the page, try closing Steam completely and reopening it.

---

### Chrome / Edge / Brave / or any Chromium
1) [Download the latest extension zip](https://github.com/hiz0147/HizSteamButton/releases/latest/download/hizsteambutton.zip) and extract it.
2) Open `chrome://extensions`.
3) Turn on **Developer mode** (top-right toggle).
4) Click **Load unpacked** and select the extracted folder.
5) The button will appear on Steam Store and SteamDB app pages.
6) Click the extension icon in your toolbar to configure position, icon and behavior.

---

### Firefox (add-on store)
[HizSearch Add-on](https://addons.mozilla.org/en-US/firefox/addon/hizsearch-steam-button/)

---

### User script
1) Install [Violentmonkey](https://violentmonkey.github.io/), [ScriptCat](https://scriptcat.org/) or [Tampermonkey](https://www.tampermonkey.net/).
2) Click [this link](https://raw.githubusercontent.com/hiz0147/HizSteamButton/main/userscript/hizsearch-steam-button.user.js) — the extension will ask you to install it. Enable auto-update if prompted.
3) To configure the button, right-click the user script manager icon and → **Configure HizSearch**. A settings modal lets you choose position, icon visibility and new-tab behavior.

## Preview

![Preview](https://i.ibb.co/dsfS3s46/image.png)
<br>
![Preview](https://i.ibb.co/yByTKQDW/b.png)

## Contributing

Suggestions and contributions are welcome. Feel free to open an [issue](https://github.com/hiz0147/HizSteamButton/issues) or submit a [pull request](https://github.com/hiz0147/HizSteamButton/pulls).
