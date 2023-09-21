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

# Invalid IPv6

Dacă ești blocat la conexiunea cu serverul principal și atunci când dai ping la `api.battlebit.cloud` îți arată ca IPv6 invalid, urmează următoarele:

<details>

<summary>Windows 10</summary>

1. Apasă pe "Network & Internet" în setări Windows.

<img src="../.gitbook/assets/network.png" alt="" data-size="original">

2. Depinzând de tipul tău de conexiune selectează Wifi sau Ethernet la "Change adapter options".

<img src="../.gitbook/assets/adapter.png" alt="" data-size="original">

3. Apasă click dreapta la adaptatorul tău principal și selectează "proprieties"

<img src="../.gitbook/assets/adapterproperties.png" alt="" data-size="original">

4. Dezactivează "Internet Protocol Version 6 (TCP/IPv6)" și apasă OK.

<img src="../.gitbook/assets/disableipv6.png" alt="" data-size="original">

</details>

<details>

<summary>Windows 11</summary>

1. Apasă pe "Network & Internet" în setări Windows.

<img src="https://images.taylorgibbs.dev/bkfhsk.png" alt="" data-size="original">

2. Apasă pe "Advanced Network Settings"

<img src="https://images.taylorgibbs.dev/uzyc3u.png" alt="" data-size="original">

3. Dă scroll jos si apasă pe "More network adapter options".

<img src="https://images.taylorgibbs.dev/a2myev.png" alt="" data-size="original">

4. Apasă click dreapta pe conexiunea ta de internet, apoi apasă "Properties".

<img src="https://images.taylorgibbs.dev/rn04y5.png" alt="" data-size="original">

4. Dezactivează "Internet Protocol Version 6 (TCP/IPv6)" și apasă OK.

<img src="https://images.taylorgibbs.dev/no8q11.png" alt="" data-size="original">

</details>
