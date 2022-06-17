<h1 align="center"><img width=30px src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/28/Chromium_Logo.svg/1200px-Chromium_Logo.svg.png"></img> Awesome Chrome (in the progress...)</h1>

All Chromium based browsers fit this page: Chrome, Microsoft Edge, Brave, Yandex, Opera, Vivaldi

[Portable Chromium (full USB!)](https://github.com/jestxfot/Google-Chrome-Portable)
<br>
https://chromium.woolyss.com
<br>
https://github.com/henrypp/chrlauncher
<br>
[Browser Portable sourceforge.net](https://sourceforge.net/projects/portableapps/files/)
<br>
[Browser Portable portapps.io](https://portapps.io/apps/)
<br>
[Effect8](http://effect8.ru/)
<br>
[Spyware Browsers](https://spyware.neocities.org/articles/browsers.html) or https://spyware.neocities.org/articles/index.html
<br>
[How to choose a browser for everyday use?](https://digdeeper.neocities.org/ghost/browsers.html)

<h3 align="center">🛡 Extensions</h3>

https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm
<br>
https://chrome.google.com/webstore/detail/keepassxc-browser/oboonakemofpalcgghocfoadofidjkkk
<br>
https://chrome.google.com/webstore/detail/favicons-for-google-searc/cmokoclkdghcohhmpohdhjahocjgjblp
<br>
https://chrome.google.com/webstore/detail/checker-plus-for-google-c/hkhggnncdpfibdhinjiegagmopldibha
<br>
https://chrome.google.com/webstore/detail/block-site/lebiggkccaodkkmjeimmbogdedcpnmfb
<br>
https://chrome.google.com/webstore/detail/improve-youtube-video-you/bnomihfieiccainjcjblhegjgglakjdd
<br>
https://github.com/z0ccc/Vytal

<details><summary><h3>📜 Policies</h3></summary>

  Source: https://admx.help/HKLM/Software/Policies
  ```powershell
  echo "Disable Windows Defender"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender" /v DisableAntiSpyware /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender" /v DisableRealtimeMonitoring /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender" /v DisableAntiVirus /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender" /v DisableSpecialRunningModes /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender" /v DisableRoutinelyTakingAction /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender" /v ServiceKeepAlive /t REG_DWORD /d 0 /f
  echo "Disable RealTimeProtection"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender\Real-Time Protection" /v DisableBehaviorMonitoring /t REG_DWORD /d 1 /f
  echo "Disable AccessProtection"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender\Real-Time Protection" /v DisableOnAccessProtection /t REG_DWORD /d 1 /f
  echo "Disable ScanProcess"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender\Real-Time Protection" /v DisableScanOnRealtimeEnable /t REG_DWORD /d 1 /f
  echo "Disable ScanDownloadFiles"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender\Real-Time Protection" /v DisableIOAVProtection /t REG_DWORD /d 1 /f
  echo "Disable VirusNotification"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender\Real-Time Protection" /v DisableRealtimeMonitoring /t REG_DWORD /d 1 /f
  echo "Disable AppControl (Windows Store)"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender\SmartScreen" /v ConfigureAppInstallControlEnabled /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender\Signature Updates" /v ForceUpdateFromMU /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender\Spynet" /v DisableBlockAtFirstSeen /t REG_DWORD /d 1 /f
  echo "Disable TamperProtection"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Defender\Features" /v TamperProtection /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Defender" /v ServiceStartStates /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Defender" /v DisableAntiSpyware /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Defender" /v DisableAntiVirus /t REG_DWORD /d 1 /f
  ```
</details>

<h3 align="center">📰 News / Build</h3>

Chrome Enterprise | https://chromeenterprise.google/intl/ru_ru/browser/download/
<br>
https://support.google.com/chrome/a/answer/7679408
<br>
https://storage.googleapis.com/chromium-browser-snapshots/index.html
<br>
Проверить revision | https://chromium.googlesource.com/chromium/src/+refs
<br>
https://crrev.com/1013379
<br>
https://www.chromium.org/developers/calendar
<br>
https://download-chromium.appspot.com
<br>
https://chromestatus.com/features
<br>
https://omahaproxy.appspot.com
<br>
https://www.google.com/search?q=chrome&newwindow=1&safe=active&tbm=nws&sxsrf=ALeKk02WflmashJLnOL3PPFSgsGn7qbdKw:1622228938473&source=lnt&tbs=sbd:1&sa=X&ved=2ahUKEwjWt_zcie3wAhXC-ioKHXf1BvUQpwV6BAgIECw&dpr=1
