---
description: Befehle, die das Grundstück betreffen.
---

# Grundstücks-Befehle

Die meisten Grundstücks-Befehle beginnen mit `/p` (Kurzform von `/plot`). Mehr Hintergrundinfos findest du im Bereich [Grundstücke](../../grundstuecke/README.md).

### Grundstücke erhalten

| Befehl     | Funktion                                                            |
| ---------- | ------------------------------------------------------------------- |
| /p auto    | Erhalte ein zufällig gewähltes freies Grundstück                    |
| /p claim   | Erhalte das freie Grundstück, auf welchem du dich aktuell befindest |
| /checkplot | Grundstück eines inaktiven Spielers beantragen                      |

### Grundstücks-Teleport

| Befehl                                                              | Funktion                                                                                                                          |
| ------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| <p>/p h &#x3C;Zahl><br>/plot home &#x3C;Zahl><br>/p h &#x3C;ID></p> | <p>Teleportiere dich zu deinem Grundstück<br></p><p>Beispiel: <code>/p h 2</code> bringt dich auf dein zweites Grundstück.</p>    |
| <p>/p h &#x3C;Spielername> &#x3C;Zahl><br>/p h &#x3C;Alias></p>     | Teleportiert dich zum Grundstück eines Mitspielers.                                                                               |
| /p middle                                                           | Teleportiere dich zur Mitte des Grundstücks                                                                                       |
| <p>/p sethome<br>/p &#x3C;ID> sethome</p>                           | Versetze den Spawnpunkt des Grundstücks an deine aktuelle Position |

### Grundstück verwalten

| Befehl                            | Funktion                                                                                                                                  |
| --------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| <p>/p i<br>/plot info</p>         | Zeigt eine Übersicht mit [Informationen und Einstellungen des Grundstücks](../../grundstuecke/hilfe-benutzen.md) an                         |
| <p>/p<br>/plot<br>/m<br>/menu</p> | [Grundstücks-Menü](../../grundstuecke/README.md) aufrufen                                                                           |
| /merge                            | [Grundstücke verbinden](../../grundstuecke/mergen.md)                                                                               |
| /p clear                          | <p>Grundstück in den Ursprungszustand versetzen <br></p><p><strong>Achtung!</strong> Bei einem Merge werden die Grundstücke getrennt!</p> |
| <p>/p delete<br>/p reset</p>      | Grundstück löschen und freigeben                                                                                                          |

### Rechte verwalten

Natürlich kannst du auch gemeinsam mit anderen an Projekten arbeiten. Dazu kannst du anderen Spielern [Rechte](../../grundstuecke/grundstucksrechte.md) zuweisen oder unerwünschten Besuch fernhalten.

| Befehl                   | Funktion                                                                                   |
| ------------------------ | ------------------------------------------------------------------------------------------ |
| /p trust \<Spielername>  | Der Spieler erhält volle Rechte auf deinem Grundstück und allem, was zum Grundstück gehört |
| /p add \<Spielername>    | Der Spieler verfügt nur über die Rechte, sofern du auf dem Citybuild online bist           |
| /p remove \<Spielername> | Du entziehst dem Spieler alle Rechte von deinem Grundstück                                 |
| /p deny \<Spielername>   | Der Spieler wird von deinem Grundstück gebannt und kann dieses nicht mehr betreten         |
| /p undeny \<Spielername> | Der Spieler darf dein Grundstück wieder betreten                                           |
| /p kick \<Spielername>   | Der Spieler wird von deinem Grundstück geworfen und kann direkt wieder drauf               |

Solltest du statt eines Spielernamens ein `*` einfügen, so gilt dieser Befehl für alle Spieler.

{% hint style="info" %}
`/p trust AbgegrieftHD` - Abge darf sich auf deinem Grundstück austoben. Sonst niemand.\
`/p trust *` - Jeder Anwesende kann auf deinem Grundstück alles machen.
{% endhint %}

{% hint style="danger" %}
Der Befehl `/p trust *` gibt Spielern Rechte **auf dem gesamten Grundstück** und ist daher nicht empfehlenswert. Damit kannst du nicht gezielt einzelne Funktionen oder Blöcke wie Kisten für alle Spieler freigeben. Wenn du beispielsweise möchtest, dass andere Spieler nur auf eine Kiste zugreifen können, nutze dafür eine use-flag.
{% endhint %}

### Weitere Grundstücks-Befehle

| Befehl                             | Funktion                                                                                                                                                                               |
| ---------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| /setowner {Spielername}            | Starte eine Überschreibung deines Grundstücks an einen anderen Spieler                                                                                                                 |
| /setowner confirm                  | Bestätige die Überschreibung eines Grundstücks                                                                                                                                         |
| /setowner deny                     | Lehne die Überschreibung eines Grundstückes ab                                                                                                                                         |
| /p description {Text}              | Füge deinem Grundstück eine Beschreibung hinzu                                                                                                                                         |
| /p description                     | Entferne die Beschreibung des Grundstücks                                                                                                                                              |
| /p alias set {Text}                | <p>Gib dem Grundstück einen Namen (Alias)<br><br><strong>Achtung!</strong> Es können keine Namen von Spielern genutzt werden, welche bereits auf dem Server angemeldet sind/waren.</p> |
| <p>/p chat on<br>/p chat off</p>   | <p>Schreibe im Grundstücks-Chat<br>Schreibe im Normalchat</p>                                                                                                                          |
| /p flag set {Flag} {true/false/ID} | [Grundstücks-Flag](../../grundstuecke/flags-setzen/README.md) setzen                                                                                                                          |
| /p setorder {Zahl}                 | Setzt das Grundstück an die ausgewählte Position deiner Grundstücksliste                                                                                                               |
| /bewertung                         | Aktiviere die Bewertungsfunktion für dein Grundstück                                                                                                                                   |
| /breakblock                        | Baut einen geschützten Block (z.B. Barrieren, Endportalrahmen, Grundgestein) auf deinem Grundstück ab. Der Block wird nach dem Anklicken abgebaut und geht verloren.                       |
