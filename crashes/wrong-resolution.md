---
description: Crash caused by wrong resolution setting.
---

# Wrong resolution

This page is for users that have manually adjusted their resolution to a value that has caused BattleBit to constantly crash upon loading the game. Here's how to fix it:

1. Open the AppData folder.

<figure><img src="../.gitbook/assets/run_menu_appdata.png" alt=""><figcaption><p>Press Win+R, type <code>%appdata%</code> and press Enter.</p></figcaption></figure>

2. Navigate to `BattleBitConfig.ini` file.

<figure><img src="../.gitbook/assets/appdata_folder_config_file.png" alt=""><figcaption><p>AppData/Roaming folder</p></figcaption></figure>

3. Set `customresolution` to true and `customscreenresolution` to match your monitor settings:

<figure><img src="../.gitbook/assets/config_file.png" alt=""><figcaption><p>BattleBit config file</p></figcaption></figure>

4. Save your changes and close config file.
