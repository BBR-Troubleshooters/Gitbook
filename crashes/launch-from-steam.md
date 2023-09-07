---
description: >-
  Игра сразу крашится если запускается из Steam, но при этом работает нормально
  если запуск происходит от исполняемых файлов в корне игры.
cover: ../.gitbook/assets/launchfromsteam.png
coverY: -10
layout:
  cover:
    visible: true
    size: hero
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Запуск из Steam

Если вы испытываете эту проблему:

1. Перейдите к параметрам запуска посредством нажатия ПКМ по игре, затем "Свойства...".

<figure><img src="../.gitbook/assets/properties.png" alt=""><figcaption></figcaption></figure>

2. Вставьте эту строку в ваши параметры запуска (замените путь к корню игры если он отличается):\
   `"C:\Program Files (x86)\Steam\steamapps\common\BattleBit Remastered\EasyAntiCheat.exe" %command%`

<figure><img src="../.gitbook/assets/launchoptionsfix.png" alt=""><figcaption><p>Должно выглядеть как на скрине. Если путь к корню игры отличается (игра установлена не на диск С) - замените его на актуальный.</p></figcaption></figure>
