---
description: 'Eroarea 5: Acces respins'
---

# Launch Error - StartService EasyAntiCheat\_EOSSys failed with 5.

<figure><img src="../.gitbook/assets/eossysfailedwith5.png" alt="" width="398"><figcaption></figcaption></figure>

1. Pornește [EAC Fix batch](https://github.com/livingflore/BattleBitEACFix/releases) (fișă .bat).
2. Permite accesul total la EAC pentru aplicarea pachetelor în registru.

<div data-full-width="true">

<figure><img src="../.gitbook/assets/runregedit.png" alt=""><figcaption><p>Apasă Win+R, scrie <code>regedit.exe</code> și apasă Enter</p></figcaption></figure>

</div>

<figure><img src="../.gitbook/assets/uacregistry.png" alt=""><figcaption><p>Apasă Da.</p></figcaption></figure>

<figure><img src="../.gitbook/assets/registrypath.png" alt=""><figcaption><p>Du-te la <code>HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\EasyAntiCheat_EOS</code>.</p></figcaption></figure>

<figure><img src="../.gitbook/assets/permissions.png" alt=""><figcaption><p>Apasă click dreapta pe <code>EasyAntiCheat_EOS</code>.</p></figcaption></figure>

<figure><img src="../.gitbook/assets/grantallapp.png" alt=""><figcaption><p>Apasă "Allow" la checkbox-ul pentru "Full Control" sub grupul "ALL APPLICATION PACKAGES".</p></figcaption></figure>
