---
description: 'Error 5: Access Denied'
---

# Ошибка запуска - StartService EasyAntiCheat\_EOSSys failed with 5.

<figure><img src="../.gitbook/assets/eossysfailedwith5.png" alt="" width="398"><figcaption></figcaption></figure>

1. Запустите [EAC Fix batch](https://github.com/livingflore/BattleBitEACFix/releases) (файл BattleBitEACFix.bat).
2. Выдайте EAC полный доступ для всех пакетов приложений в реестре.

<figure><img src="../.gitbook/assets/runregedit.png" alt="" width="369"><figcaption><p>Нажмите Win+R, введите <code>regedit.exe</code> и нажмите Enter.</p></figcaption></figure>

<figure><img src="../.gitbook/assets/uacregistry.png" alt=""><figcaption><p>Нажмите Да.</p></figcaption></figure>

<figure><img src="../.gitbook/assets/registrypath.png" alt=""><figcaption><p>Проследуйте по пути <code>HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\EasyAntiCheat_EOS</code>.</p></figcaption></figure>

<figure><img src="../.gitbook/assets/permissions.png" alt=""><figcaption><p>Нажмите ПКМ по папке <code>EasyAntiCheat_EOS</code>.</p></figcaption></figure>

<figure><img src="../.gitbook/assets/grantallapp.png" alt=""><figcaption><p>Нажмите на галочку "полный доступ" под группой "ВСЕ ПАКЕТЫ ПРИЛОЖЕНИЙ".</p></figcaption></figure>
