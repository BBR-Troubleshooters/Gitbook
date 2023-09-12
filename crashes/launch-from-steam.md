---
description: >-
  Le jeu crash instantanément au lancement via Steam, mais fonctionne s'il est lancé
  par le .exe du jeu.
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

# Lancer via Steam

Si vous avez ce problème:

1. Naviguez vers les options de lancement en faisant clic droit sur le jeu et  "Propriétés...".

<figure><img src="../.gitbook/assets/properties.png" alt=""><figcaption></figcaption></figure>

2. Collez ceci dans vos options de lancement (remplacez le chemin si votre jeu n'est pas au même endroit):\
   `"C:\Program Files (x86)\Steam\steamapps\common\BattleBit Remastered\EasyAntiCheat.exe" %command%`

<figure><img src="../.gitbook/assets/launchoptionsfix.png" alt=""><figcaption><p>Ca devrait ressembler à ça. Si le chemin de votre jeu n'est pas le même - remplacez le par le vôtre.</p></figcaption></figure>
