# Tutorial zum Nachbauen der LED-Matrix-Spielekonsole

## Input- und Output-Devices anschließen
Den Sparkfun I2C Adapter nach Anleitung auf GPIO-Pins aufstecken und per Kabel mit Sparkfun IMU 20948 verbinden. Anschließend den UnicornhatHD aufstecken.

## Dependencies installieren
```bash
pip3 install unicornhathd https://github.com/DHBW-HDH-Team-HimbeerPi/inputFramework/releases/download/latest/input_framework_lars_jaeger-0.0.1-py3-none-any.whl https://github.com/DHBW-HDH-Team-HimbeerPi/outputFramework/releases/download/latest/output_framework_simon_berndt-0.0.1-py3-none-any.whl numpy
```
## Spiele installieren
```bash
mkdir games
cd games
git clone https://github.com/DHBW-HDH-Team-HimbeerPi/raspberry-cementary.git
git clone https://github.com/DHBW-HDH-Team-HimbeerPi/GameRepo.git
```
## Hauptmenü starten
```bash
cd GameRepo
python3 main.py
```
