# Sicher handeln

Spieler handeln auf DeutschlandSMP über `/trade`. Das geschützte Handelsfenster unterstützt Items und Coins und ersetzt einen freien `/pay`-Befehl.

## Voraussetzungen

Du benötigst:

- mindestens **Aktivitätslevel 3**
- mindestens **zwei Tage Serverzugehörigkeit**

Diese Regeln schützen die Wirtschaft und erschweren Missbrauch durch Zweitaccounts.

## Handel starten

```text
/trade <Spielername>
```

1. Der andere Spieler erhält eine Handelsanfrage.
2. Nach der Annahme öffnet sich das Handelsmenü.
3. Beide Seiten legen Items oder Coins hinein.
4. Beide prüfen das vollständige Angebot.
5. Der Handel wird erst abgeschlossen, wenn beide Seiten bestätigen.

## Handelssteuer

Auf übertragene Coins werden **10 % Steuer** erhoben.

| Beispiel | Coins |
|---|---:|
| Eingesetzter Betrag | 100 |
| Empfänger erhält | 90 |
| Systemsteuer | 10 |

Items sind von dieser Coin-Steuer nicht betroffen.

## Warum gibt es kein `/pay`?

- Beide Seiten sehen das vollständige Angebot.
- Versehentliche Zahlungen werden vermieden.
- Betrugsversuche sind leichter zu verhindern.
- Die Steuer stabilisiert die Coin-Wirtschaft.

!!! warning "Vor dem Bestätigen prüfen"
    Kontrolliere Spielername, Items und Coin-Betrag noch einmal. Mündliche Nebenabsprachen sind nicht durch das Handelsfenster abgesichert.
