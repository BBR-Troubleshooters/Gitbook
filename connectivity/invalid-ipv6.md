---
cover: ../.gitbook/assets/ipv6timeout.png
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

# Adresse IPv6 invalide

Si vous êtes bliqués sur connection au server principal, et que `api.battlebit.cloud` retourne une erreur de type adresse IPv6 invalide , suivez:

<details>

<summary>Windows 10</summary>

1. Cliquez sur "Réseau & Internet" dans les paramètres Windows.

<img src="../.gitbook/assets/network.png" alt="" data-size="original">

2. Selon votre type de connection, selectionnez Wifi ou Ethernet sur "Changer les options de l'adaptateur".

<img src="../.gitbook/assets/adapter.png" alt="" data-size="original">

3. Clic droit sur votre adaptateur principal et sélectionnez propritétés.

<img src="../.gitbook/assets/adapterproperties.png" alt="" data-size="original">

4. Désactivez "Internet Protocol Version 6 (TCP/IPv6)" et validez.

<img src="../.gitbook/assets/disableipv6.png" alt="" data-size="original">

</details>

<details>

<summary>Windows 11</summary>

1. Cliquez sur "Réseau & Internet" dans les paramètres Windows.

<img src="https://images.taylorgibbs.dev/bkfhsk.png" alt="" data-size="original">

2. Cliquez sur "Paramètres réseau avancés"

<img src="https://images.taylorgibbs.dev/uzyc3u.png" alt="" data-size="original">

3. Descendez et cliquez sur "More network adapter options".

<img src="https://images.taylorgibbs.dev/a2myev.png" alt="" data-size="original">

4. Right-Cliquez sur connection internet et cliquez sur "Propriétés".

<img src="https://images.taylorgibbs.dev/rn04y5.png" alt="" data-size="original">

4. Désactivez "Internet Protocol Version 6 (TCP/IPv6)" et validez.

<img src="https://images.taylorgibbs.dev/no8q11.png" alt="" data-size="original">

</details>
