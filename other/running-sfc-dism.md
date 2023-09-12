# Lancer sfc/dism

1. Lancer le terminal en tant qu'administrateur.

<figure><img src="../.gitbook/assets/cmd.png" alt=""><figcaption><p>Type <code>cmd.exe</code> in search and press "Run as administrator".</p></figcaption></figure>

2. Exécutez les commandes suivantes dans l'ordre:\
   `sfc /scannow`\
   `dism /online /cleanup-image /checkhealth`\
   `dism /online /cleanup-image /scanhealth`\
   `dism /online /cleanup-image /restorehealth`

<figure><img src="../.gitbook/assets/sfcdism.png" alt=""><figcaption><p>Voici à quoi doit ressembler le résultat de sfc et dism.</p></figcaption></figure>

3. Une fois fini, vous pouvez aussi lancer la commande `chkdsk /f /r /x` pour vérifier toute corruption sur vos partitions.

<figure><img src="../.gitbook/assets/chkdsk.png" alt=""><figcaption></figcaption></figure>

Après avoir validé, redémarrez votre PC.

<figure><img src="../.gitbook/assets/chkdskloading.png" alt=""><figcaption></figcaption></figure>
