Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

Table name: Cars
- ID | INDEX | INT OR BIGINT | PK | NOTNULL | UNIQUE | AI
- Brand | VARCHAR(30) | NOTNULL
- Model | VARCHAR(20) | NOTNULL
- Version | VARCHAR(4)| NULL
- Car body | VARCHAR(3)| NOTNULL
- Fuel | VARCHAR(6) | NULL
- Year | YEAR | NULL
- Transmission | VARCHAR(2) | NOTNULL
- City | VARCHAR(112) |NOTNULL

| ID | Brand | Model | Version | Car body | Fuel | Year | Country | Transmission | City |
------------------------------------------------------------------------------------------
1     Toyota  Yaris   Urban      Urban     Hybrid 2020   Japana     Automatica     Kyoto
2
3
4
5
