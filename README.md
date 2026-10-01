# TIMEperative

Because nothing is more precious than your time.

TIMEperative records work and private time in one place, on your PC and on your phone. This repository is where the apps are published: it holds the installers and the update manifests. The source code is private.

## Install

Download the file for your device from the [latest release](https://github.com/Acunomic/timeperative/releases/latest).

**Windows**

1. Download `timeperative-<version>-windows-setup.exe`.
2. Run it. The installer is not code-signed yet, so Windows may show "Windows protected your PC". If you trust this page, choose **More info**, then **Run anyway**. Some company PCs do not allow this; ask your IT team.

**Android**

1. On the phone, download `timeperative-<version>-android.apk`.
2. Open it. When Android asks, allow your browser to install apps.

## Updates

Once installed, the app keeps itself up to date. It looks for a new version when it starts and once every morning, never before 06:00.

- **Windows** asks before it installs the update, then restarts the app.
- **Android** offers the download; you confirm the installation.

Installed from the earlier download page, [github.com/youserpath/timely](https://github.com/youserpath/timely)? Your app moves here by itself with its next update. Early test builds that cannot update themselves (Windows alpha.1 and alpha.2, Android alpha.4 and older) need the current version installed once by hand.

## What a release contains

| File | What it is |
|---|---|
| `timeperative-<version>-windows-setup.exe` | The Windows installer |
| `timeperative-<version>-windows-setup.exe.sig` | Its signature, which the app checks before it installs an update |
| `timeperative-<version>-android.apk` | The Android app |
| `latest.json`, `latest-android.json` | The update manifests the apps read; leave them in place |

## Deutsch

Weil nichts kostbarer ist als Deine Zeit.

Hier erscheinen die Apps: Installationsprogramme und Update-Manifeste. Der Quellcode ist privat.

**Windows:** `timeperative-<version>-windows-setup.exe` aus dem [neuesten Release](https://github.com/Acunomic/timeperative/releases/latest) herunterladen und ausführen. Weil das Installationsprogramm noch nicht signiert ist, kann Windows davor warnen. Wer dieser Seite vertraut, öffnet in der Warnung die weiteren Informationen und führt das Programm trotzdem aus. Auf Firmen-PCs ist das manchmal gesperrt; dann hilft die IT.

**Android:** `timeperative-<version>-android.apk` auf dem Telefon herunterladen und öffnen. Wenn Android fragt, dem Browser das Installieren von Apps erlauben.

Danach hält sich die App selbst aktuell und sucht beim Start und einmal jeden Morgen nach einer neuen Version, nie vor 06:00. Eine App von der früheren Download-Seite wechselt mit ihrem nächsten Update von selbst hierher.
