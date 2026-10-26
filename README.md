# Soniq downloads

Soniq is a small Windows 11 tray app that looks after your hearing. It recognizes your headphones, estimates how loud the sound in them really is (in decibels), keeps track of how long and how loud you listen against hearing-health standards, and gives you a gentle heads-up when your listening could harm your ears. Everything is calculated on your own computer; no data is ever uploaded.

This repository only hosts the installer and update files. The app's interface is currently in Simplified Chinese.

## Install

1. Open **Releases** on the right, pick the latest version, and download **`SoniqApp-win-Setup.exe`**.
2. Run it. The installer isn't digitally signed yet, so Windows may show a blue "Windows protected your PC" screen:
   click **More info** → **Run anyway**.
3. When setup finishes, Soniq opens automatically and appears in the notification area at the bottom right of the taskbar.

**If you were using the portable version before** (running `Soniq.exe` directly): before installing, right-click the Soniq icon in the notification area → **Exit (退出)**. Your listening history and settings are kept, and the installed version picks them up.

## Updates

The installed version checks for new versions automatically (about every 12 hours), downloads them in the background, and installs them the next time Soniq starts. You can also check manually, update right away, or turn automatic checks off in **Settings (设置) → General (通用) → Updates (更新)**. Soniq only downloads from this page; it never uploads anything.

## Uninstall

Open Windows **Settings → Apps → Installed apps**, find Soniq, and click **Uninstall**. This also removes Soniq from startup. Your listening history stays in `%LocalAppData%\Soniq` and is not deleted; you can delete that folder yourself if you no longer need it.
