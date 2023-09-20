---
description: >-
  Jocul dă crash instant dacă este deschis din Steam, dar merge bine dacă este
  deschis din executabile din fișierele instalate.
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

# Pornire din Steam

Dacă întâmpini această problemă:

1. Navighează la "Launch options" apăsând click dreapta pe joc și apăsând "Properties...".

<figure><img src="../.gitbook/assets/properties.png" alt=""><figcaption></figcaption></figure>

2. Lipește asta în opțiunile tale de pornire (înlocuiește drumul spre joc dacă este diferit):\
   `"C:\Program Files (x86)\Steam\steamapps\common\BattleBit Remastered\EasyAntiCheat.exe" %command%`

<figure><img src="../.gitbook/assets/launchoptionsfix.png" alt=""><figcaption><p>Ar trebui să arate așa. Dacă drumul spre jocul tău diferă - înlocuiește cu actualul tău drum spre joc.</p></figcaption></figure>
