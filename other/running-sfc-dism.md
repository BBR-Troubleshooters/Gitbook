# Запуск sfc/dism

1. Запустите коммандную строку от администратора.

<figure><img src="../.gitbook/assets/cmd.png" alt="" width="563"><figcaption><p>Введите <code>cmd.exe</code> в пуске и нажмите "Запуск от имени администратора".</p></figcaption></figure>

2. Запустите следующие команды по порядку:\
   `sfc /scannow`\
   `dism /online /cleanup-image /checkhealth`\
   `dism /online /cleanup-image /scanhealth`\
   `dism /online /cleanup-image /restorehealth`

<figure><img src="../.gitbook/assets/sfcdism.png" alt=""><figcaption></figcaption></figure>

3. После того, как они завершат свою работу, дополнительно вы можете запустить `chkdsk /f /r /x` чтобы проверить ваш диск на повреждения.

<figure><img src="../.gitbook/assets/chkdsk.png" alt=""><figcaption></figcaption></figure>

После того как вы нажмете Y, перезагрузите ваш ПК и `chkdsk` начнет работу.

<figure><img src="../.gitbook/assets/chkdskloading.png" alt=""><figcaption></figcaption></figure>
