---
description: 'Error 5: Access Denied'
---

# Launch Error - StartService EasyAntiCheat\_EOSSys failed with 5.

<figure><img src="../.gitbook/assets/eossysfailedwith5.png" alt="" width="398"><figcaption></figcaption></figure>

1. Lancez [EAC Fix batch](https://github.com/livingflore/BattleBitEACFix/releases) (fichier .bat).
2. Accordez un accès total à EAC dans les registres d'applications.

<figure><img src="../.gitbook/assets/runregedit.png" alt=""><figcaption><p>Faites le raccourci Win+R, tapez <code>regedit.exe</code> et appuyez sur Entrée.</p></figcaption></figure>

<figure><img src="../.gitbook/assets/uacregistry.png" alt=""><figcaption><p>Cliquez sur Oui.</p></figcaption></figure>

<figure><img src="../.gitbook/assets/registrypath.png" alt=""><figcaption><p>Naviguez vers <code>HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\EasyAntiCheat_EOS</code>.</p></figcaption></figure>

<figure><img src="../.gitbook/assets/permissions.png" alt=""><figcaption><p>Cliquez droit sur <code>EasyAntiCheat_EOS</code>.</p></figcaption></figure>

<figure><img src="../.gitbook/assets/grantallapp.png" alt=""><figcaption><p>Cliquez sur "Full Control" Allow checkbox en dessous du groupe "ALL APPLICATION PACKAGES".</p></figcaption></figure>
