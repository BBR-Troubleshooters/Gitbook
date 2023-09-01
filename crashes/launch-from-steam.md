---
description: >-
  Game crashes instantly if launched from Steam, but runs fine if launched from
  executables in installed files.
cover: ../.gitbook/assets/launchfromsteam.png
coverY: 0
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

# Launch from Steam

If you experience this problem:

1. Navigate to launch options by right clicking the game and pressing "Properties...".

<figure><img src="../.gitbook/assets/properties.png" alt=""><figcaption></figcaption></figure>

2. Paste this in your launch options (replace your game path if it's different):\
   `"C:\Program Files (x86)\Steam\steamapps\common\BattleBit Remastered\EasyAntiCheat.exe" %command%`

<figure><img src="../.gitbook/assets/launchoptionsfix.png" alt=""><figcaption><p>It should look like this. If your game path differs - replace it with your actual game path.</p></figcaption></figure>
