# LA1500
# Projekt-Dokumentation

☝️ Alle Text-Stellen, welche mit einem ✍️ beginnen, können Sie löschen, sobald Sie die entsprechende Stellen ausgefüllt haben.

✍️ Ihr Gruppenname und Ihre Nachnamen

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|       | 0.0.1   | ✍️ Jedes Mal, wenn Sie an dem Projekt arbeiten, fügen Sie hier eine neue Zeile ein und beschreiben in *einem* Satz, was Sie erreicht haben. |
|       | ...     |                                                              |
|       | 1.0.0   |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt

Wie programmieren mit C#  (Unity) ein Tower-Defense spiel.

Wir programmieren ein Tower-Defense spiel. Dessen Prinzip ist das die Gegner eine festgelegte Strecke ab laufen, dabei können Türme neben der Strecke gebaut werden, um zu verhindern, dass die Gegner Das Ziel (unsere Basis) erreichen. Doch für den Spieler wird es immer komplizierter, da immer mehr Gegner kommen aber er die Strecke nicht verändern kann und somit die Länge immer gleich bleibt, die verwendet werden kann, um die Gegner zu stoppen.

Für unser Spiel benutzen wir die Programmiersprache c# und verwenden Unity mit der Kollaboration Funktion.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |    muss        |   funktional   | Als Entwickler möchte ich, dass wenn man das Spiel startet ein Hauptmenü erscheint, damit der Spieler nicht direkt in die Runde gezwungen wird. |
| 2    |           muss      |   funktional   | Als Spieler möchte ich, dass es ein Startknopf im Hauptmenü gibt, damit ich eine Runde starten kann. |
| 3    |  muss               |   rand         | Als Spieler möchte ich, dass das Spiel Musik hat, damit ich mehr Spass habe und es meine Erfahrung besser macht. |
| 3    |  muss             |   rand         | Als Spieler möchte ich, dass es ein Einstellungen-Knopf im Hauptmenü gibt, damit ich die Musiklautstärke anpassen kann. |
| 4    |         muss        |    funktional  | Als Spieler möchte ich, dass es verschiedene Türme gibt, mit denen ich mich von Gegnern schützen kann. |
| 5    |         muss        |  funktional    | Als Spieler möchte ich, dass es mehrere Runden gibt, damit man eine höhere Herausforderung beim Spielen hat. |
| 6    |    muss             |  funktional    | Als Spieler möchte ich Geld von besiegten Gegner erhalten, damit ich reich sein kann. |
| 7    |  muss        |   funktional   | Als Spieler möchte ich, dass jedes Runde schwieriger als die vorherige Runde ist, damit man eine höhere Herausforderung hat. |
| 8    |       muss          |    funktional  | Als Entwickler möchte ich, dass jede Runde mehr Gegner erscheinen, damit der Spieler es schwerer hat zu gewinnen. |
| 9    |  muss          |   funktional   | Als Entwickler möchte ich, dass wenn man verliert, man ein Todes-Menü hat, damit man die Runde neu starten kann oder ins Hauptmenü zurückgehen kann. |
| 10   |         muss        |  funktional    | Als Spieler möchte ich, dass es ein Beenden-Knopf im Hauptmenü gibt, damit ich das Spiel schliessen kann. |
| 11   |           kann      |   rand         | Als Spieler möchte ich verschiedene Gegnertypen haben, damit meine Spielerfahrung besser ist.  |
| 12   |    kann             |   rand         | Als Entwickler möchte ich, dass verschiedene Gegnertypen unterschiedlich viel Leben abziehen, wenn sie das Ziel erreichen, damit der Spieler mehr aufpassen muss. |
| 13   |  kann               |   rand         | Als Spieler möchte ich meine Türme verbessern können, mit erlangtem Geld durch das besiegen von Gegnern, damit ich eine höhere Chance habe das Spiel zu gewinnen.  |
| 14   |  muss               |   funktional   | Als Spieler möchte ich mich frei auf der Map bewegen können, damit ich alles beobachten kann. |
| 15   |  kann               |   rand         | Als Spieler möchte ich, dass es am Anfang vom Spieler einen Timer von 30 Sekunden hat, damit ich eine gewisse Zeit habe mich für die erste Welle an Gegnern vorzubereiten. |
| 16   |  muss               |   funktional   | Als Entwickler möchte ich, dass das Spiel eine 'Hauptmap' hat, damit der Spieler sieht wo er was machen kann in einer Runde. |
| 17   |  kann               |   rand         | Als Spieler möchte ich, dass das Spiel verschiedene Maps hat, damit ich abwechslungsweise diese Maps spielen kann. |

✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc.), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). Die User Story selber hat folgende Form: *Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️*.

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Das Spiel wird gestartet| Man drückt den Startknopf | Runde wird gestartet. |
| 1.2  | Das Spiel wird gestartet| Man drückt den Beendenknopf | Spiel wird geschlossen. |
| 1.3  | Das Spiel wird gestartet| Man drückt den Optionenknopf | Das Fenster 'Optionen' wird geöffnet. |
| ...  |              |         |                   |

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme
<img![image](https://user-images.githubusercontent.com/110893121/220322745-6f710a14-7274-4404-822a-a6fa3db3cd10.png)


<img src="https://user-images.githubusercontent.com/110891995/220317206-28ad02f3-9c1a-4012-bf51-e1c00ce3ca2f.png" width="300">

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |       |           |              |               |
| ...  |       |           |              |               |

Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
