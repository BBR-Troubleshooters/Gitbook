---
description: Pe lângă EasyAntiCheat, conexiunea ta deasemeni poate crea această problemă.
cover: ../.gitbook/assets/redtext.png
coverY: 0
---

# Fii sigur că ai instalat EasyAntiCheat și pornește jocul cu acesta.

{% hint style="info" %}
Steam este dat jos pentru mentenanță în fiecare marți la ora 22:00 UTC. Această eroare va apărea dacă tu încerci să intri în joc în timp ce Steam este dat jos.
{% endhint %}

<details>

<summary>Pasul 1 - Pornește executabilele ca admin</summary>

Încearcă să pornești`BattlebitEAC.exe` sau `EasyAntiCheat.exe` ca admin, localizate în fișierul instalat al jocului

1. Dă click dreapta pe joc, apoi mergi la "Manage" și dă click pe "Browse local files".

<img src="../.gitbook/assets/browse.png" alt="Right click on the game, then go to manage and click on Browse local files" data-size="original">

2. Dă click dreapta pe executabil, apoi dă click pe "Run as administrator".

<img src="../.gitbook/assets/runasadmin.png" alt="Right click on executable and click &#x22;Run as administrator&#x22;." data-size="original">

</details>

<details>

<summary>Pasul 2 - Pornește <a href="https://github.com/livingflore/BattleBitEACFix/releases">EAC Fix batch</a></summary>

1. Mergi la [releases page](https://github.com/livingflore/BattleBitEACFix/releases).
2. Instalează BattleBitEACFix.bat.
3. Pornește batch-ul.
4. O să vezi un output ca cel arătat mai jos.

<img src="../.gitbook/assets/batchoutput.png" alt="" data-size="original">

</details>

<details>

<summary>Pasul 3 - VCRedists</summary>

Fii sigur că **AMBELE** VCRedits sunt instalate cum trebuie - [x86](https://aka.ms/vs/17/release/vc\_redist.x86.exe) și [x64](https://aka.ms/vs/17/release/vc\_redist.x64.exe). Când pornești instalările ar trebui să vezi 3 butoane - repară, dezinstalează și anulează, așa cum se văd în capturile de ecran de mai jos. Dacă nu le vezi, atunci continuă cu instalarea.

<img src="../.gitbook/assets/vcredistx64.png" alt="" data-size="original"><img src="../.gitbook/assets/vcredistx86.png" alt="" data-size="original">

</details>

<details>

<summary>Pasul 4 - Probleme de conectivitate</summary>

Această problemă poate apărea atunci când conexiunea ta este instabilă/ Steam este dat jos/ nu poți să te conectezi la serverele EAC sau BattleBIt.

1. Verifică dacă ești pe offline mode pe Steam
2. Dezactivează protecția de malware și firewall-u dacă folosești un antivirus third party (Kaspersky, Avast, etc).
3. Încearcă să folosești hotspot mobil în locul conexiunii primare la internet doar pentru a deschide jocul. Dacă se întâmplă să nu îl ai, mergi la următorul pas
4. Folosește orice VPN **privat** sau [Cloudflare WARP](https://install.appcenter.ms/orgs/cloudflare/apps/1.1.1.1-windows-1/distribution\_groups/release).

</details>
