---
description: Befehle, die das Plot betreffen.
---

# Grundstücks-Befehle

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
| /p middle                                                           | Teleportiere dich zur Mitte des Grundstück                                                                                        |
| <p>/p sethome<br>/p &#x3C;ID> sethome</p>                           | [Versetze den Spawnpunkt](/broken/pages/clJipGhAUZ6BchTAWC1v#grundstueck-unerreichbar) des Grundstücks an deine aktuelle Position |

### Grundstück verwalten

| Befehl                            | Funktion                                                                                                                                  |
| --------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| <p>/p i<br>/plot info</p>         | Zeigt eine Übersicht mit [Informationen und Einstellungen des Grundstücks](/broken/pages/glnOc8evqBS6ROQarPJF) an                         |
| <p>/p<br>/plot<br>/m<br>/menu</p> | [Grundstücks-Menü](/broken/pages/M4GwYqzxyVUiO0TIsxCA) aufrufen                                                                           |
| /merge                            | [Grundstücke verbinden](/broken/pages/OQU0vAd7LLGWgzYoikP7)                                                                               |
| /p clear                          | <p>Grundstück in den Ursprungszustand versetzen <br></p><p><strong>Achtung!</strong> Bei einem Merge werden die Grundstücke getrennt!</p> |
| <p>/p delete<br>/p reset</p>      | Grundstück löschen und freigeben                                                                                                          |

### Rechte verwalten

Natürlich könnt ihr auch gemeinschaftlich an Projekten arbeiten. Dazu könnt ihr anderen Spielern Rechte zuweisen oder unerwünschten Besuch fernhalten.

| Befehl                   | Funktion                                                                                   |
| ------------------------ | ------------------------------------------------------------------------------------------ |
| /p trust \<Spielername>  | Der Spieler erhält volle Rechte auf deinem Grundstück und allem, was zum Grundstück gehört |
| /p add \<Spielername>    | Der Spieler verfügt nur über die Rechte, sofern du auf dem Citybuild online bist           |
| /p remove \<Spielername> | Du entziehst dem Spieler alle Rechte von deinem Grundstück                                 |
| /p deny \<Spielername>   | Der Spieler wird von deinem Grundstück gebannt und kann dieses nicht mehr betreten         |
| /p undeny \<Spielername> | Der Spieler darf dein Grundstück wieder betreten                                           |
| /p kick \<Spielername>   | Der Spieler wird von deinem Grundstück geworfen und kann direkt wieder drauf               |

Solltest du statt einem Spielernamen ein `*` einfügen, so gilt dieser Befehl für alle Spieler.

{% hint style="info" %}
`/p trust AbgegrieftHD` - Abge darf sich auf deinem Grundstück austoben. Sonst niemand.\
`/p trust *` - Jeder Anwesende kann auf deinem Grundstück alles machen.
{% endhint %}

{% hint style="danger" %}
Rechte für alle Spieler zu vergeben ist nicht sonderlich ratsam und nur bedingt zu empfehlen.
{% endhint %}

### Weitere Grundstücks-Befehle

| Befehl                             | Funktion                                                                                                                                                                               |
| ---------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| /setowner {Spielername}            | Starte eine Überschreibung deines Grundstücks an einen anderen Spieler                                                                                                                 |
| /setowner confirm                  | Bestätige die Überschreibung eines Grundstück                                                                                                                                          |
| /setowner deny                     | Lehne die Überschreibung eines Grundstückes ab                                                                                                                                         |
| /p description {Text}              | Füge deinem Grundstücke eine Beschreibung hinzu                                                                                                                                        |
| /p description                     | Entferne die Beschreibung des Grundstück                                                                                                                                               |
| /p alias set {Text}                | <p>Gib dem Grundstück einen Namen (Alias)<br><br><strong>Achtung!</strong> Es können keine Namen von Spielern genutzt werden, welche bereits auf dem Server angemeldet sind/waren.</p> |
| <p>/p chat on<br>/p chat off</p>   | <p>Schreibe im Grundstücks-Chat<br>Schreibe im Normalchat</p>                                                                                                                          |
| /p flag set {Flag} {true/false/ID} | [Grundstücks-Flag](/broken/pages/jJcLCBiVv00DDw9y7Sbh) setzen                                                                                                                          |
| /p setorder {Zahl}                 | Setzt das Grundstück an die ausgewählte Position deiner Grundstücksliste                                                                                                               |
| /bewertung                         | Aktiviere die Bewertungsfunktion für dein Grundstück                                                                                                                                   |
| /breakblock                        | Baut einen geschützten Block (z.B. Barrieren, Endportalrahmen, Grundgestein) auf deinem Grundstück ab. Der Block wird nach anklicken abgebaut und geht verloren.                       |

