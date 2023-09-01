# Running sfc/dism

1. Run command prompt as administrator.

<figure><img src="../.gitbook/assets/cmd.png" alt=""><figcaption><p>Type <code>cmd.exe</code> in search and press "Run as administrator".</p></figcaption></figure>

2. Run next commands in order:\
   `sfc /scannow`\
   `dism /online /cleanup-image /checkhealth`\
   `dism /online /cleanup-image /scanhealth`\
   `dism /online /cleanup-image /restorehealth`

<figure><img src="../.gitbook/assets/sfcdism.png" alt=""><figcaption><p>That's how command prompt should look after both sfc and dism finished.</p></figcaption></figure>

3. After it's finished, additionally you can run `chkdsk /f /r /x` to check your drive for corruptions.

<figure><img src="../.gitbook/assets/chkdsk.png" alt=""><figcaption></figcaption></figure>

After you'll press Y, reboot your PC.

<figure><img src="../.gitbook/assets/chkdskloading.png" alt=""><figcaption></figcaption></figure>
