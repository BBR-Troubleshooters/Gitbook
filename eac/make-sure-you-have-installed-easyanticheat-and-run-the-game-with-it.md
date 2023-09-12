---
description: Beside EAC, your connection can also cause this issue.
cover: ../.gitbook/assets/redtext.png
coverY: 0
---

# Make sure you have installed EasyAntiCheat and run le jeu with it.

{% hint style="info" %}
Steam is down for maintenance every Tuesday at 22:00 UTC. This error will appear if you try to join le jeu while Steam is down.
{% endhint %}

<details>

<summary>Step 1 - Running executables as admin</summary>

Try running `BattlebitEAC.exe` or `EasyAntiCheat.exe` as admin located in installed files.

1. Right Cliquez sur le jeu, allez ensuite sur  "Manage" and Cliquez sur "Browse local files".

<img src="../.gitbook/assets/browse.png" alt="Right Cliquez sur le jeu, allez ensuite sur  manage and Cliquez sur Browse local files" data-size="original">

2. Right Cliquez sur executable and cliquez sur "Run as administrator".

<img src="../.gitbook/assets/runasadmin.png" alt="Right Cliquez sur executable and cliquez sur &#x22;Run as administrator&#x22;." data-size="original">

</details>

<details>

<summary>Step 2 - Run the <a href="https://github.com/livingflore/BattleBitEACFix/releases">EAC Fix batch</a></summary>

1. Go to [releases page](https://github.com/livingflore/BattleBitEACFix/releases).
2. Download BattleBitEACFix.bat.
3. Run the batch.
4. You should see output as shown below.

<img src="../.gitbook/assets/batchoutput.png" alt="" data-size="original">

</details>

<details>

<summary>Step 3 - VCRedists</summary>

Ensure that **BOTH** VCRedists are installed properly - [x86](https://aka.ms/vs/17/release/vc\_redist.x86.exe) and [x64](https://aka.ms/vs/17/release/vc\_redist.x64.exe). When running installers you should see 3 buttons - repair, uninstall and cancel as shown on screenshots below. If you can't see it, then proceed with installation.

<img src="../.gitbook/assets/vcredistx64.png" alt="" data-size="original"><img src="../.gitbook/assets/vcredistx86.png" alt="" data-size="original">

</details>

<details>

<summary>Step 4 - Connectivity issues</summary>

This issue can happen when your connection unstable / Steam is down / you can't reach either EAC or BattleBit servers.

1. Check Steam if you're in offline mode.
2. Désactivez malware protection and firewall if you use third party antivirus (Kaspersky, Avast, etc).
3. Try to use mobile hotspot instead of your main internet connection just to launch le jeu. If it happens that you don't have it, proceed to the next step.
4. Use any **private** VPN or [Cloudflare WARP](https://install.appcenter.ms/orgs/cloudflare/apps/1.1.1.1-windows-1/distribution\_groups/release).

</details>
