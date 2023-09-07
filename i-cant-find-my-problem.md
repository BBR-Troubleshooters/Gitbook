---
cover: .gitbook/assets/general-help.png
coverY: 0
layout:
  cover:
    visible: true
    size: full
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# ❗ Я не могу найти мою проблему

Если вы не можете найти вашу проблему в листе слева или приведенные инструкции вам не помогают, обратитесь в канал [#general-help](https://discord.com/channels/303681520202285057/1023557475242360852) в [BattleBit Discord server](https://discord.com/battlebit) для помощи.\
\
При описании проблемы, пожалуйста, приложите следующую информацию:

1. Скриншот ошибки
2. Файл `service.log`:
   * Windows: `%appdata%\EasyAntiCheat`
   * Linux (Proton): `~/.local/share/Steam/steamapps/compatdata/671860/pfx/drive_c/users/steamuser/AppData/EasyAntiCheat`
3. Файл `loader.log`:
   * Windows: `%appdata%\EasyAntiCheat\43ed9a4620fa486994c0b368cce73b5d\315826d981f4480aa6155e32d71b0d3b`
   * Linux (Proton): `~/.local/share/Steam/steamapps/compatdata/671860/pfx/drive_c/users/steamuser/AppData/EasyAntiCheat/43ed9a4620fa486994c0b368cce73b5d/315826d981f4480aa6155e32d71b0d3b`
4. Файл `player.log`:
   * Windows: `C:\Users\%username%\AppData\LocalLow\BattleBitDevTeam\BattleBit\`
   * Linux (Proton): `~/.local/share/Steam/steamapps/compatdata/671860/pfx/drive_c/users/steamuser/AppData/LocalLow/BattleBitDevTeam/BattleBit`

Чтобы найти файлы, указанные выше:

* Windows - скопируйте необходимый путь, нажмите Win+R, вставьте его и нажмите ОК.
* Linux - используйте терминал или интерфейс проводника чтобы открыть необходимый путь.

{% hint style="info" %}
Пути к файлам на Linux актуальны только в том случае, если вы пользуетесь Proton вместе со Steam, иначе вам необходимо использовать команды по типу `find ~/ -name player.log`, чтобы найти необходимые файлы.
{% endhint %}
