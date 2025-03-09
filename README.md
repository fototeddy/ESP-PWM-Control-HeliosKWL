# ESP-PWM-Control-HeliosKWL
ESP32 Control for HELIOS KWL via ESPHome

Steuerung für die dezentrale Raumlüftung von HELIOS KWL Ec 45-160 Verso
Die Steuerung kann zwei Pendellüfterpaare unabhängig von einander Steuern. (Wohnraum / Trockenraum)

Für ein Lüfterpaar (Wohnraum) gibt es den Abluft Modus. In diesem Modus reagieren beide Lüfter auf weitere Lüfter wie Badlüfter oder Dunstabzugshauben und schalten beide in den Zuluft Modus.

Außerdem gibt es einen Schalter für den Pendelmodus. Im Pendelmodus ist die Wäremrückgewinnung der Lüfter aktiv und sie Pendel im Takt von 45 Sekunden.

Ohne Pendelmodus ist ein Lüfter dauerhaft im Zuluft modus und einer Dauerhaft im Abluftmodus.
