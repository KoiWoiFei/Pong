Pong ist unser Haupt-Roboter.

Specs:

Boards:
-1 RaspberryPi 3B (Interpretiert Werte, Steuert Motoren)
-4 Nano Boards (Liest Ultraschall Sensoren aus, Abstands LED Steuerung)

Sensoren/Aktoren:
-16 Ultraschall Sensoren
-32 WS2812B LEDs (Abstandsanzeige)
-3 Motoren (mit Omniwheels)

In Pong sind zwei eigene PCBs verbaut:
-LED Platine: Hält LEDs zur Abstandsindikation über den Ultraschallsensoren an ihrem Platz
-Ultraschall-Platine: Verbindet Nano mit Sensoren, anderen Nanos und RPi
