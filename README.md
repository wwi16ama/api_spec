# api_spec

## editing

[swagger editor](https://editor.swagger.io)

## Berechtigungen

In der `summary` einer Route direkt zu Beginn stehen in eckigen Klammern die notwendigen Berechtigungen angeben. 
Die Route `/loginCheck` gibt nun die Rollen und den Status eines Members zurück.
Hierbei werden folgende Rollen und Status zurückgegeben: 

`VORSTANDSVORSITZENDER, SYSTEMADMINISTRATOR, KASSIERER, FLUGWART, ACTIVE, PASSIVE`

Rollen:
- `VV` bezeichnet die Rolle `VORSTANDSVORSITZENDER`.
- `SYSADMIN` meint die Rolle `SYSTEMADMINISTRATOR`.
- `KASSIERER` und `FLUGWART` werden ausgeschrieben.

Status:
- Ein Member kann `ACTIVE` oder `PASSIVE` sein.

Weitere Zugriffe:
- `SELF` bezeichnet den Zugriff auf _eigene_ Daten, also Daten, die dem eingeloggten User zugeordnet sind.
- `[]` bedeutet, dass _jeder_ die Route aufrufen darf. Wobei er dafür jedoch immernoch tendenziell _eingeloggt_ sein muss.

Des Weiteren werden Berechtigungen wie in der [Berechtigungs HTML](https://github.com/wwi16ama/api_spec/blob/master/Berechtigungskonzept.html) vergeben. 
