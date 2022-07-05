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

<details><summary><h3>🛡 Extensions</h3></summary>
  

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

</details>

<details><summary><h3>📜 Policies</h3></summary>

  Source: https://admx.help/HKLM/Software/Policies/Google
  ```powershell
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome" /v AdvancedProtectionAllowed /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome" /v AutofillAddressEnabled /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome" /v AutofillCreditCardEnabled /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome" /v BackgroundModeEnabled /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome" /v ComponentUpdatesEnabled /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome" /v DefaultBrowserSettingEnabled /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome" /v DownloadBubbleEnabled /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome" /v ForceGoogleSafeSearch /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome" /v MetricsReportingEnabled /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome" /v PasswordDismissCompromisedAlertEnabled /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome" /v PasswordLeakDetectionEnabled /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome" /v PasswordManagerEnabled /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome" /v PromptForDownloadLocation /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome" /v RestoreOnStartup /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome" /v RoamingProfileSupportEnabled /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome" /v SafeBrowsingProtectionLevel /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome" /v ShowFullUrlsInAddressBar /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome" /v ShowHomeButton /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome" /v SpellcheckEnabled /t REG_DWORD /d 0 /f
  ```
  
  ### Force Install Extensions
  
  ```powershell
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome\ExtensionInstallForcelist" /v 1 /d "cjpalhdlnbpafiamejdnhcphjbkeiagm" /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome\ExtensionInstallForcelist" /v 2 /d "lebiggkccaodkkmjeimmbogdedcpnmfb" /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome\ExtensionInstallForcelist" /v 3 /d "cmokoclkdghcohhmpohdhjahocjgjblp" /f
  ```

  ### [Force Block Site](https://github.com/awesome-windows11/chrome/blob/main/files/URLBlocklist.reg)
  
  
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
