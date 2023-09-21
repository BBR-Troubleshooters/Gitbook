---
description: Fii sigur că jocul este pornit adecvat cu serviciile de Anti-cheat.
cover: ../.gitbook/assets/ackick.png
coverY: -3.74785998472845
---

# Ai fost dat afară de către anti cheat.

1. Dacă folosești o filă de limbă costumizată - șterge-o și poți continua
2. Fii sigur că nu ai intrări EAC în fișierele de host (`etc/hosts` sau `C:\Windows\System32\drivers\etc\hosts`) care sunt necesare în unele jocuri (Star Citizen ca exemplu).
3. Pornește [EAC Fix batch](https://github.com/livingflore/BattleBitEACFix/releases) (fișă .bat).
4. Asigură-te că absolut **NIMIC** nu blochează conexiunea EAC (antivirus/firewall/ISP).
5. Șterge folder-ul `Certificates` în folder-ul în care jocul a fost instalat/ în folder-ul`EasyAntiCheat` și după verifică fișele jocului.

<figure><img src="../.gitbook/assets/browse.png" alt="" width="374"><figcaption><p>Dă click dreapta pe joc, apoi mergi la "Manage" și dă click pe "Browse local files".</p></figcaption></figure>

<figure><img src="../.gitbook/assets/delete.png" alt="" width="464"><figcaption><p>Du-te la folder-ul <code>EasyAntiCheat</code> și șterge folder-ul <code>Certificates</code>.</p></figcaption></figure>

<figure><img src="../.gitbook/assets/BBR_Validation.gif" alt="" width="563"><figcaption><p>Dă click dreapta pe joc și apasă "Properties...", Selectează "Installed Files" și apasă "Verify integrity of game files".</p></figcaption></figure>

6. Schimbă-ți IP-ul prin restartând modem-ul/router-ul sau folosește un VPN privat/[Cloudflare WARP](https://1.1.1.1).
7. [Verifică update-uri recente de la windows](ms-settings:windowsupdate-history) - dacă a fost un update și după acesta ai început să experimentezi probleme, [dă-l înapoi](https://www.itechtics.com/rollback-windows-updates/).
