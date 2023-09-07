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

# Недействительный IPv6

Если вы застряли на подключении к мастер-серверу, и когда вы пытаетесь проверить его работоспособность посредством команды `ping api.battlebit.cloud` в консоли вам выдает неверный IPv6, сделайте следующее:

<details>

<summary>Windows 10</summary>

1. Перейдите в Параметры Windows и нажмите на "Сеть и Интернет".

<img src="../.gitbook/assets/network.png" alt="" data-size="original">

2. Выберите "Настройка параметров адаптера".

<img src="../.gitbook/assets/adapter.png" alt="" data-size="original">

3. Нажмите ПКМ по вашей основной сети, затем выберите "Свойства".

<img src="../.gitbook/assets/adapterproperties.png" alt="" data-size="original">

4. Выключите "IP версии 6 (TCP/IPv6)" и нажмите ОК.

<img src="../.gitbook/assets/disableipv6.png" alt="" data-size="original">

</details>

<details>

<summary>Windows 11</summary>

1. Перейдите в параметры Windows 11 и нажмите на вкладку "Сеть и Интернет".

<img src="../.gitbook/assets/w11network.png" alt="" data-size="original">

2. Нажмите на "Дополнительные сетевые параметры".

<img src="../.gitbook/assets/w11advancednetworkoptions.png" alt="" data-size="original">

3. Чуть ниже нажмите на "Дополнительные параметры сетевого адаптера".

<img src="../.gitbook/assets/w11moreoptions.png" alt="" data-size="original">

4. Нажмите ПКМ по вашей основной сети, затем выберите "Свойства".

<img src="../.gitbook/assets/w11networkproperties.png" alt="" data-size="original">

5. Выключите "IP версии 6 (TCP/IPv6)" и нажмите ОК.

<img src="../.gitbook/assets/w11disableipv6.png" alt="" data-size="original">

</details>
