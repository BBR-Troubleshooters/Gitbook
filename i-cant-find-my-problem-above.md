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
    visible: false
---

# ❗ Nu îmi pot găsi problema

Dacă nu îți poți găsi problema în lista acestei pagini sau aceste instrucțiuni nu te ajută, mergi la [#general-help](https://discord.com/channels/303681520202285057/1023557475242360852) în [BattleBit Discord server](https://discord.com/battlebit) pentru asistență.\
\
Când ceri ajutor, te rog atașează următoarele informații:

1. Captură de ecran a erorii
2. `service.log`:
   * Windows: `%appdata%\EasyAntiCheat`
   * Linux (Proton): `~/.local/share/Steam/steamapps/compatdata/671860/pfx/drive_c/users/steamuser/AppData/Roaming/EasyAntiCheat`
3. `loader.log`:
   * Windows: `%appdata%\EasyAntiCheat\43ed9a4620fa486994c0b368cce73b5d\315826d981f4480aa6155e32d71b0d3b`
   * Linux (Proton): `~/.local/share/Steam/steamapps/compatdata/671860/pfx/drive_c/users/steamuser/AppData/Roaming/EasyAntiCheat/43ed9a4620fa486994c0b368cce73b5d/315826d981f4480aa6155e32d71b0d3b`
4. `player.log`:
   * Windows: `C:\Users\%username%\AppData\LocalLow\BattleBitDevTeam\BattleBit\`
   * Linux (Proton): `~/.local/share/Steam/steamapps/compatdata/671860/pfx/drive_c/users/steamuser/AppData/LocalLow/BattleBitDevTeam/BattleBit`

Pentru a naviga spre folder-ele cerute:

* În Windows, apasă Win+R și lipește drumul necesar pentru a accesa folder-ul
* În Linux, folosește terminal-ul sau un explorator de fișiere GUI pentru a naviga spre drumul specific.

{% hint style="info" %}
Drumurile Linux sunt acolo doar dacă folosești Proton cu Steam, altfel poți folosi o comandă precum `find ~/ -name player.log` etc. pentru a găsi fișierul.
{% endhint %}
