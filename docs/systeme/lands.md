# Lands und Grundstücksschutz

Mit Lands schützt du dein Grundstück. In deinen geclaimten Chunks können andere Spieler nur dann bauen, Blöcke abbauen oder Kisten öffnen, wenn du ihnen die entsprechenden Rechte gibst.

## Dein erstes Land

### 1. Land erstellen

```text
/lands create <Name>
```

Alternativ kannst du direkt `/lands claim` verwenden. Falls du noch kein Land besitzt, wird dabei automatisch eines erstellt.

### 2. Chunk claimen

Stelle dich in den Chunk, den du schützen möchtest:

```text
/lands claim
```

!!! warning "Zusammenhängendes Gebiet"
    Neue Claims müssen an dein bestehendes Land angrenzen. Prüfe die Aufteilung mit `/lands map`.

### 3. Schutz kontrollieren

```text
/lands map
/lands view
/lands info
```

`/lands map` zeigt Claims in deiner Umgebung, `/lands view` blendet Grenzen ein und `/lands info` erklärt das Gebiet, in dem du stehst.

## Mehrere Chunks claimen

```text
/lands claim radius <Anzahl>
```

Beispiel:

```text
/lands claim radius 2
```

Mit `/lands claim auto` wird jeder passende Chunk beim Betreten automatisch geclaimt. Führe den Befehl erneut aus, um den Modus zu beenden.

## Mit Freunden bauen

| Befehl | Wirkung |
|---|---|
| `/lands trust <Spieler>` | Gibt einem Spieler Rechte in deinem Land. |
| `/lands untrust <Spieler>` | Entzieht diese Rechte wieder. |
| `/lands ban <Spieler>` | Verhindert das Betreten deines Landes. |
| `/lands unban <Spieler>` | Hebt den Land-Bann auf. |

!!! tip "Rechte bewusst vergeben"
    Vertraue nur Spielern, die in deinem Gebiet wirklich bauen oder Container benutzen dürfen.

## Land-Bank

```text
/lands deposit <Betrag>
/lands balance
```

`/lands deposit` zahlt Coins in die Land-Bank ein. Den Kontostand siehst du mit `/lands balance` oder auf dem Scoreboard.

!!! warning "Auszahlung deaktiviert"
    `/lands withdraw <Betrag>` ist laut aktuellem Guide wegen technischer Fehler deaktiviert.

## Land-Spawn

```text
/lands setspawn
/lands spawn
```

Damit setzt du den Treffpunkt deines Landes und teleportierst dich später dorthin.

## Verwaltung

| Befehl | Funktion |
|---|---|
| `/lands` | Öffnet das Hauptmenü. |
| `/lands rename <Name>` | Benennt dein Land um. |
| `/lands unclaim` | Gibt den aktuellen Chunk frei. |
| `/lands delete` | Löscht dein Land dauerhaft. |
| `/lands help` | Zeigt weitere Lands-Befehle. |

!!! danger "Löschen ist dauerhaft"
    Prüfe vor `/lands delete`, ob du wirklich das richtige Land ausgewählt hast.
