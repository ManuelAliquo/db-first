# Auto in vendita

| Nome colonna  | Tipo di dato   | Attributi                  | Indice      |
| ------------- | -------------- | -------------------------- | ----------- |
| id            | BIGINT         | NOT NULL, UQ, UNSIGNED, AI | PRIMARY KEY |
| marca         | VARCHAR(20)    |                            |             |
| modello       | VARCHAR(30)    |                            |             |
| tipologia     | VARCHAR(15)    |                            |             |
| alimentazione | VARCHAR(15)    |                            |             |
| potenza_kw    | SMALLINT       |                            |             |
| consumi_km    | FLOAT(5, 1)    |                            |             |
| km_percorsi   | MEDIUMINT      |                            |             |
| prezzo_€      | DECIMAL(10, 2) |                            |             |
