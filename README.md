# Tiefgang

Endloses Tiefsee-Spiel im Browser. Du bist eine kleine Leuchtqualle und tauchst immer tiefer. Es gibt kein Ende, dafür ständig etwas Neues: Zonen, Kreaturen, Bosse, Ereignisse, Erfolge und Skins.

**▶ [Jetzt spielen](https://arcticstorm243.github.io/Tiefgang/)** – läuft direkt im Browser, auch auf dem Handy.

Offline: `index.html` herunterladen und im Browser öffnen.

🇬🇧 **English:** The game is fully available in English. Switch the language with the **🌐 English / 🌐 Deutsch** button at the bottom of the main menu. On first launch the game picks the language of your browser.

---

## Inhalt

- [Sprache](#sprache)
- [Steuerung](#steuerung)
- [Tutorial](#tutorial)
- [So funktioniert das Spiel](#so-funktioniert-das-spiel)
- [Zonen](#zonen)
- [Kreaturen](#kreaturen)
- [Bosse](#bosse)
- [Ereignisse](#ereignisse)
- [Mutationen](#mutationen)
- [Erfolge und Skins](#erfolge-und-skins)
- [Perlen, Luckybox und Mergen](#perlen-luckybox-und-mergen)
- [Arctic-Skin und Codes](#arctic-skin-und-codes)
- [Logbuch](#logbuch)
- [Speicherstand](#speicherstand)
- [Technik](#technik)

---

## Sprache

Das Spiel gibt es komplett auf **Deutsch** und **Englisch**: Menüs, HUD, Tutorial, Logbuch, Erfolge, Skins, Mutationen und alle Meldungen.

- Umschalten über den Knopf **🌐 English** bzw. **🌐 Deutsch** unten im Hauptmenü. Die Seite lädt dabei kurz neu.
- Beim ersten Start wählt das Spiel automatisch die Sprache deines Browsers. Deutsch gilt für alle deutschsprachigen Browser, sonst Englisch.
- Der Fortschritt bleibt beim Wechsel vollständig erhalten. Logbuch und Bosse werden intern sprachunabhängig gespeichert.

---

## Steuerung

| Aktion | Standard | Änderbar |
|---|---|---|
| Schwimmen | Maus bewegen / Finger ziehen | – |
| Nach oben / unten / links / rechts | W A S D oder Pfeiltasten | ✔ |
| Sprint (kurz unverwundbar) | Leertaste oder Shift links, Rechtsklick, Doppeltipp | ✔ (Tasten) |
| Pause | P oder Esc | ✔ |
| Tauchgang beenden | Pausemenü → **Tauchgang beenden**, zur Sicherheit zweimal klicken. Der Run zählt normal (Rekord, Statistik, Erfolge) und du siehst die Zusammenfassung. Im Tutorial geht es zurück ins Hauptmenü. | – |
| Ton an/aus | M | ✔ |
| Mutation wählen | 1 / 2 / 3 (mit Mutantenkönigin auch 4) oder Klick | – |
| Spiel starten | Enter | – |

### Tasten ändern

Die Tasten änderst du im **Hauptmenü → Steuerung** oder im **Pausemenü → Steuerung**.

1. Klick auf das Tastenfeld einer Aktion. Jede Aktion hat zwei Felder.
2. Drück die neue Taste.
3. **Esc** bricht ab, **Entf** oder **Rücktaste** löscht die Belegung.

Wenn eine Taste schon einer anderen Aktion zugewiesen ist, wird sie dort automatisch entfernt. **1, 2, 3** und **Enter** sind fest belegt. Mit **Standard wiederherstellen** setzt du alles zurück. Die Hinweise im Menü und im Tutorial zeigen immer deine aktuelle Belegung.

---

## Tutorial

Beim allerersten Start fragt das Spiel, ob du ein kurzes Tutorial willst. Es dauert etwa eine Minute. Du kannst es jederzeit über **Tutorial überspringen** abbrechen oder später im Hauptmenü unter **Tutorial** erneut starten.

| Schritt | Du lernst |
|---|---|
| 1. Schwimmen | Maus, Finger oder Tastatur |
| 2. Sprint | Sprint auslösen, Abklingzeit (violetter Balken) |
| 3. Lichtpuls | Automatischer Angriff, vier Treiblinge besiegen |
| 4. Plankton | Erfahrung einsammeln |
| 5. Mutationen | Stufenaufstieg und Upgrade wählen |
| 6. Ab in die Tiefe | Zonen, Logbuch, Erfolge und Skins |

Im Tutorial sinkst du nicht, es spawnen keine Gegner von selbst, und du kannst nicht sterben. Wer es abschliesst, erhält den Erfolg **Gut vorbereitet** und den Skin **Perle**.

---

## So funktioniert das Spiel

- Du **sinkst automatisch** (2 m pro Sekunde). Die Tiefe ist dein Punktestand.
- Dein **Lichtpuls** feuert automatisch und trifft alles im Umkreis. Du musst nur schwimmen, ausweichen und sammeln.
- Besiegte Gegner lassen **Plankton** fallen. Plankton füllt den Balken unten. Ist er voll, wählst du eine **Mutation**.
- Gegner werden mit der Tiefe **zäher, schneller und zahlreicher**.
- **Elite-Gegner** mit Goldring haben dreifaches Leben und geben mehr Erfahrung.
- Pfeile am Bildschirmrand zeigen, wo Bosse und Goldquallen sind.

**HUD:**

| Wo | Was |
|---|---|
| Oben links | Tiefe, aktuelle Zone und **Fortschritt zur nächsten Zone** („Noch 83 m bis Dämmerzone“, unentdeckte Zonen erscheinen als ???). Der Balken leuchtet auf, wenn weniger als 25 m fehlen. |
| Darunter | Leben (weiss) und Sprint (violett) mit Text „Sprint in 1.4 s“ bzw. „Sprint bereit“ |
| Um die Qualle | Ein **violetter Ring** füllt sich, während der Sprint auflädt. Ist er bereit, blitzt der Ring kurz auf und es gibt einen Ton. Mit dem Skin *Kristall* ab ★2 zeigt ein cyanfarbener Ring den bereiten Schild. |
| Oben rechts | Stufe, Besiegte, Rekord und **Perlen** |
| Unten | Erfahrungsbalken |

---

## Zonen

| Zone | Ab | Stimmung |
|---|---|---|
| Lichtzone | 0 m | Sonnenstrahlen, ruhiger Anfang |
| Dämmerzone | 150 m | Das letzte Tageslicht verblasst |
| Mitternachtszone | 400 m | Ewige Nacht, nur Biolumineszenz |
| Abyssal | 800 m | Eisige Kälte, seltsame Farben |
| Hadal | 1400 m | Heisse Quellen, tiefste Gräben |
| Prozedurale Zonen | ab 2200 m, alle 700 m | Kristallgraben, Echoschlund, Glimmerriff, Stille Weite, Nebelschlot, Sternenkluft, Rauschgrund, Aschemeer. Danach geht es mit nummerierten Varianten endlos weiter. |

Jede Zone hat eigene Hintergrund- und Leuchtfarben. Bei jedem Zonenwechsel erscheint ein Boss.

---

## Kreaturen

| Kreatur | Ab | Verhalten |
|---|---|---|
| Treibling | 0 m | Treibt langsam auf dich zu |
| Pfeilfisch | 60 m | Lauert und schiesst dann blitzschnell los |
| Kugelfisch | 200 m | Platzt beim Tod und verschiesst 8 Stacheln |
| Anglerfisch | 450 m | Zäh und träge, mit leuchtendem Köder |
| Schattenaal | 700 m | Schnell, schlängelt sich unberechenbar |
| Tintenkalmar | 1000 m | Hält Abstand und spuckt Tinte |
| Glasgeist | 1500 m | Wird regelmässig unsichtbar und unverwundbar |
| Glutkrabbe | 2000 m | Sehr zäh, zerfällt in zwei kleine Krabben |
| Leuchtgarnele | 120 m | Kommt immer zu viert im Schwarm und zappelt wild umher |
| Nesselqualle | 300 m | Lädt sich auf, wenn du nah bist (pinker Ring), und entlädt dann einen brennenden Ring |
| Nautilus | 600 m | Langsam, der Panzer halbiert jeden Schaden |
| Tarnkrake | 1200 m | Fast unsichtbar (nur zwei Augen im Dunkeln), schnellt aus der Nähe plötzlich hervor |
| Seeigel | 1700 m | Kriecht langsam und schiesst alle 3 s Stacheln in 8 Richtungen |
| Schleimaal | 2500 m | Hinterlässt beim Tod eine Schleimpfütze, die dich 45 % langsamer macht |
| Geisterhai | 3000 m | Kreist um dich und stösst dann mit voller Wucht zu |

Im Logbuch hat jede Kreatur und jeder Boss ein **Bild**. Es wird mit derselben Grafik wie im Spiel gezeichnet. Unentdeckte Einträge zeigen nur eine dunkle Silhouette.

---

## Bosse

Die Bosse wechseln sich bei jedem Zonenwechsel der Reihe nach ab. Wer einen Boss besiegt, erhält viel Erfahrung und wird zu 30 % geheilt.

| Boss | Erstmals | Angriff |
|---|---|---|
| Mutterqualle | Dämmerzone | Ruft ständig Treiblinge herbei |
| Riesenkalmar | Mitternachtszone | Feuert Tintenringe in alle Richtungen |
| Leviathan | Abyssal | Zielt (Leuchtstreifen), dann rammt er |

---

## Ereignisse

Alle 30 bis 50 Sekunden passiert zufällig etwas.

| Ereignis | Ab | Effekt |
|---|---|---|
| Planktonblüte | 0 m | 80 Plankton rund um dich |
| Starke Strömung | 0 m | 12 s lang treibt alles in eine Richtung |
| Fischschwarm | 40 m | Ein Schwarm zieht vorbei, jeder Fisch gibt Erfahrung |
| Angriffswelle | 80 m | Gegner kommen von allen Seiten gleichzeitig |
| Goldqualle | 100 m | Eine flüchtende Goldqualle, fang sie für eine **doppelte** Mutation |
| Fressrausch | 150 m | 12 s lang sind Gegner schneller, dafür gibt es doppelte Erfahrung |
| Schwarzes Wasser | 300 m | 14 s lang siehst du nur dein eigenes Licht |
| Luftblasen | 0 m | 14 aufsteigende Blasen, jede heilt 12 Leben |
| Stille | 0 m | 10 s lang keine neuen Gegner und +4 Leben pro Sekunde |
| Sog der Tiefe | 0 m | 12 s lang dreifache Anziehung für Plankton und Perlen |
| Elite-Patrouille | 200 m | Drei Elite-Gegner mit Goldring tauchen auf |
| Perlenregen | 350 m | Eine Perle erscheint in deiner Nähe |
| Hydrothermale Schlote | 1000 m | 16 s lang brechen um dich 5 Schlote aus. Sie glühen vorher auf, weich ihnen aus. |
| Tiefenbeben | 1400 m | 12 s lang fallen Felsbrocken. Rote Kreise mit Schatten zeigen den Einschlag. Die Felsen treffen auch Gegner. |
| Tiefenriss | 2200 m | 6 Elite-Versionen der tiefsten Kreaturen strömen heraus |

---

## Mutationen

Bei jedem Stufenaufstieg wählst du eine von drei zufälligen Mutationen.

| Mutation | Effekt | Max. |
|---|---|---|
| Stärkerer Puls | +30 % Schaden für alle Angriffe | ∞ |
| Weiter Puls | +18 % Pulsreichweite | 8 |
| Schneller Puls | Puls 15 % häufiger | 8 |
| Flossenschlag | +12 % Tempo | 6 |
| Anziehung | Plankton aus 50 % grösserer Distanz | 6 |
| Dicke Glocke | +25 max. Leben, 40 Heilung | 10 |
| Selbstheilung | +1 Leben pro Sekunde | 6 |
| Leuchtfunke | Kreisender Funke, der Gegner verbrennt | 8 |
| Sporenwerfer | Zielsuchende Sporen | 6 |
| Zitteraal | Kettenblitz zwischen Gegnern | 6 |
| Rückstoss | Sprint 20 % schneller bereit | 5 |

---

## Erfolge und Skins

Erfolge werden automatisch freigeschaltet. Die meisten geben einen neuen **Skin** für deine Qualle. Skins gibt es ausserdem aus der [Luckybox](#perlen-luckybox-und-mergen). Skins wählst du unter **Logbuch & Skins → Skins**. Sie ändern Körper, Leuchten und Pulsfarbe, einige haben Spezialeffekte.

| Erfolg | Bedingung | Skin |
|---|---|---|
| Erster Tauchgang | Ersten Tauchgang beenden | – |
| Gut vorbereitet | Tutorial abschliessen | Perle |
| Dämmerung | 150 m erreichen | Dämmerlicht |
| Mitternacht | 400 m erreichen | Mitternacht |
| Abgrund | 800 m erreichen | Tiefseerose |
| Hadal | 1400 m erreichen | Glut |
| Ins Unbekannte | 2200 m erreichen | Polarlicht (Farbwechsel) |
| Lichtbringer | 100 Gegner in einem Tauchgang | Minze |
| Tausend Funken | Insgesamt 1000 Gegner | Glasgeist (durchsichtig) |
| Riesentöter | Einen Boss besiegen | Schattenqualle |
| Alle drei Riesen | Jeden Boss einmal besiegen | Sonnenfunke |
| Goldfinger | Eine Goldqualle fangen | Goldqualle (funkelt) |
| Mutant | Stufe 10 in einem Tauchgang | Giftgrün |
| Unberührbar | 3 Minuten am Stück ohne Treffer | Kristall (funkelt) |
| Funkenkranz | 8 Leuchtfunken gleichzeitig | – |
| Glückspilz | Erste Luckybox öffnen | – |
| Verschmolzen | Einen Skin auf ★2 mergen | – |
| Meisterform | Einen Skin auf ★3 mergen | – |
| Sensenmann, Tiefenwanderer, Titanenfall, Kopfgeldjagd, Perlenfischer, Veteran, Ewigkeit, Hochmutiert, Herz des Abgrunds | siehe [Meilenstein-Skins](#meilenstein-skins) | je ein Meilenstein-Skin |
| Stammgast | 10 Tauchgänge | – |
| Forschungsdrang | Logbuch zur Hälfte gefüllt | Sternenstaub (funkelt) |
| Vollständiges Logbuch | Alles entdeckt | Prisma (Regenbogen) |

Dazu kommt der Start-Skin **Klassisch**, insgesamt also 30 Skins (16 aus Erfolgen und Box, 4 weitere Box-Skins, 9 Meilenstein-Skins, 1 Arctic-Skin).

---

## Perlen, Luckybox und Mergen

### Perlen

Perlen sind rosa leuchtende Sammelobjekte. Sie bleiben liegen, bis du sie einsammelst, und werden **dauerhaft** gespeichert.

| Quelle | Chance |
|---|---|
| Normaler Gegner | 0,25 % (Leuchtgarnelen und kleine Krabben lassen keine fallen) |
| Elite-Gegner (Goldring) | 3,5 % |
| Boss | 1 Perle garantiert |
| Planktonblüte | 25 % auf eine Perle |
| Perlenregen | 1 Perle |

Im Schnitt reicht das für etwa eine Luckybox pro 5-Minuten-Tauchgang.

Im Tutorial fallen keine Perlen.

### Luckybox

Für **5 Perlen** öffnest du eine Luckybox und bekommst einen zufälligen Skin. Die Box findest du im **Hauptmenü** und **nach einem Tauchgang**. Der Knopf zeigt an, wie viele Boxen du öffnen kannst. Spektakuläre Skins sind seltener:

| Seltenheit | Chance gesamt | Skins |
|---|---|---|
| Gewöhnlich | 56,0 % | Klassisch, Perle, Dämmerlicht, Minze, Tiefseerose |
| Selten | 23,9 % | Mitternacht, Glut, Giftgrün, Sonnenfunke |
| Episch | 11,9 % | Glasgeist, Schattenqualle, Kristall, Sternenstaub |
| Legendär | 6,0 % | Goldqualle, Polarlicht, Nebelschleier, Donnerqualle |
| Mythisch | 2,2 % | Prisma, Leere, Phönix |

Meilenstein-Skins sind **nicht** in der Box, siehe [unten](#meilenstein-skins).

Beim Öffnen läuft eine **Rolle** mit Skins durch, bremst ab und bleibt unter der goldenen Markierung auf deinem Gewinn stehen. Mit **Überspringen** siehst du das Ergebnis sofort. Verlässt du die Box während der Drehung, bekommst du den Skin trotzdem.

Ist der Skin neu, wird er freigeschaltet. Hast du ihn schon, egal ob aus einer Box oder durch einen Erfolg, bekommst du ein **Duplikat**.

### Mergen und Spezialfähigkeiten

Unter **Logbuch & Skins → Skins** mergst du Duplikate:

| Stufe | Kosten | Wirkung |
|---|---|---|
| ★1 | – | Skin freigeschaltet, nur Aussehen |
| ★2 | 3× ★1 (dein Skin + 2 Duplikate) | Spezialfähigkeit aktiv |
| ★3 | 3× ★2 (9 Kopien insgesamt, also 6 weitere Duplikate ab ★2) | Spezialfähigkeit verstärkt |

Der Merge-Knopf zeigt den Fortschritt in Kopien an, z. B. „Mergen zu ★3 (5/9 Kopien)“. Skins, die schon nach den alten Regeln gemergt wurden, behalten ihre Sterne.

Die Fähigkeit wirkt nur, solange du den Skin **trägst**. Dein aktueller Skin und seine Fähigkeit stehen im Hauptmenü.

| Skin | Fähigkeit | ★2 | ★3 |
|---|---|---|---|
| Klassisch | Robust | +15 max. Leben | +30 max. Leben |
| Perle | Perlenglück | +50 % Perlenchance | +100 % Perlenchance |
| Dämmerlicht | Stromlinie | +8 % Tempo | +16 % Tempo |
| Minze | Frische | +0,7 Leben/s | +1,4 Leben/s |
| Tiefseerose | Dornen | Angreifer bekommen Pulsschaden zurück | doppelter Pulsschaden |
| Mitternacht | Weites Licht | +10 % Pulsreichweite | +20 % |
| Glut | Glutpuls | +12 % Schaden | +24 % |
| Giftgrün | Giftsporen | Start mit 1 Sporenwerfer | Start mit 2 |
| Sonnenfunke | Sonnenkranz | Start mit 1 Leuchtfunken | Start mit 2 |
| Glasgeist | Phasensprung | Sprint 18 % schneller bereit | 36 % |
| Schattenqualle | Schattenblitz | Start mit Zitteraal | Zitteraal Stufe 2 |
| Kristall | Kristallschild | Schild blockt alle 20 s einen Treffer | alle 12 s |
| Sternenstaub | Sternensog | +40 % Anziehung | +80 % |
| Goldqualle | Goldrausch | +25 % Erfahrung | +50 % |
| Polarlicht | Polarwind | Puls 10 % häufiger | 20 % |
| Prisma | Prismakraft | +10 % Schaden, +5 % Tempo, +10 % Erfahrung | doppelt so stark |
| Nebelschleier | Nebelhülle | 10 % Chance, Treffern auszuweichen | 20 % |
| Donnerqualle | Gewitter | Zitteraal +1 Ziel, 25 % häufiger | +2 Ziele, 50 % häufiger |
| Leere | Ereignishorizont | Gegner in Pulsreichweite 25 % langsamer, +10 % Schaden | 40 % langsamer, +20 % Schaden |
| Phönix | Wiedergeburt | Einmal pro Tauchgang Wiederbelebung mit 40 % Leben und Feuerwelle | 70 % Leben, doppelte Feuerwelle |

### Zusammenspiel mit Mutationen

Skin-Fähigkeiten werden durch Mutationen **mit verbessert**:

| Mutation | Verbessert bei Skins |
|---|---|
| Stärkerer Puls | Schaden von Eiszapfen, Dornen und Phönix-Feuerwelle. Prozent-Boni wie Glutpuls oder Vollstrecker multiplizieren sich mit dem Pulsschaden, sie addieren sich also nicht bloss. |
| Weiter Puls | Reichweite von Permafrost, Eiszapfen, Ereignishorizont und Phönix-Feuerwelle |
| Schneller Puls | Permafrost und Eiszapfen kommen häufiger |
| Sporenwerfer | Arktisqualle: pro Stufe ein Eiszapfen mehr pro Salve |
| Zitteraal | Donnerqualle und Schattenqualle: zusätzliche Blitzziele |
| Rückstoss | Kristallschild lädt schneller, Phasensprung stapelt sich damit |
| Anziehung | Perlensog der Perlentaucherin reicht weiter |
| Leuchtfunke | Sonnenkranz: zählt zu den Start-Funken dazu |

### Meilenstein-Skins

Diese Skins bekommst du nur durch Spielen. Ihre Fähigkeit ist **sofort aktiv**. Sie sind nicht in der Luckybox und können nicht gemergt werden. Der Fortschritt wird über alle Tauchgänge gezählt, ausser dort, wo „in einem Tauchgang“ steht.

| Skin | Erfolg | Bedingung | Fähigkeit |
|---|---|---|---|
| Sensenqualle | Sensenmann | 10 000 Gegner insgesamt | +20 % Schaden, normale Gegner unter 15 % Leben sterben sofort |
| Tiefenwanderer | Tiefenwanderer | 50 000 m insgesamt | 20 % weniger erlittener Schaden |
| Titanenqualle | Titanenfall | 25 Bosse insgesamt | +60 % Schaden gegen Bosse |
| Kopfgeldjägerin | Kopfgeldjagd | 250 Elite-Gegner insgesamt | Elites nehmen +50 % Schaden, doppelte Perlenchance bei Elites |
| Perlentaucherin | Perlenfischer | 100 Perlen gesammelt | Perlen fliegen aus grosser Distanz zu, +25 % Perlenchance |
| Veteranin | Veteran | 100 Tauchgänge | Start mit «Stärkerer Puls» und «Schneller Puls» |
| Ewige Qualle | Ewigkeit | 30 Minuten in einem Tauchgang | +2 % Schaden pro Minute, max. +60 % |
| Mutantenkönigin | Hochmutiert | Stufe 30 in einem Tauchgang | 4 statt 3 Mutationen pro Level-up |
| Abgrundherz | Herz des Abgrunds | 5000 m erreichen | +1 % Schaden pro 100 m Tiefe, max. +50 % |

---

## Arctic-Skin und Codes

**Arctic** ist die seltenste Stufe. Es gibt genau einen Skin darin, die **Arktisqualle**. Sie ist weder in der Luckybox noch über Erfolge zu bekommen, sondern **nur mit einem geheimen Code**.

**So löst du einen Code ein:** Hauptmenü → **Code einlösen** → Code eingeben → **Einlösen** oder Enter. Gross- und Kleinschreibung zählt. Der Skin wird sofort angelegt.

| | Arktisqualle |
|---|---|
| Stufe | Sofort **★3**, kein Mergen nötig |
| Permafrost | Alle 6 s friert eine Eiswelle alle Gegner in 1,4-facher Pulsreichweite **2 s lang ein**. Eingefrorene Gegner bewegen sich nicht, verursachen keinen Berührungsschaden und nehmen +25 % Schaden. Bosse werden stattdessen 2,5 s lang um 50 % verlangsamt. |
| Eiszapfen | Von Anfang an schiesst sie alle 0,8 s bis zu 3 Eiszapfen auf die nächsten Gegner. Jeder durchbohrt bis zu 3 Gegner und friert mit 30 % Chance 1,2 s ein. |

Einfrieren und Eiszapfen sind **exklusiv**. Keine andere Qualle hat sie, und sie kommen nie als Mutation.

Der Code steht nicht im Quelltext. Das Spiel speichert nur seinen SHA-256-Hash und vergleicht die Eingabe damit.

---

## Logbuch

Das Logbuch öffnest du im Hauptmenü, im Pausemenü oder nach einem Tauchgang. Es hat sechs Reiter:

| Reiter | Inhalt |
|---|---|
| Kreaturen | Alle 15 Kreaturen mit Bild und Beschreibung |
| Zonen | 5 feste und 8 prozedurale Zonen |
| Bosse | Alle 3 Bosse mit Bild, inklusive ob schon besiegt |
| Ereignisse | Alle 15 Ereignisse |
| Erfolge | Alle 30 Erfolge mit Bedingung und Belohnung |
| Skins | Alle Skins mit Seltenheit, Box-Chance, Sternen, Fähigkeit, Tragen und Mergen |

Unentdeckte Einträge erscheinen als **???** mit einem Hinweis, wo man sie findet, zum Beispiel „Taucht ab 450 m auf“. Neue Einträge meldet das Spiel während des Tauchgangs mit „Neu im Logbuch“. Insgesamt gibt es 46 Einträge (13 Zonen, 15 Kreaturen, 3 Bosse, 15 Ereignisse).

---

## Speicherstand

Alles wird lokal im Browser gespeichert (`localStorage`):
Rekordtiefe, Logbuch, Erfolge, Sprache, eingelöste Codes, Perlen, Skin-Inventar (Sterne und Duplikate), gewählter Skin, Tastenbelegung, Ton-Einstellung, Lebenszeit-Statistik (Tauchgänge, besiegte Gegner, Bosse, Goldquallen) und ob das Tutorial schon angeboten wurde.

Der Fortschritt gilt pro Browser und Gerät. Wer die Browserdaten löscht, setzt alles zurück.

---

## Technik

- Eine einzige Datei `index.html` mit HTML, CSS und JavaScript, ohne Frameworks und ohne Build.
- Grafik über das Canvas 2D mit additivem Leuchten (vorgerenderte Glow-Sprites).
- Sound entsteht live über die Web Audio API, es gibt keine Audiodateien.
- Die Schrift „Bricolage Grotesque“ kommt von Google Fonts, offline greift eine Systemschrift.
- Das Spiel respektiert `prefers-reduced-motion` (keine Bildschirmerschütterung).
- Hosting über GitHub Pages aus dem `main`-Branch.
