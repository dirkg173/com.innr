Mit dieser App können Sie Ihre INNR-Geräte mit Homey verbinden

Unterstützte Geräte:

RB 285 C, BY 285 C
RB 265, BY 265
RB 250 C,
RF 261
RF 263, BF 263
RF 264,
RF 265, BF 265
SP 110, SP 120, SP 222, SP 220
RB 185 C, BY 185 C
FL 130 C
RB 162, RB 165, RB 175 W, BY 165
RB 145, B 245
RS 125, RS 122, RS 225
RS 128 T, RS 228 T, RS 229 T
RS 230 C
BY 178 T, RB 178 T, RB 278 T
RB 148 T, RB 248 T
PL 110, PL 115
RSL 110
DL 110 N, DL 110 W, SL 110 N, SL 110 M, SL 110 W
UC 110, FL 110, ST 110
RC 110

Anmerkungen

INNR Remote.

Das Koppeln benötigt Zeit und die Meldung zeigt, dass Sie das Gerät in den Koppelmodus versetzen müssen.
Aber lassen Sie es wie es ist, die Kopplung geht wenige Augenblicke später weiter.

Flows sind in Arbeit und Programmtasten werden (noch) nicht unterstützt! Nur wenn der Schieberegler auf LIGHTS steht, können die Tasten -, + und An/Aus mit den Tasten 1-6 genutzt werden. Beispiel: Stellen Sie den Schieberegler auf LIGHTS. Drücken Sie kurz eine Zahlentaste gefolgt von -, + oder An/Aus. Langes Drücken der Tasten -, + wird ebenfalls unterstützt und sind über Tokens innerhalb der Flows verfügbar.

Verfügbare Tokens:

Taste (Nummer): 1, 2, 3, 4, 5, 6
Typ (Tastenfolge): "- kurz", "+ kurz", An, Aus, "- lang", "+ lang", Stop


Schieberegler auf der Fernbedienung in Position SCENES, Befehle werden gesendet und auf Gruppe 0 angewendet. Wenn ich richtig liege, gilt dies für alle ZigBee-Geräte, konnte es aber nicht testen, da ich keine anderen ZigBee-Marken mit Homey verwende.

Feedback:

Bei Fragen kontaktieren Sie mich bitte unter Slack
Bitte melden Sie Probleme im Abschnitt "Issues" auf Github