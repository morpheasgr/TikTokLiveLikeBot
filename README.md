# TikTokLiveLikeBot
Ein Click-Bot für TikTok Live (stream) likes. Basiert auf Smart AutoClicker, 

Vorwort:

Das Smart AutoClicker Programm worauf der Bot basiert ist ist Open Source, hat keine Werbung und ich habe mich für diese Lösung entschieden, weil ich den zahlreichen chinesischen Clickern auf Google Play Store nicht vertraue. Jeder ClickBot benötigt die Erlaubnis zu sehen was auf dem Bildschirm angezeigt wird, und die Erlaubnis auf dem Bildschirm beliebig etwas anzuklicken. Offener Quellcode bedeutet in diesem Fall keine Geheimnisse, keine Datensammlung und keine Viren.

## Installationsanleitung:

1. Smart AutoClicker installieren ber die APK oder über den F-Droid App Store:

Github Diwnload Link:
https://github.com/Nain57/Smart-AutoClicker/releases/latest/download/smartautoclicker-release.apk

F-Droid Download Link, oder einfach im F-Droid App Store nach Smart AutoClicker suchen:
https://f-droid.org/en/packages/com.buzbuz.smartautoclicker/

(Der übliche Prozess zur Installation von APK Dateien wird hier benötigt, also müsst ihr "Installation von unbekannten Quellen" erlauben . Falls ihr keine Erfahrung mit der Installation von APKs habt würde ich euch empfehlen die Erlaubnis dannach wieder zu Deaktivieren, damit ihr nicht irgendwann mal aus Versehen beim surfen auf ner boßhaftigen Werbung klickt und der Finger auf "Installieren" verrutscht. Ist je nach Hersteller und Android-Version etwas unterschiedlich aber auf den aktuellen Versionen findet man die Berechtigung unter Einstellungen > Apps & Berechtigungen > Spezieller App Zugriff > Installieren unbekannter Apps)

Bei der ersten Ausführung Berechtigungen ("Über andere Apps einblenden", "Bedienungshilfe") zuweisen. Die erste ist für den Zugriff auf den Bildschirminhalt und die zweite für das Anklicken.

Quellcode findet ihr hier bei Interesse oder falls ihr wie ich gerne überprüft welchen Programmen ihr vertraut:
https://github.com/Nain57/Smart-AutoClicker

2. Meine Backup-ZIP Datei (SmartAutoClicker-TikTokLiveLikeBot.zip) herunterladen und über das Ordner-Symbol un Smart AutoClicker importieren, dann jedes mal über Smart AutoClicker das "Szenario" (den Bot) anklicken/laden und von der Overlay Leiste die dann angezeigt wird beliebig auf Play, Pause, bearbeiten oder Stop drücken.

Download:
https://github.com/morpheasgr/TikTokLiveLikeBot/releases/latest/download/SmartAutoClicker-TikTokLiveLikeBot.zip


## Technisches Info über meinen Bot:
Der Bot (das Szenario) reagiert wenn der Rosen-Button auf dem Bildschirm sichtbar wird, und klickt dann mit unmenschlicher Geschwindigkeit am oberen linken Bildschirmbereich.

Wenn der Rosen-Button für eine Gesamtdauer von 8 Minuten und 15 Sekunden nicht auf dem Bildschirm sichtbar ist, beendet sich das Szenario und muss erneut gestartet werden.
Die Sichtbarkeit des Rosen-Buttons wird jede 5 Sekunden überprüft, das bedeutet dass es bis zu fünf Sekunden dauern kann bis der Bot erneut anfängt auf den Bildschirm zu tippen jedes mal wenn andere Bildschirmaktivität erkannt wird.

Die Klick-Punkte verlangen leider feste X-Y Koordinaten und die Wartezeit zwischen jedem Klick wird bei jedem definierten Klick als Konstante definiert. Fühlt euch frei die Koordinaten zu korrigieren und die Timings anzupassen falls es Probleme bei eurem Gerät verursacht oder wenn ihr einen milderen Effekt haben wollt.

Ihr könnt mit jederzeit bei Github unter https://github.com/morpheasgr/TikTokLiveLikeBot unter "Issues" Probleme, Fragen oder Wünsche melden, denn mein Ziel ist es den Bot so anzupassen, dass er universal auf allen Android-Geräten ohne Aufwand gebrauchbar ist.

Mit freundlichen Grüßen,
Morpheas
