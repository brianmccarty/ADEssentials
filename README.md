<p align="center">
  <a href="https://www.powershellgallery.com/packages/ADEssentials"><img src="https://img.shields.io/powershellgallery/v/ADEssentials.svg"></a>
  <a href="https://www.powershellgallery.com/packages/ADEssentials"><img src="https://img.shields.io/powershellgallery/vpre/ADEssentials.svg?label=powershell%20gallery%20preview&colorB=yellow"></a>
  <a href="https://github.com/EvotecIT/ADEssentials"><img src="https://img.shields.io/github/license/EvotecIT/ADEssentials.svg"></a>
</p>

<p align="center">
  <a href="https://www.powershellgallery.com/packages/ADEssentials"><img src="https://img.shields.io/powershellgallery/p/ADEssentials.svg"></a>
  <a href="https://github.com/EvotecIT/ADEssentials"><img src="https://img.shields.io/github/languages/top/evotecit/ADEssentials.svg"></a>
  <a href="https://github.com/EvotecIT/ADEssentials"><img src="https://img.shields.io/github/languages/code-size/evotecit/ADEssentials.svg"></a>
  <a href="https://github.com/EvotecIT/ADEssentials"><img src="https://img.shields.io/powershellgallery/dt/ADEssentials.svg"></a>
</p>

<p align="center">
  <a href="https://twitter.com/PrzemyslawKlys"><img src="https://img.shields.io/twitter/follow/PrzemyslawKlys.svg?label=Twitter%20%40PrzemyslawKlys&style=social"></a>
  <a href="https://evotec.xyz/hub"><img src="https://img.shields.io/badge/Blog-evotec.xyz-2A6496.svg"></a>
  <a href="https://www.linkedin.com/in/pklys"><img src="https://img.shields.io/badge/LinkedIn-pklys-0077B5.svg?logo=LinkedIn"></a>
</p>

# ADEssentials

## To install

```powershell
Install-Module -Name ADEssentials -AllowClobber -Force
```

Force and AllowClobber aren't really nessecary but they do skip errors in case some appear.

## And to update

```powershell
Update-Module -Name ADEssentials
```

That's it. Whenever there's new version you simply run the command and you can enjoy it. Remember, that you may need to close, reopen PowerShell session if you have already used module before updating it.

**The important thing** is if something works for you on production, keep using it till you test the new version on a test computer. I do changes that may not be big, but big enough that auto-update will break your code. For example, small rename to a parameter and your code stops working! Be responsible!

## Changelog

- 0.0.22 - 28.10.2019
  - [x] Added some functions
- 0.0.21 - 10.10.2019
  - [x] Fix for Get-WinADLastBackup
- 0.0.7 - 3.08.2019
  - [x] Added Get-WinADLastBackup
