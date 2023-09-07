---
description: Краш, вызванный неправильным разрешением экрана.
---

# Неправильное разрешение

Если вы изменили разрешение экрана на неправильное и теперь при запуске игры она крашится, сделайте следующее:

1. Откройте папку AppData.

<figure><img src="../.gitbook/assets/run_menu_appdata.png" alt="" width="369"><figcaption><p>Нажмите Win+R, введите <code>%appdata%</code> и нажмите Enter.</p></figcaption></figure>

2. В этой папке найдите файл `BattleBitConfig.ini`.

<figure><img src="../.gitbook/assets/appdata_folder_config_file.png" alt=""><figcaption></figcaption></figure>

3. Задайте `customresolution` значение true и `customscreenresolution` значение необходимого разрешения экрана (как на скриншоте ниже):

<figure><img src="../.gitbook/assets/config_file.png" alt=""><figcaption></figcaption></figure>

4. Сохраните файл, закройте его и запустите игру.
