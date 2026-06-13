# Auktionshaus

Das Auktionshaus, kurz **AH**, ermöglicht dir, Items an andere Spieler zu verkaufen und Angebote anderer Spieler zu kaufen. So kannst du unter anderem Ressourcen, Werkzeuge und seltene Items handeln und Coins verdienen.

## Auktionshaus öffnen

```text
/ah
```

Im Auktionshaus kannst du:

- aktuelle Angebote durchsuchen
- Items kaufen
- Preise vergleichen
- nach bestimmten Items suchen

## Item verkaufen

1. Nimm das Item, das du verkaufen möchtest, in die Hand.
2. Gib den gewünschten Verkaufspreis ein:

```text
/ah sell <Preis>
```

Beispiel:

```text
/ah sell 5000
```

Das gehaltene Item wird damit für **5.000 Coins** im Auktionshaus angeboten.

!!! warning "Vor dem Einstellen prüfen"
    Kontrolliere sorgfältig, ob du das richtige Item in der Hand hältst und der Preis stimmt. Falsch eingestellte Angebote können nicht immer rückgängig gemacht werden.

## Verkaufsgebühr

Auf den Verkauf von Items fallen **10 %** an. Berücksichtige das bei der Wahl deines Verkaufspreises.

## Item kaufen

1. Öffne das Auktionshaus mit `/ah`.
2. Suche das gewünschte Item.
3. Klicke auf das Angebot.
4. Bestätige den Kauf.

Nach dem Kauf erhältst du das Item direkt in dein Inventar.

## Eigene Angebote verwalten

```text
/ah listings
```

Dort siehst du:

- deine laufenden Verkäufe
- die Verkaufspreise
- die verbleibende Laufzeit

Möchtest du ein Angebot zurückziehen, öffne `/ah listings` und entferne es über das Menü. Das Item wird anschließend an dich zurückgegeben.

## Tipps für Verkäufe

### Preise vergleichen

Prüfe vor dem Einstellen ähnliche Angebote. Ist dein Preis deutlich höher, wird das Item möglicherweise nicht verkauft.

### Nachfrage beachten

Laut Guide werden unter anderem folgende Itemgruppen häufig angeboten:

- Ressourcen
- Werkzeuge
- verzauberte Gegenstände
- Farmbox-Items
- seltene Drops

### Angebote kontrollieren

Überprüfe deine Listings regelmäßig und passe den Preis bei Bedarf an.

## Häufige Probleme

### Ich kann nichts verkaufen

Mögliche Gründe:

- Du hältst kein Item in der Hand.
- Der eingegebene Preis ist ungültig.
- Du hast dein Angebotslimit erreicht.

### Mein Item wurde nicht verkauft

Möglicherweise ist der Preis zu hoch, es gibt günstigere Angebote oder die Nachfrage ist derzeit gering.

### Kann ich Coins direkt versenden?

Nein. Für direkte Coin- und Item-Transaktionen zwischen Spielern nutzt du das sichere Handelssystem:

```text
/trade <Spielername>
```

[Mehr zum Spielerhandel](trade.md)

## Befehle

| Befehl | Funktion |
|---|---|
| `/ah` | Öffnet das Auktionshaus. |
| `/ah sell <Preis>` | Bietet das Item in deiner Hand zum angegebenen Preis an. |
| `/ah listings` | Zeigt und verwaltet deine eigenen Angebote. |
