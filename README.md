# Räuber-Rallye 🏃‍♂️💨

Ein kindertaugliches Browser-Spiel: Du bist der Räuber in einer von oben
betrachteten Stadt (Stadtplan-Optik). Sammle **1000 Münzen**, ohne von der
Patrouillen-Polizei gesehen zu werden!

**Spiel online:** https://michburkhalter.github.io/rauber-rallye/

## Spielprinzip

- Bewege dich mit **WASD** oder den **Pfeiltasten** durch die Straßen
  (auf dem Handy mit dem **virtuellen Joystick**).
- Steh vor einem Haus und drücke **Leertaste** (oder den **AUSRAUBEN-Button**),
  um es auszurauben (jedes Haus birgt **0–100 Münzen** 💰).
- Die Stadt ist ein echter Stadtplan: gewundene Straßen, **Kurven**,
  **Sackgassen** und **Abzweigungen** – jede Runde neu generiert.
- Polizisten und Fußgänger haben ein sichtbares **Blickfeld** –
  die Häuser blockieren die Sicht, Verstecken funktioniert!
- Ein konfigurierbarer Anteil der Häuser hat eine **Alarmanlage 🚨**:
  Beim Einbruch kommt die Polizei, der erste Polizist vor Ort stoppt den Alarm.
- **Fußgänger** sehen dich und verraten deine Position 20 Sekunden lang
  an die Polizei – mit rotem Alarm-Rand und angeregtem Hinterherlaufen!

## Features

- 4 Schwierigkeits-Presets (füllen nur die Regler vor – alles ist anpassbar):

  | Stufe | Alarmanlagen | Polizisten | Polizei-Tempo | Fußgänger |
  |---|---|---|---|---|
  | 🙂 Einfach | 5 % | 2 | 70 % | 1 |
  | 😐 Mittel | 10 % | 3 | 100 % | 0 |
  | 😈 Schwer | 20 % | 4 | 110 % | 1 |
  | 🤯 Ultra | 10 % | 3 | 85 % | 3 |

- Einstellbare Regler: Alarmanlagen (%), Anzahl/Tempo der Polizisten,
  Anzahl/Tempo der Fußgänger, Kartengröße (Standard 10×10)
- Prozedural generiertes Straßennetz mit Kurven und unregelmäßigen Kreuzungen
- 4 Haus-Typen im Skizzen-Look
- WebAudio-Sirene und Soundeffekte
- **Responsiv & mobile-tauglich**: Joystick + Ausrauben-Button auf Touch-Geräten
- Neustart per **Leertaste** nach Spielende oder über den HUD-Button
  (zurück zum Startbildschirm mit Reglern)

## Los geht's

Keine Installation nötig – einfach `index.html` im Browser öffnen
oder die GitHub-Pages-Version spielen:

https://michburkhalter.github.io/rauber-rallye/

## Lizenz

MIT – siehe [LICENSE](LICENSE).
