# api_spec

## editing

[swagger editor](https://editor.swagger.io)

## Berechtigungen

In der `summary` einer Route direkt zu beginn in eckigen Klammern die notwendigen Berechtigungen angeben.

- `VV` bezeichnet die Rolle Vorstandsvorsitzenden.
- `SYSADMIN` meint den Systemadministrator.
- `SELF` bezeichnet den Zugriff auf _eigene_ Daten, also Daten, die dem eingeloggten User zugeordnet sind.
- `KASSIERER` und `FLUGWART` werden ausgeschrieben.
- `[]` bedeutet, dass _jeder_ die Route aufrufen darf. Wobei er dafür jedoch immernoch tendenziell _eingeloggt_ sein muss.
