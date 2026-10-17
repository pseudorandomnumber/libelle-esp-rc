# Libelle Control

Web Bluetooth remote control for the Libelle dragonfly ornithopter (ESP32-C3 bench firmware).

**Open the app: https://pseudorandomnumber.github.io/libelle-esp-rc/**

Open the page in Chrome on Android or on a computer, tap **Connect** and pick `Libelle-XXXX`.
iPhone: use the Bluefy browser.

Motors only start when armed with throttle at 0 and stop on STOP, on disconnect, when the page is hidden,
or 0.5 s after the last control packet.
