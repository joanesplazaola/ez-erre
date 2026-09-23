# EZ ERRE

Android aplikazio txiki bat: botoia sakatu, GIFa erakutsi eta euskarazko esaldi bat ausaz aukeratzen du.

## GitHub Actions bidez APK-a sortzea

Repo honetako fitxategi guztiak GitHub-era igo.

Ondoren:
1. GitHub-en ireki repo-a.
2. `Actions` atalera joan.
3. `Build Android APK` aukeratu.
4. `Run workflow` sakatu (edo `main` branch-era push egitean automatikoki exekutatuko da).
5. Build-a bukatzean, workflow run-aren behealdean `Artifacts` atalean `ez-erre-apk` deskargatu.
6. ZIP horren barruan `app-debug.apk` egongo da.

APK hau debug sinadurarekin sinatuta dago eta Android telefono batean zuzenean instala daiteke.

## Teknologia
- Android app arrunta
- Java Activity + WebView lokal bat
- Ez du Internetik behar
- Ez du baimenik behar
- Ez du backendik
- GIFa aplikazioaren barruan dago
