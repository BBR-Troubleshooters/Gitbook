---
description: >-
  ACCESS_VIOLATION - процесс попытался произвести запись в зону памяти которая
  недоступна/запись в ней запрещена.
---

# Ошибка при запуске приложения (0xc0000005).

<figure><img src="../.gitbook/assets/0xc0000005.jpg" alt=""><figcaption></figcaption></figure>

1. Если вы используете сторонний антивирус - убедитесь, что вы добавили EAC в его исключения. Если это не поможет - попробуйте удалить антивирус (особенно trend micro), чтобы проверить, уйдет ли проблема.
2. Попробуйте запустить `BattleBitEAC.exe` или `EasyAntiCheat.exe` (расположены в папке с игрой) от имени администратора.

<figure><img src="../.gitbook/assets/browse.png" alt="" width="374"><figcaption><p>Нажмите ПКМ по игре, затем "Управление" и "Просмотреть локальные файлы".</p></figcaption></figure>

<figure><img src="../.gitbook/assets/runasadmin.png" alt="" width="417"><figcaption><p>Нажмите ПКМ по исполняемому файлу, затем "Запуск от имени администратора".</p></figcaption></figure>

3. Запустите [EAC Fix batch](https://github.com/livingflore/BattleBitEACFix/releases) (файл BattleBitEACFix.bat).
4. Выключите любой оверклокинг (разгон) / софт для него.
5. Проверьте целостность файлов игры.

<figure><img src="../.gitbook/assets/BBR_Validation.gif" alt=""><figcaption><p>Нажмите ПКМ по игре, затем "Свойства...", перейдите во вкладку "Установленные файлы" и нажмите "Проверить целостность файлов игры".</p></figcaption></figure>

6. Переустановите игру на другой диск / раздел.
